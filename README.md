# LocaiOS — Local AI for iOS

LocaiOS is a privacy-first, on-device chatbot framework targeted for iPhone devices (iPhone 15, XR, ...).  
This repo contains:

- `web/` — simple Safari-friendly chat UI (static HTML + JS).
- `ios/` — Swift app skeleton that embeds a local server and bridges to a local LLM binary (e.g., a GGML/llama.cpp build or Core ML model).
- `models/` — place small, mobile-ready model files here (e.g., SmolLM, TinyLlama ggml files or converted Core ML models).

### Goals
- Run offline on-device (private).
- Offer a web UI accessible from Safari (http://localhost:xxxx) or as a native SwiftUI view.
- Provide multiple model slots and an upgrade path to Core ML.

### References
- Apple on-device Llama/Core ML guide (Apple Machine Learning).  [oai_citation:4‡Apple Machine Learning Research](https://machinelearning.apple.com/research/core-ml-on-device-llama?utm_source=chatgpt.com)
- Community runtimes (llama.cpp / ggml iOS integration).  [oai_citation:5‡GitHub](https://github.com/ggml-org/llama.cpp/discussions/4423?utm_source=chatgpt.com)
