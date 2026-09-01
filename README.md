# GEO — Generative Engine Optimization



Working notes on how to get cited inside AI answers ([ChatGPT](https://chatgpt.com/), [Perplexity](https://www.perplexity.ai/), [Gemini](https://gemini.google.com/), [Claude](https://claude.ai/), [Copilot](https://copilot.microsoft.com/), [Google AI Overviews](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide)), not just ranked in blue links.



This repo holds the file. Use it as a brief, not as decoration.



**Author:** [DeFrens](https://t.me/defrensnews/372) 

**X:** [@officer_secret](https://twitter.com/officer_secret)



---



## What this is



SEO still decides whether a page can be found. 

GEO decides whether a model quotes you when it writes the answer.



If the product ranks and ChatGPT still recommends a competitor, the gap is usually structure, extractable facts, entity consistency, and proof on other sites — not another keyword list.

AEO (Answer Engine Optimization) sits next to GEO in the same pile of acronyms. People use the labels interchangeably. AEO usually means “be the extractable answer.” GEO usually means “be part of the synthesized reply, cited or recommended.” The work overlaps. The output is still an AI-written paragraph with a short source list.



---



## How to use the file



Upload the file from this repository to the LLM you already use ([ChatGPT](https://chatgpt.com/), [Claude](https://claude.ai/), [Gemini](https://gemini.google.com/), etc.) and treat it as a working document:



- website / content audits

- content planning

- page edits

- a GEO strategy for a specific product or niche



Do not apply it blindly. Cut what does not fit the market, the offer, and the engines your buyers actually use.



Prompt starter:



```text

You are helping me apply this GEO document to my project.

Read the attached file first.

Then audit [URL] and produce:

1) what an AI engine can extract today

2) missing facts, entities, and proof

3) page-level edits

4) off-site mentions worth earning

5) a 30-day plan

Stay specific to this niche and product. No generic SEO filler. Give me an answer in English.

```

## Pair it with an agent-readiness scan

GEO is the content and citation layer. 

Agent readiness is the machine-readable layer: can an agent discover the site, read it, respect bot rules, find protocols, and (if relevant) transact.



Cloudflare’s scanner: [isitagentready.com](https://isitagentready.com/)



Example scan: [isitagentready.com/roamzy.io](https://isitagentready.com/roamzy.io)



Launch write-up: [Introducing the Agent Readiness score](https://blog.cloudflare.com/agent-readiness/)



It checks things like:



- **Discoverability** — `robots.txt`, sitemap, Link headers, DNS-AID

- **Content accessibility** — Markdown content negotiation

- **Bot access control** — AI bot rules, Content Signals, Web Bot Auth

- **Protocol discovery** — MCP server card, Agent Skills, WebMCP, API catalog, OAuth, Auth.md

- **Commerce** — x402, MPP, UCP, ACP



Workflow that actually works:



1. Scan the domain on [isitagentready.com](https://isitagentready.com/).

2. Drop this repo’s GEO file into an LLM.

3. Paste the scan results next to it.

4. Fix crawl / discovery / bot rules first, then rewrite pages so a model can lift a clean answer.

5. Adjust for the niche. A docs site, a SaaS pricing page, and a local service do not need the same protocol stack.


A high agent-readiness score with unquotable marketing copy still loses the answer. 

Strong copy on a site that blocks GPTBot / PerplexityBot never enters the retrieval set.

## Support

If this saved you time: [Donate](github.com/OffcierCia/support)
​​​​​​​​​​​​​​​​​​​​​​​​
