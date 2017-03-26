# My Visual Studio 2017 Settings

## Disable Arrow Icons for C# Files

http://stackoverflow.com/a/42690759

Instructions for Visual Studio 2017:

- Close Visual Studio 2017
- Open Registry Editor (regedit), select HKEY_USERS
- File → Load Hive → %localappdata%\Microsoft\VisualStudio\15.0_<id>\privateregistry.bin where <id> is some hexadecimal gibberish. Set Key Name to the one you like e.g. vs2017
- Go to HKEY_USERS\vs2017\Software\Microsoft\VisualStudio\15.0_<id>
- Create new key UseSolutionNavigatorGraphProvider of DWORD (32-bit) type, value 0
- Select HKEY_USERS\vs2017, File → Unload Hive

## Disable Preview Tabs

![...](https://raw.githubusercontent.com/tobiasschulz/vs2017/master/disable%20preview%20tabs.png)

## Fonts

![...](https://raw.githubusercontent.com/tobiasschulz/vs2017/master/font%20environment.png)
![...](https://raw.githubusercontent.com/tobiasschulz/vs2017/master/font%20text%20editor.png)
