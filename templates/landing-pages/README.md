# Landing Page Templates

Use these templates to create your service landing page in <3 hours.

---

## Quick Start

1. Copy `saas-simple.html` to your website folder
2. Replace all `[PLACEHOLDER]` text with your content
3. Deploy to Vercel/Netlify (free tier)
4. Done!

---

## Customization Checklist

### Global Replacements
Find and replace these throughout the file:

- `[Your Service Name]` → Your actual service name
- `[YOUR_STRIPE_CHECKOUT_URL]` → Your Stripe checkout link
- `[STARTER_CHECKOUT_URL]` → Stripe link for Starter tier
- `[PRO_CHECKOUT_URL]` → Stripe link for Pro tier
- `[SCALE_CHECKOUT_URL]` → Stripe link for Scale tier

### Hero Section
- **Headline:** `[Solve Problem X] in [Timeframe Y]`
  - Example: "Analyze Customer Sentiment in Seconds"
  - Formula: [Action Verb] + [Benefit] + [Speed]

- **Subheadline:** 1-2 sentences explaining what you do
  - Example: "Automatically detect urgent, angry, or at-risk customer emails using AI. Never miss a critical issue again."

### Benefits Section
**Benefit 1: Time Saving**
- Icon: ⚡ (can change)
- Heading: What time you save
- Body: Specific numbers ("Analyze 1,000 emails in seconds")

**Benefit 2: Money Saving**
- Icon: 💰 (can change)
- Heading: What money you save or make
- Body: Specific numbers ("Reduce support costs by 40%")

**Benefit 3: Risk Reduction**
- Icon: 🔒 (can change)
- Heading: What risk you eliminate
- Body: Specific outcome ("Never miss urgent issues")

### Pricing Section
Update these for each tier:

**Starter Tier:**
- Price: $9/month (or your price)
- Features: List 4-5 features included
- CTA link: Your Stripe checkout URL

**Pro Tier (Featured):**
- Price: $29/month (or your price)
- Badge: "Most Popular" (keep this)
- Features: List 5-6 features (more than Starter)
- CTA link: Your Stripe checkout URL

**Scale Tier:**
- Price: $99/month (or your price)
- Features: List 5-6 premium features
- CTA link: Your Stripe checkout URL

### FAQ Section
Customize the 5 questions:
1. How does the free trial work? (Update trial length if needed)
2. Can I change plans later?
3. What payment methods do you accept?
4. Do you offer refunds? (Update refund policy)
5. Is there a setup fee?

Add more questions if needed - just copy the `faq-item` div.

### Footer CTA
- **Headline:** "Ready to [Achieve Outcome]?"
  - Example: "Ready to Stop Missing Urgent Emails?"
- **Subheadline:** "Join [X] customers..." (use real number or "Join hundreds of customers")

### Footer
- Update copyright year
- Add your links:
  - Terms of Service page
  - Privacy Policy page
  - Support email

---

## Color Customization

Want different colors? Update these CSS values:

**Primary Blue:** `#2563eb` → Your brand color
**Purple Gradient:** `#667eea` and `#764ba2` → Your gradient colors
**Green Checkmarks:** `#10b981` → Your accent color

Find/replace these hex codes in the `<style>` section.

---

## Deployment

### Vercel (Recommended)
1. Create GitHub repo
2. Push your `index.html` (rename saas-simple.html)
3. Connect repo to Vercel
4. Deploy (30 seconds)

### Netlify
1. Drag and drop your HTML file into Netlify
2. Done!

### Custom Domain
Both Vercel and Netlify offer free custom domains:
- Add your domain in their dashboard
- Update DNS records (they'll tell you how)
- SSL certificate auto-configured

---

## A/B Testing Headlines

Test these headline formulas:

1. **Outcome-focused:** "[Achieve X] Without [Pain Y]"
   - "Manage Customer Sentiment Without Reading Every Email"

2. **Time-based:** "[Do X] in [Time Y]"
   - "Understand Customer Mood in 3 Seconds"

3. **Comparison:** "The [Simple/Fast/Cheap] Way to [Outcome]"
   - "The Simple Way to Prioritize Support Tickets"

4. **Question:** "Struggling with [Problem]? We Can Help."
   - "Drowning in Customer Emails? We Can Help."

5. **Social proof:** "Join [X] Teams Already [Outcome]"
   - "Join 500+ Teams Never Missing Urgent Emails"

Test 2-3 headlines over 1 week. Pick the winner.

---

## Landing Page Checklist

Before going live, verify:

- [ ] All `[PLACEHOLDER]` text replaced
- [ ] Stripe checkout links work (test in incognito)
- [ ] Free trial terms are accurate (length, credit card requirement)
- [ ] Pricing matches your Stripe products
- [ ] FAQ answers are correct
- [ ] Support email exists and is monitored
- [ ] Mobile responsive (check on phone)
- [ ] Load time <2 seconds (use PageSpeed Insights)
- [ ] Terms of Service and Privacy Policy pages exist
- [ ] Meta description filled in (for SEO)

---

## Tips for Higher Conversion

1. **Add social proof:** "Join 100+ users" (even if starting at 0, say "Join early adopters")
2. **Use testimonials:** Add customer quotes above pricing
3. **Show screenshots:** Add product images in Benefits section
4. **Add urgency:** "Limited spots for beta users" (if true)
5. **Clear CTA:** Every section should end with a CTA button

---

## Advanced: Adding Analytics

Track your landing page performance:

### Google Analytics
Add before `</head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### Track Conversions
Add to each CTA button:
```html
<a href="[URL]" onclick="gtag('event', 'click', {event_category: 'CTA', event_label: 'Start Trial'});">
```

---

## Getting Help

Stuck? Common issues:

**Problem:** Landing page looks broken on mobile
- **Fix:** Open in Chrome DevTools, toggle mobile view, check padding/font sizes

**Problem:** Stripe checkout doesn't work
- **Fix:** Verify you copied the full checkout URL (should start with https://checkout.stripe.com/)

**Problem:** Colors look off
- **Fix:** Use hex color codes (#2563eb format), not color names ("blue")

**Problem:** Text overflows on small screens
- **Fix:** Reduce font-size in @media queries OR shorten text

---

## Next Steps

1. Deploy your landing page (Day 5)
2. Share the URL in 3 places (Day 7)
3. Track visitors with Google Analytics
4. A/B test headlines weekly
5. Add testimonials as you get customers

**Goal: 5% landing page → trial conversion rate**

---

**Landing page done? Great. Now get traffic to it (see Playbook Day 8-14).**
