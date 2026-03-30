# SEO Action Plan: Mountain View Commons
## www.mtnviewcommonsut.com
### Generated: March 25, 2026

---

## Priority: CRITICAL (Fix Immediately)

These issues are blocking indexing, hurting rankings, or could cause penalties.

### 1. Add Meta Descriptions to All 13 Pages
**Impact:** High | **Effort:** 1-2 hours

Every page is missing a meta description. Google auto-generates snippets that are often poor. Write unique, compelling descriptions (150-160 characters) for each page.

**Recommended meta descriptions:**

| Page | Suggested Meta Description |
|------|---------------------------|
| Homepage | "Mountain View Commons — 43 mixed-use units in Heber City, UT. Residential, commercial & warehouse space near Park City. Starting from [price]. Schedule a tour." |
| Mixed-Use Real Estate | "Explore flexible mixed-use property options at Mountain View Commons. Live, work & play in Heber City, Utah. Residential, retail, warehouse & studio zoning." |
| The Hideout | "The Hideout — 1-bedroom unit with garage, office & living space. 4,920 sq ft across 3 floors at Mountain View Commons, Heber City. View floor plans." |
| The Frontier | "The Frontier — 2-bedroom layout with expansive garage for snowmobiles & gear. 3 floors at Mountain View Commons, Heber City. View floor plans & pricing." |
| The Mercantile | "The Mercantile — professional workspace with garage, open floor plan & private office. 3 floors at Mountain View Commons, Heber City. View floor plans." |
| The Outlaw | "The Outlaw — 3-bedroom unit with garage workshop & 2 levels of living space. Mountain View Commons, Heber City. View floor plans & request pricing." |
| Location | "Mountain View Commons is in Heber City, UT — 15 min from Deer Valley, 25 min from Park City. Located on Hwy 40 near downtown. Schedule a private tour." |
| FAQs | "FAQs about Mountain View Commons — pricing, HOA dues ($446/mo), unit sizes, phases, CC&Rs, and more. 43 mixed-use units in Heber City, Utah." |
| Contact | "Contact Mountain View Commons sales — Jonathan Crosswhite at Christie's International Real Estate. Call 435.649.4757 or request info online." |
| Gallery | "Browse photos and renderings of Mountain View Commons — a mixed-use development in Heber City, Utah. Aerial views, interiors & floor plans." |
| Site Plan | "View the Mountain View Commons community site plan — 43 units across 7 buildings in 4 phases. See available units in Heber City, Utah." |
| Downloads | "Download Mountain View Commons documents — CC&Rs, HOA budget, and builder spec sheets. All resources for prospective buyers." |

### 2. Fix Duplicate Title Tags (5 Pages)
**Impact:** High | **Effort:** 30 minutes

Five pages share "Site Plans & Available Units — Mountain View Commons." Each needs a unique title:

| Page | Current Title | Recommended Title |
|------|--------------|-------------------|
| The Hideout | Site Plans & Available Units — Mountain View Commons | The Hideout Floor Plan — 1BR Mixed-Use Unit | Mountain View Commons |
| The Frontier | Site Plans & Available Units — Mountain View Commons | The Frontier Floor Plan — 2BR Mixed-Use Unit | Mountain View Commons |
| The Mercantile | Site Plans & Available Units — Mountain View Commons | The Mercantile Floor Plan — Professional Space | Mountain View Commons |
| The Outlaw | Site Plans & Available Units — Mountain View Commons | The Outlaw Floor Plan — 3BR Mixed-Use Unit | Mountain View Commons |
| Site Plan | Site Plans & Available Units — Mountain View Commons | Community Site Plan — 43 Units | Mountain View Commons |

### 3. Fix Homepage Title Typo
**Impact:** High | **Effort:** 5 minutes

Change "Herber City" to "Heber City" in the homepage title tag.

### 4. Add Canonical Tags to All Pages
**Impact:** High | **Effort:** 30 minutes

In Squarespace, enable canonical URLs in SEO settings. Each page should have:
```html
<link rel="canonical" href="https://www.mtnviewcommonsut.com/[page-slug]" />
```

### 5. Fix Social Media Links
**Impact:** Medium-High | **Effort:** 10 minutes

All three social links (Facebook, Twitter, Instagram) point to Squarespace's profiles. Update to Mountain View Commons or VUE Real Estate profiles, or remove them entirely.

---

## Priority: HIGH (Fix Within 1 Week)

### 6. Add Alt Text to All Images
**Impact:** High | **Effort:** 2-3 hours

57 of 69 images (83%) are missing alt text. Priority order:
1. **Gallery page** — 33 images with no alt text
2. **Homepage** — hero and logo images
3. **Floorplan pages** — hero images (floor plan images already have alt text)
4. **Location page** — map and area images

Example alt text for gallery images:
- "Aerial view of Mountain View Commons development in Heber City Utah"
- "Mountain View Commons exterior rendering showing mixed-use buildings"
- "Interior rendering of Mountain View Commons living space"

### 7. Add FAQPage Schema to FAQ Page
**Impact:** High | **Effort:** 30 minutes

