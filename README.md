# Darkula theme for Omarchy

A dark Omarchy theme: cyan accents, pink borders and off-white text on a near-black navy.

### Neovim
![Editor, btop and files](preview.png)

### Browser & music
![Browser, player and files](preview2.png)

## Install

```bash
omarchy theme install git@github.com:sebday/omarchy-darkula-theme.git
```

## 🎨 Palette

<table>
  <tr>
    <th>&nbsp;&nbsp;&nbsp;</th>
    <th>Labels</th>
    <th>Hex</th>
    <th>RGB</th>
    <th>HSL</th>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/accent.svg" width="12" /></td>
    <td>Accent</td>
    <td><code>#8be9fd</code></td>
    <td><code>rgb(139, 233, 253)</code></td>
    <td><code>hsl(190.53°, 96.61%, 76.86%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/highlight.svg" width="12" /></td>
    <td>Highlight</td>
    <td><code>#ff79c6</code></td>
    <td><code>rgb(255, 121, 198)</code></td>
    <td><code>hsl(325.52°, 100.00%, 73.73%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/foreground.svg" width="12" /></td>
    <td>Foreground</td>
    <td><code>#f8f8f2</code></td>
    <td><code>rgb(248, 248, 242)</code></td>
    <td><code>hsl(60.00°, 30.00%, 96.08%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/background.svg" width="12" /></td>
    <td>Background</td>
    <td><code>#0a0e19</code></td>
    <td><code>rgb(10, 14, 25)</code></td>
    <td><code>hsl(224.00°, 42.86%, 6.86%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/selection.svg" width="12" /></td>
    <td>Selection</td>
    <td><code>#44475a</code></td>
    <td><code>rgb(68, 71, 90)</code></td>
    <td><code>hsl(231.82°, 13.92%, 30.98%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/muted.svg" width="12" /></td>
    <td>Muted</td>
    <td><code>#6272a4</code></td>
    <td><code>rgb(98, 114, 164)</code></td>
    <td><code>hsl(225.45°, 26.61%, 51.37%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/red.svg" width="12" /></td>
    <td>Red</td>
    <td><code>#ff5555</code></td>
    <td><code>rgb(255, 85, 85)</code></td>
    <td><code>hsl(0.00°, 100.00%, 66.67%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/green.svg" width="12" /></td>
    <td>Green</td>
    <td><code>#50fa7b</code></td>
    <td><code>rgb(80, 250, 123)</code></td>
    <td><code>hsl(135.18°, 94.44%, 64.71%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/orange.svg" width="12" /></td>
    <td>Orange</td>
    <td><code>#ffb86c</code></td>
    <td><code>rgb(255, 184, 108)</code></td>
    <td><code>hsl(31.02°, 100.00%, 71.18%)</code></td>
  </tr>
  <tr>
    <td><img src="assets/palette/circles/purple.svg" width="12" /></td>
    <td>Purple</td>
    <td><code>#bd93f9</code></td>
    <td><code>rgb(189, 147, 249)</code></td>
    <td><code>hsl(264.71°, 89.47%, 77.65%)</code></td>
  </tr>
</table>

The active Hyprland border is a cyan-to-pink gradient
(`rgba(8be9fdee) rgba(ff79c6ee) 45deg`). File manager icons use `Yaru-blue`.

## Backgrounds

<p align="center">
  <img src="backgrounds/evo-x.webp" width="30%" alt="Evo X" />
  <img src="backgrounds/forest.webp" width="30%" alt="Forest" />
  <img src="backgrounds/nebula.webp" width="30%" alt="Nebula" />
</p>
<p align="center">
  <img src="backgrounds/space.webp" width="30%" alt="Space" />
  <img src="backgrounds/spacepyramid.webp" width="30%" alt="Space pyramid" />
  <img src="backgrounds/sea.webp" width="30%" alt="Sea" />
</p>

## Notes

`libadwaita-gtk.css` supplies `@define-color` overrides for GTK4/libadwaita apps such as Nautilus & file dialogs. Stock Omarchy does not deploy GTK4 palette CSS; this file is for a patched install that generates it from `colors.toml` and writes `~/.config/gtk-4.0/gtk.css` on theme switch.

