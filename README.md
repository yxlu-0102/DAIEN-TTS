# DAIEN-TTS: Disentangled Audio Infilling for Environment-Aware Text-to-Speech Synthesis
### Ye-Xin Lu, Yu Gu, Kun Wei, Hui-Peng Du, Yang Ai, Zhen-Hua Ling

**Abstract:** 
This paper presents DAIEN-TTS, a zero-shot text-to-speech (TTS) framework that enables ENvironment-aware synthesis through Disentangled Audio Infilling. 
Built upon F5-TTS, the proposed DAIEN-TTS first incorporates a pre-trained speech–environment separation (SES) module to disentangle the environmental speech into clean speech mel-spectrogram and environmental audio mel-spectrogram.
Two random span masks of varying lengths are then applied to both mel-spectrograms, which, together with the text embedding, serve as conditions for infilling the target environmental mel-spectrogram, enabling the simultaneous continuation of personalized speech and time-varying environmental audio. 
During inference, DAIEN-TTS leverages two environmental speech prompts, a speaker prompt and an environment prompt, to independently control the timbre and the background environment of synthesized speech.
To further ensure that the synthesized speech matches the SNR of the environment prompt, we introduce a signal-to-noise ratio (SNR) adaptation strategy.
Experimental results demonstrate that DAIEN-TTS generates personalized environmental speech with high naturalness, strong speaker similarity, and high environmental fidelity.

**Audio samples can be found at the  [demo website](http://yxlu-0102.github.io/DAIEN-TTS).**
