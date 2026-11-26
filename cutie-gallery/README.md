# r34 gallery

A clean, white photo + video gallery for GitHub Pages, branded **r34**. It reads supported media files from the `cutie/` folder in the public GitHub repository configured in `index.html`.

## Repository settings already filled in

- GitHub username: `Sl1wed`
- Repository name: `r34`
- Branch: `main`
- Media folder: `cutie`

If your repository has a different name, change `repo: "r34"` in the `GITHUB` settings near the bottom of `index.html`.

## Add your media

Put photos and videos in the `cutie/` folder.

- Photos: JPG, JPEG, PNG, GIF, WEBP, AVIF, BMP
- Videos: MP4, WEBM, MOV, M4V, OGV

The supplied logo image is saved as `assets/logo.png`.

## Publish with GitHub Pages

1. Upload all project files to the `r34` repository owned by `Sl1wed`.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose `main` and `/ (root)`, then Save.
5. Open the Pages URL GitHub provides.

The repository needs to be public for this version to fetch media through GitHub's unauthenticated Contents API. Do not put access tokens or passwords in the HTML file.

## Notes

- The gallery reads files directly inside `cutie/`, not nested folders.
- GitHub Pages is static hosting; add new files to the repository and refresh the page.
- GitHub API rate limits and folder response limits apply to very large collections.
