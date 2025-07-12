# ![wsl - 2025]()

## Table of Contents

## To restore WSL (Windows Subsystem for Linux) to its original state and clean it completely, there are several levels of cleanup:

In `Windows PowerShell`, use the following command to list the installed distributions:

```bash
wsl --list --verbose

or 

wsl --list --all
```


delete a distribution (like Ubuntu) and restore it to its original state

```bash
wsl --unregister Ubuntu
```
