
![Legcord](https://github.com/user-attachments/assets/f7b007d4-44fa-4c88-96e4-0a448b568b5d)

# Features

- **Standalone client**

   Legcord is built as a standalone client and doesn't rely on the original Discord client in any way.

- **Various mods built-in**

   Enjoy [Vencord](https://github.com/Vendicated/Vencord), [Equicord](https://github.com/Equicord/Equicord), [Shelter](https://github.com/uwu/shelter) and their many features, or have a more vanilla experience, it's your choice!

- **Themes**

   Legcord natively supports theming of the entire app, you can easily import BetterDiscord themes and manage them

- **Made for Privacy™**

   Legcord automatically blocks all of Discord's trackers; even without any client mods, you can feel safe and secure!

- **Supports Rich Presence**

   Unlike other clients, Legcord supports rich presence (game activity) out of the box thanks to [arRPC](https://arrpc.openasar.dev).

- **Mobile support**

   Legcord has **experimental** mobile support for phones running Linux such as the PinePhone. While this is still far from an ideal solution, we're slowly trying to improve it.

- **Much more stable**

   Legcord is using a newer build of Electron than the stock Discord app. This means you can have a much more stable and secure experience, along with slightly better performance.

- **Cross-platform support!**

   The base Legcord client was originally created for AArch64 Linux devices since Discord doesn't support them. We soon decided to support every platform that [Electron supports](https://github.com/electron/electron#platform-support)!

- **Unjustified ban bypassing**

   Blisscord is big on freedom of speeh/expression, and is also aware of how excruciating these ban appeals are (especially with Discord's in-house support team), so Blisscord will work to allow users to still use their disabled accounts, and still access servers that have banned them, we will use a custom client-side automatic moderation system to ensure that this bypass feature isnt abused by those deserving of their ban(s).

- **Disboard sidebar**

  Browse servers in Disboard while still comfortably sitting inside of the application.

- **Better VC Features**

  Like a better Watch Together etc.
  
# How to run/install it?

## Packaging status

[![Packaging status](https://repology.org/badge/vertical-allrepos/legcord.svg)](https://repology.org/project/legcord/versions)

### Windows

You need to use [pre-built installers](https://www.legcord.app/download).

### Flatpak

Not available yet.

### Debian, Ubuntu and Raspbian repository

Not available yet.

### Snap package

Not available yet.

### Winget Package

Not available yet.

### Scoop package

Not available yet.

### AUR Package

- [legcord-git](https://aur.archlinux.org/packages/legcord-git) Built locally against dev branch

### Homebrew repository

LegCord is also available on the [Homebrew Cask](https://github.com/Homebrew/homebrew-cask) repo

```zsh
brew install --cask legcord
```

### FreeBSD

You can also get Legcord running on FreeBSD by following [these instructions](https://gist.github.com/axyiee/4d29c982ac85d5d26f98a51040b5de37).

### Pi-Apps

Not available yet.

### Pre-built binaries

 Check the **releases tab** for precompiled packages for Linux, Windows, and macOS.

### Compiling

 Alternatively, you can run Legcord from source ([NodeJS](https://nodejs.dev) and [pnpm](https://pnpm.io/installation#using-npm)) are required:

 1. Clone Legcord repo: `git clone https://github.com/Legcord/Legcord.git`
 2. Run `pnpm install` to install dependencies
 3. Build with `pnpm run build`
 4. Compile/Package with `pnpm run package`

# FAQ

## Do you have a support Discord?

[![Discord Server](https://dcbadge.vercel.app/api/server/TnhxcqynZ2)](https://discord.gg/TnhxcqynZ2)

## Will I get banned for using this?

- You are breaking [Discord ToS](https://discord.com/terms#software-in-discord%E2%80%99s-services) by using Legcord, but no one has been banned from using it or any of the client mods included.

## How can I access the settings?

- Open Discord settings and there should be a button `Legcord Settings` button with a white Discord icon, you can also right click on the tray icon and click `Open Settings`

## How does this work?

- We utilize the official web app and package it within Electron. While this approach may seem familiar, our focus is on delivering a truly customized and enhanced experience. Unlike many others, we provide seamless integration for loading themes and mods without the need for installers or injectors. You can easily enable transparency effects and adopt Windows' Fluent Design, offering a modern and sleek interface. Though it's fundamentally a web wrapper, we have implemented numerous optimizations and patches to ensure a smooth and tailored experience for you.

## Where can I find the source code?

- The source code is on [GitHub](https://github.com/Legcord/Legcord/).

## Where can I translate this?

- Translations are done using our [Weblate page](https://hosted.weblate.org/projects/Legcord/Legcord/).

# Credits

- [Legcord UI design, branding, and a few features](https://github.com/kckarnige)
- [OpenAsar](https://github.com/GooseMod/OpenAsar)
- [arRPC (for Rich Presence)](https://github.com/OpenAsar/arrpc)
- [electron-builder](https://electron.build)
  
Discord is trademark of Discord Inc. Legcord is not affiliated with or endorsed by Discord Inc.
Legcord is not affiliated with or endorsed by ARM Limited.
