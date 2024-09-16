---
name: Bug report (applications only)
about: Create a report to fix installation and integration of the available apps
title: ''
labels: ''
assignees: ''

---

# Premise
"AM"/"AppMan" is just a tool to provide applications easily and quickly and is only responsible for integrating the AppImages into the system and installing the various programs available, respecting the following order (refer to the option "-d" to download the installation script without installing it):
- creation of the base directories and the removal script
- download of the package
- creation of the version file and the update script
- possibly, extraction of the icons and .desktop files, if needed

The malfunction of the installation scripts will then be taken into account. On the contrary, any malfunction related to individual applications is the responsibility of the related developer or packager. Refer to the option "-a" to know the sources of each program listed here, so you can contact them to report the bug.

--------------------------------------------------

## Please, describe the bug
Write here