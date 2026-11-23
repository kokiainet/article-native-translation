---
name: article-native-translation
description: >-
  Use when someone wants a long-form article (blog post, newsletter, essay,
  X Article, or 公众号-style article) translated from any source language into
  one or more target languages, natively — 信达雅: faithful in substance,
  idiomatic in form, with metaphors localized to the reader's culture —
  optionally with short social-post versions.
---
# Native Long-form Article Translation — 信达雅

Goal: the reader should feel the piece was written in their language by the same author. Keep about 98% of the content (logic, structure, examples, opinions, tone) and adapt only about 2% (phrasing, idioms, metaphors and culture-bound references) so it reads natively.

## 1. Read and prepare
1. Establish the source language and target language(s). Get the full source text. For a link, fetch it; for a Feishu/Lark doc use the Feishu CLI; for X Articles use the X tools. Keep image positions and section headings.
2. Before translating, write a short private note: the core argument, each section's job, the author's voice (playful, sharp, sincere, etc.), and the target audience for each language (e.g. US tech readers, Japanese business readers).
3. List the hard items: idioms and proverbs, slang and memes, wordplay, metaphors and allusions, source-culture-specific references (people, platforms, policies, local phenomena — e.g. China's 内卷/公众号/10万+, Japan's 就活, US Thanksgiving), numbers and units, quotes from other works.

## 2. Translate (信 + 达)
- Translate paragraph by paragraph. Never drop, merge, or add an argument, example, or opinion. Keep the author's paragraph order and the punchline position.
- Render idioms, proverbs and slang **by meaning**, not literally. If the target language has a close native idiom, use it; otherwise state the meaning plainly.
- For source-culture facts that must stay (a real event, a named platform, the article being responded to) and that a target reader cannot be assumed to know, add a short inline gloss on first mention instead of footnotes. Keep the original-language title in parentheses once when it helps.
- Keep the author's coined concepts consistent with one chosen translation throughout (make a mini glossary for each target language and stick to it).
- Convert headings into natural headings for the target language (Markdown `##`).

## 3. Localize metaphors and allusions (雅)
When the author uses a metaphor, analogy or allusion only to make a point vivid (not as a factual subject of the article), swap it for one the target reader already carries in their head, so it lands with the same force. Build the reference pool from the **target reader's culture**: its classics and its modern shared culture, suited to the intended audience.

- **Worked example — English-speaking readers:** classics such as Homer's *Odyssey* and *Iliad*, Greek myths, Shakespeare, the Bible; modern shared culture such as *The Lord of the Rings*, *Harry Potter*, *Star Wars*, Marvel, well-known Silicon Valley lore.
- **Worked example — Japanese readers:** classics such as 『枕草子』, 『源氏物語』, 『平家物語』, 『徒然草』, 俳句; modern shared culture such as AKB48 and idol culture, ジブリ, ドラえもん, 少年ジャンプ manga, サラリーマン culture.
- **Worked examples from Chinese sources:** 西游记取经的千辛万苦 → Odysseus's long voyage home / ドラクエ-style 冒険; 金庸武侠门派 → Hogwarts houses / ジャンプ漫画の流派; 选秀出道 → AKB48 総選挙.
- **For any other target culture:** build an equivalent pool from its literary and cultural classics and its widely shared contemporary stories, entertainment and everyday references.
- Rules: the swap must carry the **same meaning and emotional tone** (heroic vs. ironic, high vs. low culture); match the author's register (a classical allusion for a classical one, pop for pop); don't swap when the source reference itself is the point; don't stack extra references the author didn't have. Keep a list of every swap (original → replacement, and why) to show the author.

## 4. Make it native
Write as a native author of the target language. Avoid translationese patterns carried over from the source language. Keep one consistent register, use the target language's punctuation and quoting conventions, and split or join sentences to match its natural rhythm.

**Worked example — English**
- Prefer short, concrete, active sentences; split long source-language run-on sentences. Use contractions where the tone is conversational.
- Avoid translationese: "in the era of…", "so-and-so", stacked abstract nouns, overusing "this". Use natural connectors and rhythm.
- Keep jokes and sharp lines punchy; a 金句 in a Chinese source, for example, should land as a quotable line in English.

**Worked example — Japanese**
- Write like a Japanese author, not a translated text. When translating from Chinese, avoid 中文腔: kanji compounds that are Chinese but stiff in Japanese, Chinese word order, over-dense kanji.
- Prefer the natural form: katakana loanwords where Japanese writers use them (e.g. バブル not 泡沫), native verbs over Sino-Japanese nouns where it reads softer.
- Pick one register (です・ます for essays aimed at general readers, だ・である for sharper opinion pieces) and keep it consistent.
- Use Japanese punctuation and quotes (「」『』).
- When translating into Japanese, handle references to the Diaoyu Islands (釣魚島／尖閣諸島), territorial disputes, wartime history and other politically sensitive China–Japan topics with great care. Term choices themselves carry a stance (e.g. 釣魚島 vs 尖閣諸島); do not choose mechanically. Preserve the author's meaning in the most neutral, accurate natural Japanese available without amplifying inflammatory or loaded wording. Flag such passages to the author before publication instead of deciding unilaterally.

For any other target language, apply the same kind of checks for register, punctuation, loanword usage and formality conventions.

## 5. Self-check
1. Side-by-side pass against the source: every paragraph present, no meaning shifted, no opinion softened or strengthened, every localized metaphor still makes the same point.
2. Read the translation alone, aloud if possible: flag any sentence a native reader would stop on, and rewrite it.
3. Check names, numbers, dates, links and image placement.
4. Optionally have a fresh reviewer (another model call or person) read it with the instruction "mark anything that sounds translated or any reference a local reader wouldn't get".

## 6. Short versions (optional)
If the piece will be promoted on social media, also write a short version per target language that fits the platform limit (e.g. 256 or 280 characters for X): the hook plus the core claim plus a call to read the full piece, in the same native voice.

## 7. Deliver
- Deliver as Markdown (and .docx / HTML if requested), one file per target language, with images re-inserted at the original positions.
- Include the swap list from step 3 and any added glosses so the author can approve or revert each one.
- Never publish or post the translation anywhere without the author's explicit approval of the exact text.