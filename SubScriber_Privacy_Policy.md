# Privacy Policy

## **1. Introduction**
This Privacy Policy describes how SubScriber (the "Bot") handles data. The Bot is proprietary, non-commercial, and intended to automate Reddit post sharing on Discord with minimal data retention.

## **2. Data Collected**
- **Configuration Data**:
  - Discord guild and channel IDs
  - Subreddit name
  - Webhook URL (for posting)
  - Discord user ID (who configured the subreddit)
- **Usage**: Stored locally and used only to operate the bot.

## **3. Data Not Collected**
- The Bot does **not** collect:
  - Message content
  - Discord usernames or profiles
  - Email addresses or identifying personal information
  - Sensitive or private user data

## **4. Use of Reddit Content**
- Posts are retrieved from Reddit’s public API.
- Content may include titles, usernames, flair, and images — all from publicly visible Reddit posts.

## **5. Data Retention**
- Configurations persist until removed via `/reddit remove` or system cleanup.
- Webhook and post tracking is maintained only as needed for functionality.
- The Bot does not retain logs of user actions or past content after posting.

## 6. Security Measures

- Stored configuration data is kept in local SQLite databases without encryption.
- This data is limited to non-sensitive configuration information and is not intended to include personal or identifying data.
- No guarantees are made regarding the security of this data.
- The Bot is hosted on a system that may run other applications or cloud services, but it does not intentionally transmit stored bot data to any external services.

## **7. Public Content Notice**
- Reddit content may be offensive or unmoderated.
- Users are responsible for configuring subreddits appropriately for their communities.

## **8. Opt-Out and User Control**
- Users may remove subreddits at any time using `/reddit remove`.
- Admins may disable or remove the Bot to cease all functionality.

## **9. Limitation of Liability**
- The Bot’s developer is not responsible for:
  - Reddit content or user behavior
  - Misuse of webhooks or content shared via Discord
  - Errors or omissions in Reddit data
- By using the Bot, you agree to hold the developer harmless from any associated claims or liabilities.

## **10. Policy Updates**
- This policy may be revised over time. Use of the Bot after changes constitutes acceptance of the revised terms.

## **11. Contact**
Please reach out via the GitHub repository issues page or support email if you have questions.
