# Tevican developer website

A small static website for Tevican games, hosted with GitHub Pages.

- Homepage: https://tevican.github.io/
- AdMob authorized sellers file: https://tevican.github.io/app-ads.txt

## Enable the site (one-time setup)

1. In this repository, open **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose **main**, folder **/ (root)**, then **Save**.
4. Wait for deployment and open both URLs above. The `app-ads.txt` URL should show one plain-text Google AdMob seller record.
5. In the Google Play Console listing for **Vampire Test**, enter `https://tevican.github.io/` as the developer website and publish the change.
6. After Google Play has updated, check **AdMob → Apps → app-ads.txt** for the verification result. Discovery can take time.

## Site files

- `index.html` — public developer homepage, including Vampire Test and Sea Dominion.
- `app-ads.txt` — AdMob authorized-seller declaration. Keep this file at the site root; use the exact record provided by AdMob.

Future apps that use the same publisher account can also use the same website and file, provided the website is listed in each app's store listing.
