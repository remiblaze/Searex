# Searex: Rhythmic Gate & Volume Chopper

![Searex free rhythmic gate & volume chopper UI](https://raw.githubusercontent.com/RemiBlaze/Searex/main/searex-ui-screenshot.png)

**Tempo-synced rhythmic gating with a visual step sequencer.**

Searex chops, stutters, and gates your audio in time with your DAW's BPM. Draw patterns on the step sequencer to carve rhythmic movement into pads, vocals, synths, and drums, from subtle groove to full-on trance-gate stutter.

**macOS** (Apple Silicon and Intel): AU, VST3, CLAP, AAX, Standalone. Signed and notarized by Apple.

**Windows** 10 and 11, 64-bit: VST3, CLAP, Standalone. Authenticode signed.

AAX ships on macOS only.

---

## 🚀 Download & Install

Go to the [latest release](https://github.com/RemiBlaze/Searex/releases/latest) and pick your platform.

**macOS**
1. Download **`Searex_Installer.pkg`**.
2. Double-click it and follow the installer. It is signed and notarized by Apple, so it installs cleanly with no security warnings.
3. Restart your DAW and rescan plug-ins. Searex appears under **Remi Blaze**.

**Windows 10 and 11, 64-bit**
1. Download **`Searex_Installer.exe`**.
2. Run it and follow the installer. It is Authenticode signed.
3. Restart your DAW and rescan plug-ins. Searex appears under **Remi Blaze**.

No dongle and no extra account on either platform.

Full guide: **[remiblaze.com/support](https://remiblaze.com/support/)**.

---

## 🎛️ Features
- **Visual Step Sequencer**: Click and drag to draw per-step volumes. Choose 4, 8, 16, or 32 steps.
- **Rate**: Sync the pattern grid to 1/4, 1/8, 1/16, or 1/32 notes.
- **Envelope Shapes**: Square, Smooth, Ramp Up, or Ramp Down contour on every gate.
- **Smoothing**: Round off gate edges (0–100%) to tame clicks and pops.
- **Depth**: Set how far each gate ducks the signal (0–100%).
- **Swing**: Push the groove from straight to shuffled (0–100%).
- **Speed**: Play the pattern at Half, Normal, or Double time for buildups and breakdowns.
- **Gate Filter**: A per-step low-pass sweep (0–100%) that adds tonal movement to the chops.
- **Sub Anchor**: Protects sub-bass below 150 Hz from being gated, keeping your low end solid.
- **Invert**: One click flips the whole pattern on/off for instant variations.
- **Randomize**: Generate fresh step patterns instantly (touches only step volumes).
- **Per-Step Stereo Pan**: Bounce individual chops between the left and right speakers.
- **Mix**: Dry/wet blend (0–100%) for parallel gating.
- **Output**: Level trim (−24 dB to +6 dB) for honest gain matching.
- **Bypass**: Instant A/B against the dry signal.
- **A/B Comparison**: Snapshot two full states, parameters and pattern, and flip between them.
- **Preset Save/Load**: Export and import your own `.preset` files.

---

## 🔬 Under the Hood
- **Linkwitz-Riley 4th-Order Crossover**: Sub Anchor splits the signal at 150 Hz with a phase-coherent LR4 crossover, gating only the mids and highs so the bass stays anchored.
- **TPT State-Variable Gate Filter**: The per-step filter sweep uses a zero-delay-feedback state-variable low-pass for clean, stable movement.
- **DC Blocker**: A 10 Hz high-pass on the output keeps the signal centered after gating.

---

## 💻 System Requirements

**macOS**
- macOS 15.0 or later
- Apple Silicon or Intel Mac (Universal Binary)
- An AU, VST3, CLAP or AAX host

**Windows**
- Windows 10 or Windows 11, 64-bit
- A VST3 or CLAP host

---

## 🎚️ Factory Presets (14)

| Preset | Feel |
|--------|------|
| Full On | All steps open, pattern off |
| Basic Gate | Straight on/off eighths |
| Offbeat | Off-the-beat gating |
| Trance Gate | Classic pumping trance gate |
| Buildup | Rising gate into the drop |
| Breakdown | Opening that fades out |
| Stutter | Sparse four-on-the-floor stutter |
| Syncopated | Off-grid syncopation |
| Half Time | Broad half-time chops |
| Shuffle | Shuffled swing groove |
| Remi Blaze Chop | Signature chop pattern |
| Ghost Vocal | Airy ghosted vocal gate |
| Warehouse Stutter | Driving warehouse rhythm |
| Percussion Enh | Percussive offbeat accent |

---

## 🐛 Bugs & Issues
Open an issue on the **[Issues](https://github.com/RemiBlaze/Searex/issues)** tab with your macOS or Windows version, DAW + version, and steps to reproduce.

---

## 📄 License & Credits
- **Plugin page:** [remiblaze.com/plugins/searex/](https://remiblaze.com/plugins/searex/).
- **Developer:** [Remi Blaze](https://remiblaze.com).
- **Framework:** [JUCE](https://juce.com).
- **License:** free under a proprietary [Freeware License](LICENSE) (see also our [terms](https://remiblaze.com/terms/)). Reverse-engineering, repackaging, binary redistribution, or reselling the compiled installer is strictly prohibited.

---

## Trademarks

All product names, company names, and logos mentioned herein are trademarks or registered trademarks of their respective owners. Any such references are used for descriptive or compatibility purposes only and do not imply affiliation with, endorsement by, or sponsorship from their owners.

VST is a trademark of Steinberg Media Technologies GmbH, registered in Europe and other countries.

Apple, macOS, Audio Units (AU), and Apple Silicon are trademarks of Apple Inc., registered in the U.S. and other countries.

AAX, Avid, and Pro Tools are trademarks or registered trademarks of Avid Technology, Inc. in the U.S. and other countries.

Microsoft and Windows are trademarks of the Microsoft group of companies.
