<img src="https://github.com/arendst/Tasmota/blob/master/tools/logo/TASMOTA_FullLogo_Vector.svg" alt="Logo" align="right" height="76"/>

# RELEASE NOTES

## HttpHook support

This fork adds HttpHook support to Tasmota. The original Hubitat fork of Tasmota (from which this HttpHook fork was derived) was created by erocm123 (https://github.com/erocm123/Sonoff-Tasmota) and all credit for that fork is his. markus-li (https://github.com/markus-li/Tasmota-Hubitat) have adapted it to newer versions of Tasmota and made major changes.

## Fork maintenance

To keep this fork in-sync with the original Tasmota, firstly the HttpHook changes are kept in its own branch and then "git merge master" is used against the original Tasmota.

Commands used:
git fetch upstream
git merge upstream/[remote-branch-name] master

## Changelog

For the complete Changelog, see RELEASENOTES.md.

### Version 8.5.1 Hannah (HTTP Hook related changes)

- Expanded the Hubitat support into HttpHook support

### Version 8.1.0 Doris (Hubitat related changes)

- Added Hubitat support

### Version 7.2.0 Constance (Hubitat related changes)

- Added Hubitat support

### Version 7.1.0 Betty (Hubitat related changes)

- Added RELEASENOTES_HTTPHOOK.md
- Added Hubitat support
