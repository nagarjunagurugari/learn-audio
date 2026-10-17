# learn-audio

A series of interactive, visual guides to audio — from the physics of sound
all the way to DSP algorithms. Written to be approachable, with live
in-browser labs (no audio files needed; everything is synthesized with
Web Audio).

Open `index.html` in a browser, or view it via GitHub Pages.

## The guides

### Part 1 — Audio Basics to Algorithms (`audio-basics.html`)
Sound waves, volume & decibels, mono vs. stereo, going digital (sampling,
bit depth, Nyquist), lossy vs. lossless, the FFT frequency view,
pre-processing (noise reduction, echo cancellation, AGC, SRC, beamforming),
post-processing (EQ, compressor, reverb, mixing/ducking), clipping, speaker
driver types (woofer, mid-range, tweeter, full-range), 2.1 / 5.1 / Dolby
Atmos layouts, microphones, latency (buffer math, cold vs. continuous,
jitter, real measurements), ALSA concepts (samples, frames, periods, period
count, ring buffers, thresholds, underrun/overrun), and why voice uses
16 kHz. Closes with a scored quiz.

### Part 2 — DSP Basics (`dsp-basics.html`)
Filters as weighted averages, FIR vs. IIR, convolution (the universal
operation), why the frequency domain exists, fixed-point vs. floating-point
arithmetic, and the real-time budget. Interactive labs throughout, plus a
quiz.
