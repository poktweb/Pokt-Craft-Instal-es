# Pokt Craft — Instalações

Pacotes do **Pokt Craft Launcher** para distribuição.

| Ficheiro | Descrição |
|----------|-----------|
| `Pokt-Craft-Launcher-0.1.0.exe` | Launcher portátil (~139 MB) — Windows 10/11 |
| `Pokt-Craft-Launcher-0.1.0-x86_64.flatpak` | Instalador Flatpak (~143 MB) — Linux x86_64 |

## Windows

Execute o `.exe` portátil.

## Linux (Flatpak)

```bash
flatpak install --user ./Pokt-Craft-Launcher-0.1.0-x86_64.flatpak
flatpak run com.clientmine.launcher
```

Requer o runtime `org.freedesktop.Platform//24.08` (Flathub) e a BaseApp Electron (instalados automaticamente se o Flathub estiver configurado).

Download: [poktcraft.shop](https://poktcraft.shop)
