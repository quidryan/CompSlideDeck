---
theme: seriph
background: https://cover.sli.dev
transition: slide-left
highlighter: shiki
lineNumbers: false
title: Tech Compensation
info: |
  Understanding RSUs, ISOs, and NQSOs —
  the equity components that make up total comp in tech.
---

# Tech Compensation
## It's Not Just $/hr

Understanding RSUs, ISOs, and NQSOs before you sign the offer letter

<div class="abs-bl m-10 text-sm text-gray-400">
Not financial advice. Consult a CPA for your specific situation.
</div>

---
transition: fade
layout: section
---

# Total Comp (TC)

### What you're actually being paid

---

# What Is Total Comp?

Most job postings lead with **base salary**. That's only part of the picture.

<div class="columns mt-4">
<div>

**Typical TC Components**

<v-clicks>

- Base Salary
- Annual Cash Bonus
- **Equity** (RSU / ISO / NQSO)
- Benefits (401k match, health)
- Signing Bonus *(one-time)*

</v-clicks>

</div>
<div>

<v-click>

**Why it matters**

At a FAANG-tier company, equity can be **50–200%** of base salary in expected annual value.

Ignoring it means comparing a $200K TC offer to a $130K one as if they're the same.

</v-click>

</div>
</div>

<v-click>

<div class="callout mt-8">

**Rule of thumb:** Annualized equity value = Total grant value ÷ Vesting years. Always add this to base when comparing offers.

</div>

</v-click>

---

# TC in Practice: A Real Example

<v-click>

| Component | Annual Value |
|---|---|
| Base Salary | $175,000 |
| Annual Cash Bonus (15% target) | $26,250 |
| RSU Vesting (annualized) | $100,000 |
| **Total Comp (TC)** | **$301,250** |

</v-click>

<v-click>

The RSU component here is **33% of total comp**.

</v-click>

<v-click>

<div class="warning mt-4">

Offers are often quoted as "base + bonus." Always ask: **"What is the full RSU grant and vesting schedule?"** That number needs to be part of the math.

</div>

</v-click>

---
transition: fade
layout: section
---

# RSUs

### Restricted Stock Units

---

# What Are RSUs?

RSUs are grants of **actual company stock**, delivered to you on a vesting schedule.

<v-clicks>

- Used by **public companies**: Google, Meta, Microsoft, Apple, Amazon
- You receive real shares — **no purchase required**
- Taxed as **ordinary income** when they vest (treated like a paycheck by the IRS)
- Shares go directly into your brokerage account at vest
- No exercise decision — they just appear

</v-clicks>

<v-click>

<div class="callout mt-4">

**RSU = Deferred salary paid in stock.** The company is saying: "We'll give you $X of our stock, but you have to stay employed to earn it."

</div>

</v-click>

---

# Grants, Vesting, and the Cliff

**The grant** is the total value awarded at hire. **Vesting** is when you actually receive the shares.

<v-click>

Standard 4-year schedule with a 1-year cliff:

| Year | Event | Shares Received | Cumulative |
|---|---|---|---|
| Year 1 | Cliff vest | 25% (1,000 shares) | 1,000 |
| Year 2 | Quarterly | 25% (1,000 shares) | 2,000 |
| Year 3 | Quarterly | 25% (1,000 shares) | 3,000 |
| Year 4 | Quarterly | 25% (1,000 shares) | 4,000 |

</v-click>

<v-click>

<div class="callout mt-4">

**The cliff** means if you leave before your 1-year anniversary, you receive **zero** equity. After the cliff, vesting typically happens quarterly or monthly.

</div>

</v-click>

---

# Offer Letter: Reading the RSU Section

<v-click>

A real offer letter will say something like:

> *"You will receive a grant of 4,000 Restricted Stock Units, subject to a 4-year vesting schedule with a 1-year cliff, vesting quarterly thereafter."*

</v-click>

<v-click>

What you need to calculate from that:

</v-click>

<v-clicks>

- **Grant value at hire:** shares × current stock price
- **Annualized value:** grant value ÷ 4 years
- **Your actual cliff risk:** 12 months with nothing vested

</v-clicks>

<v-click>

<div class="warning mt-4">

The grant is denominated in **shares**, not dollars. The dollar value will change with the stock price. The offer letter's stated dollar value is a snapshot, not a guarantee.

</div>

</v-click>

---

# RSU Example: Building the Math

<v-click>

**The offer:** $150,000 base salary + $200,000 RSU grant over 4 years

</v-click>

<v-click>

**Step 1 — Convert to shares at the grant date stock price of $50:**

```
$200,000 ÷ $50/share = 4,000 shares total
```

</v-click>

<v-click>

**Step 2 — Split across the vesting schedule:**

