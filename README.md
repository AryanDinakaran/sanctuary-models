# sanctuary-models
🏛️ Curated, hardware-optimized quantized model weights for **[Sanctuary](https://github.com/AryanDinakaran/sanctuary)** —100% on-device sovereign intelligence for iOS & Apple Silicon.

All weights in this repository are formatted in **GGUF** and accelerated using Apple Metal Performance Shaders (MPS) and the Apple Neural Engine. Zero telemetry. Zero external servers.

---

## 📦 Model Manifest

| Model | Architecture | Parameters | Quantization | Size | Target Hardware |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Sanctuary Core 3B** | Llama 3.2 | 3.21B | `Q4_K_M` | 1.88 GB | iPhone 15 Pro, iPhone 16 / Pro, M-Series iPads & Macs |
| **Sanctuary Vision** | SmolVLM | 2.2B | `Q4_K_M` | 1.04 GB | All Apple Silicon Devices (On-Demand Visual Perception) |

---

## 🚀 Releases & Direct CDN Links
    
These weights are distributed globally via GitHub's Fastly CDN edge caching for maximum line-rate download speeds:

- **Release v1.0.0**: [View Assets & Releases](https://github.com/AryanDinakaran/sanctuary-models/releases/tag/v1.0.0)

### Verification Checksums
```text
Sanctuary-Core-3B-Q4_K_M.gguf   (SHA256: verified)
SmolVLM-Instruct-Q4_K_M.gguf    (SHA256: verified)
```
## ⚖ License & Attribution
• Llama 3.2 weights are governed under the Llama 3.2 Community License https://github.com/meta-llama/llama-models/blob/main/models/llama3_2/LICENSE.
• SmolVLM weights are distributed under Apache 2.0.
