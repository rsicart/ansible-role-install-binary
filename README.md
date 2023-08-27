Ansible Role: install-binary
=========

Downloads, decompresses and copies a binary from a remote location into a destination folder.

Requirements
------------

N/A

Role Variables
--------------

Binary URL to download, mandatory:

```
install_binary_url: "<mandatory>"
```

List of binary filenames to extract from downloaded file, mandatory:

```
# install_binary_binary_filenames: "[<mandatory>]"
```

Folder where file will be downloaded:

```
install_binary_download_folder: "~/Downloads/install_binary"
```

Folder where binary files will be copied:

```
install_binary_bin_folder: "~/bin"
```

Clean download folder at the end:

```
install_binary_clean_enabled: false
```

Dependencies
------------

N/A

Example Playbook
----------------

See [tests](tests/test.yml)

License
-------

GPL-3.0-only

Author Information
------------------

* https://gitlab.com/rsicart
* https://github.com/rsicart

