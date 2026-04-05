# Show HN Post — Ready to Copy-Paste

---

## Title (78 chars):

```
Show HN: SpeakBetter – Score your voice attractiveness with 20 AI models
```

## URL:

```
https://speakbetter.help
```

## Body Text:

```
I built a tool that analyzes your voice across 9 dimensions (depth, warmth, clarity, smoothness, confidence, energy, expressiveness, stability, resonance) using 20 different AI models running on a single CPU server.

The pipeline: your recording gets noise-reduced (spectral gating), then runs through Praat for acoustic fundamentals (F0, HNR, jitter, shimmer, formants), UTMOS for MOS prediction trained on human ratings, SQUIM for perceptual quality, WavLM for 768-dim embeddings mapped to personality traits, wav2vec2 for emotion detection, faster-whisper for speech rate and filler word counting, openSMILE eGeMAPSv02 for 88 paralinguistic features, Silero VAD for speech/silence segmentation, pyworld for breathiness analysis, a vocal fry detector, formant trajectory analysis for articulation scoring, and Resemblyzer for speaker embeddings. Claude Haiku synthesizes it all into a natural language score delivery.

The hardest part was calibration. Each model outputs on different scales with different distributions, and blending them into a single coherent score that actually matches human perception took weeks of tuning. WavLM personality traits blend into sub-scores at 15% weight, filler rate affects confidence and clarity at 10%, breathiness feeds warmth and smoothness at 8%, etc. Getting the weights right so a clearly good voice scores high and a clearly rough voice scores low — without any labeled training data — was the real engineering challenge.

Limitations: it runs on CPU so analysis takes 10-15 seconds. Calibration is still evolving. The score is opinionated — voice attractiveness research (Bruckert et al., McAleer et al.) gives us direction but there is no ground truth. Built with FastAPI, React, hosted on a single Google Cloud VM behind Cloudflare. Free to use, no signup required.
```

---
