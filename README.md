The legacy i965 video acceleration driver, packaged as a Flatpak for Freedesktop runtimes that have not reached end of life. This repository is unsigned, so `--no-gpg-verify` is required when adding the remote. It builds a fork of intel-vaapi-driver: https://github.com/irql-notlessorequal/intel-vaapi-driver. The GPL-3.0 license only covers this repository, the driver and its dependencies may have different licenses.

Installation:
```bash
flatpak remote-add --user --no-gpg-verify --if-not-exists vaapi-i965-repo 'https://snappyhaswell.github.io/vaapi-i965-repo/'
```

```bash
flatpak install --user vaapi-i965-repo org.freedesktop.Platform.VAAPI.Intel
```
