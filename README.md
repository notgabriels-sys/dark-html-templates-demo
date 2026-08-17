# Dark HTML Templates — live demo

**→ [notgabriels-sys.github.io/dark-html-templates-demo](https://notgabriels-sys.github.io/dark-html-templates-demo/)**

Eight self-contained dark website templates. One `index.html` each, CSS inline —
no build step, no dependencies, no framework, nothing loaded over the network.

| Template | What it's for |
|---|---|
| [portfolio](https://notgabriels-sys.github.io/dark-html-templates-demo/portfolio/) | Developer / creative portfolio |
| [landing](https://notgabriels-sys.github.io/dark-html-templates-demo/landing/) | Product / SaaS landing page |
| [link-in-bio](https://notgabriels-sys.github.io/dark-html-templates-demo/link-in-bio/) | One hub for socials and releases |
| [docs](https://notgabriels-sys.github.io/dark-html-templates-demo/docs/) | Documentation — sidebar, code blocks, callouts |
| [pricing](https://notgabriels-sys.github.io/dark-html-templates-demo/pricing/) | Plans, comparison table, FAQ accordion |
| [changelog](https://notgabriels-sys.github.io/dark-html-templates-demo/changelog/) | Versioned release notes |
| [waitlist](https://notgabriels-sys.github.io/dark-html-templates-demo/waitlist/) | Coming soon + email capture |
| [resume](https://notgabriels-sys.github.io/dark-html-templates-demo/resume/) | One page, prints to a clean PDF |

## How the theming works

Every template reads the same nine CSS variables:

```css
--bg  --surface  --hair  --ink  --mute  --faint  --accent  --accent-2  --accent-dim
```

The full pack ships 50 hand-tuned dark palettes. Re-skinning any template is copying one
`:root` block and pasting it over the template's own — no config, no preprocessor, no build.

## This repo

Static demo only. The full pack — all eight templates plus the 50 palettes and the license
for unlimited personal and commercial use — is at
**[notgabriel.gumroad.com/l/cfcvmy](https://notgabriel.gumroad.com/l/cfcvmy)**.

Same palettes as [50 dark themes for Claude Code](https://github.com/notgabriels-sys/claude-code-50-dark-themes)
(free, MIT), if you want your terminal to match.
