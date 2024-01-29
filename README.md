**wiki.gg Redirect** is a browser extension that automatically redirects you from wikis that are forked/abandoned from Fandom to [wiki.gg](https://wiki.gg/). It will also adjust Google's search results to try and populate the wiki instead of Fandom's SEO.

The extension is available on these browsers:
- [Google Chrome](https://chrome.google.com/webstore/detail/redirect-to-wikigg/cngoemokfjekjkmajenlaokhnmmiinca)
  - Opera users may also use this link. For search filtering to work, you will have to go to your browser's extensions panel and tick the "Allow access to search page results" checkbox next to wiki.gg Redirect.
- [Firefox](https://addons.mozilla.org/en-US/firefox/addon/redirect-to-wiki-gg/)
- [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/redirect-to-wikigg/pagmnhcicfingbflafkgemhdaadpojoo)
  - Update verification can be slow for Edge, and this version may be lagging slightly behind Chrome and Firefox.
  - Listing in the Edge Add-ons Portal has changed in mid-November 2023 due to a publisher change. To receive updates, switch to the listing linked above.
- Opera GX
  - Download the [Open in Google Chrome](https://addons.opera.com/en/extensions/details/open-in-google-chrome/) extension then head to to the Chrome Store to download the [wiki.gg Redirect](https://chrome.google.com/webstore/detail/redirect-to-wikigg/cngoemokfjekjkmajenlaokhnmmiinca).

**Only wiki.gg wikis will be added to this extension.** Independent or nearly-independent wikis are out of scope, because a separate **[Indie Wiki Buddy](https://github.com/KevinPayravi/indie-wiki-buddy)** extension is already available for Chrome and Firefox that you can use alongside **wiki.gg Redirect**.

## Permission justifications
* Persistent storage (`storage`): used for saving and loading user preferences.
* Navigation activity (`webNavigation`): used to react to navigation events resulting in visits to former wikis. This enables performing the redirection functionality.
* Site data access to fandom.com, gamepedia.com: used to redirect visits to former wikis (through the use of the limited `tabs` API). This enables performing the redirection functionality.
* Running scripts on google.com, duckduckgo.com, and their regional sites: used to rewrite search results.
* Running scripts on fandom.com: used to display notice banners about wiki forks, if enabled in settings.

------

The code was originally based on [proEndreeper's RSWikiRedirector](https://github.com/proEndreeper/RSWikiRedirector), and is licenced under the MIT licence.
