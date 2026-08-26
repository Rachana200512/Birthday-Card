# 🎂 Birthday Book Card

This is an interactive, book-style digital birthday card that lives in a single HTML file. Pages turn with a real 3D flip animation, just like an actual book, and one page hides a letter inside a tappable envelope. There are no build tools or dependencies involved, so you can just open the file in a browser and it works.

The card has four pages: a cover with an animated candle-lit cake, a page dedicated to "the most amazing person" with a polaroid-style photo collage, a page with an envelope you tap open to reveal a full letter, and a final page with a grid of cherished photo memories.

To use it, open `birthday_card.html` in any modern browser. You can turn pages using the arrow buttons, by clicking the folded corner at the bottom of each page, by swiping on mobile, or with the left and right arrow keys on desktop. On the letter page, tap the envelope to open it and read the message, then tap the ✕ to close it again.

Everything is contained in the one HTML file, so customizing it just means editing that file directly. Text can be changed wherever it appears in the markup, photos can be swapped by changing the `src` on the relevant `img` tag, and the color palette is defined once near the top of the file so the whole card can be re-themed by changing a few values there. Adding another page means duplicating one of the existing page blocks, giving it a new id, and registering that id in the small script at the bottom of the file.

The card is built with plain HTML, CSS, and JavaScript, using CSS 3D transforms for the page-flip effect. It works in any modern browser on both desktop and mobile, and needs no internet connection after loading aside from the Google Fonts used for the decorative titles.

This is a personal project, free to copy, adapt, and reuse for your own cards.
