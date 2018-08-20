Sitepackage for the project "Mainzific Rim"
===========================================

The package serves as a base for TYPO3 v8 sites used in the Mainzific Rim adventure.
Young students solve missions in order to save Mainz from a Dino attack and become Certified TYPO3 editors
doing so.

The package contains

- the bootstrap package as base for FE output
- the news extension
- an image in fileadmin to start with
- initial content (pages, content elements, necessary sys-folders)
- a preconfigured BE usergroup designed for editors
- a BE user (editor:editor) that uses the group and serves as start
- a BE user (bob.bernsteiner:you_must_not_forget_your_password) that is a base for one of the missions
- a preconfigured BE usergroup designed for news editors
- a preconfigured FE usergroup   

How to install

- set up a TYPO3 instance as usual
- include the extension (via composer or download)
- go to ExtensionManager, activate the extension.
    - note: bootstrap_package and news get activated, too. No singe activation needed.
- when you get logged out, use the user root:root to gain login immediately.
- recreate your own root user, or change the password for root
    - note: do the one or the other, don't leave this temporary user active!
