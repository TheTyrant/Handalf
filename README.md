# Handalf

Make Content Magical.

Handalf is a contrarian content engine for creators. You give it a topic, and it maps what most creators in your space would say about it (the 1x baseline). It then ranks contrary takes by how far they move from that baseline and how well your own stances back them up.

## How it works

1. **Landing.** "What are we talking about?" opens every visit. Type a topic and Conjure content, or switch the same space to the brand quiz, link your LLM, upload a prompt, or erase everything.
2. **Stances.** Drop in ChatGPT or Claude conversation exports. Handalf reads only your side of each chat and pulls out the positions where you pushed back.
3. **Engine.** Enter a topic and get a consensus map plus ranked takes. Each take is scored on divergence, ownership, defensibility and fit.
4. **Remix.** Add your own context, or talk a take through with the interviewer, then rebuild it.
5. **Vault.** Plan each take as a single post or a series, with dates and a cadence.
6. **Export.** Pick text, audio or video for each concept, outline them, and download the plan or a ready-to-use prompt as a Word doc.

## Running it

`index.html` is a single self-contained page. It currently runs as a Claude artifact: AI calls, saved data and downloads go through the viewer's Claude account. To run it on its own, it needs a small server for the AI calls, a database, and user sign-in. See `docs/spec.md`.
