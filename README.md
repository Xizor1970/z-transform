# The Z-Transform — Interactive Knowledge Base

[![Pages](https://img.shields.io/badge/Live_Site-GitHub_Pages-blue)](https://xizor1970.github.io/z-transform/)
[![Pages](https://img.shields.io/badge/Pages-10-gold)]()
[![Animations](https://img.shields.io/badge/Animations-5-green)]()
[![Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen)]()

**[View the live site →](https://xizor1970.github.io/z-transform/)**

A visual, interactive educational website covering the Z-transform from first principles to practical filter design. Built with pure HTML, CSS, and JavaScript — no build step, no frameworks, no dependencies.

## Sections

| # | Page | Description |
|---|------|-------------|
| 01 | [Definition](https://xizor1970.github.io/z-transform/definition.html) | Forward and inverse Z-transform, bilateral vs unilateral, historical context |
| 02 | [Properties](https://xizor1970.github.io/z-transform/properties.html) | Linearity, time shifting, convolution theorem, value theorems |
| 03 | [Common Pairs](https://xizor1970.github.io/z-transform/common-pairs.html) | The essential lookup table — impulse, step, exponential, sinusoidal |
| 04 | [Region of Convergence](https://xizor1970.github.io/z-transform/roc.html) | Why the ROC matters, annular regions, causality, and ambiguity |
| 05 | [Inverse Z-Transform](https://xizor1970.github.io/z-transform/inverse.html) | Partial fractions, power series, contour integration |
| 06 | [Transfer Functions](https://xizor1970.github.io/z-transform/transfer-functions.html) | Poles, zeros, frequency response, system characterisation |
| 07 | [Stability](https://xizor1970.github.io/z-transform/stability.html) | BIBO stability, unit circle criterion, Jury test |
| 08 | [Digital Filters](https://xizor1970.github.io/z-transform/filters.html) | FIR/IIR design, windowing, bilinear transform, implementation |
| 09 | [Applications](https://xizor1970.github.io/z-transform/applications.html) | Audio, control, comms, biomedical, radar, finance |
| 10 | [Interactive Animations](https://xizor1970.github.io/z-transform/animations.html) | Draggable pole-zero plots, frequency response, impulse response, s→z mapping, convolution |

## Interactive Animations

Five canvas-based visualizations you can interact with:

1. **Pole-Zero Explorer** — Drag poles (×) and zeros (○) around the z-plane. Watch the gain heatmap update in real time. See stability change as poles cross the unit circle.
2. **Frequency Response** — Adjust pole radius and angle to see how resonance peaks sharpen and move.
3. **Impulse Response Viewer** — See how pole location determines decay rate and oscillation frequency. Toggle between impulse and step response.
4. **S-Plane to Z-Plane Mapping** — Visualize how z = e^(sT) maps continuous-time poles to discrete-time poles. Animate the mapping.
5. **Convolution in Action** — Watch input signals pass through a moving-average filter sample by sample.

## Design

- Dark space-themed aesthetic with gold accents
- Every concept has an analogy making it tangible
- Speculation and open questions on every page
- Responsive — works on mobile and desktop
- Opens directly in any browser (no server needed)

## License

Educational content. Use freely.
