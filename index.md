---
title: JAIB privacy policy
---

# JAIB privacy policy

Last updated: 30 October 2026 (beta).

## In short

JAIB keeps your money picture on your phone, encrypted. There is no JAIB account and no JAIB server. Nothing about your
money leaves the phone unless you choose to send or save it somewhere.

## What JAIB reads

- **Payment alerts as they arrive**, only from the apps on JAIB's list (banks, wallets, shops, and your messages and
  email apps), after you turn on notification access. Notifications from every other app are ignored the moment they
  arrive and never stored. Chats, one-time passwords (OTPs) and promotions from listed apps are read in memory and
  dropped (of a promotion from a bank or wallet app, only a template is kept for 7 days; see below).
- **Bank texts** are read this way too: JAIB reads the alert your messages app shows when a bank or wallet texts you.
  JAIB has no permission to read your SMS and never opens your messages app or its inbox, so texts from people are
  never stored.
- **Your SMS app, if it is not on the list and you say yes.** If your bank texts arrive in another SMS app, such as
  Truecaller, JAIB names that app and asks before reading its notifications. It reads them the same way: it keeps the
  payments, and chats and everything else are read on the phone and dropped at once. You can say "Not now", and JAIB
  does not ask again.
- **Gmail, if you connect it (optional), for each address you connect.** JAIB asks Gmail only for emails from the
  senders on its list: banks, wallets, and the shops and services that send payment receipts, in your inbox and in
  Spam (so an alert Gmail filed as spam is not missed; never the bin). It never asks for the rest of your mail. Access is read-only and the emails are read on your phone. Emails from before you connected are
  not counted as transactions; JAIB only learns from them which accounts you have. Nothing from these emails leaves
  the phone unless you send a report yourself (see below).
- **Files you pick**: a JAIB backup you restore.
- **What you type to the JAIB Assistant (optional)**: it is understood by a model that runs on your phone. What you
  type, and the Assistant's answers, never leave the phone.

## What JAIB keeps

- What it read from each money message: amount, date, account, reference, the other side's name, and category.
- The text of a message for 7 days (so you can check it), then only its fingerprint (a hash), never the text.
- For a message from a bank or wallet app, or an email from a bank, wallet or payment service, that JAIB did not count
  (a promotion, a notice, or one it could not read), a template of it for 7 days (every name, amount, number and address replaced), so you can send it to help JAIB learn.
  Never the message itself, never chats or one-time passwords.
- Your accounts, balances, categories, rules and settings.
- If you turn on "Help improve the Assistant" (off unless you turn it on): each request you typed, what the Assistant
  understood and what you saved, so you can export it yourself to help train the Assistant. It stays on the phone,
  encrypted, until you export or clear it.
- Everything is encrypted on the phone with a key protected by Android's hardware keystore.

## What leaves the phone

- **Nothing financial**, unless you do one of these yourself:
  - export a CSV or JSON file;
  - make a backup file, encrypted with your passphrase (JAIB cannot open it without your passphrase or recovery key);
  - if you turn it on, an automatic backup to your own Google Drive, in a hidden JAIB folder, encrypted on the phone
    with your backup passphrase first (Google stores it but cannot read it; JAIB cannot see your other Drive files);
  - if you link a second phone: what that phone read from each payment alert (amount, account, reference, the other
    side, the alert's wording with names and numbers replaced), encrypted on the phone with a key only your two phones
    have, through a hidden JAIB folder in your own Google Drive. Google stores it but cannot read it; the main phone
    deletes each file once read. Scanning the link code uses Google's code scanner, which may send Google usage counts
    for the scanner (never the code);
  - send a "wrong result" report or diagnostics (which include how far you got setting up JAIB, as days since
    install, and how many balances JAIB's weekly self-check corrected, as a count) from your own email app, to the
    JAIB team (ahmadsefik463@gmail.com).
    You see exactly what is sent first and can untick any message. Messages, including bank and wallet emails JAIB
    read from your Gmail, are sent only as templates: the bank's
    wording with every name, amount, reference, account number, phone number, date, email and street address
    replaced (for example "Rs. {AMOUNT} sent to {NAME}"), with what JAIB did with them. They are used only to teach
    JAIB new message formats.
- **The JAIB Assistant's model**: if you turn the Assistant on, JAIB downloads its model file once (about 500 MB, and
  again only when you choose to update it) from the address in JAIB's model list (currently Hugging Face,
  huggingface.co). The request is the same for everyone and carries nothing about you or your money.
- **Exchange rates**: once a day JAIB downloads public currency rates (fawazahmed0/exchange-api through jsDelivr or
  Cloudflare). The request is the same for everyone and carries nothing about you or your money.
- **Google**: Gmail sign-in and access go through Google; Play may count crashes for users who share usage data with
  developers. JAIB has no analytics or crash SDK.

## Google API Services User Data Policy (Limited Use)

JAIB's use and transfer of information received from Google APIs to any other app will adhere to the
[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the
Limited Use requirements. Gmail data is read and processed on your phone. It leaves the phone only when you choose to
send a report to the JAIB team from your own email app: you see each bank or wallet email first, as a template with
every name, amount, number and address replaced, and can untick it. The JAIB team reads only the templates you send,
and only to teach JAIB new bank email formats. Gmail data is not used for advertising, not sold, not shared with
anyone else, and not used to train AI models.

## Deleting your data

JAIB has no account on any server: signing in with Google only lets JAIB read your bank and wallet emails on your
phone. To delete everything:

1. **In JAIB: More > Settings > Delete all my data.** This removes every transaction, account, setting and key from
   the phone. Uninstalling JAIB does the same.
2. **Remove JAIB's access to your Google account**: More > Settings > Sources > Disconnect this Gmail in JAIB, or
   myaccount.google.com > Security > Your connections to third-party apps & services > JAIB > Delete all connections.
3. **Backups and the second-phone link in your Google Drive**, if you turned them on: in Google Drive on the web,
   Settings > Manage apps > JAIB > Options > Delete hidden app data.
4. **Reports or diagnostics you emailed to the JAIB team**: write to ahmadsefik463@gmail.com and ask for them to be
   deleted; they are deleted within 30 days.

JAIB keeps nothing else about you anywhere.

## Contact

ahmadsefik463@gmail.com
