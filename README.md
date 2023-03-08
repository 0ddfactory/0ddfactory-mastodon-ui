## Mastodon, but it's Twitter

Blasphemy! Yes, I know, but I just had to do this. I wanted to see if it's possible to get <a href="https://github.com/mastodon/mastodon">Mastodon</a> default user interface to look exactly like Twitter.

**Please note** that this is a personal experiment _for fun_, but as far as I know colors can't be trademarked. No logos or other elements have been used without permission.

See the [original post](https://mementomori.social/@rolle/109984108360395822).

_Mastodon colors:_

![mementomori social_notifications (4)](https://user-images.githubusercontent.com/1534150/223775421-e1fa0b00-f794-4599-b2fe-60f4190d6044.png)


_Twitter colors:_

![mementomori social_notifications (3)](https://user-images.githubusercontent.com/1534150/223725571-b7f8ef41-212c-476c-9006-4e7cb2ddc062.png)

### Goals

- **CSS only.** This means some pseudos and modern CSS hacks. The intent is to have the code base as simple and extendable as possible. The styles should be easily modifiable. Ready-made code works when placed in _Custom CSS_ box in {yourinstance.social/mementomori.social/admin/settings/appearance}
- **Single-column layout only.** This experiment is not meant for advanced layout.

### Roadmap

- [x] Desktop views
- [x] Mobile views
- [ ] Star to like heart with animation

## Installation

1. Copy the contents of style.css
2. Install it as CSS to your assets or use Custom CSS in the Appearance settings in your instance

## Contributing / testing

1. Install [live-css-editor](https://github.com/webextensions/live-css-editor) (or any other extension that allows you to inject CSS into web pages) or use [Unite for macOS](https://www.bzgapps.com/unite)
2. Get style.css from this repo
3. Open extension and paste the CSS into the editor
4. Click 📌-icon so the styles will be remembered for the domain or if you want just to use it as needed, activate styles from the extension's popup
