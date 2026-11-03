# Brand Studio decisions

This is the durable agreement between the learner and agent. Keep it concise and update it only with agreed choices or actual evidence. `Not chosen yet` is a valid status. Persona cards are hypotheses unless supported by real research.

[LEARNING.md](LEARNING.md) holds the short, reviewable record of learner explanations and help received. Keep the brand decisions and implementation evidence here; link rather than duplicate them.

## Current stage

- Stage: BRAND-001 storefront, live guide, size guide, and two ethical applications implemented; review and merge decision pending.
- Current feature: `BRAND-001` — first branded storefront and live style guide.
- Status: Commit `ba4f256` is local on `feature/brand-001-storefront-styleguide`; learner reports issue #1 is open. Push and PR are pending SSH write access.
- Next small action: Restore SSH write access, then push the feature branch and open its PR.

## Product boundary

The product is the same white T-shirt throughout the comparison. The baseline offers a size selector and temporary demo bag. No real orders, payment, accounts, or persistence. Keep product facts stable between directions; do not add unsupported claims about materials, manufacturing, sustainability, fit, delivery, scarcity, reviews, or sales.

## Audience hypotheses

The primary need guides the page. Give the secondary card one contrasting need to check that same page; keep both cards brief.

| Tiny card                             | Primary audience                                                                                      | Secondary audience                                                                              |
| ------------------------------------- | ----------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Person in a concrete situation        | Student who wears the same few shirts all week and washes them often                                  | Someone buying the shirt as a present                                                           |
| Goal or meaning they seek             | Find an everyday shirt that stays soft and does not shrink                                            | Feel confident choosing something the recipient would like (recipient is inferred from context) |
| Concern before choosing               | Wants a premium-quality shirt that fits their age group and wants fabric details to judge its quality | Not stated yet                                                                                  |
| What the page should help them decide | Which size is suitable and whether available fabric details support their quality expectations        | Whether the shirt is a suitable gift (inferred; needs confirmation)                             |
| Evidence or assumption                | Learner-proposed audience hypothesis; not validated. Product quality claims remain unverified.        | Learner-proposed need; not validated. Recipient wording and page decision are inferred.         |

## Early brand brief

| Decision                                 | Agreement                                                                                                                                                    |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Brand name                               | Cotton Fold                                                                                                                                                  |
| One-sentence promise                     | “A white tee made to be lived in, not saved for later” (proposed; the durability implied by “made to be lived in” is not yet supported by product evidence). |
| Primary archetype: the brand's character | Innocent                                                                                                                                                     |
| Three voice traits                       | Gentle, effortless, youthful                                                                                                                                 |
| One example line in this voice           | “Easy, from the start”                                                                                                                                       |
| Learner's predicted audience effect      | Learner predicts the Innocent character may appeal through a soft, effortless, youthful feel.                                                                |

## Visual decision

Compare two small hero previews before building the whole page. Hold the product, headline, supporting copy, and action identical. Use specific real design references and annotate visual choices, intended effect, and risk.

A simple original SVG wordmark is enough. Show small-size and one-color presentations; they may use the same asset when it works.

