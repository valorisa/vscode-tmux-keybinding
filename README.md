# VSCode Tmux Keybinding

<img src="https://raw.githubusercontent.com/StephLin/vscode-tmux-keybinding/master/images/icon.png" height="128">

[![https://marketplace.visualstudio.com/items?itemName=stephlin.vscode-tmux-keybinding](https://vsmarketplacebadge.apphb.com/version/stephlin.vscode-tmux-keybinding.svg)](https://marketplace.visualstudio.com/items?itemName=stephlin.vscode-tmux-keybinding)
[![](https://vsmarketplacebadge.apphb.com/installs-short/stephlin.vscode-tmux-keybinding.svg)](https://marketplace.visualstudio.com/items?itemName=stephlin.vscode-tmux-keybinding)

This is a simple extension for tmux behavior in vscode terminal.

## Keybinding

| Shortcut           | Command                                          | When                                         |
| ------------------ | ------------------------------------------------ | -------------------------------------------- |
| `ctrl+b c`         | `workbench.action.terminal.newInActiveWorkspace` | `terminalFocus`                              |
| `ctrl+b shift+5`   | `workbench.action.terminal.split`                | `terminalFocus && panelPosition == 'bottom'` |
| `ctrl+b shift+4`   | `workbench.action.terminal.split`                | `terminalFocus && panelPosition != 'bottom'` |
| `ctrl+b x`         | `workbench.action.terminal.kill`                 | `terminalFocus`                              |
| `ctrl+b alt+up`    | `workbench.action.terminal.resizePaneUp`         | `terminalFocus`                              |
| `ctrl+b alt+down`  | `workbench.action.terminal.resizePaneDown`       | `terminalFocus`                              |
| `ctrl+b alt+left`  | `workbench.action.terminal.resizePaneLeft`       | `terminalFocus`                              |
| `ctrl+b alt+right` | `workbench.action.terminal.resizePaneRight`      | `terminalFocus`                              |
| `ctrl+b ctrl+b`    | `workbench.action.toggleSidebarVisibility`       | `terminalFocus`                              |
| `ctrl+b d`         | `workbench.action.terminal.toggleTerminal`       | `terminalFocus`                              |
| `ctrl+b w`         | `workbench.action.quickOpenTerm`                 | `terminalFocus`                              |
| `ctrl+b z`         | `workbench.action.toggleMaximizedPanel`          | `terminalFocus`                              |
| `shift+right`      | `workbench.action.terminal.focusNext`            | `terminalFocus`                              |
| `shift+left`       | `workbench.action.terminal.focusPrevious`        | `terminalFocus`                              |
| `ctrl+b right`     | `workbench.action.terminal.focusNextPane`        | `terminalFocus && panelPosition == 'bottom'` |
| `ctrl+b left`      | `workbench.action.terminal.focusPreviousPane`    | `terminalFocus && panelPosition == 'bottom'` |
| `ctrl+b down`      | `workbench.action.terminal.focusNextPane`        | `terminalFocus && panelPosition != 'bottom'` |
| `ctrl+b up`        | `workbench.action.terminal.focusPreviousPane`    | `terminalFocus && panelPosition != 'bottom'` |
| `ctrl+b 1`         | `workbench.action.terminal.focusAtIndex1`        | `terminalFocus`                              |
| `ctrl+b 2`         | `workbench.action.terminal.focusAtIndex2`        | `terminalFocus`                              |
| `ctrl+b 3`         | `workbench.action.terminal.focusAtIndex3`        | `terminalFocus`                              |
| `ctrl+b 4`         | `workbench.action.terminal.focusAtIndex4`        | `terminalFocus`                              |
| `ctrl+b 5`         | `workbench.action.terminal.focusAtIndex5`        | `terminalFocus`                              |
| `ctrl+b 6`         | `workbench.action.terminal.focusAtIndex6`        | `terminalFocus`                              |
| `ctrl+b 7`         | `workbench.action.terminal.focusAtIndex7`        | `terminalFocus`                              |
| `ctrl+b 8`         | `workbench.action.terminal.focusAtIndex8`        | `terminalFocus`                              |
| `ctrl+b 9`         | `workbench.action.terminal.focusAtIndex9`        | `terminalFocus`                              |
