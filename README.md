# My-WebSite

# VS-code settings:

{
"editor.wordWrap": "on",
"editor.formatOnPaste": true,
"editor.formatOnSave": true,
"emmet.includeLanguages": {
"javascript": "javascriptreact"
},
"highlight-matching-tag.styles": {
"opening": {
"left": {
"custom": {
"borderWidth": "0 0 0 3px",
"borderStyle": "solid",
"borderColor": "yellow",
"borderRadius": "5px",
"overviewRulerColor": "white"
}
},
"right": {
"custom": {
"borderWidth": "0 3px 0 0",
"borderStyle": "solid",
"borderColor": "yellow",
"borderRadius": "5px",
"overviewRulerColor": "white"
}
}
}
},
"explorer.confirmDelete": false,
"code-runner.executorMapByFileExtension": {
".vb": "cd $dir && vbc /nologo $fileName && $dir$fileNameWithoutExt",
".vbs": "cscript //Nologo",
".scala": "scala",
".jl": "julia",
".cr": "crystal",
".ml": "ocaml",
".exs": "elixir",
".hx": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
    ".rkt": "racket",
    ".scm": "csi -script",
    ".ahk": "autohotkey",
    ".au3": "autoit3",
    ".kt": "cd $dir && kotlinc $fileName -include-runtime -d $fileNameWithoutExt.jar && java -jar $fileNameWithoutExt.jar",
    ".kts": "kotlinc -script",
    ".dart": "dart",
    ".pas": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
".pp": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
".d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
".hs": "runhaskell",
".nim": "nim compile --verbosity:0 --hints:off --run",
".csproj": "dotnet run --project",
".fsproj": "dotnet run --project",
".lisp": "sbcl --script",
".kit": "kitc --run",
".v": "v run",
".vsh": "v run",
".sass": "sass --style expanded",
".cu": "cd $dir && nvcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
".ring": "ring",
".js": "node"
},
"launch": {
"configurations": [
{
"outputCapture": "std"
}
],
"compounds": []
},
"bracketPairColorizer.depreciation-notice": false,
"workbench.list.automaticKeyboardNavigation": false,
"diffEditor.ignoreTrimWhitespace": false,
"prettier.jsxSingleQuote": true,
"editor.defaultFormatter": "esbenp.prettier-vscode",
"[css]": {
"editor.defaultFormatter": "vscode.css-language-features"
},
"[javascript]": {
"editor.defaultFormatter": "esbenp.prettier-vscode"
},
"editor.cursorBlinking": "expand",
"editor.tabSize": 2,
"javascript.updateImportsOnFileMove.enabled": "always",
"window.newWindowDimensions": "inherit",
"liveServer.settings.donotShowInfoMsg": true,
"typescript.updateImportsOnFileMove.enabled": "always",
"git.autofetch": true
}
