
Now on functionality of our App:

* It allows you to backup individual apps and their data.
* Both backup and restore of individual programs one at a time and batch backup and restore of multiple programs are supported.
* Restoring system apps should be possible without requiring a reboot afterwards.
* Backups can be scheduled with no limit on the number of individual schedules and there is the possibility of creating custom lists from the list of installed apps.

And here's the project's [FAQ](FAQ.md).

A combination with your favourite sync solution (e.g. Syncthing, Nextcloud...)  keeping an encrypted copy of your apps and their data on your server or "stable" device could bring a lot of benefits and save you a lot of work while changing ROMs or just cleaning your mobile device.

Encryption

If enabled the data backup will be encrypted with AES256 based on a password you can set in the settings, which you'll have to use when you want to restore the data. This way you can store your backups more securely, worrying less about their readability.

Compatibility

Version 5.0.0 uses new encryption, new databases, fixes most of reported bugs in 4.0.0 and boost the performance to something near the 3.2.0's. With that said, it's incompatible with the older versions.

Version 4.0.0 marks a full overhaul of the app structure and thus breaks compatibility with previous versions.

Till the version 0.9.3 there's been no structural change in how the app handles backup/restore. So you could use that version to restore the old backups, then move to the newest version and renew your backups so that they'll stay compatible as long as the logic of the app doesn't radically change.

## Screenshots

### Dark Theme

<p float="left">
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" width="170" />
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" width="170" />
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/3.png" width="170" />
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/4.png" width="170" />
</p>

### Light Theme

<p float="left">
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/5.png" width="170" />
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/6.png" width="170" />
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/7.png" width="170" />
 <img src="/fastlane/metadata/android/en-US/images/phoneScreenshots/8.png" width="170" />
</p>

## Building

OAndBackupX is built with gradle, for that you need the android sdk.

## Licenses <img align="right" src="agplv3.png" width="64" />

OAndBackupX is licensed under the [GNU's Affero GPL v3](LICENSE.md).

App's icon is based on an Icon made by [Catalin Fertu](https://www.flaticon.com/authors/catalin-fertu) from [www.flaticon.com](https://www.flaticon.com)

Placeholders icon foreground made by [Smashicons](https://www.flaticon.com/authors/smashicons) from [www.flaticon.com](https://www.flaticon.com)