```
4,000 shares ÷ 4 years = 1,000 shares/year
```

</v-click>

<v-click>

**Year 1 vest value:** 1,000 shares × $50 = `$50,000`

</v-click>

<v-click>

Your first year TC: $150,000 base + $50,000 RSU = **$200,000**

</v-click>

---

# What Happens When the Stock Goes Up?

<v-click>

You're now in Year 2. The company has had a strong year. Stock rises from $50 → **$100/share**.

</v-click>

<v-click>

Your Year 2 vest is still the same 1,000 shares from your original grant:

```
1,000 shares × $100/share = $100,000
```

</v-click>

<v-click>

<span class="big-number">$100,000</span>

</v-click>

<v-click>

From the same grant that valued this tranche at $50,000. **The upside is real.**

</v-click>

<v-click>

<div class="gain mt-4">

Your Year 2 TC: $150,000 base + $100,000 RSU = **$250,000** — 25% more than when you accepted the offer.

</div>

</v-click>

---

# What Happens When the Stock Goes Down?

<v-click>

The same math works in reverse. Stock drops from $50 → **$25/share** by Year 2.

</v-click>

<v-click>

```
1,000 shares × $25/share = $25,000
```

</v-click>

<v-click>

Year 2 TC: $150,000 + $25,000 = **$175,000** — well below the offer letter number.

</v-click>

<v-click>

<div class="warning mt-4">

**Tax note:** You are taxed at vest based on the **fair market value on that day**, regardless of whether you sell. If the stock drops further after vest, you may owe taxes on a value you no longer have.

</div>

</v-click>

<v-click>

Many engineers sell shares immediately on vest to lock in the value and avoid this risk. Others hold. Neither is universally right — it depends on your tax situation and conviction in the company.

</v-click>

---

# Refreshers: Maintaining Your TC Target

<v-click>

Companies know a 4-year grant runs out. To retain employees, they issue **refresh grants** before the original grant depletes.

</v-click>

<v-click>

**A 3-year scenario:**

| Year | Event | Annual RSU Vesting |
|---|---|---|
| 1 | Hired — $200K/4yr grant | $50,000 (cliff) |
| 2 | Vesting | $50,000 |
| 3 | **Refresh grant issued** — $150K/3yr | $50,000 original + $50,000 refresh |
| 4 | Overlapping grants | $50,000 original + $50,000 refresh |
| 5 | Original exhausted | $50,000 refresh only |

</v-click>

<v-click>

<div class="gain mt-4">

**Refreshers are negotiable.** Ask: *"What is the annual refresh policy?"* and *"What have engineers at my level historically received?"* The refresh is often where the real retention value lives.

</div>

</v-click>

---
transition: fade
layout: section
---

# ISOs

### Incentive Stock Options

---

# What Are ISOs?

ISOs give you the **right to purchase** company stock at a fixed price, called the **strike price** (or exercise price).

<v-clicks>

- Used almost exclusively by **private startups**
- Strike price = Fair Market Value (FMV) on the grant date — often pennies
- You do **not** receive shares automatically — you must **exercise** (pay) for them
- Special tax treatment: if you hold properly, gains may qualify as long-term capital gains (LTCG)
- There is a **10-year expiration** window to exercise

</v-clicks>

<v-click>

<div class="callout mt-4">

**ISO = The right to buy stock at today's price, sometime in the future.** If the company grows 100×, your locked-in low strike price becomes enormously valuable.

</div>

</v-click>

---

# The ISO Decision: When to Exercise?

You have choices. Each carries different risk and tax implications.

<v-click>

| Timing | Risk Level | Tax Implication |
|---|---|---|
| **Immediately** (83(b) election) | High — company may fail | Pay taxes on minimal spread, max LTCG holding period |
| **While still private** | Medium — illiquid, cash outlay | Spread at exercise may trigger AMT |
| **At or after IPO** | Medium/High — lockup risk | Spread at market price; large potential AMT bill |
| **At expiration (10yr)** | Lowest cash risk | Company may be worthless by then |

</v-click>

<v-click>

<div class="warning mt-4">

**AMT trap:** The spread between FMV and strike price is an Alternative Minimum Tax preference item. A large spread at exercise can trigger a massive tax bill — even with no cash in hand.

</div>

</v-click>

---

# The IPO Scenario: The Tax Trap

<v-click>

**The scenario:** You exercise ISOs at IPO. There's a standard **180-day lockup period** — you cannot sell.

</v-click>

<v-click>

The math that can go wrong:

```
Grant: 10,000 ISOs  |  Strike: $0.10/share
IPO price: $50/share

Spread at exercise = ($50.00 − $0.10) × 10,000 = $499,000 AMT income
```

</v-click>

<v-click>

Stock drops 60% during the lockup period:

