# Tulip Moments Beginner-Safe Website Structure Brief

**Project:** Tulip Moments  
**Website type:** Existing static single-page preorder website  
**Repo:** `pav4o71/tulip-moments`  
**Public site:** `https://pav4o71.github.io/tulip-moments/`  
**Purpose:** Keep an accurate, beginner-safe roadmap for improving the existing website without rebuilding it.

---

## 0. Important Safety Rule

This website is already built. Do not treat it as a new project.

For now:

- Use HTML and CSS only.
- Do not add JavaScript.
- Do not edit `script.js`.
- Do not add frameworks, libraries, or build tools.
- Do not rebuild the site.
- Do not add payment handling.
- Do not add backend submission.
- Do not force push.
- Do not push unless the user explicitly asks.

The current site should be improved gradually through small, reviewable changes.

---

## 1. Current Project Reality

The current project contains:

- `index.html`
- `style.css`
- `script.js`
- `images/`
- `AGENTS.md`
- `WEBSITE_STRUCTURE_PLAN.md`

The website is a static single-page site deployed with GitHub Pages.

`script.js` exists and is empty. No JavaScript behavior is implemented. It should stay empty unless JavaScript is explicitly approved later.

### Current section order

1. Skip link
2. Navigation
3. Hero (`#home`)
4. Trust Promise
5. Why Tulips
6. How Preorder Works
7. OFW / long-distance sender
8. Packages (`#packages`)
9. What Every Bouquet Includes
10. Preorder form (`#preorder`)
11. FAQ (`#faq`)
12. Final CTA
13. Footer (`#footer`)

### Current navigation

- Home -> `#home`
- Packages -> `#packages`
- Preorder -> `#preorder`
- FAQ -> `#faq`

### Additional links

- Skip link -> `#preorder`
- Hero primary button -> `#preorder`
- Hero secondary button -> `#footer`
- OFW CTA -> `#preorder`
- Package buttons -> `#preorder`
- Final CTA -> `#preorder`
- Footer CTA -> `#preorder`

Keep all existing IDs and links safe.

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

Tone:

- calm
- warm
- precise
- reassuring
- premium without sounding fake
- clear about what is confirmed before payment

Avoid fake luxury, fake urgency, fake reviews, unapproved prices, unapproved delivery areas, guaranteed-perfect wording, and "DM for price" style uncertainty.

---

## 3. Completed Improvements

These improvements are present in the current website.

### Hero and trust messaging

- The hero headline and subheadline have been polished.
- The hero trust strip is present:

```text
Preview before delivery • Clear stem count • Delivery confirmation • Human support
```

- The Trust Promise focuses on seeing the bouquet before delivery.
- The Trust Promise lists the preview photo, stem count, message card confirmation, delivery confirmation, and human support.
- The Why Tulips copy explains why tulips feel thoughtful, soft, rare, and intentional.

### How Preorder Works

- A five-step flow covers choosing a bouquet, sharing details, confirming the preorder, receiving a preview, and delivery confirmation.
- A reassurance line explains that preordering supports sourcing, preparation, preview, and proper delivery.

### Packages

- Package guidance text is present.
- Package buttons retain their styling and link to `#preorder`.
- Package links do not automatically select a form option.
- Mini has 10 stems and the `Sweet Gesture` badge.
- Classic has 20 stems and the `Signature Choice` badge.
- Grand has 30 stems and the `Milestone Statement` badge.
- Classic has featured styling and the recommendation for most first-time orders.

### Bouquet inclusions

The inclusions section lists:

- Fresh tulips
- Clear stem count
- Elegant wrapping
- Personalized message card
- Bouquet preview before delivery
- Delivery confirmation after arrival
- Human support for preorder questions
- Delivery details confirmed before payment

### Preorder form

- The introduction explains that availability, delivery details, and next steps are confirmed before payment.
- A delivery note says selected Metro Manila delivery availability is confirmed before payment.
- Required and optional fields are identified.
- The form is grouped into Your Details, Recipient and Delivery, and Bouquet Preferences.
- Helper text is present for the form fields.
- Four required confirmation checkboxes are grouped semantically.
- The submit button says `Send Preorder Request`.
- A note explains that the form collects preorder details only and asks customers to message afterward.
- The form has no configured `action` or `method`.
- No backend submission behavior is implemented.

### FAQ, final CTA, SEO, and accessibility

- The static FAQ wording has been polished and answers seven current topics.
- The final CTA headline and supporting text have been polished.
- The SEO title and meta description are implemented.
- A skip link, sticky navbar, anchor offsets, focus styles, semantic form structure, responsive styling, and reduced-motion support are present.

---

## 4. Buyer Fears the Website Should Answer

