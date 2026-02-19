# GEO Starter Kit

Free templates to make your site visible to AI search engines (ChatGPT, Perplexity, Claude).

## What is GEO?

**Generative Engine Optimization** — Optimizing your site to be cited by AI-powered search.

Unlike SEO (ranking in Google), GEO focuses on:
- Being crawlable by AI bots
- Having machine-readable structured data
- Providing context via llms.txt

## Templates

### 1. robots.txt (AI-Friendly)

```txt
# robots.txt — Allow AI crawlers

User-agent: GPTBot
Allow: /

User-agent: ClaudeBot
Allow: /

User-agent: PerplexityBot
Allow: /

User-agent: Google-Extended
Allow: /

User-agent: *
Allow: /

Sitemap: https://yoursite.com/sitemap.xml
```

### 2. llms.txt

```markdown
# yoursite.com

> Brief description of what your site/product does.

## Overview

One paragraph explaining your product, service, or content.

## Key Pages

- /about — Company information
- /pricing — Plans and pricing
- /docs — Documentation

## Contact

- Email: hello@yoursite.com
- Website: https://yoursite.com
```

### 3. Schema.org (Organization)

```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Your Company",
  "url": "https://yoursite.com",
  "description": "What you do",
  "sameAs": [
    "https://twitter.com/yourhandle",
    "https://linkedin.com/company/yourcompany"
  ]
}
```

## Check Your GEO Score

Use these templates, then verify your site:

**[Free GEO Scanner →](https://geoautopilot.com)**

Get your GEO Score and see:
- AI crawler access status
- Schema.org quality
- llms.txt validation
- Content structure analysis

## Resources

- [What is GEO?](https://geoautopilot.com/what-is-geo)
- [llms.txt Specification](https://llmstxt.org)
- [Schema.org Documentation](https://schema.org)

## License

MIT — Use freely
