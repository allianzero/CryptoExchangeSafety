# CryptoExchangeSafety

A guide to using crypto exchanges safely: choosing an exchange, securing your account, depositing and withdrawing correctly, and understanding what happens if an exchange fails. Exchanges are convenient — and they are also where some of the largest crypto losses in history have happened, through hacks, fraud, and bankruptcy.

> This guide is educational only, not financial or legal advice. No exchange is risk-free, and "regulated" does not mean "your funds are guaranteed".

## 1. What an exchange does — and what it does not do

A centralised exchange (CEX) is a company that:

- Holds your funds in wallets it controls (custody).
- Matches buyers and sellers on its own order books.
- Provides fiat on-ramps (bank transfers, cards) and off-ramps.
- Often offers additional services: staking, lending, derivatives, and cards.

What an exchange does **not** do, unless it explicitly guarantees it (and even then, read the terms):

- Guarantee your funds against its own failure, hack, or fraud.
- Segregate your funds from its own operating funds (some do, some do not, and practices vary by jurisdiction).
- Provide deposit insurance equivalent to a bank's. Some jurisdictions offer limited protections; most crypto deposits have none.
- Reverse a withdrawal you sent to the wrong address or network.

**The core trade-off:** exchanges are convenient and beginner-friendly, but you trade self-custody for counterparty risk. "Not your keys, not your coins" is not a slogan — it is a description of who controls your funds on an exchange.

## 2. Choosing an exchange: a checklist

Before depositing meaningful funds, check:

- [ ] **Reputation and history:** how long has it operated, through which market cycles, and has it survived crashes, hacks, or regulatory actions transparently?
- [ ] **Regulation and jurisdiction:** is it licensed or registered where it operates, and what does that actually protect? Regulation varies enormously — a licence in one country may offer little protection in yours.
- [ ] **Proof of reserves and audits:** does it publish proof of reserves (cryptographic evidence that it holds customer assets), audited financials, or third-party attestations? Proof of reserves is a snapshot, not a guarantee, and it does not prove liabilities — but its absence is a warning sign.
- [ ] **Security history:** has it been hacked? How did it respond — transparently, with customer compensation, or with silence? Past incident handling predicts future incident handling.
- [ ] **Insurance:** does it hold insurance for hot wallet hacks or crime? What exactly is covered, up to what limit, and what is excluded? Read the policy summary, not the marketing.
- [ ] **Liquidity and volume:** real trading volume (not wash-traded volume) means your orders fill at fair prices. Obscure exchanges with thin books give worse prices and are easier to manipulate.
- [ ] **Supported assets, networks, and fiat methods:** does it support the assets and withdrawal networks you actually need, through fiat methods available in your country?
- [ ] **Fee schedule:** trading, deposit, withdrawal, and conversion fees, stated clearly. Hidden spreads (a worse price than the market price, disguised as "no fee") are still fees.
- [ ] **Customer support quality:** test it with a small question before you need it urgently. Support that is unreachable during normal times will be unreachable during a crisis.
- [ ] **Withdrawal policies:** withdrawal limits, processing times, whitelisting options, and any history of withdrawal pauses. An exchange that frequently pauses withdrawals is signalling liquidity or security problems.

If an exchange fails several of these checks, do not use it for meaningful funds, however attractive its fees or promotions look.

## 3. Securing your exchange account

Your exchange account is only as safe as your email account, because email can reset almost everything. Secure both, in this order:

1. **Email first:** unique, long password, authenticator-app or security-key 2FA, and recovery options you control. If your email is compromised, your exchange account is next.
2. **Exchange password:** unique, long, stored in a password manager. Never reused anywhere else.
3. **2FA:** authenticator app or security key, not SMS alone (SIM-swap attacks can defeat SMS 2FA). Save 2FA backup codes on paper, offline.
4. **Withdrawal whitelist:** if the exchange supports it, whitelist only your own wallet addresses, with a time delay for adding new addresses. A hacker who compromises your account then cannot immediately withdraw to their own address.
5. **Anti-phishing code:** if the exchange supports it, set a personal code that appears in genuine exchange emails. Emails without your code are phishing, however official they look.
6. **Login alerts and device management:** turn on login and withdrawal notifications, and regularly review logged-in devices and sessions, removing ones you do not recognise.
7. **API keys (if you use them):** trading-only permissions, withdrawals disabled, IP restrictions where supported, and keys stored securely — never in code, chat messages, or public repositories.

## 4. Phishing: the exchange-specific version

Exchange phishing is the most common exchange-related loss for individuals:

- **Fake login pages:** identical to the real exchange, reached from links in emails, posts, DMs, or search ads. You log in; the attacker captures your credentials and drains your account, often within minutes.
- **Fake support:** "support" DMs you first, offering to unlock an account or fix a deposit. Real support never DMs first and never asks for your password, 2FA codes, or remote access.
- **Fake deposit addresses:** a phishing site or a compromised account shows you a deposit address controlled by the attacker. Funds sent there are gone.
- **Fake apps:** exchange apps in app stores that look real but steal logins.

**Defences:** bookmark the real exchange site and use only that bookmark or the official app. Never log in from a link. Verify deposit addresses inside your logged-in account, not from an email or message. Treat any "urgent account action required" email as phishing until proven otherwise through the official app.

## 5. Depositing correctly

