<div align="center">

<img src=".github/assets/mediami-icon.png" alt="MediAmi app icon" width="140" height="140">

# MediAmi

**A native Mac and iPad app for the media services you run yourself.**<br>
Connect your own servers and manage them from one place, with the look and speed of a built-in app.

[![Status](https://img.shields.io/badge/status-public%20beta-orange?logo=apple&logoColor=white)](https://testflight.apple.com/join/fptM7mKv)
[![Latest release](https://img.shields.io/github/v/release/mediami-app/MediAmi?label=release&color=blue)](../../releases)
![macOS 26](https://img.shields.io/badge/macOS-26-lightgrey?logo=apple&logoColor=white)
![iPadOS 26](https://img.shields.io/badge/iPadOS-26-lightgrey?logo=apple&logoColor=white)
![Price](https://img.shields.io/badge/price-100%25%20free-brightgreen)
![Privacy](https://img.shields.io/badge/privacy-no%20account%20%C2%B7%20no%20tracking-success)

![Languages](https://img.shields.io/badge/languages-EN%20%C2%B7%20ES%20%C2%B7%20FR-informational)
![Source](https://img.shields.io/badge/source-closed-lightgrey)
[![Website](https://img.shields.io/badge/web-mediami.app-0A64C8)](https://mediami.app)
[![Discord](https://img.shields.io/badge/chat-Discord-5865F2?logo=discord&logoColor=white)](https://discord.gg/DgCkXtMSC6)
[![Reddit](https://img.shields.io/badge/community-r%2FMediAmi-FF4500?logo=reddit&logoColor=white)](https://www.reddit.com/r/MediAmi/)
[![Sponsors](https://img.shields.io/badge/sponsor-optional-EA4AAA?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/finalpets)

**[Join the beta](https://testflight.apple.com/join/fptM7mKv)** · **[mediami.app](https://mediami.app)**

</div>

> This repository is the public home of MediAmi: bug reports, ideas, the roadmap and release notes.
> **The app's source code is private.** There is nothing to build here.

## What it does

- **Movies, series and music.** Browse your libraries, search and add titles, check what is
  missing, change monitoring and run searches (Radarr, Sonarr, Lidarr).
- **Indexers.** See which of your indexers work, test, add and edit them, search across all of them,
  read their statistics and keep your apps in sync (Prowlarr).
- **One dashboard.** A customizable grid of widgets: what is downloading, what is coming up,
  storage, health and more, per connection or all together.
- **Activity.** Queue, calendar, history and wanted across every connection, with downloads and
  their speed in one view (SABnzbd included).
- **Requests.** Browse, request and follow requests from Overseerr or Jellyseerr.
- **Monitoring.** See who is watching right now and how your server is playing it, with viewing
  statistics, in a dashboard you arrange (Tautulli).
- **Private by design.** MediAmi talks directly to your servers. There is no account, no
  analytics, no tracking and no server of ours. Your API keys stay in the Keychain on your device.
- **Made for the platform.** Liquid Glass design, sidebar navigation, keyboard and VoiceOver
  support, in English, Spanish and French.
- **Try it without a server.** Demo Mode fills the app with sample data.

## Requirements

- A Mac (macOS 26) or an iPad (iPadOS 26).
- Your own Radarr, Sonarr, Lidarr, Prowlarr, SABnzbd, Overseerr/Jellyseerr or Tautulli server, reachable from
  the device, and its API key.

## Status

MediAmi is in **public beta** on TestFlight, for Mac (macOS 26) and iPad (iPadOS 26), and it is not on
the App Store yet. **[Join the beta](https://testflight.apple.com/join/fptM7mKv)** (it needs Apple's free
TestFlight app). It is free, with every feature, and Demo Mode works without a server. Follow this
repository (**Watch → Custom → Releases**) to hear about new versions.

Every version's notes are in [Releases](../../releases). The releases here hold **notes only**:
there is no code and no download attached, and their tags point at this documentation repository.
Builds reach testers through TestFlight and, from 1.0.0, the App Store.

## Why MediAmi exists

MediAmi began as a homelab hobby. I have run my own servers for years, and I had always wanted to
build an app of my own but never found the time. When AI coding tools arrived I hesitated for a while,
because many people were quickly shipping apps with ideas close to mine. Then my company encouraged
us to get a Claude Code certification, and I decided to do it properly: I spent about three months
studying and applied everything I learned, best practices included, to a real project. That project
became MediAmi.

It is for the Mac and iPad, not the iPhone, on purpose. There are already plenty of iPhone apps for
this, and I manage my libraries in the Radarr, Sonarr and Lidarr web interfaces on a big screen. I am a
visual person, and on a phone I cannot see what I am doing clearly.

MediAmi is built with AI assistance (Claude Code), under my direction and review. It is closed source
for now, and I would rather say that plainly than dodge it. What you can check for yourself is the
promise: free, with every feature, no account, no tracking, and your API keys stay in the Keychain on
your device.

If MediAmi saves you time and you would like to help cover the Apple Developer Program and hosting,
there is an optional [Sponsors page](https://github.com/sponsors/finalpets). Everything stays free
either way.

## Get involved

| I want to… | Go to |
|---|---|
| Report a bug | [Open an issue](../../issues/new/choose) (bug report) |
| Suggest a feature | [Open an issue](../../issues/new/choose) (feature request), or start a [Discussion](../../discussions) if it is still an idea |
| Ask a question | [Discussions → Q&A](../../discussions) |
| Visit the website | [mediami.app](https://mediami.app) |
| Chat with the community and follow news | [r/MediAmi](https://www.reddit.com/r/MediAmi/) on Reddit |
| Chat and get help from other users | [Discord server](https://discord.gg/DgCkXtMSC6) |
| Support the project | [Sponsor on GitHub](https://github.com/sponsors/finalpets). MediAmi stays 100% free with every feature for everyone; sponsoring is optional and unlocks nothing |
| See what is planned | The roadmap board in [Projects](../../projects) |
| Read the privacy policy | [PRIVACY.md](PRIVACY.md) |
| Report a security problem | [Privately](../../security/advisories/new), see [SECURITY.md](SECURITY.md) |

**Never paste API keys, server URLs, hostnames or IP addresses** into an issue, a discussion or a
screenshot. If a log contains them, remove them first. More in [CONTRIBUTING.md](CONTRIBUTING.md).

## Not affiliated

MediAmi is an independent app. It is not affiliated with or endorsed by Radarr, Sonarr, Lidarr,
Prowlarr, SABnzbd, Overseerr, Jellyseerr or Tautulli. It does not provide, host or download any media: it only talks to
the servers you run. All product names belong to their owners and are used here only to say what
MediAmi connects to.

## Copyright

© 2026 Peter Leyva. All rights reserved. MediAmi and its source code are proprietary. The text in
this repository is published to inform users; it does not grant any license to the app.
