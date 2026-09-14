# Mountain Dew Code

### Code Red
<style>
.container {display:flex; flex-direction:column; gap:8px}
.color .i {height:20px; width:20px; border-radius:3px;}
.color {display:flex; gap:8px; font-size:large; align-items:center}
</style>

A dark, cyberpunk theme: backgrounds so dark they're almost black with a red
tint, soft desaturated red as the default text/UI color (easy on the eyes),
brighter red for keywords and accents, and blue/yellow/green used sparingly
to help syntax stand out. Code Red Mountain Dew, but a text editor.

<div class="container">
    <div class="color"><div class="i" style="background:#0a0407"></div>#0a0407 - editor background</div>
    <div class="color"><div class="i" style="background:#d1707c"></div>#d1707c - default text</div>
    <div class="color"><div class="i" style="background:#ff4d6d"></div>#ff4d6d - keywords / accents</div>
    <div class="color"><div class="i" style="background:#6b3a42"></div>#6b3a42 - comments</div>
    <div class="color"><div class="i" style="background:#ffb454"></div>#ffb454 - strings</div>
    <div class="color"><div class="i" style="background:#ffd166"></div>#ffd166 - types / classes</div>
    <div class="color"><div class="i" style="background:#6bcf7f"></div>#6bcf7f - numbers / constants</div>
    <div class="color"><div class="i" style="background:#5eb3f6"></div>#5eb3f6 - functions</div>
    <div class="color"><div class="i" style="background:#4dd0e1"></div>#4dd0e1 - regex / links</div>
</div>

## VS Code

Install this extension, then set the color theme to **Mountain Dew Code Red**
(`Ctrl+K Ctrl+T`). Theme source: [`themes/code-red.json`](themes/code-red.json).

## Zed

A matching Zed theme extension lives in [`zed/`](zed/). To try it locally:

1. Open Zed's extension panel and choose **Install Dev Extension**.
2. Point it at the `zed/` folder in this repo.
3. Select **Mountain Dew Code Red** from the theme picker (`Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`).

Zed's theme JSON schema differs from VS Code's, so the palette was ported by
hand to Zed's `style`/`syntax` keys ([`zed/themes/mountain-dew-code-red.json`](zed/themes/mountain-dew-code-red.json)).
If a future Zed release renames or adds theme keys, re-check against
[Zed's theme docs](https://zed.dev/docs/extensions/themes) and update accordingly.
