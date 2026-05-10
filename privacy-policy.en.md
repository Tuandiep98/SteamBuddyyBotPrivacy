# Privacy Policy — Steam Buddy

**Tiếng Việt:** [Chính sách bảo mật (Vietnamese)](privacy-policy.vi.md)

**Document version:** 1.0  
**Effective date:** [10/05/2026]  
**Last updated:** [10/05/2026]

Steam Buddy is a Telegram bot that helps you discover Steam games, read gaming news, and receive optional notifications. This policy explains how we process personal data when you use the bot.

---

## 1. Data controller

**[DANG TUAN DIEP]**  
**Contact:** [tuandiep98usa@gmail.com] · [OPTIONAL: Telegram / @tuandiep98]

If you are in the European Economic Area (EEA), the United Kingdom, or Switzerland and require a GDPR representative, [FILL IN IF APPLICABLE: name and EU/UK representative address].

---

## 2. Scope

This policy applies to your interaction with the **Steam Buddy** bot on Telegram. It does not apply to other websites or apps unless we state otherwise later.

---

## 3. Data we process

### 3.1 From Telegram

When you interact with the bot, Telegram provides basic account information you have agreed to share with the bot under your Telegram settings, including at least:

- **Telegram identifier** (`telegram_id`) — to recognise your account and store settings.
- **Username** (`username`) and **display name** (`first_name`) if available — for display and profile sync in the bot.

### 3.2 From Steam (when you link your account)

If you send a Steam URL or Steam ID to link your account, we process:

- **Steam ID** and **public profile data** obtained via the Steam Web API / public data you allow to be visible (e.g. display name, avatar, public stats — depending on your Steam privacy settings).

We **do not** ask for your Steam password.

### 3.3 In-bot settings and preferences

For example: interface language, notification time zone, digest send time, daily digest on/off, game genres of interest (if any), and per-day feature usage (to enforce free-plan limits).

### 3.4 Paid plan (Premium) — Telegram Stars

When you purchase a plan via Telegram Stars, we process information needed to activate and maintain your plan (e.g. transaction / plan reference, duration). Payment details are handled by **Telegram** under Telegram’s terms.

### 3.5 In-bot activity history

For example: history of notifications sent, game interests, and “random game” history — to personalise features and operate the service.

### 3.6 Content sent to artificial intelligence (AI)

Some features send **text you type or context generated in the bot** (e.g. game titles, search queries, short descriptions) to AI providers to produce suggestions or replies. That content may relate to your gaming preferences.

### 3.7 Data we do not intentionally collect

We do not require your home address, government ID, or other special-category data to use the bot. Please **do not** send such information through the bot.

---

## 4. Purposes of processing

- Operate the bot and respond to your commands.
- Link Steam, show profiles, and related features.
- Personalise suggestions, digests, and notifications (when enabled).
- Apply free-plan limits and manage Premium subscriptions.
- Improve reliability and security (including minimal technical logging if any).

---

## 5. Legal bases (summary)

Depending on your region, legal bases may include: performance of a contract / terms of service, **consent** (e.g. enabling notifications, linking Steam), and/or **legitimate interests** (operating and securing the service). [FILL IN: legal review if you fully target the EU/UK market.]

---

## 6. Third parties and subprocessors

| Party             | Role                                                                                                                                    |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Telegram**      | Messaging platform; processes account data and Stars payments per Telegram’s policies.                                                  |
| **Valve / Steam** | Steam Web API and public Steam data.                                                                                                    |
| **AI providers**  | The bot may call **DeepSeek** and/or **Google (Gemini)** APIs to process prompts. Data transferred is subject to each provider’s terms. |

Reference links (may change over time):

- [Telegram Privacy Policy](https://telegram.org/privacy)
- [Steam Privacy Policy](https://store.steampowered.com/privacy_agreement/)
- [Google Privacy Policy](https://policies.google.com/privacy)

---

## 7. Storage

User data is stored in a **database controlled by the bot operator** (default in this project: SQLite at the path set in `DATABASE_URL`). Retention: **until you delete data through the bot or we delete it under internal policy / legal obligation** [30 days — adjust if this describes a different retention rule].

**Note on AI:** Deleting data in the bot **does not** automatically delete data that an AI provider may retain under its own policies. We do not control provider-side logs.

---

## 8. Deleting data and your rights

### 8.1 In-bot deletion (self-service)

You can send **`/delete_user_data`** or **`/delete-user-data`**. The bot will ask for **confirmation** (inline buttons). After you confirm:

**Removed or cleared (as implemented in the current software):**

- Records of sent notifications, game interests, and random-game history linked to your account.
- Steam link and stored Steam profile snapshot in the bot.
- Username / display name stored in the bot (reset to empty / default).
- Notification settings, time zone, bot language, and daily usage counters — reset to defaults.

**Retained (important):**

- **Premium / payment-related records** in the bot (to preserve entitlements you paid for). If your plan is still valid, after **`/start`** the bot may **re-apply** Premium based on remaining subscription data.

**Note:** A **Telegram ID** user row may still exist as a minimal “shell” after deletion for subscription sync and technical consistency; personalised fields above are cleared or reset.

### 8.2 Other requests

You may request access, correction, or additional deletion via the **email / contact channel** in Section 1, within applicable law. Response time: [30 days].

---

## 9. Security

We apply reasonable measures to protect data (restricted access, secure storage on the server running the bot). No transmission or storage method is perfectly secure.

---

## 10. Children

The service is intended for users who meet **Telegram** and local age requirements. We do not knowingly collect data from children below the minimum age in your jurisdiction.

---

## 11. Changes to this policy

We may update this document. A new **effective date** will appear at the top. For material changes, we will give reasonable notice (e.g. in-bot message or updated policy link).

---

## 12. Contact

Questions about this policy: **[tuandiep98usa@gmail.com]** [OPTIONAL: · Telegram @tuandiep98]

---

_This English version is provided for convenience. The Vietnamese version ([privacy-policy.vi.md](privacy-policy.vi.md)) is the primary version for users in Vietnam; if there is a conflict, the Vietnamese text prevails unless your local law requires otherwise._
