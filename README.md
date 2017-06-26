# Ansible eecli
Install [eecli](https://github.com/rsanchez/eecli) globally.

## Installation
Clone this repository inside your ```roles``` directory.

## Usage
Installs ```eecli``` to ```/usr/local/bin```

## Role Variables
```
---
# defaults to /usr/local/bin
eecli_install_path: /usr/local/bin

# defaults to latest version
eecli_version: ~
```