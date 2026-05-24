# Parametric Literacy Tool: Enhanced Educational Edition

Version: **3.0.0**

The Parametric Literacy Tool is a browser-based educational software package for teaching digital image processing through **parametric literacy**: the ability to understand visual outcomes as explicit configurations of adjustable parameters.

The tool combines an HTML5 Canvas image-processing interface, real-time RGB/luminance histograms, clipping diagnostics, histogram metrics, before/after split view, point zoom inspection, structured AI prompt generation, JSON metadata export/import, and an optional AI Tutor for parameter-aware feedback.

## Live Demo

GitHub Pages:

https://gk1966.github.io/Parametric_Literacy_Learning_Tool/

Direct application:

https://gk1966.github.io/Parametric_Literacy_Learning_Tool/enhanced_parametric_app.html

## Repository

https://github.com/gk1966/Parametric_Literacy_Learning_Tool

## Author

Georgios Korakakis  
Assistant Professor  
Department of Graphic Design and Visual Communication  
School of Applied Arts and Culture  
University of West Attica (UniWA), Greece

## Archived Releases

Current v3 release DOI:10.5281/zenodo.20366944

```text
TO_BE_ASSIGNED_BY_ZENODO
```

Previous archived releases:

```text
v2.0.0: https://doi.org/10.5281/zenodo.20112617
v1.0.0: https://doi.org/10.5281/zenodo.19451351
```

For publication or formal citation, please cite the Zenodo DOI corresponding to the exact version used.

## Key Features

- Client-side image processing using HTML5 Canvas and JavaScript.
- Built-in AI-generated landscape demo image for quick testing.
- Pixel-level parameter manipulation through Canvas/ImageData workflows.
- Real-time RGB/luminance histograms and simple quantitative metrics.
- Diagnostic clipping overlay and clipping percentage indicators.
- Before/after split view for comparing original and edited images.
- Point zoom inspection for examining local detail, noise, blur, sharpening, and clipping.
- Parameter search, presets, undo/redo, and reset-by-group controls.
- JSON metadata export/import for reproducible parameter states.
- Structured prompt generation from active parameter states.
- Optional AI Tutor requiring a user-provided API key and explicit privacy confirmation.
- Scientific tooltip explanations with DOI-based further reading.

## Privacy and API Notes

The core editing workflow runs locally in the user's browser. No image is uploaded during ordinary slider-based editing, histogram rendering, clipping visualization, image export, JSON metadata export, or JSON import.

The optional AI Tutor sends a compressed canvas snapshot and active parameter context to an external AI API only when the user explicitly invokes the AI analysis function. API keys are stored locally in the browser.

JSON metadata exports do not include image pixels or API keys.

## Getting Started

1. Open `index.html`.
2. Launch `enhanced_parametric_app.html`.
3. Load the built-in demo image or upload a non-sensitive image.
4. Adjust parameters and inspect the live preview, histogram, metrics, clipping warnings, and prompt output.
5. Use **Export JSON** to save a reproducible parameter record.
6. Optional: enter a Gemini API key in the AI Tutor tab for parameter-aware AI feedback.

## Documentation

Technical and educational manual:

```text
Parametric_Literacy_Technical_Manual.html
```

Image attribution:

```text
IMAGE_ATTRIBUTION.md
```

Tooltip bibliography:

```text
TOOLTIP_REFERENCES.md
```

## Suggested Citation

Before Zenodo assigns the v3 DOI:

```text
Korakakis, G. (2026). Parametric Literacy Tool: Enhanced Educational Edition (v3.0.0). Zenodo. DOI to be assigned.
```

After creating the Zenodo release, replace `TO_BE_ASSIGNED_BY_ZENODO` with the DOI assigned to v3.

## License

This software is released under the MIT License. See `LICENSE` for details.
