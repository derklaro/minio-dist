# MinIO-DL

This repository automates the MinIO build process, creates binaries and container images from it, and publishes them as
releases or on Docker Hub. New releases are automatically created once a new tag is pushed to the upstream MinIO
repository. This project is a direct result of MinIO going source-only for the community edition.

### Useful Links

- [This Repository](https://github.com/derklaro/minio-dl)
- [Latest Release](https://github.com/derklaro/minio-dl/releases/latest)
- [Dockerhub](https://hub.docker.com/r/derklaro/minio)
- [MinIO Source](https://github.com/minio/minio)

### Notes on MinIO

MinIO is an open source project by MinIO, Inc. It is licensed under the GNU Affero General Public License v3.0 (AGPLv3).
The source code for MinIO is available here: https://github.com/minio/minio

All binaries, container images, or releases built by this repository that contain or are based on MinIO are also
subject to the AGPLv3 license. The code in this repository (e.g., build scripts, CI/CD workflows, and Dockerfiles),
unless part of MinIO itself, is licensed under the MIT License (see LICENSE).

#### Please note

If you redistribute or make publicly available the binaries or containers created here, you are required to comply with
the AGPLv3 license terms and provide or link to the complete source code.

#### Disclaimer

This is not an official build from MinIO, Inc. All trademarks and copyrights remain with their respective owners.
