# The games' website

What is published at https://daavans.github.io: a page for ZAP!, its privacy
policy (the address the Play Console asks for), and later `app-ads.txt` for
AdMob. This game repo is private, and GitHub Pages is free only for public
repos, so these files are copied into the public repo `Daavans.github.io`.

To publish or update: copy every file in this folder (including the hidden
`.nojekyll`) into the root of `Daavans.github.io` and commit. The pages are
then at https://daavans.github.io and https://daavans.github.io/privacy.html.

Edit the privacy policy here, then copy it over again. When the game handles
data in a new way, update the policy (and its date) before that version is
released.

## app-ads.txt (once there is an AdMob account)

AdMob looks for it at the root of the developer website given in the Play
listing (https://daavans.github.io). One line, with the publisher id from
AdMob (Settings, Account information):

    google.com, pub-0000000000000000, DIRECT, f08c47fec0942fa0
