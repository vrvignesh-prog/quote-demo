# Quote of the Day demo

A single-page "Daily Motivation" app in `index.html`. It shows a random motivational quote and its author on a centered card over a purple gradient background.

## Features

- Shows a random quote when the page loads.
- The **New Quote** button picks another quote. It never repeats the one currently on screen.
- The **Copy** button copies the current quote to the clipboard.
- The **Share** button opens a new tab with a pre-filled tweet of the current quote.
- A toggle in the card's top-right corner switches between dark (the default) and light mode. The choice is saved in `localStorage` and restored on the next visit.
- A footer below the card links to this project's GitHub repository.
- Ships with eight quotes from Steve Jobs, Nelson Mandela, Sam Levenson, Theodore Roosevelt, Mark Twain, William James, Aristotle and Wayne Gretzky.
- Responsive layout: the card is up to 560px wide and shrinks to fit small screens. On screens 480px wide or less, the quote, author and buttons use larger text.
- Everything (HTML, CSS and JavaScript) is in one file, with no dependencies or build step.

## Usage

Open `index.html` in any modern browser.

## Customizing

To change the quotes, edit the `quotes` array in the `<script>` block of `index.html`. Each entry is a `[text, author]` pair:

```js
const quotes = [
  ["The only way to do great work is to love what you do.", "Steve Jobs"],
  // ...
];
```

To change the colors and fonts, edit the `<style>` block in the page's `<head>`.
