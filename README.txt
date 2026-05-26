LayerCanvas Studio v21

クラシカル枠画像をHTML埋め込みから外し、img/frames/classical01/ に分離しました。
GitHub Pagesでは index.html と img フォルダを同じ階層に配置してください。

枠素材を追加する場合は、img/frames/classical02/ のようにフォルダを増やし、index.html 内の CLASSICAL_FRAME_PRESETS に追記してください。
- classical03 = クラシカルC

Update v25: Classical frame X/Y base sliders were removed. Spacing now uses canvas-center-based symmetric X/Y offset sliders. Frame shadow Y default is 0.

Version 26: Fixed center spacing values over 1000px being treated as legacy data and visually resetting to 0.


Version 29: Updated the built-in manual.
- Added text gradient explanation.
- Added classical frame A/B/C explanation.
- Added canvas-center-based symmetric spacing explanation.
- Added note that each classical frame size is capped at that design's original image size.


Added hand material layer preset: gao
Files: img/hand-materials/gao/{line,base,shadow1,shadow2}.png

Version 41: Improved hand material downscaling quality.
- Added high-quality multi-step downsampling for hand material drawing.
- Prevents line art from becoming rough/jagged when hand materials are scaled down very small.
- Preview and PNG export use the same improved drawing path.


Version 62: Restored missing effect types from the attached reference file.
- Added only effect-related missing code and UI.
- Restored Duotone, Diffusion, Overlay Color, Noise / Film Grain, Halftone, and Scanlines / CRT.
- Glow was not re-added.
- JavaScript syntax check passed.

Version 63: Restored texture backgrounds while keeping missing effects.
- Rebased on the texture-background version so Check 01 / Dot Background / Border Background remain available.
- Re-added only missing effect types from the attached reference file.
- Kept Glow removed.
- Included img/background-textures/check01 assets in the ZIP.


Version 65:
- Based on v63 texture/effects restored file.
- Fixed only the effect type dropdown inside the effect layer card.
- The effect layer card dropdown now matches the Selected Effect Detail dropdown.
- Texture backgrounds, including Check 01 / Dot Background / Border Background, were left intact.
