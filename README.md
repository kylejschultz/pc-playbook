# pc-playbook
Repo for my Ansible Playbook to run when a fresh install is done to take some of the tedium out of the twice-annual Windows reinstalls.  Currently, there is no playbook, but I'm trying to keep track of apps that I will want to make sure I carry over to a clean installation of Windows.

## List of Things I Install
In somewhat of a loose order:
### Core
- [1Password](https://github.com/kylejschultz/pc-playbook.git)
- [Chrome](https://www.google.com/chrome/)
- [Google Drive for Desktop](https://www.google.com/drive/download/)
- [DisplayFusion](https://www.displayfusion.com/Download/)
- [Discord](https://discord.com/)
   - [BetterDiscord](https://betterdiscord.app/)
- [Beacn App](https://www.beacn.com/pages/downloads)
- [Nvidia Geforce and Drivers](https://www.nvidia.com/en-us/geforce/geforce-experience/) 
- [Logitech Capture](https://www.logitech.com/en-us/software/capture.html)
- [Steam](https://store.steampowered.com/about/)
- [Epic](https://store.epicgames.com/en-US/download)
- [Snagit](https://download.techsmith.com/snagit/releases/2145/snagit.exe)
   - Direct link to licensed version.
- [Spotify](https://www.spotify.com/us/download/windows/)
- [StartAllBack](https://www.startallback.com/)
   - Gives extra functionality to taskbar, start menu and more.

### Dev Tools
- [WSL2](https://docs.microsoft.com/en-us/windows/wsl/install)
   - Dev box instance on W: drive
- [VSCode](https://code.visualstudio.com/download)
   - Most things synced automatically with Github account
   - Manual Installs:
      - [GitOps Plugin](https://github.com/weaveworks/vscode-gitops-tools/releases)
- Fonts
   - Hack (VSC text editor)
   - MesloLGS NF (VSC terminal)
- [OhMyZSH](https://ohmyz.sh/#install)
   - [PowerLevel10k Theme](https://github.com/romkatv/powerlevel10k)
- [Sublime Text](https://www.sublimetext.com/)
- [Lens](https://k8slens.dev/) for Kubernetes

### Work
- [Office Suite + Teams](https://portal.office.com/account/?ref=MeControl#installs)
- [Zoom](https://zoom.us/download)
- [Slack](https://slack.com/downloads/windows)

### Extras
- [DualSenseX](https://github.com/Paliverse/DualSenseX) 
   - Better PS5 Controller Support

## Tasks to Automate
- Driver updates
- Installs of as many apps listed above as I can swing
- Configure SSH token for VSCode Remote to dev box
