### Recipes for [autopkg](https://autopkg.github.io/autopkg/)

To use the Cisco AnyConnect recipe, you must first have the DMG of the installer pkg. You designate the path to the download with `-p /path/to/dmg`. The recipe verifies that it is indeed signed by Cisco, so do not repackage or otherwise alter it. Note that by default only the VPN would be installed, as all 'posture' and websecurity-related components are disabled by default. Feel free to modify the choice changes XML in the pkginfo file as needed, including the receipts.