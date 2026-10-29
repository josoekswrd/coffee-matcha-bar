[README (1).md](https://github.com/user-attachments/files/34137261/README.1.md)
# Coffee & Matcha Bar

An interactive barista simulator. Click ingredients to fill a glass or a 1-liter bottle, and the app recognizes your drink or hints at what to fix. Includes 23 coffee and matcha recipes with auto-mix, plus a guide to beans, roast levels, brew methods, and matcha basics.

**Live demo:** https://your-project.vercel.app <!-- replace with your Vercel link -->

## Features

- **Mix by clicking.** Add espresso, milk, foam, ice, palm sugar, matcha and more, and watch the layers stack up in the glass.
- **Drink recognition.** The app matches your mix against known recipes. If nothing matches, it names the closest drink and tells you what to add, remove, or reorder.
- **Two sizes.** Switch between a 360 ml glass and a 1-liter bottle. In bottle mode every measure triples, for batch drinks you can share.
- **Auto-mix.** Each recipe card has a button that pours the ingredients in the right order.
- **Barista notes.** Short guides on coffee beans, Indonesian origins, roast levels, brew methods, matcha, and common terms.
- **Light and dark mode.** Follows your device setting.
- **Works on phones.** The layout adapts to small screens.

## Recipes

| Coffee | Matcha |
| --- | --- |
| Espresso, Doppio | Usucha, Koicha |
| Americano, Long Black | Matcha Latte |
| Macchiato, Cortado, Flat White | Iced Matcha Latte |
| Caffè Latte, Cappuccino, Caffè Mocha | Palm Sugar Iced Matcha |
| Espresso Con Panna | Dirty Matcha |
| Palm Sugar Iced Coffee (es kopi susu gula aren) | Matcha Affogato |
| Iced Latte, Iced Americano | |
| Affogato, Kopi Tubruk | |

Small-serving drinks such as espresso, affogato, usucha and koicha are hidden in 1-liter mode.

## Tech

A single `index.html` file with plain HTML, CSS and JavaScript. No framework, no build step, no dependencies. Fonts load from Google Fonts.

## Run locally

Open `index.html` in any browser. That's it.

Or serve it locally:

```bash
npx serve .
```

## Deploy to Vercel

1. Push this repository to GitHub.
2. On [vercel.com](https://vercel.com), choose **Add New → Project** and import the repository.
3. Set **Framework Preset** to **Other** and click **Deploy**.

Every new commit to the main branch redeploys the site automatically.

## Notes

Measures and figures are general guidelines, rounded to 30 ml steps so the mixes are easy to try. Every café has its own version of each recipe.

This is a personal, non-commercial learning project.
