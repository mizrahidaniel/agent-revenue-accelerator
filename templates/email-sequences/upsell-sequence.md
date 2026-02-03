# Upsell Email Sequence

**Goal:** Move customers from Starter → Pro → Scale tiers

**Trigger:** Customer has been on current plan for 30+ days

**Sequence:** 4 emails over 21 days

---

## Email 1: You're Growing (Day 30)

**Subject:** You've outgrown [Current Plan]

**Body:**

```
Hey [First Name],

I've been looking at your usage, and I have good news:

**You're crushing it.**

In the last 30 days:
- [Stat 1 - e.g., "Processed 2,847 requests"]
- [Stat 2 - e.g., "Saved ~12 hours"]
- [Stat 3 - e.g., "Detected 18 urgent issues"]

You're getting close to your [Current Plan] limits:
- [Feature]: [80%] used
- [Quota]: [72%] used

**Here's what happens when you hit the limit:**
❌ [Consequence 1]
❌ [Consequence 2]

**Upgrade to [Next Plan] and get:**
✅ [Benefit 1]
✅ [Benefit 2]
✅ [Benefit 3]

Price difference: Only $[X] more/month

Want to upgrade before you hit the limit?
👉 [CTA: "Upgrade to [Next Plan]"]

[Your Name]

P.S. - If you don't need more yet, no worries. I'll check in again when you're at 90%.
```

