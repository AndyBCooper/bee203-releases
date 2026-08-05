# Bee203 — Android Releases

Download page for the Bee203 Android app (APK sideload).

**This repository contains no source code.** It exists only to host signed APK
builds so they can be installed on a phone without going through an app store.

> The **"Source code (zip)"** and **"Source code (tar.gz)"** links GitHub attaches
> to every release are NOT the app. GitHub generates them automatically from this
> repository, which holds only this README. Ignore them.

## Install

1. Open the newest release under [Releases](../../releases) **in Chrome on your phone**.
2. Scroll to **Assets** and tap the file ending in **`.apk`** — for example
   `Bee203-3.125.1-309.apk`. That is the app.
3. Chrome may warn that this type of file can harm your device. Tap
   **Download anyway** — that warning appears for every APK.
4. Tap the downloaded file.
5. When Android says it cannot install from unknown sources, tap **Settings**,
   turn on **Allow from this source**, go back, and tap **Install**.

## One-time: you will see two Bee203 icons

As of **v3.125.0+308** the app id changed from `com.example.bee203` to
`com.bee203.app`, and builds are now signed with a proper release key instead of
Android's shared debug key.

Android therefore treats this as a **different app**, not an upgrade: it installs
alongside the old one instead of replacing it. Sign in on the new one, check your
data is there, then delete the old icon.

This happens **once**. Later updates install over the top normally and keep your
data.

The web app is at [bee203.com](https://bee203.com) — you can also reach this page
from **Settings → Get the Android app**.
