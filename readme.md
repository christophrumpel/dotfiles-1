# Christoph Rumpel's Dotfiles

This is a fork from [Dries Vints](https://github.com/driesvints/dotfiles)'s dotfiles. Check out his detailed documentation about all the files. I just changed a few things to better fit my needs.

Be careful when using these dotfiles because they change a lot of MacOS settings and install all the apps I need.

## Backup Checklist

- Did you commit and push any changes/branches to your git repositories?
- Did you copy your .env files to a safe place if they are not casual?
- Did you copy your IDE settings? (e.g. PhpStorm)
- Did you backup local databases you need?
- Did you remember to save all important documents from non-cloud directories?
- Did you save all of your work from apps which aren't synced through cloud?
    + Insomnia (Export to Dropbox)
- Did you update [mackup](https://github.com/lra/mackup) to the latest version and ran `mackup backup`?
- Export Tyme data because it wasn't synced correctly the last time

## Installation

- More Details here [here](https://github.com/driesvints/dotfiles)
- `Update` macOS to the latest version with the App Store
- `Install Xcode` from the App Store, open it and accept the license agreement
- `Install macOS Command Line Tools` by running xcode-select --install
- Copy your public and private `SSH keys to ~/.ssh` and make sure they're set to 600 (Or Create new ones)
- `Clone` this repo to ~/.dotfiles
- Install [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh/wiki)
- Run `install.sh (from the dotfiles dir)` to start the installation
- SignIn to 1Password for Dropbox credentials
- Sync `Mackup` Folder (e.g. Dropbox)
- After mackup is synced with your cloud storage, restore preferences by running `mackup restore`
- Restart your computer to finalize the process

## Further Steps

- Install manually
    - Elgato Control Center
- Permissions
    - Bartender
    - Alfred

## Still Missing

- Backup Spark Mail Accounts (Working if you login in with one of your accounts)
- Activate right mouse click
- Sleep time missmatch/error
- Brave extensions are not synced
- Set Github confid details (name, email)
- Terminal theme?
- Rectangle settings?
- Operator Mono font
- Disable Mac sounds
- Finder Show file extensions
- Modifier keys: Switch caps lock to Esc, possible through commandline?
