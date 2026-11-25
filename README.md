# byOS Store Plugins (PLG1)

Repositório público de plugins nativos (`.byt` / `kind: plugin`) para a **byStore** do **byOS** (`Topbar`, `Dockbar` e `Desktop`).

## Estrutura
- `catalog.json`: catálogo indexado pela aba **Plugins** e categoria **Plugins** da `byStore`.
- `packages/`: pacotes `.byt` assinados com Ed25519.
- `icons/`: ícones `.svg` / `.png` de cada plugin.

## Plugins incluídos

| ID | Nome | Versão | byOS Mín. | Slot | Pacote |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `by-capture-hub` | Captura e Historico | `v1.0.0` | `>= 2026.11` | `topbar` | `packages/by-capture-hub.byt` (2474 B) |
| `by-media-pill` | Controle de Midia | `v1.1.0` | `>= 2026.11` | `topbar` | `packages/by-media-pill.byt` (1728 B) |
| `by-usb-eject` | Ejetar USB | `v1.1.0` | `>= 2026.11` | `topbar` | `packages/by-usb-eject.byt` (2042 B) |
| `by-battery-power` | Energia e Tela | `v1.0.0` | `>= 2026.11` | `topbar` | `packages/by-battery-power.byt` (2156 B) |
| `by-dock-folder` | Grupo de Apps | `v1.1.0` | `>= 2026.11` | `dockbar` | `packages/by-dock-folder.byt` (2080 B) |
| `by-classic-app-menu` | Menu de Apps Clássico | `v1.0.0` | `>= 2026.11` | `dockbar` | `packages/by-classic-app-menu.byt` (3453 B) |
| `by-net-monitor` | Monitor de Rede | `v1.1.0` | `>= 2026.11` | `topbar` | `packages/by-net-monitor.byt` (2400 B) |
| `by-minimal-clock` | Relogio Minimal | `v1.0.0` | `>= 2026.11` | `desktop` | `packages/by-minimal-clock.byt` (1503 B) |
| `by-dock-power` | Energia na Dock | `v1.0.0` | `>= 2026.12.1` | `dockbar` | `packages/by-dock-power.byt` (1805 B) |
| `by-dock-trash` | Lixeira | `v1.0.0` | `>= 2026.12.1` | `dockbar` | `packages/by-dock-trash.byt` (3056 B) |
