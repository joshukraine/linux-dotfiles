# My Dotfiles for Linux Desktop

These are my dotfiles and general system preferences adapted for Debian-type Linux systems. This setup is intended for a personal development machine, not a web-facing server.

### Linux Bootstrap Script

This repo previously contained my entire provisioning solution for a new machine running Linux. I've now extracted the provisioning functionality into its own repository. Check it out:

&#9657; **Provision a new machine with [Linux Bootstrap](https://github.com/joshukraine/linux-bootstrap).**

NOTE: Linux Bootstrap automatically clones and installs this dotfiles repo.


### Prerequisites

The dotfiles assume you are running Ubuntu 14.04 (or similar) with the following software preinstalled:

* [Git](https://git-scm.com/)
* [Vim](http://www.vim.org/)
* [Tmux](http://tmux.github.io/)
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
* [Ruby](https://www.ruby-lang.org/en/)
* [rbenv](https://github.com/sstephenson/rbenv)

All of the above and more are included in [Linux Bootstrap](https://github.com/joshukraine/linux-bootstrap).

### Installation

```sh
git clone https://github.com/joshukraine/linux-dotfiles.git ~/dotfiles
source ~/dotfiles/install.sh
```


### Post-install Tasks

After running `install.sh` there are still a couple of things that need to be done.

* Add personal data to `~/.gitconfig.local` and `~/.zshrc.local`.


### Some of my favorite dotfile repos

* Pro Vim (https://github.com/Integralist/ProVim)
* Trevor Brown (https://github.com/Stratus3D/dotfiles)
* Lars Kappert (https://github.com/webpro/dotfiles)
* Ryan Bates (https://github.com/ryanb/dotfiles)
* thoughtbot (https://github.com/thoughtbot/dotfiles)
* Ben Orenstein (https://github.com/r00k/dotfiles)
* Joshua Clayton (https://github.com/joshuaclayton/dotfiles)
* Drew Neil (https://github.com/nelstrom/dotfiles)
* Chris Toomey (https://github.com/christoomey/dotfiles)
* Kevin Suttle (https://github.com/kevinSuttle/OSXDefaults)
* Carlos Becker (https://github.com/caarlos0/dotfiles)
* Zach Holman (https://github.com/holman/dotfiles/)
* Mathias Bynens (https://github.com/mathiasbynens/dotfiles/)
* Paul Irish (https://github.com/paulirish/dotfiles)


### Helpful web resources on dotfiles, et al.

* http://dotfiles.github.io/
* https://medium.com/@webprolific/getting-started-with-dotfiles-43c3602fd789
* http://code.tutsplus.com/tutorials/setting-up-a-mac-dev-machine-from-zero-to-hero-with-dotfiles--net-35449
* https://github.com/webpro/awesome-dotfiles
* http://blog.smalleycreative.com/tutorials/using-git-and-github-to-manage-your-dotfiles/
* http://carlosbecker.com/posts/first-steps-with-mac-os-x-as-a-developer/
* https://mattstauffer.co/blog/setting-up-a-new-os-x-development-machine-part-1-core-files-and-custom-shell
