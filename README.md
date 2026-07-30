# Street Kittys Studio (SKS)

**Street Kittys Studio** is a modular creative, business, nonprofit, and AI-assisted desktop software suite. It uses a shared **Studio Core** and installable modules designed to work together through one Street Kittys Studio launcher.

> **Current status:** Private Beta — version 1.0.0

## Project goals

Street Kittys Studio is designed to make professional software tools easier to install and use, with graphical workflows for regular users and no command-line requirement for normal installation, updates, repairs, or troubleshooting.

## Studio architecture

- **Studio Core** — shared launcher, settings, updates, notifications, AI configuration, Shared Assets, and Integrity records
- **Creative tools** — Book, Image, Music, Video, Product, and related production workflows
- **Development tools** — website, desktop app, mobile app, and game development
- **Business tools** — Assistant Studio, office tools, scheduling, email, forms, databases, shipping, and accounting
- **Mission tools** — grants, volunteers, events, donors, programs, governance, compliance, and impact reporting

Modules may be released at different times and may have separate platform packages.

## Current platform

Initial beta packages are intended for supported **64-bit Linux Mint systems (`amd64`)**. Other operating systems and architectures may be added as separate release files when they are tested and approved.

## Downloads and releases

Installers belong on the repository's **Releases** page rather than in the normal source-file area.

Beta releases should use this format:

- Tag: `v1.0.0-beta-rXX`
- Title: `Street Kittys Studio 1.0.0 Beta — rXX`
- Mark the release as a **pre-release**
- Attach the correctly named installer and its SHA-256 checksum
- Include supported operating system, architecture, included modules, known limitations, and upgrade notes

## Installation safety

Before installing a beta release:

1. Confirm that the installer came from the official Street Kittys Studio repository.
2. Compare the downloaded file's SHA-256 checksum with the published checksum.
3. Read the release notes and Beta Evaluation License.
4. Back up important project data before testing beta software.

## Security and privacy

Never commit or upload:

- API tokens or passwords
- Private signing keys
- Customer or donor information
- Private configuration files
- Personal financial or medical information
- Unredacted logs containing private data

Release packages should be scanned, checksummed, and tested before publication. Production update catalogs must be signed with the trusted Street Kittys release key. The private signing key must never be stored in this repository.

## Licensing

Street Kittys Studio is currently proprietary beta software distributed under a Beta Evaluation License. No open-source license has been granted. Unless a release explicitly states otherwise, all rights are reserved.

## Repository owner

Copyright © Street Kitty Boutique, Inc. and the Street Kittys Studio project.