| Buyer Fear | Safe Website Answer |
|---|---|
| Will the bouquet look good? | Mention the preview photo before delivery. |
| Will it look smaller than expected? | Keep clear stem counts on package cards. |
| Can I trust this brand? | Use calm process wording, delivery confirmation, and human support. |
| What if I order from abroad? | Keep OFW/long-distance reassurance prominent. |
| What if tulip colors are unavailable? | Mention availability confirmation and backup color. |
| Why preorder? | Explain sourcing, preparation, preview, and delivery care. |
| Will delivery be handled properly? | Confirm delivery details and availability before payment. |
| Is it worth it? | Explain the complete gifting experience, not just stems. |

---

## 5. Current Section Strategy

### 1. Hero

Current headline:

```text
Rare tulips, shown before they're delivered.
```

The primary button links to `#preorder`, the secondary button links to `#footer`, and the trust strip is implemented.

### 2. Trust Promise

The section directly explains the preview-before-delivery promise. Keep all promises truthful and do not use fake proof, screenshots, or reviews.

### 3. Why Tulips

The current copy positions tulips as thoughtful, soft, rare, and intentional. Do not add unsupported claims.

### 4. How Preorder Works

The five-step flow and reassurance line are implemented. Keep this section static.

### 5. OFW / Long-Distance

The section mentions a preview before delivery and confirmation after arrival. Only mention contact channels that are genuinely available.

### 6. Packages

The current packages are Mini with 10 stems, Classic with 20 stems, and Grand with 30 stems. Do not change stem counts or add prices without explicit approval.

### 7. What's Included

The section explains the approved gifting and reassurance details. Add a care guide only when the business is ready to provide one.

### 8. Preorder Form

The form is grouped semantically and includes markers, helper text, confirmations, and a static-form status note. Do not connect submission or change field IDs and names without explicit approval.

### 9. FAQ

Current topics:

1. Will I see the bouquet before delivery?
2. Why is this preorder only?
3. What does stem count mean?
4. Can I order from abroad?
5. What if my preferred tulip color is unavailable?
6. Can I choose the delivery time?
7. What is included in every bouquet?

### 10. Final CTA

The polished CTA links to `#preorder`.

### 11. Footer

The footer has the `#footer` ID and its CTA links to `#preorder`.

---

## 6. Future Tasks

Keep these as future tasks only when the required information or approval is available:

- Recipient-unavailable FAQ, after policy wording is approved
- Real public contact links
- Real proof photos or gallery
- Customer reviews with consent
- Tulip care guide
- Form submission connection
- Any future JavaScript behavior

Never use fake reviews, fake order screenshots, fake delivery confirmations, private customer information, or photos without permission.

---

## 7. Business Decisions Needed Before Website Changes

Ask the user before changing or adding:

- exact package prices
- any change from the current 10/20/30 stem counts
- exact delivery areas and fees
- payment methods and instructions
- real public contact links
- exact order deadlines
- same-day delivery policy
- real proof photos or gallery
- customer reviews with consent
- tulip care guide
- form submission connection
- any future JavaScript approval

---

## 8. Features Not Approved

Do not implement without separate approval:

- multi-step form
- FAQ accordion
- checkout or payment system
- sticky mobile CTA
- automatic package selection
- proof gallery
- customer review screenshots
- backend form submission
- any JavaScript behavior
- any framework, library, or build system

The current project is a beginner-built static HTML/CSS website. Do not rebuild it.

---

## 9. Future Public-Safe Planning Page

A real private admin panel is not approved. Do not add authentication, saved state, backend behavior, order management, or admin panel functionality.

A possible future `internal-plan.html` could only be a static HTML/CSS public-safe planning page. Do not create this page yet and do not add JavaScript.

If a file is published in the GitHub Pages repository, it may be publicly reachable even when it is not linked from the website. Do not describe the page as private, secure, hidden, or protected.

The page must not contain:

- customer or order data
- passwords or payment information
- supplier notes
- private pricing or private business details
- secrets or anything sensitive

Suitable content is limited to public-safe checklists, launch tasks, content tasks, and placeholders for business decisions that still need approval.

The page should not be linked from the public navbar, footer, or other website sections unless explicitly approved later.

---

## 10. Codex Workflow for Every Task

### Step 1 - Planning only

Read `AGENTS.md` and `WEBSITE_STRUCTURE_PLAN.md` first. Do not edit files. Report safety, files, placement, CSS needs, risks, and a short plan.

### Step 2 - Diff only

After approval, return a unified diff only. Do not edit files, create a pull request, or push.

### Step 3 - Apply only after review

Apply only the approved diff. Do not make extra improvements or push.

### Step 4 - User commits and pushes

Commit and push only after visual review and explicit instruction.

---

## 11. Final Website Rule

Every major section should answer one of these questions:

1. Why tulips?
2. Why this brand?
3. Will it look good?
4. Will it arrive correctly?
5. Is it worth the price?
6. Can I trust the process?
7. What should I do next?

If a future section does not answer one of these questions, simplify it or skip it.
