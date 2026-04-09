# [ CREATIVE_OVERRIDE ] - Terminal Prompt Generator 

A lightweight, zero-dependency web application designed to act as a "creative slot machine." Instead of gambling for coins, you spin for inspiration. 

This tool generates highly unique, randomized prompts by combining four distinct wheels: **[SUBJECT]**, **[LOCATION]**, **[ACTION]**, and **[STYLE]**. Built with a retro terminal/ASCII aesthetic, it's perfect for artists, writers, game masters, and creators looking to break through creative block.

---

## ⚡ Features

* **Massive Permutation Engine:** Contains hundreds of unique, non-repeating parameters across four categories, yielding hundreds of millions of possible creative combinations.
* **Retro Terminal UI:** A pure CSS/JS hacker-style interface featuring classic phosphor-green text, glowing CRT effects, and staggered spinning animations.
* **Single-File Architecture:** Zero external assets, no databases, and no frameworks. Everything lives cleanly inside one `index.html` file.
* **Universal "Copy" Function:** Includes a robust copy-to-clipboard button with built-in legacy fallbacks, ensuring it works even when embedded in restrictive iframes (like Miro or restrictive website builders).
* **Cache-Busting:** Hardcoded meta tags ensure that users always load the newest version of the app when deployed.

## 🔗 Live Demo

**[Click here to try the generator live!]**  https://andsni.github.io/creativeTerminal/

## How to Use

1. Click the **`EXECUTE SPIN //_`** lever.
2. Watch the terminal parameters cycle rapidly.
3. Once the sequence locks in, your generated prompt will appear in the output field at the bottom.
4. Click **`📋 COPY`** to instantly copy the comma-separated prompt to your clipboard.
5. Paste it into your sketchbook, writing app, or AI image generator.

## Tech Stack

* **HTML5:** Semantic structure.
* **CSS3:** Custom variables, flexbox layouts, and CSS text-shadows for the neon glow effect.
* **Vanilla JavaScript:** Core logic for the randomized arrays, staggered setTimeouts for the spinning animation, and clipboard API handling.

## Local Setup

Because this is a completely static, single-file application, installation is instant:

1. Clone or download this repository.
2. Double-click `index.html` to open it in any modern web browser.
3. No local server or build tools required.

## Customization

Adding your own prompts is incredibly easy. Open `index.html` in any text editor and scroll down to the `<script>` tag. You will find four arrays:

* `subjects = [...]`
* `locations = [...]`
* `actions = [...]`
* `styles = [...]`

Simply add your new words wrapped in quotes and separated by commas. The JavaScript engine automatically adapts to the new array sizes.

---
*Generated for maximum creative output.*
