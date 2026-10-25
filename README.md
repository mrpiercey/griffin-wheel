# Should I Vote for Griffin VanMeter on November 3?

A rigged decision wheel in Griffin for Lex blue and white. The TV types out a question like "Should I vote for Griffin VanMeter on November 3?", you pull the lever, and a giant Price-Is-Right-style drum rolls past you and stops on YES. Every panel on the drum says YES, with Griffin's face on both sides of the word, so it cannot land anywhere else. A pop-up then sends you to [griffinforlex.org](https://www.griffinforlex.org).

Based on the [Eagle Chase 5K Wheel-O-Registration](https://github.com/mrpiercey/eaglechase-wheel).

Open `index.html` in any browser. No build step, no dependencies. Works on phones too, where the lever becomes a big SPIN THE WHEEL button under the drum.

Ten questions rotate in random order. Press **Space** to pull the lever. Click anywhere off the TV pop-up (or press Escape) to load the next question and spin again.

## Files

- `index.html` is the whole app.
- `griffin.png` is Griffin's headshot from griffinforlex.org with the background removed.
- `logo.png` is the Griffin for Lex logo from griffinforlex.org.

## Embed it

```html
<iframe src="https://mrpiercey.github.io/griffin-wheel/" width="960" height="540"
        style="border:0;max-width:100%" title="Should I Vote for Griffin VanMeter?"></iframe>
```

## Publishing

`.github/workflows/pages.yml` deploys the folder to GitHub Pages on every push to `main`, the same as the Eagle Chase wheel.
