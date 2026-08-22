# Archnon Linux's Project Files v4.0.0 (by archnon@protonmail.com btw)
# Coded by: archnon@protonmail.com, at all btw

####################################################################
# Copyright (c) 2026 archnon@protonmail.com. All Rights Reserved.  #
####################################################################

scripts = (lazyanon, anonman, anondns, lazymac, mactd, nkill, setup-archnon, wifictl)

Requires = (bash, git, sudo/root)

Service for = (systemd, runit, open-rc)

Package managers = (apt, apk, pacman, emerge, xbps-install, dnf, yum, zypper)

Description = “Developed by: archnon@protonmail.com btw, Archnon is an Alpine Linux based distro with the only focus being anonymous, fully private, super portable/light, using as much 50 mb of ram by default on its minimal”

Project.usage = $(su && git clone https://github.com/sleuth3301/archnon-files && cd archnon-files && chmod +x * && ./make_it_work)
