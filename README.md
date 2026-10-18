# Recording Studio

A professional browser-based recording studio — no low-budget sound. Record vocals through a real studio vocal chain, mix, master, and export finished WAV files. Installable as a phone app (PWA).

## The rooms

- **Booth** — live mic input with level scope and meter, vocal chain presets, 4 algorithmic reverbs (Hall, Room, Plate, Chamber) with decay + wet/dry controls and Send/Insert routing, echo, 3-band EQ, compressor, Auto-Tune-style pitch correction (key, scale, retune speed), beat/backing-track import, metronome with 4-beat count-in
- **Arrange** — playlist timeline; every take is a draggable waveform clip
- **Mixer** — channel strip per track: fader, pan, mute/solo, reverb send, live meters
- **Master** — one-tap mastering presets (Streaming −14, Loud & Proud −9, Warm, Bright Pop, Punch), loudness targeting, limiter ceiling, maximizer drive, master EQ; renders and downloads a finished mastered WAV with loudness/peak readout

## Run it

Open `index.html` in a browser (microphone permission required for recording), or install it to your phone's home screen — it works offline.

## Notes

- Takes live in the session only — export your mastered mix before closing the page.
- 100% client-side: no accounts, no servers, no API keys. Your audio never leaves your device.
