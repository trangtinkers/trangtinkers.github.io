---
layout: post
title: "Tools & Workflows I Invented On Principle (Jan–Mar 2026)"
date: 2026-03-04
categories: jekyll update
---

## Code Shipped

| Item | Date | Status |
|---|---|---|
| Stacker DSL (reader + macro expander) in Racket | Jan 20–22 | Completed |
| Matrix-vector multiplication module in Racket | Jan 26 | Completed |
| PowerShell `git-summary` alias | Jan 30 | Completed |
| Single-neuron malt training demo | Jan 16 | Completed |
| UHG visual explorer (Klein disk, drag-point) | Feb 13 | Completed + discarded |
| Quadrance computation table | Feb 17 | Completed + discarded |
| `cross_ratio_proj()` Python function | Feb 18 | Completed |
| `quadrance()` + `loss()` PyTorch embedding functions | Feb 23 | Written, framing paused |
| instacomments README fix | Feb 19 | Shipped |
| Bilinear form Scheme DSL stubs | Mar 2 | Exploratory |

---

## Original Frameworks Invented

1. **"Seeing Tools" as a design philosophy** — DSLs, visualizers, tables as instruments for making invisible structure visible. Coined and elaborated across Feb 13–25. "Inventing on Principle at its finest! Bret Victor would be proud of me."

2. **"Probing" as a research epistemology** — when facing an opaque system, don't demand a theory first; send cheap experiments and read the echoes. Crystallized Feb 26. "This is how working mathematicians actually experience the subject."

3. **UHG as an "API to the hyperbolic plane"** — Universal Hyperbolic Geometry as a kernel/seeing tool for hyperbolic ML, replacing classical logmap/expmap. Feb 28. "Universal Hyperbolic Geometry is an interface to the API of the hyperbolic plane, one whose implementation I could not take a peek at."

4. **DSL-as-cheaper-neural-net argument** — structured domains don't need neural nets if you design the right language. Jan 18. "Often, creating a domain specific language is a much cheaper solution!"

5. **"Math as DSL / proofs as programs"** — arrived at the Curry-Howard correspondence organically through the stacker work. Jan 21. "Now, I see math as choosing the right language. Proofs are just programs that type-check."

6. **Conceptual Design as constraint analysis** — a design without forcing functions cannot evolve. Applied to UHG Feb 15. "Limitations are forcing functions. But right now UHG has no forcing functions."

---

## Workflows Developed

1. **REPL + Claude Code learning loop** (DrRacket + timed work sessions) — Jan 15 onward, sustained. "REPL-based interactive development might solve my problem with slow feedback loops."

2. **`uv` Python project workflow** — adopted Jan 23, ongoing. Figured out through trial and error: `uv init` → `uv add` → `uv sync` → `uv run`.

3. **Intermediate artifacts for learning hard math** — build a series of visualizations, each making one property salient while hiding others. Feb 18. "The quadrance computation table (makes the 1/(1-r²) blowup salient, hides the projective formalism)."

4. **Live-blog while working** (Roam capture → Twitter) — Feb 18, active. "This workflow just grew organically during this work session. Everything that turned out well in my life followed the same design process."

5. **Reply-to-build-audience Twitter strategy** — high-quality replies to niche-popular users rather than broadcasting to a general audience. Working: DefenderOfBasic turned on notifications, +6 followers from one reply.

6. **Somatic processing before cognitive work** — exercise/emotional release as prerequisite to focus. Feb 12–21. "I felt depressed until 6 pm. Then, I decided to go on a walk and exercise. Now, I'm working again like nothing happened."
