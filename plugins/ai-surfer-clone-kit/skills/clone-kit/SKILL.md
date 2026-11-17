---
name: clone-kit
description: The AI Surfer Clone Kit, a guided path to a voice clone (ElevenLabs) and a video clone (HeyGen) built from the client's own "brain". Use when the person runs /ai-surfer-clone-kit:start, opens their "AI Surfer Brain" folder, mentions the Clone Kit, or asks to continue their brain, voice clone, video clone, footage check, test video or starter videos.
---

# The AI Surfer Clone Kit

The kit's step-by-step guide lives on The AI Surfer's server, not in this plugin.

1. Call the Clone Kit connection's `get_kit_guide` tool with part `skill` (in Code mode:
   `mcp__claude_ai_Clone_Kit__get_kit_guide`) and follow it exactly. It says which part to get next.
2. If the Clone Kit connection isn't there, say so in one plain line and give these steps: in
   Claude, Customize -> Connectors -> + Add -> Add custom connector; name it **Clone Kit**, address
   `https://clonekit.theaisurfershowroom.com/mcp`; click Continue and type the access password we sent
   you; then start a new Code session in this folder and type `/ai-surfer-clone-kit:start`.
3. Never guess the kit's steps or rules without the guide, and never ask for the password.
