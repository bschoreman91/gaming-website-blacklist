# gaming-website-blacklist

## Goal

The search results for information and tutorials on games have been flooded by low quality websites in recent years.

These websites
- Use SEO to manipulate search results to appear before high quality, organized, and centralized websites like [BG3 Wiki](https://bg3.wiki) or [Serebii](https://www.serebii.net/)
- Use AI or other filler content to increase article surface area to serve additional advertisements
- Publish articles as fast as possible after release to become the first result but neglect to update incorrect or outdated information
- Have intrusive advertisement, cookie, subscription, or other privacy related concerns

The first few search results for any gaming question you have should always be helpful, high quality content. 

## Installation instructions

1. Install uBlacklist for [Chrome](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublacklist/)
2. Download [uBlacklist.txt](https://github.com/bschoreman91/gaming-website-blacklist/blob/main/uBlacklist.txt)
3. Go to uBlacklist options in [Chrome](chrome-extension://pncfbmialoiaghdehhbnbhkkgmjanfhe/pages/options.html) or by clicking the extension and clicking "options" in Firefox
4. Click Import and select the uBlacklist.txt you downloaded earlier

## Blacklist Criteria

Websites that feature pages which match one or more of the following criteria have been added to the blacklist:
- Articles with useless filler content
- Low quality or vastly inaccurate
- Excessive advertisements
- Advertisements that circumvent uBlock origin and PiHole
- Websites with popups demanding that the user disable ad blockers
- Stream embed websites
- Listicles

## Games checked against

- Baldur's Gate 3
- Stardew Valley
- Vampire Survivors

## How to contribute

Create a pull request with your updated list. In the commit message please provide the general criteria for why you added these websites. No need to go into detail - a quick one liner for the whole PR is good.

If you would like to remove a website from the list, the commit message must provide info that the website no longer matches blacklist criteria as well as what game the website is a critical resource for.