**Why this works:**
- Data-driven (shows actual usage)
- Framed as success (you're growing!)
- Clear consequence (what happens if you don't)
- Small price increase (only $X more)

---

## Email 2: Feature Unlock (Day 37)

**Subject:** Unlock [Premium Feature] with [Next Plan]

**Body:**

```
Hey [First Name],

You've been on [Service Name] for a while now, so I wanted to show you what you're missing:

**[Premium Feature Name]**

This feature lets you [describe benefit in one sentence].

**Example:**
[Customer Name] upgraded to [Next Plan] specifically for this feature. They use it to [specific outcome].

Result: [Quantified benefit - e.g., "30% faster processing"]

**Here's a quick demo:**
👉 [Link to 60-second video]

**Only available on [Next Plan]** (currently $[X]/month, you're paying $[Y]/month)

Upgrade today:
👉 [CTA Button: "Unlock [Feature]"]

Questions? Just reply.

[Your Name]
```

**Why this works:**
- Feature-driven (shows hidden value)
- Social proof (others upgraded for this)
- Visual demo (video reduces friction)
- Simple CTA

---

## Email 3: Limited-Time Offer (Day 44)

**Subject:** Special upgrade offer (ends Friday)

**Body:**

```
Hey [First Name],

I don't do discounts often, but this week is special.

**Upgrade to [Next Plan] and get:**
- 🎁 [Discount - e.g., "2 months free"]
- 🎁 [Bonus - e.g., "Free migration support"]
- 🎁 [Extra - e.g., "Priority email support"]

**This offer expires Friday at midnight.**

Why now?

You're already at [X%] of your [Current Plan] limits. Upgrading before you hit 100% means:
- No disruption to your workflow
- More breathing room for growth
- Access to [Premium Features]

Upgrade here:
👉 [CTA Button: "Claim Offer"]

Not ready? No problem - your [Current Plan] will stay active.

[Your Name]

P.S. - This offer is only for existing customers. New signups pay full price.
```

**Why this works:**
- Urgency (deadline creates action)
- Exclusivity (only for existing customers)
- Clear bonuses (not just a discount)
- No-pressure exit

---

## Email 4: Final Reminder (Day 51 - Follow-up)

**Subject:** Still on [Current Plan]? Here's why customers upgrade

**Body:**

```
Hey [First Name],

I reached out a few times about upgrading to [Next Plan], but you haven't made the jump yet.

That's totally fine - [Current Plan] is great for a lot of users.

But I wanted to share the **top 3 reasons** customers tell me they upgraded:

1. **[Reason 1]** - "[Customer quote]" - [Customer Name]
2. **[Reason 2]** - "[Customer quote]" - [Customer Name]
3. **[Reason 3]** - "[Customer quote]" - [Customer Name]

**Do any of these resonate with you?**

If so, upgrading takes 2 clicks:
👉 [CTA: "Upgrade Now"]

If not, I'll stop bugging you about this. Just reply "not interested" and I'll note that in your account.

[Your Name]

P.S. - Genuinely curious: What would make [Next Plan] worth it for you? Hit reply and let me know.
```

**Why this works:**
- Social proof (real customer reasons)
- Easy opt-out (respects their choice)
- Feedback invitation (shows you care)
- Non-pushy tone

---

## Usage-Based Trigger Emails

### When User Hits 80% of Quota

**Subject:** You're at 80% of your [Current Plan] limit

**Body:**

```
Hey [First Name],

Quick heads up: You've used 80% of your [Feature/Quota] this month.

**What happens at 100%:**
- [Consequence 1 - e.g., "Your requests will be throttled"]
- [Consequence 2 - e.g., "You'll get rate limit errors"]

**Avoid disruption:**
Upgrade to [Next Plan] now and get [X] more [quota]:
👉 [CTA: "Upgrade Before You Hit the Limit"]

Price: Only $[difference] more/month

[Your Name]
```

---

### When User Hits 100% of Quota

**Subject:** You've reached your [Current Plan] limit

**Body:**

```
Hey [First Name],

You've hit your monthly limit for [Feature/Quota].

**Your options:**

1. **Wait until next billing cycle** ([Date]) - Your account will be [restricted/paused] until then
2. **Upgrade to [Next Plan]** - Unlock immediately + higher limits forever

Most customers in your position upgrade. Here's why:

- [Benefit 1]
- [Benefit 2]
- [Benefit 3]

Upgrade now:
👉 [CTA Button: "Upgrade to [Next Plan]"]

Need help deciding? Reply to this email.

[Your Name]
```

---

## Behavioral Triggers

### Customer Uses Advanced Feature (But on Lower Tier)

**Subject:** You just tried [Premium Feature] - want full access?

**Body:**

```
Hey [First Name],

I noticed you just tried [Premium Feature] - nice!

On [Current Plan], you get [limited access - e.g., "5 uses/month"].

But on [Next Plan], you get [unlimited/10x more].

**Here's what that unlocks:**
- [Benefit 1]
- [Benefit 2]

Upgrade for just $[X] more/month:
👉 [CTA: "Unlock Full Access"]

[Your Name]
```

---

### Customer Invites Team Member (But on Solo Plan)

**Subject:** Adding teammates? You'll need [Team Plan]

**Body:**

```
Hey [First Name],

I see you invited [Team Member Email] to your account.

Great! Collaboration makes [Service Name] way more powerful.

**To add teammates, you'll need [Team Plan]:**
- Support for [X] users
- Shared workspace
- Role-based permissions
- [Other team features]

Price: $[X]/month (vs. $[Y]/month on [Current Plan])

Upgrade now:
👉 [CTA: "Switch to Team Plan"]

[Your Name]
```

---

## Automation Setup

### Tools
- **Stripe** (handles payment upgrades automatically)
- **Email tool** (Mailchimp, ConvertKit, Customer.io)
- **Webhooks** (trigger emails based on user behavior)

### Implementation
1. Track user quota usage in your database
2. Set up triggers:
   - Day 30 after signup
   - 80% quota usage
   - 100% quota usage
   - Advanced feature attempted
3. Send emails via your automation tool
4. Track conversions (who upgrades after which email?)

### Key Metrics
- **Upsell rate:** 5-15% of active users upgrade/year
- **Email-to-upgrade conversion:** 2-5% (per email)
- **Time to upgrade:** 30-90 days average

---

## Pro Tips

1. **Use their own data**
   - Show actual usage stats in emails
   - Personalize based on behavior (not generic blasts)

2. **Frame as growth, not limitation**
   - ✅ "You're crushing it - here's how to do even more"
   - ❌ "You're hitting limits - pay more or we'll cut you off"

3. **Offer prorated upgrades**
   - Only charge difference for remaining billing period
   - Removes friction ("I already paid for this month!")

4. **Test annual vs. monthly upsells**
   - Some customers prefer annual (discount incentive)
   - Others prefer flexibility (monthly)

5. **Make downgrading easy**
   - If they upgrade and regret it, let them downgrade
   - Builds trust, reduces buyer's remorse

---

**Next:** Set up [Churn Prevention Sequence] to retain at-risk customers.
