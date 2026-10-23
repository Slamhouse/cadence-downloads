# Cadence third-party notices

Cadence is a personal derivative of [Handy](https://github.com/cjpais/Handy), originally copyright 2025 CJ Pais, under the MIT license. The original LICENSE and Git history are retained. Cadence is independently maintained by Slamhouse and is not affiliated with Wispr Flow.

The Windows package includes the Vulkan build of [llama.cpp](https://github.com/ggml-org/llama.cpp), build b11669, under MIT. Its license is included in the runtime directory. The archive SHA-256 is checked during packaging.

Optional local polish downloads [Qwen3.5-4B-GGUF](https://huggingface.co/unsloth/Qwen3.5-4B-GGUF), quantized by Unsloth from [Qwen3.5-4B](https://huggingface.co/Qwen/Qwen3.5-4B), revision e87f176479d0855a907a41277aca2f8ee7a09523, quantization Q4_K_M. Its SHA-256 is checked before installation. The original model's Apache 2.0 license is included with the runtime. Model weights are downloaded separately and are not embedded in the installer.

Speech models retain their respective licenses, shown in the model catalog. Other dependencies retain their original notices. See Cargo.lock and bun.lock for exact versions.
