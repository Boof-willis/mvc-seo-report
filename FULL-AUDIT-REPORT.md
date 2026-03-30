# Full SEO Audit Report: Mountain View Commons
## www.mtnviewcommonsut.com
### Audit Date: March 25, 2026

---

## Executive Summary

| Metric | Score |
|--------|-------|
| **Overall SEO Health Score** | **34 / 100** |
| Business Type Detected | Mixed-Use Real Estate Development |
| Pages Crawled | 13 (full site) |
| Platform | Squarespace |

### Top 5 Critical Issues
1. **Zero meta descriptions** across all 13 pages — massively hurts CTR in search results
2. **Duplicate title tags** — 4 floorplan pages share the identical title "Site Plans & Available Units"
3. **No canonical tags** on any page — risks duplicate content indexing
4. **33+ images missing alt text** — accessibility violation and lost image SEO
5. **Social media links point to Squarespace defaults** (facebook.com/squarespace) — no real social presence linked

### Top 5 Quick Wins
1. Add unique meta descriptions to all 13 pages (1-2 hours)
2. Fix duplicate title tags on floorplan pages (30 minutes)
3. Add alt text to all images, especially gallery (1-2 hours)
4. Add FAQPage schema to the FAQ page (30 minutes)
5. Fix social media links to actual business profiles (10 minutes)

---

## Technical SEO (Score: 38/100)

### Crawlability

| Check | Status | Notes |
|-------|--------|-------|
| robots.txt | Present | Hosted by Squarespace; blocks AI crawlers (ClaudeBot, GPTBot, etc.) |
| XML Sitemap | Present | 13 URLs listed at /sitemap.xml |
| Sitemap in robots.txt | Yes | Referenced correctly |
| Internal linking | Adequate | All pages reachable from navigation |
| Redirect chains | Issue Found | /flex-use-real-estate 301 redirects to /mixed-use-real-estate |
| Broken links | Not detected | — |

### Indexability

| Check | Status | Notes |
|-------|--------|-------|
| Canonical tags | MISSING | No canonical tags on ANY page |
| Meta robots tags | MISSING | No robots meta tags found |
| Noindex pages | N/A | None detected |
| Duplicate content risk | HIGH | 4 pages share identical title tag |

### Security

| Check | Status | Notes |
|-------|--------|-------|
| HTTPS | Yes | SSL active |
| Mixed content | Not detected | — |
| HSTS | Unknown | Squarespace-managed |

### URL Structure

| Check | Status | Notes |
|-------|--------|-------|
| Clean URLs | Good | Descriptive, hyphenated slugs |
| URL depth | Good | All pages 1 level deep |
| Trailing slashes | Consistent | — |

### Sitemap Issues

| Issue | Severity |
|-------|----------|
| changefreq "daily" on all pages | Medium — unrealistic for static property pages |
| /home listed instead of / | Medium — potential duplicate indexing of homepage |
| /flex-use-real-estate not in sitemap | Low — redirects to /mixed-use-real-estate |
| Priority values all 0.75 (except home at 1.0) | Low — not differentiated |

---

## Content Quality (Score: 30/100)

### E-E-A-T Assessment

| Signal | Rating | Notes |
|--------|--------|-------|
| Experience | Weak | No testimonials, case studies, or buyer stories |
| Expertise | Moderate | Developer and builder info provided |
| Authoritativeness | Weak | Christie's brand mentioned but not leveraged with schema |
| Trustworthiness | Moderate | Contact info visible, physical address provided |

### Page-by-Page Content Analysis

| Page | Word Count | Content Quality | Issues |
|------|-----------|----------------|--------|
| Homepage | ~900 | Moderate | Typo in title: "Herber City" instead of "Heber City" |
| Mixed-Use Real Estate | ~1,300 | Good | Best content page on site |
| The Hideout | ~450 | Thin | Below 500-word threshold |
| The Frontier | ~375 | Thin | Below 500-word threshold |
| The Mercantile | ~450 | Thin | Below 500-word threshold |
| The Outlaw | ~450 | Thin | Below 500-word threshold |
| Location | ~1,300 | Good | Solid demographic data |
| FAQs | ~850 | Moderate | Typo: "UNITES" should be "UNITS" |
| Contact | ~300 | Thin | Minimal beyond form |
| Gallery | ~100 | Very Thin | Almost no text content |
| Site Plan | ~200 | Very Thin | Minimal text |
| Downloads | ~375 | Thin | 2023 budget doc is outdated |
| Privacy Policy | ~800 | Adequate | Standard policy page |

### Thin Content Summary
- **7 of 13 pages** have thin content (under 500 words)
- Floorplan pages need expanded descriptions, features, specs, and use-case content
- Gallery page needs descriptive text and captions

