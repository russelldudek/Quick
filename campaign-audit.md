# Campaign Audit

## User-steering revision delta

**Observed defect:** the public repository did not contain the deployable campaign or its linked stylesheet assets. The site could not load its visual system.

**Why the prior audit missed it:** the local browser test replaced linked assets with local inline content before rendering. That proved the rules could render but did not prove `brand-tokens.css`, `styles.css`, `styles-components.css`, `app.js`, routes, images, and PDFs existed or could be retrieved from public `main`.

**Rejected execution:** compressed source plus a workflow-dependent materialization step, combined with a local-only inline-asset browser pass.

**Approved correction:**

- publish the actual source files directly to `main`;
- link three explicit CSS files on every route;
- test the browser request pipeline rather than injecting local assets;
- generate PDFs from the exact public HTML/CSS;
- fail publication when any route, stylesheet, script, or PDF is missing, empty, or mispaginated;
- preserve keyboard tabs, roving focus, reset, hardening, causal state changes, reduced motion, reciprocal document navigation, and exact Letter geometry.

## Strategic argument

- Nominal role: develop and optimize AI models, pipelines, APIs, production integrations, framework choices, and technical documentation.
- Inferred mandate: make enterprise AI operable across outcome, context, model behavior, runtime, human authority, evidence, reliability, economics, and ownership.
- Thesis: `Enterprise AI scales when every model sits on an operable backplane.`
- Operating artifact: six-contract Enterprise AI Backplane, keyboard-operable production fault drill, and printable Backplane Review.
- Strongest objection: verified evidence does not support presenting Russell as a five-year foundation-model researcher, recent PyTorch/JAX specialist, or owner of a large production MLOps estate.
- Response: state the boundary directly and test fit for a systems role centered on integration, controls, reliability, workflows, evidence, and ownership.

## Source-level QA contract

The publication workflow verifies:

- six non-empty HTML routes;
- `brand-tokens.css`, `styles.css`, `styles-components.css`, and `app.js` exist and load as linked resources;
- all six routes reference all three stylesheets;
- the homepage references the interaction script;
- five PDFs are rendered from the public routes;
- resume page count `2`;
- cover-letter page count `1`;
- interview-brief page count `3`;
- first-90-days page count `3`;
- Backplane Review page count `1`;
- candidate name, phone, email, fit-boundary language, and credential order remain present in generated PDFs;
- interaction source retains arrow-key navigation, ARIA selection, reset, and hardening controls.

## Local rendered QA completed before publication

- Browser routes: all six HTML routes.
- Viewports: desktop, laptop, tablet, and mobile.
- States: default, four fault scenarios, hardened state, reset, keyboard navigation, and reduced motion.
- Documents: full-page previews, mobile reflow, print canvases, reciprocal navigation, contact information, and footer safety.
- PDF pages: all ten pages rasterized and visually reviewed in the approved branded build.
- Confidentiality: zero public internal-system-name matches in authored public source.

## Brand and candidate distinction

- Company label: `Quik Hire Staffing` in the posting; `Quick Hire` public identity.
- End client: undisclosed and not inferred.
- Public recognition layer: clearly typeset company name plus source-sampled violet/periwinkle tokens.
- Candidate originality: Enterprise AI Backplane, production fault drill, scorecard, review worksheet, and role-specific thesis.
- Independent-work distinction: present on every route and document surface.

## Completion boundary

This record may state `complete` only after the complete manifest is re-fetched from `main`, the final main head is captured, and the live Pages routes, linked CSS, reciprocal document navigation, interaction, and PDF responses are verified against that head.
