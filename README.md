# Moss & Moon Terrarium Hospital

An interactive FAQ chatbot for a fictional business that cares for terrariums.

[Open the live demo](https://sampeluso.github.io/moss-and-moon-chatbot/)

## How it works

Google Apps Script reads an editable Google Sheet on every question. An OpenAI model selects the matching FAQ row, and the chatbot displays the answer from that row. Sheet edits appear on the next question without republishing.

The API key is stored in Apps Script’s server settings.

## Project files

- [`apps-script/Code.gs`](apps-script/Code.gs) handles live Sheet lookups and OpenAI requests.
- [`apps-script/Index.html`](apps-script/Index.html) is the interactive chatbot.
- [`index.html`](index.html) is the GitHub Pages landing page.
