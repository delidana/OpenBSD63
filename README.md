# OpenBSD63
This is to manage my OpenBSD workstation

You need to configure some stuff manually we can use our ansible playbook

# Set PKG_PATH
export PKG_PATH=https://ftp.eu.openbsd.org/pub/OpenBSD/snapshots/packages/amd64

# Install Ansible
pkg_add -Uv ansible git
