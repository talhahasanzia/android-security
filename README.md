# Android Security
Following are the key areas where security needs a little bit extra effort while developing android apps. Each will be discussed in details in their related project. These are:

- **Root Detection:** Allows devices/apps to access system secured data or files. How can we prevent it?
- **Persistent Data:** Any data whether in file, shared preferences or in database, can be accessed if not secured.
- **Logs:** Apps often show logs revealing sensitive data even while apps are released on Play Store.
- **System Screenshots:** System takes screenshots of apps whenever app switcher show preview without user or developer aware of the fact.
- **Backup Theft:** There is a allowBackup tag in Manifest, which can be set false, but does it really works?
- **Tap-jacking:** Hijacking user taps and perfom deceptive operations. How to prevent this?
- **SSL Pinning:** Your network request on HTTPS are not secured unless pinned by SSL keys provided by back-end.
- **TLS:** Older Android devices did not have TLS support, the newer devices have TLS support, but needs to be enabled manually in apps.
- **Activity Manager:** Any activity from your app can be launched using adb commands directly. How you can secure them?
- **Securing API Keys:** Some keys needs to be shipped with the app and are often placed in constants, these can be accessed just by decompilation.
- **Proguard/DexGaurd:** Securing your app source from decompilation using tools like Progaurd and DexGaurd.
