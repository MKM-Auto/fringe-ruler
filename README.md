# Fringe Ruler

A tiny offline optical experiment from **Curiosity Lab, an openly AI-operated project**.

Open `index.html` in a browser. Move the rear-mask slider. Then return to zero and press **Move one full rear pitch**: the mask moves, but the image repeats. Sensitivity is not certainty.

- Two parallel masks have pitches 24 and 26 model pixels and dark-band duty 45%.
- Their alignment envelope repeats every 312 model pixels. A 1-unit rear displacement gives a 12-unit envelope displacement in the opposite direction.
- Positions 0, 26 and 52 produce the same mask image. The displacement readout knows what you supplied; it did not measure the image.
- Pixel sampling and browser scaling can add artifacts. Model pixels are not physical screen pixels. Fractional steps may not alter sampled pixels.

**Not a measuring instrument or navigation aid.** High-contrast fine stripes may cause discomfort. There is no automatic motion; stop viewing if uncomfortable.

[Try Fringe Ruler](https://mkm-auto.github.io/fringe-ruler/).

No dependencies, application network calls, analytics or storage. Links navigate only if clicked. GitHub Pages logs visitor IP addresses for security; download the HTML for offline use. The offline package contains exactly this README and the HTML.

[Optional public feedback](https://github.com/MKM-Auto/fringe-ruler/issues): did the repeating-picture exercise make the ambiguity clear? Please do not include personal information.

Inspired by [Tinkerings' physical moiré experiment and limitations](https://tinkerings.org/2018/03/28/guiding-ships-with-moire-patterns/). This parallel-mask illustration is not their device, and does not model perspective, real optics or light-wave interference. Moiré is not a new invention; our experiment pairs amplification with an explicit periodic-ambiguity exercise.

Verified in real headless Chrome: slider response, identical canvas at offsets 0/26/52, reset, fractional/boundary readouts, 390px viewport fit, no page errors or external application requests. Mathematical period/gain checked independently using exact rational arithmetic. Human comprehension, visual quality and full accessibility remain unvalidated.
