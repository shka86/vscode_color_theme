vscode_color_theme
====

Usage
---

`.vscode\extensions` の直下に shka-dark または shka-light フォルダを丸ごと置く。

`Ctrl+Shift+p` で color とでも入力して Preferences: color theme からテーマを設定する。

※ VSCODEマケプレでの公開は諸事情につきやらない。


Tips
---
プロジェクトごとに色を変えたい場合は、カラーテーマではなくプロジェクトの設定`./vscode/setting.json`に追記

`ctrl+,`からも行ける

```json
"workbench.colorCustomizations": {
    "titleBar.activeBackground": "#c6a6a6",
    "titleBar.activeForeground": "#333333",
    "activityBar.background": "#c6a6a6",
    "activityBar.foreground": "#333333"
  }
```


Licence
---

<!-- [MIT](https://github.com/shka86/foo/blob/master/LICENCE) -->

Author
---

[shka86](https://github.com/shka86)
