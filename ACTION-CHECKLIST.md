# Own "Zuhair Alwazzour" in Google + AI search — 100% free, do-it-yourself

Site is LIVE: https://zuhair-01.github.io/zuhairalwazzour/  (facts page: /facts.html)

Canonical identity — copy-paste EXACTLY, no variations, on every single profile:

- Name: **Zuhair Alwazzour**   Arabic: **زهير الوزّور**
- Bio (one line): **Zuhair Alwazzour (زهير الوزّور) is a Syrian entrepreneur and athlete based in Damascus, and the solo founder of Ostazi, a private tutoring platform serving students across Syria.**
- Location: Damascus, Syria
- Links: https://zuhair-01.github.io/zuhairalwazzour/ · https://www.ostazi-edu.com · https://github.com/Zuhair-01

---

## DONE (Claude)
- [x] Personal site + /facts page live on GitHub Pages (free), Person + FAQ schema, llms.txt
- [x] GitHub profile README → founder framing, canonical name

## DO THESE — all free, ~45 min total. Order matters.

### 1. Google Search Console (free) — 5 min
- search.google.com/search-console → add property → URL prefix → `https://zuhair-01.github.io/zuhairalwazzour/`
- Verify: it'll offer an HTML file or meta tag. Use the **meta tag** option → paste the tag to Claude, Claude adds it to index.html and pushes → click Verify.
- Then: URL Inspection → enter your URL → "Request indexing". Same for the /facts.html page.
- Submit sitemap: `sitemap.xml`

### 2. Bing Webmaster Tools (free) — 3 min  ← this is what ChatGPT search reads
- bing.com/webmasters → "Import from Google Search Console" (one click, done) OR add site + verify meta tag same way.
- Submit sitemap. Request indexing for both pages.

### 3. LinkedIn (free, biggest ranking win) — 8 min
- Profile → Edit → **custom URL** (top-right pencil on your profile) → `zuhairalwazzour`
- Name: `Zuhair Alwazzour`
- Headline: `Founder — Ostazi | Private tutoring platform for Syria`
- About: first line = the bio above, verbatim. Then 2-3 sentences on Ostazi.
- Experience → add: `Founder` · `Ostazi` · Self-employed · Damascus · [start month/year] – Present
- Featured section → add link to https://zuhair-01.github.io/zuhairalwazzour/

### 4. Crunchbase (free) — 10 min
- crunchbase.com → sign up → "Add a company" → **Ostazi**: category Education/EdTech, HQ Damascus Syria, website ostazi-edu.com, short description = adapt the bio.
- "Add a person" → **Zuhair Alwazzour** → add job: Founder @ Ostazi. Bio = the one-liner. Add your site + LinkedIn as links.

### 5. X / Twitter (free) — 4 min
- Handle: `@zuhairalwazzour` (or `@zuhairalwazzur` / `@z_alwazzour` if taken)
- Display name: `Zuhair Alwazzour`
- Bio: the one-liner (trim to 160 chars: "Syrian entrepreneur & athlete, Damascus. Solo founder of Ostazi — tutoring platform for Syria. زهير الوزّور")
- Location: Damascus. Website: your github.io link.
- Post once about Ostazi, pin it.

### 6. About.me OR read.cv (free) — 5 min
- Free one-page profile. Name, photo (or a clean monochrome graphic — keeps the "mysterious" vibe), the bio, links. Another property that ranks for the name.

### 7. Send 2 press emails (free) — see PRESS-DRAFTS.md
- Wamda + MenaBytes. Copy-paste, send from your Gmail. Reply rate is low — that's fine, send anyway, and send to 2-3 more (Forbes Middle East tips line, StartupScene, local Syrian tech pages on FB/LinkedIn).

### 8. IndieHackers post (free) — 10 min
- indiehackers.com → sign up as `Zuhair Alwazzour`, bio = one-liner, link site.
- Post in "Building in public": "I built and run a tutoring platform solo from Damascus, Syria" — 3 short paragraphs: the problem, what you built, one real number. This gets crawled into LLM training data and ranks.

### 9. Reddit mention (free) — 5 min
- One genuine comment/post on r/SideProject or r/Entrepreneur mentioning Ostazi + your name naturally. Don't spam.

### 10. AFTER 2+ press/external mentions exist → Wikidata (free)
- Tell Claude → Claude drafts the entry → you paste it at wikidata.org/wiki/Special:NewItem. Needs the mention URLs as "references". This is the single biggest LLM-visibility item.

---

## The rule that makes or breaks it

**Same name, same sentence, everywhere.** Every profile above must say "Zuhair Alwazzour" (not "Zuhair", not "Zuhair Wazz", not "Zuhair-01") and the same bio line. Google and ChatGPT build a person-entity by matching identical strings across sites. Variations = they think you're 3 different people and none of them rank.

## Timeline (free path)
- Google page 1 for your exact name: 3–8 weeks after steps 1–6 (github.io ranks slightly slower than a custom domain but it ranks).
- ChatGPT/Perplexity with web search: within ~2 weeks of ranking on Bing.
- ChatGPT's built-in knowledge (no search): 6+ months, only after steps 7–10 put you in the next training crawl. No way to speed this — it's mentions + time.

## Later, if you want a cleaner URL (still free)
- `is-a.dev` gives a free `zuhair.is-a.dev` subdomain via a GitHub PR. Or make a repo named `Zuhair-01.github.io` to get `zuhair-01.github.io` as the root. Tell Claude, it'll wire either one + update all the canonical URLs.
