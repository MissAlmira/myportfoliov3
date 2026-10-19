# Almira R. Bogayan Portfolio

A responsive, single-page portfolio with a dedicated photography page, built for GitHub Pages using HTML, CSS, and vanilla JavaScript.

## Project files
- `index.html`: main portfolio
- `photography.html`: dedicated photo gallery
- `css/style.css`: styling and responsive layout
- `js/script.js`: navigation and interactive samples
- `assets/Almira-Bogayan-Resume.pdf`: resume download
- `assets/images/profile-photo.png`: profile image
- `assets/images/photography/photography.json`: photography manifest

## Add photography
Upload images to `assets/images/photography/`, then add each filename to `photography.json`, for example:
```json
{
  "photos": [
    {
      "src": "forest-trail.jpg",
      "alt": "A green forest trail",
      "caption": "A quiet trail"
    }
  ]
}
```
The Photography navigation link is hidden while the manifest is empty. Keep image filenames and manifest entries accurate.

## Publish on GitHub Pages
Upload the contents of the `almira-portfolio` folder to the repository root. Enable GitHub Pages from Settings > Pages and publish from the main branch root. Replace any placeholder social metadata with the actual public site URL if adding social preview URLs later.

## Notes
The case studies and AI response examples are fictional demonstrations, not confidential company work or official evaluation guidelines. Review resume wording and dates before publishing. The PUP logo loads from Wikimedia Commons and requires an internet connection.
