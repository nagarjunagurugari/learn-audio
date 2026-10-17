# audio_basics

An interactive, visual guide to audio — from the physics of sound all the way to
the algorithms that process it. Written to be approachable for a high-school
student, with live in-browser labs (no audio files needed; everything is
synthesized with Web Audio).

Open `index.html` in a browser, or view it via GitHub Pages.

## Contents

1. **Sound waves** — pitch, loudness, wave shapes (Pitch & Loudness Lab)
2. **Volume & decibels** — everyday-sounds dB chart, gain lab (wave height vs
   power vs perceived loudness)
3. **Going digital** — sampling lab (sample count, bit depth, quantization),
   Nyquist rule, aliasing
4. **The frequency view** — FFT analyser bars for tones, chords, and noise
5. **Pre-processing** — hiss removal, noise gate, echo cancellation, AGC,
   noise reduction, sample-rate conversion, beamforming
6. **Post-processing** — 3-band EQ + balance with live response curve,
   compressor, reverb, mixing/ducking/normalization
7. **Speakers** — woofer, mid-range, tweeter, full-range; crossovers;
   "hear the split" lab; 2.1, 5.1, and Dolby Atmos room diagrams
8. **Full pipeline** — mic → ADC → pre → DSP → post → volume → DAC → speaker
9. **Latency** — buffer-size math, feel-the-delay tap test, real-world latency
   chart, measure-your-own-device tool
10. **ALSA concepts** — samples, frames, periods, ring buffers, thresholds,
    XRUNs (animated Ring Buffer Lab); why voice calls use 16 kHz and VR uses
    16/24 kHz instead of 48 kHz

Each section ends with hands-on labs, and a scored quiz closes the guide.
