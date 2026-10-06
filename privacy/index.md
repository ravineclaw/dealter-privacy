---
layout: default
---

# Privacy Policy: The De-Alter

**Last updated: October 5, 2026**

The De-Alter ("the Bot") is a Discord moderation bot used by Minecraft tier-testing communities (McTiers and Subtiers). This policy explains what data the Bot collects, how it is used and shared, how long it is kept, and how you can ask for it to be corrected or deleted.

Contact: **dealter@ravineclaw.dev**

## 1. What data we collect

**From tier-test result messages.** A separate test bot posts each finished tier test as an embed in a log channel that a server admin has selected. From those embeds the Bot stores:
- the tested player's Discord user ID
- the tested player's Minecraft UUID and username
- the test date, and links to the source and result messages

**From Discord's moderation data.** For servers in the participating networks, the Bot stores ban records: Discord user ID, server ID and name, ban reason and timestamp.

**To operate.** The Bot also stores:
- Discord user IDs of Bot admins
- channel IDs of the input, output and resolution-log channels
- resolution logs: the staff member's user ID, the outcome, and the reason they gave
- a short-lived cache of Minecraft UUID status lookups from the McTiers and Subtiers public APIs

**What we do not collect.** The Bot does not store the text of ordinary messages, direct messages, presence or activity, email addresses, passwords or any login credentials. It only reads messages posted by the configured test bot in channels an admin has set as input channels, and it ignores all other messages.

## 2. How we use it

Only to provide the Bot's moderation function: matching identifiers in test and ban records so staff can review possible alt accounts or ban evasion, and showing the result to staff in staff-only channels. Staff decide what action, if any, to take. The Bot takes no punitive action by itself.

We do not use the data for advertising or marketing, sell or license it, or use it to train machine learning or AI models. We do not contact users, on Discord or elsewhere, using this data.

## 3. Who sees it

- Staff of the servers where the Bot is configured see the alert embeds, which show linked accounts and ban information.
- Ban information from one participating server may be shown to staff of other participating servers in the same network, so they can check for ban evasion.
- We do not share data with data brokers, advertisers or other third parties, except where the law requires it.

## 4. Retention

- Test and ban records are kept while they are needed for the Bot's moderation purpose, and for as long as the Bot operates in the relevant servers.
- Ban records are refreshed from Discord, so a lifted ban is dropped from the Bot's records when they are next refreshed.
- Cached UUID lookups are cleared automatically after a short time.
- All data tied to a person is deleted when they ask us to (see Section 6).
- If the Bot stops operating, we delete the stored data.

## 5. Security

Data is held in a private database on the Bot operator's server. Access is limited to the operator. If we learn of unauthorized access to this data, we will notify Discord and affected users as required.

## 6. Your choices: access, correction and deletion

You can ask us to show you, correct or delete your data at any time. Email **dealter@ravineclaw.dev** from any address and include your Discord user ID and, if you have one, your Minecraft username or UUID. We may ask you to prove the Discord account is yours (for example by messaging us from it).

We will act on a request within 30 days. A deletion removes your test records, ban records, admin entries and cached lookups, replaces your ID in resolution logs with "deleted", and adds your IDs to a block list so a later resync does not bring the records back. The block list holds only the IDs.

Server admins can stop the Bot reading a channel with `/removeinput`, or remove the Bot from their server at any time.

To report a problem with the Bot or its use, email the same address.

## 7. Children

The Bot is only for use on Discord, which requires users to be at least 13 (or older where local law says so). We do not knowingly collect data from anyone under that age. If you believe we have, email us and we will delete it.

## 8. Changes

We may update this policy. The date at the top shows the latest version, and material changes will be noted here.

## 9. Contact

dealter@ravineclaw.dev
