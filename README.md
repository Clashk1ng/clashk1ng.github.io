# clashk1ng.github.io

Root of the GitHub Pages user site. It exists for one reason: Google AdMob looks for
`app-ads.txt` at the root of the developer website listed on the App Store
(https://clashk1ng.github.io/app-ads.txt). The games' website itself lives in the
`games` repository and is served at https://clashk1ng.github.io/games/.

- `app-ads.txt` - authorises Google AdMob publisher pub-6612011927134164 to sell ads in the apps.
- `index.html` - forwards visitors to /games/.
- `.nojekyll` - serve files as they are.

Do not add a `games/` folder or a custom domain here: either would interfere with the games site.
