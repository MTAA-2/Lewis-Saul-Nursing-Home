# Resident Care (Nursing Home Neglect & Abuse) Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) landing page for the **nursing home neglect and abuse claims** sponsored by **Lewis Saul & Associates, P.C.**, built on the framework of your uploaded hospitality page (`index-8.html` / `style-8.css` — your edited version, published at justiceclaimsupport.com) and filled with content from **residentcareclaim.com**. Per your instruction, the law firm and disclaimer information were updated to this firm, and placeholder areas were left for pictures, branding, and parallax section backgrounds.

## Kept from your framework, unchanged

- Page structure, classes, the MTAA CIPA block script, and your form embed: `forms.mtaa.ai/f/nf_14bb49f057af4602b5676b8892df3c32`, in the overflow form card — the container hangs past the hero over the section below it, the frame scrolls internally with `overflow: auto` if the embed runs tall, and your mobile values are preserved.
- Your new Meta Pixel (`1238664640565416`), including the `fbq('track', "ViewContent")` line you added in this upload.
- Your design elements from the framework: the `.basic-imaga` photo style, the two parallax variants (`.section-parallax` on the hero, `.section-parallax-info1` on the middle section), the two-column image layout in the middle section, and the two-column attorney area.
- The call/text consent paragraph and the footer legal links to your `privacy-policy.html` and `disclaimer.html` on justicehelpnow.com, as in the framework.

## Phone number — none, and here's why

The page is **phoneless**. The live rendered residentcareclaim.com displays no phone number anywhere (checked top, middle, and footer, including text searches). The page's raw text does contain two numbers that never render — a "555-555-5555" under a "Call Today for a FREE Consultation" line (an obvious placeholder on their own page) and an "856-489-1515" in a footer block. Because the two conflict and neither is actually displayed, neither was used. If the firm confirms a number, it drops into the attorney block and footer in two spots.

## Placeholders left for you, as instructed

- **Branding:** the logo slots (hero eyebrow and footer) are `images/REPLACE-LOGO.png` — the framework's Andrews & Higgins logo image was removed. Drop the firm's logo file in with that name, or swap in a hosted URL. (Their logo is the text "LEWIS SAUL & ASSOCIATES"; the commented-out header also carries the firm name as a text logo.)
- **Pictures:** the middle section's side photo is `images/REPLACE-FACILITY-IMAGE.jpg`, and the attorney area has two photo slots, `images/attorney-photo-1.jpg` and `images/attorney-photo-2.jpg`, with `[Attorney Name]` / `[Title]` captions — the sample names no individual attorneys.
- **Parallax backgrounds:** both parallax blocks keep your code, overlay tint recolored to this site's dark navy (`--overlay-rgb: 21, 62, 126`, opacity 0.75), with image lines as placeholders — `YOUR-IMAGE-URL-HERE` (hero) and `YOUR-IMAGE-URL-HERE-2` (middle section) in `css/style.css`. Your framework URLs (the hospitality server photo and the gavel image) were not carried over.

## Colors and typeface

`css/style.css` is your uploaded `style-8.css` with **color values and heading font-family values only** changed (diff-verified), plus the two parallax placeholder URL lines. Palette sampled from the rendered residentcareclaim.com on 2026-11-04:

- Dark navy `#153e7e` (their mid-page section and logo tone) for the top bar, dark surfaces, footer, and headline color; medium blue `#3477e0` (their form-panel blue) through the hero gradient
- Blue `#3771cc` (their heading-rule accent) for kickers, headline accents, and checkmark circles (white checks); pale blue `#bcd4fb` for highlights on dark backgrounds
- Bright green `#03a410` CTA buttons with white text (their "Do I Qualify?" green; hover `#028a0d`)
- Pale gray `#ececec` (their footer tone) for the results band, light gray `#dedede` border lines, white page background
- Typeface: their headlines are a bold traditional serif (Times/Georgia-like), so the logo text, hero title, and section titles switch to Georgia / Times New Roman serif. Body text stays Inter/Arial sans, and the form heading stays sans — their form panel heading and button text are sans-serif too. Colors are close visual approximations sampled from the rendered page.

## Content (from residentcareclaim.com)

- Hero: their main headline — "Is Your Loved One a Victim of Nursing Home Neglect or Abuse? Compensation May Be Available." — with "You may qualify for a nursing home abuse and neglect lawsuit," the families-of-victims line, and their "No fees unless we win" offer language.
- We Represent the Families of Victims — dedicated nursing home neglect attorneys, a FREE claim review, "if your loved one is suffering from abuse, chances are that he or she is not the only one," and filing suit as possibly the only path to stopping the mistreatment.
- Some of the Results of Nursing Home Neglect — their list (starvation, dehydration, emotional abuse, financial abuse, over-medication, unauthorized medication, unnecessary or dangerous medication including opioid prescriptions) with their underpaid-staff / victims-of-their-environments copy, and an evaluation-does-not-guarantee note.
- What Neglect and Abuse Can Look Like — nine cards from their "Have you or a loved one suffered from any of the following?" list: bedsores and pressure ulcers, falls/fractures/broken bones, dehydration and malnutrition, medication errors, physical abuse and assault, sexual abuse, infections and sepsis, head and unexplained injuries, wrongful death.
- Hundreds of Millions Recovered — their claim ("recovered hundreds of millions of dollars for our clients through settlements and verdicts") with their honesty line: "Recovery is not guaranteed. Results may vary depending on the facts of your case."
- What We Look At — their practice line (complex nursing home litigation, consumer protection class actions, serious personal injury) and their form's relationship options: spouse, child, parent, guardian, executor of the injured person, or other.
- Disclaimer: their sponsor line verbatim — "THIS IS ATTORNEY ADVERTISING sponsored by Lewis Saul & Associates, P.C. located at 43 W. 43rd Street, Suite 351 New York, NY 10036." — plus the recovery-not-guaranteed line and the framework consent paragraph.

## Files

```
github-resident-care-landing-page/
├── index.html
├── css/style.css   (your framework CSS, colors + heading fonts only changed + parallax placeholders)
└── README.md
```

Publish the same way as the other GitHub pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root).
