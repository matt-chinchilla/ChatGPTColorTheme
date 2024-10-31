# ChatGPT Color Theme

**A custom color palette that resembles the default ChatGPT programming output, specifically tailored for Python development.**

## Installation Instructions

### Step 1: Install the Theme

1. **Download and install** this theme from the Visual Studio Code Marketplace (or from a `.vsix` file, if you have packaged it locally).
2. **Apply the theme** in Visual Studio Code:
   - Open the **Command Palette** (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS).
   - Type "Preferences: Color Theme" and select "ChatGPT Color Theme".

### Step 2: Add Additional Customizations

To fully experience the **ChatGPT Color Theme**, add the following customizations to your VS Code `settings.json` file. These will apply semantic token color customizations, workbench color settings, and Python-specific formatting configurations.

#### Editor Semantic Token Color Customizations

Add the following to your `settings.json` file to customize colors for semantic tokens like functions, parameters, and classes:

```json
"editor.semanticTokenColorCustomizations": {
    "enabled": true,
    "rules": {
        "function": "#FFFFFF",
        "function.builtin": "#F5922F",
        "function.declaration": "#EC3479",
        "parameter": "#FFFFFF",
        "parameter.declaration": "#FFFFFF",
        "variable": "#FFFFFF",
        "class": "#7c09c9",
        "namespace": "#32CD32"
    }
}
```

#### Workbench Color Customizations

To match the overall look and feel of the theme, add these settings for the editor's background, foreground, and notebook views:

```json
"workbench.colorCustomizations": {
    "editor.background": "#000000",
    "editor.foreground": "#FFFFFF",
    "notebook.cellEditorBackground": "#000000",
    "notebook.focusedCellBackground": "#1F1F1F"
}
```

#### Python Formatter Settings

To make sure Python files are formatted consistently with the ChatGPT color theme, add the following Python-specific settings:

```json
"[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter",
    "editor.background": "#000000"
}
```

### Summary

By following these steps, you can experience the **ChatGPT Color Theme** in its entirety, with carefully chosen colors for Python programming and additional editor customization settings that create a consistent and pleasant coding environment.

- **Step 1**: Install the theme via the VS Code Marketplace.
- **Step 2**: Add the semantic token customizations, workbench color settings, and Python formatter settings to your `settings.json`.

Feel free to contribute to this project or report any issues on [GitHub](https://github.com/matt-chinchilla)
