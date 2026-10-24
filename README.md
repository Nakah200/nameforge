# NameForge

A free, responsive username generator built with **HTML, CSS, and vanilla JavaScript**. Generate gaming, aesthetic, developer, and random usernames directly in your browser.

## Features

- **Four styles:** Gaming, Aesthetic, Developer, and Random
- **Custom prefix:** Add a prefix to generated usernames
- **Length control:** Choose a maximum username length
- **Number options:** Generate mixed names, names with numbers, or names without numbers
- **Copy tools:** Copy one username or copy the full results list
- **Favourites:** Save and remove favourite names; they persist in your browser using `localStorage`
- **Responsive design:** Works on desktop and mobile screens
- **No backend:** No account, API key, database, or build tools required

## Live demo with GitHub Pages

1. Create a public GitHub repository named `nameforge-generator`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)` folder, then save.
6. After deployment, your site should be available at:

   `https://YOUR-USERNAME.github.io/nameforge-generator/`

Replace `YOUR-USERNAME` with your GitHub username. GitHub Pages may take a few minutes to publish the first deployment.

## Run locally

Download or clone this repository, then open `index.html` in a browser. A local development server is optional.

```bash
git clone https://github.com/YOUR-USERNAME/nameforge-generator.git
cd nameforge-generator
```

Then open `index.html`.

## Project structure

```text
nameforge-generator/
├── index.html
└── README.md
```

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser `localStorage` for favourites

## Limitations

- Names are generated from built-in word lists and simple combinations.
- NameForge does **not** verify username availability on Discord, YouTube, GitHub, or other platforms.
- Favourites are saved in the current browser only; they do not sync across devices.

## Ideas for future improvements

- Add more word packs and naming styles
- Add a dark/light theme toggle
- Export generated names as a `.txt` file
- Add shareable result cards
- Add automated tests for name length and duplicate handling

## Contributing

Ideas and improvements are welcome. Fork the repository, create a branch, and submit a pull request.

## License

This project is available under the MIT License. Add a `LICENSE` file containing the standard MIT license text before distributing it as an MIT-licensed project.

---

**NameForge** — Forge your next identity.
