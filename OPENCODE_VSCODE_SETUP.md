# OpenCode VSCode Setup Guide

## Installation

1. Install the OpenCode VSCode extension from the VSCode marketplace
2. Configure your settings in `.vscode/settings.json`
3. Set up keyboard shortcuts in `.vscode/keybindings.json`

## Troubleshooting

### Ctrl+P Not Working

If Ctrl+P is not working to access the OpenCode menu:

1. Check `.vscode/keybindings.json` is properly configured
2. Try resetting VSCode keybindings: `Developer: Reset Keyboard Shortcuts`
3. Verify the extension is loaded: `Help: Show Running Extensions`
4. Check for conflicts with other extensions

### Cannot Select OpenAgents

If you cannot pick from the OpenAgent list:

1. Ensure the OpenCode extension is properly installed and enabled
2. Restart VSCode: `Developer: Reload Window`
3. Check the output channel: `View: Output` → Select "OpenCode"
4. Verify your API configuration in settings

## Keyboard Shortcuts

- `Ctrl+P` - Open OpenCode menu (when editor has focus)
- `Ctrl+Shift+P` → "OpenCode: Show Menu" - Alternative access method

## Configuration

See `.vscode/settings.json` for recommended configuration options.
