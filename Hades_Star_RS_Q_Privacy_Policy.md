# **Privacy Policy**  

## **1. Introduction**  
- **Overview**: This policy explains how *Hades' Star RS Q* (the "Bot") collects, processes, and shares data.  
- **Scope**: This policy applies to all users and entities interacting with the Bot.  
- **Purpose**: The Bot is a community service designed to facilitate Red Star queues, scoreboards, and related functionalities.  

## **2. Information We Collect**

### **2.1 User Preferences and Queue Data**
- The Bot stores **user-submitted preferences and configuration settings** tied to Discord user IDs.
- These preferences are used to facilitate dungeon queues, particularly where **technology levels or strategy preferences** are relevant for group formation.
- Discord IDs are used as persistent identifiers, and the Bot relies on Discord as the **authentication authority**. No attempt is made to independently verify or link Discord IDs to any real-world identity.
- This data is stored solely to enhance usability and avoid requiring users to re-enter preferences each time.
- For queue activity, the Bot creates and displays internally obfuscated identifiers derived from Discord user IDs. These identifiers are used to show queue participation consistently over time and are not linked to Discord usernames, server names, or any personal data. While the obfuscation method is designed to prevent identification, users should be aware that de-anonymization may still be possible in small or closely connected communities.

### **2.2 Webhook Event Data**
- The Bot processes event data sent by **Hades’ Star’s webhook system**, which includes JSON payloads for:
  - Red Star Started  
  - Red Star Ended  
  - White Star Started  
  - White Star Ended
- To enable this, **Discord server administrators must use the `/rse webhook` command**, which creates a webhook tied to the Bot’s application ID.
- Only data from these authorized webhooks is processed. While this setup helps limit data sources, it is not fully secure and could be manipulated by others.
- The Bot **does not have read access to message content directly**, so it must **query Discord for webhook message content** based on the webhook ID. The message is then reformatted into a human-readable form and optionally edited for clarity.
- **Visibility of the webhook messages within Discord is up to each server administrator** (i.e., whether the `data.json` posts are made in a public or private channel). However, the **data is still processed independently for use in leaderboards**, regardless of how it is displayed in Discord.

### **2.3 Aggregated Statistics and Public Leaderboards**
- The Bot aggregates event data using **obfuscated Hades’ Star identifiers**, which are stable across events but not traceable to real-world identities.
- It generates **public leaderboards and performance stats** using algorithms like Elo and experimental TrueSkill variants.
- These leaderboards are:
  - **Accessible via bot commands by any user**
  - **Publicly viewable for White Star events through a GitHub-hosted page**
- While data visibility in Discord is controlled by each server, **processed data and leaderboard outputs are public** and not restricted based on Discord channel settings.

## **3. Data Usage**  
- **Services & Automation**: Data is used for queue management, event tracking, and bot functionality.  
- **Public Data Sharing**:  
  - **Obfuscated queue data is uploaded to GitHub**, where it remains publicly accessible.  
  - **Aggregated leaderboard or analytical data is shared publicly**  
- **Third-Party Access**:  
  - Other bots and services **may access publicly available data on GitHub**.  
  - **No personally identifiable data is collected, processed, or shared**.  

## **4. Data Retention & Security**  
- **User preferences are stored** for customization.  
- **Obfuscated queue data remains on GitHub indefinitely**, and previous revisions may be retained by GitHub.  
- **Webhook data is retained for an undetermined period, typically no longer than one year**.  
- **Once published, public data cannot be removed upon request**, as it is outside the Bot’s control and may be aggregated by other services.  
- **There is no method to associate a Discord ID with an obfuscated Hades' Star ID**; user identity cannot be verified.  

## **5. Responsibility & Liability**  
- **Hades’ Star determines webhook content**; the Bot only processes what is received.  
- **Corporations voluntarily enable webhooks** and can disable them at any time.  
- **Disputes regarding webhook data should be directed to the corporation that enabled the webhook**, though resolution is not guaranteed.  
- **GitHub may retain historical data, including raw data or scoreboards, beyond the Bot’s control**.  
- **The Bot does not process any personal or sensitive data** and has no method to verify user identities between Discord and Hades’ Star.  

## **6. User Rights & Opt-Out**  
- **Obfuscated queue data cannot be modified or deleted** after publication.  
- **Users may stop interacting with the Bot at any time** to prevent their data from being included in queue aggregation. However, data received from a Hades’ Star webhook enabled by a corporation may still be processed, regardless of user interaction with the Bot.
- **Corporations may disable webhooks or remove the Bot from the relevant channels** to stop data collection.
- Internally obfuscated identifiers shown in public queue logs are derived from Discord user IDs. These are not linked to usernames or server details, and the Bot does not authenticate users or verify their identity. While the obfuscation is designed to limit identifiability, absolute anonymity cannot be guaranteed in small or highly active communities.


## **7. Limitation of Liability**  
- **The Bot is provided "as-is" without warranties of any kind**, express or implied.  
- **The developers of the Bot shall not be held liable** for any damages, losses, or issues arising from the use of the Bot, including but not limited to:  
  - Data inaccuracies  
  - Service disruptions  
  - Third-party access or misuse of publicly available data  
- **By using the Bot, you agree to hold the developers harmless** from any claims or liabilities related to its use.  

## **8. Disclaimers**  
- **The Bot is not responsible for the accuracy of third-party data, including webhook content from Hades' Star**.  
- **Other bots and services may use publicly available aggregated data, but no personally identifiable data is processed or shared.**  
- **Privacy Considerations:** Users concerned about data collection under privacy laws should be aware that this Bot processes **publicly available data that is not personally identifiable**. The Bot does not collect, store, or process sensitive information and does not perform any form of identity verification. It assumes that the Discord IDs and obfuscated Hades’ Star IDs provided by their respective platforms are correct. The Bot uses Hades’ Star obfuscated IDs **only to differentiate users with the same name** and does not attempt to link them to real-world identities. Any identification or association of users is determined solely by the **services providing the data**, such as Discord or Hades’ Star. If you have concerns about how your information is handled, we recommend addressing them directly with the **platforms responsible for providing user identification**, as this Bot has no control over or ability to modify the data supplied by those services.
- **Privacy Considerations:** Users may choose to associate their Discord ID with their Hades' Star name, but this association is **self-reported** and **not verified by the Bot**. Any verification or approval of these links is the responsibility of **Discord server administrators**, not the Bot. The Bot does not authenticate, enforce, or guarantee the accuracy of any user-provided identity links. The Bot uses Hades’ Star obfuscated IDs **only to differentiate users with the same name** and does not attempt to link them to real-world identities. Any identification or association of users is determined solely by the **services providing the data**, such as Discord or Hades’ Star. If you have concerns about how your information is handled, we recommend addressing them directly with the **platforms responsible for providing user identification**, as this Bot has no control over or ability to modify the data supplied by those services.

## **9. Changes to the Policy**  
- **This policy may be updated** periodically.  
- **Updates will be posted on the GitHub repository** where this agreement is published. Continued use of the Bot after changes take effect constitutes acceptance of the updated policy.  

## **10. Contact**  
For inquiries, contact **[caprican@tsl.rocks](mailto:caprican@tsl.rocks)**.  
