# Subten on-device AI models

GGUF model files downloaded by the Subten iOS app for its on-device AI coach.

- `subten-base-q4-*.gguf` / `subten-base-q5-*.gguf` — split GGUF of **Gemma 4 E2B it** (quantized Q4_K_M / Q5_K_M), originally from [unsloth/gemma-4-E2B-it-GGUF](https://huggingface.co/unsloth/gemma-4-E2B-it-GGUF).
- License: **Apache-2.0** (Gemma 4, © Google). Redistributed unmodified in split-GGUF form.
- `manifest.json` — tells the app which files/version to fetch per device tier.

Not intended for direct use — see the Subten app.
