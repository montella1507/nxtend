# Changelog

# 11.0.0

## Features

- Nx 11 support (Nx 11 now required)
- update Capacitor to 2.4.5
- added `cap` builder for a more generic interface with the Capacitor CLI

## BREAKING CHANGES

- the `command` builder has been removed

# 2.0.2

# Fixes

- fix Windows support

# Features

- update Capacitor to 2.4.2
- add Capacitor configs to frontend application
- add or update `package.json` in project folder when generating a Capacitor project
- add builder configurations for Nx Console
- add `add-plugin` schematic for adding Capacitor plugins

# BREAKING CHANGES

- Capacitor plugins must now be added to both the root and project-level `package.json`

# 1.1.0

## Features

- upgrade Capacitor to 2.4.0
- copy package.json from workspace root for cap commands
