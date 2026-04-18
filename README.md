# 🎵 easyeffects 


<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                    AUDIO PROCESSING PRESET                         ║
║              Professional Studio-Grade Configuration               ║
╚══════════════════════════════════════════════════════════════════╝
```

[![Platform](https://img.shields.io/badge/platform-Linux-blue?logo=linux&logoColor=white)](https://www.linux.org/)
[![EasyEffects](https://img.shields.io/badge/EasyEffects-7.0+-purple)](https://github.com/wwmm/easyeffects)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

**Author:** Vladislav Khudash (17)  
**Date:** 2026

</div>

---

# English

## 📥 Quick Install — Copy & Paste

### Save as JSON files

<details>
<summary><b>📁 Click to expand: output.json (Speakers/Headphones Preset)</b></summary>

```json
{
    "output": {
        "bass_enhancer#0": {
            "amount": 3.0,
            "blend": -10.0,
            "bypass": false,
            "floor": 20.0,
            "floor-active": false,
            "harmonics": 8.5,
            "input-gain": 0.0,
            "output-gain": 0.0,
            "scope": 120.0
        },
        "blocklist": [],
        "compressor#0": {
            "attack": 10.0,
            "boost-amount": 3.0,
            "boost-threshold": -72.0,
            "bypass": false,
            "dry": -100.0,
            "hpf-frequency": 10.0,
            "hpf-mode": "off",
            "input-gain": 0.0,
            "knee": -6.0,
            "lpf-frequency": 20000.0,
            "lpf-mode": "off",
            "makeup": 0.0,
            "mode": "Boosting",
            "output-gain": 0.0,
            "ratio": 5.0,
            "release": 150.0,
            "release-threshold": -100.0,
            "sidechain": {
                "lookahead": 0.0,
                "mode": "RMS",
                "preamp": 0.0,
                "reactivity": 10.0,
                "source": "Middle",
                "stereo-split-source": "Left/Right",
                "type": "Feed-forward"
            },
            "stereo-split": false,
            "threshold": -25.0,
            "wet": 0.0
        },
        "crossfeed#0": {
            "bypass": false,
            "fcut": 800,
            "feed": 7.0,
            "input-gain": 0.0,
            "output-gain": 0.0
        },
        "deesser#0": {
            "bypass": false,
            "detection": "RMS",
            "f1-freq": 6000.0,
            "f1-level": 0.0,
            "f2-freq": 4500.0,
            "f2-level": 12.0,
            "f2-q": 1.0,
            "input-gain": 0.0,
            "laxity": 15,
            "makeup": 0.0,
            "mode": "Wide",
            "output-gain": 0.0,
            "ratio": 4.0,
            "sc-listen": false,
            "threshold": -15.0
        },
        "equalizer#0": {
            "balance": 0.0,
            "bypass": false,
            "input-gain": 0.0,
            "left": {
                "band0": {
                    "frequency": 32.0,
                    "gain": 2.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band1": {
                    "frequency": 64.0,
                    "gain": 5.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.6,
                    "slope": "x1",
                    "solo": false,
                    "type": "Lo-shelf",
                    "width": 4.0
                },
                "band10": {
                    "frequency": 3500.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.9,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band11": {
                    "frequency": 5000.0,
                    "gain": 1.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band12": {
                    "frequency": 8000.0,
                    "gain": 4.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Hi-shelf",
                    "width": 4.0
                },
                "band13": {
                    "frequency": 12000.0,
                    "gain": 3.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band14": {
                    "frequency": 16000.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band2": {
                    "frequency": 90.0,
                    "gain": 3.0,
                    "mode": "RLC (MT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band3": {
                    "frequency": 125.0,
                    "gain": 2.5,
                    "mode": "RLC (MT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band4": {
                    "frequency": 200.0,
                    "gain": -2.0,
                    "mode": "RLC (MT)",
                    "mute": false,
                    "q": 1.5,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band5": {
                    "frequency": 350.0,
                    "gain": 1.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band6": {
                    "frequency": 500.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band7": {
                    "frequency": 800.0,
                    "gain": 1.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band8": {
                    "frequency": 1200.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band9": {
                    "frequency": 2000.0,
                    "gain": 2.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                }
            },
            "mode": "IIR",
            "num-bands": 15,
            "output-gain": 0.0,
            "pitch-left": 0.0,
            "pitch-right": 0.0,
            "right": {
                "band0": {
                    "frequency": 32.0,
                    "gain": 2.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band1": {
                    "frequency": 64.0,
                    "gain": 5.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.6,
                    "slope": "x1",
                    "solo": false,
                    "type": "Lo-shelf",
                    "width": 4.0
                },
                "band10": {
                    "frequency": 3500.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.9,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band11": {
                    "frequency": 5000.0,
                    "gain": 1.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band12": {
                    "frequency": 8000.0,
                    "gain": 4.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Hi-shelf",
                    "width": 4.0
                },
                "band13": {
                    "frequency": 12000.0,
                    "gain": 3.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band14": {
                    "frequency": 16000.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band2": {
                    "frequency": 90.0,
                    "gain": 3.0,
                    "mode": "RLC (MT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band3": {
                    "frequency": 125.0,
                    "gain": 2.5,
                    "mode": "RLC (MT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band4": {
                    "frequency": 200.0,
                    "gain": -2.0,
                    "mode": "RLC (MT)",
                    "mute": false,
                    "q": 1.5,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band5": {
                    "frequency": 350.0,
                    "gain": 1.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band6": {
                    "frequency": 500.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band7": {
                    "frequency": 800.0,
                    "gain": 1.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band8": {
                    "frequency": 1200.0,
                    "gain": 2.0,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band9": {
                    "frequency": 2000.0,
                    "gain": 2.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                }
            },
            "split-channels": false
        },
        "expander#0": {
            "attack": 20.0,
            "bypass": false,
            "dry": -100.0,
            "hpf-frequency": 10.0,
            "hpf-mode": "off",
            "input-gain": 0.0,
            "knee": -6.0,
            "lpf-frequency": 20000.0,
            "lpf-mode": "off",
            "makeup": 1.0,
            "mode": "Downward",
            "output-gain": 0.0,
            "ratio": 1.5,
            "release": 100.0,
            "release-threshold": -100.0,
            "sidechain": {
                "lookahead": 0.0,
                "mode": "RMS",
                "preamp": 0.0,
                "reactivity": 10.0,
                "source": "Middle",
                "stereo-split-source": "Left/Right",
                "type": "Internal"
            },
            "stereo-split": false,
            "threshold": -25.0,
            "wet": 1.0
        },
        "limiter#0": {
            "alr": true,
            "alr-attack": 5.0,
            "alr-knee": 2.5,
            "alr-release": 150.0,
            "attack": 5.0,
            "bypass": false,
            "dithering": "None",
            "external-sidechain": false,
            "gain-boost": true,
            "input-gain": 0.0,
            "lookahead": 5.0,
            "mode": "Herm Wide",
            "output-gain": 0.0,
            "oversampling": "None",
            "release": 5.0,
            "sidechain-preamp": 0.0,
            "stereo-link": 100.0,
            "threshold": -3.0
        },
        "pitch#0": {
            "anti-alias": true,
            "bypass": false,
            "cents": 0.0,
            "input-gain": 0.0,
            "octaves": 0.0,
            "output-gain": 0.0,
            "overlap-length": 15,
            "quick-seek": false,
            "rate-difference": 0.0,
            "seek-window": 25,
            "semitones": 0.0,
            "sequence-length": 50,
            "tempo-difference": 0.0
        },
        "plugins_order": [
            "equalizer#0",
            "compressor#0",
            "deesser#0",
            "bass_enhancer#0",
            "expander#0",
            "pitch#0",
            "reverb#0",
            "stereo_tools#0",
            "crossfeed#0",
            "limiter#0"
        ],
        "reverb#0": {
            "amount": -12.0,
            "bass-cut": 400.0,
            "bypass": false,
            "decay-time": 0.5,
            "diffusion": 0.5,
            "dry": 0.0,
            "hf-damp": 4000.0,
            "input-gain": 0.0,
            "output-gain": 0.0,
            "predelay": 5.0,
            "room-size": "Experimental",
            "treble-cut": 3000.0
        },
        "stereo_tools#0": {
            "balance-in": 0.0,
            "balance-out": 0.0,
            "bypass": false,
            "delay": 0.0,
            "input-gain": 0.0,
            "middle-level": 0.0,
            "middle-panorama": 0.0,
            "mode": "LR > LR (Stereo Default)",
            "mutel": false,
            "muter": false,
            "output-gain": 0.0,
            "phasel": false,
            "phaser": false,
            "sc-level": 1.0,
            "side-balance": 0.0,
            "side-level": 0.0,
            "softclip": false,
            "stereo-base": 0.0,
            "stereo-phase": 0.0
        }
    }
}
```

</details>

<details>
<summary><b>📁 Click to expand: input.json (Microphone Preset)</b></summary>

```json
{
    "input": {
        "blocklist": [],
        "compressor#0": {
            "attack": 15.0,
            "boost-amount": 6.0,
            "boost-threshold": -72.0,
            "bypass": false,
            "dry": -100.0,
            "hpf-frequency": 10.0,
            "hpf-mode": "off",
            "input-gain": 0.0,
            "knee": -6.0,
            "lpf-frequency": 20000.0,
            "lpf-mode": "off",
            "makeup": 2.0,
            "mode": "Boosting",
            "output-gain": 0.0,
            "ratio": 2.5,
            "release": 180.0,
            "release-threshold": -40.0,
            "sidechain": {
                "lookahead": 0.0,
                "mode": "RMS",
                "preamp": 0.0,
                "reactivity": 10.0,
                "source": "Middle",
                "stereo-split-source": "Left/Right",
                "type": "Feed-forward"
            },
            "stereo-split": false,
            "threshold": -19.0,
            "wet": 0.0
        },
        "deesser#0": {
            "bypass": false,
            "detection": "RMS",
            "f1-freq": 6000.0,
            "f1-level": -6.0,
            "f2-freq": 4500.0,
            "f2-level": -6.0,
            "f2-q": 1.5,
            "input-gain": 0.0,
            "laxity": 15,
            "makeup": 0.0,
            "mode": "Wide",
            "output-gain": 0.0,
            "ratio": 2.5,
            "sc-listen": false,
            "threshold": -14.0
        },
        "equalizer#0": {
            "balance": 0.0,
            "bypass": false,
            "input-gain": 0.0,
            "left": {
                "band0": {
                    "frequency": 80.0,
                    "gain": 0.0,
                    "mode": "LRX (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x3",
                    "solo": false,
                    "type": "Hi-pass",
                    "width": 4.0
                },
                "band1": {
                    "frequency": 200.0,
                    "gain": -1.5,
                    "mode": "BWC (MT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band2": {
                    "frequency": 500.0,
                    "gain": 1.5,
                    "mode": "BWC (MT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band3": {
                    "frequency": 3500.0,
                    "gain": 1.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band4": {
                    "frequency": 9000.0,
                    "gain": 1.0,
                    "mode": "BWC (MT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                }
            },
            "mode": "IIR",
            "num-bands": 5,
            "output-gain": 0.0,
            "pitch-left": 0.0,
            "pitch-right": 0.0,
            "right": {
                "band0": {
                    "frequency": 80.0,
                    "gain": 0.0,
                    "mode": "LRX (BT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x3",
                    "solo": false,
                    "type": "Hi-pass",
                    "width": 4.0
                },
                "band1": {
                    "frequency": 200.0,
                    "gain": -1.5,
                    "mode": "BWC (MT)",
                    "mute": false,
                    "q": 1.0,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band2": {
                    "frequency": 500.0,
                    "gain": 1.5,
                    "mode": "BWC (MT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band3": {
                    "frequency": 3500.0,
                    "gain": 1.5,
                    "mode": "BWC (BT)",
                    "mute": false,
                    "q": 1.2,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                },
                "band4": {
                    "frequency": 9000.0,
                    "gain": 1.0,
                    "mode": "BWC (MT)",
                    "mute": false,
                    "q": 0.7,
                    "slope": "x1",
                    "solo": false,
                    "type": "Bell",
                    "width": 4.0
                }
            },
            "split-channels": false
        },
        "gate#0": {
            "attack": 10.0,
            "bypass": false,
            "curve-threshold": -46.0,
            "curve-zone": -2.0,
            "dry": -100.0,
            "hpf-frequency": 10.0,
            "hpf-mode": "off",
            "hysteresis": true,
            "hysteresis-threshold": -3.0,
            "hysteresis-zone": -1.0,
            "input-gain": 0.0,
            "lpf-frequency": 20000.0,
            "lpf-mode": "off",
            "makeup": 0.0,
            "output-gain": 0.0,
            "reduction": -12.0,
            "release": 180.0,
            "sidechain": {
                "input": "Internal",
                "lookahead": 0.0,
                "mode": "RMS",
                "preamp": 0.0,
                "reactivity": 10.0,
                "source": "Middle",
                "stereo-split-source": "Left/Right"
            },
            "stereo-split": false,
            "wet": -1.0
        },
        "limiter#0": {
            "alr": true,
            "alr-attack": 5.0,
            "alr-knee": 0.0,
            "alr-release": 120.0,
            "attack": 1.0,
            "bypass": false,
            "dithering": "16bit",
            "external-sidechain": false,
            "gain-boost": false,
            "input-gain": 0.0,
            "lookahead": 6.0,
            "mode": "Herm Wide",
            "output-gain": 0.0,
            "oversampling": "Half x2(2L)",
            "release": 10.0,
            "sidechain-preamp": 0.0,
            "stereo-link": 100.0,
            "threshold": -2.0
        },
        "pitch#0": {
            "anti-alias": true,
            "bypass": false,
            "cents": 0.0,
            "input-gain": 0.0,
            "octaves": 0.0,
            "output-gain": 0.0,
            "overlap-length": 15,
            "quick-seek": false,
            "rate-difference": 0.0,
            "seek-window": 25,
            "semitones": 0.0,
            "sequence-length": 50,
            "tempo-difference": 0.0
        },
        "plugins_order": [
            "rnnoise#0",
            "gate#0",
            "compressor#0",
            "equalizer#0",
            "deesser#0",
            "pitch#0",
            "limiter#0"
        ],
        "rnnoise#0": {
            "bypass": false,
            "enable-vad": true,
            "input-gain": 0.0,
            "model-name": "",
            "output-gain": 0.0,
            "release": 25.0,
            "vad-thres": 25.0,
            "wet": 0.0
        }
    }
}
```

</details>

---

## 📋 Overview

This is a **professional-grade audio processing preset** for EasyEffects, designed to deliver:

| Feature | Output (Speakers/Headphones) | Input (Microphone) |
|---------|------------------------------|---------------------|
| **Sound Character** | Warm, punchy, detailed | Clean, clear, professional |
| **Bass Enhancement** | +5.5dB @ 64Hz shelf | Hi-pass @ 80Hz |
| **Dynamic Control** | Compressor + Expander + Limiter | Gate + Compressor + Limiter |
| **Noise Reduction** | — | RNNoise with VAD |
| **Stereo Enhancement** | Crossfeed + Stereo Tools | — |
| **Spatial Effects** | Reverb (subtle) | — |
| **Total Plugins** | 10 plugins | 7 plugins |

---

## 🔊 Output Chain (Speakers/Headphones)

### Plugin Order
```
Equalizer → Compressor → DeEsser → Bass Enhancer → Expander → Pitch → Reverb → Stereo Tools → Crossfeed → Limiter
```

### Key Settings Summary

| Plugin | Key Parameters |
|--------|---------------|
| **EQ** | 15 bands, +5.5dB @ 64Hz, -2.0dB @ 200Hz, +4.0dB @ 8kHz |
| **Compressor** | Boosting mode, threshold -25dB, ratio 5:1, attack 10ms |
| **DeEsser** | Wide mode, F2 @ 4.5kHz (-12dB), threshold -15dB |
| **Bass Enhancer** | Amount 3.0, harmonics 8.5, scope 120Hz |
| **Expander** | Downward, threshold -25dB, ratio 1.5:1 |
| **Reverb** | Experimental room, amount -12dB, decay 0.5s |
| **Crossfeed** | Fcut 800Hz, feed 7.0 |
| **Limiter** | Herm Wide, threshold -3dB, ALR enabled |

---

## 🎤 Input Chain (Microphone)

### Plugin Order
```
RNNoise → Gate → Compressor → Equalizer → DeEsser → Pitch → Limiter
```

### Key Settings Summary

| Plugin | Key Parameters |
|--------|---------------|
| **RNNoise** | VAD enabled, threshold 25%, release 25ms |
| **Gate** | Reduction -12dB, threshold -46dB, release 180ms |
| **Compressor** | Boosting mode, threshold -19dB, ratio 2.5:1 |
| **EQ** | 5 bands, Hi-pass @ 80Hz, +1.5dB @ 500Hz/3.5kHz |
| **DeEsser** | F1/F2 @ 6kHz/4.5kHz (-6dB), threshold -14dB |
| **Limiter** | Herm Wide, threshold -2dB, oversampling x2 |

---

## 🔧 Quick Tuning Guide

| Scenario | Adjustment |
|----------|------------|
| **Too much bass** | Reduce EQ Band 1 (64 Hz) from +5.5 to +3.0 |
| **Sounds muddy** | Increase EQ Band 4 (200 Hz) cut from -2.0 to -4.0 |
| **Too bright/harsh** | Reduce EQ Band 12 (8 kHz) from +4.0 to +2.0 |
| **Microphone too quiet** | Increase Compressor Makeup from +2.0 to +4.0 |
| **Background noise** | Increase RNNoise VAD Threshold to 30-35% |
| **Voice cutting out** | Decrease Gate Threshold from -46 to -52 dB |

---

## 📊 Signal Flow Diagram

```
                    OUTPUT CHAIN
┌─────────────────────────────────────────────────────────────────┐
│ Audio In → [EQ] → [COMP] → [DEESS] → [BASS] → [EXP] → [PITCH]  │
│           15band  Boosting  Sibilance  Harmonics Downward Bypass│
│                                                                 │
│ → [REVERB] → [STEREO] → [CROSS] → [LIMITER] → Audio Out        │
│    Spatial    Width      Feed       Protection                   │
└─────────────────────────────────────────────────────────────────┘

                    INPUT CHAIN
┌─────────────────────────────────────────────────────────────────┐
│ Mic In → [RNNoise] → [GATE] → [COMP] → [EQ] → [DEESS] →        │
│          AI Denoise   Silence   Boosting 5band  Sibilance       │
│                                                                 │
│ → [PITCH] → [LIMITER] → Audio Out                               │
│    Bypass    Protection                                          │
└─────────────────────────────────────────────────────────────────┘
```

---

# Русский

## 📥 Быстрая установка — Скопируй и вставь

### Сохранить как JSON файлы

Скопируй содержимое из секций выше:
- `output.json` — для колонок/наушников
- `input.json` — для микрофона

---

## 📋 Обзор

Это **профессиональный пресет обработки звука** для EasyEffects:

| Характеристика | Выход (Колонки/Наушники) | Вход (Микрофон) |
|----------------|--------------------------|-----------------|
| **Характер звука** | Тёплый, мощный, детальный | Чистый, ясный, профессиональный |
| **Усиление баса** | +5.5 дБ @ 64 Гц полка | Обрезной фильтр @ 80 Гц |
| **Динамическая обработка** | Компрессор + Экспандер + Лимитер | Гейт + Компрессор + Лимитер |
| **Шумоподавление** | — | RNNoise с VAD |
| **Стерео улучшение** | Crossfeed + Stereo Tools | — |
| **Всего плагинов** | 10 плагинов | 7 плагинов |

---

## 🔊 Цепочка выхода (Колонки/Наушники)

### Порядок плагинов
```
Эквалайзер → Компрессор → ДеЭссер → Басовый Энхансер → Экспандер → Питч → Ревербератор → Стерео Инструменты → Кроссфид → Лимитер
```

### Ключевые настройки

| Плагин | Ключевые параметры |
|--------|-------------------|
| **EQ** | 15 полос, +5.5 дБ @ 64 Гц, -2.0 дБ @ 200 Гц, +4.0 дБ @ 8 кГц |
| **Компрессор** | Режим Boosting, порог -25 дБ, ratio 5:1, атака 10 мс |
| **ДеЭссер** | Режим Wide, F2 @ 4.5 кГц (-12 дБ), порог -15 дБ |
| **Басовый Энхансер** | Количество 3.0, гармоники 8.5, диапазон 120 Гц |
| **Экспандер** | Нисходящий, порог -25 дБ, ratio 1.5:1 |
| **Ревербератор** | Experimental комната, количество -12 дБ, затухание 0.5 с |
| **Кроссфид** | Частота среза 800 Гц, подмешивание 7.0 |
| **Лимитер** | Herm Wide, порог -3 дБ, ALR включено |

---

## 🎤 Цепочка входа (Микрофон)

### Порядок плагинов
```
RNNoise → Гейт → Компрессор → Эквалайзер → ДеЭссер → Питч → Лимитер
```

### Ключевые настройки

| Плагин | Ключевые параметры |
|--------|-------------------|
| **RNNoise** | VAD включено, порог 25%, восстановление 25 мс |
| **Гейт** | Ослабление -12 дБ, порог -46 дБ, восстановление 180 мс |
| **Компрессор** | Режим Boosting, порог -19 дБ, ratio 2.5:1 |
| **EQ** | 5 полос, Hi-pass @ 80 Гц, +1.5 дБ @ 500 Гц/3.5 кГц |
| **ДеЭссер** | F1/F2 @ 6 кГц/4.5 кГц (-6 дБ), порог -14 дБ |
| **Лимитер** | Herm Wide, порог -2 дБ, передискретизация x2 |

---

## 🔧 Быстрая настройка

| Сценарий | Регулировка |
|----------|-------------|
| **Слишком много баса** | Уменьшить EQ Полосу 1 (64 Гц) с +5.5 до +3.0 |
| **Звук мутный** | Увеличить срез EQ Полосы 4 (200 Гц) с -2.0 до -4.0 |
| **Слишком ярко/резко** | Уменьшить EQ Полосу 12 (8 кГц) с +4.0 до +2.0 |
| **Микрофон слишком тихий** | Увеличить Makeup компрессора с +2.0 до +4.0 |
| **Фоновый шум** | Увеличить порог VAD RNNoise до 30-35% |
| **Голос обрезается** | Уменьшить порог гейта с -46 до -52 дБ |

---

<div align="center">

**[⬆ Back to Top](#-easyeffects-professional-audio-preset)**

*Professional Audio Processing for Linux*

</div>
