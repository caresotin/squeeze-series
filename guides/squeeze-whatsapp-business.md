# Squeeze WhatsApp Business: The Most Complete Guide

> Version: v1 | 2026-08-28 | Sources: Meta official documentation + community field testing
> Approach: every claim carries data. Where a number hasn't been verified, this guide says so instead of guessing. Data current as of August 2026.

---

Your customers stopped opening email years ago. They're on WhatsApp now.

People in foreign trade, running DTC stores, selling services overseas — most still use WhatsApp for voice notes and group chats. Meanwhile, the people winning orders use it for quoting, support, and automation. The tutorials you'll find online mostly stopped updating in 2023, and the billing model was overhauled in July 2025 — a lot of old advice will actively get you banned or overcharged now.

This guide walks the whole chain in one pass: which path to pick, registering and migrating, squeezing every feature, the truth about broadcasting, warming up your number so it doesn't die, what to do when you're banned, and how to wire WhatsApp into your customer acquisition pipeline. Everything verified as of August 2026.

> This is the most complete guide you'll find on the topic. Bookmark it and work through it slowly.

---

## Contents

1. Choose your path: Business App / Meta Verified / API — which one, and why it matters
2. Registering a new number: the full SOP from download to taking orders
3. Migrating an existing number: personal → Business without losing chats
4. Business profile + catalog: so clients know who you are in one glance
5. Drowning in messages? Quick replies, labels, and auto-replies in one pass
6. The truth about broadcast lists: the 256-person cap and the ban risk behind it
7. Multi-device and security: the right way for four people to reply at once
8. Meta Verified green check: worth it, and which tier
9. The real cost math: from the free app to the API
10. Warming up and staying alive: the first 10 days, and what gets you banned
11. Banned or lost your account: the recovery sequence, in order
12. The endgame: wiring WhatsApp into your overseas customer acquisition
13. Appendix: one-page cheat sheet

---

## 1. Choose your path: Business App / Meta Verified / API

The first question everyone asks is "is WhatsApp Business free?" The honest answer: three different products answer to that name, and they cost very different money.

**The three paths**

Path one is the **WhatsApp Business App**, and it's free. It's the "seller edition" of regular WhatsApp — business profile, product catalog, quick replies, labels, greeting messages. It fits one person managing one number and a few dozen inquiries a day.

Path two is **Meta Verified**, a paid subscription. It's a certification layer on top of the Business App, and it buys you exactly two things: the green check (verified badge) and multi-device login across more phones. No advanced automation, no CRM integration.

Path three is the **WhatsApp Business Platform (API)**, billed per message. It connects to CRMs, runs chatbots, supports multi-person teams and bulk processing — the only option that actually scales. But it runs through a Business Solution Provider (BSP), which means a subscription fee on top of per-message charges.

**The short version**

| | Business App | Meta Verified | Business API |
|---|---|---|---|
| Cost | Free | From $14.99/month | Subscription + per-message fees |
| Devices | 1 phone (primary) | Up to 10 | Unlimited (multi-agent) |
| Green check | No | Yes | Requires business verification, priced separately |
| Auto-replies | Basic (greeting/away) | Same as the app | Chatbots, CRM workflows |
| Bulk broadcasting | Broadcast lists, 256 per batch | Same as the app | No cap (rate limits apply) |
| Best for | Testing the waters, solo sellers | Small teams that need a trust badge | Established volume, automation |

**Bottom line:** run the free version until the process works, buy the green check when volume justifies it, and go API when automation becomes the bottleneck. The three tiers are a ladder, not rivals.

---

## 2. Registering a new number: the full SOP

Registration itself is easy. Choosing the number, the network, and the verification — get those wrong and everything after is damage control.

**Two decisions before you register**

First, use a clean number. Get a dedicated business line; don't repurpose the personal number you text your friends on. For overseas business, a giffgaff +44 UK number or a PayGo +1 US number is the standard move (there's a full tutorial elsewhere in this series). The cleaner the number's history, the less risk of tripping the risk controls.

Second, lock down your network. WhatsApp is sensitive to the purity of the IP you register from — stay on the same network the whole time and don't switch nodes mid-registration. +86 numbers can register, but you need a network that can actually reach WhatsApp.

**The registration steps**

