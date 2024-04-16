# How to install Spicetify

1. Download Spicetify - custom spotify client. Follow this [step-by-step guide](https://spicetify.app/docs/advanced-usage/installation/)
or
2. Download Spicetify -> open your Windows Powershell.
And run the following commands:
```sh
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex
```
3. Important Spicetify Powershell commands:
```sh
spicetify update //updates the spicetify client to the newest version
spicetify apply //applies the client
spicetify restart //restarts the client
spicetify restore //restores Spotify to the original state
spicetify refresh //reloads the client (CSS, plugins,etc.)
spicetify backup (apply) //restores backup
```
4. You can finally install any additional plugins in the Marketplace section (I recommend: Beautiful Lyrics, Adblock).

# How to install the custom apps
## Eternal Jukebox

1. Run `spicetify config-dir` to open the spicetify folder.
2. Go to the `CustomApps` folder.
3. Create a `eternal-jukebox` folder.
4. Download the custom app files as a zip from [here](https://github.com/Pithaya/spicetify-apps-dist/archive/refs/heads/dist/eternal-jukebox.zip).
5. Extract the zip and put the files inside the folder you created in step 3.

Then, run the following commands:

```sh
spicetify config custom_apps eternal-jukebox
spicetify apply
```

# How to uninstall the custom apps

## Eternal Jukebox

1. Run `spicetify config-dir` to open the spicetify folder
2. Go to the `CustomApps` folder
3. Delete the `eternal-jukebox` folder

Then, run the following commands:

```sh
spicetify config custom_apps eternal-jukebox-
spicetify apply
```
