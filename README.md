# usta.run machine client — releases

Builds of the usta.run machine client: the program that connects your own
computer to a usta.run workspace.

Nothing here is written by hand. Every release is built and published by CI
from the client's source, which lives in a private repository; this one is
public so that an installed client can download its updates without a
credential.

Each release carries:

- `ustarun-machine-setup.exe` — the Windows installer
- `ustarun-machine.exe` — the client itself, which an installed client
  updates to
- `latest.json` — the version, download addresses and SHA-256 digests the
  workspace reads to offer an update

The newest manifest is always at
`https://github.com/cihad/ustarun-client-releases/releases/latest/download/latest.json`.
