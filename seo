---
title: SEO
layout: 2017/sheet
prism_languages: [scss, haml, html]
weight: -1
category: Growth
description: |
  .container .row .col-md-6, @screen-sm-min, .form-control, grids, .modal-content, tooltips, and other Bootstrap CSS examples.
---

### Important HTML Elements
These affect how you show up in search results

```

Title Tag
<head>
 <title>Page Title</title>
</head>

• Best between 50–60 characters
• Important keywords near the beginning
• Well-written descriptions influence
 click-through rates (CTR)
```

Meta Description Tag

```scss
<head>
 <meta name="description"
 content="This is an example.">
</head>

• Best around 160 characters
• Each description should be unique
• Well-written descriptions influence
 click-through rates (CTR)
```

Image


```scss
<img src="img/keyword.jpg" alt="description of image" width="100" height="100">

• Providing image height and width improves
 page speed
```

### Hyperlinks

```scss
Text Link
<a href="https://www.example.com/webpage.
html">Anchor Text</a>
NoFollowed Link
<a href="https://www.example.com/webpage.html" rel="nofollow">
Anchor Text</a>
Image Link
<a href="https://www.example.com/webpage.html"><img src="/img/keyword.jpg"
alt="description of image" height="50"
width="100"></a>

Use “nofollow” for paid links and
 distrusted content
• Use “sponsored” for sponsored or
 compensated links
• Use “ugc” for links within user-generated
 content
• For image links, the alt attribute serves as the
 anchor text
```

### HTTP Status Codes

```scss
200 OK/Success
301 Permanent redirect
302 Temporary redirect
404 Not found
410 Gone (permanently removed)
500 Server error
503 Unavailable (retry later
```

### Webmaster Tools

```scss
Google Search Console
search.google.com/search-console/about
Bing Webmaster Tools
bing.com/toolbox/webmaster
Yandex
webmaster.yandex.com
```

### Canonicalization

```scss
Preferred URL = https://example.com/
• Place the following in <head> section to
 indicate preferred URL:

 <link href="https://example.com/" rel=
 "canonical" />
More information at mz.cm/canonical
```

### URLs

```scss
Common URL Elements
https://store.example.com/category/keyword?id=123#top
1 2 3 4 5 6 7 8
1. Protocol
5. Subfolder/path
2. Subdomain
6. Page
3. Root domain
7. Parameter
4. Top-level domain
8. Named anchor

• Choose shorter, human-readable URLs with descriptive keywords
• Exclude dynamic parameters when possible (see “Canonicalization” and “Pagination”)
• When possible, place content on the same subdomain to preserve authority
```

### Robots Exclusion Standard

```scss
Robots.txt
Location: https://example.com/robots.txt
User-agent: googlebot
Disallow: /example.html
Sitemap: https://example.com/sitemap.xml
More information at mz.cm/robotstxt
X-Robots-Tag
Location: Sent in the HTTP headers
X-Robots-Tag: noindex
More information at mz.cm/x-robots
Meta Robots
Location: In the HTML <head>
<meta name="robots" content="[PARAMETER]" />
More information at mz.cm/x-robots

• Only Meta Robots and X-Robots-Tag remove
 URLs from search results
• Don’t block CSS or JavaScript files with
 robots.txt
 
 Important Parameters
• Noindex (do not index)
• Nofollow (do not follow links)
• Noarchive (do not show cache)
...or combine (noindex, nofollow)
If the robots <META> tag is not defined, the
default is "INDEX, FOLLOW"
Don’t block noindex URLs in robots.txt.
They need to be crawled to be respected.

```
### Important User Agents

```scss
For Robots.txt, Robots Meta Tags, and X-Robots-Tag:
• Googlebot (can be used as default for most
 Google crawlers)
• Googlebot-News
• Googlebot-Image
• AdsBot-Google
• Mediapartners-Google (Mobile Adsense)
 or Mediapartners
• Googlebot-Video
• Bingbot
• Yandexbot
• Baiduspider
• FacebookExternalHit
• Applebot
• Slurp
• Twitterbot
• Rogerbot
• Dotbot
• Wildcard for all robots: *
```

### Sitemap Syntax

```scss
XML Sitemap Example:
RSS and text sitemaps are also options
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
 <url>
 <loc>http://www.example.com/foo.html</loc>
 <lastmod>2019-06-04</lastmod>
 </url>
</urlset>
Sitemap Index File
<?xml version="1.0" encoding="UTF-8"?>
<sitemapindex xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
<sitemap>
 <loc>https://example.com/sitemap1.xml.gz</loc>
 <lastmod>2019-01-01T18:23:17+00:00</lastmod>
 </sitemap>
 <sitemap>
 <loc>https://example.com/sitemap2.xml.gz</loc>
 <lastmod>2019-01-01</lastmod>
 </sitemap>
</sitemapindex>

Default Location:
https://example.com/sitemap.xml
sitemap: parent tag for each sitemap
 loc: location of the sitemap
lastmod: the last modified date
* A sitemap cannot contain over 50,000 URLs.
 Large websites should use multiple sitemaps
 listed under a single sitemap index file.
Other Common Sitemap Types:
• Images
• Video
• News
* Don't forget to submit your sitemap to Google
 via Google Search Console.
```

