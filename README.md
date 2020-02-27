Settings json:

{
    "workbench.startupEditor": "newUntitledFile",
    "editor.fontSize": 12,
    "window.zoomLevel": 1,
    "git.confirmSync": false,
    "editor.formatOnSave": true,
    "explorer.confirmDelete": false,
    "git.enableSmartCommit": true,
    "latex-workshop.view.pdf.viewer": "tab",
    "latex-workshop.latex.recipes": [
        {
            "name": "pdflatex",
            "tools": [
                "pdflatex"
            ]
        }
    ],
    "latex-workshop.latex.tools": [
        {
            "name": "pdflatex",
            "command": "pdflatex",
            "args": [
                "--shell-escape", // if you want to have the shell-escape flag
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOC%.tex"
            ]
        }
    ]
}

Command: STRG + Alt + b