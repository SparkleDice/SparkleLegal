# Privacy Policy for Sparkle

**Last Updated:** April 13, 2025

This Privacy Policy describes how personal information and bot-related data ("Data") are collected, stored, used, and shared when you interact with the Discord bot "Sparkle" (the "Bot").

By adding or using Sparkle in your server or direct messages, you agree to the collection and use of information in accordance with this policy.

## Information We Collect and Store

We collect and store certain information necessary for the Bot to function correctly and provide its features. We are committed to data minimization and user privacy.

**Data Collected Automatically from Discord:**

1.  **Discord User IDs:** Your unique Discord User ID is stored to associate data (like inventory, game stats, or signatures) with your account. **User IDs are always stored in an encrypted format** (as seen in your examples like `owner_id` and `playerSignatures.p`).
2.  **Discord Server (Guild) IDs:** If you use server-specific features (like custom prefixes), the unique ID of that Discord server is stored to manage settings for that server.

**Data Provided By You or Derived From Your Commands:**

3.  **Character & Inventory Data:** If you use features related to character management or inventories (like `!invadd Player sword`), we store data you provide or generate, such as character names, virtual currency amounts (e.g., `gold`), and item details (`items` array including name, quantity, etc.).
4.  **Game Tracking Data:** If you use game tracking features, we store data related to those games, such as game identifiers/names,in-game time (`time`), session counts (`sessions`), and last played dates (`lastPlayed`), which are not connected to your User ID.
5.  **Configuration Data:** We store settings you configure, such as custom command prefixes (`prefix`, stored per Server ID) or player signatures (`playerSignatures.s`, stored per encrypted User ID).
6.  **Ephemeral Command Data:** When you issue a command (e.g., `!d20`, `!add Player sword`), the content of that specific command message is processed ephemerally (temporarily, in memory) solely to execute the requested action. **We DO NOT log or store the raw content of your command messages.** Our storage consists only of the structured data listed above, generated as a result of commands.

## How We Use Your Information

The information collected is used solely for the following purposes:

* **Providing Bot Functionality:** To enable core features like dice rolling, managing inventories, tracking game statistics, applying custom prefixes, and associating player signatures.
* **Associating Data:** To link stored data (inventory, game stats, signatures) correctly to your Discord User ID and Server ID using the encrypted IDs.
* **Processing Commands:** To understand and execute the commands you send to the Bot (ephemeral use only, no storage of the command itself).
* **Maintenance & Debugging:** To diagnose and fix errors. Error reports may contain non-personal technical information but **do not** include raw command logs or your personal data beyond potentially an encrypted User ID for context if an error is user-specific. We may use aggregated, anonymized usage statistics to monitor performance.

## Data Storage, Security, and Hosting

* **Hosting Provider:** The Bot and its data (stored, for example, in JSON files or a similar structured format) are hosted on servers provided by Cybrancee. Data storage is subject to Cybrancee's security practices and infrastructure. You can review their policies for more details.
* **Storage Format:** Data is stored in structured formats (like the JSON examples provided) necessary for the bot's operation.
* **Security Measures:** We take reasonable measures to protect your information. Notably, all stored Discord User IDs are encrypted. However, no method of transmission or electronic storage is 100% secure.
* **Off-Platform Storage:** All persistent data required for the Bot's functionality (as listed above) is stored off-platform on our hosting provider's servers.

## Data Retention

We retain stored data only for as long as necessary to provide the Bot's functionality or as required by law.
* **User-Specific Data (Inventory, Game Stats, Signatures):** Retained until you request its deletion, or potentially if you haven't interacted with the relevant features for an extended period.
* **Server-Specific Data (Prefixes):** Retained until the Bot is removed from the server or the prefix setting is changed.
* You can request deletion of your user-specific data at any time (see User Rights).

## Data Sharing and Disclosure

We do not sell, trade, or rent your personal information. Your information is only shared in the following limited circumstances:

* **Hosting Provider:** With Cybrancee, as necessary to host the Bot and store its data.
* **Legal Requirements:** If required by law, subpoena, or other legal process, or to protect our rights, property, or safety, or that of others.

## User Rights and Choices (Opt-Out)

You have certain rights regarding your data:

* **Access and Correction:** You may be able to view or modify some stored data (like inventory items) through Bot commands. For other requests or corrections, please contact us.
* **Deletion:** You can request the deletion of your user-specific data (inventory, game stats, signatures) stored by the Bot by contacting us via the email below. Please note that deleting data will prevent you from using Bot features that rely on that specific data.
* **Opt-Out of Data Storage:** You can opt-out of having specific data stored by choosing not to use the Bot features that require data persistence (like inventory management, game tracking, or setting signatures). Core functionality like basic dice rolling does not result in persistent data storage linked to your user messages.

## Children's Privacy

The Bot is not intended for use by children under the age of 13 (or the relevant minimum age threshold in your jurisdiction, e.g., 16 in the EU/UK). We do not knowingly collect personal information from children under this age. If we become aware that we have collected such data, we will take steps to delete it.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes by posting the new policy with an updated "Last Updated" date, potentially via a Bot command or support server announcement. Your continued use of the Bot after changes constitutes acceptance of the new policy.

## Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us at: **sparkledicebot@gmail.com**
