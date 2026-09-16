# Nova Launcher

Nova Launcher is a personal, non-commercial custom Minecraft launcher built with Python and CustomTkinter.

## Features

- Dark, space-themed interface with a dynamically generated starry background
- Sign in with your own Microsoft account (Xbox Live / Minecraft Services authentication)
- Launches modded Minecraft instances using the Fabric mod loader
- Built from scratch — no third-party launcher frameworks

## Tech Stack

- Python
- [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter) for the UI
- [minecraft-launcher-lib](https://minecraft-launcher-lib.readthedocs.io/) for installation, authentication, and launching

## Status

Actively in development. Core UI is complete; Microsoft authentication and launch logic are being finalized.

## Authentication

Nova Launcher uses the standard Microsoft OAuth2 authorization code flow to authenticate players with their own Microsoft account. No passwords are ever seen or stored by this application — all sign-in happens directly through Microsoft's own login page.

## License

Personal project, not for redistribution without permission.
