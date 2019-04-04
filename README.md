# FMODGame

## Working with ONLY the GAME, not FMOD
Just checkout the project

_Note:_

You should not need to change the FMOD settings. If you do, you will need to add a line to your `.git/exclude` file so that your changes don't get committed. That line is: 
```
**/FMODStudioSettings.*
```

## Working with ONLY FMOD, not the GAME
Audio Repo : https://github.com/webthingee/FMODAudio

## Working with FMOD, and the GAME
Audio Repo : https://github.com/webthingee/FMODAudio

Structure w/ both repos should look like this example:
```
drwxr-xr-x  8 user  staff  256 Apr  1 15:55 FMODAudio
drwxr-xr-x  8 user  staff  256 Apr  1 15:55 FMODGame
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
