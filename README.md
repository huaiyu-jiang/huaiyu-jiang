### Hi, I'm Dan (Huaiyu Jiang) 👋

AI/ML Engineer at [AtlasCloud](https://www.atlascloud.ai), an LLM inference provider on OpenRouter. I work on making large models serve faster and cheaper: speculative decoding, attention kernels, disaggregated serving, and TPU bring-up.

**What I've been working on**
- **Speculative decoding**: tuned MTP for GLM-5.1 (744B MoE, 8×H200), +32.6% output throughput at k=3
- **Sparse attention kernels**: hierarchical indexed sparse attention as a DSA replacement, 2.7–5.1× kernel speedup
- **Kernels**: TileLang fused RMSNorm-SiLU for the Wan VAE (~1.8× end-to-end); an agent for CUDA kernel optimization (~13% end-to-end on LongCat)
- **Serving**: prefill/decode disaggregation with dynamic P/D instance scheduling
- **TPU**: contributing to vllm-torchtpu and sglang-torchtpu

**Open-source contributions**
<!-- add merged PRs here, e.g. -->
<!-- - sgl-project/sglang #xxxxx: short description -->

**Background**: M.S. Columbia University · B.S. UC Davis (CS) · previously systematic crypto strategies at Lucy Labs and research at Acadian Asset Management
