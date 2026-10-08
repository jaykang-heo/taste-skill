# rune adapter

This fork exists so rune's build-design-system can stand on upstream work instead of rebuilding it.
Rule: never edit upstream files here; rune-side changes live only in this rune/ directory.
Weekly sync: `git fetch upstream` then fast-forward main; re-check this adapter after each sync.

- Upstream: https://github.com/Leonxlnx/taste-skill
- Licence notice: MIT (Copyright (c) 2026 Leonxlnx); full text in the upstream LICENSE file.
- What we use: taste and direction layer: Design Read one-liner plus DESIGN_VARIANCE/MOTION_INTENSITY/VISUAL_DENSITY dials (skills/taste-skill/SKILL.md sections 0-1).
- Rune seam: rune build-design-system intake-to-direction step (SKILL.md section 1).
