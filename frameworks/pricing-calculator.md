# Pricing Calculator

Use this framework to set pricing for your service. Don't guess - calculate.

---

## Step 1: Calculate Your Costs (10 minutes)

### Fixed Costs (monthly)
- Domain: $12/year = **$1/month**
- Hosting: Free tier (Railway/Fly.io) = **$0/month** (until you scale)
- Total fixed: **$1/month**

### Variable Costs (per customer)
Estimate costs for API calls, compute, storage per customer:

**Example: Sentiment Analysis API**
- AI API calls: $0.001 per request
- Customer uses 1,000 requests/month
- Cost: $1/customer/month

**Your service:**
- API/compute cost per request: $___
- Expected requests per customer: ___
- **Cost per customer: $___/month**

---

## Step 2: Set Profitability Target

**Cost per customer:** $___
**Target profit margin:** 80% (industry standard for SaaS)

**Formula:** Price = Cost / (1 - Margin)

**Example:**
- Cost: $1/customer
- Margin: 80%
- Price: $1 / 0.20 = **$5 minimum**

**Your minimum price:** $___

---

## Step 3: Research Competitor Pricing

Find 3-5 competitors. What do they charge?

| Competitor | Price | Features Included |
|------------|-------|-------------------|
| Comp A | $__/mo | ___ |
| Comp B | $__/mo | ___ |
| Comp C | $__/mo | ___ |

**Market median:** $___/month

---

## Step 4: Value-Based Pricing

What is your service WORTH to the customer?

### Time Savings
"Without my service, this task takes ___ hours/month"
"Customer's time is worth $___/hour"
**Time value:** $___ × ___ hours = $___/month

### Revenue Impact
"My service helps customer make an extra $___ /month"
**10% of value = fair price:** $___/month

### Risk Reduction
"My service prevents $___  in potential losses"
**1% of risk value:** $___/month

**Highest value metric:** $___/month ← Use this as your anchor

---

## Step 5: Tiered Pricing Model

Create 3 tiers (proven to maximize revenue):

### Tier 1: Starter (Anchor for small users)
- **Price:** 40-50% of median tier
- **Limits:** Tight but usable
- **Goal:** Get people in the door

**Example:**
- $9/month
- 100 requests
- Email support only

### Tier 2: Pro (Target tier - 70% choose this)
- **Price:** Market median OR 3x your cost
- **Limits:** Covers 80% of use cases
- **Goal:** Main revenue driver

**Example:**
- $29/month
- 1,000 requests
- Email + chat support
- Priority processing

### Tier 3: Scale (Catch whales)
- **Price:** 3-5x Tier 2
- **Limits:** High/unlimited
- **Goal:** Capture power users

**Example:**
- $99/month
- 10,000 requests
- Dedicated support
- SLA guarantee
- Custom integrations

---

## Step 6: Your Pricing Table

Fill this out:

| Tier | Price | Requests | Support | Other Features |
|------|-------|----------|---------|----------------|
| Starter | $___/mo | ___ | ___ | ___ |
| Pro | $___/mo | ___ | ___ | ___ |
| Scale | $___/mo | ___ | ___ | ___ |

---

## Step 7: Pricing Psychology

### Make Pro tier obvious winner:
- Highlight it (badge: "Most Popular")
- Show value: "$29/mo = $0.029 per request"
- Anchor high: Put Scale tier first, makes Pro look cheap

### Avoid these mistakes:
❌ Too many tiers (3 is optimal, 4 max)
❌ Confusing names ("Bronze/Silver/Gold" → Use Starter/Pro/Scale)
❌ Tiny differences ($29 vs $31 → use $29 vs $49)
❌ Hiding pricing (always show on landing page)

---

## Step 8: Annual Discount

Offer annual billing with discount:

**Formula:** 2 months free (16.7% discount)

**Example:**
- Pro: $29/month × 12 = $348/year
- Annual price: $29 × 10 = **$290/year** (save $58)

**Why?** Locks in revenue, reduces churn.

---

## Step 9: Free Trial vs Freemium

Choose ONE:

### Free Trial (Recommended)
- 7 or 14 days, full access to Pro tier
- Requires credit card upfront
- Converts 10-15% to paid

**Use if:** Your service has immediate value (they see ROI in days)

### Freemium (Not Recommended for MVP)
- Free forever tier with tight limits
- No credit card required
- Converts 2-5% to paid

**Use if:** Your service requires learning curve OR viral growth

**For MVP:** Start with free trial. Simpler, higher conversion.

---

## Step 10: Revenue Projections

Estimate your first 90 days:

### Conservative Scenario
- Month 1: 2 customers × $29 = **$58 MRR**
- Month 2: 5 customers × $29 = **$145 MRR**
- Month 3: 10 customers × $29 = **$290 MRR**

### Optimistic Scenario
- Month 1: 5 customers × $29 = **$145 MRR**
- Month 2: 15 customers × $29 = **$435 MRR**
- Month 3: 30 customers × $29 = **$870 MRR**

**Your projections:**

| Month | Customers | MRR |
|-------|-----------|-----|
| 1 | ___ | $___ |
| 2 | ___ | $___ |
| 3 | ___ | $___ |

---

## Step 11: Testing & Iteration

**Launch with your calculated pricing. Then:**

### Week 1: Measure
- Landing page visitors: ___
- Trial signups: ___
- Paid conversions: ___

### Week 2: Test
If conversion <5%:
- Try lowering Starter tier price 20%
- OR add more free trial days (7 → 14)
- OR clarify value prop on landing page

### Week 3: Optimize
- Which tier do most customers choose?
- Are power users hitting Scale limits?
- Is Starter tier profitable?

**Iterate monthly based on data.**

---

## Pricing FAQs

**Q: Should I charge more or less than competitors?**
A: Match competitors UNLESS you have clear advantage (10x faster, unique feature). Don't compete on price alone.

**Q: What if nobody pays?**
A: Either (1) price is too high, (2) value prop is unclear, or (3) no real demand exists. Test lowering price by 30%. If still zero, pivot service.

**Q: Can I change pricing later?**
A: Yes! Grandfathered customers keep old pricing. New customers see new pricing. Common to increase 10-20% annually.

**Q: How do I handle enterprise customers?**
A: Add "Enterprise" tier with "Contact us" pricing. Negotiate custom deals starting at 3x your Scale tier price.

---

## Final Pricing Decision

**Starter Tier:** $___/month for ___ requests
**Pro Tier:** $___/month for ___ requests  
**Scale Tier:** $___/month for ___ requests

**Free Trial:** ___ days (7 or 14)

**Annual Discount:** __% off (15-20% recommended)

**Next Step:** Set up these tiers in Stripe (Day 4 of playbook)

---

**Remember: You can always change pricing. Start with something reasonable, iterate based on data.**

**Pricing is not set in stone - it's a hypothesis you test.**
