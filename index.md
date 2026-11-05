---
title: JAIB privacy policy
---

# JAIB privacy policy

Last updated: 5 November 2026 (beta).

## In short

JAIB keeps your money picture on your phone, encrypted. There is no JAIB account. Nothing about your money leaves the
phone unless you choose to send or save it somewhere. JAIB's own small server is used only to check which plan you have
(see "Your plan"), and the free plan shows a few ads from Google (see "Ads").

## What JAIB reads

- **Payment alerts as they arrive**, only from the apps on JAIB's list (banks, wallets, shops, and your messages and
  email apps), after you turn on notification access. Notifications from every other app are ignored the moment they
  arrive: JAIB never reads or stores what they say. It keeps only the app's name for 7 days, on your phone, so you can
  choose to add it (below); for chat and phone apps it does not keep even that. Chats, one-time passwords (OTPs) and promotions from listed apps are read in memory and
  dropped (of a promotion from a bank or wallet app, only a template is kept for 7 days; see below).
- **Bank texts** are read this way too: JAIB reads the alert your messages app shows when a bank or wallet texts you.
  JAIB has no permission to read your SMS and never opens your messages app or its inbox, so texts from people are
  never stored.
- **Your SMS app, if it is not on the list and you say yes.** If your bank texts arrive in another SMS app, such as
  Truecaller, JAIB names that app and asks before reading its notifications. It reads them the same way: it keeps the
  payments, and chats and everything else are read on the phone and dropped at once. You can say "Not now", and JAIB
  does not ask again. If you said yes, you can change your mind at any time: Sources lists the SMS app with "Stop
  reading", and JAIB stops reading it at once and does not ask again.
- **Other apps, if you switch them on.** In Sources > Apps JAIB reads you can switch on any app that posted a notification
  this week, if it sends you payment alerts. JAIB reads it the same way as your SMS app: it keeps the payments, and chats,
  one-time passwords and everything else are read on the phone and dropped at once. Chat and phone apps, such as WhatsApp,
  can never be switched on. Switch an app off to stop at once; payments already recorded stay.
- **A message you paste or share to JAIB.** It is read on the phone and waits in your Review Inbox for you to check. JAIB
  never adds it by itself.
- **Gmail, if you connect it (optional), for each address you connect.** JAIB asks Gmail only for emails from the
  senders on its list: banks, wallets, the shops and services that send payment receipts, the utilities, phone and
  internet companies and brokers that send bills and confirmations, and any sender you add yourself in Sources >
  Senders you add (an email address or a domain, never a whole public mail domain such as gmail.com; remove it there
  to stop), in your inbox and in
  Spam (so an alert Gmail filed as spam is not missed; never the bin). It never asks for the rest of your mail. Access is read-only and the emails are read on your phone. Emails from before you connected are
  not counted as transactions; JAIB only learns from them which accounts you have. Nothing from these emails leaves
  the phone unless you send a report yourself (see below).
- **Files you pick**: a JAIB backup you restore.
- **What you type to the JAIB Assistant (optional)**: it is understood by a model that runs on your phone. What you
  type, and the Assistant's answers, never leave the phone.

## What JAIB keeps

- What it read from each money message: amount, date, account, reference, the other side's name, and category.
- The text of a message for 7 days (so you can check it), then only its fingerprint (a hash), never the text.
- For a message from a bank or wallet app, or an email from a bank, wallet or payment service or from a sender you
  added, that JAIB did not count
  (a promotion, a notice, or one it could not read), a template of it for 7 days (every name, amount, number and address replaced), so you can send it to help JAIB learn.
  Never the message itself, never chats or one-time passwords.
- The names of other apps that posted a notification in the last 7 days, and the apps you switched on. These stay on the
  phone: they are in no backup, report or diagnostics.
- Your accounts, balances, budgets, savings goals, bills and subscriptions, categories, rules and settings. A rule can look for words you choose in a new
  message. That check happens on your phone as the message arrives; nothing is sent anywhere.
- If you turn on "Help improve the Assistant" (off unless you turn it on): each request you typed, what the Assistant
  understood and what you saved, so you can export it yourself to help train the Assistant. It stays on the phone,
  encrypted, until you export or clear it.
- Everything is encrypted on the phone with a key protected by Android's hardware keystore.
- If you add a JAIB widget to your home screen, it shows your net worth or recent payments there, outside JAIB's lock, to
  anyone who can see your screen. Hide amounts hides the figures. Remove the widget to stop.

