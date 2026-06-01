# Tulip Moments Beginner-Safe Website Structure Brief

**Project:** Tulip Moments  
**Website type:** Existing static single-page preorder website  
**Repo:** `pav4o71/tulip-moments`  
**Public site:** `https://pav4o71.github.io/tulip-moments/`  
**Purpose of this file:** Use this as the safe Codex-ready roadmap for continuing the current website without rebuilding it.

---

## 0. Important Safety Rule

This website is already built. Do not treat it as a new project.

For now:

- Use HTML and CSS only.
- Do not add JavaScript.
- Do not edit `script.js`.
- Do not add frameworks, libraries, build tools, React components, TypeScript files, or data folders.
- Do not rebuild the site.
- Do not turn the site into a multi-page app yet.
- Do not create a multi-step form yet.
- Do not add payment handling.
- Do not add backend submission.
- Do not force push.
- Do not push unless the user explicitly asks.

The current site should be improved gradually through small, reviewable changes.

---

## 1. Current Project Reality

The current project is a simple static website with:

- `index.html`
- `style.css`
- `script.js`
- `images/`

The website is deployed with GitHub Pages.

`script.js` exists but should stay empty unless JavaScript is explicitly approved later.

The site currently includes:

1. Navigation
2. Hero section
3. Trust Promise section
4. Why Tulips section
5. How Preorder Works section
6. Packages section
7. OFW / long-distance sender section
8. Bouquet inclusions section
9. Preorder form section
10. FAQ section
11. Final CTA section
12. Footer

Keep the existing section IDs and navigation anchors safe, especially:

- `#home`
- `#packages`
- `#preorder`
- `#faq`
- `#footer`

---

## 2. Main Brand Direction

The website should feel like a premium reassurance system for emotionally important gifts, not a loud flower shop.

Core idea:

```text
Rare tulips. Real proof. Beautifully delivered.
```

Most important trust promise:

```text
You will see your bouquet before it is delivered.
```

Positioning:

```text
Premium preorder tulip bouquets in Metro Manila, prepared with care, shown before delivery, and confirmed after arrival.
```

Tone:

- calm
- warm
- precise
- reassuring
- premium without sounding fake
- clear about what is confirmed before payment

Avoid:

- fake luxury language
- fake urgency
- fake reviews
- unapproved prices
- unapproved delivery areas
- guaranteed-perfect wording
- “DM for price” style uncertainty

---

## 3. What We Have Already Improved

These improvements have already been made or are expected to be reflected in the current website before future tasks continue:

### Packages

- Package buttons now link to the preorder form using `href="#preorder"`.
- Package buttons keep their button styling.
- The Packages section includes buyer guidance:

```text
Mini for a sweet gesture. Classic for the signature gift. Grand for milestone moments.
```

### Preorder form clarity

- The preorder section explains that details are confirmed before payment:

```text
Send your details below. We will confirm availability, delivery details, and next steps before payment.
```

- A delivery availability note was added:

```text
Serving selected Metro Manila delivery areas by preorder. We will confirm delivery availability before payment.
```

- Submit button text changed from:

```text
Submit Preorder
```

to:

```text
Send Preorder Request
```

### Form helper text

Helper text has been added for:

- Contact Number
- Preferred Contact Channel
- Delivery Address
- Preferred Tulip Color
- Backup Tulip Color
- Delivery Date
- Message Card Text

These were HTML-only changes. They should not change form behavior.

### Workflow files

The project should include or plan to include:

- `AGENTS.md`
- `WEBSITE_STRUCTURE_PLAN.md`

These files are for Codex/project guidance only. They do not change the live website.

---

## 4. Buyer Fears the Website Should Answer

Every important section should answer at least one buyer fear.

| Buyer Fear | Safe Website Answer |
|---|---|
| Will the bouquet look good? | Mention preview photo before delivery. |
| Will it look smaller than expected? | Keep clear stem counts on package cards. |
| Can I trust this brand? | Use calm process wording, preview promise, delivery confirmation, and human support. |
| What if I order from abroad? | Keep OFW/long-distance reassurance prominent. |
| What if tulip colors are unavailable? | Mention availability confirmation and backup color. |
| Why preorder? | Explain freshness, sourcing, preparation, preview, and delivery care. |
| Will delivery be handled properly? | Ask for delivery details and confirm availability before payment. |
| Is it worth it? | Explain the complete gifting experience, not just stems. |

---

## 5. Current Section Strategy

This is the desired direction, adapted for the existing single-page HTML/CSS website.

### 1. Hero Section

Goal: explain the product, create desire, and introduce the trust promise.

