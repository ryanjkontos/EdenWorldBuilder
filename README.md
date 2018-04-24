# Eden: World Builder
This repo hosts files for Eden World Builder. You can download the App Store release, or help us work on an offical update.

# Branches
The "master" branch containes files that are actively being worked on by the Eden community. Anyone that wants to work on this branch can.

The "2.1" branch contains the files for the offical 2.1 update of Eden. Build from this branch if you want the latest officially released, guarunteed stable version.

## Devlopment
The community is working on developing an update for Eden. You can help too by joining the Discord.

Currently, some changes that have been partially or fully implemented include:

- Autosave
- iTunes File Sharing support for worlds
- Full screen iPhone X support
- New Vine block texture
- Vine turns to stone when burnt
- Ice turns to water when burnt
- Minor UI tweaks


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Setting up local repo

Use the Terminal command `git clone https://github.com/ryankontos/EdenWorldBuilder.git` to download the existing repo to your home folder. You will also need to download the "Flurry" folder from this link: https://mega.nz/#!cDQ1SKKA!0G7USvZ3Yf79QOQ6u-Gjn8G7kTNyJ8sAMcqeRy9n3q0, unzip it, and place it inside /EdenWorldBuilder.

When building in Xcode, make sure Bitcode is disabled, and that Xcode can find all required files.

### Uploading your local repo

After you are done making changes cd into ~/EdenWorldBuilder using `cd ~/EdenWorldBuilder` then type `git add .` to add the changes to the resolve, then commit your changes and add a reason with `git commit -m "INSERT REASON HERE"` and finally upload with `git push -u origin master`. You can also commit using Xcode's built in Source Control features.

## License

This project is licensed under the GNU General Public License v3 - see the [LICENSE.md](LICENSE.md) file for details
