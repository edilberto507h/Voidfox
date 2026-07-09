![Badge](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2Fyokoffing%2FBetterfox&label=&icon=github&color=%23198754&message=&style=flat&tz=US%2FEastern)![GitHub Maintained](https://img.shields.io/badge/maintained-yes-green)![GitHub last commit](https://img.shields.io/github/last-commit/yokoffing/betterfox)![GitHub issues](https://img.shields.io/github/issues/yokoffing/betterfox)![GitHub closed issues](https://img.shields.io/github/issues-closed/yokoffing/betterfox)[![shields.io Stars](https://img.shields.io/github/stars/yokoffing/betterfox)](https://github.com/yokoffing/betterfox/stargazers)

:warning: Do not trust sites that claim to be Betterfox. This page is the only official source.

# Betterfox
[about:config](https://support.mozilla.org/en-US/kb/about-config-editor-firefox) tweaks to enhance [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/).

## Made for everyday browsing
Make Firefox more private and secure — without using third-party code.

Betterfox is an opinionated preference list inspired by the [law of diminishing returns](https://miro.medium.com/v2/resize:fit:1206/1*lcOcxriV_II_lZuXQYLoXg.jpeg) and the [minimum effective dose](https://medium.com/the-mission/less-is-more-the-minimum-effective-dose-e6d56625931e).

## Required reading
0) Create a [backup profile](https://github.com/yokoffing/Betterfox/wiki/Backup).
1) Download the user.js file [here](https://raw.githubusercontent.com/yokoffing/Betterfox/main/user.js) (Right click > `Save Link As…`).
2) Review both [Common Overrides](https://github.com/yokoffing/Betterfox/wiki/Common-Overrides) and [Optional Hardening](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening) to make any necessary changes.
3) Open Firefox. In the URL bar, type `about:profiles` and press **Enter**.
4) For the profile you want to use, click **Open Folder** in the **Root Directory** section.
5) Move the `user.js` file into the folder.

*After restarting Firefox:*
1) Get an **ad blocker** like [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) with Betterfox [recommended filters](https://github.com/yokoffing/filterlists#guidelines).
2) Enable **DNS-level protection** with your chosen [provider](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening#secure-dns) to further protect against security threats, ads, and trackers.

## Simple goals
1) **Minimalism:** get what isn't needed out of the way
2) **Efficiency:** unleash Firefox's ability to be fast and performant
3) **Privacy:** protect your data without causing site breakage

### Guides
* [FMHY Browser Tools: Privacy Tweaks](https://www.reddit.com/r/FREEMEDIAHECKYEAH/wiki/storage/#wiki_privacy_based_browsers)
* [Firefox-UI-Fix](https://github.com/black7375/Firefox-UI-Fix/wiki/Tips#privacy)
* [Narsil/desktop_user.js](https://git.nixnet.services/Narsil/desktop_user.js#thanks)
* [pyllyukko/user.js](https://github.com/pyllyukko/user.js) [comparator](https://jm42.github.io/compare-user.js/)

## Credit
* Betterfox mirrors the ongoing work provided by [arkenfox](https://github.com/arkenfox/user.js). Additionally, this repository includes content reproduced or adapted from other sources. Credit for overlapping material goes to the original authors.
* Appreciation goes to the [Firefox](https://www.mozilla.org/en-US/firefox/new/) team and developers working on [Bugzilla](https://bugzilla.mozilla.org/home), fighting for the open web.
* Thanks to [Denperidge](https://github.com/Denperidge) for adding [`install.py`](https://github.com/yokoffing/Betterfox/blob/main/install.py) for advanced users in v.131.
* A special thanks to [Alex Kontos](https://github.com/MrAlex94) of [Waterfox](https://github.com/WaterfoxCo/Waterfox) for his collaboration in v.116.
* Many thanks to the 2021 [Ghostery](https://github.com/ghostery) team for testing Betterfox at scale in its early days.
