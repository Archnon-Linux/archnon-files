# Archnon Linux's Project File v3.0.12 (by archnon@protonmail.com btw)
# Coded by: archnon@protonmail.com, at all btw

Contains.utils = (lazyanon, anonman, anondns, lazymac, mactd, nkill, setup-archnon, wifictl)
Contains.files = (archnon.iso, .profile, .shrc, README.md, config.ini, example_bridges.txt)

Requires.packages = (bash, sudo)
Supports.service_managers = (systemd, runit, open-rc)
Supports.package_managers = (apt, apk, pacman, emerge, xbps-install, dnf, yum, zypper)

Project.description = “Developed by: archnon@protonmail.com btw, Archnon is an Alpine Linux based distro with the only focus being anonymous, fully private, super portable/light, using as much 50 mb of ram by default on its minimal”

Project.usage = $(sudo git clone https://github.com/Archnon-Linux/archnon-files && cd archnon-files && sudo chmod +x * && sudo ./make_it_work)
