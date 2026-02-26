---
layout: page
title: Privacy Policy
permalink: /privacy/
---

# InvoiceSnap Privacy Policy

**Last updated:** February 2026

**Service:** InvoiceSnap Discord bot with Google Sheets integration  
**Location:** Australia  
**Contact:** admin@invoicesnapbot.com  

---

## What This Policy Covers

This Privacy Policy explains how InvoiceSnap collects, uses, and protects your personal information when you use our Discord bot.

## What Data We Collect

We collect only the minimum information needed to provide our service:

- **Discord User ID** – to identify your account and link it to your Google Sheet
- **Email address** – the email you provide via Stripe checkout to receive your Stripe receipt and welcome email
- **Google Sheets account email address** – the email you provide via `!setup [email]` to be invited as an editor to the sheet we create for you
- **Invoice images/files** – temporarily processed to extract data (not permanently stored by us)
- **Discord messages** – messages you send to the bot (in DMs or in a server where the bot is present) that are necessary for the service (e.g., `!setup`, `!sheet`, file uploads)
- **Payment information** – processed by Stripe. We do not see or store your full card details. Through our Stripe merchant dashboard, we can see your name, email address, card type and last four digits, and payment history. This is standard for any online merchant using Stripe

**Important note about uploaded files:** When you upload an invoice, receipt, PDF, or image to Discord, **Discord stores a copy of that file** on its servers. We provide a link to the uploaded file in your spreadsheet so you can re‑download it later. We do not keep a separate copy of your uploaded files.

## How We Use Your Data

| Data | Purpose | How Long We Keep It |
|------|---------|---------------------|
| Discord User ID | To identify your account and provide access to your sheet | Until cancellation + 90 days, or upon deletion request |
| Email address | To send your Stripe receipt, welcome email | Until cancellation + 90 days, or upon deletion request |
| Google Sheets account email | To invite you as an editor to the sheet we create | Until cancellation + 90 days, or upon deletion request |
| Invoice images | To extract data using AI | Deleted immediately after processing (Discord retains its own copy) |
| Discord messages | To process your commands and file uploads | Retained by Discord per Discord's policies; we do not store them separately |

## Data Ownership

**Your data is yours.** While the Google Sheet is owned by our service account (a Google Workspace requirement), all invoice data extracted through the bot belongs to you. You can view, edit, copy, export, or download your data at any time.

## Data Storage & Security

- **Google Sheets:** The sheet we create for you is hosted **on our Google Workspace account**, not in your personal Google Drive. You are invited as an Editor, but ownership remains with us (Google Workspace prevents transferring ownership to external accounts).
- **Uploaded files:** We do **not** keep copies of your PDFs, Word documents, or images after processing. Discord retains the files you upload according to Discord's own storage policies.
- **Other data:** We store Discord User IDs, email addresses, and sheet IDs in a simple configuration file on our server. We use industry‑standard security practices to protect this data.
- We never sell your data or use it for advertising.

## Your Rights

Under GDPR (for EU users) and Australian privacy principles, you have the right to:

- **Access** – see what data we hold about you
- **Correction** – ask us to fix inaccurate information
- **Deletion** – request we delete your data

**Important:** Because we are a small operation without automated data‑access systems, we currently do not have a self‑service portal. To exercise any of these rights, email us at **admin@invoicesnapbot.com** and we will manually retrieve and act on your request.

**Deletion note:** If you request deletion, we will remove your Discord User ID, email address, and sheet ID from our records and delete the Google Sheet we created. You will be given **14 days' notice** before the sheet is deleted so you can make a copy for your own records. However:
- Discord's copy of any uploaded files will remain subject to Discord's policies — we cannot delete files you uploaded to Discord
- Stripe's payment records are governed by Stripe's policies and legal requirements

**Data retention after cancellation:** If you cancel your subscription, we retain your Google Sheet for **90 days** to give you time to make a copy. After 90 days, the sheet and your configuration data are permanently deleted.

We aim to respond to all rights requests within 30 days.

## Third‑Party Services

We rely on the following services to operate InvoiceSnap:

- **Discord** – for the bot platform and file hosting (see [Discord's Privacy Policy](https://discord.com/privacy))
- **Google** – for creating and managing your spreadsheet (see [Google's Privacy Policy](https://policies.google.com/privacy))
- **Stripe** – for payment processing (see [Stripe's Privacy Policy](https://stripe.com/privacy))
- **AI data extraction** – we use AI models to extract data from your uploaded documents (document data is processed in real time and is not permanently stored by the AI provider)
- **Zapier** – for connecting Stripe to our email system (Zapier's privacy policy applies)

## Children's Privacy

InvoiceSnap is not intended for users under 16. We do not knowingly collect data from children.

## Changes to This Policy

We may update this policy occasionally. Changes will be posted here with a new "last updated" date.

## Contact Us

Questions about privacy? Email **admin@invoicesnapbot.com**.
