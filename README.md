# Ubicon sync data

This repository stores sync data for the Ubicon browser extension
(Ubicon - Device Icons for UniFi). The extension reads and writes it for you.

## What is in here

- `ubicon.json`: which icon you assigned to which device, listed by MAC address.
- `icons/`: custom icons you uploaded, one PNG file per icon.

Both appear after your first sync. Until then this README is the only file.

## Keep this repository private

`ubicon.json` lists MAC addresses and device labels from your network. Ubicon's
setup creates this repository as private. Leave it that way.

## Looking around is fine, editing is not

You can read the files and the commit history whenever you like. Each sync is
one commit, so the history shows what changed and when. Please do not edit
`ubicon.json` by hand. The extension merges by timestamp and may undo your edit.

## Turning sync off

1. In Ubicon's options, click Disconnect. Your assignments stay in your browser.
2. If you no longer want this data on GitHub, delete this repository: Settings,
   Danger Zone, Delete this repository.
3. Delete the access token at https://github.com/settings/personal-access-tokens

## Help

Questions and bug reports: https://github.com/tvirelli/Ubicon/issues

If you are reading this at tvirelli/ubicon-sync-template: this is the starter
that Ubicon's setup copies into your own account. You do not need to use it
directly. Open Ubicon's options and click Set up GitHub sync.