## What leaves the phone

- **Nothing financial**, unless you do one of these yourself:
  - export a CSV or JSON file;
  - make a backup file, encrypted with your passphrase (JAIB cannot open it without your passphrase or recovery key);
  - if you turn it on, an automatic backup to your own Google Drive, in a hidden JAIB folder, encrypted on the phone
    with your backup passphrase first (Google stores it but cannot read it; JAIB cannot see your other Drive files);
  - if you link a second phone: what that phone read from each payment alert (amount, account, reference, the other
    side, the alert's wording with names and numbers replaced), encrypted on the phone with a key only your two phones
    have, through a hidden JAIB folder in your own Google Drive. Google stores it but cannot read it; the main phone
    deletes each file once read. Scanning the link code uses Google's code scanner, which sends Google diagnostics and
    usage for the scanner and device information such as the phone's maker, model and Android version (never the
    code; Google does not pass it on), declared in Play's Data safety form;
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
- **Your plan** (see below): a random install number, a few risk signals and, after a purchase, Google Play's purchase
  token, to JAIB's plan server.
- **Ads** (see below): on the free plan, Google's ad library.
- **Google**: Gmail sign-in and access go through Google; Play may count crashes for users who share usage data with
  developers. JAIB has no analytics or crash SDK.

## Your plan (subscriptions)

JAIB's plans (Hisaab and Khazana, monthly) are sold by Google Play: Google takes the payment, and JAIB never sees your
card or bank details. To know which plan you have, the app asks JAIB's own small server (on Cloudflare), which checks
the purchase with Google and sends back a signed answer. Each check sends only:

- a random number JAIB made for this install (not your phone's or Google account's ID; a new one after a reinstall or
  "Delete all my data");
- after a purchase or "Restore purchases", Google Play's purchase token;
- a few risk signals, as short codes, so a tampered app cannot unlock paid features: whether a debugger is attached,
  whether USB debugging or developer options are on, whether the app was repackaged, whether it was installed from
  outside Google Play, and whether the plan answer saved on the phone was edited. They never block you; a phone with
  them is simply checked again sooner.

The server keeps, for each purchase, the token, the install number it belongs to, the plan and when it ends, and a log
of checks (time, install number, the result and any risk codes). It never receives anything about your money, your
messages or your accounts. The log is deleted after 90 days, and each purchase record 90 days after the subscription
ends. In the beta everyone has Bunyaad, so no purchase is involved.

## Ads

On the free plan (and, during the beta, as Google's test ads, so testers can check them), JAIB shows a few ads from
Google AdMob among your own items: about one after every three. They are non-personalised: JAIB asks Google not to use
a profile of you, and removes the advertising ID permission. To show and count an ad, Google's ad library collects
information such as your phone's model and system, approximate location from your internet address, and how you
interact with the ad, as described in [Google's partner policy](https://policies.google.com/technologies/partner-sites).
It never gets your money data, messages or accounts. Paid plans have no ads, and the ad library never starts for
them.

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
phone. JAIB's plan server keeps no money data; its records are deleted on their own (see "Your plan"). To delete
everything:

1. **In JAIB: More > Settings > Delete all my data.** This removes every transaction, account, setting and key from
   the phone, unlinks your other phones, and, if you tick "Also delete my backups in Google Drive", deletes JAIB's
   backups there too; JAIB then says what it removed. Uninstalling JAIB removes what is on the phone only.
2. **Remove JAIB's access to your Google account**: More > Settings > Sources > Disconnect this Gmail in JAIB, or
   myaccount.google.com > Security > Your connections to third-party apps & services > JAIB > Delete all connections.
3. **Backups and the second-phone link in your Google Drive**, if you turned them on and did not tick the box above:
   in Google Drive on the web, Settings > Manage apps > JAIB > Options > Delete hidden app data.
4. **Reports or diagnostics you emailed to the JAIB team**: write to ahmadsefik463@gmail.com and ask for them to be
   deleted; they are deleted within 30 days.

5. **JAIB's plan server**: it holds only your install number, purchase token and check log, deleted on their own
   after 90 days (or 90 days after a subscription ends). To have them deleted sooner, write to ahmadsefik463@gmail.com.

JAIB keeps nothing else about you anywhere.

## Contact

ahmadsefik463@gmail.com
