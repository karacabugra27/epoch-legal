---
title: Privacy policy
lang: en
permalink: /en/privacy
---

# Privacy policy

Last updated: 14 November 2026

This policy explains how your personal data is processed when you use Epoch ("the app"), in line with
Türkiye's Personal Data Protection Law No. 6698 ("KVKK"). The [Turkish version](../privacy) is the
binding one; this is a translation.

## Data controller

The data controller is Buğrahan Karaca, who builds and runs the app. For any question or request about
this policy: {{ site.contact_email }}

## What we process

- **Account details:** your email address and a one-way hash of your password (argon2). We never store
  the password itself.
- **Sessions:** your open sessions, each with its browser/device string (user agent), creation time
  and last use.
- **Content you enter:** areas, time entries, plans, goals, day-closing notes, ideas, projects, tasks,
  clients and contacts, deals, proposals, invoices and payments.
- **Preferences:** language, time zone, currency, daily goals, pomodoro lengths.
- **Technical data:** your IP address is kept briefly in server memory only, to stop abuse (attempt
  limits), and is never written to the database. Server logs may be kept for a short time for security
  and debugging.
- **Sign-up time:** when you accepted the terms and this policy.

You enter your clients' details (name, email, phone and so on) yourself. For those people you are the
data controller, and you are responsible for having a legal basis to enter them. We store that data
only to provide the service to you.

## Why, and on what legal basis

- Opening your account, signing you in and providing the app: forming and performing our contract
  (KVKK art. 5/2-c).
- Sending password reset emails: performing the contract (art. 5/2-c).
- Protecting your account and the service (attempt limits, bot checks, security logs): legitimate
  interest (art. 5/2-f).
- Meeting legal obligations and answering official requests: art. 5/2-ç.

We don't use your data for advertising, profiling or sale. We use no analytics or tracking tools.

## Who we share it with

We use these service providers to run the app. Each one processes your data only on our behalf and
only as far as needed:

| Provider | Purpose | Data | Location |
|---|---|---|---|
| Hostinger | Server and database | All of your account data | {{ site.server_location }} |
| Resend | Password reset emails | Your email address, the email's content | USA |
| Cloudflare (Turnstile) | Bot check on sign-up and password reset | Your IP address, browser signals | USA and global network |
| Backup provider (Backblaze B2 or Cloudflare R2) | Encrypted daily database backups | All of your account data | The provider's chosen region |

Transfers to providers abroad follow KVKK art. 9, with appropriate safeguards such as the standard
contracts published by the Personal Data Protection Board. We share your data with no one else, except
authorities where the law requires it.

## How long we keep it

- We keep your data while your account is open.
- When you delete your account, all of your data is removed from the database right away. Copies in
  backups are gone within 30 days, as the backups rotate.
- Password reset links stop working after 3 hours and are deleted once used or when your password
  changes.
- Sessions you sign out are deleted right away. Expired sessions are cleared the next time you sign in.

## Cookies and browser storage

We use one strictly necessary session cookie to keep you signed in (HttpOnly, never shared with third
parties). Your theme and language choices are kept in your browser's local storage. On the sign-up and
password reset pages, Cloudflare Turnstile may process its own technical data for the bot check. We use
no advertising or tracking cookies.

## Security

Connections are encrypted with HTTPS. Passwords are hashed with argon2 and session keys are stored
hashed. Each account's data is kept apart from every other account; no other user can see yours.

## Your rights

Under KVKK art. 11 you can ask whether your data is processed and request details about it, learn why
it is processed and who it is shared with, have incomplete or wrong data corrected or deleted and those
recipients told, object to an outcome against you that comes only from automated analysis, and claim
compensation for damage.

You can do most of this in the app: under **Settings → Account and security** you can download all of
your data as JSON, sign out sessions and delete your account for good. For anything else, write to
{{ site.contact_email }}; we answer within 30 days. If you're not satisfied with our answer, you can
complain to the Personal Data Protection Board (KVKK).

## Age

The app is not meant for anyone under 18.

## Changes

If we change this policy, we update the date at the top. We announce important changes in the app.
