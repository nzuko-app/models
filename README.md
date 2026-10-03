
# Nzuko speaker models (ORT format)

ONNX Runtime `.ort` conversions used by Nzuko and Captur for on-device speaker
diarization. They are downloaded on first use and checked by SHA-256. They are
the same weights as upstream, only converted to ORT format for a reduced-operator
runtime.

| File | Bytes | SHA-256 | Upstream | Licence |
|---|---:|---|---|---|
| `segmentation-3.0.ort` | 6,011,328 | `11fb360af5e185214fee82d45a51716865c1b630ad826151152ac738dcd86f5b` | [pyannote/segmentation-3.0](https://huggingface.co/pyannote/segmentation-3.0) via the ONNX export [csukuangfj/sherpa-onnx-pyannote-segmentation-3-0@9403a69](https://huggingface.co/csukuangfj/sherpa-onnx-pyannote-segmentation-3-0/tree/9403a6902bb58e3d5ae8c7e77c3422de279db2e0) | MIT, Copyright (c) 2022 CNRS. See `LICENSE-pyannote-segmentation-MIT` |
| `wespeaker_en_voxceleb_resnet34_LM.q8.ort` | 6,805,976 | `706a89167cd1ec62c99a297119623c653e81ba3f6bb1a662711896fbe9d16a09` | [Wespeaker/wespeaker-resnet34-LM@f0c48c2](https://huggingface.co/Wespeaker/wespeaker-resnet34-LM/blob/f0c48c298fd835726c27956a5d617bad7115627e/README.md), int8-quantized | [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/legalcode). Attribution: the WeSpeaker project. Modified: quantized to int8 and converted to ORT format |

Download the files from this repository's [releases](https://github.com/nzuko-app/models/releases). Release assets are never replaced, so a new or changed file always gets a new release tag.
