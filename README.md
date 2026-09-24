# StudioSeven Releases

Installers for the StudioSeven app suite. Source code lives in private repositories; this repo only hosts release assets and notes.

Each app uses its own tag prefix, and every asset carries its version in the filename:

| App | Tag prefix | Asset |
|-----|-----------|-------|
| Pure Harmony Admin | `pureharmony-admin-v<version>` | `PureHarmony-<version>.dmg` |
| Ether Cloud | `ether-cloud-v<version>` | `EtherCloud-<version>.dmg` |

Apps auto-update through Sparkle; the appcast for each app points at the release assets here.
