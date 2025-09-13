# Flutter

Flutter Basic.

## Flutter CMD

Comandos e configurações básicas para projeto em Flutter.

1. Flutter Profile
```json
{
    "dart.lineLength": 100,
    "[dart]": {
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.rulers": [
            100
        ],
        "editor.selectionHighlight": false,
        "editor.suggestSelection": "first",
        "editor.tabCompletion": "onlySnippets",
        "editor.wordBasedSuggestions": "off"
    },
    "editor.codeActionsOnSave": {
        "source.fixAll": "explicit",
        "quickfix.insertSemicolon": "explicit",
        "source.organizeImports": "explicit"
    },
    "editor.fontSize": 13,
    "editor.fontFamily": "Source Code Pro",
    "terminal.integrated.cursorStyle": "line",
    "dart.flutterSdkPath": "C:\\dev\\flutter",
    "files.exclude": {
        "**/*.dart_tool": true,
        "**/*.idea": true,
        "**/*.metadata": true,
        "**/*.vscode": true,
        "**/flutter_fundamentos.iml": true
    },
    "terminal.integrated.fontFamily": "MesloLGM Nerd Font",
    "terminal.integrated.fontSize": 13,
    "workbench.colorTheme": "Webstorm IntelliJ Darcula Theme",
    "workbench.iconTheme": "material-icon-theme",
    "editor.rulers": []
}
```

2. Extensions
<img width="1365" height="720" alt="flutter-extensions" src="https://github.com/user-attachments/assets/128f5edc-91a9-4c25-a6ab-3b27a95b64fb" />

3. Criar novo projeto em Flutter
```powershell
flutter create --project-name=my_project_name --org br.com.my_org --platforms android,ios -a kotlin -i swift ./my_project_name_folder
```

## Flutter - Basic Widgets

Este projeto contempla a apresentação de alguns dos principais widgets do Flutter com o detalhe de suas implementações dividas em páginas.

Lista de Widgets:

- PopupMenuButton (HomePage)
- Container
- Rows & Columns
- MediaQuery
- LayoutBuilder
- Botões e Rotação de Texto
- SingleChidScrollView
- ListView
- Dialogs
- SnackBar
