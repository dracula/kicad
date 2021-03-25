### [KiCad](https://kicad-pcb.org/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/kicad.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/kicad/archive/master.zip) option and unzip them.

**In KiCad 6 (2020)**

Drop the file `kicad/dracula.json` into the following color themes directory:

* Linux: `~/.config/kicad/VERSION/colors`
* Windows XP: “C:\Documents and Settings\username\Application Data” + kicad (= %APPDATA%\kicad) + "VERSION/colors":
* Windows Vista & later: “C:\Users\username\AppData\Roaming” + kicad (= %APPDATA%\kicad) + "VERSION/colors"
* OSX: `~/Library/Preferences/kicad/VERSION/colors`

**In KiCad 5**

Override the set of variables beginning with `Color` in the file below with the contents of `kicad/eeschema`

* Linux: `~/.config/kicad/eeschema`
* Windows XP: “C:\Documents and Settings\username\Application Data” + kicad (= %APPDATA%\kicad) + "eeschema":
* Windows Vista & later: “C:\Users\username\AppData\Roaming” + kicad (= %APPDATA%\kicad) + "eeschema"
* OSX: `~/Library/Preferences/kicad/eeschema`

#### Activating theme (KiCad 6 only)

1. Open eschema properties
2. Select _colors_ option screen
3. Select _Dracula_ and hit apply
