sudo dnf config-manager addrepo --from-repofile=https://repo.librewolf.net/librewolf.repo

# add the repo via dnf4
sudo dnf config-manager --add-repo https://repo.librewolf.net/librewolf.repo

# install the package
sudo dnf install librewolf

# or on atomic desktops
rpm-ostree install librewolf
