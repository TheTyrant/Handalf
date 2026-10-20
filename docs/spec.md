# Handalf: 1of10 process mapped to the engine

Tagline: Find the magic in your stories.

## What 1of10 does
1. Outlier score: a video's views divided by its channel's typical views. 10x to 100x marks an outlier.
2. Outlier Finder: search a topic, results ranked by outlier score.
3. Idea Generator: connect a channel so the AI learns niche and style, then remix ideas for variations.
4. Bookmarks and tracked channels: a swipe file of saved winners.

## How Handalf translates it
1. Channel average becomes the consensus: the takes most creators would make on a topic (the 1x baseline).
2. Connected channel becomes the brand profile plus a stance bank mined from the creator's own AI conversations.
3. Outlier score becomes the take multiple: (divergence/5) x (ownership/5) x (defensibility/5) x (0.5 + fit/10). Tiers: 5x+ Outlier, 2.5x Strong, 1.2x Fresh, below that Echo.
4. Ownership only scores high when one of the creator's own stances backs the take, cited with their words.

## Current flow (v9, Oct 20, 2026)
1. Landing page (also what Start over opens): "What are we talking about?" with Conjure content. An icon row switches the same space, one mode at a time, to the brand quiz (one question at a time with the wizard owl, 12 archetypes, then niche and expertise), link your LLM (copy a profile prompt into ChatGPT, Claude or Gemini and paste the answer back), upload a prompt or brief, or erase everything. Lines only, no pills or rounded boxes.
2. Engine: topic in, consensus map plus ranked contrary takes shaped by archetype and expertise.
3. Remix: add personal context or talk the take through with an interviewer; rebuilt takes cite stances pulled from that dialogue.
4. Vault: no cap. Grouped by idea or by date. Each take is a single post with a date, or a 3 to 6 episode series with a start date and cadence.
5. Export: pick concepts and choose one or more media per take (text, audio, video; several makes it mixed content with a version per medium). Each version gets an outline for its medium plus image prompts for image generators, and video versions get shot prompts for text-to-video tools. Filter by medium and download labeled Word docs: "Handalf video plan", "Handalf video prompt", and a "Shot and image prompts" pack.
6. Start over: new search, redo brand setup, or erase everything.

## Look
Two editions, switched by tapping the book logo: Leather bound (brown leather with light monochrome noise, gold lines, gold serif tabs and headers) and Paperback (black and white paper and ink line art, a children's book for business people). Web app layout: header fixed at the top, the icon row fixed as a footer, only the middle scrolls. Uncial wordmark, Cinzel titles, EB Garamond content titles. Logo: a book with Handalf's face on the cover, drawn in the other edition's colors so it previews the switch. Handalf, full body, rests on a branch that runs off the left edge of the screen and waves his wand to bring in each question.

## Tied to Claude today
1. AI calls (engine, remix, interview, outlines) run on the viewer's Claude account. Standalone needs a small server holding an AI API key.
2. Saved data (profile, stances, vault) lives in the viewer's Claude account. Standalone needs its own database.
3. Sign-in uses the viewer's Claude login. Standalone needs its own sign-in.
4. Word export already works in any browser.

## Next
Real connections to other LLMs and agents to pull conversations and profile directly. Real platform outlier data to weight topics. Google sign-in for a direct Save to Google Docs once standalone.

## Idea: "May I read your LLM notes?"
A starter dialogue from Handalf, with Yes and No. Yes opens the best available route:
1. Handalf as a connector (most promising). Handalf runs as an MCP server. The user adds it to ChatGPT or Claude as a custom connector, then asks their own assistant to send Handalf their profile and opinions. Their assistant already has their memory, and the user approves the share inside it.
2. Data exports. ChatGPT, Claude and Google (Gemini through Takeout) all let users export their chats. Handalf already reads these. A guided "fetch your export" flow per app would make it smoother.
3. Paste a profile (works today). Handalf writes the prompt, the user's assistant answers, the user pastes it back.
Not recommended: a browser extension that reads chat pages. It breaks easily and runs into the apps' terms.
Note: none of the big chat apps offers an API for reading a user's chat history (as of Oct 2026), so routes 1 and 2 are how a standalone Handalf gets this data.