1. Download WhatsApp Business from the app store (free — look for the orange logo and the word "Business"; don't grab regular WhatsApp by mistake)
2. Tap "Agree and continue," pick the country that matches your number, and enter the business number
3. Wait for the SMS or voice verification code, enter it, done
4. Fill in your business name, pick a category, upload a profile photo — all editable later, but the first impression gets set here
5. Turn on two-step verification immediately (Settings → Account → Two-step verification → Enable), set a 6-digit PIN, and save a recovery email you'll actually keep
6. Don't start adding people. Use the number like a normal person for 3–7 days first (Chapter 10)

**Verification code not arriving?**

No SMS after a bit? Wait 90 seconds and tap resend — don't spam the button. If it still won't come, switch to the voice-call verification channel. Multiple rapid failures trigger a cooldown: stop for 1–2 hours and try again. Code delivery is partly on your carrier — some domestic numbers are slow with international SMS, while overseas numbers (+44/+1) are usually the most reliable.

**Bottom line:** clean number + fixed network + two-step verification + three quiet days. That combination makes registration the boring, reliable step it should be.

---

## 3. Migrating an existing number: personal → Business without losing chats

Already chatting with clients on regular WhatsApp? Don't register a new number. Convert the existing one to Business and keep every chat and contact.

**The one rule that governs all of it**

A single number can't be active on regular WhatsApp and WhatsApp Business at the same time. The conversion is one-way and happens once — after you switch, the number stops working on regular WhatsApp.

**The migration steps**

1. Back up first: Settings → Chats → Chat backup → back up to Google Drive (Android) or iCloud (iPhone)
2. Download WhatsApp Business and enter the same number
3. After verification, the app detects your existing account — choose "Restore chat history"
4. Check everything restored: contacts, groups, chat history, archived conversations

**Two places people trip**

First, on a dual-SIM phone, don't let both apps claim the same number. The same number logged into two apps at once reads as suspicious activity — at best you get logged out, at worst you trip the risk controls.

Second, confirm the backup is complete before migrating. Moving to a new phone later is where this bites: Android and iPhone backups aren't directly transferable between each other — you'd need third-party tools or manual export, so plan ahead if your history is big.

**Bottom line:** one number, one app. Back up, convert, restore, and not a single chat is lost.

---

## 4. Business profile + catalog: so clients know who you are in one glance

On regular WhatsApp, a stranger looking at you sees a profile photo and "online." The Business version lets you answer three questions at once: who you are, what you sell, and how to reach you.

**Business profile (Settings → Business profile)**

Fill in four fields: business name, category, business hours, website link. Add a short description covering what you sell and how long delivery takes. For overseas clients, a complete profile changes the trust calculation immediately.

**Product catalog (Settings → Business tools → Catalog)**

This is the most underrated feature on the platform. One account gets one catalog with up to 500 products, each with image, name, price, description, and product code — plus "collections" to organize them by category. Clients browse and order right inside the chat; no more sending price lists back and forth as files.

Upload at least 3–5 core products. A business page with an empty catalog is a storefront with the lights off.

**Short links (wa.me)**

Every number gets its own link: wa.me/8613812345678. Put it on your website, your Instagram bio, your email signature. One tap and the visitor is in your chat. It's the official, free customer-acquisition entry point.

**Bottom line:** profile + catalog + wa.me link. Two hours of setup, and your conversion path is half as long.

---

## 5. Drowning in messages? Quick replies, labels, and auto-replies in one pass

Once inquiries pick up, reply speed decides close rate. The free app ships three automation tools, and most people never touch them.

**Quick replies (Settings → Business tools → Quick replies)**

Store your most-sent answers as short commands: /price pulls the price list, /ship pulls the shipping info. Two minutes of typing becomes two seconds. Start with the 5 questions you get asked most, and make 5 quick replies.

**Labels (main screen → long-press a chat → Label)**

Color-code your conversations: new lead, quote sent, closed, follow up. First thing every morning, one glance at the labels tells you what today needs. The free tier's labels cover a solo business just fine.

**Greeting + away messages (Settings → Business tools → Greeting/Away message)**

First-time customers get an automatic greeting that introduces your business and your main products. Outside working hours, the away message tells them "received — I'll reply within X hours." Ten minutes of setup, and the customer experience is a different product.

One caveat: these are reply templates, not a real chatbot. Question-aware, intelligent answers require the API route (Chapter 9).

**Bottom line:** quick replies handle speed, labels handle priority, greetings handle first impressions. The free tier is enough to run on for six months.

---

## 6. The truth about broadcast lists: the 256-person cap and the ban risk

The thing foreign-trade sellers want most from WhatsApp is cold-outreach blasting. Get the facts straight first: the free app's broadcast feature caps each batch at 256 people — and messages only go through if the recipient has saved your number.

**Using broadcast lists properly**

Contacts → Broadcast lists → New, pick people from your contacts (max 256). Every recipient sees the message as a private chat; nothing about it screams "mass message" — provided they saved your number.

So broadcasting is built for existing customers and leads who already have you in their contacts. It is not built for cold-blasting strangers.

**Why blasting gets you banned**

WhatsApp's policy on marketing behavior is explicit: contacting people in bulk without consent, high complaint rates, and automated sending tools all trigger the risk controls. Blasting strangers on day one is the fastest way to lose the account.

And the practical reality is uglier: a stranger who doesn't know you is likely to report you, and enough reports kills the number. Instead of blasting cold numbers, push traffic to your wa.me link — people who come to you — then collect the inquirers into a broadcast list.

**Bottom line:** a broadcast list is for messaging customers you already have, not advertising to strangers. Get the order wrong and the number is gone.

---

## 7. Multi-device and security: four people replying at once, done right

The free tier supports one phone plus up to 4 linked devices (WhatsApp Web/desktop/tablet). It handles multiple logins, with a few hard rules.

**Linked devices (phone → Settings → Linked devices)**

Scan the QR code on your phone; up to 4 devices can be online simultaneously. The catch: the phone is the primary device — the 4 linked devices depend on it receiving messages, so if the phone drops offline, the linked devices do too.

Need more than 4 devices, or want different people handling different conversations? The free tier can't do it. That's Meta Verified (up to 10 devices) or the API (a proper multi-agent inbox).

**Two security rules that are non-negotiable**

First, two-step verification must be on. The 6-digit PIN goes in your password manager, and the recovery email should be an address you'll still have in five years (the Gmail plus-alias trick from the Gmail guide works here).

Second, handle a lost device immediately. Log into WhatsApp on the new device and the old one is force-logged-out; then run Settings → Linked devices → Log out of all devices to be thorough. Cheaper than changing numbers.

**Bottom line:** 4 linked devices is the free ceiling — want multi-person teamwork, pay up. Skip two-step verification and your account is walking around naked.

---

## 8. Meta Verified green check: worth it, and which tier

The green check = verified badge, shown in the chat list and on your profile page. Clients see at a glance that this is the official account, not an impersonator. For trust-sensitive businesses — payments, consulting, services — that has real value.

**The tiers (verified August 2026)**

| Tier | Monthly price (first 12 months of a new subscription) | Linked devices | Verified channels |
|---|---|---|---|
| Business Standard | $14.99 | Up to 4 | 1 |
| Business Enhanced | $44.99 | Up to 6 | 3 |
| Business Premium | $119.99 | Up to 8 | 5 |
| Business Ultimate | $349.99 | Up to 10 | 10 |

Three things to know: pricing varies by region (the UK, for one, is priced differently); renewals after 12 months run at the standard rate; and Meta Verified is only available in some countries — if you don't see the option in your app settings, it's not available to you, and no third party can "buy" it for you. Don't pay someone to.

**Is it worth it?**

For solo sellers and small teams, the $14.99 tier solves both pain points — more devices and the badge — and is the best value on the table. If your business mostly gets found by customers coming to you (website, ads), the green check's conversion boost is limited. If you're in B2B or agency work where both sides care about credentials, it's worth it.

**Bottom line:** the green check doesn't win customers, it wins trust. Starts at $14.99 — run the free version first, then decide.

---

## 9. The real cost math: from the free app to the API

The API is the only path to CRM integration, chatbots, and bulk processing — but the billing model was rewritten in July 2025, and the numbers in older tutorials are basically void.

**The current billing logic (as of August 2026)**

Since July 1, 2025, Meta charges per message instead of per conversation, and only messages that are successfully delivered get billed.

Still free right now:
- Free-form text replies inside the 24-hour customer service window (officially announced: this becomes paid on October 1, 2026)
- All messages within 72 hours of a customer starting a conversation through a free entry point such as Click-to-WhatsApp ads or Facebook buttons

Paid (priced by destination country — roughly $0.025 per marketing message in the US, about $0.0025 in India):
- Marketing template messages, per message
- Authentication template messages, per message
- Since August 1, 2026: AI auto-replies from Meta Business Agent, billed per token (about $2 per million tokens — roughly 4–5 cents a reply)
- From October 1, 2026: free-form replies inside the 24-hour window and utility templates start being charged

**You also go through a BSP**

The API normally requires a Business Solution Provider (Wati, 360dialog, respond.io, Twilio, and others). The bill has three parts: a setup fee (provider-dependent — free at some, up to $1,000 at others), a monthly subscription (roughly $50–$500), and Meta's per-message charges. BSP quotes vary wildly, so before signing ask exactly: how many messages are included, and what happens beyond that.

**A sample calculation**

Say you send 1,000 customers one marketing template message each per month, targeting the US at $0.025 per message: about $25 in message fees. Add a $50-tier BSP subscription and you're at roughly $75/month to start. If you only send service messages (customer reaches out first), the cost is far lower.

**Bottom line:** API money goes to subscription + per-message + automation/integration. Until volume is real, the free app plus broadcast lists is enough.

---

## 10. Warming up and staying alive: the first 10 days, and what gets you banned

WhatsApp publishes no official "warming up" rules. The following is community experience from years of field testing — not official policy — but follow it and the ban rate drops noticeably.

**Getting through the first 10 days**

The first 10 days after registration are the tightest risk window:
- Days 1–3: chat normally, view statuses, reply to messages. No adding people, no groups, no broadcasts
- Days 4–7: start adding a few contacts — 5–10 per day, all manual
- Days 8–10: up to 10–15 per day, still no broadcasting
- After day 10: scale up gradually, keep new adds within 20–30 per day, and never first-contact more than 50 people in one push

**The fastest ways to lose the number**
- Broadcasting and adding dozens of people on day one
- Automated tools/scripts for bulk adding and bulk messaging (WhatsApp detects automation fingerprints)
- Running multiple numbers from the same IP or device (the accounts get linked, and one ban takes them all)
- Constantly switching login devices and hopping IP nodes
- Getting reported a lot (a high complaint rate is the most direct ban signal)

**The quality score**

Behind the scenes there's a message quality rating (visible to API users) shaped by complaint rate, ban history, and content type. Let it drop and your sending limits shrink — worst case, you can only receive. Maintaining it comes down to one sentence: only message people who actually want your messages.

**Bottom line:** act like a normal user for 10 days, add people slowly, and let the number mature before broadcasting. Best ban-prevention ROI in the game.

---

## 11. Banned or lost your account: the recovery sequence, in order

Bans come in two flavors: temporary (requires verification) and permanent (policy violation). Figure out which one you're dealing with, then work the sequence in order.

**Case 1: "Verify your account" (temporary ban)**

Open the app and enter the code it asks for (SMS or voice). If verification passes, the account usually recovers within 24 hours. Note: verification needs the original number to receive codes — this is where that overseas number (giffgaff/PayGo) becomes a life raft.

**Case 2: "Your account is disabled" (policy ban)**

WhatsApp has an appeal path (look for "request a review" on the in-app notice page, or contact official support). Explain honestly what the account is for. Success rates aren't high, but they improve if you can back the appeal with registration details — the number, the email, the devices you normally use.

**After you're back: 3 moves (important)**

1. Stop broadcasting and aggressive marketing; chat normally for 3–7 days
2. Audit your login devices and IP, clean up anything suspicious, avoid re-triggering
3. Check your message-sending limits and rebuild from small numbers gradually

**Lost phone / changing numbers**

Changed your number? Don't register fresh: Settings → Account → Change number migrates the existing account to the new number, chats and groups intact. The option is buried, but it's official, and infinitely safer than starting over.

**Bottom line:** temporary ban → verify; policy ban → appeal; after unban, stay quiet 3–7 days; changing numbers → use the official Change number, never a fresh registration.

---

## 12. The endgame: wiring WhatsApp into your overseas customer acquisition

For foreign trade and overseas business, WhatsApp isn't a chat app — it's the closing end of the customer acquisition chain. Acquisition feeds into it; payment comes out of it.

**Step 1: the number is your storefront**

Register the business WhatsApp on a clean overseas number — giffgaff (+44) or PayGo (+1) — and pair it with the Gmail plus-alias trick for account isolation: one number for WhatsApp, one email for payments, one email for platform signups. Nothing cross-contaminates.

**Step 2: route acquisition into WhatsApp**

Put the wa.me link on your website, Instagram, email signature. Tag the links per channel so you can see where customers come from and what they clicked, and pair that with Gmail filters for source stats — far better than asking "how did you find me?"

**Step 3: close in WhatsApp, get paid via Wise/PayPal**

Quotes, samples, order confirmations all happen inside WhatsApp (catalog + quick replies cover it). Payment moves to a Wise multi-currency account or PayPal (the two payment guides in this series have full fee comparisons). The chat history itself is your order record — pull it up if there's ever a dispute.

**Step 4: go API when volume justifies it**

Once inquiries stabilize, add API + CRM and track inquiries, quotes, and follow-up status properly. The free app + broadcast lists handles a few hundred inquiries a month without breaking a sweat. Pay for scale when you've actually got scale.

**Bottom line:** WhatsApp closes deals; it doesn't open them. wa.me pulls people in, Wise/PayPal gets you paid, the chat log keeps the record — that chain is what "squeezing" this platform actually means.

---

## Appendix: one-page cheat sheet

**Choosing a path**
Free app first → need a badge or more devices? Meta Verified (from $14.99) → need automation/CRM/bulk? API.

**Registration SOP**
Clean number → fixed network → WhatsApp Business app → verify → two-step verification on → first 3 days, normal chatting only.

**Migrating an existing number**
Back up first → register Business with the same number → restore chat history → one number can only be active on one app.

**Feature quick reference**
Business profile + catalog (up to 500 products) + wa.me link + quick replies + labels + greeting/away messages.

**Broadcast limits**
Max 256 per batch; recipients must have your number saved; never blast from a new number — enough reports and it's gone.

**Multi-device**
Free: 1 phone + 4 linked devices. Meta Verified: up to 10. Multi-person teams: API.

**Billing (August 2026)**
Per-message, delivered-only billing; 24h-window free-text replies become paid 2026-10-01; 72h free after free entry points; US marketing ~$0.025/message; AI replies billed per token ($2/million).

**Warm-up red lines**
First 10 days: no adding, no blasting; adds start at 5/day, cap at 20–30/day; never first-contact more than 50 at once; no automation tools; maintain your quality score.

**Recovery**
Temporary ban → verify. Policy ban → appeal. After unban: no broadcasting, 3–7 quiet days. Changing numbers → official "Change number."

**Security**
Two-step verification + recovery email + device management. All three, no exceptions.

---

## References

1. WhatsApp Business official site: https://business.whatsapp.com/
2. Meta per-message pricing: https://business.whatsapp.com/products/platform-pricing
3. Meta Verified for WhatsApp: https://www.whatsapp.com/business/meta-verified
4. WhatsApp Business Help Center: https://business.whatsapp.com/help
5. WhatsApp Help Center: https://faq.whatsapp.com/

---

## More in the Squeeze Series →

- [Squeeze WhatsApp Business: The Most Complete Guide](squeeze-whatsapp-business.md)
- [Squeeze Made-in-China: From Beginner to Fully Monetized] (coming soon)
- [Squeeze AI for Export Customer Acquisition: From Beginner to Fully Monetized] (coming soon)
- [Squeeze Customs Data: From Beginner to Fully Monetized] (coming soon)

---

> Compiled by the CARESO team. Data current as of August 2026; official pages take precedence. Verified 2026-08-28. Per-message prices, Meta Verified tiers, and BSP quotes follow Meta's official pages and your provider's real-time info; warm-up rates and sending limits are community-tested experience values, not official rules. WhatsApp changes policies and pricing often — confirm against the official Help Center before acting. Broadcasting must comply with Meta's Business Policy: get consent before you message.
