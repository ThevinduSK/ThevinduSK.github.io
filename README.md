# Thevindu-Kalubowila.github.io

Personal portfolio site for Thevindu Kalubowila, built as a static single-page website for GitHub Pages.

## Structure

- `index.html` contains the page content and section layout
- `styles.css` contains the visual design and responsive behavior
- `script.js` adds reveal animations, active navigation state, and the footer year
- `assets/favicon.svg` contains the site icon
- `assets/images/` contains profile photos, award photos, and other site images

## Run locally

You can preview the site locally with any simple static file server, for example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

Because your GitHub username is `ThevinduSK` and this repository is named
`Thevindu-Kalubowila.github.io`, this will publish as a project site at:

`https://thevindusk.github.io/Thevindu-Kalubowila.github.io/`

If you want the site to live at the root user-site URL instead:

`https://ThevinduSK.github.io/`

rename the repository to `ThevinduSK.github.io`.

After pushing the files:

1. Open the repository settings on GitHub.
2. Go to the Pages section.
3. Under "Build and deployment", set "Source" to "Deploy from a branch".
4. Select the `main` branch and the `/(root)` folder.
5. Click Save.
6. Wait for the deployment to finish, then open the site URL above.

## Images

- Put your profile photo in `assets/images/profile/`
- Put award photos in `assets/images/awards/`
- Put project or lab photos in `assets/images/projects/`
- The current hero image placeholder is `assets/images/profile/thevindu-portrait-placeholder.svg`
