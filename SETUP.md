# AI RFC — repo setup

Prep only. Nothing here publishes itself. Tee creates the repo — Muse cannot.

## Why Tee creates it

The Muse GitHub App cannot create repositories — it gets a 403 when it tries. It can only work inside repos that already exist and that Tee has selected for it. So there is no working route for Muse to create this repo. Tee creates the empty repo on github.com, then the files go in. That is the whole blocker, stated plainly.

## Suggested repo name

**`ai-rfc`**

Short, matches the document, easy to link. If Tee wants a different name, use that instead — just tell Tim the exact name so the push goes to the right place.

Suggested description for the repo page:

> The AI RFC — a protocol defining AI maturity levels 1–5, from one working setup. Plain words, no hype.

## License — Tee's pick, not Tim's

No `LICENSE` file is included yet, on purpose. Pick one, then Tim adds that file.

- **MIT** — lets anyone use, copy, change, and sell the work, as long as they give credit.
- **CC BY** — lets anyone share and adapt the writing, even commercially, as long as they give credit.

One line each, that is the difference that matters here: MIT is the usual pick for code, CC BY is the usual pick for writing. This RFC is writing. Tee picks — Tim does not pick it for him.

## Step-by-step: create the empty repo

1. Go to https://github.com/new — sign in as Tee if it asks.
2. **Repository name:** `ai-rfc`
3. **Description:** `The AI RFC — a protocol defining AI maturity levels 1–5, from one working setup. Plain words, no hype.`
4. **Public.** (It is meant to be read and argued with — that is what an RFC is for.)
5. Leave **all** of these OFF / empty: do NOT tick "Add a README file", do NOT add a .gitignore, do NOT choose a license here. The repo must start empty, or the push will clash with what GitHub puts in it.
6. Click **Create repository**.
7. GitHub shows an empty-repo page with a URL like `https://github.com/<your-username>/ai-rfc`. That URL is the proof it exists. Keep it.

## Step-by-step: get the files in

Pick one route. Route A is the simplest if Tee wants to do it himself. Route B is the least work for Tee.

### Route A — upload on github.com (no terminal)

1. On the empty repo page, click **uploading an existing file** (or the "Add file" button, then "Upload files").
2. Upload these three files from Tim's handoff in main chat:
   - `README.md`
   - `AI-RFC.md`
   - `SETUP.md` (this file — optional to keep in the repo, fine to leave in)
3. At the bottom, commit message: `Add AI RFC v2`
4. Click **Commit changes**. Done — the repo is live with v2 in it.

### Route B — Tim pushes after Tee creates it

1. Tee creates the empty repo as above.
2. Tee tells Tim the exact repo name (and his GitHub username if it is not obvious from the URL).
3. Tee selects the new repo for the Muse GitHub App, so Tim can reach it — GitHub will offer that when Tim asks, or under Settings → Connectors → GitHub.
4. Tim pushes `README.md` and `AI-RFC.md` into it and reads them back to verify they landed.
5. Tim reports back in main chat with the live repo link.

Do not do both routes — pick one, or the second push will just say "nothing new" at best and clash at worst.

## After the push

- Tee picks the license (MIT or CC BY above). Tim adds the matching `LICENSE` file.
- If Tee wants the live page linked from the repo, it is already in the README: https://taigtsp.duckdns.org/way-i-use-ai/
- Future versions: v3 folds in corrections and comments. The source of truth stays `~/workspace/your_files/ai-rfc/ai-rfc.md` — the GitHub copy follows it, not the other way round.

## Files in this prep folder

- `README.md` — short version: what it is, the 1–5 scale, three lenses, Tee at 3.5 / setup at 3.
- `AI-RFC.md` — the full v2 protocol, byte-identical to `~/workspace/your_files/ai-rfc/ai-rfc.md`.
- `SETUP.md` — this file.
