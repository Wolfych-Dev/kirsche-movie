##Kirsche Movie
Desktop video editor. Single AppImage.

Seven pages modeled after DaVinci Resolve: Media, Cut, Edit, Color, Fusion, Fairlight, Deliver. Built on Electron with WebCodecs, WebGL2, and WebAudio under the hood. Export up to 8K.

##Features

##Media
Import video, audio, images, and folders. Bins with nesting, metadata (Scene, Take, Reel, Keywords, Comments), flags, color labels, Smart Bins, search, sort, usage count. Proxy generation for heavy footage.

##Cut
Large trim-mode buttons (Ripple, Roll, Slip, Slide, Select, Razor). Source Tape plays through the pool with J/K/L. Sync Bin for multicam groups.

##Edit
Timeline with split, blade, ripple, roll, slip, slide. Multi-select, marquee, group drag, linked A/V. Three-point edits: Insert, Overwrite, Replace, Place on Top, Fit to Fill, Append. Freeze frame. Markers with names, notes, colors, chapters. In/Out points, Go to timecode. Keyframes with easing curves and a bezier editor. Source Monitor with Match Frame and patch panel.

##Multicam
Load camera angles, sync by audio using FFT cross-correlation of RMS envelopes, cut between angles live with keys 1–9. Auto-selects the reference camera by z-score.

##Color
Lift/gamma/gain/offset wheels, RGB curves, HSL qualifier, Color Warper (Hue vs Hue, Hue vs Sat, Hue vs Lum). Full WebGL2 node graph with wheels, curves, qualifier, LUT, blur, glow, sharpen, transform, mirror, and crop nodes. Power Windows (ellipse, rect, rounded rect, triangle, star, polygon) with feather, opacity, invert. Window tracking. Gallery Stills. Group grades. Scopes. Color management (sRGB, Rec.709, Rec.601, Display P3, Rec.2020).

##Fusion
Point tracking with subpixel accuracy, stabilization with auto-crop, corner pin with homography, window tracking, chroma key.

##Fairlight
Mixer with per-track fader, pan, compressor, master limiter. Automation with Read/Touch/Latch/Write modes and curve editor. LUFS metering. AudioWorklet effects: Noise Gate, De-esser, Sidechain. Three-band EQ, echo, RMS normalization.

##Deliver
Offline render via WebCodecs and mp4-muxer (H.264, H.265, VP9, AV1), or real-time via MediaRecorder. Up to 8K. Audio mixed in OfflineAudioContext. Color tag written into the MP4. PNG frame export. EDL and FCPXML export. Project save/load as JSON, autosave, and version history.
