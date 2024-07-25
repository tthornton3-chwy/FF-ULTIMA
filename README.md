# <p align="center"> FF ULTIMA... </p>

###### <p align="center">. . . Experimental branch, to reference experimental features, pre-implementations, and extras.</p>

## API & Size

https://api.github.com/repos/soulhotel/FF-ULTIMA
```
cloc output (07.25.2024 - still decreasing)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
CSS                             39           1364           1054           6261
Markdown                        10            129              0            380
SVG                             13              1              3            228
JavaScript                       1              8             13             42
JSON                             1              0              0              1
-------------------------------------------------------------------------------
SUM:                            64           1502           1070           6912
-------------------------------------------------------------------------------

```

## Experimental Features
###### <ins>File, task and outcome</ins>

```
function-safeguard.css
```

- Safeguards for when multiple tab size preferences are enabled at once.
- Code miniaturization.
- A display message to notify the User included.

https://github.com/soulhotel/FF-ULTIMA/assets/155501797/70c10229-5224-4b71-94f4-54f304c8b8b5

```
function-tabs-always-ontop.css
```

- ~~Add user preference `ultima.tabs.always.ontop`.~~
- Add user preference `ultima.tabs.vertical`.
- Allow the user to keep default tab layout.
- Tabs on top instead of vertical.
- Disabling vertical tabs configuration.
- Almost there.

![2024-07-20_00-24](https://github.com/user-attachments/assets/5eec1e15-0dc7-4880-80cf-98938e521c06)

```
theme-context-menu.css
```

- Add user preference `ultima.contextmenu-declutter`.
- Allow the user to toggle/remove excess context menu items.

```
function-sidebery-autohide.css
```

Contribution: https://github.com/soulhotel/FF-ULTIMA/pull/88
- autohide/show Sidebery
- But other Sidebar's (bookmarks, history, sideview extensions) remain static (no autohide)
- enabled via `ultima.sidebery.autohide`.

⚠️ Currently the sidebar is drawn on top of the tabs panel when both are visible and on the left side of the browser. Issue resolved with `safeguard 1/2` & `safeguard 2/2`. More testing needed, but stable.

[343008543-c6140b4c-7331-4c15-be0a-41af08037d5d.webm](https://github.com/soulhotel/FF-ULTIMA/assets/155501797/b6412401-afe3-469b-8674-0dbd92ce6708)

![2024-06-30_18-30](https://github.com/soulhotel/FF-ULTIMA/assets/155501797/c035adb6-8487-4a17-9982-b9574475bd12)

