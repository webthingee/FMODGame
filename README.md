# FMODGame

## Working with ONLY the GAME, not FMOD
* You will need to adjust/create the path to the `FMODBanks` folder, located in the root (e.g. a sibling to `Assets` folder. 
* FMOD > EDIT SETTINGS
* Browse and find your local path to `FMODBanks`
* This will likely require the banks to be refreshed FMOD > REFRESH BANKS

## Working with ONLY FMOD, not the GAME
Audio Repo : https://github.com/webthingee/FMODAudio

## Working with FMOD, and the GAME
Audio Repo : https://github.com/webthingee/FMODAudio

Structure w/ both repos should look like this example:
```
drwxr-xr-x  8 user  staff  256 Apr  1 15:55 FMODAudio
drwxr-xr-x  8 user  staff  256 Apr  1 15:55 FMODGame
```

## Configure Git NOT to track FMODStudioSettings
If you need to change the FMOD settings, you will need to add a line to your `.git/exclude` file so that your changes don't get committed. That line is: 
```
**/FMODStudioSettings.*
```


Open Unity Game
Assets will load
You may get errors on first load, hit play or ignore them until Unity is pointing to the FMOD project file.

Top Menu
FMOD > EDIT SETTINGD

Settings Window
Project Button Selected (dark)
Studio Project Path (Browse...)
- point to the project file

There is a scene in the FMOD_UI for testing.
You may need ot assing Music and a Test sound effect. Both of which need to be 2D at the moment.
