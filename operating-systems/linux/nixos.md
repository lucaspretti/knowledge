# [NixOS](https://nixos.org)

NixOS is a Linux distro built around the Nix package system. Nix is built around the idea of immutability. It makes all packages immutable by giving them their own directory identified by a hash that is derived from ALL of that package's dependencies. This has a number of desirable properties:

- It makes it trivial to have multiple versions of the same package installed at the same time and allows you to switch between them at will.
- It is trivial to roll back your system after a failed upgrade. Difficult system recovers after you upgrade to a new unstable version are a thing of the past.
- Non-privileged users can install software completely securely.
- Projects packaged with nix have the best possible build reproducibility because nix accounts for ALL of your dependencies all the way down to the lowest level system libraries, compilers, etc.

Whilst I don't use NixOS as my primary OS. I use [nix package manager](../../package-managers/nix/nix.md) on macOS. And I am exploring using NixOS for servers I use.

## Nix configs (Linux)

- [Infrastructure](https://github.com/rvolosatovs/infrastructure#readme)
- [Bob nix-home](https://github.com/bobvanderlinden/nix-home)
- [Brian McKenna Nix Files](https://github.com/puffnfresh/nix-files) - NixOS configuration and custom Nix derivations.
- [William A. Kennington III](https://github.com/wkennington/nixos) - NixOS configurations for my local cluster of machines.
- [Arian van Putten](https://github.com/arianvp/nixos-stuff)
- [Michael Peyton Jones](https://github.com/michaelpj/nixos-config)

## Nix configs (macOS)

- [John Wiegley](https://github.com/jwiegley/nix-config)
- [LnL7](https://github.com/LnL7/dotfiles#readme)
- [cmacrae](https://github.com/cmacrae/.nixpkgs/blob/master/darwin-configuration.nix)
- [Tom's nix-configs](https://github.com/nocoolnametom/nix-configs)

## Notes

- [Even if you curate your system, it gathers dust: configuration files left to rot, manually installed packages that didn't get uninstalled properly, orphaned packages difficult to track down... You could argue that it shouldn't happen in the first place, but that actually takes discipline. In NixOS, this is managed for you. Once you do nixos collect-garbage -d, you know that your system is only left with what it needs. Nothing more, nothing less.](https://www.reddit.com/r/NixOS/comments/441ymh/nixos_users_tell_me_what_are_the_cons/czmu9lo/)

## Links

- [PhD thesis on nixOS](https://nixos.org/~eelco/pubs/phd-thesis.pdf)
- [Search NixOS options](https://nixos.org/nixos/options.html#)
- [Notes on nixOS package manager](https://yoshuawuyts.gitbooks.io/knowledge/content/bin/nix.html)
- [Why nixOS?](https://www.reddit.com/r/NixOS/comments/8bxdyu/why_nixos/)
- [Not OS](https://github.com/cleverca22/not-os) - Operating system generator, based on NixOS, that, given a config, outputs a small (47 MB), read-only squashfs for a runit-based operating system, with support for iPXE and signed boot.
- [NixOS 💜 Chromebook?](https://sphalerite.org/ghotl/posts/2017-11-10-chromebook.html)
- [NixOS Wiki](https://nixos.wiki/wiki/Main_Page)
- [NixOps](https://github.com/NixOS/nixops) - NixOS-based cloud deployment tool.
- [NixOS Discourse forum](https://discourse.nixos.org/)
- [Getting started with NixOS on Raspberry Pi 3 Model B+](https://github.com/zupo/nix#readme)
- [Collection of NixOS image builders](https://github.com/nix-community/nixos-generators) - Allows to take the same NixOS configuration, and generate outputs for different target formats.
- [HN: Guix An advanced operating system (2019)](https://news.ycombinator.com/item?id=18902823)
