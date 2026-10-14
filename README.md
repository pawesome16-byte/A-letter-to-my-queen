# 💌 A Letter for My Queen

An interactive love letter for long-distance relationships. Open the envelope, read the note, and send a little love across the miles.

A single HTML file with no frameworks, no build step and no dependencies.

## ✨ Features

- **Animated envelope** that wiggles until you open it. It reads "Hello My Queen" on the front.
- **Letter pop-up** with a typewriter effect: *"I miss you so much, my dear 💕"*
- **Floating hearts** that rise across the screen when the letter opens.
- **Kiss stamps.** Tap the open letter to leave 💋 marks.
- **Miss-o-meter.** A slider that answers "How much do I miss you?" and goes off the charts at 100%.
- **Open when…** notes for when she misses you, can't sleep, or needs a smile.
- **Catch my hearts.** A small tap game with falling hearts.
- **Light and dark themes** that follow the device, plus a manual toggle.
- **Mobile friendly**, with `prefers-reduced-motion` respected.

## 🚀 Usage

1. Download `love-letter-fun.html`.
2. Open it in any browser.
3. Send her the file, or host it (see below) and share the link.

### Host it free with GitHub Pages

1. Rename the file to `index.html` and push it to a repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. Your page will be live at `https://<your-username>.github.io/<repo-name>/`.

## 🎨 Make it yours

Everything lives in the one HTML file.

| What to change | Where to look |
| --- | --- |
| Name on the envelope | `<div class="to">Hello My Queen</div>` |
| Letter text and sign-off | the `<div class="letter">` block |
| "Open when…" messages | the `notes` array in the script |
| Miss-o-meter wording | the `meter()` function |
| Game win and lose messages | the `end()` function inside the "Catch the hearts" section |
| Colors | the CSS variables at the top of the `<style>` block (`--pink`, `--env`, `--bg1`, `--bg2`) |

Tip: the text is yours to write. Use inside jokes, nicknames, and memories only the two of you share.

## 🧰 Built with

- HTML, CSS and vanilla JavaScript
- [Google Fonts](https://fonts.google.com/): Caveat and DM Sans
- The Web Animations API for hearts, kisses and the falling-heart game

## 📁 Project structure

```
.
├── index.html   # the whole letter (love-letter-fun.html, renamed)
└── README.md
```

## 📄 License

MIT. Use it, remix it, and send it to someone you love.

---

Made with ❤️ for someone far away.
