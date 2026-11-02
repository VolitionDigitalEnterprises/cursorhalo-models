# cursorhalo-models

This repository hosts model files that the CursorHalo macOS app downloads on first use.
It contains no app code. The model files are attached to GitHub releases, not committed.

## Releases

| Release tag | Contents |
| --- | --- |
| `parakeet-tdt-0.6b-v3-coreml-r1` | NVIDIA Parakeet TDT 0.6B v3, Core ML conversion by FluidInference, mirrored unmodified from [FluidInference/parakeet-tdt-0.6b-v3-coreml](https://huggingface.co/FluidInference/parakeet-tdt-0.6b-v3-coreml) at revision `7dd20fe6b1797d35f5e3307e8b1732d9a178edfe`. |

Each release lists the SHA-256 checksum and byte size of every file. The app checks both before it uses a download.

## Licence and attribution

**Parakeet TDT 0.6B v3** © NVIDIA Corporation, licensed under the
[Creative Commons Attribution 4.0 International licence (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/).

- Original model: [nvidia/parakeet-tdt-0.6b-v3](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3) by NVIDIA.
- Changes: FluidInference converted the model to Core ML and quantized the encoder to int8
  ([FluidInference/parakeet-tdt-0.6b-v3-coreml](https://huggingface.co/FluidInference/parakeet-tdt-0.6b-v3-coreml)).
  CursorHalo repackages the compiled `.mlmodelc` folders as zip files and makes no other changes.
- No warranty. See the licence for full terms.

The full notices file, `PARAKEET_THIRD_PARTY_NOTICES.md`, is in this repository and attached to each release.

The licence covers the model files only. It grants no rights to the CursorHalo app.
