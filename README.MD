# ASCENT — Type to Climb

A browser-based typing-speed game: type the word above the stairs to climb higher. Miss a letter or run out of time, and you fall. Chain words without missing to build combos — big streaks earn bonus hearts, free revives, and rare skins.

🔗 **Live demo:** [ascent-navy-one.vercel.app](https://ascent-navy-one.vercel.app)

## Why I built it

I wanted to build a game that turns typing practice into something genuinely competitive and replayable, rather than a static drill — with real progression (levels, currency, cosmetics) and a leaderboard to make speed and accuracy something players actually chase.

## Features

- **Free Mode** — competitive, leaderboard-ranked runs. Ranked by steps climbed, with ties broken by steps per second.
- **Learn Mode** — levels unlock one at a time, grouped into worlds that increase in difficulty. Stars are awarded based on hearts remaining at the end of a level; run out of hearts and pay coins to revive.
- **Currency & Shop** — earn coins 🪙 and gems 💎 to unlock characters, stair themes, and cosmetic skins.
- **Gift codes** — redeem codes for bonus skins and rewards.
- **Accounts & leaderboard** — sign in with Google, opt in/out of appearing on the public leaderboard, and compare best runs. English and French runs are ranked separately since typing speed isn't comparable across languages.
- **Accessibility / customization options** — pace ghost marker showing your best run's pace in real time, adjustable typing language (EN/FR), and optional translation hints shown alongside each word.
- **Keyboard-first design** — the game detects touchscreen-only devices and prompts users to switch to a physical keyboard, since Free Mode leaderboard runs need a fair, consistent input method.

## Tech stack

- HTML, CSS, JavaScript (single-page app)
- Firebase (Authentication for Google sign-in, Firestore for leaderboard and account data)
- Deployed on Vercel

## Running locally

```bash
git clone https://github.com/omarbenayed05-maker/ascent.git
cd ascent
# open index.html directly in a browser, or serve it locally:
npx serve .
```

## Roadmap / what's next

- [ ] Additional worlds and level packs
- [ ] More languages beyond EN/FR
- [ ] Expanded cosmetic shop items

## License

*(Add a license if you want others to know how they can use/reuse this code — MIT is a common permissive choice for portfolio projects.)*
