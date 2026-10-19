INDUS TRADER — GOOGLE SITES HOSTING PACKAGE

CONTENTS
index.html: HTML player, using Ruffle 0.4.1 from jsDelivr.
indus_valley.swf: your uploaded file, unchanged.
xml/ and swf/: configuration and all 38 assets listed in that configuration,
retrieved from the game's original BBC download location.

SETUP WITH GITHUB PAGES
1. Unzip this package.
2. Create a public GitHub repository named indus-trader.
3. Choose Add file > Upload files. Upload the CONTENTS of the extracted folder,
   including index.html, indus_valley.swf, and both folders. Keep the folder
   structure intact. Do not upload just the ZIP. Commit the files.
4. Open the repository's Settings > Pages.
5. Choose Deploy from a branch, branch main, folder / (root), and Save.
6. Wait for GitHub Pages to display your published URL. It normally resembles:
   https://YOUR-USERNAME.github.io/indus-trader/
7. Open that URL and test the game, including starting a new game.
8. In Google Sites choose Insert > Embed > By URL and paste your published URL.
   Alternatively, paste the code from google-sites-embed.txt in Embed code
   after replacing its placeholder URL. Resize the embed to approximately
   700 pixels high, then publish your Google Site.

IMPORTANT LIMITATIONS
This package has been checked for SWF file integrity and the presence of all
configuration-listed assets. Gameplay has NOT been verified in a browser.
Ruffle compatibility with this particular game's ActionScript 3 code is untested.
The main SWF also contains a reference to xml/game.xml. That file returns 404
at the BBC host; whether it is used in the normal game flow is unconfirmed.
If the player stalls or requests that file, more recovery work will be needed.
Ruffle's CDN must be accessible to visitors; school filtering can affect this.
Double-clicking index.html locally is not a reliable test; serve it over HTTP
or use your published GitHub Pages URL.

SOURCE LINKS
Original game asset base:
https://downloads.bbc.co.uk/schools/primaryhistory/games/indus_trader/
Ruffle setup:
https://ruffle.rs/downloads
https://github.com/ruffle-rs/ruffle/blob/master/web/packages/selfhosted/README.md
GitHub Pages setup:
https://docs.github.com/en/pages/quickstart
Google Sites embeds:
https://support.google.com/sites/answer/90569

The game and its assets retain their original ownership. This wrapper does not
grant a license to republish those assets.
