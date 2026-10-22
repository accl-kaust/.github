<picture>
  <source media="(prefers-color-scheme: dark)" srcset="accl-lockup-colour-reverse.svg">
  <source media="(prefers-color-scheme: light)" srcset="accl-lockup-colour.svg">
  <img alt="ACCL Logo" src="accl-lockup-colour-on-navy.svg">
</picture>

# KAUST Accelerated Connected Computing Lab

The **Accelerated Connected Computing Lab (ACCL)** at KAUST, led by Prof. Suhaib Fahmy, works at the intersection of hardware acceleration and connected computing, looking at how innovation there can make systems more efficient, performant and secure. FPGAs are our main platform for exploring the interplay between connectivity and custom hardware, programmable accelerators, SmartNICs, and GPUs.

This organisation hosts the open-source code and research artifacts behind our work.

## 🌐 Network-attached acceleration

| Repository | Summary |
| --- | --- |
| [**frac**](https://github.com/accl-kaust/frac) | fRAC: clients invoke FPGA-hosted accelerators directly over the network with no host CPU involved. Multi-tenant, FaaS-style acceleration at 100 Gbps with 8 µs end-to-end latency on Alveo U280. |
| [**frac-atc26-artifact**](https://github.com/accl-kaust/frac-atc26-artifact) | Artifact for the ACM ATC '26 paper *fRAC: Remote Accelerator Calls on FPGAs*. Request-level, in-network invocation of FPGA accelerators at 100G, with runtime accelerator swapping via partial reconfiguration. [Docs](https://accl-kaust.github.io/frac-atc26-artifact/) · [Zenodo](https://doi.org/10.5281/zenodo.23200153) |

## 🔢 Efficient arithmetic and numerics

| Repository | Summary |
| --- | --- |
| [**mx-systolic-fpga**](https://github.com/accl-kaust/mx-systolic-fpga) | Open-source, parametrisable systolic arrays for OCP Microscaling (MX) minifloats (MXFP8/MXFP6) on FPGAs, with exact and BF16 accumulation modes for GEMM workloads. |
| [**ooc-cholesky-mx**](https://github.com/accl-kaust/ooc-cholesky-mx) | Out-of-core, GPU-based Cholesky factorisation with MX low-precision tile emulation, built on [ecrc/ooc-cholesky](https://github.com/ecrc/ooc-cholesky). |

## ⚡ AMD Versal AI Engines

| Repository | Summary |
| --- | --- |
| [**PRNGine**](https://github.com/accl-kaust/PRNGine) | Massively parallel pseudo-random number generation (XORWOW, XOROSHIRO, SFMT) and distribution approximation on AI Engines, as a co-processor or within a dataflow overlay. *CGRA4HPC @ IPDPS '25* |
| [**mc-option-pricing-aie**](https://github.com/accl-kaust/mc-option-pricing-aie) | A scalable dataflow overlay for Monte Carlo multi-asset option pricing on the VCK5000. *ISC '25* |
| [**fp-versal-bench**](https://github.com/accl-kaust/fp-versal-bench) | Benchmarks floating-point performance of massively parallel dataflow overlays on Versal AI Engines and DSP58s versus UltraScale+ DSP48E2s. |

## 📝 Research tooling

| Repository | Summary |
| --- | --- |
| [**PhiTeX**](https://github.com/accl-kaust/PhiTeX) | An incremental TeX engine in Rust: output is byte-identical to pdfTeX, and each edit rebuilds only what it affects. Targets native and WebAssembly. |
| [**PhiTeX-frontends**](https://github.com/accl-kaust/PhiTeX-frontends) | PhiTeX Instant for Overleaf (unofficial): a live, in-browser LaTeX preview that updates as you type. |
