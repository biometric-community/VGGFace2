# VGGFace2

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FVGGFace2-181717?logo=github)](https://github.com/biometric-community/VGGFace2)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://www.robots.ox.ac.uk/~vgg/data/vgg_face2/)

**VGGFace2** — tbiom catalog packaging for `vggface2` (face-recog; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/VGGFace2
- **Upstream source**: https://www.robots.ox.ac.uk/~vgg/data/vgg_face2/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `vggface2` |
| Category | `face-recog` |
| Access | `register` |
| Upstream homepage | https://www.robots.ox.ac.uk/~vgg/data/vgg_face2/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Oxford VGG Face 2; registration required.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/VGGFace2.git
cd VGGFace2
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_vggface2.sh
```

Place licensed archives under `projects/datasets/vggface2/` (gitignored).

## Dataset structure

```text
VGGFace2/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://www.robots.ox.ac.uk/~vgg/data/vgg_face2/
- Packaging: https://github.com/biometric-community/VGGFace2/issues
