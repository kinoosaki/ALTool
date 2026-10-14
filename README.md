# ALTool

**DISCLAIMER:** This is a hard fork of the original project, I claim nothing. I don't know Python and hence much of the changes are being done by AI, I am not telling you to use it and I'm not claiming that the work is mine, it's purely for personal use. **Use at your own risk.**

**Notice:** Program is compiled with pyinstaller so some anti-viruses may give false positives. For people who want to compile it themselves download the source files and run `Main.py`. There is a script that will install the necessary python modules in the source files and releases.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [License](#license)

## Features
This program is a utility for interacting with the Anilist API. It provides several features to manage your Anilist account:

### Get Users Not Following Back
This feature retrieves a list of users that you are following but who are not following you back. 
- Option to exclude certain users from this list.
- Option to unfollow these users.

### Get Users You Are Not Following Back
This feature retrieves a list of users who are following you, but you are not following back. 
- Option to follow these users.

### Follow Random Users From Global Activity Feed
This feature allows you to follow a specified number of random users from the global activity feed.

## Download
- The executable can be found in the releases section as well as GitHub Actions for the latest commits as that's what I'm using to compile an exe for this program. 
- The `altool.exe` file requires no prerequisites. Just run it.
- For those compiling it themselves:
  - Download the source files
  - Download the required python packages with the included `InstallPackages.py` script or yourself
  - Run `Main.py`

## License
Distributed under the GNU General Public License v3.0 License. See `LICENSE` for more information.