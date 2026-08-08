# Lyric Glow

[![Installs](https://img.shields.io/endpoint?url=https://better-lyrics-themes-api.boidu.dev/api/badge/lyric-glow)](https://github.com/LMatiuxXcd/lyric-glow)
[![Rating](https://img.shields.io/endpoint?url=https://better-lyrics-themes-api.boidu.dev/api/badge/lyric-glow/rating)](https://github.com/LMatiuxXcd/lyric-glow)

An Aurora Cinematic Better Lyrics theme with typography-first lyrics, album-art ambience and a restrained Kawarp shader preset.

![Lyric Glow preview](images/1.png)

## Features

- Aurora cyan, violet and rose visual system
- Diffuse active-line Lyric Glow with readable forward hierarchy
- Native Better Lyrics rich-sync animations
- Voice-aware secondary, tertiary and shared-vocal layouts
- Translation and romanization styling
- Dynamic album-art ambience with a CSS fallback
- Optional Better Lyrics Shaders / Kawarp integration
- Glass navigation, dialogs, menus, queue and player controls
- Responsive desktop/fullscreen layout
- Reduced-motion and increased-contrast support

## Install

In Better Lyrics:

1. Open Themes.
2. Choose Install from URL.
3. Enter:

    https://github.com/MatiuxXcd/lyric-glow

After Marketplace approval, Lyric Glow can also be installed directly from the Better Lyrics Theme Store.

## Enable Aurora Shaders

The theme ships an official Better Lyrics Shaders preset in shader.json.

1. Install [Better Lyrics Shaders](https://github.com/better-lyrics/shaders).
2. Install Lyric Glow from the Better Lyrics Marketplace.
3. Open Lyric Glow's Marketplace detail and download its shader configuration, or download shader.json from this repository.
4. Import the JSON in the Better Lyrics Shaders popup.
5. Keep Audio Responsive enabled for the soft beat pulse.

Better Lyrics stores and exposes the shader configuration, but the separate Better Lyrics Shaders extension is what renders the Kawarp canvas. Without it, the theme keeps its blurred album-art fallback.

## Theme Metadata

- **ID:** `lyric-glow`
- **Version:** `1.4.0`
- **Minimum Better Lyrics:** `2.4.0.1`
- **Creator:** [MatiuxXcd](https://github.com/LMatiuxXcd)

## Development

The main stylesheet is style.css and the shader preset is shader.json.

Better Lyrics owns rich-sync word timing and motion through its animation engine. Lyric Glow deliberately avoids overriding word-level transforms so native swipe, wobble and glow behavior remains intact.

The Better Lyrics engine knobs block inside style.css is intentionally a CSS comment because Better Lyrics parses those values at runtime.

## Credits

Created by **LMatiuxXcd**.

Portions of the early selector/layout foundation were derived from Lucid (https://github.com/drago-oo/lucid-theme) by drago-oo (MIT). Lyric Glow was extensively redesigned around a different lyric stage, hierarchy and visual system.

Apple Music is a trademark of Apple Inc. This project is unofficial and is not affiliated with or endorsed by Apple.

## License

MIT. See LICENSE and NOTICE.md.
