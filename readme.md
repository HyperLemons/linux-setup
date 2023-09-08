This repo will be worked out to be like the win10-setup repo after I have found myself the right distro and properly established myself with gpu + monitor support.

Currently serves as a place to get the most important linux things I need to keep myself noted on going about to best install and tools before writing a guide for the public.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

Why not private the repo? ¯\_(ツ)_/¯

Well if your reading this then you can take a look at what i've already written for myself to possibly help youself if your at a similar stage to where I am, or... you can possibly help ME! By opening an issue or PR with some way to go about my setup better if you happen to know something you think I would want listed. As a reminder, the setup will always be going towards finding/making a distro that is geared towards **preformance** all around (not really including stuff like scientific workloads) and most importantly **LATENCY**. That includes sound latency! And of course, debloated as much as possible.

My goals are inspired by the [PC-Tuning](https://github.com/amitxv/PC-Tuning) guide in it's extreme minimalism of stripping Windows ISOs, then debloating and tweaking the OS for most **preformance** and least **latency** possible. No different goals from my win10-setup repo, but just for Linux!

These will hopefully end up as guides for setting up these 2 OS's as best as possible for dual booting (with or without seperate drives, I am still unsure of... current dual boot setup on a laptop on same drive works fine but I have started to read up on Windows updates quite possibly breaking linux even though its formatted in btrfs and the pc-tuning guide pretty much disables every update possible for everthing... need to research this further).

And I still need to find the best **STABLE** and **COMPTAIBLE WITH MOST DEVICES/DEVICE BIOS** boot manager if [Grub](https://alternativeto.net/software/grub/?license=opensource&sort=likes) isn't the best!

--------------------------------------------------------------------------------------------------------------------------------------------------------------
So far what i've found for myself:

Most "end game/customizable" distro that isn't containers (Distrobox) or virtualization (VanillaOS? must recheck): [Bedrock Linux](https://bedrocklinux.org/)

"Fastest" Arch-based/fork distro (systemd only and their repos enforce systemd): [CachyOS](https://cachyos.org/)

"Fastest" BOOT TIME Arch-based/fork distro BOOT TIME using **dinit** and **LXDE**: [Artix Linux (community built iso if base iso install is too complicated)](https://artixlinux.org/download.php#official)

Someone's effort to use CachyOS repos on Artix: https://www.reddit.com/r/artixlinux/comments/15cl4rp/comment/jty08qq

--------------------------------------------------------------------------------------------------------------------------------------------------------------

Best IMMUTABLE pre-configured gaming distro: [Bazzite desktop variant (HTPC variant only supports AMD gpus at the time of writing this)](https://github.com/ublue-os/bazzite/#desktop)

--------------------------------------------------------------------------------------------------------------------------------------------------------------

CachyOS kernel for Fedora (includes immutable distributions): https://copr.fedorainfracloud.org/coprs/bieszczaders/kernel-cachyos/
Benchmark of different Fedora kernels (possibly outdated): https://reddit.com/r/Fedora/s/e0IFbgJVQF