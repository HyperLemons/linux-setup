This repo will be worked out to be like the win10-setup repo after I have found myself the right distro and properly established myself with gpu + monitor support.

Currently serves as a place to get the most important linux things I need to keep myself noted on going about to best install and tools before writing a guide for the public.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

--------------------------------------------------------------------------------------------------------------------------------------------------------------
So far what i've found for myself:

Most "end game/customizable" distro that isn't containers (Distrobox) or virtualization (VanillaOS? must recheck): [Bedrock Linux](https://bedrocklinux.org/)

"Fastest" Arch-based/fork distro (systemd only and their repos enforce systemd): [CachyOS](https://cachyos.org/)

"Fastest" BOOT TIME Arch-based/fork distro using **dinit** and **LXDE**: [Artix Linux (community built iso if base iso install is too complicated)](https://artixlinux.org/download.php#official)

Someone's effort to use CachyOS repos on Artix: https://www.reddit.com/r/artixlinux/comments/15cl4rp/comment/jty08qq

--------------------------------------------------------------------------------------------------------------------------------------------------------------

Best IMMUTABLE pre-configured gaming distro: [Bazzite desktop variant (HTPC variant only supports AMD gpus at the time of writing this)](https://github.com/ublue-os/bazzite/#desktop)

--------------------------------------------------------------------------------------------------------------------------------------------------------------

CachyOS kernel for Fedora (includes immutable distributions): https://copr.fedorainfracloud.org/coprs/bieszczaders/kernel-cachyos/

Benchmark of different Fedora kernels (possibly outdated): https://reddit.com/r/Fedora/s/e0IFbgJVQF

--------------------------------------------------------------------------------------------------------------------------------------------------------------
LXinput mouse settings that pretty close to Windows stock (imo): https://files.catbox.moe/z3lwd5.png

GUI for changing picom settings (requires building for some distros): https://github.com/qtilities/picom-conf/

--------------------------------------------------------------------------------------------------------------------------------------------------------------

Flatpak apps to install:

Alternative GUI (requires building and may be outdated/limited support): https://github.com/ohno9119/picom-conf-gtk

Manually starting and stopping Picom (not really needed but if you want to?, requires building for some distros): https://github.com/sparkylinux/sparky-picom
