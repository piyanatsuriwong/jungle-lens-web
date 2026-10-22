# Third-party notices

UNBROKEN · Shadow Within is © 2026 piyanatsuriwong, all rights reserved (see `LICENSE`).
These parts were made by others and stay under their own licences. The same
list is shown in the game (title menu → "เครดิต / ลิขสิทธิ์", `scripts/ui/legal.gd`);
keep the two in step.

| Part | Author | Licence | Where |
|---|---|---|---|
| Godot Engine 4.7 | Juan Linietsky, Ariel Manzur and contributors | MIT (full text: in game, `Engine.get_license_text()`) | the engine (`index.wasm`, `index.js`) |
| Godot third-party components | various (FreeType, HarfBuzz, ...) | various (in game: `Engine.get_copyright_info()`) | the engine |
| netfox, netfox.internals | Gálffy Tamás | MIT (`addons/netfox/LICENSE`) | `addons/netfox*` |
| Effekseer for Godot 4 (the effects runtime) | Effekseer Project | MIT (`addons/effekseer/LICENSE`) | `addons/effekseer/` (Windows and web builds) |
| Effekseer sample effects: ToonHit and Light (tktk), actionLines_halo / radial2 / shockwave / strip and fire (AndrewFM), Flame (Pierre), PowerUp (NextSoft) | their authors, shipped with Effekseer 1.80.6 | free to use and remodel in games made with Effekseer (the Effekseer readme) | `assets/vfx/effekseer/` |
| webrtc-native and its libraries | Godot Engine and others | see `addons/webrtc_native/LICENSE.*` | desktop builds only (not in the web build) |
| Noto Sans Thai, Noto Sans Symbols | The Noto Project Authors | SIL Open Font License 1.1 (`assets/fonts/OFL.txt`) | `assets/fonts/` |
| Music: the jingles (2) | MintoDog | CC0 1.0 (`assets/audio/music/CREDITS.md`) | `assets/audio/music/` |
| Music: the main track (`stage.ogg`) | alex-morgan (Pixabay) | Pixabay Content License (`assets/audio/music/CREDITS.md`) | `assets/audio/music/` |
| Music: the boss fight (`boss.ogg`) | u_98a917e4i7 (Pixabay) | Pixabay Content License (`assets/audio/music/CREDITS.md`) | `assets/audio/music/` |
| Monsters' sprites: Shella the snail, the dragon fish, the Totem Monster (from Monster Battlegrounds) | Wouter van Ham (art, code and design of Monster Battlegrounds) | used with the author's permission (`assets/sprites/monsters/CREDITS.md`) | `assets/sprites/monsters/` |
| Recorded sound effects (12) | Pixabay uploaders | Pixabay Content License (`art_src/sfx/CREDITS.md`) | cut into `assets/audio/sfx/` |
| The Muay Thai fighter's voice (8 short shouts, `muay_*`) | generated with ElevenLabs text to speech (voice "Jessica", eleven_v3) on the project owner's account | ElevenLabs terms for generated audio (`art_src/sfx/CREDITS.md`) | cut into `assets/audio/sfx/` by `tools/make_muay_voice.py` |

The MIT licence of Godot Engine:

```
Copyright (c) 2014-present Godot Engine contributors.
Copyright (c) 2007-2014 Juan Linietsky, Ariel Manzur.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

The netfox licence is the same MIT text with the line
`Copyright 2023 Gálffy Tamás`; the Effekseer licence with `Copyright (c) 2020 Effekseer`.
