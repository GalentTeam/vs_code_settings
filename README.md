# VS Code Settings

Course link: [VS Code course](https://go.galent.am/588)  
More themes: [VS Code themes](https://vscodethemes.com)  
For weak computers use `--disable-gpu`.

## Used Extensions

- Live Server
- Highlight matching tag
- Auto Rename Tag
- Image preview
- CSS Peek
- IntelliSense for CSS class names in HTML
- HTML to CSS autocompletion
- Minify
- Beautify
- Autoprefixer
- One Dark Pro
- Python
- Live Sass Compiler

- Project Manager
- SFTP

## Settings

```
{
    "editor.renderLineHighlight": "none",
    "editor.renderWhitespace": "none",
    "editor.wordWrap": "on",
    "editor.multiCursorModifier": "ctrlCmd",
    "files.autoSave": "onFocusChange",
    "editor.matchBrackets": "near",
    "window.zoomLevel": 1,
    "editor.fontSize": 16,
    "explorer.confirmDelete": false,
    "explorer.confirmDragAndDrop": false,
    "breadcrumbs.enabled": false,
    "editor.minimap.enabled": false,
    "editor.renderIndentGuides": false,
    "html.hover.references": false,
    "less.hover.references": false,
    "scss.hover.references": false,
    "css.hover.references": false,
    "html.hover.documentation": false,
    "css.hover.documentation": false,
    "less.hover.documentation": false,
    "scss.hover.documentation": false,
    "editor.mouseWheelZoom": true,
    "editor.occurrencesHighlight": false,

    // Extension: Live Server
    "liveServer.settings.donotShowInfoMsg": true,

    // Extension: Highlight Matching Tag
    "highlight-matching-tag.styles": {
        "opening": {
            "name": {
                "highlight": "rgba(255, 255, 255, 0.1)"
            }
        }
    },

    // Workbench: Color Customizations
    "workbench.colorTheme": "One Dark Pro Darker",
    "workbench.colorCustomizations": {
        "editor.background": "#1e2027",
        // "editor.selectionBackground": "#000",
        "editorCursor.foreground": "#999",
        "editorBracketMatch.background": "#ffffff1a",
        "editorBracketMatch.border": "#ffffff00",
        "editor.selectionHighlightBorder": "#ffffff00",
        // "editor.selectionHighlightBackground": "#ffffff1a",
        "editor.findMatchBorder": "#ffffff00",
        // "editor.findMatchBackground": "#40567c",
        "editor.findMatchHighlightBackground": "#ffffff1a",
    },

    // Terminal
    "terminal.integrated.defaultProfile.windows": "PowerShell",
}
```
