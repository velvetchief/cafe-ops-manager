---
name: coffee-shop-getting-started
description: >-
  Use for the first conversation with a new coffee shop owner who just installed
  the coffee shop bot template: connect Drive and Sheets, set up folders, the
  staff email intake, and count reminders.
---
# Getting started (coffee shop owner)

Say in one line: "I keep your shop's bills, sales, stock counts and low-stock alerts in your own Google Drive. Your staff just email me photos." Then ask the questions below one at a time, and wait for each answer.

1. **Shop name.** Ask what to call the shop. Use the name for the top Drive folder.
2. **Connect Google Drive and Google Sheets.** If they aren't connected, show the connect card. Wait until both work.
3. **Create the files.** Create the top folder `<Shop name> Back Office` with Inbox, POS Sales, Order Receipts, Recipes (BOM) and Daily Counts inside it. Then create the Stock log Sheet (tabs Purchases, Stock, BOM, Sales, Review queue, Setup) and the Suppliers and par levels Sheet (tabs Suppliers, Par levels). **Create both Sheets with the Google Drive connector, as spreadsheets inside the top folder.** Don't create them with the Sheets connector: it saves them in the root of My Drive, and they can't be moved or deleted afterward. Once they exist, use the Sheets connector to add the tabs and headers. Read the folder back and show the owner its link.
4. **POS.** Ask "Which POS do you use?" and offer Square, Toast, Shopify POS, Clover, NCR Aloha and Other. Note the answer in Setup. Explain that for now staff email the end-of-day sales report (a CSV export, or a photo of the Z-report) each night. Never ask for a POS key in chat.
5. **Staff emails.** Ask for the email addresses of the people who will send bills, counts and sales, including the owner. Only these addresses will reach the bot.
6. **Email intake.** Find this bot's own email inbox and create an email routine on it. Set the sender filter to those addresses and leave the authentication checks on. The routine runs the coffee-shop-ops skill on each email and reports to the owner in this chat. Give the owner the address and this note for staff: "Email bill photos, end-of-day sales and counts to this address. Put bill, sales or count in the subject. Send photos at Medium size."
7. **Count days.** Ask which two days a week staff count stock, then create a routine that reminds the owner in this chat on those mornings.
8. **Menu and stock (optional now).** Ask for recipes (what goes into each drink, per serving), suppliers, and par levels. They can paste, upload a file, or skip and add them later. Write whatever they give into the BOM, Suppliers and Par levels tabs.
9. **Test.** Ask the owner to email one bill photo to the bot address now. When it's read, show the supplier, date and total, and ask whether they match the paper. If the photo couldn't be opened, ask them to resend it at Medium size.

Save the shop name, POS, count days and inbox address to memory. Never save keys or passwords anywhere. Finish with a short summary of what's set up and what's still missing.
