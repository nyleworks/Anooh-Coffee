# Anooh Coffee website

The website for Anooh Coffee, KM3 Kundasang–Ranau road, 89308 Ranau, Sabah. *Love from the mountain.*

It is a single static page: plain HTML, CSS and JavaScript with no build step. Fonts load from Google Fonts.

## What's in this folder

| Path | What it is |
| --- | --- |
| `index.html` | The whole site (Home, About Us, Menu, Discover Us, Shop, Personal Data Notice) |
| `images/hero.jpg` | Hero photo on the home page |
| `media/souvenirs.mp4`, `media/souvenirs-poster.jpg` | Keychain preview video (Shop › Souvenirs) |
| `media/keychains/` | The 8 Sabahan dress keychain photos |
| `media/artisan-corner.mp4`, `media/artisan-corner-poster.jpg` | Busker video (Discover Us › Artisan Corner) |
| `media/prihatin/` | Anooh Prihatin photos (Kongsi Rezeki Jumaat, Latihan Industri di Jepun) |
| `media/book/` | Drink and pastry photos on the home page menu book |
| `media/promos/` | Promotion posters (Mix & Match, Milky Fruit, Soda Fruit Day) |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

Keep the folders and file names exactly as they are: `index.html` links to them by these paths.

## Put it on GitHub Pages

1. On GitHub, click **New repository**. Name it (for example `anooh-coffee`), set it to **Public**, and create it.
2. On the new repository page, click **uploading an existing file**.
3. Drag in everything from this folder: `index.html`, `README.md`, and the `images` and `media` folders. (`.nojekyll` is a hidden file; on a Mac press Cmd+Shift+. in Finder to show it. The site works without it.)
4. Click **Commit changes**.
5. Go to **Settings › Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, and click **Save**.
6. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`. The link also shows at the top of the Pages settings.

To use your own domain (for example `anoohcoffee.com`), add it under **Settings › Pages › Custom domain** and follow GitHub's DNS instructions.

## Updating the site

Edit `index.html` (or replace a photo with a new file of the same name) and upload it to the repository again. GitHub Pages republishes automatically.

## Still to fill in

Text in square brackets is a placeholder waiting for real details:

- Shop items in Anooh Blend and Local Products, and their prices
- Photos for the remaining grey tiles
- The weekend line-up in the "Who's playing this weekend" pop-up (`[Time]`, `[Performer name]`)
- The bracketed details in the Personal Data Notice
