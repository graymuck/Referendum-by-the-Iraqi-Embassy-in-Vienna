# Iraqi Consular Services Survey in Vienna

An Arabic, right-to-left survey prototype for gathering feedback about visits to the Iraqi consulate in Vienna. The form asks about the visit date, the service requested, the outcome, and the visitor's rating. It also includes an optional comments field.

> **Status** — This project is still in development. You can download and preview it in your browser.

## Download and try it

1. [Download the ZIP](https://github.com/graymuck/Referendum-by-the-Iraqi-Embassy-in-Vienna/archive/refs/heads/main.zip).
2. Extract the archive and open `index.html` in your browser.
3. Use sample details to try the form. Submitting opens a draft in your default email app with a placeholder recipient. Leave the draft unsent when testing.

## How it works

The survey is a single HTML file with embedded CSS and JavaScript. Open it directly in a browser. The page loads Arabic typefaces from Google Fonts when available.

JavaScript checks the required fields and formats the responses into an email draft. A configured email app is required to preview the draft. The page has no backend or database.
