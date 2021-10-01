# The Great-*er*  Discarder-*er* 
#### LordXerus Fork
```diff
- The Great Discarder
+ The Great-er Discarder-er
```

First attempt at contributing to open source... 

I'm going to make a pull request, then probably abandon this fork.

#### Background

I use The [Marvellous Suspender](https://github.com/gioxx/MarvellousSuspender)(Fork of The Great Suspender)
and I like it, so I don't really use nor care about Chrome's built-in discard feature.
In fact, it kinda annoys me because it discards my Spotify Web Player every time I pause it using my Fn keys.

Hopefully whitelisting it here in The Great-er Discard-er fork will work. 
I will turn off automatic discard because I already suspend my tabs.

##### Problem

I also like the discard tab on startup feature.
But it's hidden when automatic discard is set to `Never`.

Seems like an easy problem, so I'll take a crack at it with my nooby Javascript skills and make a pull request instead of an issue.
This repository is for that pull request and other potential contributions.

##### Solution
WIP




## The Great-er Discard-er readme

Since the "The Great Discarder" project has been dormant for years, and the semi-related "The Great Suspender" has hit some bumps in the road,
I thought I'd take a crack at publishing this fork.

"The Great-er Discarder-er" continues where "The Great Discarder" left off, and will (hopefully) add some functionality while keeping things simple.

If you have suggestions or problems using the extension, please [submit a bug or a feature request](https://github.com/rkodey/the-great-er-discarder-er/issues).

### Chrome Web Store

"The Great-er Discarder-er" is available on the [Chrome Web Store](https://chrome.google.com/webstore/detail/the-great-er-discarder-er/plpkmjcnhhnpkblimgenmdhghfgghdpp).



### Most of the original readme...

"The Great Discarder" started as a clone of another (former) open source chrome extension "The Great Suspender".
It was built to take advantage of Chromium's 'tab discarding' functionality which is essentially a native implementation of tab suspension.
This extension is more robust and performant, both in the resources consumed by the extension, and the memory savings of the tab suspension.
It is also compatible with chrome tab history syncing.

### Install as an extension from source

1. Download the **[latest release](https://github.com/rkodey/the-great-er-discarder-er/releases)** and unarchive to your preferred location (whichever suits you).
2. Using **Google Chrome** browser, navigate to chrome://extensions/ and enable "Developer mode" in the upper right corner.
3. Click on the <kbd>Load unpacked extension...</kbd> button.
4. Browse to the src directory of the downloaded, unarchived release and confirm.

### Build from github

Dependencies: openssl, nodejs / npm.

Clone the repository and run these commands:
```
npm install
npm run generate-key
npm run build
```

It should say:
```
Done, without errors.
```

The extension in crx format will be inside the build/crx/ directory. You can drag it into [extensions] (chrome://extensions) to install locally.

### License

This work is licensed under a GNU GENERAL PUBLIC LICENSE (v2)

### Shoutouts

This package uses the indexedDb wrapper [db.js] (https://github.com/aaronpowell/db.js) written by Aaron Powell.<br>
Thank you also to www.browserstack.com for providing free chrome testing tools.
