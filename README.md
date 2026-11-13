# Cinematic Web Architect v9.1

**Outcome-first Agent Skill for original cinematic, interactive and scroll-driven websites.**

This public repository contains **one master Agent Skill file**, not a multi-plugin installer:

[**View complete SKILL.md**](skills/cinematic-web-architect/SKILL.md)

## One-command install

```bash
npx skills add namanahir128-stack/cinematic-web-architect --skill cinematic-web-architect -g
```

Then restart the coding-agent session and confirm the skill is listed/activated.

Already installed? Refresh it using `npx skills update cinematic-web-architect -g` (check your Skills CLI version).

For a particular coding agent select it interactively, or use `-a codex` / `-a claude-code` where supported. You can use `--copy` where symlinks are unavailable.

## What changed in v9 / v9.1

User feedback on the preceding output was **5–6/10**, not 10/10. This upgrade addresses the failure mode rather than claiming the visuals have already been fixed.

- **Reference forensics first:** understand actual composition, story, texture, interaction and shot timing from observed/reference-video evidence.
- **Tool ecosystem routing:** REA, MengTo Skills, Sharp Design, Motion Primitives, current 21st MCP, Figma MCP, browser DevTools and 2.5D/3D render paths.
- **Visual proof before full build:** multiple competing hero directions, real asset map and approved keyframes.
- **Outcome-oriented QA:** desktop/mobile screenshots, actual forward/reverse scroll recordings, and replacement of poor visuals before superficial polish.
- **No forced rendering stack:** select 2.5D, media sequences, WebGL or DOM based on shot needs, available authorized tools and asset quality.
- **No unsupported quality claims:** a full working site and human visual review are still required.

### Additional v9.1 evidence requirements

- Two distinct **actual rendered** hero styleframes before full implementation, wherever rendering tools exist.
- Desktop and mobile visual proofs with real file paths and asset provenance; never invent a screenshot or QA pass.
- Copyable Playwright browser-QA recipe in the single master SKILL.md (for use in a real project, not a pre-run test).
- A rebuild-vs-polish diagnostic so generic hero art triggers **asset/composition replacement**, not extra particles or glow.
- Independent creative critique and two different-style benchmarks before any production-quality claim.

### Tool and research references

- REA: https://github.com/morluto/rea (MCP setup separate from skill)
- MengTo Skills: https://github.com/MengTo/skills
- Sharp Design: https://github.com/ostaver/Sharp-design (self-reported scores are not independent benchmarks)
- Motion Primitives: https://github.com/ibelick/motion-primitives
- 21st MCP: https://21st.dev/mcp (API/credits depend on account)
- Figma MCP: https://developers.figma.com/docs/figma-mcp-server/
- Paper MCP: https://paper.design/docs/mcp
- React Bits: https://github.com/DavidHDev/react-bits (review license/Commons Clause)
- GSAP Skills: https://github.com/greensock/gsap-skills
- Spline exporting: https://docs.spline.design/exporting-your-scene/web/exporting-as-code
- Theatre.js: https://www.theatrejs.com/docs/latest/manual/studio
- Chrome DevTools MCP: https://github.com/ChromeDevTools/chrome-devtools-mcp
- Trionn case study: https://tympanus.net/codrops/2026/07/15/the-architecture-behind-trionn-coordinating-gsap-three-js-lenis-and-web-audio/
- Sketching the Impossible: https://tympanus.net/codrops/2026/06/11/sketching-the-impossible-a-3d-portfolio-built-without-a-single-3d-model/

**Installing this skill does not install third-party MCP servers, Blender, browser tools or paid services.** It instructs agents how to use those tools when already authorized and available. Always inspect third-party source licenses, permissions and pricing before downloading, running or reusing components.

## Quick benchmark prompt

> Use cinematic-web-architect. Build an original cinematic, scroll-driven coffee website as a fully runnable experience. Make the opening hero visually outstanding, show a meaningful Beans → Brewing → First Sip narrative, and include one coffee-specific interaction. Inspect the live page on desktop and mobile, fix the three largest visual defects, and show actual screenshots or state honestly why unavailable.

## Contribution policy

The repository is public, so anyone can read, install or fork it. Only the owner and explicitly authorized collaborators can push to the original. Suggestions can be made through pull requests or issues; no contributor's PR merges without an authorized maintainer.

See [LICENSE](LICENSE).
