---
title: Free alternatives to paid Google Sheets add-ons (open-source scripts)
description: Free, open-source Apps Script alternatives to popular paid or limited Google Sheets add-ons for mail merge, PDF generation, count by color, CSV import, form emails and more.
image: https://decodedxr.github.io/free-google-sheets-scripts/assets/cover.png
---
{% raw %}

# Free alternatives to paid Google Sheets add-ons

Many popular Google Sheets add-ons are free to install but limit the free tier: emails per day, documents per month, a trial that runs out. If you need one of these jobs done regularly and would rather not pay a subscription, a single Apps Script file often does the same core job for free, inside your own Google account.

Below, each job lists a well-known add-on, what its free tier looked like when we checked (October 2026, from the vendor's listing or third-party reviews; **always check the vendor's current pricing**), and a free, MIT-licensed script that covers the core of it. The add-ons are good products and often do more, with better UIs, support and extra features. The scripts suit people who want the basic job done with no limits beyond Google's own quotas.

| Job | Popular add-on (free tier when checked) | Free script |
|---|---|---|
| Mail merge from a sheet | Yet Another Mail Merge (reported as about 50 recipients/day free) | [Free Mail Merge](https://github.com/DecodedXR/sheets-mail-merge): Gmail draft as the template, per-row attachments, a status column |
| Documents/PDFs from rows | Form Publisher (reported 20 documents/month free) | [Doc Merge](https://github.com/DecodedXR/sheets-doc-merge): a Google Doc template → one PDF per row |
| Count or sum cells by color | Ablebits Function by Color (30-day trial, then a subscription) | [Count and Sum by Color](https://github.com/DecodedXR/count-by-color): `COUNTBYCOLOR` and `SUMBYCOLOR` formulas |
| Import CSV files automatically | SheetsIE (reported 10 files/month free); Sheetgo (reported 1 connection free) | [Gmail CSV to Sheets](https://github.com/DecodedXR/gmail-csv-to-sheets) for email attachments and [Drive CSV to Sheets](https://github.com/DecodedXR/drive-csv-to-sheets) for a Drive folder |
| Email form respondents | Various form-notification add-ons | [Form Auto-Reply](https://github.com/DecodedXR/form-auto-reply): a personalized email per response, using their answers |
| Collect files without a Google sign-in | Paid file-request tools | [Drive Upload Form](https://github.com/DecodedXR/drive-upload-form): a public upload page into your Drive folder |

Some free add-ons are excellent and unlimited. **Autocrat**, for example, is a free document-merge add-on. When a free add-on already does what you need, use it. The scripts here are most useful when you hit a free-tier limit, or when your organization blocks Marketplace add-ons but allows Apps Script.

## Jobs with no common add-on

Some everyday jobs have no well-known add-on, and usually get solved with a script copied from a forum. These are tidied-up, tested versions:

- **Automatic timestamps and an edit log:** [Sheets Edit Tracker](https://github.com/DecodedXR/sheets-edit-tracker)
- **Move rows to a Done tab, delete blank rows:** [Row Cleanup](https://github.com/DecodedXR/sheets-row-cleanup)
- **Dependent dropdowns on every row:** [Dependent Dropdowns](https://github.com/DecodedXR/dependent-dropdowns)
- **Deadline reminder emails:** [Deadline Reminders](https://github.com/DecodedXR/sheets-deadline-reminders)
- **Sheet rows to Google Calendar events:** [Sheets to Calendar](https://github.com/DecodedXR/sheets-to-calendar)
- **Pre-filled Google Form links per row:** [Form Prefill Links](https://github.com/DecodedXR/form-prefill-links)

## Add-on or script: how to choose

**Choose an add-on** when several non-technical people will use it, you want support, or you need a feature the script doesn't have (open tracking, scheduling UIs, many templates).

**Choose a script** when you've hit a free-tier limit, you don't want a third party to have access to your data, or add-ons are blocked in your organization. Setup is pasting one file into **Extensions → Apps Script**. The script runs in your account, under Google's normal daily quotas (for example, Gmail sending limits).

---

[All free Google Sheets scripts](https://decodedxr.github.io/free-google-sheets-scripts/)
{% endraw %}
