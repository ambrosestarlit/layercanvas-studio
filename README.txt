LayerCanvas Studio v45

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

Version 42: Added a duotone effect.
- Added a duotone effect layer that remaps luminance to a dark color and a light color.
- Shadow/highlight colors can be chosen independently.
- Effect strength can be adjusted.

Version 45: Fixed and added effect layer types.
- Restored v42 duotone support as the base.
- Added Diffusion to the effect layer type selector.
- Added Overlay Color to the effect layer type selector.
- Added Glow to the effect layer type selector.
- Added Noise / Film Grain to the effect layer type selector.
- Added Halftone to the effect layer type selector.
- Added Scanlines / CRT to the effect layer type selector.
- Added each effect's adjustment controls and render processing.
- Available in Japanese / English / Korean UI.


Version 46: Halftone update and Glow removal.
- Removed Glow from the effect type selector.
- Added Blend Mode to Halftone.
- Added a "Apply Uniformly" checkbox to Halftone.
- When Apply Uniformly is enabled, evenly sized dots are drawn across the full canvas regardless of the image content.

Version 47: Added built-in background illustration presets.
- Added Hand-drawn background illustration selector to each background layer.
- Added AI-finished background illustration selector to each background layer.
- Hand-drawn note: この素材は管理人の手書きのみで作成されています。
- AI-finished note: この素材はベース作画：管理人/仕上げAIで作成されています。
- Added background rotation slider.
- Background layers now support move / scale / rotation.
- Added bundled assets under img/backgrounds/handwritten/ and img/backgrounds/ai-finish/.