| Item                                              | Agreement or evidence                                                                                                                                                                                                                                                               |
| ------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Shared headline / support / action                | Headline: “Plain white, made for every day” (frequent-wear implication unverified); supporting copy: “A simple white tee for easy days and quick mornings”; action: “Choose your size”                                                                                              |
| Modernist preview, reference, and annotations     | [Live preview](public/explorations/modernist.html): Josef Müller-Brockmann, _Der Film_ (1960), MoMA. Quiet editorial grid, serif headline, warm neutrals, rounded action, and arched product field; intent and risk in [notes](docs/explorations/brand-001-directions.md).          |
| Postmodernist preview, reference, and annotations | [Live preview](public/explorations/postmodernist.html): April Greiman, _Your Turn, My Turn_ (1983), Cooper Hewitt. Pastel collage, playful type shadow, tilted product card, and rounded sans-serif details; intent and risk in [notes](docs/explorations/brand-001-directions.md). |
| Chosen direction and reason                       | Postmodern: learner says the soft, colorful design makes it look youthful.                                                                                                                                                                                                          |
| Learner prediction about audience effect          | Predicts the soft, colorful look may feel friendly and low-pressure and attract a younger audience; says it does not communicate quality and wants fabric details. These audience effects are hypotheses, not validated.                                                            |
| Product-intro line and reason                     | Uses Easy, from the start to signal simplicity and convenience for a student lifestyle; learner says this helps more than the size guide.                                                                                                                                           |
| Original SVG logo                                 | Learner approved the [single-color SVG](public/assets/cotton-fold-logo.svg) as shown in the [logo review page](public/explorations/cotton-fold-logo.html).                                                                                                                          |
| Monochrome and small-size variants                | Same single-color artwork at 175px and 110px, plus an inverted one-color presentation; approved as shown.                                                                                                                                                                           |
| Logo review at actual use size                    | Agent visually inspected render at 175px and 110px; images loaded and layout fit at 900px and 390px widths. Learner approved the draft as shown.                                                                                                                                    |
| Shared palette, typography, spacing, and assets   | Storefront and guide currently share the approved Cotton Fold SVG, postmodern pastel tokens, Georgia display family, and Trebuchet MS/Arial body family; learner review pending.                                                                                                    |

## Ethical persuasion

Choose two applications that help the visitor make a voluntary, informed decision. Record their real implementation and mechanism rather than a principle name alone. Required size selection or validation alone does not establish consistency. Do not invent social proof, scarcity, authority, or product facts.

| Principle   | Actual copy or interaction                                                                                                                                  | Visitor benefit / factual support                                                                                                    |
| ----------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Reciprocity | Size guide provides simple measuring steps for a familiar shirt before the visitor chooses a demo size; it clearly says garment dimensions are unavailable. | Practical help is offered without signup or purchase. It cannot confirm fit or recommend a size without actual garment measurements. |
| Liking      | The page uses the line Easy, from the start with gentle language and the approved soft pastel direction.                                                    | A friendly, low-pressure tone may make it more comfortable to explore; this is a hypothesis, not a measured effect or product claim. |

## BRAND-001 — first branded storefront and live style guide

**Scope:** turn the working neutral storefront into the chosen brand's first coherent page. Keep the existing size selector and demo bag usable. Do not add checkout or all future features.

Keep when:

- The learner has chosen the audience hypotheses, brief, visual direction, and logo; the page visibly expresses those choices.
- Two annotated hero directions compare modernist/postmodernist thinking with the same content and real source links.
- The selected SVG logo works at small size and in one color; the presentations may share one asset.
- The storefront and live style guide share CSS variables, typography, components, and assets; they do not drift into separate identities.
- Two ethical persuasion applications are visible and their claims are supportable.
- Prepared checks pass, the agent has reviewed the slice and discussed one actual check, and the learner has reported a browser impression plus keyboard/mobile observations.
- The issue, branch, commit, and PR explain this feature in the learner's repository; agreed decisions and actual evidence are saved here. The learner has approved keeping and merging the change, and the merge into `main` is verified. Publishing is a separate choice.

## Evidence

Write a short result and link only evidence that exists. A passing browser check is evidence for its assertions, not customer research or proof of full accessibility.

| Spec ID   | Files                                                                                                                                                                                             | Issue / PR                                                             | Actual checks and observations                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| --------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| BRAND-001 | [Previews and notes](docs/explorations/brand-001-directions.md), [storefront and size guide](public/index.html), [live guide](public/styleguide.html), [logo](public/assets/cotton-fold-logo.svg) | [Issue #1](https://github.com/mayumizurita/is117brand_studio/issues/1) | Format/lint passed; server tests 7/7 passed; all 10 browser tests printed passing, but Playwright did not exit and was interrupted, so a clean overall exit is unconfirmed. Render inspection at 1440px/390px showed loaded images and no overflow across the storefront, guide, and studio overview. Size guide makes no fit recommendation; fabric facts remain unavailable. Learner first impression, keyboard/mobile observations, and render-check explanation are in LEARNING.md. |

## Later

No follow-up is selected. After keeping `BRAND-001`, choose one next cycle: perhaps a brand story, a supported fit guide, or richer demo-bag behavior. Agree its scope and add one new spec ID at that time.
