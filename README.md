> [!WARNING]
> This project has moved to
> <https://github.com/skeletony007/ansible-roles/tree/bac65cad05663557257262baee6aede0ff2e67cc/firefox>
> and is no longer maintained here.

### Firefox CLI profile / policy manager

**`push`**, **`pull`**, **`create`** 

Ideal for migrating Firefox profiles between machines.

### moz://a Firefox

> https://support.mozilla.org/en-US/kb/profiles-where-firefox-stores-user-data

> https://mozilla.github.io/policy-templates

### Firefox profile 🦊

> See [https://support.mozilla.org/en-US/kb/profiles-where-firefox-stores-user-data](https://support.mozilla.org/en-US/kb/profiles-where-firefox-stores-user-data)

#### Bookmarks 📚

- `places.sqlite` This file contains all your Firefox bookmarks and lists of all the files you've downloaded and websites you’ve visited.
- `favicons.sqlite` This file contains all of the favicons for your Firefox bookmarks.

#### Site-specific preferences ☕️

- `permissions.sqlite` Stores many of your Firefox permissions. (🍪 Cookie Exceptions etc.)

#### Cookies 🍪

- `cookies.sqlite` ❗️ *VERY* **PRIVATE**

#### User preferences ⚙️

- `user-overrides.js` The [arkenfox
  user.js](https://github.com/arkenfox/user.js) updater gets the current live
  arkenfox and appends your overrides, and then it compares that to the current
  user.js in your profile. If it's different, it replaces it.

#### Extension keybinds

- `extension-settings.json`
