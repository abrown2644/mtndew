# Mountain Dew Code

<style>
.container {display:flex; flex-direction:column; gap:8px; margin-bottom: 16px;}
.color .i {height:20px; width:20px; border-radius:3px;}
.color {display:flex; gap:8px; font-size:large; align-items:center}
</style>

Two dark, cyberpunk themes: backgrounds so dark they're almost black, a soft
desaturated color as the default text/UI color (easy on the eyes), a
brighter version of that color for keywords and accents, and a handful of
other colors used sparingly to help syntax stand out. Mountain Dew flavors,
but for a text editor.

### Code Red

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

### Code Blue

Same structure, mirrored into blue: a blue base with coral/red used as the
contrast accent (instead of Code Red's blue accent), plus the same gold,
yellow, and green pops for strings, types, and numbers.

<div class="container">
    <div class="color"><div class="i" style="background:#05080f"></div>#05080f - editor background</div>
    <div class="color"><div class="i" style="background:#7fb8e0"></div>#7fb8e0 - default text</div>
    <div class="color"><div class="i" style="background:#2d9cff"></div>#2d9cff - keywords / accents</div>
    <div class="color"><div class="i" style="background:#3d6182"></div>#3d6182 - comments</div>
    <div class="color"><div class="i" style="background:#ffb454"></div>#ffb454 - strings</div>
    <div class="color"><div class="i" style="background:#ffd166"></div>#ffd166 - types / classes</div>
    <div class="color"><div class="i" style="background:#6bcf7f"></div>#6bcf7f - numbers / constants</div>
    <div class="color"><div class="i" style="background:#ff5f6d"></div>#ff5f6d - functions</div>
    <div class="color"><div class="i" style="background:#4dd0e1"></div>#4dd0e1 - regex / links</div>
</div>

## VS Code

Install this extension, then set the color theme (`Ctrl+K Ctrl+T`) to
**Mountain Dew Code Red** or **Mountain Dew Code Blue**. Theme sources:
[`themes/code-red.json`](themes/code-red.json),
[`themes/code-blue.json`](themes/code-blue.json).

## Zed

Matching Zed theme extensions live in [`zed/`](zed/). To try them locally:

1. Open Zed's extension panel and choose **Install Dev Extension**.
2. Point it at the `zed/` folder in this repo.
3. Select **Mountain Dew Code Red** or **Mountain Dew Code Blue** from the
   theme picker (`Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`).

Zed's theme JSON schema differs from VS Code's, so the palettes were ported
by hand to Zed's `style`/`syntax` keys
([`zed/themes/mountain-dew-code-red.json`](zed/themes/mountain-dew-code-red.json),
[`zed/themes/mountain-dew-code-blue.json`](zed/themes/mountain-dew-code-blue.json)).
If a future Zed release renames or adds theme keys, re-check against
[Zed's theme docs](https://zed.dev/docs/extensions/themes) and update accordingly.
