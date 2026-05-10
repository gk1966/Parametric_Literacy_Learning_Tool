# Parametric Literacy Tool: Enhanced Educational Edition

The Parametric Literacy Tool is a browser-based educational software package for teaching digital image processing through the concept of **parametric literacy**: the ability to understand visual outcomes as explicit configurations of adjustable parameters.

The tool combines an HTML5 Canvas image-processing interface, real-time RGB/luminance histograms, diagnostic clipping visualization, structured AI prompt generation, JSON metadata export, and an optional Google Gemini AI Tutor for parameter-aware feedback.

## Live Demo

https://gk1966.github.io/Parametric_Literacy_Learning_Tool/

Alternative direct application link:

https://gk1966.github.io/Parametric_Literacy_Learning_Tool/enhanced_parametric_app.html

## Author

Georgios Korakakis  
Assistant Professor  
Department of Graphic Design and Visual Communication  
School of Applied Arts and Culture  
University of West Attica (UniWA), Greece

## Repository

https://github.com/gk1966/Parametric_Literacy_Learning_Tool

## Archived Release

Current/new release DOI:

```text
Forthcoming after Zenodo archival of this release.
```

Previous archived version:

https://doi.org/10.5281/zenodo.19451351

For publication or formal citation, please cite the Zenodo DOI corresponding to the exact version used.

## Academic Motivation

Digital image editing education often sits between two difficult extremes: professional software with complex interface conventions, and generative AI tools that hide technical decisions behind natural-language prompts. This software bridges that gap by exposing image adjustments as named, measurable parameters and by visualizing their effects on pixel data.

The tool is designed for design education, digital imaging courses, and AI literacy activities where learners need to connect visual intention, numerical adjustment, histogram behavior, and AI-readable instructions.

An earlier educational version of this work was presented at Cumulus 2026. This enhanced software release focuses on implementation, reproducibility, public availability, and reuse potential for software-oriented publication.

## Key Features

- **Client-side image processing:** core image editing runs locally in the browser using HTML5 Canvas and JavaScript.
- **Pixel-level parameter manipulation:** tonal and color operations are applied through Canvas/ImageData workflows.
- **Real-time statistical visualization:** RGB and luminance histograms help learners understand tonal distribution.
- **Diagnostic clipping overlay:** near-white and near-black regions are highlighted to reveal potential data loss.
- **Configuration-driven controls:** UI controls are generated from parameter definitions, supporting extensibility.
- **Structured prompt generation:** active parameters can be translated into AI-readable editing instructions.
- **Optional AI Tutor:** Gemini API integration can analyze the current canvas and active parameters when explicitly invoked by the user.
- **JSON metadata export:** parameter states can be exported as reproducible records without image pixels or API keys.

## Privacy and API Notes

The core editing workflow runs locally in the user's browser. No image is uploaded during ordinary slider-based editing, histogram rendering, clipping visualization, image export, or JSON metadata export.

The optional AI Tutor sends a compressed canvas snapshot and the active parameter context to the Gemini API only when the user clicks **Analyze My Image**. The Gemini API key is stored locally in the browser's `localStorage`. Users should consult the official Google Gemini API pricing, rate-limit, and data-use documentation before using the AI features.

JSON metadata exports do not include image pixels or API keys.

## Getting Started

1. Open the live demo or download the repository.
2. Open `index.html` or `enhanced_parametric_app.html` in a modern web browser.
3. Upload an image.
4. Adjust the parameters and observe the canvas, histogram, and clipping diagnostics.
5. Use **Export JSON** to save a reproducible parameter record.
6. Optional: enter a Gemini API key in the AI Tutor tab to enable parameter-aware AI feedback.

## Requirements

- Modern web browser with HTML5 Canvas support
- No server installation required for the core application
- Optional: Google Gemini API key for AI Tutor features

## Suggested Repository Structure

```text
index.html
enhanced_parametric_app.html
README.md
LICENSE
CITATION.cff
IMAGE_ATTRIBUTION.md
Parametric_Literacy_Technical_Manual.html
parametric_manual_assets/

## Documentation

The technical and educational manual is provided in:

```text
Parametric_Literacy_Technical_Manual.html
```

The sample lioness photograph visible in the screenshots is third-party material and is credited separately in:

```text
IMAGE_ATTRIBUTION.md
```

## Suggested Citation

Please cite the archived Zenodo release corresponding to the version used:

```text
[Author Name]. (2026). Parametric Literacy Tool: Enhanced Educational Edition (v2.0.0). Zenodo. [new Zenodo DOI]
```

Previous archived version:

```text
https://doi.org/10.5281/zenodo.19451351
```

## License

This software is released under the MIT License. See `LICENSE` for details.

