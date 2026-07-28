# BerryYield™

**This is a joke.** There is no company, no platform, no funding round, no SOC 2. There is one
HTML file and a genuine desire to stop throwing away raspberries.

BerryYield™ is a fake B2B SaaS landing page for a fake startup that "converts distressed fruit
inventory into shelf-presentable preserves." It has an enterprise pricing table (every tier is
free), a Solutions-by-persona page, a login form that authenticates against nothing, and a button
labeled **Make It Pretentious** that generates unbearable tasting notes about your jam.

The bit is that it commits: the navy-and-mint palette, the mono-spaced eyebrow text, the
"proprietary yield engine," the ticker of made-up metrics. It reads like a Series B company until
you actually read it.

## The one part that isn't a joke

The jam math is real. Enter what's actually wilting in your fridge — strawberries, blueberries,
raspberries, blackberries, in grams, cups, or pints — and the page computes:

- **Sugar** at 70% of total fruit weight
- **Pectin**, weighted per berry (strawberries need the most, blackberries the least — they bring
  their own)
- **Lemon juice**, weighted by how acidic each berry already is, then rounded to measures a human
  can actually execute with a spoon (`¾ tsp`, `1 ½ tbsp`) instead of `2.7314 tsp`
- A six-step method including the frozen-plate set test, which is the only reliable way to know
  when jam is done

Mix any combination of the four berries and it re-weights everything and renames the output
accordingly (two berries gets you a "&" jam, four gets you a "Four-Berry Reserve").

If you follow it, you get jam. That was the actual goal. The fake company is just the wrapper.

## Running it

It's one file. Open `index.html` in any browser and it works — no build step, no dependencies, no
server, no `npm install`. The only network request is to Google Fonts.

Nothing you type is sent anywhere, because there is nowhere to send it. There is no backend, no
database, and no account. The login page says as much, at length.

## License

MIT. Take it, fork it, make jam.