Target headline for future review:

```text
Rare tulips, shown before they’re delivered.
```

Target subheadline for future review:

```text
Preorder premium tulip bouquets in Metro Manila — beautifully wrapped, personalized with your message, previewed before delivery, and confirmed after arrival.
```

CTA text should stay close to:

```text
Preorder Your Tulips
```

Secondary CTA can stay close to:

```text
Message Us for Help
```

Safe future improvement:

- Add or refine a small trust strip below the hero CTA.

Possible trust strip:

```text
Preview before delivery • Clear stem count • Delivery confirmation • Human support
```

Do not add prices yet unless approved.

---

### 2. Trust Promise Section

Goal: reduce fear of paying before seeing the bouquet.

Target headline:

```text
You’ll see your bouquet before it’s delivered.
```

Safe future improvement:

- Make this section more directly explain the preview-before-delivery promise.
- Keep it truthful.
- Do not use fake proof screenshots or fake reviews.

Possible bullets:

- Preview photo before delivery
- Clear stem count
- Message card confirmation
- Delivery confirmation
- Human support

---

### 3. Why Tulips Section

Goal: position tulips as intentional and less expected.

Target headline:

```text
When roses feel too expected, tulips feel chosen.
```

Safe future improvement:

- Improve the body copy so it explains why tulips feel thoughtful, soft, rare, and intentional.

Do not make claims that cannot be supported.

---

### 4. How Preorder Works Section

Goal: make the process feel simple and safe.

Target flow:

```text
Choose your bouquet → Confirm details → Reserve by preorder → Receive preview photo → Delivered with confirmation
```

Safe future improvement:

- Add one short reassurance line under the steps:

```text
Preordering helps us source, prepare, preview, and deliver each tulip bouquet properly.
```

Do not add JavaScript or progress interactions yet.

---

### 5. Packages Section

Goal: help buyers choose without overthinking.

Current package names are simple:

- Mini
- Classic
- Grand

The workbook suggests upgraded names:

- Mini Tulip Moment
- Classic Tulip Moment
- Grand Tulip Moment

Safe future improvement:

- Add small badges without changing package prices or stem counts:
  - Mini: `Sweet Gesture`
  - Classic: `Signature Choice`
  - Grand: `Milestone Statement`

Potential later improvement:

```text
Recommended for most first-time orders.
```

This could be added to Classic after review.

Important:

- Do not change current stem counts yet.
- Do not add workbook price ranges yet.
- Do not copy package data from the old advanced brief directly.
- Do not add automatic package selection yet.

The current website and workbook use different package stem counts. Treat package counts and prices as business decisions needing explicit approval.

---

### 6. OFW / Long-Distance Section

Goal: reassure people ordering from abroad or outside Manila.

Target headline:

```text
Sending from abroad? You won’t be left guessing.
```

Safe future improvement:

- Keep this section prominent.
- Mention preview photo before delivery and delivery confirmation after arrival.
- Mention accepted contact channels only if those are truly available.

Do not add a fake phone/chat visual unless the image is real or clearly labeled as a sample.

---

### 7. What’s Included Section

Goal: justify the premium feeling by explaining the full gifting experience.

Possible inclusions to review:

- Fresh tulips
- Elegant wrapping
- Personalized message card
- Clear stem count
- Bouquet preview photo before delivery
- Scheduled delivery support
- Delivery confirmation
- Human support

Only include a `Tulip care guide` if the business is ready to provide one.

---

### 8. Proof / Preview Gallery

Goal: build credibility later.

Do not add this yet unless real approved photos are available.

If sample photos are used, label them honestly:

```text
Sample bouquet shown for style and size reference.
```

Never use fake reviews, fake order screenshots, fake delivery confirmations, or private customer information.

---

### 9. FAQ Section

Goal: remove objections before the form.

Safe future improvement:

- Improve FAQ wording in the existing static FAQ section.
- Do not build an accordion yet because JavaScript is not approved.

Good FAQ topics:

1. Will I see the bouquet before delivery?
2. Why is this preorder only?
3. What does stem count mean?
4. Can I order from abroad?
5. What if my preferred tulip color is unavailable?
6. Can I choose the delivery time?
7. What happens if the recipient is unavailable?
8. What is included in every bouquet?

Do not add policies that are not approved.

---

### 10. Final CTA Section

Goal: close with emotion and reassurance.

Target headline:

```text
Send something rare, thoughtful, and reassuringly real.
```

Target body:

```text
Preorder your tulip bouquet today and see it before it is delivered.
```

Safe future improvement:

- Update final CTA copy after reviewing the current section.

