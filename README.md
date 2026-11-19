# MockQuest model files

Model files for the MockQuest Android app. Copies of the app installed from the Play Store get these from Google Play; only test copies installed directly (not from Play) download them from here.

## Files (release `v1`)

| File | Used for | Original source |
|---|---|---|
| `gemma3-1b-it-int4.task` | MockBuddy's AI | Gemma 3 1B (instruction-tuned, int4) by Google, MediaPipe format |
| `asr-encoder.int8.onnx`, `asr-decoder.onnx`, `asr-joiner.int8.onnx`, `asr-tokens.txt` | English speech recognition | [csukuangfj/sherpa-onnx-streaming-zipformer-en-20M-2023-02-17](https://huggingface.co/csukuangfj/sherpa-onnx-streaming-zipformer-en-20M-2023-02-17) |
| `kitten-nano-en-v0_2-fp16.tar.bz2` | Standard voices | [k2-fsa/sherpa-onnx tts-models](https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models) |
| `vits-piper-en_US-lessac-medium.tar.bz2` | Lessac voice | [k2-fsa/sherpa-onnx tts-models](https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models) |
| `vits-piper-en_GB-alba-medium.tar.bz2` | Alba voice | [k2-fsa/sherpa-onnx tts-models](https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models) |

All files are unmodified copies, each under its original licence.

## Gemma licence

Gemma is provided under and subject to the Gemma Terms of Use found at https://ai.google.dev/gemma/terms. Use of Gemma is also subject to the Gemma Prohibited Use Policy at https://ai.google.dev/gemma/prohibited_use_policy. See [NOTICE](NOTICE).
