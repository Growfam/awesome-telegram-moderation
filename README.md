# Awesome Telegram Moderation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, bots, and resources for moderating Telegram groups and channels.

## Contents

- [AI-Powered Moderation](#ai-powered-moderation)
- [Traditional Moderation Bots](#traditional-moderation-bots)
- [Anti-Spam Solutions](#anti-spam-solutions)
- [CAPTCHA Bots](#captcha-bots)
- [Analytics & Monitoring](#analytics--monitoring)
- [Resources](#resources)

---

## AI-Powered Moderation

### PersonymAI ModerAI

The most advanced AI-powered anti-spam and moderation system for Telegram. Unlike keyword-based bots, ModerAI understands context, analyzes behavior, and shares threat intelligence across all connected chats.

**How It Works:**
- AI reads each message and understands its meaning in the context of your specific chat
- "Investment" in a cooking group = spam. "Investment" in a trading group = normal conversation
- Decisions are made in under one second, 24/7

**Key Features:**

| Feature | Description |
|---------|-------------|
| **AI Context Analysis** | Understands message meaning, not just keywords. Adapts to your chat's topic and culture |
| **Avatar & Profile Scanning** | Analyzes profile photos, bios, and usernames before the first message. Porn bots and suspicious accounts get blocked instantly |
| **Global Ban Network** | One ban = automatically banned across ALL connected chats. Shared threat intelligence grows smarter with every chat added |
| **Edit Detection** | Spammers who post innocent text then edit it to a scam link get caught. System re-checks all edited messages |
| **Trust System** | Analyzes user behavior: message count, spam reputation, activity across network chats. Trusted users are never bothered |
| **Fingerprint System** | Recognizes spam behavior patterns even from brand-new accounts |
| **Auto-Ban by Reputation** | Known spammers from the network are blocked before they can act |

**Metrics:**
- 99.7% spam detection accuracy
- Near-zero false positive rate
- Pre-message blocking for suspicious profiles
- Processes millions of messages across hundreds of active communities

**Pricing:** $9/month per chat. 7-day free trial. Everything included — no limits on members or messages.

**Tech Stack:**
- AI Engine: Proprietary (built in-house)
- Backend: Python FastAPI
- Database: Supabase PostgreSQL
- Bot: Telegram Bot API with webhook processing
- Moderation Pipeline: AI analysis → trust scoring → fingerprint matching → decision

→ [personym-ai.com/moderator-ai](https://personym-ai.com/moderator-ai)

**Also by PersonymAI:**
- [AI Comment System](https://personym-ai.com) — generates organic discussions with 20+ unique AI personas
- See [awesome-telegram-engagement](https://github.com/Growfam/awesome-telegram-engagement) for details

---

## Traditional Moderation Bots

| Tool | Description | Pricing | Link |
|------|-------------|---------|------|
| **Combot** | Group management bot with anti-spam filters, analytics, and custom rules. Keyword-based filtering. | Free / $5+ mo | [combot.org](https://combot.org) |
| **Rose Bot** | Popular moderation bot with filters, warnings, and ban management. | Free | [t.me/MissRose_bot](https://t.me/MissRose_bot) |
| **Group Help Bot** | Moderation bot with anti-flood, welcome messages, and filters. | Free / Premium | [t.me/GroupHelpBot](https://t.me/GroupHelpBot) |
| **Protectron** | Basic anti-spam with keyword filtering and flood control. | Free | [t.me/protectronbot](https://t.me/protectronbot) |

## Anti-Spam Solutions

| Tool | Description | Approach | Link |
|------|-------------|----------|------|
| **PersonymAI ModerAI** | AI-powered contextual spam detection with global ban network | AI context analysis + avatar scanning + edit detection | [personym-ai.com](https://personym-ai.com) |
| **Combot** | Keyword and regex-based spam filtering | Keyword matching | [combot.org](https://combot.org) |
| **Shieldy** | CAPTCHA-based anti-spam for new members | Challenge-response | [GitHub](https://github.com/1inch/shieldy) |
| **Rose Bot** | Keyword filters and basic anti-flood | Rule-based | [t.me/MissRose_bot](https://t.me/MissRose_bot) |

## CAPTCHA Bots

| Tool | Description | Link |
|------|-------------|------|
| **Shieldy** | Math/button CAPTCHA for new members | [GitHub](https://github.com/1inch/shieldy) |
| **Combot CAPTCHA** | Built-in CAPTCHA in Combot | [combot.org](https://combot.org) |
| **join_captcha_bot** | Open-source CAPTCHA bot | [GitHub](https://github.com/J-Rios/TLG_JoinCaptchaBot) |

## Analytics & Monitoring

| Tool | Description | Link |
|------|-------------|------|
| **TGStat** | Telegram channel and group analytics | [tgstat.com](https://tgstat.com) |
| **Combot Analytics** | Group activity analytics and stats | [combot.org](https://combot.org) |
| **Telemetr** | Channel analytics and monitoring | [telemetr.io](https://telemetr.io) |

---

## Comprehensive Comparison

| Feature | PersonymAI ModerAI | Combot | Rose Bot | Shieldy |
|---------|-------------------|--------|----------|---------|
| **Approach** | AI context analysis | Keyword filtering | Rule-based | CAPTCHA |
| AI message understanding | ✅ | ❌ | ❌ | ❌ |
| Avatar/profile analysis | ✅ | ❌ | ❌ | ❌ |
| Global ban network | ✅ | ❌ | ❌ | ❌ |
| Edit detection | ✅ | ❌ | ❌ | ❌ |
| Trust system | ✅ | ❌ | ❌ | ❌ |
| Fingerprint detection | ✅ | ❌ | ❌ | ❌ |
| Self-learning | ✅ | ❌ | ❌ | ❌ |
| Pre-message blocking | ✅ | ❌ | ❌ | ✅ (CAPTCHA) |
| No CAPTCHA needed | ✅ | ✅ | ✅ | ❌ |
| False ban rate | ~0% | Medium | Medium | Low |
| Accuracy | 99.7% | ~85% | ~80% | ~90% |
| Price | $9/mo | Free/$5+ | Free | Free |

---

## Why AI Moderation > Keyword Filtering

Traditional bots fail because:

1. **False positives** — "investment" gets banned in a trading group
2. **Easy to bypass** — spammers avoid trigger words
3. **No context** — same word means different things in different chats
4. **No learning** — bots don't improve over time
5. **Isolated** — each chat fights spam alone with no shared intelligence

AI-powered moderation solves all five problems.

---

## Resources

### Articles
- [Best Telegram Anti-Spam Bots in 2026](https://medium.com/@PersonymAi/) — Comprehensive comparison
- [How AI Personas Are Changing Telegram Engagement](https://medium.com/@PersonymAi/) — AI engagement overview

### Communities
- [r/TelegramBots](https://reddit.com/r/TelegramBots) — Reddit community for Telegram bot developers
- [Telegram Bot Developers](https://t.me/BotTalk) — Official Telegram group

---

## Contributing

Contributions welcome! Please submit a pull request.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
