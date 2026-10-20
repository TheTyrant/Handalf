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
1. The storybook (first visit): a full-screen book that opens from a leather cover. Chapter one introduces Handalf, chapter two is the brand quiz one question per page (each answer is inscribed on the page as you choose it, then the page turns), chapter three reveals the archetype (changeable), chapter four records niche, audience, expertise and platforms, and the last page starts conjuring. Settings: Retake the quiz reopens it at question one; Reread my story retells the answers as read-only pages. Skip closes it.
1b. Landing page (also the home for the footer icons): "What are we talking about?" with Conjure content; the dialogue drifts between Conjure, Handalf's quiz invite and Link LLM or bio.
2. Alchemy (the engine): topic in, consensus map plus ranked contrary takes shaped by archetype and expertise.
3. Remix: add personal context or talk the take through with an interviewer; rebuilt takes cite stances pulled from that dialogue.
4. Library: a library of books on shelves. The first shelf holds the Book of your spell book (archetype, niche, expertise, elements, with Reread, Retake and Edit). Takes are shelved by idea or by date; series are thicker books; spine color marks the medium. Opening a book shows its planner: single post or 3 to 6 episode series with dates and cadence.
5. Conjurings (export): pick concepts and choose one or more media per take (text, audio, video; several makes it mixed content with a version per medium). Each version gets an outline for its medium plus image prompts for image generators, and video versions get shot prompts for text-to-video tools. Filter by medium and download labeled Word docs: "Handalf video plan", "Handalf video prompt", and a "Shot and image prompts" pack.
6. Start over: new search, redo brand setup, or erase everything.

## Look
Three editions, cycled by tapping the book logo: Leather bound (leather and gold header and footer around cream pages with deep gray text), Chalkboard (slate green, chalk white text, yellow chalk accents) and Paperback (black and white paper and ink line art, a children's book for business people). Web app layout: header fixed at the top, the icon row fixed as a footer, only the middle scrolls. Uncial wordmark, Cinzel titles, EB Garamond content titles. Logo: a book with Handalf's face on the cover, drawn in the other edition's colors so it previews the switch. Handalf, full body, rests on a branch that runs off the left edge of the screen and waves his wand to bring in each question.

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
