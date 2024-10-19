# VS Code Custom Configuration

This repository contains custom CSS and JS configurations for Visual Studio Code using the [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) plugin.

## Installation Instructions

1. **Install the Custom CSS and JS Loader Extension**
   - Download and install the plugin from [here](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css).
   - Or search it up in the plugin list in vscode.
   
2. **Clone the Repository**
   - Clone this repository to your local machine or download the files directly:
     ```bash
     git clone https://github.com/raincuhh/vs-code-config.git
     ```

3. **Edit Your VS Code Settings**
   - Add the following to your `settings.json` file to load the custom CSS and JS:

   ```json
   "vscode_custom_css.imports": [
       "file:///C:/path/to/the/repository/vs-code-config/vscode_css_config.css",
       "file:///C:/path/to/the/repository/vs-code-config/vscode_js_config.js"
   ]
   ```

4. **Enable Custom Styles**
   - After editing the settings, run the command `Reload Custom CSS and JS` from the VS Code command palette (`Ctrl+Shift+P`).

5. **Restart VS Code**
   - Close and reopen Visual Studio Code for the changes to take effect.

## File Descriptions

- **vscode_css_config.css**: Contains custom CSS styles for enhancing the appearance of VS Code.
- **vscode_js_config.js**: Contains custom JavaScript for additional functionality or modifications.

## Notes

- You may need to run Visual Studio Code with the `--disable-extensions` flag if there are issues with the custom CSS/JS.
- Ensure that you have file system access permissions for the paths specified in the `settings.json`.

## Troubleshooting

- If the custom styles do not load after restarting, make sure that:
  - The paths in `settings.json` are correct and use the `file:///` protocol.
  - The plugin is enabled and properly installed.
  - You run the `Reload Custom CSS and JS` command after making changes.
```
Feel free to modify the text to better fit your needs!
