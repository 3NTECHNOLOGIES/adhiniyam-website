# Adhiniyam Project Status

Last Updated: 2026-07-01

## 1. Project Overview

Adhiniyam.com is a business, legal, tax, HR and compliance tools website for India.

The website is positioned as:

- Free business utility tools platform
- GST, compliance, payroll and business document support platform
- Lead-generation website for professional services
- Future-ready platform for monetisation, sponsored placements, premium tools and custom business tools

## 2. Live Website

Primary Website:

https://www.adhiniyam.com

Redirect:

https://adhiniyam.com redirects to https://www.adhiniyam.com

## 3. Technical Setup

GitHub Repository:

adhiniyam-website

Vercel Project:

adhiniyam-website

Hosting:

Vercel static website

Domain Provider:

GoDaddy

Primary Domain:

www.adhiniyam.com

## 4. Contact Details

Email shown on website:

enquiry@adhiniyam.com

Call / WhatsApp:

+91 9999395031

Contact form endpoint:

https://formspree.io/f/xpqgdvew

Address:

Do not show address on website.

## 5. Global UI Notes

Current global header includes:

- Top slim contact strip above navbar
- Left side: email icon + enquiry@adhiniyam.com
- Right side: call icon + +91 9999395031
- Navbar with Adhiniyam logo
- Navigation: Home, Free Tools, Services, Blog, About, Contact
- Header buttons: Explore Tools and WhatsApp

Important fix already done:

Top contact strip icon size was fixed because SVG icons became too large and covered the page.

Current tool cards use attractive SVG-style icons instead of first-letter initials.

## 6. Live Tools

The following tools are live or were added to the project:

1. Invoice Generator
2. Salary Slip Generator
3. New Joiner Salary Calculator
4. GST Calculator
5. PF / ESIC Calculator
6. TDS Calculator
7. Offer Letter Generator
8. Appointment Letter Generator
9. Experience Letter Generator
10. Relieving Letter Generator
11. Quotation Generator
12. Purchase Order Generator
13. Delivery Challan Generator
14. Credit Note / Debit Note Generator
15. Receipt Generator
16. Full & Final Settlement Calculator

Latest pending / next tool package:

Board Resolution Generator

Expected URL:

https://www.adhiniyam.com/tools/board-resolution-generator/

## 7. Blog Status

Known blog themes already created:

- GST invoice
- salary slip
- GST registration documents
- trademark registration
- company registration process
- tax invoice vs bill of supply
- GST invoice format for services
- common GST invoice mistakes
- GST calculation
- offer letter vs appointment letter
- employee joining documents
- PF and ESIC basics
- Private Limited Company vs LLP
- trademark registration vs company name registration
- what to do after company registration

## 8. SEO / Search Console Status

Google Search Console:

Domain property verified for adhiniyam.com

Sitemap:

https://www.adhiniyam.com/sitemap.xml

robots.txt:

https://www.adhiniyam.com/robots.txt

Workflow already used:

- Submit sitemap after every new tool/blog batch.
- Request indexing for each new important URL.
- If URL inspection quota is exceeded, submit remaining URLs next day.
- Do not repeatedly request indexing for same URL unless major update is made.

## 9. Standard New Tool Upload Workflow

For every new tool, use this safe method:

Step 1:

Upload the new tool folder inside GitHub's tools folder.

Example:

tools/new-tool-slug/

Confirm these files exist:

tools/new-tool-slug/index.html
tools/new-tool-slug/og-image.png

Step 2:

Upload supporting files in correct locations:

assets/tools.json
assets/common.js
tools/index.html
sitemap.xml
README.txt

Sometimes index.html at root may also be updated if homepage featured cards change.

Step 3:

Wait for Vercel deployment to show Ready.

Step 4:

Test:

https://www.adhiniyam.com/tools/new-tool-slug/
https://www.adhiniyam.com/tools/
https://www.adhiniyam.com/sitemap.xml

Step 5:

Submit updated sitemap in Search Console.

Step 6:

Request indexing for the new tool URL.

## 10. Common Issue and Fix

Issue:

A tool card shows on homepage/tools page but direct tool URL gives 404.

Meaning:

assets/tools.json or common.js updated, but actual tool folder is missing or not deployed.

Fix:

Upload the new tool folder inside /tools/ again and confirm index.html exists.

Issue:

Direct tool URL works but card is not showing as Live.

Meaning:

Tool folder exists, but tools.json/common.js/tools/index.html are not updated.

Fix:

Upload supporting files again.

Issue:

Update uploaded but not reflected on website.

Possible causes:

- GitHub upload did not commit.
- Vercel deployment not Ready.
- Browser cache.
- common.js cached.

Fix:

- Check GitHub path.
- Check Vercel deployment.
- Hard refresh with Ctrl + Shift + R.
- Add cache/version tag if needed.

## 11. Important Project Rule

Adhiniyam should not depend only on ChatGPT chat history.

The permanent source of truth should be:

- GitHub repository
- PROJECT_STATUS.md
- CHANGELOG.md
- NEXT_TASKS.md

If chat history disappears, paste or upload these files in the new chat and ask ChatGPT to continue.
