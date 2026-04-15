---
description: Show whether toot sounds are muted
---
!if [ -f "$HOME/.claude/toot.muted" ]; then echo "🤫 muted"; else echo "🔊 unmuted"; fi
