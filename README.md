# Northfire IRC Client – downloads

Installers for the **Northfire IRC Client**, the free chat client for the [Northfire IRC Network](https://northfire.dev/) (irc.northfire.net) that also connects to any other IRC network.

Get the latest version from the [Releases page](https://github.com/kbargman/northfire-releases/releases/latest) or from [northfire.dev/download](https://northfire.dev/download).

## Install with a package manager

**macOS (Homebrew)**
```sh
brew tap kbargman/northfire
brew install northfire
```

**Debian / Ubuntu (apt)**
```sh
curl -fsSL https://northfire.dev/northfire-packages.asc | sudo gpg --dearmor -o /usr/share/keyrings/northfire.gpg
echo "deb [signed-by=/usr/share/keyrings/northfire.gpg] https://northfire.dev/apt stable main" | sudo tee /etc/apt/sources.list.d/northfire.list
sudo apt update && sudo apt install northfire
```

**Fedora / RHEL (dnf / yum)**
```sh
sudo curl -fsSL https://northfire.dev/rpm/northfire.repo -o /etc/yum.repos.d/northfire.repo
sudo dnf install northfire
```

**Windows**
```powershell
scoop bucket add northfire https://github.com/kbargman/scoop-northfire
scoop install northfire
```
or `winget install Northfire.Northfire` (once approved in the winget catalog).

The app updates itself automatically when installed from the download page; package-manager installs update with your package manager.

Need help? Join **#support** on irc.northfire.net or email link@northfire.org.

<!-- Built by Kyle Bargman -->
