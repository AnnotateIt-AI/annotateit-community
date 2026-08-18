# Roadmap

Last reviewed against the shipping application: 18 August 2026.

This roadmap shows the current direction of AnnotateIt AI at a high level. Priorities may change with product feedback and technical findings. Inclusion does not guarantee delivery, and no dates are promised.

Released web-app changes are recorded in the [public changelog](https://annotateit.ai/changelog/).

## Already shipped

These are current capabilities, not roadmap items:

- Dataset versions with compare, download and restore
- On-device quality scans and deterministic train/validation/test splits
- Activity history, dataset copies and portable project/profile backups
- Video tracks with manual keyframes and local interpolation
- MOT, MOTS and KITTI export alongside COCO, YOLO, Pascal VOC, Datumaro, Supervisely Video and Plain ZIP
- Batch pre-labelling with review, semantic search and custom ONNX inference
- A desktop local REST API with access-token authentication

Rotated boxes can be imported, rendered and edited today, and Datumaro preserves their angle. There is not yet a rotated-box drawing tool or native YOLO OBB/DOTA round trip. Video tracks interpolate user-supplied keyframes; no model follows an object automatically.

## Now

- Finish and document the remaining local REST API gaps, publish a stable OpenAPI contract and decide how a supported command-line client should be distributed
- Continue import/export round-trip hardening, loss warnings and regression coverage across tasks and shapes
- Harden long-video workflows, including classification ranges and large-project performance
- Build the planned self-hosted Docker image for on-premise and air-gapped environments

## Next

- Complete oriented-bounding-box workflows: drawing, numeric angle editing and native OBB formats
- Add automatic local video propagation/tracking as an optional assistant to manual tracks
- Extend dataset quality assistance with near-duplicate detection and carefully scoped fixes
- Evaluate a thin Python client after the REST API stabilises

## Exploring

These directions are less certain and depend on demonstrated demand:

- Linux and Android distributions
- Additional compatible local model architectures
- Optional external storage integrations
- Broader accessibility and localisation work

## Deliberately out of scope

AnnotateIt is focused on private, single-user, local annotation. The current direction does not include mandatory cloud storage, hosted model training, workforce management, enterprise SSO/RBAC, seat-based team billing, DICOM workflows or LiDAR/3D annotation.

Have a concrete need? Open a [feature request](https://github.com/AnnotateIt-AI/annotateit-community/issues/new?template=feature.yml) and describe the workflow and constraints. Specific use cases influence priority more than votes.
