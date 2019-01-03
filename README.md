# ansible-role-aur

This is a small Ansible role I wrote to install aur packages.

The role clones the Git repository to `/var/git/{{ pkg_name }}` and executes `makepkg` with a non root user. 

# Parameters

`pkg_name`: The name of the package in aur to install.
`build_user`: The unix user name of the user to run the `makepkg` command with.

# License

GNU AGPLv3

Author Information

This role was created in 2019 by Henrik Pingel.
