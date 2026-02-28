# Todoist Quick Save

A Firefox extension that allows you to quickly save the current URL as a task to a predefined Todoist project using a keyboard shortcut, a toolbar button, or a context menu.

## Installation

You can install the extension directly from the Firefox Add-ons store:
[Todoist Quick Save on Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/todoist-quick-save/)

## Features

- **Keyboard Shortcut**: Save the current URL instantly with `Ctrl+Alt+S` (default).
- **Toolbar Button**: Click the extension icon in the toolbar to save the current page.
- **Context Menu**: 
  - Right-click on any link to save it directly to Todoist.
  - Right-click the extension icon to access configuration.
- **Project Specific**: Automatically saves tasks to a specific project ID of your choice.

## Configuration

After installation, you need to configure the extension with your Todoist API details:

1. Right-click the extension icon and select **Configure**.
2. Enter your **Todoist API Token**. You can find this in your [Todoist Integrations Settings](https://todoist.com/app/settings/integrations).
3. Enter the **Project ID** where you want tasks to be saved. You can find the Project ID in the URL when you open a project in the Todoist web app (it's the number at the end of the URL).
4. Click **Save**.

## Usage

- **Save Current Page**: Press `Ctrl+Alt+S` or click the extension's toolbar icon.
- **Save a Link**: Right-click any link and select **Todoist autosave**.
- **Configure**: Right-click the extension icon and select **Configure**.

## Privacy & Security

- **No Data Collection**: This extension does not collect, store, or transmit any user data to external servers other than the Todoist API.
- **Local Storage**: Your API Token and Project ID are saved securely using Firefox's built-in `browser.storage.sync` API. This means your settings are stored locally on your device (and synced across your Firefox instances if sync is enabled) and are never accessible by the developer.

## License

This project is open-source and available under the [MIT License](LICENSE).
