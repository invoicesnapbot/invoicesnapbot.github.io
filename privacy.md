---
layout: page
title: Privacy Policy
permalink: /privacy/
---

Last updated: March 2026

Service: InvoiceSnap Discord bot with Google Sheets integration

Location: Australia

Contact: admin@invoicesnapbot.com

## What This Policy Covers

This Privacy Policy explains how InvoiceSnap collects, uses, and protects your personal information when you use our Discord bot.

## What Data We Collect

We collect only the minimum information needed to provide our service:

- **Discord User ID** - to identify your account and link it to your Google Sheet
- **Email address** - the email you provide via Stripe checkout when upgrading to a paid plan
- **Google Sheets account email address** - the email you provide via `!setup` to be invited as an editor to the sheet we create for you
- **Invoice images/files** - temporarily processed to extract data (not permanently stored by us)
- **Discord messages** - messages you send to the bot (in DMs or in a server where the bot is present) that are necessary for the service (e.g., `!setup`, `!help`, file uploads)
- **Payment information** - processed by Stripe. We do not see or store your full card details. Through our Stripe merchant dashboard, we can see your name, email address, card type and last four digits, and payment history. This is standard for any online merchant using Stripe.

## How We Use Your Data

| Data | Purpose | How Long We Keep It |
|------|---------|---------------------|
| Discord User ID | To identify your account and provide access to your sheet | Until you request deletion, or 30 days after cancellation |
| Email address | To send your Stripe receipt and link your payment to your account | Until you request deletion, or 30 days after cancellation |
| Google Sheets account email | To invite you as an editor to the sheet we create | Until you request deletion, or 30 days after cancellation |
| Invoice images | To extract data using AI | Processed in real-time, not stored by us (Discord retains its own copy) |
| Discord messages | To process your commands and file uploads | Retained by Discord per their policies; we do not store them separately |

## Free and Paid Tiers

InvoiceSnap offers a free tier (15 invoices per month) and a paid tier ($9 USD/month for unlimited invoices). The same data collection applies to both tiers. Free tier users are not required to provide payment information.

## Data Ownership

Your data is yours. While the Google Sheet is technically owned by our service account (a Google Workspace requirement), all invoice data extracted through the bot belongs to you. You can view, edit, copy, export, or download your data at any time.

## Data Storage and Security

- **Google Sheets:** The sheet we create for you is hosted on our Google Workspace account. You are invited as an Editor, but ownership remains with us (Google Workspace prevents transferring ownership to external accounts). Sharing settings are locked; editors cannot reshare or make the sheet public.

- **Uploaded files:** We do not keep copies of your PDFs, Word documents, or images after processing. Discord retains the files you upload according to Discord's own storage policies.

- **Customer data:** We store Discord User IDs, email addresses, and sheet IDs in an encrypted configuration file on our server, protected with AES-256-GCM encryption at rest. Access is restricted to the server operator only.

- **Server security:** Our server is protected behind Cloudflare's network. Your data is encrypted in transit (HTTPS/TLS) and at rest. We maintain daily encrypted backups of customer data.

- We never sell your data or use it for advertising.

## AI Processing

InvoiceSnap uses artificial intelligence to extract data from your invoices and to generate personality responses (quips). Here is how your data is handled by AI providers:

- **Receipt image extraction:** Processed by Google Gemini (Google, USA). The AI receives your uploaded document, extracts structured data (vendor, date, amount, etc.), and returns it. The document is not stored by Google beyond the processing request.

- **Personality responses:** A summary of the extracted data (vendor name, total amount, category, description, and line items) may be sent to Moonshot AI (Kimi, China) or DeepSeek (China) to generate a short personality response. No receipt images, personal information, or file contents are sent to these providers; only the extracted summary fields listed above.

- According to their published policies, these AI providers do not retain your data beyond the individual processing request.

## Your Rights

Under GDPR (for EU users) and Australian privacy principles, you have the right to:

- **Access** - see what data we hold about you
- **Correction** - ask us to fix inaccurate information
- **Deletion** - request we delete your data

To exercise any of these rights, email us at admin@invoicesnapbot.com.

**Deletion process:** If you request deletion, we will remove your Discord User ID, email address, and sheet ID from our records. Your Google Sheet will be moved to Google's Trash, where it remains accessible for 30 days so you can make a copy. After 30 days, Google permanently deletes trashed files. However:

- Discord's copy of any uploaded files will remain subject to Discord's policies. We cannot delete files you uploaded to Discord.
- Stripe's payment records are governed by Stripe's policies and legal requirements.

We aim to respond to all rights requests within 30 days.

## Third-Party Services

We rely on the following services to operate InvoiceSnap:

- **Discord** - bot platform and file hosting ([Discord's Privacy Policy](https://discord.com/privacy))
- **Google** - creating and managing your spreadsheet ([Google's Privacy Policy](https://policies.google.com/privacy))
- **Stripe** - payment processing ([Stripe's Privacy Policy](https://stripe.com/privacy))
- **Cloudflare** - network security and content delivery ([Cloudflare's Privacy Policy](https://www.cloudflare.com/privacypolicy/))
- **Google Gemini** - AI data extraction from documents (processed in real-time, not stored)
- **Moonshot AI / DeepSeek** - AI personality responses (receives extracted text summaries only, not stored)
- **Zapier** - connecting Stripe payments to our notification system ([Zapier's Privacy Policy](https://zapier.com/privacy))

## Children's Privacy

InvoiceSnap is not intended for users under 16. We do not knowingly collect data from children.

## Changes to This Policy

We may update this policy occasionally. Changes will be posted here with a new "last updated" date.

Questions about privacy? Email admin@invoicesnapbot.com.
