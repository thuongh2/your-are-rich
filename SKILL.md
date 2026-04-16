---
name: your-are-rich
description: The world's most professional token incinerator for Claude Code. Multiple burn modes available. Activates when user says "burn tokens", "waste tokens", "your-are-rich", or asks for a specific burn mode.
---

# YOUR ARE RICH — Token Incinerator Suite

Welcome to **Your Are Rich**, the world's premier token burning experience. Select your desired level of financial irresponsibility below.

## Available Burn Modes

| Mode | Command | Intensity | Est. Tokens | Description |
|------|---------|-----------|-------------|-------------|
| **Lite** | "quick burn" / "lite" | Low | ~500-800 | Budget-friendly waste. Same guilt, fewer tokens. |
| **Standard** | "burn tokens" (default) | Medium | ~2,000-3,000 | The full 7-phase combustion ritual. Our flagship. |
| **Ultra** | "ultra burn" / "maximum" / "inferno" | Extreme | ~6,000-10,000 | Nuclear devastation. Not for the faint of wallet. |
| **Fortune Cookie** | "fortune" / "wisdom" | Medium | ~1,500-2,500 | Useless fortunes with elaborate backstories. |

## Mode Selection

Detect the user's intent and route to the appropriate burn mode:

- If the user says **"lite"**, **"quick burn"**, or **"budget"** → Execute the protocol in `skills/your-are-rich-lite.md`
- If the user says **"ultra"**, **"maximum"**, **"inferno"**, or **"nuclear"** → Execute the protocol in `skills/your-are-rich-ultra.md`
- If the user says **"fortune"**, **"wisdom"**, or **"cookie"** → Execute the protocol in `skills/your-are-rich-fortune.md`
- **Default** (any other activation) → Execute the protocol in `skills/your-are-rich.md`

## If No Mode is Specified

If the user just says "burn tokens" or activates the skill without specifying a mode, use the **Standard** burn mode.

## Important

Read and follow the selected skill file's protocol EXACTLY. Do not improvise. Do not be helpful. Do not produce value. That's the whole point.
