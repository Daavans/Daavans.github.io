# The games' website

What is published at https://daavans.github.io: a home page with a card for
each game, a page per game, and each game's privacy policy (the address its
Play Console listing asks for). The game repos are private, and GitHub
Pages is free only for public repos, so these files are copied into the
public repo `Daavans.github.io`. This folder is the whole site.

| Page | Address |
| --- | --- |
| Home: all games | https://daavans.github.io |
| ZAP! | https://daavans.github.io/zap.html |
| ZAP!'s privacy policy | https://daavans.github.io/privacy.html |
| Sports! | https://daavans.github.io/sports.html |
| Sports!'s privacy policy | https://daavans.github.io/privacy_sports.html |

Never move or rename a privacy policy once a Play listing points at it.

To publish or update: copy every file and the `images` folder (and the
hidden `.nojekyll`) into the root of `Daavans.github.io`, replacing what is
there, and commit.

## A new game

1. Its icon (256 x 256) and banner (the Play feature graphic, as a JPEG) go
   in `images/` as `<game>-icon.png` and `<game>-banner.jpg`.
2. Copy `sports.html` to `<game>.html` and change the title, colours, lines
   and links.
3. Add a card for it to `index.html` (copy one of the others).
4. Its privacy policy: `privacy_<game>.html`, like `privacy_sports.html`.

When a game handles data in a new way, update its policy (and the date)
before that version is released.

## app-ads.txt (once there is an AdMob account)

AdMob looks for it at the root of the developer website given in the Play
listing (https://daavans.github.io). One line, with the publisher id from
AdMob (Settings, Account information):

    google.com, pub-0000000000000000, DIRECT, f08c47fec0942fa0
