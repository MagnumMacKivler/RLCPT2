<p align="center">
  <a href="https://titusstudios.net/">
    <img
      alt="rlc-logo"
      title="RLC Logo - www.titusstudios.net/"
      src="https://titusstudios.net/data/static/images/rlc-logo-new-2.png"
      width="600"
    />
  </a>
</p>

<br>



RLC Platinum 2.0 (RLC PT2 or simply PT2 for short) is a highly realistic simulation chip for diesel-electric locomotives in Garry's Mod.

RLC PT 2.0 is now publicly available for use. The version found on here should be stable, however, there is always the chance that some bugs may remain in the code. Future updates are certain, and you will need to update your locomotives as time goes by. That means updating E2s, re-wiring dupes.

Thankfully, certain features within RLC PT 2.0 make it easier for users to update their locomotives, and the new include-based config system should streamline the process. Gone are the days of copy/pasting blocks of code from one PT chip into the next!

| NOTE | RLC PT 2.0 is **not** MU-compatible with RLC PT (1). |
| :--- | :--- |

[Check out the wiki for locomotive data sheets, general info, and PT2-specific tips!](https://github.com/MagnumMacKivler/RLCPT2/wiki)

# Table of Contents

* [Support](#support)
* [Release Types](#release-types)
  * [Download](#download)
    * [Current, Beta, LTS and Misc Releases](#current-beta-lts-and-misc-releases)
* [Installation](#installation)
  * [Install Using SVN](#install-using-svn)
  * [Install Using Releases](#install-using-releases)
* [Required Addons](#required-addons)
* [In-Game Setup and Usage](#in-game-setup-and-usage)
* [Current Project Team Members](#current-project-team-members)


## Support
#### Need help setting up a locomotive?

Read the RLCPT2 User Manual [Here](/ptgamma/RLC_PT2_Operator_Manual.txt)
<br>
Or Check out [The Wiki](https://github.com/MagnumMacKivler/RLCPT2/wiki) for [tutorials](https://github.com/MagnumMacKivler/RLCPT2/wiki/Configuring-Locomotives-in-RLC-PT2), [data sheets](https://github.com/MagnumMacKivler/RLCPT2/wiki/Locomotive-Data-Sheets), and more!


## Release Types

* **Current**: Not Under active development. Finished and polished (but may still contain minor bugs) versions of the code Release. (for example, **Version 2.x.x (Current)**).
* **Betas**: Under active development. Code in the Beta release(s) is currently being worked on, it may contrain game breaking bugs. (for example, **Version 2.x.x (Beta)**).
* **LTS**: Releases that receive Long-term Support, with a focus on stability. Note if you use an LTS release you may encounter compatibility issues with newer (or older) versions depending on the code version. (for example, **Version 2.x.x (LTS)*
* **Misc**: Miscellaneous Release. Reasoning for release will be explained in the Release Description. (for example, **Version 2.x.x (Misc)**).

Current, Betas, LTS and Misc releases follow [Semantic Versioning](https://semver.org). A
member of the Release Team signs each Current, Beta, LTS, and Misc release.

## Download

**Current, Beta, LTS and Misc Releases**
See all Releases [Here](https://github.com/MagnumMacKivler/RLCPT2/releases)

<br>

# Installation

## Install Using SVN:

Please note that this requires [Tortoise SVN.](https://tortoisesvn.net/downloads.html) Back in the old days, this was how all the really big Garry's Mod addons were installed.

1. Navigate into `<Your active steam directory>\SteamApps\common\Garry's Mod\garrysmod\data\expression2\` and make a new folder called "ptgamma".
2. Right click this folder and do an SVN checkout with this link:
`https://github.com/MagnumMacKivler/RLCPT2/trunk/ptgamma/`
3. Press "Okay" and Tortoise SVN will automatically install everything.
4. To update RLC PT2's files, simply right click the ptgamma folder, navigate into the Tortoise SVN bar, and click "SVN Update".

## Install Using Releases:

1. Head to the releases tab of the RLCPT2 GitHub

<p align="left">
  <a href="https://titusstudios.net/data/static/images/rlcpt2_readmeimg5.jpg">
    <img
      alt="rlcpt-installimg1"
      src="https://titusstudios.net/data/static/images/rlcpt2_readmeimg5.jpg"
    />
  </a>
</p>

<hr>

2. Download the Release of your choice (usually the latest one), usually you will only be downloading `(Current)` Releases.

<p align="left">
  <a href="https://titusstudios.net/data/static/images/rlcpt2_readmeimg1.jpg">
    <img
      alt="rlcpt-installimg1"
      src="https://titusstudios.net/data/static/images/rlcpt2_readmeimg1.jpg"
    />
  </a>
</p>

<hr>

3. Under the Release's Description, look for `Assets`, then download the `Source code (zip)`, As we want the ZIP file. 

<p align="left">
  <a href="https://titusstudios.net/data/static/images/rlcpt2_readmeimg2.jpg">
    <img
      alt="rlcpt-installimg1"
      src="https://titusstudios.net/data/static/images/rlcpt2_readmeimg2.jpg"
    />
  </a>
</p>

<hr>

4. Open the Zip file using a program like WinZip or WinRar, if it didn't open automatically. Then open the first folder in the zip file. 

| CAUTION | DO NOT Extract the first folder (Ex, `RLCPT2-master`)! RLC will not work correctly!  |
| :--- | :--- |

<p align="left">
  <a href="https://titusstudios.net/data/static/images/rlcpt2-readme/Screenshot_4.jpg">
    <img
      alt="rlcpt-installimg1"
      src="https://titusstudios.net/data/static/images/rlcpt2-readme/Screenshot_4.jpg"
    />
  </a>
</p>

<hr>

5. Extract **EVERYTHING BUT** the `README.md` and `version.txt`, ie, only extract the folders shown in the red box.... As these are just for the GitHub, and are not required ingame.

<p align="left">
  <a href="https://titusstudios.net/data/static/images/rlcpt2-readme/Screenshot_5.jpg">
    <img
      alt="rlcpt-installimg1"
      src="https://titusstudios.net/data/static/images/rlcpt2-readme/Screenshot_5.jpg"
    />
  </a>
</p>

<hr>

6. Extract the folders directly into: `<Your active steam directory>\SteamApps\common\Garry's Mod\garrysmod\data\expression2\`.
The file path should then look like `..\expression2\ptgamma\..`.

<p align="left">
  <a href="https://titusstudios.net/data/static/images/rlcpt2_readmeimg7.jpg">
    <img
      alt="rlcpt-installimg1"
      src="https://titusstudios.net/data/static/images/rlcpt2_readmeimg7.jpg"
    />
  </a>
</p>

| NOTE | If you see the folder "RLCPT2-master" inside the "expression2" folder, YOU INSTALLED IT WRONG and the E2s will not work!  |
| :--- | :--- |

<br>

## Required Addons

| NOTE | You will also need Grovestreetgman's Sound packs for RLC PT2 to work correctly. There are three.  |
| :--- | :--- |

1. Base Sounds: https://steamcommunity.com/sharedfiles/filedetails/?id=240020348
2. Engine Sounds 1: https://steamcommunity.com/sharedfiles/filedetails/?id=1254010890
3. Engine Sounds 2: https://steamcommunity.com/sharedfiles/filedetails/?id=1254014222

If you're currently in-game in Garry's Mod, open the E2 Editor, and click the "Update" button under the list of E2s on the lefthand side of the window.

## In-Game Setup and Usage:

READ THE OPERATOR'S MANUAL FOR SETUP AND USAGE INSTRUCTIONS!

<br>

## Current Project Team Members & Stats

[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/0)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/0)[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/1)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/1)[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/2)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/2)[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/3)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/3)[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/4)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/4)[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/5)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/5)[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/6)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/6)[![](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/images/7)](https://sourcerer.io/fame/TitusStudiosMediaGroup/MagnumMacKivler/RLCPT2/links/7)


"RLC"'s Logo, (and relating assets) are copyrighted under: Copyright © 2019 Titus Studios Media. [www.titusstudios.net](https://titusstudios.net/)
