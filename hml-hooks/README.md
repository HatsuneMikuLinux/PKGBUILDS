# hml-hooks

Pacman hooks for setting up certain system identification files and other useful features of Hatsune Miku Linux.

File name | Description
:--- | :---
hml-hooks-runner | Fixes files like `os-release`, `lsb-release`, `issues` for Hatsune Miku Linux.
hml-hooks.hook | Runs `hml-hooks-runner` after the `hml-hooks` package is updated.
hml-lsb-release.hook | Runs `hml-hooks-runner` after package `lsb-release` has been updated.
hml-os-release.hook | Runs `hml-hooks-runner` after package `filesystem` has been updated.
hml-reboot-required | Notifies user to reboot after essential system files have been updated.
hml-reboot-required2 | Filters kernel targets to `hml-reboot-required`.
hml-reboot-required.hook | Runs `hml-reboot-required2` after any of the listed essential system packages have been updated.
