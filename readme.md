This repo will be worked out to be like the win10-setup repo after I have found myself the right distro and properly established myself with gpu + monitor support.

Currently serves as a place to get the most important linux things I need to keep myself noted on going about to best install and tools before writing a guide for the public.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

Why not private the repo? ¯\_(ツ)_/¯

Well if your reading this then you can take a look at what i've already written for myself to possibly help youself, or... you can possibly help ME! By opening an issue or pr with some way to go about my setup better if you happen to know something you think I would want listed. as a reminder, the setup will always be going towards finding/making a distro that is geared towards **preformance** all around (not really including stuff like scientific workloads) and most importantly **LATENCY**. And of course, debloated as possible.

My goals are inspired by the [PC-Tuning](https://github.com/amitxv/PC-Tuning) guide in it's extreme minimalism of stripping Windows ISOs, then debloating and tweaking the OS for most **preformance** and least **latency** possible. No different goals from my win10-setup repo, but just for Linux!

These will hopefully end up as guides for setting up these 2 OS's as best as possible for dual booting (with or without seperate drives, I am still unsure of... current dual boot setup on a laptop on same drive works fine but I have started to read up on windows quite possibly breaking linux even though its formatted in btrfs and the pc-tuning guide pretty much disables every update possible for everthing... need to research this further).

Amd I still need to find the best boot manager if [Grub](https://alternativeto.net/software/grub/?license=opensource&sort=likes) isn't the best!

--------------------------------------------------------------------------------------------------------------------------------------------------------------
so far what ive found for myself:

most "end game/customizable" distro that isn't containers (distrobox) or virtualization (VanillaOS? must recheck): [Bedrock Linux](https://bedrocklinux.org/)

"fastest" arch-based/fork distro (systemd only and their repos enforce systemd): [CachyOS](https://cachyos.org/)

"fastest" BOOT TIME arch-based/fork distro BOOT TIME using **dinit** and **LXDE**: [Artix Linux (community built iso if base iso install is too complicated)](https://artixlinux.org/download.php#official)

someone's effort to use cachyos repos on artix: https://www.reddit.com/r/artixlinux/comments/15cl4rp/comment/jty08qq

--------------------------------------------------------------------------------------------------------------------------------------------------------------

best IMMUTABLE pre-configured gaming distro: [Bazzite desktop variant (HTPC variant only supports AMD gpus at the time of writing this)](https://github.com/ublue-os/bazzite/#desktop)
