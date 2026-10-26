# Mac Tools downloads

[Download the latest Mac Tools release](https://github.com/diamondplated/mac-tools-releases/releases/latest)

Mac Tools is one native Mac app that installs, opens, updates, and configures four apps:

| App | What it does | Requires |
| --- | --- | --- |
| DockPeek | Live Dock window previews, switching, and browser tabs | macOS 14+ |
| ScreenWren | Screenshots, markup, redaction, and text recognition | macOS 26+ |
| ScrollSplit | Mouse-wheel direction and speed without changing trackpad gestures | macOS 14+ |
| LinkRoutes | Send websites to chosen browsers and profiles | macOS 14+ |

It also includes six diagnostics that run inside the app: Permission Doctor, Startup Detective, SleepPeek, SpaceWatch, HogWatch, and NetPeek. Mac Tools itself requires macOS 14 or newer.

All four apps are included in the download, so installing them works offline. Open Mac Tools and choose **Overview** to install, update, or open each one.

Releases are locally signed and **not notarized**. They use the project's persistent local certificate, so another Mac may ask you to approve the app in System Settings → Privacy & Security the first time you open it.

Mac Tools updates itself automatically and verifies the signed update feed and downloaded archive against its embedded release key. After it updates, choose **Update** in Overview to install the newer versions of your apps.

The standalone ScreenWren releases and Homebrew cask are no longer updated; ScreenWren now ships only in Mac Tools.

This repository contains public downloads, release metadata, and update feeds. Application source is maintained separately in a private repository. Signing keys and credentials are not published. To report a security problem, see [SECURITY.md](SECURITY.md).
