# TB Wwise Plugin Bundle

**TB Wwise Plugin Bundle** is a collection of 20 custom audio DSP effect plugins designed for Audiokinetic Wwise. This suite provides a wide range of audio processing tools—including spatial effects, modulation, pitch shifting, and distortion—to enable highly creative and detailed sound design.

## 📦 Included Plugins

This bundle includes the following 20 plugins:

* **TB_BitCrusher**: Lo-Fi effect utilizing resolution and sample rate reduction.
* **TB_Chorus**: Thick and lush chorus ensemble effect.
* **TB_CombFilter**: Comb filter ideal for metallic resonance and robotic voices.
* **TB_ConvolutionReverb**: High-quality convolution reverb based on Impulse Responses (IR).
* **TB_CrossSynth**: Synthesizer that cross-modulates the characteristics of two audio signals.
* **TB_Distortion2**: Powerful distortion with versatile textures.
* **TB_Doppler**: Physical Doppler effect simulation for moving objects.
* **TB_Doubler**: Doubling effect to enrich and widen vocals or instruments.
* **TB_Filter**: Multi-purpose, multi-mode audio filter.
* **TB_FrequencyShift**: Inharmonic frequency shifting for SFX and alien sound design.
* **TB_Gate**: Noise gate for background noise removal and rhythmic dynamics control.
* **TB_GrainDelay**: Granular delay that chops and delays audio streams.
* **TB_Haas**: Stereo image widener utilizing the Haas effect.
* **TB_NoiseRemover**: Utility to remove unwanted background noise like hums and hisses.
* **TB_Phaser**: Dynamic phaser effect using phase shifting.
* **TB_RingMod**: Metallic ring modulator.
* **TB_SubEnhancer**: Sub-harmonic enhancer to boost and synthesize low-frequency energy.
* **TB_TruePitchShifter**: Precise pitch shifter with formant preservation and control capabilities.
* **TB_TubeExeciter**: Exciter that adds analog tube-style harmonics and warmth.
* **TB_Vocoder**: Classic robotic voice and vocoding processor.

## ⚙️ Installation

1. Extract the downloaded `TB_WwisePlugins` archive.
2. Locate the `.xml` (plugin definition) and `.dll` / `.dylib` (dynamic library) files.
3. Copy these files to your Wwise installation directory based on your OS and Wwise version.
   * **Windows (Authoring) Default Path:** `C:\Program Files (x86)\Audiokinetic\Wwise [Version]\Authoring\x64\Release\bin\Plugins`
4. Restart the Wwise Authoring Tool.
5. Verify that the `TB_...` plugins load correctly in the Project Explorer (under ShareSets) or in your Mixer/Object Effect lists.

## ⚠️ Compatibility Warning

To enable sidechain functionality, these plugins were implemented specifically for **Wwise version 25.1**. Please be aware that they may not function correctly in future updates or different versions of Wwise.

## 🛠 Disclaimer

This software is provided "AS IS", without warranty of any kind. The creator shall not be held liable for any direct or indirect damages, including but not limited to project file corruption, software crashes, or hardware issues arising from the use of these plugins. **Please back up your Wwise projects before applying new plugins.**

---

**Contact / Support**
* **Developer:** TaeBeum Kim
* **Email:** ktb7056@gmail.com
