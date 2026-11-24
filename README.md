# Windows 98 (orca-window-theme)

Retro Windows 95/98 look for Orca: silver chrome, navy highlights, teal desktop sidebar,
a black DOS-prompt terminal and pixel-style file icons.

This is a data-only plugin (themes, terminal themes, icon themes): it runs no code and needs no approval.

## What is included

| Kind | Name | Notes |
|---|---|---|
| App theme | Windows 98 | Light slot |
| App theme | Windows 98 (Dark slot) | Same colors, so the look is identical in dark mode |
| Terminal theme | Windows 98 DOS Prompt | Dark slot, black background, Win98 16-color palette |
| Terminal theme | Windows 98 DOS Prompt (Light slot) | Same palette for the light slot |
| Icon theme | Windows 98 Icons | Pixel folder and file icons for common extensions |

## After installing: pick all three

Installing does not select everything for you. Open Orca settings and choose each one:

1. **App theme**: select `Windows 98` (and `Windows 98 (Dark slot)` for the dark slot).
2. **Terminal theme**: select `Windows 98 DOS Prompt` (and the Light slot variant).
3. **Icon theme**: select `Windows 98 Icons`.

The icons show in the file explorer, Source Control, tabs, Quick Open and search results.
The previous themes are not deleted; select them again in settings to go back.

## Limits

Orca themes only set colors. Bevelled 3D borders, title-bar gradients and the MS Sans Serif font
(as in 98.css) cannot be done by a theme.

## Develop

```sh
orca plugin validate .
orca plugin dev load .    # load this folder into Orca; edits reload automatically
```

Orca names the publisher after where the plugin is installed from: the GitHub or GitLab owner of
its repository, or `local` for a folder.
