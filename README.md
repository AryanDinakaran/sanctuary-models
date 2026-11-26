Official, hardware-calibrated neural network weights for **[Sanctuary](https://github.com/AryanDinakaran/sanctuary)** — 100% on-device sovereign intelligence for iOS and Apple Silicon.

Every model in this repository is distributed in **GGUF** format using `Q4_K_M` medium k-quantization. All models are tuned for Apple Silicon unified memory architectures, Metal Performance Shaders (MPS), and iOS Jetsam memory constraints.

---

## Model Catalog
| Model | Architecture | Parameters | Quantization | Size | Target Hardware | Primary Use |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Sanctuary Core 3B (Sovereign)** | Llama 3.2 (Fine-Tuned) | 3.21B | `Q4_K_M` | 1.88 GB | iPhone 15 Pro, iPhone 16 / 16 Pro, M-Series iPads & Macs | Tactical survival, executive negotiation, biometric telemetry, deep reasoning |
| **Sanctuary Compact 1B** | Llama 3.2 | 1.23B | `Q4_K_M` | 800 MB | iPhone 13, 14, 15 (Standard), SE | Fast everyday conversational assistant |
| **Sanctuary Pocket 360M** | SmolLM2 | 360M | `Q4_K_M` | 229 MB | All Apple devices | Instant startup, minimal battery footprint |
| **Sanctuary Vision** | SmolVLM | 2.2B | `Q4_K_M` | 1.04 GB | On-demand on all supported devices | 100% offline edge image perception & scene analysis |

---
## Production Release

All production model binaries are hosted on GitHub Releases with HTTP range-request support for resumable, background downloads:
- **Latest Release**: [v1.1.0 Sovereign Weights](https://github.com/AryanDinakaran/sanctuary-models/releases/tag/v1.1.0)

### What's New in v1.1.0 (Sanctuary Core 3B Sovereign):
- **Tactical Field Recovery & Triage**: Integrated doctrines from official military manuals (FM 21-76 and FM 20-22).
- **High-Stakes Negotiation & Frame Control**: Baked-in tactical empathy, calibrated questioning (Chris Voss doctrine), and dating wingman intelligence.
- **Biometric Telemetry Decoding**: Innate contextual adaptation to HealthKit vitals (sleep debt, HRV, and resting heart rate).
- **Zero Prompt Drift**: Personality, brevity, and formatting discipline embedded directly into neural layer weights.

---
## Architectural Highlights
- **Zero Cloud Calls**: Model weights are executed exclusively on local hardware via `llama.cpp` and Apple Metal shaders.
- **Transient Multimodal Pipeline**: The vision model executes as an isolated inference pass to prevent displacing active conversational models from unified RAM.
- **Resilient Background Networking**: Handled natively by iOS `URLSession` background daemons (`nsurlsessiond`) across Wi-Fi and Cellular.

---
## Attribution & Licenses
- **Sanctuary Core 3B (Sovereign)**: Developed & fine-tuned by Epochlypse Research. Base architecture built on Meta Llama 3.2 under the [Llama 3.2 Community License Agreement](https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/LICENSE).
- **SmolLM2 & SmolVLM**: Developed by Hugging Face. Distributed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).
- **Sanctuary Runtime**: Copyright © 2026 Epochlypse Research. All rights reserved.
