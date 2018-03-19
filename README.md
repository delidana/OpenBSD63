# OpenBSD63
This is to manage my OpenBSD workstation

You need to configure some stuff manually we can use our ansible playbook

# Set PKG_PATH (Does not work with syspatch)
export PKG_PATH=https://ftp.eu.openbsd.org/pub/OpenBSD/snapshots/packages/amd64

or

# Set installurl (Does work with syspatch)
echo "https://ftp.eu.openbsd.org/pub/OpenBSD" > /etc/installurl

# Install Ansible
pkg_add -Uv ansible git
