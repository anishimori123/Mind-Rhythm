# Architecture - Mind Rhythm Sampler

Voice (mic) + Mind (EEG Muse 2) -> AI Brain -> Sampler Station

Input Layer:
- Voice Mode TODAY: Hum, Beatbox, Whistle - Web Audio API <20ms
- Mind Mode NEXT: Imagined Rhythm - Muse 2 / OpenBCI

AI Brain:
1. Detection: Basic Pitch / CREPE / librosa
2. Understanding: Quantizer + Intent (trap/lo-fi/bossa)
3. Generation: RAVE / DDSP / MusicGen

Sampler: 16 pads MPC - puh=kick, tss=hat, MIDI/WAV/VST/Ableton Link