### Duplicate Content Issues
- 4 floorplan pages share the same title tag
- /home and / may index as separate pages

### Readability
- Content uses appropriate language for target audience (real estate buyers/investors)
- Heavy use of ALL CAPS in headings hurts readability and accessibility

---

## On-Page SEO (Score: 22/100)

### Title Tags

| Page | Title | Issues |
|------|-------|--------|
| Homepage | "Mixed-Use Property in Herber City Utah - Commercial & Residential Real Estate" | Typo: "Herber" should be "Heber"; missing brand at end |
| Mixed-Use Real Estate | "Mixed-Use Property Uses & Examples — Mountain View Commons" | Good |
| The Hideout | "Site Plans & Available Units — Mountain View Commons" | DUPLICATE — not unique to this floorplan |
| The Frontier | "Site Plans & Available Units — Mountain View Commons" | DUPLICATE |
| The Mercantile | "Site Plans & Available Units — Mountain View Commons" | DUPLICATE |
| The Outlaw | "Site Plans & Available Units — Mountain View Commons" | DUPLICATE |
| Location | "Convenient Location in Heber City — Mountain View Commons" | Good |
| FAQs | "FAQs about Mixed-Use Property — Mountain View Commons" | Good |
| Contact | "Contact Us — Mountain View Commons" | Good |
| Gallery | "Gallery — Mountain View Commons" | Good but generic |
| Site Plan | "Site Plans & Available Units — Mountain View Commons" | DUPLICATE (same as floorplans) |
| Downloads | "Document Downloads — Mountain View Commons" | Good |
| Privacy Policy | "Privacy Policy — Mountain View Commons" | Good |

**5 pages share the exact same title tag.** This is a critical SEO issue.

### Meta Descriptions

| Page | Meta Description |
|------|-----------------|
| ALL 13 PAGES | **MISSING** |

**No page on the entire site has a meta description.** Google will auto-generate snippets, which are often suboptimal and reduce click-through rates.

### Heading Structure

| Page | H1 | Issues |
|------|----|----|
| Homepage | "MIXED-USE PROPERTY IN HEBER CITY, UTAH" | Good |
| Mixed-Use Real Estate | "MIXED-USE PROPERTY FOR SALE" | Good |
| The Hideout | "THE HIDEOUT MODEL" | Good |
| The Frontier | "THE FRONTIER MODEL" | Good |
| The Mercantile | "THE MERCANTILE MODEL" | Good |
| The Outlaw | "THE OUTLAW MODEL" | Good |
| Location | "HEBER CITY, UTAH" | Could include "Mixed-Use Property Location" |
| FAQs | "Frequently Asked Questions" | Generic — could include "Mountain View Commons" |
| Contact | "CONTACT US" | Generic |
| Gallery | "Image GALLERY" | Generic |
| Site Plan | "COMMUNITY SITE PLAN" | OK |
| Downloads | "Download Center" | OK |

### Internal Linking
- Navigation provides links to all main pages
- Footer duplicates navigation links (good)
- **Missing:** Cross-links between floorplan pages (e.g., "See also: The Frontier" on The Hideout page)
- **Missing:** Breadcrumb navigation

---

## Schema & Structured Data (Score: 25/100)

### Current Implementation

| Schema Type | Present | Valid | Notes |
|-------------|---------|-------|-------|
| WebSite | Yes | Partial | Name and logo present |
| LocalBusiness | Yes | Minimal | Missing key fields |
| FAQPage | NO | — | FAQ page has 12 Q&As but no FAQPage schema |
| RealEstateListing | NO | — | Major missed opportunity |
| BreadcrumbList | NO | — | No breadcrumbs |
| Product | NO | — | Could be used for individual units |
| ImageGallery | NO | — | Gallery page has 33 images with no schema |

### LocalBusiness Schema Issues
- Missing: opening hours, price range, geo coordinates
- Missing: aggregate rating, reviews
- Missing: telephone, email in schema
- Missing: sameAs links to social profiles

### Recommended Schema Additions
1. **FAQPage** on /faqs — would enable FAQ rich results in Google
2. **RealEstateListing** or **Product** for each floorplan unit
3. **BreadcrumbList** site-wide
4. **ImageGallery** on /gallery
5. **Organization** with full details (phone, email, address, social)
6. **Place** on /location-heber-city with geo coordinates

---

## Performance (Score: 45/100)

### Estimated Core Web Vitals

| Metric | Estimate | Status |
|--------|----------|--------|
| LCP (Largest Contentful Paint) | ~3-4s (image-heavy hero) | Needs Improvement |
| INP (Interaction to Next Paint) | ~100-150ms | Likely Good |
| CLS (Cumulative Layout Shift) | ~0.1-0.2 (images without dimensions) | Needs Improvement |

