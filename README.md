# Understanding and Using GenAI: Resources for Critical Practice

A static website with seven AI education modules for I301 undergraduates at the UT Austin School of Information.

## Structure

- `index.html`: overview (about, learning path, module cards, all resources)
- `module0-nlp.html` … `module6-integrity.html`: one page per module
- `assets/style.css`: shared styles (supports light and dark mode)

| # | Module |
|---|--------|
| 0 | NLP Foundations: next-word prediction |
| 1 | Transformers and language models |
| 2 | Prompting techniques as options to test |
| 3 | Moving from prompts to skills |
| 4 | Evaluating responses as texts (includes the diagnose–revise–retest activity) |
| 5 | UT tools and model selection |
| 6 | Intellectual contribution and attribution |

## Publish with GitHub Pages

1. Create a new GitHub repository and upload every file in this folder, including `.nojekyll`.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. After a minute, the site is live at `https://<username>.github.io/<repo-name>/`.

No build step is needed. To preview locally, open `index.html` in a browser.
