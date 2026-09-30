# Bee203 — Android Releases

Download page for the Bee203 Android app (APK sideload).

**This repository contains no source code.** It exists only to host signed APK
builds so they can be installed on a phone without going through an app store.

> The **"Source code (zip)"** and **"Source code (tar.gz)"** links GitHub attaches
> to every release are NOT the app. GitHub generates them automatically from this
> repository, which holds only this README. Ignore them.

## Samsung phones: turn off Auto Blocker FIRST

**Read this before you start if you have a Samsung (Galaxy) phone.** Most of them
ship with **Auto Blocker** switched on, and it will refuse the install with this
message:

> **To keep your phone and data safe, Auto Blocker prevents the installation of
> unknown apps.** You can only install apps from authorized sources such as Play
> Store or Galaxy Store.

Bee203 is not in the Play Store or Galaxy Store yet, so Auto Blocker stops it.
Turn Auto Blocker off just long enough to install:

1. Open **Settings**.
2. Tap the **search** icon at the top and search for **Auto Blocker** — that is
   quicker than hunting through the menus. (The full path is
   **Settings → Security and privacy → Auto Blocker**.)
3. Open **Auto Blocker** and turn it **off**.
4. Install Bee203 using the steps below.
5. **Turn Auto Blocker back on as soon as Bee203 is installed.** Samsung may also
   prompt you to switch it back on — say yes. Bee203 runs normally with Auto
   Blocker on; it only gets in the way during the install itself.

Auto Blocker is a Samsung-only feature. On a Pixel, Motorola, OnePlus or other
non-Samsung phone you will not see it — those phones only ask for "Allow from
this source" (step 5 under **Install**).

## Install

1. Open the newest release under [Releases](../../releases) **in Chrome on your phone**.
2. Scroll to **Assets** and tap the file ending in **`.apk`** — for example
   `Bee203-3.205.1-433.apk`. That is the app.
3. Chrome may warn that this type of file can harm your device. Tap
   **Download anyway** — that warning appears for every APK.
4. Tap the downloaded file.
5. When Android says it cannot install from unknown sources, tap **Settings**,
   turn on **Allow from this source**, go back, and tap **Install**.

If the install is refused with the "Auto Blocker" message instead, see
[Samsung phones: turn off Auto Blocker FIRST](#samsung-phones-turn-off-auto-blocker-first)
above.

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