### Resource Analysis
- **20+ CSS/JS files** loaded (Squarespace rollups)
- Heavy reliance on Squarespace CDN for images
- Facebook Pixel + Google Tag Manager adding third-party scripts
- No evidence of lazy loading on gallery page (33 images)

### Recommendations
- Enable lazy loading for gallery images
- Ensure all images have explicit width/height to prevent CLS
- Consider WebP format for images
- Minimize third-party script impact

---

## Images (Score: 15/100)

### Alt Text Audit

| Page | Images | With Alt Text | Missing Alt Text |
|------|--------|--------------|-----------------|
| Homepage | ~4 | 0 | 4 |
| Mixed-Use Real Estate | ~6 | 0 | 6 |
| The Hideout | ~5 | 3 (floor plans) | 2 |
| The Frontier | ~5 | 3 (floor plans) | 2 |
| The Mercantile | ~5 | 3 (floor plans) | 2 |
| The Outlaw | ~5 | 3 (floor plans) | 2 |
| Gallery | ~33 | 0 | 33 |
| Location | ~3 | 0 | 3 |
| Site Plan | ~3 | 0 | 3 |
| **TOTAL** | **~69** | **~12 (17%)** | **~57 (83%)** |

**83% of images are missing alt text.** This is:
- An accessibility violation (WCAG 2.1)
- A major missed SEO opportunity for image search
- Particularly damaging on the Gallery page with 33 unoptimized images

### Image Format
- Images appear to be JPEG format served via Squarespace CDN
- No evidence of WebP/AVIF optimization
- File names are non-descriptive (e.g., "001_004_dji_20250711050533_0241_d_copy_554_586.jpg")

---

## AI Search Readiness (Score: 20/100)

### AI Crawler Access
- **robots.txt blocks major AI crawlers:** ClaudeBot, GPTBot, Amazonbot, CCBot
- This means the site is **invisible to AI-powered search** (ChatGPT, Perplexity, Claude, etc.)
- No llms.txt file detected

### Citability Assessment

| Factor | Rating | Notes |
|--------|--------|-------|
| Structured answers | Moderate | FAQ page has good Q&A format |
| Definitive statements | Weak | Content is more marketing than informational |
| Data/statistics | Moderate | Location page has demographic data |
| Unique insights | Weak | Generic real estate development language |
| Entity clarity | Weak | No clear entity definitions in schema |

### Recommendations
1. **Decide on AI crawler policy** — blocking all AI crawlers means zero visibility in AI search results (ChatGPT, Perplexity, Google AI Overviews)
2. Add llms.txt if you want AI visibility
3. Structure content in Q&A and fact-based formats
4. Include unique data points that AI models would cite

---

## Additional Issues Found

### Typos & Errors
1. **Homepage title tag:** "Herber City" should be "Heber City"
2. **FAQ page:** "ARE ALL THE UNITES THE SAME SIZE?" — "UNITES" should be "UNITS"

### Social Media Links
- Facebook link: facebook.com/squarespace (NOT the business)
- Twitter link: twitter.com/squarespace (NOT the business)
- Instagram link: instagram.com/squarespace (NOT the business)
- **All three social links go to Squarespace's profiles, not Mountain View Commons**

### Phone Number Inconsistency
- Most pages: 435.649.4757
- Privacy policy: 435-659-4757 (different number — possible typo)

### Outdated Content
- Downloads page offers a "2023 Budget" — should be updated to 2025/2026

### Open Graph Tags
- No OG tags detected on any page
- Shared links on social media will display poorly

### 301 Redirect
- /flex-use-real-estate redirects to /mixed-use-real-estate
- Internal links should be updated to point directly to /mixed-use-real-estate

---

## Scoring Breakdown

| Category | Weight | Score | Weighted |
|----------|--------|-------|----------|
| Technical SEO | 25% | 38 | 9.5 |
| Content Quality | 25% | 30 | 7.5 |
| On-Page SEO | 20% | 22 | 4.4 |
| Schema / Structured Data | 10% | 25 | 2.5 |
| Performance (CWV) | 10% | 45 | 4.5 |
| Images | 5% | 15 | 0.75 |
| AI Search Readiness | 5% | 20 | 1.0 |
| **TOTAL** | **100%** | — | **34.15** |

---

## Competitive Disadvantages

For a mixed-use real estate development in the competitive Heber City / Park City corridor market, this site has significant SEO gaps:

1. **Will not rank** for high-intent searches like "mixed use property Heber City" due to missing meta descriptions and thin content
2. **Invisible to AI search** — blocked all AI crawlers
3. **No rich results** in Google — missing FAQ schema, product schema, review schema
4. **Poor social sharing** — no OG tags + wrong social links
5. **Accessibility concerns** — 83% of images missing alt text could trigger ADA compliance issues

---

*Report generated by SEO Audit Tool — March 25, 2026*
