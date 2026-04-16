# Language Translator

A language translation web app that works **entirely in the browser** — no API, no internet, no cost.

## How It Works

Uses a **built-in JavaScript dictionary** of 300+ common English words and phrases, each translated into 9 languages. Translation uses English as a pivot language, so any supported language pair works (e.g. Spanish → Japanese).

## Supported Languages

English, Spanish, French, German, Italian, Portuguese, Hindi, Arabic, Japanese, Chinese

## Features

- Translate words and phrases between 10 languages
- 300+ built-in translations covering greetings, numbers, food, travel, colors, and more
- Clickable phrase cards for instant common translations
- Swap source/target languages in one click
- Press Enter to translate
- Translation history (last 10 saved in localStorage)
- Copy to clipboard & download as `.txt`
- Works fully offline — no internet required

## How to Use

1. Clone or download the repo
2. Open `index.html` in any browser
3. Type a word or phrase and click **Translate** (or press Enter)

## Deploy to GitHub Pages

1. Push to GitHub
2. Go to **Settings → Pages → Source: main branch**
3. Share your live link!

## Project Structure

```
language-translator/
├── index.html
└── README.md
```

## Note

Since this uses a built-in dictionary, it works best with common words and phrases. For full sentence translation, an online service would be needed.

## License

MIT
