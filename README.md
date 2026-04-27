# 🧚 toot

> Hey! Listen!

Ocarina of Time sound effects for Claude Code. Navi chirps on permission prompts, menu blips on replies, bonks on errors.

## Install

Add the marketplace, then install the plugin:

```
/plugin marketplace add rgbkrk/toot
/plugin install toot@toot
```

## Sounds

| Event              | Sound                      |
| ------------------ | -------------------------- |
| Session start      | Navi "Hello!"              |
| Permission request | Navi "Listen!"             |
| Notification       | Navi "Hey!"                |
| Stop (reply done)  | Dialogue-done chime        |
| Tool failure       | Navi "Bonk"                |

## Commands

- `/toot:mute` - silence everything
- `/toot:unmute` - bring Navi back (plays a test chime)
- `/toot:status` - check whether sounds are on
- `/toot:play` - play a random Navi line right now (ignores mute)

Mute state lives at `~/.toot.muted`. Delete it, touch it, whatever. toot just checks for the file.

## Conductor

toot auto-silences when `$CONDUCTOR_WORKSPACE_NAME` is set. Running many workspaces at once with auto-approve turned on is noisy enough without Navi pitching in.

## Credits

Sounds from *The Legend of Zelda: Ocarina of Time* (Nintendo, 1998). For personal use — don't ship this plugin with the audio included in anything commercial.