The FAQ page has 12 questions and answers but no FAQPage structured data. Adding this enables rich results in Google (expandable Q&A directly in search).

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Where is Mountain View Commons Located?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Mountain View Commons is conveniently located on Hwy 40 a half mile East of Hwy 189, minutes from downtown Heber City, 13 minutes from Deer Valley Resort, and 25 minutes from Park City."
      }
    }
  ]
}
```
*(Repeat for all 12 questions)*

### 8. Fix FAQ Typo
**Impact:** Low | **Effort:** 2 minutes

Change "ARE ALL THE UNITES THE SAME SIZE?" to "ARE ALL THE UNITS THE SAME SIZE?"

### 9. Expand Thin Content Pages
**Impact:** High | **Effort:** 4-6 hours

7 pages have thin content. Priority pages to expand:

**Floorplan pages (The Hideout, Frontier, Mercantile, Outlaw):**
- Add detailed feature lists (square footage per floor, ceiling heights, door dimensions)
- Add use-case scenarios (e.g., "Perfect for a home-based business with street-level retail")
- Add construction specifications and finishes
- Add pricing information or "starting from" ranges
- Target 800-1,200 words per page

**Gallery page:**
- Add descriptive captions to images
- Add introductory text about the development
- Organize images by category (exteriors, interiors, floor plans, aerials)

**Site Plan page:**
- Add text describing the layout, phases, and unit availability
- Include building numbers and unit types per building

### 10. Add Open Graph Tags
**Impact:** Medium | **Effort:** 1 hour

No OG tags on any page. When links are shared on social media, they display poorly. Add to all pages:
```html
<meta property="og:title" content="[Page Title]" />
<meta property="og:description" content="[Meta Description]" />
<meta property="og:image" content="[Featured Image URL]" />
<meta property="og:url" content="[Page URL]" />
<meta property="og:type" content="website" />
```

---

## Priority: MEDIUM (Fix Within 1 Month)

### 11. Enhance LocalBusiness Schema
**Impact:** Medium | **Effort:** 1 hour

Current LocalBusiness schema is minimal. Add:
- `telephone`: "435-649-4757"
- `email`: "jonathan.crosswhite@vuere.com"
- `geo` with latitude/longitude coordinates
- `openingHours`
- `priceRange`
- `sameAs` array with actual social media profile URLs
- `address` with full structured address

### 12. Add Breadcrumb Navigation + Schema
**Impact:** Medium | **Effort:** 2 hours

Add breadcrumbs to all pages (e.g., Home > Floorplans > The Hideout) with BreadcrumbList schema.

### 13. Decide AI Crawler Policy
**Impact:** Medium-High | **Effort:** 30 minutes

The site currently blocks ALL major AI crawlers (ClaudeBot, GPTBot, Amazonbot, etc.). This means:
- No visibility in ChatGPT search results
- No visibility in Perplexity answers
- Potentially excluded from Google AI Overviews

**Decision needed:** If you want AI search visibility (recommended for real estate), allow these crawlers in robots.txt or at minimum allow GoogleBot-Extended for AI Overviews.

### 14. Fix Phone Number Inconsistency
**Impact:** Low | **Effort:** 5 minutes

Privacy policy lists 435-659-4757 while all other pages list 435.649.4757. Verify which is correct and standardize.

### 15. Update Internal Links for Redirect
**Impact:** Low | **Effort:** 15 minutes

/flex-use-real-estate 301 redirects to /mixed-use-real-estate. Update all internal links to point directly to /mixed-use-real-estate to avoid unnecessary redirect hops.

### 16. Fix Sitemap Issues
**Impact:** Low-Medium | **Effort:** 30 minutes

- Change `changefreq` from "daily" to "weekly" or "monthly" (these pages don't change daily)
- Ensure homepage URL is `/` not `/home` to avoid duplicate indexing
- Differentiate priority values based on page importance

### 17. Update Outdated Content
**Impact:** Low | **Effort:** 30 minutes

- Replace "2023 Budget" with current year budget on Downloads page
- Review all pages for outdated information

---

## Priority: LOW (Backlog)

### 18. Add RealEstateListing Schema
**Impact:** Medium | **Effort:** 2 hours

Create RealEstateListing or Product schema for each unit type with pricing, features, and availability.

### 19. Add ImageGallery Schema
**Impact:** Low | **Effort:** 30 minutes

Add ImageGallery schema to /gallery page.

### 20. Create llms.txt File
**Impact:** Low | **Effort:** 30 minutes

If AI crawler access is enabled, create an llms.txt file providing a structured summary of the property for AI models.

### 21. Reduce ALL CAPS Usage
**Impact:** Low | **Effort:** 1 hour

Many headings use ALL CAPS via content (not CSS). This hurts readability and can trigger spam signals. Use CSS `text-transform: uppercase` instead of typing in all caps.

### 22. Add Testimonials / Social Proof
**Impact:** Medium | **Effort:** Ongoing

No reviews, testimonials, or social proof on the site. Consider adding:
- Buyer testimonials
- Community highlights
- Local business spotlights (if any units are occupied)

### 23. Create a Blog / Content Hub
**Impact:** Medium-High | **Effort:** Ongoing

No blog or content marketing presence. Target keywords like:
- "mixed use property Utah"
- "live work space Heber City"
- "Heber City real estate development"
- "Park City area mixed use"

---

## Implementation Timeline

| Week | Tasks | Estimated Hours |
|------|-------|----------------|
| **Week 1** | Items 1-5 (Critical) | 3-4 hours |
| **Week 2** | Items 6-10 (High) | 8-12 hours |
| **Week 3-4** | Items 11-17 (Medium) | 5-7 hours |
| **Backlog** | Items 18-23 (Low) | Ongoing |

**Total estimated effort for Critical + High items: ~12-16 hours**

---

## Expected Impact

After implementing Critical and High priority items:
- **CTR improvement:** 20-40% increase from meta descriptions alone
- **Ranking potential:** Unique titles + expanded content should improve rankings for target keywords
- **Rich results:** FAQPage schema could generate featured snippets
- **Accessibility:** Alt text additions bring site closer to WCAG compliance
- **Social sharing:** OG tags and correct social links improve referral traffic

---

*Action plan generated by SEO Audit Tool — March 25, 2026*