1. **Log in through your bookmark or official app.** Verify the domain and your anti-phishing code if set.
2. **Generate a fresh deposit address in your account** for the asset and network you intend to use. Do not reuse an address from an old screenshot or message.
3. **Check the asset and network three times:** the asset, the network, and any memo/tag required (some assets, such as XRP or BNB on certain networks, require a memo — sending without it can lose funds).
4. **Send a test deposit first** for any new asset, network, or large amount. Confirm it arrives and is credited before sending the rest.
5. **Allow for confirmation times.** Deposits require network confirmations, and exchanges add their own processing time. A deposit that is "confirmed on-chain" but not yet credited is normal for a period — check the exchange's required confirmation count before panicking.
6. **Keep records:** transaction hash, amount, network, date, and screenshots of the deposit instructions, for tax and for support if something goes wrong.

## 6. Withdrawing correctly

Withdrawing is where the most expensive mistakes happen, because withdrawals are irreversible.

Before every withdrawal, check, slowly:

1. **Destination address:** copied, not typed, with first and last characters compared after pasting.
2. **Network:** the network you select on the exchange must match the network your receiving wallet supports for that asset. Wrong network is the single most common withdrawal loss.
3. **Memo/tag:** required or not? If required and omitted, funds can be lost or stuck for weeks.
4. **Amount and fee:** the amount that will actually arrive, after the exchange's withdrawal fee and any network fee.
5. **Whitelist status:** if you use whitelisting, is the destination already whitelisted, and has any waiting period passed?
6. **Test withdrawal first** for any new address, network, or large amount.

**If a withdrawal goes wrong:** contact exchange support immediately with the transaction hash, and contact the receiving wallet's support if applicable. Recovery is sometimes possible if funds went to an exchange-controlled wallet on the wrong network, and almost never possible if they went to a private wallet you do not control. Do not pay anyone offering to "recover" the withdrawal for a fee.

## 7. What happens if an exchange fails

Exchange failures follow a pattern, and the warning signs usually appear before the collapse:

**Warning signs:**
- Withdrawal pauses, delays, or new limits, explained vaguely ("maintenance", "upgrades").
- Leadership silence, deleted posts, or contradictory statements.
- Rumours of insolvency, regulatory action, or lost funds, denied without evidence.
- Native token price collapsing, or the exchange offering unusually high yields to attract deposits.
- Auditors resigning, or proof-of-reserves reports withdrawn or disputed.

**What failure means for your funds:**
- In bankruptcy, customer funds may be treated as the company's assets, and customers become unsecured creditors — last in line, recovering cents on the dollar, after years, if anything.
- Some jurisdictions and some exchange structures protect customer funds better (segregated accounts, trusts), but this is the exception, not the rule, and it depends on local law and the exchange's actual practices, not its marketing.
- "Your funds are SAFU" or similar slogans are marketing, not legal guarantees. Read the terms of service for what actually happens in insolvency — most users never do, until it is too late.

**Control:** keep only what you need for active trading on any exchange. Move long-term holdings to self-custody (see WalletSetupGuide), accepting that self-custody adds its own risks (seed phrase loss). Split across exchanges if you must keep funds on exchanges, so no single failure takes everything.

## 8. Exchange services beyond trading: extra risks

- **Staking on exchanges:** the exchange stakes on your behalf. You bear exchange risk plus staking risk (lockups, slashing, rate changes), and you cannot choose the validator.
- **Lending / earn products:** "earn" products lend your assets to traders or protocols. Returns come with borrower, protocol, and exchange risk. "Earn" is marketing for lending — read what your assets are actually doing.
- **Derivatives on exchanges:** leveraged products with liquidation risk, funding costs, and exchange-specific rules (see CryptoDerivativesGuide). Exchange derivatives are not suitable for beginners.
- **Exchange tokens:** holding an exchange's own token for fee discounts ties your funds to that exchange's fortunes. If the exchange fails, its token usually collapses first.

Each additional service adds a risk layer. Use only services you understand, with amounts sized for their risks.

## 9. If something goes wrong: a response checklist

- **Unauthorised login or withdrawal:** change your password immediately, revoke sessions and API keys, contact support with timestamps and transaction hashes, and freeze the account if the exchange offers that option.
- **Deposit not credited:** wait for the required confirmations, verify the transaction hash on a block explorer, check asset/network/memo, then contact support with full details. Do not resend until support advises.
- **Withdrawal stuck:** check the exchange's status page and your email for verification requests (some withdrawals require email confirmation). If it remains stuck beyond the stated processing time, contact support with the withdrawal ID.
- **Exchange pauses withdrawals:** do not panic-sell or panic-buy. Document your balances (screenshots, exports), follow official announcements only, and do not pay anyone offering early access or recovery.
- **Suspected phishing:** do not click further, change your password from a clean device via your bookmark, enable or re-check 2FA, and report the phishing page/account to the exchange and to the platform hosting it.

## 10. Frequently asked questions

**Should I keep all my crypto on one exchange?**
No. Split between self-custody for long-term holdings and, if needed, one or two reputable exchanges for active trading — with only trading amounts on exchanges.

**Is a "regulated" exchange safe?**
Safer in some respects (oversight, reporting, sometimes segregation requirements), but regulation does not guarantee solvency, security, or recovery in bankruptcy. Check what the specific regulation actually requires and protects in your jurisdiction.

**What is proof of reserves, and should I trust it?**
Proof of reserves is cryptographic evidence that an exchange controls certain assets at a point in time. It does not prove the exchange's liabilities, its off-balance-sheet obligations, or that assets will still be there tomorrow. It is a useful signal, not a guarantee — and its absence is a warning.

**Can I use a DEX instead to avoid exchange risk?**
Yes, for trading — DEXs remove exchange custody risk. But DEXs add smart contract, slippage, MEV, and self-custody risks, and they generally do not offer fiat on-ramps. Many users use both: a CEX for fiat entry/exit, a DEX and self-custody for holding and trading. Understand each tool's risks before relying on it.

> Educational content only. This is not financial, legal, or tax advice.
