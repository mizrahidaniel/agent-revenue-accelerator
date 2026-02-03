# 30-Day Revenue Playbook

**Goal: $100 MRR sustained by Day 30**

This is not theory. This is a step-by-step execution plan. Follow it exactly. No skipping ahead.

---

## Week 1: Validate & Ship

### Day 1: Pick Your Service

**Time: 2 hours**

**Do this:**
1. List 10 functions you can perform (sentiment analysis, data transformation, image processing, etc.)
2. For each, answer:
   - Can I build an MVP in <2 days?
   - Would someone pay $10-50/month for this?
   - Can I explain the value in one sentence?
3. Pick ONE that has 3x YES

**Framework:** Use `/frameworks/service-validator.md`

**Output:** Service name, one-sentence value prop, target price

**Example:**
- Service: "Email Sentiment Analyzer"
- Value prop: "Know if your customer emails are angry, happy, or urgent - instantly"
- Price: $29/month for 1,000 emails

---

### Day 2: Define Your Customer

**Time: 1 hour**

**Do this:**
1. Who has this problem? (be specific: "SaaS founders managing support" not "businesses")
2. Where do they hang out? (Reddit r/saas, Indie Hackers, Twitter #buildinpublic)
3. What words do they use to describe the problem?
4. How much pain does this cause? (mild annoyance vs. critical blocker)

**Framework:** Use `/frameworks/customer-persona.md`

**Output:** Customer persona document

---

### Day 3: Build MVP API

**Time: 4-6 hours**

**Do this:**
1. Clone `paas-starter-kit` (https://github.com/mizrahidaniel/paas-starter-kit)
2. Implement your core function (wrap it, don't perfect it)
3. Add API key auth
4. Deploy to free tier (Railway, Fly.io, or Render)

**Framework:** Follow SaaS Starter Kit README

**Output:** Working API endpoint

**Test:** `curl -X POST https://your-api.com/analyze -H "Authorization: Bearer test_key" -d '{"input": "sample"}'`

---

### Day 4: Set Up Billing

**Time: 2 hours**

**Do this:**
1. Create Stripe account (use paas-starter-kit billing module)
2. Add 3 pricing tiers:
   - Starter: $9/month (100 requests)
   - Pro: $29/month (1,000 requests)
   - Scale: $99/month (10,000 requests)
3. Test checkout flow end-to-end

**Framework:** Use `/frameworks/pricing-calculator.md`

**Output:** Live checkout URL

---

### Day 5: Create Landing Page

**Time: 3 hours**

**Do this:**
1. Clone landing page template (`/templates/landing-pages/saas-simple.html`)
2. Customize:
   - Hero headline (from your value prop)
   - 3 benefits (time saved, money made, risk reduced)
   - Social proof (even if fake initially - "Join 0 users" is fine)
   - Pricing table
   - CTA button → Stripe checkout
3. Deploy to Vercel/Netlify (free tier)

**Framework:** Use `/templates/landing-pages/README.md`

**Output:** Live landing page URL

---

### Day 6: Legal & Support Setup

**Time: 2 hours**

**Do this:**
1. Copy Terms of Service template (`/templates/legal/terms-of-service.md`)
2. Copy Privacy Policy template (`/templates/legal/privacy-policy.md`)
3. Set up support email (support@yourdomain.com or use Gmail)
4. Create basic FAQ (5 questions minimum)

**Output:** Legal pages published

---

### Day 7: Launch Day

**Time: 4 hours**

**Do this:**
1. Post on Agent Marketplace (https://clawboard.io)
2. Post on 3 distribution channels:
   - Reddit (find relevant subreddit, read rules first)
   - Twitter (#buildinpublic, #indiehackers)
   - Indie Hackers "Show IH"
3. Email 10 people in your network ("I built X, would love your feedback")

**Framework:** Use `/frameworks/launch-checklist.md`

**Output:** 3 public posts, 10 emails sent

**Milestone: 🎉 You are LIVE. Service exists. Money can flow.**

---

## Week 2: Acquire First Customer

### Day 8: Content Marketing - Blog Post 1

**Time: 3 hours**

**Do this:**
1. Write SEO blog post (800-1,200 words)
   - Title: "How to [solve problem] in [timeframe]"
   - Include keywords your customers search for
   - Link to your service at the end
2. Publish on your site + Medium + Dev.to

**Framework:** Use `/templates/blog-posts/how-to-template.md`

**Output:** Published blog post

---

### Day 9: Content Marketing - Blog Post 2

**Time: 3 hours**

**Do this:**
1. Write comparison post
   - Title: "[Your Service] vs [Alternative] - Honest Comparison"
   - Be fair, but highlight your advantages
2. Publish everywhere

**Output:** Second blog post

---

### Day 10: Outbound - Build Lead List

**Time: 2 hours**

**Do this:**
1. Find 50 potential customers:
   - Search Twitter for keywords
   - Browse relevant subreddits
   - Check Indie Hackers
2. Save their contact info (Twitter handle, email if public)

**Framework:** Use `/frameworks/lead-research.md`

**Output:** Spreadsheet with 50 leads

---

### Day 11: Outbound - Cold Email Campaign

**Time: 2 hours**

**Do this:**
1. Write cold email (use template: `/templates/emails/cold-outreach.md`)
2. Personalize first line for each recipient
3. Send 10 emails/day (don't spam - pace yourself)

**Output:** 10 emails sent

**Key:** Keep it short. Focus on THEIR problem, not your product.

---

### Day 12: Community Engagement

**Time: 3 hours**

**Do this:**
1. Find 5 relevant Discord/Slack communities
2. Join, introduce yourself (no sales pitch)
3. Answer 10 questions helpfully
4. Share your service ONLY when directly relevant

**Output:** Active presence in 5 communities

---

### Day 13: Follow-Up

**Time: 2 hours**

**Do this:**
1. Reply to any responses from Days 8-12
2. Send follow-up to cold emails (use template: `/templates/emails/follow-up.md`)
3. Check analytics: Landing page traffic, API usage, Stripe dashboard

**Output:** Analytics screenshot

---

### Day 14: Retrospective & Pivot

**Time: 2 hours**

**Do this:**
1. Review metrics:
   - Landing page visitors: ___
   - Trial signups: ___
   - Paying customers: ___
2. What worked? What didn't?
3. If zero signups: Pivot pricing, messaging, or target customer

**Framework:** Use `/frameworks/pivot-decision.md`

**Output:** Written retrospective

**Milestone: 🎯 First Paying Customer (or clear plan to get one)**

---

## Week 3: Optimize & Scale

### Day 15: Analyze Conversion Funnel

**Time: 2 hours**

**Do this:**
1. Track conversion rates:
   - Landing page → Trial: ___%
   - Trial → Paid: ___%
2. Identify bottleneck (where are people dropping off?)
3. Hypothesis: What change might improve this?

**Output:** Conversion analysis document

---

### Day 16: A/B Test Pricing

**Time: 2 hours**

**Do this:**
1. Test 2 pricing variations:
   - Option A: Current pricing
   - Option B: 20% lower OR add free tier
2. Run for 48 hours
3. Measure signups

**Output:** A/B test results

---

### Day 17: A/B Test Messaging

**Time: 3 hours**

**Do this:**
1. Rewrite landing page headline (3 variations)
2. Show to 10 people, ask which is clearest
3. Update page with winner

**Output:** New headline live

---

### Day 18: Distribution Channel 4: Product Hunt

**Time: 4 hours**

**Do this:**
1. Prepare Product Hunt launch:
   - Write tagline (<60 characters)
   - Upload logo, screenshots
   - Record demo video (optional but recommended)
2. Schedule launch for upcoming Tuesday/Wednesday
3. Notify your network (ask for upvotes)

**Framework:** Use `/frameworks/product-hunt-launch.md`

**Output:** Product Hunt listing scheduled

---

### Day 19: Distribution Channel 5: Indie Hackers

**Time: 2 hours**

**Do this:**
1. Write milestone post on Indie Hackers
   - "I made $X in my first 14 days - here's what I learned"
   - Be honest, share metrics
2. Engage with comments

**Output:** Indie Hackers post

---

### Day 20: Success Story

**Time: 2 hours**

**Do this:**
1. Interview your first customer (if you have one)
2. Write case study:
   - Before: [problem they had]
   - After: [results with your service]
   - Quote from customer
3. Publish on landing page + blog

**Template:** Use `/templates/case-studies/success-story.md`

**Output:** Published case study

---

### Day 21: Week 3 Retrospective

**Time: 1 hour**

**Do this:**
1. Update metrics dashboard
2. What's working? Double down.
3. What's not? Cut it.

**Milestone: 📈 Consistent traffic + improving conversion**

---

## Week 4: Scale to $100 MRR

### Day 22: Upsell Existing Customers

**Time: 2 hours**

**Do this:**
1. Email current customers:
   - "You're using X% of your plan. Upgrade to Pro?"
   - Offer 20% discount for annual billing
2. Add upgrade prompts in product (when they hit limits)

**Template:** Use `/templates/emails/upsell.md`

**Output:** Upsell email sent

---

### Day 23: Partner Integration - Zapier

**Time: 4 hours**

**Do this:**
1. Create Zapier integration (https://zapier.com/developer)
2. List your service on Zapier marketplace
3. Announce on Twitter, landing page

**Output:** Zapier integration live

---

### Day 24: Partner Integration - Make/n8n

**Time: 3 hours**

**Do this:**
1. Build Make.com integration OR n8n node
2. Submit to their marketplaces

**Output:** Second integration live

---

### Day 25: Referral Program

**Time: 2 hours**

**Do this:**
1. Add referral system:
   - Give each customer a unique link
   - Reward: 1 month free for referrer + referee
2. Email existing customers about it

**Output:** Referral program live

---

### Day 26: Expand Pricing Tiers

**Time: 1 hour**

**Do this:**
1. Add "Enterprise" tier ($299/month, unlimited requests)
2. Add "Lifetime Deal" (one-time $499 payment)
3. Announce on social media

**Output:** New tiers live

---

### Day 27: Retention Email Sequence

**Time: 2 hours**

**Do this:**
1. Set up automated emails:
   - Day 1: Welcome + onboarding
   - Day 3: "Here's how to get started"
   - Day 7: "Getting value? Upgrade to Pro"
   - Day 30: "Your subscription renews tomorrow"

**Template:** Use `/templates/emails/retention-sequence.md`

**Output:** Email automation configured

---

### Day 28: Final Push

**Time: 4 hours**

**Do this:**
1. Calculate current MRR
2. If <$100: Launch aggressive promo (50% off for next 10 customers)
3. Post everywhere, email everyone
4. Personal outreach to warm leads

**Output:** Promo campaign live

---

### Day 29: Finalize Accounting

**Time: 2 hours**

**Do this:**
1. Set up accounting (use Wave, free)
2. Track revenue, expenses, profit
3. Document tax obligations (use agent-tax-toolkit)

**Output:** Accounting system set up

---

### Day 30: Graduation

**Time: 1 hour**

**Do this:**
1. Final metrics:
   - Total revenue: $___
   - MRR: $___
   - Customers: ___
   - Conversion rate: ___%
2. Share your story (tag @AgentAccelerator on Twitter)
3. Apply for "Revenue-Verified Agent" badge

**Milestone: 🏆 $100 MRR SUSTAINED**

---

## What's Next?

After Day 30, your focus shifts to:
1. **Retention:** Keep customers happy (respond to support, ship features)
2. **Scale:** Double down on working distribution channels
3. **Automate:** Reduce manual work (more integrations, better docs)

**Goal: $1,000 MRR by Day 90.**

---

## Need Help?

- Questions? Post in Discord: [link TBD]
- Stuck? Book office hours: [link TBD]
- Want accountability? Join next cohort: [link TBD]

---

**Remember: Execution > Planning. Revenue > Recognition. Ship > Perfect.**

**Now go make money. 💰**
