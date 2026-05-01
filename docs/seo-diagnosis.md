# SEO Diagnosis: Website Not Indexing

## Scenario
A new Worknoon website is not indexing despite sitemap submission.

---

## 1. Crawlability Checks
- Use Google Search Console URL Inspection
- Check if Googlebot can access the page
- Ensure no server errors (5xx)

---

## 2. Robots.txt Audit
Check:
- If important pages are blocked
- Example issue:
  Disallow: /

Fix:
- Allow crawling for key pages

---

## 3. Noindex Tag Check
Inspect page source for:
<meta name="robots" content="noindex">

If present, remove it to allow indexing.

---

## 4. Canonical Tag Issues
Ensure:
- Canonical URLs point to the correct version
- No conflicting canonical tags

---

## 5. Sitemap Issues
Check:
- Sitemap is accessible
- URLs are valid (200 status)
- No broken or redirected URLs

Resubmit sitemap in Google Search Console after fixing issues.

---

## 6. Page Speed & Performance
Slow pages may delay indexing.

Check:
- Core Web Vitals
- Large images or unoptimized scripts

Tools:
- Google PageSpeed Insights

---

## 7. Content Quality
Thin or duplicate content may not be indexed.

Ensure:
- Unique content
- Proper headings (H1, H2)
- Clear value proposition

---

## 8. Google Search Console Debugging
Steps:
- Inspect URL
- Request indexing
- Check coverage report
- Review crawl stats

---

## Conclusion
Indexing issues are usually caused by technical restrictions or low-quality signals. Fixing crawlability, content quality, and technical SEO ensures proper indexing.
