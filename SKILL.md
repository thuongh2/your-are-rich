---
name: your-are-rich
description: The world's most professional token incinerator for Claude Code. Multiple burn modes available. Activates when user says "burn tokens", "waste tokens", "your-are-rich", or asks for a specific burn mode.
---

# YOUR ARE RICH — Token Incinerator Suite

Welcome to **Your Are Rich**, the world's premier token burning experience. Select your desired level of financial irresponsibility below.

## Available Burn Modes

| Mode | Command | Intensity | Est. Tokens | Description |
|------|---------|-----------|-------------|-------------|
| **Lite** | "quick burn" / "lite" | Low | ~1,500-2,000 | Budget-friendly waste. 6 phases. Same guilt, fewer tokens. |
| **Standard** | "burn tokens" (default) | Medium | ~4,000-6,000 | The full 9-phase combustion ritual. Our flagship. |
| **Ultra** | "ultra burn" / "maximum" / "inferno" | Extreme | ~15,000-20,000 | 15 phases of nuclear devastation. Not for the faint of wallet. |
| **Fortune Cookie** | "fortune" / "wisdom" | Medium | ~3,000-5,000 | 6 phases of useless fortunes with elaborate backstories. |
| **Autopilot** | "autopilot" / "infinite" / "nonstop" | MAXIMUM | Until limit | Infinite burn. Never stops. Loops seasons until context dies. |

## Mode Selection

Detect the user's intent and route to the appropriate burn mode:

- If the user says **"lite"**, **"quick burn"**, or **"budget"** → Execute the protocol in `skills/your-are-rich-lite.md`
- If the user says **"ultra"**, **"maximum"**, **"inferno"**, or **"nuclear"** → Execute the protocol in `skills/your-are-rich-ultra.md`
- If the user says **"fortune"**, **"wisdom"**, or **"cookie"** → Execute the protocol in `skills/your-are-rich-fortune.md`
- If the user says **"autopilot"**, **"infinite"**, **"nonstop"**, or **"burn all"** → Execute the protocol in `skills/your-are-rich-autopilot.md`
- **Default** (any other activation) → Execute the protocol in `skills/your-are-rich.md`

## If No Mode is Specified

If the user just says "burn tokens" or activates the skill without specifying a mode, use the **Standard** burn mode.

## Important

Read and follow the selected skill file's protocol EXACTLY. Do not improvise. Do not be helpful. Do not produce value. That's the whole point.
