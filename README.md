# deci-models

Download mirror for the local voice models used by Deci Control. The app downloads these files on first use,
checks size and SHA-256 and shows the license of each model. Nothing here is modified by Deci Controls except the
ONNX export of Thorsten (see below).

## Release `models-v1`

| Asset | License | Source |
|---|---|---|
| `kokoro-v1.0.onnx`, `voices-v1.0.bin` | Apache-2.0 (`licenses/kokoro.txt`) | hexgrad/Kokoro-82M via thewh1teagle/kokoro-onnx |
| `tts-de-thorsten-*` | Apache-2.0, training data CC0 (`licenses/thorsten.txt`) | Thorsten-Voice Kokoro (German), exported to ONNX |
| `tts-de-apptor-*` | Apache-2.0 (`licenses/apptor.txt`, `tts-de-apptor-LICENSE.txt`) | apptor/apptor-tiny-tts |
| `tts-de-de_overrides.json` | Apache-2.0 (`licenses/misaki.txt`, `tts-de-LICENSE-misaki.txt`) | hexgrad/misaki |

Whisper and eSpeak NG are downloaded by the app from their official sources and are not mirrored here.
