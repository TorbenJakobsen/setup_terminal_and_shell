#############################
  Set up Terminal and Shell
#############################

**WORK IN PROGRESS**

Introduction
============

Documents my personal setup.

At a later point I will use GNU Stow to manage configuration.

Install prefered shell - zsh
----------------------------

For macOS and Linux I will for now use zsh - but I am considering nushell (which also run on Windows!)

| For Windows I will for now use the built-in shells.
| I will later go into how to configure WSL.

Install prefered terminal emulator - Ghostty
--------------------------------------------

| I will use GhostTTY on my Linux (debian and fedora) and macOS.
| For Windows 11 I will use the regular Windows Terminal.

Fedora
~~~~~~

Hosted on COPR.

https://copr.fedorainfracloud.org/coprs/pgdev/ghostty/

.. code:: bash
  
  # enable copr repo
  sudo dnf5 copr enable pgdev/ghostty 

  # install stable
  sudo dnf5 install ghostty

Install prefered Terminal theme - Oh-My-Posh
--------------------------------------------

I will use Oh-My-Posh, as it is universal across my shells.

https://ohmyposh.dev/

  **Oh My Posh**
  A prompt theme engine for any shell.

