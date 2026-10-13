# Tevican — independent games by NetiKOD

Public website for the **Tevican** independent game-development brand. **NetiKOD** is the developer name used to publish games on Google Play. Tevican is a creative brand, not a separately registered company.

- Developer website: https://tevican.github.io/
- Privacy policy index: https://tevican.github.io/policies/
- Vampire Test policy: https://tevican.github.io/policies/vampire-test/
- Authorized ad sellers: https://tevican.github.io/app-ads.txt
- Contact: tevican.com@gmail.com

## Publishing

GitHub Pages serves the default branch `main` from the repository root. The static site does not require a build tool.

- `index.html` — homepage, with the game portfolio and NetiKOD/Tevican attribution.
- `policies/index.html` — policy links.
- `policies/<game>/index.html` — publicly readable HTML versions of each game's policy.
- `app-ads.txt` — AdMob sellers authorization for the publisher account; keep in the site root.

## Policy maintenance

The source privacy-policy texts live in [tevican/Policies](https://github.com/tevican/Policies). This website currently hosts static HTML copies so users and Google Play can open each policy at a stable, public URL.

**When editing a policy in the Policies repository, also update its corresponding HTML page here.** Existing data handling statements were preserved during the initial migration and still require review against the installed SDKs, actual application behavior, and Google Play Data safety answers. Avoid adding inaccurate legal or technical guarantees.

## Google Play and AdMob setup

1. Confirm the developer website `https://tevican.github.io/` is set in each app's Google Play Store listing.
2. Confirm `https://tevican.github.io/app-ads.txt` displays the AdMob seller record as plain text.
3. In Google Play Console, set each game's publicly accessible Privacy Policy URL to its corresponding `/policies/<game>/` page; publish listing updates.
4. Make sure the same policy is accessible in the app where required.
5. Check AdMob's app-ads.txt status after Google Play has published the site URL. Discovery and verification may take time.

Do not present Tevican as a registered legal entity unless that changes in the future.
