# eos-hooks

Pacman hooks for setting up certain system identification files and other useful features of EndeavourOS.

File name | Description
:--- | :---
eos-hooks-runner | Fixes files like `os-release`, `lsb-release`, `issues` for EndeavourOS.
eos-hooks.hook | Runs `eos-hooks-runner` after the `eos-hooks` package is updated.
lsb-release.hook | Runs `eos-hooks-runner` after package `lsb-release` has been updated.
os-release.hook | Runs `eos-hooks-runner` after package `filesystem` has been updated.
eos-reboot-required | Notifies user to reboot after essential system files have been updated.
eos-reboot-required.hook | Runs `eos-reboot-required` after any of the listed essential system files have been updated.
