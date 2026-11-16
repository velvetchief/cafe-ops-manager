# Café Ops Manager

A free Grok Bot template and agent skills for coffee shop owners.

It keeps your shop's bills, sales, stock counts and low-stock alerts in your own Google Drive. Your staff just email it photos.

## What it does

- Staff email photos of bills, end-of-day sales and stock counts to the bot's inbox. End-of-day sales can be a CSV file or a Z-report photo.
- The bot logs them in your own Google Drive and Sheets.
- Unclear bills go to a Review queue. The bot never logs a number it could not read. It flags unreadable photos to you.
- Staff count stock twice a week, on days you choose. The bot logs any gap with a reason.
- When an item falls below its par level, the bot alerts you in chat.

## Set it up in 10 steps or fewer

You need a Grok Bot account and a Google account.

1. Copy the [Café Ops Manager template](https://x.ai/bot/s8y3G66D-xmuPJc8wmRDw) into your own Grok Bot.
2. Tell the bot your shop name.
3. Connect Google Drive and Google Sheets.
4. The bot creates the folders and two Sheets in your Drive.
5. Pick your POS: Square, Toast, Shopify POS, Clover, NCR Aloha, or Other. In this first version, staff email the end-of-day sales report each night. That can be a CSV file or a photo of the Z-report.
6. Add the staff email addresses that will send bills, counts and sales, including yours. Only those senders reach the bot.
7. The bot starts watching its own inbox and gives you the address. Give staff this note: "Put bill, sales or count in the subject. Send photos at Medium size."
8. Pick two days a week for stock counts.
9. You can add recipes, suppliers and par levels now, or later.
10. Email one test bill to the bot address. Check that the supplier, date and total match the paper.

## Tips for staff

- Email bill photos, end-of-day sales and counts to the bot address the owner gives you. You do not need a new app or a new account.
- Put bill, sales or count in the subject.
- Send photos at Medium size, so the bot can open them.

## What it won't do

- It will not email your staff.
- It will not place orders with suppliers.
- This first version does not connect live to your POS. Staff email the end-of-day sales report instead.
- It will not guess a number it could not read.

## What's in this repo

- `skills/coffee-shop-getting-started/SKILL.md`: the first-run setup the bot walks the owner through.
- `skills/coffee-shop-ops/SKILL.md`: the daily work. It covers bills, end-of-day sales, stock counts, the Review queue and low-stock alerts.

To use the skills in your own Grok Bot without the template, add both files as skills, then ask the bot to run `coffee-shop-getting-started`.

## License

MIT. Café Ops Manager is free. The shop's data stays in your own Google Drive.

