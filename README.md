# Clip Chain

Build the longest paperclip chain you can. Every length is real: a clip adds 33 mm, uses 10.7 cm of 1 mm steel wire and weighs about 0.66 g.

Play it in the browser. No server, no accounts, no subscriptions. It is one self-contained `index.html`.

## How it plays

1. **By hand.** Click the scissors to cut wire, then drag the glowing ring round each peg. Three bends make one clip, and it links onto the chain.
2. **Hire help.** Three hires take over one bend each, until the bench runs itself.
3. **Machines.** 16 tiers, from a bending machine to galactic works. They need power and floor space, and they jam, so you repair them on the factory floor or hire a crew.
4. **Wire.** Buy spools, watch the market price, set a restocking rule, and expand the store.
5. **Orders and overtime.** Take customer orders against the clock, or run flat out for a while.
6. **Milestones.** 36 real-world comparisons, from a pencil to the Andromeda galaxy. Each one pays out and lets you bend a coloured clip to hang on the wall of frames.
7. **The gallery.** From a family car's length, visitors pay to see the chain. Set the ticket price. Visitors sometimes snag the chain, and you bend replacement links at the bench to reopen it.
8. **Legacy.** After a billion clips you can build a new factory. The wall and a permanent production bonus carry over.
9. **Statistics.** Chain weight and what it compares to, growth speed against real things up to light, wire used, time to the next milestone, power and energy, earnings, jams, history.

Progress saves in your browser's local storage and only advances while the page is open. Saves are per site address, so a new host starts fresh.

## Controls

- Mouse or touch: scissors, ring and shop buttons.
- `Space` or `C`: cut a new length at the bench.

## Run it locally

Open `index.html` in a browser. Fonts load from Google Fonts and fall back to system fonts if offline.

## Host it on GitHub Pages

1. Put `index.html`, `README.md` and `.nojekyll` in the root of a repository.
2. Repository Settings, Pages, Source: deploy from branch `main`, folder `/ (root)`.
3. The game appears at `https://<user>.github.io/<repo>/`.

## Notes

- Game logic and UI live in two inline `<script>` blocks in `index.html`. The first, `CORE`, is pure logic with no DOM.
- Save key: `clipchain.save.v1`. Older saves are upgraded automatically on load.