---

## 6. Safe Next Website Tasks

Codex should suggest small tasks from this list first.

### Priority 1 — Hero trust strip

Add a small trust strip under the hero CTA.

Possible copy:

```text
Preview before delivery • Clear stem count • Delivery confirmation • Human support
```

Type: HTML/CSS only  
Risk: low  
Files likely: `index.html`, maybe `style.css`

---

### Priority 2 — Trust Promise wording polish

Improve the Trust Promise section headline/body to focus on the bouquet preview before delivery.

Type: HTML only  
Risk: low  
Files likely: `index.html`

---

### Priority 3 — How Preorder Works reassurance line

Add or improve a short sentence explaining why preorder helps.

Possible copy:

```text
Preordering helps us source, prepare, preview, and deliver each tulip bouquet properly.
```

Type: HTML only  
Risk: low  
Files likely: `index.html`

---

### Priority 4 — Package badges

Add small badges to package cards:

- Mini: `Sweet Gesture`
- Classic: `Signature Choice`
- Grand: `Milestone Statement`

Type: HTML/CSS only  
Risk: low to medium  
Files likely: `index.html`, maybe `style.css`

Do not change stem counts or prices.

---

### Priority 5 — Classic recommendation line

Add a short line to Classic:

```text
Recommended for most first-time orders.
```

Type: HTML only  
Risk: low  
Files likely: `index.html`

---

### Priority 6 — FAQ wording polish

Update existing static FAQ copy to better answer buyer fears.

Type: HTML only  
Risk: low  
Files likely: `index.html`

Do not create an accordion yet.

---

### Priority 7 — SEO metadata

Review and possibly update `<title>` and meta description.

Possible title:

```text
Premium Tulip Bouquets in Metro Manila | Preview Before Delivery
```

Possible meta description:

```text
Preorder premium tulip bouquets in Metro Manila. Every Tulip Moment includes elegant wrapping, message card, clear stem count, preview photo before delivery, and delivery confirmation.
```

Type: HTML only  
Risk: low  
Files likely: `index.html`

Do not keyword-stuff.

---

## 7. Business Decisions Needed Before Website Changes

Ask the user before changing or adding:

- final package stem counts
- final package prices
- exact delivery areas
- delivery fees
- payment methods
- payment instructions
- real public contact links
- exact order deadlines
- same-day delivery policy
- real proof photos
- customer reviews
- tulip care guide
- whether JavaScript is allowed later
- whether form submission should be connected later

---

## 8. Advanced Ideas to Save for Later

The original analysis brief includes some advanced ideas. These are useful later but should not be implemented now.

Do not implement yet:

- React components
- TypeScript package data files
- `/data/packages.ts`
- `/data/faqs.ts`
- multi-step form
- FAQ accordion
- checkout system
- payment blocks
- sticky mobile CTA
- automatic package selection
- multiple structured pages
- proof gallery
- customer review screenshots
- full image system
- backend form submission

Reason:

The current project is a beginner static HTML/CSS website. These ideas may require JavaScript, frameworks, new files, or business decisions.

---

## 9. Codex Workflow for Every Task

Every task should follow this workflow.

### Step 1 — Planning only

Prompt Codex with:

```text
READ-ONLY PLANNING MODE.

Read AGENTS.md and WEBSITE_STRUCTURE_PLAN.md first.

Do not edit files.
Do not apply changes.
Do not create a pull request.
Do not push to GitHub.

Suggest one small beginner-safe HTML/CSS-only improvement from the structure plan.
```

Codex should report:

1. Whether the change is safe.
2. Which file would change.
3. Exact placement.
4. Whether CSS is needed.
5. Risks to check.
6. Short step-by-step plan.

### Step 2 — Diff only

Only after approval:

```text
DIFF-ONLY MODE.

Do not apply changes automatically.
Do not edit files directly.
Do not create a pull request.
Do not push to GitHub.
Return a unified diff only.
```

### Step 3 — Apply only after review

Only after the diff is approved:

```text
APPLY APPROVED CHANGE ONLY.

Apply only the approved diff.
Do not make extra improvements.
Do not push to GitHub.
```

### Step 4 — User commits and pushes

After visual review:

```powershell
git status
git add <changed-files>
git commit -m "<clear commit message>"
git push
```

---

## 10. Final Website Rule

Every major section should answer one of these questions:

1. Why tulips?
2. Why this brand?
3. Will it look good?
4. Will it arrive correctly?
5. Is it worth the price?
6. Can I trust the process?
7. What should I do next?

If a future section does not answer one of these questions, simplify it or skip it.
