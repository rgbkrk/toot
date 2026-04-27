---
description: Unmute toot sound effects and play a test sound
---
!`rm -f "$HOME/.toot.muted"`
!`afplay "${CLAUDE_PLUGIN_ROOT}/sounds/navi/OOT_Navi_Hello$((RANDOM % 5 + 1)).wav" >/dev/null 2>&1 &`

🧚 Toot unmuted. Navi says hi.
