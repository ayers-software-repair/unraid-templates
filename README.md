# Ayers Electronics Unraid templates

Community Applications templates for Ayers Electronics products. The templates describe containers; they do not grant a license to the proprietary applications or Docker images they install.

## Magpie

Magpie is the self-hosted, cable-TV-first media server. The Community Applications template uses `ayerselectronics/magpie:latest`, host networking, and the Magpie web interface on port `24622`.

The template mounts persistent application data at `/data` (default `/mnt/user/appdata/magpie`) and the media library at `/media` (default `/mnt/user/media`). Review those paths and permissions for your server before applying the template.

Project: https://ayers.repair/magpie/
Support: https://ayers.repair/magpie/support.html

## Template license

The repository's MIT license applies only to the repository's authored template XML and supporting repository files. It does not license Magpie software, the `ayerselectronics/magpie` image, or other product assets. See [LICENSE](LICENSE).

## Community Applications

The repository is intended for submission to Unraid Community Applications. Template updates are reviewed and scanned through the Unraid submission flow.
