# How to upload:


Fork the repo

Create a file called `all/YourAppName/script.(file extension)` and put your app code there (varies per OS)
- .osl for OSL apps (originOS)
- .crl for CRL apps (Constellinux / Derivatives)

Create `icon.icn` in the same folder, and add your applications .icn file in there

Create `info.json` and fill out this json

## Screenshots
Put Screenshots into `all/YourAppName/screenshots`

Screenshots need to be 16:9

You can have a maximum of 5 screenshots

## Changelogs
Put Changlogs into `all/YourAppName/changelogs`

Changelogs should be .md

Find an example of changelogs in the [claw](https://github.com/RoturTW/apps/tree/main/all/claw) app

```json
{
  "title": "Your App Name",
  "description": "A description for your application",
  "author": "Your Rotur Username",
  "version": "If you update your app later, increment this value",
  "genre": "Pick the genre your app falls into",
  "game_modes": ["Single-player","Multiplayer"],
  "permissions": ["i'll fill these out for you based on your application code"],
  "supports": ["systems that your app supports"],
  "screenshots": ["the name of a screenshot file"],
  "changelogs": ["the name of a changelog file"]
}
```

Create a pull request for your app
