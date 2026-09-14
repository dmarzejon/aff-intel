# Affiliate Link Map

> **For Affiliate Bot:** replace each `#AFFILIATE:...` placeholder with the live tracking URL.
> Keep slugs stable — posts and the hub reference these IDs.

| Slug | Product | Placeholder | Live URL | Notes |
|------|---------|-------------|----------|-------|
| `chatgpt-plus` | ChatGPT Plus | `#AFFILIATE:chatgpt-plus` | _pending_ | OpenAI ChatGPT Plus / Team |
| `claude-pro` | Claude Pro | `#AFFILIATE:claude-pro` | _pending_ | Anthropic Claude Pro / Team |
| `notion-ai` | Notion AI | `#AFFILIATE:notion-ai` | _pending_ | Notion + Notion AI add-on |
| `make` | Make.com | `#AFFILIATE:make` | _pending_ | Make (Integromat) cloud |
| `n8n-cloud` | n8n Cloud | `#AFFILIATE:n8n-cloud` | _pending_ | n8n Cloud hosted |
| `descript` | Descript | `#AFFILIATE:descript` | _pending_ | Descript Creator/Pro |
| `capcut` | CapCut | `#AFFILIATE:capcut` | _pending_ | CapCut Pro |
| `midjourney` | Midjourney | `#AFFILIATE:midjourney` | _pending_ | Midjourney subscription |
| `cursor` | Cursor | `#AFFILIATE:cursor` | _pending_ | Cursor Pro / Business |
| `github-copilot` | GitHub Copilot | `#AFFILIATE:github-copilot` | _pending_ | Copilot Individual/Business |
| `convertkit` | ConvertKit (Kit) | `#AFFILIATE:convertkit` | _pending_ | Kit / ConvertKit creator plan |
| `beehiiv` | Beehiiv | `#AFFILIATE:beehiiv` | _pending_ | Beehiiv Scale / Max |
| `gumroad` | Gumroad | `#AFFILIATE:gumroad` | _pending_ | Gumroad creator store |
| `meta-muse` | Meta Muse | `#AFFILIATE:meta-muse` | _pending_ | muse.ai — partner link TBD |
| `sesame` | Sesame | `#AFFILIATE:sesame` | _pending_ | Sesame iOS agents — partner link TBD |
| `gemini-spark` | Gemini Spark | `#AFFILIATE:gemini-spark` | _pending_ | Google AI Pro / Spark |

## Placeholder convention

In HTML and markdown content, use:

```html
<a class="btn primary" href="#AFFILIATE:cursor">Try Cursor</a>
```

Affiliate Bot should rewrite `href="#AFFILIATE:<slug>"` → live URL and optionally add `rel="sponsored noopener"`.

## Official fallbacks (until live)

| Slug | Official |
|------|----------|
| chatgpt-plus | https://chatgpt.com/ |
| claude-pro | https://claude.ai/ |
| notion-ai | https://www.notion.so/product/ai |
| make | https://www.make.com/ |
| n8n-cloud | https://n8n.io/cloud/ |
| descript | https://www.descript.com/ |
| capcut | https://www.capcut.com/ |
| midjourney | https://www.midjourney.com/ |
| cursor | https://cursor.com/ |
| github-copilot | https://github.com/features/copilot |
| convertkit | https://kit.com/ |
| beehiiv | https://www.beehiiv.com/ |
| gumroad | https://gumroad.com/ |
| meta-muse | https://muse.ai/ |
| sesame | https://www.sesame.com/ |
| gemini-spark | https://gemini.google.com/ |
