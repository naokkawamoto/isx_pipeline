# InsightScanX — Pipeline Storyboard (紙芝居)

Interactive click-through storyboard of the full InsightScanX flow:
Project setup → iPad scan → cloud integration → point-cloud cleaning → MEP conversion + LLM-as-judge → part confirmation → progress → IFC export.

**Live:** https://naokkawamoto.github.io/isx_pipeline/

Navigate with the ‹ › buttons, the arrow keys, or the dots.
Frame **S11 (MEP conversion)** is interactive:
- toggle layers (mesh / point cloud / MEP / base drawing)
- dummy MEP pipes & fittings colored by AI confidence (green=high / amber=mid / red=low)
- tap a point-cloud marker (dashed circle) for an AI recommendation
- press **「MEP変換を実行」** to grow the conversion

Single self-contained `index.html` — no build step.
