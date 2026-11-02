# Parakeet notices

NVIDIA parakeet-tdt-0.6b-v3 is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/legalcode).
The [FluidInference Core ML conversion](https://huggingface.co/FluidInference/parakeet-tdt-0.6b-v3-coreml)
is pinned to revision 7dd20fe6b1797d35f5e3307e8b1732d9a178edfe.
FluidInference converted the model to Core ML and quantized the encoder to int8.
CursorHalo only packages and mirrors these files unmodified. Weights are not bundled: they are downloaded on first use
from the `parakeet-tdt-0.6b-v3-coreml-r1` release of https://github.com/VolitionDigitalEnterprises/cursorhalo-models
and checked against pinned SHA-256 hashes and sizes before use.

FluidAudio v0.18.0 (FluidInference), Apache-2.0. A full copy of that licence
ships in `Phonon31M/LICENSE` in this app's Resources. No upstream NOTICE file exists.
The local MIT-licensed FluidAudioASR wrapper disables all optional traits:
TTS, Diarizer and NemoTextProcessing are excluded, including their data and notices.
FastClusterWrapper and MachTaskSelfWrapper remain unconditional dependencies.

## FastClusterWrapper (BSD-2-Clause)
Copyright:
  * Until package version 1.1.23: © 2011 Daniel Müllner <https://danifold.net>
  * All changes from version 1.1.24 on: © Google Inc. <https://www.google.com>
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

  * Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
  * Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
