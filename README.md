# Issue #5138 visual evidence

CSS-only patch tested against main 672d82731 with the installed Astryx 0.5.2 component, React server rendering and Chromium. Actual Astryx CSS, Maka theme/tokens and cascade layers were loaded, with either base or patched product CSS.

At 800, 480 and 320px reading widths, all 21 patched cases fit without horizontal overflow. All 12 baseline long-text cases reproduced clipping. Nine short/divider/icon comparisons retained identical measured layout.

These screenshots show a focused component harness, not the full Desktop app. results.json contains the geometry measurements. Text samples are synthetic/public diagnostics; no user conversation data is included.

Generated-by: OpenAI Codex