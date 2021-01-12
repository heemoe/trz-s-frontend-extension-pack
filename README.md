# README
前端常用插件集合

## 常用插件

1. Npm
2. Npm Intellisense
3. Auto Rename Tag
4. Auto Close Tag
5. ESLint
6. Path Intellisense
7. vetur
8. Color the tag name
9. Prettier
## 推荐设置 Recommended Settings
···

{
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "editor.wordSeparators": "`~!@#$%^&*()=+[{]}\\|;:'\",.<>/?",
  "path-intellisense.extensionOnImport": true,
  "git.enableSmartCommit": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "editor.formatOnSave": true,
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "editor.defaultFormatter": "vscode.typescript-language-features",
  "files.associations": {
    "*.cjson": "jsonc",
    "*.wxss": "css",
    "*.wxs": "javascript"
  },
  "emmet.includeLanguages": {
    "wxml": "html"
  },
  "minapp-vscode.disableAutoConfig": true,
"cSpell.userWords": [
  "iife",
  "sourcemap"
],
"gitlens.advanced.messages": {
  "suppressCommitHasNoPreviousCommitWarning": true
},
"tabnine.experimentalAutoImports": true,
}

···