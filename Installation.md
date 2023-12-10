# Installation

## Windows
### Installer
* Download the official Windows version of Ruby from:
  * the [RubyInstaller website](https://rubyinstaller.org/downloads/)
  * the RubyInstaller's [GitHub releases](https://github.com/oneclick/rubyinstaller2/releases/) page

### Winget
* Alternatively, you can use Windows Package Manager (winget) to install Ruby. Open your command prompt or PowerShell and enter the following command:

```bash
winget install RubyInstallerTeam.Ruby.3.2
```

This will automatically download and install the latest version of Ruby available through the Windows Package Manager.

## macOS
* Ruby comes pre-installed on macOS. You can check the version by opening a terminal and typing:

```bash
ruby -v
```

If for some reason you need to update or install a different version, consider using a version manager like [RVM](https://rvm.io/) or [rbenv](https://github.com/rbenv/rbenv).

## Linux

### Ubuntu/Debian-based Distros
* Most Ubuntu/Debian-based Linux distributions come with Ruby pre-installed. You can check the version by opening a terminal and typing:

```bash
ruby -v
```

If Ruby is not installed or you need a different version, you can use the package manager to install it:

```bash
sudo apt-get update
sudo apt-get install ruby-full
```

### Red Hat/Fedora-based Distros
* For Red Hat and Fedora-based distributions, you can use the following commands:

```bash
sudo yum install ruby
```

### Arch Linux
* On Arch Linux, you can install Ruby using the package manager:

```bash
sudo pacman -S ruby
```

### Other Distros
* For other Linux distributions, consult your package manager's documentation to install Ruby.

## Verifying Installation
To verify that Ruby has been successfully installed, open a terminal or command prompt and type:

```bash
ruby -v
```

This should display the installed Ruby version.