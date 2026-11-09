---
title: Privacy Notice
permalink: /privacy/
---

# Supernova Privacy Notice
Last updated: 2026-11-10

## Who we are
Supernova is made by Auzzitech, an independent developer based in Australia.
Privacy enquiries and complaints: Email supernovaclient@outlook.com.

## The short version
Supernova has no servers, no accounts and no analytics. We do not receive or store personal information about you through Supernova. Everything it saves stays on your PC. When you use it, it talks directly to Microsoft, Mojang, Fabric and Modrinth, which are listed below.

## What is stored on your PC
In the Supernova data folder (on Windows: %APPDATA%\Supernova):
- your accounts: Minecraft name, UUID, skin link and your login tokens (encrypted);
- your settings, profiles, mod lists and logs (launcher.log, with tokens and your Windows user name removed);
- the game files, mods, worlds and skins you download or create.
Nothing in this folder is sent to us.

## What is sent over the internet, and to whom
- When you log in with Microsoft: to Microsoft (login.microsoftonline.com), Xbox (xboxlive.com) and Mojang (api.minecraftservices.com). Your sign-in happens on Microsoft's page, and the tokens needed to prove you own Minecraft: Java Edition are exchanged with them.
- When you install or launch a version: to Mojang (mojang.com, minecraft.net) and Fabric (fabricmc.net, repo1.maven.org). They receive a request for the game, library and runtime files, which includes your IP address as with any web request.
- When you browse or install mods: to Modrinth (api.modrinth.com, cdn.modrinth.com). They receive your search and the mod you pick.
- When your head is shown: to Mojang (textures.minecraft.net), a request for your skin file.
Apart from what each service needs to do its job (such as your sign-in), Supernova adds only a User-Agent that names the launcher and its version. Supernova only connects to addresses on a fixed list of these services, over HTTPS.

## Overseas processing
Microsoft, Mojang, Fabric and Modrinth are international services. They may process and store information in other countries, including outside Australia, under their own privacy practices. Supernova does not choose where they do this.

## What Supernova does not do
Supernova itself contains no telemetry, analytics, advertising or tracking code, and has no automatic crash reporting and no update checker (you install updates yourself). It does not send anything to us or to any server we run, and it does not sell or share data. Its built-in client mod does not connect to the internet.

## Third-party services and software
We do not operate Microsoft, Xbox, Mojang, Fabric or Modrinth, and we cannot control their privacy practices, security or how long they keep information. Read their own privacy policies.
Minecraft itself (made by Mojang), the servers you join, and any mods or resource packs you install are also made by other people and may collect data about you. Supernova does not control that. Like every launcher, Supernova tells the game its own name and version ("Supernova" and its version number).

## Logs and support
launcher.log stays on your PC. Supernova removes login tokens and your Windows user name from it, but check it before you send it to anyone. Logs and crash reports made by the game or by Java are not made by Supernova, so check those too. If you contact us and send a log or message, we use it only to reply to you and to fix the problem, and we delete it when it is no longer needed.

## How your login is protected, and the limits
- Your login tokens are encrypted on your PC. On Windows they use Windows data protection (DPAPI), which ties them to your Windows account so another Windows user cannot read them. On other systems they use AES-256-GCM with a key file next to the accounts file.
- Tokens are removed from Supernova's logs.
- Encryption protects the saved file. It does not protect against malware running on your PC, or against someone using your signed-in Windows account. While Supernova runs, the tokens are held in memory, and when you play, Minecraft requires Supernova to give the game a login token as a launch argument, so software running as you could read it.
- We take reasonable measures to protect information stored on your PC, but no software or storage method can guarantee absolute security.

## Keeping and deleting your data
Your data stays on your PC until you remove it.
- Erase: Legal, then Your data, then "Erase accounts and settings" removes your saved accounts and tokens, the key file, settings, logs and cached skins from Supernova's data folder. Your game files and worlds are not touched.
- Delete the data folder and uninstall the app to remove the launcher data stored there. This does not guarantee that every trace is gone: Windows, backups (such as File History or OneDrive folder backup), the Recycle Bin and security software may keep their own copies.
- Microsoft permission: your login permission for Supernova stays active at Microsoft until you revoke it at https://account.live.com/consent/Manage.
- Sign out: removing an account in the launcher deletes its tokens from the data folder.

## Children
Minecraft accounts for children are managed by Microsoft's family settings. Supernova does not collect any information itself, including from children.

## Access, correction and complaints
We hold no personal information about you through Supernova, so there is nothing to access or correct on our side. If you have emailed us, you can ask us what we hold, to correct it, or to delete it. To make a privacy complaint, email us (see above). We aim to reply within 30 days. If you are not happy with our response, you can complain to the Office of the Australian Information Commissioner (https://www.oaic.gov.au).

## Australian privacy law
We are an independent developer, and the Privacy Act 1988 (Cth) may or may not apply to us. We aim to follow the Privacy Act and the Australian Privacy Principles in any case.

## Changes to this notice
This notice may change when Supernova's features, dependencies or the third-party services it uses change. The date above shows the latest version. If a change matters, Supernova shows you the new version and asks you to agree again.

## Not affiliated
Supernova is an unofficial third-party launcher. It is not made, approved or endorsed by Mojang or Microsoft.
