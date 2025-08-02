Downloading tldr pages to /home/morcego/.local/share/tldr
apt

[0m[0mPackage manager for Debian-based distributions.
Intended as a user-friendly alternative to apt-get for interactive use.
For equivalent commands in other package managers, see https://wiki.archlinux.org/title/Pacman/Rosetta.
More information: https://manned.org/apt.8.

 - [0m[32;23;22;24;25mUpdate the list of available packages and versions (recommended before running other apt commands):
   [33;23;22;24;25msudo apt update[0m
[0m
 - [0m[32;23;22;24;25mSearch packages by name or description:
   [33;23;22;24;25mapt search [0mpackage
[0m
 - [0m[32;23;22;24;25mSearch packages by name only (supports wildcards like *):
   [33;23;22;24;25mapt list [0mpackage
[0m
 - [0m[32;23;22;24;25mShow detailed information about a package:
   [33;23;22;24;25mapt show [0mpackage
[0m
 - [0m[32;23;22;24;25mInstall a package, or update it to the latest version:
   [33;23;22;24;25msudo apt install [0mpackage
[0m
 - [0m[32;23;22;24;25mRemove a package (use purge instead to also remove configuration files):
   [33;23;22;24;25msudo apt remove [0mpackage
[0m
 - [0m[32;23;22;24;25mUpgrade all installed packages to their latest versions:
   [33;23;22;24;25msudo apt upgrade[0m
[0m
 - [0m[32;23;22;24;25mList all installed packages:
   [33;23;22;24;25mapt list [0m[-i|--installed]
[0m[0m