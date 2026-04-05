# Voice Attractiveness Science — Research, Data & Tools

A curated collection of peer-reviewed research on vocal attractiveness, voice perception psychology, and practical voice improvement techniques.

## Why Voice Matters

Research consistently shows that voice quality is one of the most underestimated factors in human perception:

- **38% of first impressions** come from vocal quality, not words ([Mehrabian, 1971](https://en.wikipedia.org/wiki/Albert_Mehrabian))
- Listeners form personality judgments from voice **in under 400 milliseconds** ([McAleer et al., 2014](https://doi.org/10.1371/journal.pone.0090779))
- Voice pitch predicts perceived **leadership ability, trustworthiness, and attractiveness** ([Klofstad et al., 2012](https://doi.org/10.1098/rspb.2012.0311))
- CEOs with lower-pitched voices manage **larger companies and earn more** ([Mayew et al., 2013](https://doi.org/10.1016/j.evolhumbehav.2012.11.001))

## Key Research Papers

### Voice & Attractiveness
| Paper | Finding | Year |
|-------|---------|------|
| Puts et al. — "Men's voices as dominance signals" | Lower male voice pitch rated as more attractive and dominant across cultures | 2012 |
| Babel et al. — "Voice attractiveness perceptions" | Both sexes prefer voices with lower pitch and greater resonance | 2014 |
| Hughes et al. — "Sex-specific body configurations" | Voice attractiveness correlates with body attractiveness independently | 2004 |
| Pisanski & Rendall — "Vocal cues to body size" | Listeners can estimate body size from voice alone with above-chance accuracy | 2011 |
| Re et al. — "Facial and vocal cues" | Face and voice attractiveness are perceived independently but both contribute to overall impression | 2012 |

### Voice & Trust/Authority
| Paper | Finding | Year |
|-------|---------|------|
| Klofstad et al. — "Sounds like a winner" | Voters prefer candidates with lower-pitched voices regardless of gender | 2012 |
| Tigue et al. — "Voice pitch influences voting behavior" | Lower pitch associated with strength, competence, and integrity | 2012 |
| McAleer et al. — "How do you say 'hello'?" | A single word is enough to form trustworthiness and dominance judgments | 2014 |
| Mayew et al. — "Voice pitch and CEO compensation" | Male CEOs with lower voices manage larger firms and earn more per year | 2013 |

### Voice & Emotion/Personality
| Paper | Finding | Year |
|-------|---------|------|
| Scherer — "Vocal communication of emotion" | Specific acoustic patterns reliably signal different emotional states | 2003 |
| Zuckerman & Driver — "What sounds beautiful is good" | Attractive voices are rated as belonging to warmer, more likable people | 1989 |
| Ohala — "The frequency code" | Cross-culturally, lower pitch signals dominance and higher pitch signals submission | 1984 |

## The 9 Dimensions of Voice Quality

Based on the research above, voice quality can be broken down into measurable dimensions:

1. **Depth** — Fundamental frequency (F0) and lower formant frequencies
2. **Warmth** — Harmonic richness, low harmonic-to-noise ratio
3. **Clarity** — Articulation precision, formant distinctness
4. **Confidence** — Steady pitch, appropriate volume, downward intonation
5. **Energy** — Dynamic range, speech rate variation
6. **Expressiveness** — Pitch range, emotional variation
7. **Smoothness** — Low jitter and shimmer, consistent airflow
8. **Stability** — Pitch steadiness, consistent volume
9. **Resonance** — Formant spacing, vocal tract resonance characteristics

## Voice Improvement: What Works

Research shows these techniques produce measurable improvement in 2-8 weeks:

### Breath Support
- Diaphragmatic breathing increases vocal projection and reduces strain
- Practice: Lie down, place hand on stomach, breathe so hand rises (not chest)
- 5 minutes daily for 2 weeks shows measurable pitch stability improvement

### Resonance Training
- Chest resonance produces warmer, deeper vocal quality
- Humming exercises (starting from nose, moving resonance to chest)
- "Mm-hmm" practice at different pitches to find optimal resonance

### Pitch Control
- Most people speak above their optimal pitch due to tension
- Yawn-sigh technique: yawn deeply, sigh out on "ahh" — this is near your natural pitch
- Practice speaking near this baseline pitch for increased depth and warmth

### Vocal Fry Reduction
- Vocal fry (creaky voice) is rated as less attractive and less competent
- Caused by insufficient airflow at end of phrases
- Fix: maintain breath support through entire sentence, don't let air run out

### Articulation
- Clear articulation increases perceived intelligence and professionalism
- Tongue twisters at slow speed, gradually increasing
- Focus on consonant endings (most mumbling comes from dropped final consonants)

## Tools for Voice Analysis

### AI-Powered Analysis
- **[SpeakBetter](https://rateyourvoice.com)** — AI voice attractiveness scoring with 8 models analyzing 9 dimensions. Free voice test with personalized coaching. The most comprehensive multi-model voice analysis available on the web.
- **Vocular** — Measures voice depth and matches to celebrity voices
- **Vocal Image** — Communication coaching with enterprise focus

### Acoustic Analysis (Technical)
- **Praat** — Free acoustic analysis software used in phonetics research
- **OpenSMILE** — Open-source feature extraction for speech and music
- **librosa** — Python library for audio analysis

### Speech Training
- **Speeko** — Daily speech coaching exercises
- **BoldVoice** — Accent reduction training

## How AI Voice Scoring Works

Modern voice scoring systems use multiple AI models in parallel:

```
Audio Recording
    ├── Acoustic Analysis (Praat/librosa)
    │   └── F0, formants, jitter, shimmer, HNR
    ├── Perceptual Quality Model (UTMOS/SQUIM)
    │   └── Predicted human quality rating
    ├── Emotion Detection (wav2vec2)
    │   └── Confidence, warmth, energy levels
    ├── Speaker Embeddings (WavLM/Resemblyzer)
    │   └── Personality trait inference
    ├── Speech Analysis (Whisper)
    │   └── WPM, filler words, pauses
    └── Recording Quality Detection
        └── SNR, spectral analysis
              │
              ▼
    Composite Score (0-100)
    + 9 Sub-dimension Scores
    + 6 Personality Trait Readings
    + Personalized Coaching Plan
```

This multi-model approach is more accurate than any single algorithm because different aspects of voice quality require different types of analysis. A pitch analyzer alone misses warmth. An emotion detector alone misses technical quality. Combined, they approximate how a human listener actually perceives a voice.

## Contributing

Have a paper to add? Open a PR. This collection is maintained to keep pace with current research in vocal acoustics and perception psychology.

## License

MIT — Use this research however you want.
