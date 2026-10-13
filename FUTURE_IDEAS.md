# Future Ideas - Don't Lose Them!

## 1. VST Plugin (Mind Rhythm as plugin)
- What: Turn the web hum-to-drum tool into a real VST3/AU plugin for 【entity-Ableton¦canonical_name=Ableton】/【entity-Logic¦canonical_name=Logic】
- Difficulty: Hard (Level 2-3) - Need C++ + JUCE framework
- Why hard: Real-time audio can't crackle, need DSP math
- Steps:
    1. Build web version first (Tone.js) - easy to test
    2. Learn JUCE tutorial - make a volume knob VST (1 week)
    3. Wrap Basic Pitch model into JUCE (Phase 4 of main plan)
- When: After Phase 1 web MVP works

## 2. Phone -> Car Amp Booster (Make car sound expensive)
- What: App that makes Spotify from phone to car sound like  amp
- How: EQ fix + Loudness compressor + Stereo widener before Bluetooth
- Difficulty: Medium - DSP is known, just tune for your car
- Inspiration: Wavelet app on Android does similar
- Steps:
    1. Android music player app with built-in EQ presets for cars
    2. Measure your car speakers with phone mic
    3. Auto-tune bass/mids/highs for that car
- Test: Daily on 101 commute!
- When: Side project after hum-to-drum MVP

Both reuse same audio skills. Build web MVP first.
