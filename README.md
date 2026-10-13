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
- `policies/vampire-test/index.html` — the published privacy policy for Vampire Test. Discontinued games are not listed on the site.
- `app-ads.txt` — AdMob sellers authorization for the publisher account; keep in the site root.

## Policy maintenance

The source privacy-policy texts live in [tevican/Policies](https://github.com/tevican/Policies). This website publishes only the privacy policies for games currently supported on the public site; source texts of discontinued games remain archived in the Policies repository.

**When editing the Vampire Test policy in the Policies repository, also update its HTML page here.** Existing data handling statements were preserved during the initial migration and still require review against the installed SDKs, actual application behavior, and Google Play Data safety answers. Avoid adding inaccurate legal or technical guarantees.

## Google Play and AdMob setup

1. Confirm the developer website `https://tevican.github.io/` is set in the Vampire Test Google Play Store listing.
2. Confirm `https://tevican.github.io/app-ads.txt` displays the AdMob seller record as plain text.
3. In Google Play Console, set Vampire Test's Privacy Policy URL to `https://tevican.github.io/policies/vampire-test/` and publish the listing update.
4. Make sure the same policy is accessible in the app where required.
5. Check AdMob's app-ads.txt status after Google Play has published the site URL. Discovery and verification may take time.

Do not present Tevican as a registered legal entity unless that changes in the future.