### Important Social Metadata

```html
Sample Meta Tag Template: "Article"
Place this data between the <head> tags of your website.
<!-- Required Open Graph data -->
<meta property="og:title" content="Developer's Cheat
Sheet to SEO" />
<meta property="og:type" content="article" />
<meta property="og:image" content="https://example.
com/image.jpg" />
<meta property="og:url" content="https://example.
com" />
<!-- Optional Open Graph data -->
<meta property="og:audio" content="https://example.
com/guide.mp3." />
<meta property="og:description" content="Description
here." />
<meta property="og:site_name" content="Your Site
Name, i.e. Moz" />
<meta property="og:locale" content="en_us" />
<meta property="og:video" content="https://example.
com/guide.mp4" />
<meta property="fb:app_id" content="Your FB_APP_ID" />
<!-- Find additional markup on https://ogp.me -->
<!-- Twitter Card data -->
<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@Moz">
<meta name="twitter:title" content="Title of content
(max 70 characters)">
<meta name="twitter:description" content="Description of content">
<meta name="twitter:image" content="https://example.
com/unique-image.jpg">

Default to Open Graph
Platforms that support Open Graph protocol include Facebook,
Twitter, LinkedIn, and Pinterest.
Optimal Image Sizing
 Twitter:
 • Minimum 144x144 px
 • No larger than 4096x4096 px or 5MB
 Facebook:
 • Minimum 600x600 px
 • Try to use images that are at least 1080 px in width
```

### Rich Snippets and Structured Data
Enhance search results and help search engines understand your content


```haml
Common Vocabularies: schema.org
Popular Formats: JSON-LD, RDFa, Microdata
Breadcrumbs
<script type="application/ld+json">
{
 "@context": "http://schema.org",
 "@type": "BreadcrumbList",
 "itemListElement": [
{
<---Repeat markup for additional list items--->
 "@type": "ListItem",
 "position": 1,
 "item": {
 "@id": "http://example.com/dinner",
 "name": "Dinner" }
},
<---Additional list items here--->
 }]
 }</script>
Reviews
<script type="application/ld+json">
{
 "@context": "http://schema.org/",
 "@type": "Review",
 "reviewBody": "The restaurant has great ambiance.",
 "itemReviewed": {
 "@type": "Restaurant",
 "name": "Fine Dining Establishment"
 },
 "reviewRating": {
 "@type": "Rating",
 "ratingValue": 5,
 "worstRating": 1,
 "bestRating": 5,
 "reviewAspect": "Ambiance"
 }
}
</script>
Review stars won’t show up in search results.

Common Structured Data Types:
• Local business
• FAQ page
• Person
• How to
More information at mz.cm/rich-snippets
• Product
• Article
• Recipes
• QApage
```

### Page Speed

```haml
Page Speed Tips:
• Compress and minify your code
• Reduce page redirects
• Remove render-blocking JavaScript
• Use treeshaking
• Leverage browser caching
• Use a CDN
• Leverage preconnect, prefetch and preload
• Analyze your critical rendering path performance for additional opportunities
 in Chrome Dev Tools.
Test your Page Speed with:
 Lighthouse: developers.google.com/web/tools/lighthouse
PageSpeed Insights: developers.google.com/speed/pagespeed/insights
 GTmetrix: gtmetrix.com
 WebPageTest: webpagetest.org
```

### Image Optimization
The most common culprit of poor page speed is images!

```haml
Image Optimization Tips:
• Compress your images & experiment with quality settings
• Remove unnecessary image metadata
• Explore lazy loading
• Leverage SRCSET for different screen sizes
• Ensure that your images have alt text
• Invest in automated tools that can help ensure your image assets will always
 be optimized (example: mz.cm/imageopt)
```

### Modern JavaScript Sites

```html
JavaScript Tips:
• Keep JavaScript bundles small (especially for mobile devices). Small bundles improve
 speed, lower memory usage, and reduce CPU costs.
• Use server-side or pre-rendering to improve site speed, user experience,
 and crawler accessibility.
• Stuck with client-side rendering? Try pre-rendering to help Googlebot get a
 more immediate HTML snapshot of your page.
• Use Chrome Dev Tools “Performance” tab to test your runtime performance
 and network “throttling” to simulate different device capabilities.
Explore Chrome DevTools’ Timeline & JavaScript Profiler to analyze the impact
of your JavaScript.
```