```
Sell at $20/share  →  cash received = $200,000
AMT owed on $499,000 spread  →  can exceed $150,000
```

</v-click>

<v-click>

<div class="warning mt-4">

**You can owe more in taxes than you received in cash.** This destroyed fortunes during the 2000 dot-com bust and again in the 2021–2022 tech correction. Work with a CPA *before* any IPO exercise decision.

</div>

</v-click>

---

# ISOs: The 10-Year Comparison

You have **0.1% equity** in a startup. Two paths, 10 years.

<v-click>

<div class="columns">
<div>

**Startup Path**

- 2026: Join, strike price $0.10
- Multiple funding rounds → dilution
- 2036: IPO at $80/share
- Valuation: $2B
- 0.1% pre-dilution: ~$2,000,000

*After dilution (typical 40–60%), taxes, lockup risk, AMT:*

**Realistic net: $400K–$900K**

</div>
<div>

**FAANG Path (10 years)**

- $175K base × 10 yrs = $1.75M
- $100K/yr RSU (refreshed) × 10 = $1M
- Liquid at each vest
- No AMT, no lockup

**Total: ~$2.75M — predictable**

</div>
</div>

</v-click>

<v-click>

<div class="callout mt-4">

The startup wins only if: the exit is large AND you survive dilution AND timing and taxes work in your favor. FAANG is the **risk-adjusted winner** for most people at most startups. The lottery-ticket scenario is real but rare.

</div>

</v-click>

---
transition: fade
layout: section
---

# NQSOs

### Non-Qualified Stock Options

---

# What Are NQSOs?

NQSOs are stock options with **simpler but less favorable tax treatment** than ISOs.

<v-clicks>

- Used by public companies — **Netflix is the most prominent example**
- Strike price set at FMV on grant date
- **Taxed as ordinary income at exercise** on the spread (FMV − strike), regardless of holding period
- No AMT complication
- The remainder (if you hold shares after exercise) is taxed as capital gains when sold

</v-clicks>

<v-click>

<div class="callout mt-4">

**NQSO = Option to buy at strike price, taxed as W-2 income when you buy.** Simpler than ISOs, but the preferential capital gains treatment on the spread is gone.

</div>

</v-click>

---

# NQSOs: The Netflix Model

Netflix famously offers employees a **choice** between RSUs and NQSOs — more options for higher upside if you believe in the stock.

<v-click>

**NQSO example:**

```
Grant: 1,000 NQSOs  |  Strike price: $500/share
Current stock price: $700/share

Intrinsic value = ($700 − $500) × 1,000 = $200,000
```

</v-click>

<v-click>

**To exercise:**

```
Cost to buy shares: 1,000 × $500 = $500,000 cash outlay
Shares worth:       1,000 × $700 = $700,000

Spread taxed as W-2 income: $200,000
Tax on spread (~37% bracket): ~$74,000

Net gain after tax: ~$126,000
```

</v-click>

<v-click>

<div class="warning mt-4">

You need **cash to exercise** NQSOs — or do a same-day sale (exercise + immediately sell). They don't appear in your account automatically like RSUs.

</div>

</v-click>

---

# RSU vs ISO vs NQSO: Side by Side

| Feature | RSU | ISO | NQSO |
|---|---|---|---|
| Typical company | Public | Private startup | Public |
| Purchase required | No | Yes | Yes |
| Tax at vest/exercise | Ordinary income | None (if careful) | Ordinary income on spread |
| Capital gains clock | Starts at vest | Starts at exercise | Starts at exercise |
| AMT risk | None | **Yes** | None |
| Upside if stock rises | Proportional | Leveraged | Leveraged |
| Risk if stock falls | Grant value shrinks | Options may be worthless | Options may be worthless |
| Complexity | Low | High | Medium |

---
transition: fade
layout: center
class: text-center
---

# Key Takeaways

<v-clicks>

1. **Always calculate TC**, not just base — equity is often 30–50%+ of the number that matters
2. **RSUs** are the most predictable: deferred salary in stock, taxed straightforwardly at vest
3. **ISOs** offer high upside but high complexity — understand AMT before you exercise anything
4. **NQSOs** give leveraged upside with simpler (but unfavorable) ordinary income tax treatment
5. **The cliff and vesting schedule** create golden handcuffs — build them into your career planning
6. **Refreshers are negotiable** — often the real retention mechanism after year 2
7. **Work with a CPA** who specializes in equity compensation before exercising any options

</v-clicks>

<v-click>

<div class="callout mt-8 text-left">

**Resources:** `carta.com/learn` · `equity.fyi` · `fairmark.com` (ISO/AMT deep dives)
Consider a **fee-only financial advisor** (no commissions) for major decisions.

</div>

</v-click>
