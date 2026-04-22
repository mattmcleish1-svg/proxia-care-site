# Proxia Care — Website Update Specification

**Purpose:** This document gives you exact copy and structural changes to apply to `proxia-care-v2.html` to make it E2-application-ready and aligned with the Aqara-based product you've actually decided to build.

**Two principles guiding everything below:**
1. **Nothing fabricated.** Every claim must be defensible if a USCIS adjudicator questions it. No invented customer counts, no fake testimonials, no metrics you can't substantiate.
2. **Aligned with the business plan.** Pricing, service areas, and capabilities on the website must match what's in your E2 business plan. Contradictions get applications denied.

---

## SECTION 1 — Navigation Bar

**Current state:** Standard nav with logo, links, CTA button.

**Changes:**
- Add these nav links (so they exist for footer/internal linking even if hidden on mobile):
  - How It Works
  - What's Included
  - Pricing
  - FAQ
  - About
  - Contact
- CTA button text: **"Free Consultation"** (better than "Get Started" — sets expectation that this is a phone/in-person process, not a self-serve signup)

---

## SECTION 2 — Hero Section

**Keep:**
- The headline structure ("Always Home. Always Safe. Always Informed." or whatever you have)
- The tagline "Mom always says she's OK — now you can know" (this line is genuinely good, don't touch it)
- The visual layout

**Change the subhead to:**
> Phoenix's only locally-owned senior monitoring service, designed for the realities of Arizona living. Discreet in-home sensors, real-time family alerts, and 24/7 monitoring — without cameras, wearables, or anything for your loved one to remember.

**Change the primary CTA button to:**
> Schedule Free Consultation

**Change the secondary CTA / link to:**
> See How It Works

---

## SECTION 3 — Trust Strip (below hero)

**Current state:** "1,800+ Phoenix Families" / "<60s Alert Response" / "4.9★ Family Rated" — REMOVE THESE. They're fabricated and they're a real risk for your E2.

**Replace with these four trust signals, all of which are defensible:**

| Slot | Text |
|---|---|
| 1 | **Built for Phoenix** |
| 2 | **24/7 Monitoring** |
| 3 | **No Cameras. No Wearables.** |
| 4 | **Locally Owned & Operated** |

If your existing layout only fits 3, drop "24/7 Monitoring" temporarily until your monitoring partner contract (COPS or AvantGuard) is signed and in hand. Add it back the day the contract is signed.

---

## SECTION 4 — Tagline Banner (the teal section with the big quote)

**Keep:** the banner exists, the styling, the visual treatment.

**Replace the quote text with:**
> "We don't replace family. We give families the *peace of mind* to keep loving without the worry."

**Replace the sub-text with:**
> Phoenix-based. Family-built. Built for Arizona's seniors and the families who love them.

**CTA button text:**
> Schedule Free Consultation

---

## SECTION 5 — How It Works (3 steps)

**Replace the entire section content with:**

### Section heading
> **How Proxia Care Works**

### Subheading
> From your first call to your loved one's first night protected — typically under one week.

### Step 1
**Title:** Free In-Home Consultation
**Body:** A Proxia Care specialist visits your loved one's Phoenix-area home, walks through their daily routine room by room, and designs a personalized monitoring plan around their actual habits and risks. Completely free. Zero obligation. About 45 minutes.

### Step 2
**Title:** Same-Day Professional Installation
**Body:** We install the complete sensor system in under 2 hours. No drilling, no wall damage, no construction. Discreet sensors placed exactly where they're needed, configured for your loved one's specific routine. We test every alert with your family before we leave.

### Step 3
**Title:** 24/7 Monitoring Begins Immediately
**Body:** Every family member gets the Proxia Care app. Real-time alerts begin the moment installation is complete. Your first weekly Wellness Report arrives within 7 days, and our monitoring team is watching the system around the clock.

---

## SECTION 6 — Alerts / What We Detect

**Replace the entire section with these 5 alert types** (if you currently have 6, drop the weakest one — likely "medication adherence" since you can't deliver it on day one):

### Section heading
> **What Proxia Care Watches For**

### Subheading
> Real protection for the situations that actually put Phoenix seniors at risk.

### Alert 1: Fall Detection
Ceiling-mounted radar sensors detect falls within seconds in your loved one's highest-risk rooms — typically the bathroom, bedroom, and main living area. No cameras. No wearable required. The moment a fall is detected, designated family members are alerted instantly and our monitoring team responds.

*Powered by enterprise-grade millimeter-wave radar — the same technology used in modern automotive safety systems.*

### Alert 2: Phoenix Heat Protection
The protection no national service offers. Multiple temperature sensors throughout the home plus a power monitor on the AC unit. If indoor temperatures rise above safe thresholds, if the AC fails, or if exterior doors are left open during peak heat — your family knows in minutes, not hours. Built specifically for Arizona summers, when heat-related emergencies among seniors spike sharply.

*Phoenix-specific monitoring built for Arizona's realities.*

### Alert 3: Wandering & Nighttime Activity
Door sensors and motion detectors learn your loved one's normal patterns — when they wake, when they leave the house, when they're up at night. Any meaningful deviation from their baseline triggers an alert. If the front door opens at 3 AM, you'll know. If they haven't appeared in their usual morning kitchen, you'll know.

### Alert 4: Routine Anomaly Alerts
Subtle changes — fewer trips to the kitchen, longer time in bed, less movement during the day — can be early signals worth investigating. Our system learns your loved one's normal week and flags meaningful changes for your family. Not a medical diagnosis — an early signal that something may be worth a check-in or a conversation with their doctor.

### Alert 5: Water Leak & Home Hazard Detection
Sensors under sinks and near appliances catch leaks the moment they start. A leaking water heater or burst pipe in a senior's home can become a $20,000 problem overnight. We catch it in minutes — and your family is notified just like any other alert.

---

## SECTION 7 — Weekly Wellness Report (the Dorothy mockup)

**Keep:** The visual mockup, the styling, the personal feel.

**Change the metrics shown** to ones you can actually deliver:

| Metric | What it shows |
|---|---|
| **Sleep Quality** | Hours, sleep stages, breathing patterns (from under-mattress sensor — Complete tier and above) |
| **Daily Activity** | Movement throughout the home, by room |
| **Routine Consistency** | This week vs. baseline — flags meaningful deviations |
| **Home Environment** | Temperature ranges, any heat events, AC status |
| **Alert Summary** | Everything that triggered a notification this week |

**Remove from the mockup if currently shown:**
- Gait pattern / gait analysis (Aqara FP2 doesn't deliver this; the FP400 might when it ships, but don't promise it yet)
- Medication adherence (not in the base hardware package)
- Any specific medical condition predictions ("UTI risk," "Parkinson's signs," etc.)

**Section heading:**
> **Your Weekly Wellness Report**

**Subheading:**
> Every Sunday morning, every family member receives a clear, honest snapshot of how your loved one's week actually went. No medical jargon. No alarming over-interpretation. Just a calm, useful picture of the people you love.

---

## SECTION 8 — NEW SECTION: "What's Actually In Your Loved One's Home"

**This section doesn't exist on your site yet — add it.** Place it after the Alerts section and before the Weekly Report section. This is the section that converts skeptical adult children because it tells them exactly what gets installed.

### Section heading
> **What's Actually Installed in the Home**

### Subheading
> Discreet, professional-grade equipment from world-leading smart home manufacturer Aqara, configured by a Proxia Care specialist for your loved one's specific home and routine.

### Equipment list (use icons or simple bullets):

- **Smart Home Hub** — The brain of the system. Centrally located, connects every sensor, manages alerts. Continues working through internet outages.
- **Two Radar Presence Sensors** — Ceiling-mounted in the bathroom and primary living area for fall detection. No camera, no recording — just radar.
- **Motion Sensors (4–6 throughout the home)** — Discreet sensors that learn your loved one's daily movement patterns.
- **Door & Window Sensors** — Front door, back door, bedroom door — tracks entries, exits, and unusual nighttime activity.
- **Temperature & Humidity Sensors** — Two units monitoring the home environment, critical for Arizona summers.
- **AC Power Monitor** — Detects AC failures the moment they happen, before the home becomes unsafe.
- **Water Leak Sensors** — Under-sink and near appliances, catching leaks instantly.
- **Under-Mattress Sleep Sensor** *(Complete tier and above)* — FDA-cleared sleep tracking with apnea detection. Nothing to wear, nothing to remember.
- **Cellular Backup** *(Premium tier)* — Monitoring continues even if home internet goes down.

### Callout box (highlighted styling):
> **Total install time: under 2 hours. No drilling. No wall damage. No construction. No disruption to your loved one's home.**

---

## SECTION 9 — Why Proxia Care (replace the existing 6-benefit section)

**Cut from 6 to 4 sharper benefits.**

### Section heading
> **Why Phoenix Families Choose Proxia Care**

### Benefit 1: Built for Arizona
We're the only senior monitoring service designed around Phoenix's real risks. AC failures, extreme heat events, and the specific challenges of desert living are built into how we monitor. National providers don't think about your loved one's July afternoons. We do.

### Benefit 2: No Wearables. No Cameras. Real Privacy.
Your loved one doesn't have to wear anything, charge anything, or remember anything. There are no cameras in any room of the home. Just discreet sensors that learn their routine and protect them quietly.

### Benefit 3: A Local Phoenix Team
When something happens, you're talking to a local Phoenix specialist who knows your family — not a 1-800 call center across the country. We do the consultation in person. We do the install ourselves. We answer when you call.

### Benefit 4: Transparent Pricing. Month-to-Month.
No long-term contracts. No hidden fees. No surprise renewals. If Proxia Care isn't right for your family, you can cancel with 30 days' notice. We earn your trust every month.

---

## SECTION 10 — NEW SECTION: Pricing

**Add a real pricing section** — your E2 needs this. Place it after "Why Proxia Care" and before testimonials/form.

### Section heading
> **Simple, Transparent Pricing**

### Subheading
> Three tiers. No contracts. Month-to-month. Phoenix-area service.

### Essential — $179/month
*+ $199 one-time installation*
- Two radar presence sensors (bathroom + main room)
- Motion sensors throughout the home
- Door & window sensors
- Temperature and humidity monitoring
- AC failure detection
- Water leak protection
- Smart home hub
- Family app (unlimited family members)
- Weekly Wellness Report
- 24/7 monitoring

### Complete — $249/month *(Most Popular)*
*+ $299 one-time installation*
- Everything in Essential, plus:
- Third radar presence sensor (additional high-risk room)
- Withings Sleep Analyzer with FDA-cleared sleep apnea detection
- Activity baseline reports with trend tracking
- Priority alert response
- Monthly check-in call with your Proxia Care specialist

### Premium — $349/month
*+ $399 one-time installation*
- Everything in Complete, plus:
- Fourth radar presence sensor (whole-home coverage)
- Quarterly in-home wellness review by your specialist
- Direct line to a dedicated Care Coordinator
- Monthly summary sent to your loved one's physician (with your consent)
- Outdoor heat monitoring for patios and garages
- Cellular backup for internet outages

### Footer line under pricing:
> *All plans are month-to-month. No contracts. Cancel anytime with 30 days' notice. Phoenix metro area only. Installation typically scheduled within 5–7 days of consultation.*

---

## SECTION 11 — Testimonials

**Current state:** Three fabricated testimonials. These are a real problem for E2.

**Replace with one of these two options:**

### Option A (recommended): Honest "we're new" framing
Replace the testimonial cards with a single, full-width section:

> **Customer testimonials coming soon.**
>
> Proxia Care is currently onboarding our first Phoenix families. We'll publish testimonials as our customers experience the service and choose to share their stories — never before, and never invented.

### Option B: Founder voice / mission statement
Replace the testimonials with three cards that are actually statements of your own commitment, clearly attributed to you as the founder:

**Card 1:**
> "I started Proxia Care because I watched my own family struggle with the gap between 'mom's still independent' and 'mom needs full-time care.' That gap is years long, and it's terrifying. We exist to fill it."
> — [Your Name], Founder

**Card 2:**
> "Phoenix is unique. Our heat is unique. Our retirement community is unique. The monitoring services families actually need here can't be the same generic product sold in Minneapolis."
> — [Your Name], Founder

**Card 3:**
> "Every family deserves to know that someone local is watching. Not a call center. Not an algorithm alone. A real person, in Phoenix, who answers the phone."
> — [Your Name], Founder

Either approach is far stronger for E2 than fake reviews. Pick whichever feels more honest to you.

---

## SECTION 12 — NEW SECTION: FAQ

**Add an FAQ section** before the contact form. Use a clean accordion-style or simple Q/A list.

### Section heading
> **Common Questions from Phoenix Families**

### Q1: Will my loved one have to wear anything?
No. Proxia Care uses discreet in-home sensors. No wearables, no pendants, no buttons to press. Your loved one's daily life doesn't change.

### Q2: Are there cameras in the home?
No cameras anywhere in the home. Our system uses millimeter-wave radar (the same technology used in modern automotive safety systems) to detect presence and falls without recording video or audio.

### Q3: What happens when an alert fires?
Our 24/7 monitoring team is notified immediately. Within seconds, designated family members receive a push notification, SMS, and call as needed. For confirmed emergencies, our team can dispatch local emergency services directly.

### Q4: What if the internet goes out?
Our system continues monitoring locally even when internet drops. Critical alerts are sent via cellular backup (included in Premium, available as add-on for other tiers), so your loved one stays protected through outages and storms.

### Q5: How long does installation take?
Under 2 hours, typically. No drilling, no construction, no disruption.

### Q6: What's the contract length?
All plans are month-to-month. Cancel anytime with 30 days' notice.

### Q7: Do you serve all of Greater Phoenix?
Yes. Phoenix, Scottsdale, Paradise Valley, Mesa, Gilbert, Chandler, Tempe, Glendale, Peoria, Sun City, Sun City West, and surrounding communities throughout Maricopa County.

### Q8: What if my loved one isn't comfortable with technology?
That's the point. Proxia Care is designed to be invisible to them. They don't need to use an app, press a button, or remember anything. The technology works around their life, not the other way around.

---

## SECTION 13 — Contact Form Section

**Keep:** The form layout, the sticky checklist on the left.

**Update the section heading:**
> **Schedule Your Free In-Home Consultation**

**Update the subheading:**
> A Proxia Care specialist will visit your loved one's home, walk through their daily routine, and design a personalized monitoring plan. No cost, no obligation, about 45 minutes.

**Update the checklist on the left to:**
- ✓ Free, no-obligation consultation
- ✓ Phoenix metro area service
- ✓ Personalized plan for your loved one's home
- ✓ Same-week installation typically available
- ✓ Month-to-month — no long-term contracts
- ✓ Local Phoenix team, not a national call center

**Form fields (keep these):**
- Your Name
- Your Email
- Your Phone
- Your Loved One's City (Phoenix / Scottsdale / Mesa / etc. dropdown)
- Best Time to Reach You
- Tell Us About Your Situation (textarea)

**Submit button text:**
> Request My Free Consultation

**Below submit button (small text):**
> We'll respond within one business day. Your information stays with Proxia Care — we never sell or share family data.

---

## SECTION 14 — Footer

**Add to footer:**

### Column 1: Proxia Care
- About
- How It Works
- Pricing
- FAQ
- Contact

### Column 2: Service Areas
- Phoenix
- Scottsdale
- Mesa
- Gilbert
- Chandler
- Tempe
- Glendale
- Sun City
- Peoria
- Paradise Valley

### Column 3: Contact
- Phone: [Your Google Voice number]
- Email: hello@proxiacare.com (or whatever you set up)
- Address: [Your Phoenix business address — co-working space is fine, PO Box is not]
- Hours: Consultations by appointment, 7 days a week

### Column 4: Legal
- Privacy Policy
- Terms of Service
- Press

### Bottom line:
> © 2026 Proxia Care, LLC. Phoenix, Arizona. Proxia Care is not a medical device or emergency response service. For life-threatening emergencies, always dial 911.

That last disclaimer line matters legally — keep it.

---

## SECTION 15 — Pages You Need to Add Beyond the Landing Page

For E2, single-landing-page sites look thin. Add these as separate pages, even if minimal:

### /about
- Your founder photo
- Your story (why you started Proxia Care, your background, why Phoenix)
- Your connection to senior care (personal experience, family motivation)
- Your commitment statement
- ~300–500 words is plenty

### /contact
- Real Phoenix phone number
- Email address
- Physical business address
- Map embed of your business location
- Contact form

### /service-areas
- List every zip code you serve
- Brief paragraph for major cities (Scottsdale, Mesa, Sun City — each gets a sentence about why Proxia Care fits that community)
- Helps SEO, helps E2

### /privacy
Standard privacy policy. Use a generator like Termly or iubenda. Customize the company name and contact info. Should mention:
- What data you collect
- That sensor data is encrypted
- That you don't sell family data
- That data is stored on US servers
- How families can request deletion
- HIPAA disclaimer (you're not a covered entity, but you treat data with care)

### /terms
Standard terms of service. Same generators work. Should cover:
- Service description
- Month-to-month billing
- Cancellation policy (30 days)
- Equipment ownership (you retain ownership, customer returns at end of service)
- Liability disclaimers (not a medical device, not 911)
- Phoenix metro service area

### /press
Empty or minimal. Just: "Press inquiries: press@proxiacare.com" — signals legitimacy.

---

## CRITICAL E2 ALIGNMENT CHECKLIST

Before submitting your E2 packet, verify every one of these:

- [ ] No fabricated customer counts anywhere on the site
- [ ] No fabricated testimonials anywhere on the site
- [ ] Pricing on website matches pricing in business plan
- [ ] Service area on website matches service area in business plan
- [ ] Year-one customer projections in business plan are consistent with website's "we're new" framing
- [ ] Real Phoenix phone number (not blank, not 555-0100)
- [ ] Real Phoenix business address (not PO Box)
- [ ] Privacy Policy page exists and loads
- [ ] Terms of Service page exists and loads
- [ ] About page tells your real founder story
- [ ] Every link in the navigation works
- [ ] Every link in the footer works
- [ ] Site loads on mobile without breaking
- [ ] No "Lorem ipsum" or placeholder text anywhere
- [ ] Site reflects Aqara as the technology foundation in language ("enterprise-grade smart home technology" is fine; you don't have to name Aqara on the site, but if you do, spell it correctly)
- [ ] All medical/health claims are appropriately hedged — no "diagnoses," no "predicts UTI," no "detects Parkinson's"
- [ ] 911 disclaimer appears at least once (footer is fine)

---

## EXECUTION ORDER (next 7 days)

**Day 1 — Tuesday:** Strip the fabricated stats and testimonials. Update hero, trust strip, How It Works, and Why Proxia Care sections.

**Day 2 — Wednesday:** Update Alerts section, Weekly Report mockup, and add the new "What's Installed" section.

**Day 3 — Thursday:** Add the Pricing section and the FAQ section.

**Day 4 — Friday:** Build the four supporting pages (About, Contact, Service Areas, Privacy/Terms).

**Day 5 — Saturday:** Mobile testing, link checking, copy proofreading, screenshot capture for E2 packet.

**Day 6–7 — Weekend:** Buffer for fixes and polish. Send the link to one friend who isn't familiar with the project and ask them to find anything confusing or unconvincing. Fix what they find.

---

## ONE LAST THING

The website's job for your E2 is not to be the best landing page on the internet. Its job is to look like a real, operating, professional business that an investor would actually be running. That bar is much lower than "perfect marketing site" and much higher than "wireframe with placeholder text." Aim for the middle: clean, honest, complete, and consistent with everything else in your application packet.

You can always make it more beautiful in month 3. You can't unsubmit a contradicted E2.
