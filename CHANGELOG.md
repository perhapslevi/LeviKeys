# LeviKeys Changelog
All notable changes to LeviKeys will be documented in this file

## [Unreleased]
### Added
- Tray Menu. LeviKeys now has options to open up LeviKeys Help, toggle LeviKeys Sounds, Suspend, Restart, or Exit LeviKeys.
- LeviKeys Mapping Utility - This tool allows the user to remap several keys to act as the AppKey (for keyboards that omit it.)
- G051 | Toggle text case.

### Changed
- Help Menu updated to include option for using the LeviKeys Mapping Utility - Help Menu runs this separate app as Administrator to allow registry changes to be made. As part of this, some minor changes have been madde to the design of this dialog.
- Uninstaller updated to remove registry entries from LeviKeys Mapping Utility - Uninstaller Package now runs the Uninstaller Temp as administrator to allow this.
- Installer now has a progress bar included to prevent action before files are copied.

### Deprecated

### Removed

### Fixed
- Issue with Feedback dialog, where it would error out the second time you tried to load it.3
- Fixed typo in Documentation and Quick Reference Sheet, where SAGOV Acronyms did not include the letter 's' before the acronym.

## [2.1.3] - 2019-02-18
### Added
- Feedback option in Help menu.

### Changed
- Considerable updates to Uninstaller

### Fixed
- Issue with Uninstaller, where it is unable to remove itself.

## [2.1.2] - 2019-02-17
### Added
- This change log.
- Installer now includes a shortcut to this change log in the Documentation folder.
- Sound! LeviKeys now has the option during installation to turn sound on or off.
- M006 | Opens LeviKeys Change Log in IE.

### Changed
- LeviKeys Documentation and Quick Reference Sheet updated to reflect this change log - Version notes now point here.
- LeviKeys Splash Screen now plays music if sound is turned on.
- M002 now plays sounds when suspending/unsuspending LeviKeys if sound is turned on.
- M003 now calls a GUI with options to open Quick Reference, Documentation, Change Log, and also has an option to turn sound on or off.
- M003 now makes a dinging noise when sound is turned on.
- M004 now plays a snippet of Hotline Bling when setting the extension if sound is turned on.
- Resource files now named without extensions - extensions are added when needed by individual scripts. Resource files also have much more ambiguous names than in previous versions.
- Resource Files are now hidden.
- Added a border to all GUI without a title bar, purely for aesthetic reasons.

### Fixed
- Issue with installer when setting extension for G037 (installer included the prefix: send,  when setting extension.)
- Typo in LeviKeys Documentation - NECare templates G024AA - G024AD were all labelled as G024b
- Typo in LeviKeys Documentation and Quick Reference Sheet where G001 was shown to have4 Menu+Alt+N instead of Menu+Alt+V
- Numerous other small typos in Documentation and Quick Reference Sheet.
- Issue with installer where image wasn't displaying.

## [2.1.1] - 2019-02-11
### Added
- G046 | "( ͡° ʖ̯ ͡°)"
- G047 | "ヽ༼ຈل͜ຈ༽ﾉ"
- G048 | "(ノ͡° ͜ʖ ͡°)ノ︵┻┻"
- G049 | "ヽ( ͡° ͜ʖ ͡° )つ──☆*:・ﾟ"
- G050 | “Provided customer with REQ number”

### Changed
- Installer has been updated to remove previous versions of LeviKeys.
- Installer updated to copy a version of LeviKeys into the startup folder on C:/ drive. Currently in test phase.
- Updated Q001 and Q002 to add the line "Thankyou for contacting the Service Desk"
- Updated H001 to reflect 9:30 start instead of 10:00 start.

## [2.1.0] - 2019-02-11
### Added
- Option during installation to set extension for use with G037
- LeviKeys Logging Assistant - considerable GUI work went into this to add information on how to log various types of tickets, as well as MIM processes for all 34 customers with MIM.
- G037 | Returns the user’s extension.
- M004 | Allows the user to set their extension
- G038A to G038P | Managed Services Templates
- M005 | LeviKeys Logging Assistant
- G039 | "( ͡° ͜ʖ °)"
- G040 | Displays information on how to log Botnet emails
- G041 | Displays information on how to log Unexpected Shutdown emails
- G042 | Displays information on how to log UQ Fault emails
- G043 | "Multivendor Voice TAC"
- G044 | "Multivendor Data TAC"
- G045 | "03 8392 6947"

### Changed
- Altered convention for shortkeys G020A - G020AL

## [2.0.1] - 2019-01-17
### Added
- New storage convention - instead of using a folder on H:/ named after the version, LeviKeys now uses a folder called "LeviKeys Required Files" in order to put all LeviKeys files in one place.

## [2.0.0] - 2019-01-16
### Added
- Installer to handle installation of LeviKeys
- MetaKeys with naming convention M000
- Autoformatting for month names and days of the week
- Autoformatting for NEC Specific language such as NECare
- Autocorrect for over 4600 common misspellings
- M002 | Suspends LeviKeys (toggle)
- M003 | LeviKeys Help (opens quick reference sheet)
- G024A to G024AD | NECare Template Shortkeys
- G025A to G025I | Engineering Team Acronyms
- G026 | Channel Partner Call Template
- G027 | Set current window to always on top
- G028 | TSA email
- G029A to G029U | VOTS Acronyms
- G030 | "N/A"
- G031 | "Original email attached"
- G032 | "Closing as information only"
- G033 | Password Reset template
- G034 | "Customer called for update. Advised as per below notes."
- G035 | "Co-Operative Bulk Handling LTD"
- G036 | "Security Operations Group"
- H001 - H004 | Fills in timesheets for 4x4 team.

### Changed
- G018 | Minor formatting changes

### Removed
- R001 to R003 | Replaced with G030 to G031

## [1.3.0] - 2019-01-09
### Added
- LeviKeys Quick Reference Sheet
- G015 | Generates a random number between 1 and 10 (inclusive.)
- G016 | Generates a random number between options entered by the user.
- G017 | Opens Internet Explorer and browses to snapshot
- G018 | KTS Call template
- G019 | "AustralianSuper"
- S??? | Secret Shortkey
- G020A to G020AL | SAGOV Acronyms
- G021 | VOTS team email
- G022 | VOTS Config email
- G023 | VOTS Config email

## [1.2.0] - 2019-01-07
### Added
- G006 | Forwarded email to VOTS and Config teams.
- G007 | Replied to customer.
- G012 | "‽"
- G013 | "7510"
- G014 | "7510"

### Changed
- Naming convention for all shortkeys is now A000 where A is a letter pertaining to the type of shortkey.

## [1.1.0] - 2019-01-06
### Added
- LeviKeys v1.1 Documentation.

## [1.0.0] - 2019-01-06
### Added
- Remedy Exclusive Keys, Qmaster Exclusive Keys, and Global Keys.
- G001 | Opens internet explorer and browses to nebula
- G002 | Equals horizontal line
- G003 | Hyphen horizontal line
- G004 | Underscore horizontal line
- G005 | "If you require any further assistance, please don't hesitate to contact us."
- G008 | "¯\\\_(ツ)\_/¯"
- G009 | "¯&#92;\_(ツ)\_/¯"
- G010 | Copyright Symbol
- G011 | Trademark Symbol
- Q001 | Pastes email template with reference number
- Q002 | Inserts email template with placeholder for reference number
- R001 | N/A
- R002 | "Original Email Attached"
- R003 | "Closing as Information Only"
- R004 | Automatically Attaches Email in Remedy (unstable)
- R005 | Automatically selects first option for categorization (unstable)
