# AI Halloween Hollow · AI 万圣夜

A standalone, interactive 3D Halloween hollow you can open in the browser.

**Live:** https://huagechen-lab.github.io/ai-halloween-hollow/
**Source:** https://github.com/huagechen-lab/ai-halloween-hollow

## Controls

- Arrow keys / WASD move the camera (forward / back along the view, strafe left / right)
- Drag to orbit; scroll or pinch to zoom. Free camera: FOV 34–90°. Character mode: the follow camera dollies between 6.5 and 14.5 m. Pinch in / scroll down zooms out; pinch out / scroll up zooms in. Double-click resets the camera on desktop; touch uses the view presets
- Time presets: Day / Sunset / Night · Weather presets: Clear / Drift / Overcast / Drizzle / Storm (15 independent combinations)
- God view: rise above the hollow and return exactly to the previous camera
- Auto-orbit toggle; paused by drag, movement and god view
- Character group: Camera / TIBO / Potato Sister. As a mascot, arrows/WASD walk; walk near the eight AI lanterns to collect sigils (gold diamonds)
- Reset: press `E` near the giant button, press `R` anywhere, click/tap the red dome, or use the **RESET** button in the control panel. Collect all 8 sigils first for the full "reset all" finale
- Hide HUD: use the **Hide HUD / 隐藏 HUD** button at the top-right; it stays visible and becomes **Show HUD** so you can bring the interface back. On the public landing the host promo bar, focus hint and credit line hide with the HUD too. Nothing auto-restores it
- Mobile: select TIBO or Potato Sister, then tap the ground to walk (a gold ring marks the target); drag to orbit, pinch to zoom. Double-tap camera reset is disabled on touch so repeated taps keep walking; use the view presets instead. On very small screens, hide the HUD first for more room
- Duo ritual: at the gate, step TIBO into the cyan ring and Potato Sister into the amber ring (switch characters; both keep their positions). Hold both for 1.2 s to raise the spirit fire — magical embers, light columns and a sky halo, not a civic fireworks show
- Background music: a procedural WebAudio score (no audio files), off by default; use the ♪ note button in the control panel header to fade it in or out
- Chinese / English UI: auto-detected from the browser, toggle in the top bar or scene HUD; `?lang=zh` / `?lang=en` override

## What it is

A single-file Three.js scene generated end-to-end by an LLM from one prompt:
a misty hollow with eight stylized, non-official AI-motif jack-o'-lanterns,
TIBO the reset robot and Potato Sister, a pumpkin patch, cottage, graveyard,
bats, mist and a day/weather light system. A small playable loop lets you
collect lantern sigils as either mascot and hit the giant physical RESET
button to bring the lane back to life.

No backend, no tracking, no cookies, no storage in the scene; Three.js from
a CDN is the only network request. The public landing page stores only a
language preference locally.

## Fan-art & rights

This is an unofficial fan-art homage to the AI community. All AI-brand-like
motifs are abstract, procedural designs — no official logos, wordmarks or
exact brand artwork. TIBO and Potato Sister are original mascot characters;
no real-person likeness is used. Not affiliated with or endorsed by OpenAI or
any company or person. Commercial use requires a separate license.

## Use and credit

CC BY-NC 4.0 — non-commercial reuse with attribution; commercial use requires
a license. Copy-ready attribution, HTML snippet and commercial licensing:
[credit.html](https://huagechen-lab.github.io/ai-halloween-hollow/credit.html).

- Scene: **孙小画** · [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) · generated with **DeepSeek V4.1 Flash 1017**
- Landing page and metadata: © 2026 BillionWorlds, all rights reserved

See [LICENSE](./LICENSE) for the code/content split and terms.

## Follow

More one-prompt 3D worlds: [@huagechen on X](https://x.com/huagechen)
