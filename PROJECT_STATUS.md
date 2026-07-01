# Adhiniyam Project Status

Last Updated: 2026-07-01

## Project Overview

Adhiniyam is a business, legal, tax, HR and compliance tools website for India.

Live Website: https://www.adhiniyam.com  
GitHub Repository: adhiniyam-website  
Vercel Project: adhiniyam-website  

## Contact Details

Public Email: enquiry@adhiniyam.com  
Call Number: +91 9999395031  
WhatsApp Number: +91 9999395031  
Contact Form Endpoint: https://formspree.io/f/xpqgdvew  

Top contact strip is active above the navbar:
- Left side: Email icon + enquiry@adhiniyam.com
- Right side: Call icon + +91 9999395031

## Current Website Setup

The website includes homepage, free tools page, services page, blog page, about page, contact page, policy pages, sitemap, robots.txt, Google Search Console setup, Formspree contact form, logo/favicon, SVG tool icons and global top contact bar.

## Current Live Tools

1. Invoice Generator
2. Salary Slip Generator
3. New Joiner Salary Calculator
4. GST Calculator
5. PF / ESIC Calculator
6. TDS Calculator
7. HRA Calculator
8. Offer Letter Generator
9. Appointment Letter Generator
10. Experience Letter Generator
11. Relieving Letter Generator
12. Quotation Generator
13. Purchase Order Generator
14. Delivery Challan Generator
15. Credit Note / Debit Note Generator
16. Receipt Generator
17. Full & Final Settlement Calculator
18. Board Resolution Generator
19. Rent Agreement Draft Generator
20. NDA Generator
21. Client Proposal Generator

## Recently Completed Tools

NDA Generator is live, sitemap updated and indexing requested.  
URL: https://www.adhiniyam.com/tools/nda-generator/

Client Proposal Generator is live, sitemap updated and indexing requested.  
URL: https://www.adhiniyam.com/tools/client-proposal-generator/

HRA Calculator is live, sitemap updated and indexing requested.  
URL: https://www.adhiniyam.com/tools/hra-calculator/

## Blog Status

Adhiniyam currently has multiple SEO blogs live, including GST, invoice, payroll, HR, company registration and trademark-related articles.

Examples of live blog topics:
- How to Create a GST Invoice Online
- What is a Salary Slip and Why is it Important?
- Documents Required for GST Registration
- How to Register a Trademark in India
- Company Registration Process in India
- Difference Between Tax Invoice and Bill of Supply
- GST Invoice Format for Services in India
- Common GST Invoice Mistakes to Avoid
- How to Calculate GST on an Invoice
- Offer Letter vs Appointment Letter
- Documents Required From New Employees
- PF and ESIC Contribution Basics
- Private Limited Company vs LLP
- Trademark Registration vs Company Name Registration
- What to Do After Company Registration

## Search Console Status

Google Search Console ownership is verified. Sitemap is submitted at:
https://www.adhiniyam.com/sitemap.xml

For new URLs:
1. Submit updated sitemap.
2. Request indexing.
3. If quota is exceeded, leave remaining URLs for sitemap discovery and request the next day.
4. Avoid repeatedly requesting indexing for unchanged URLs.

## Important Upload Workflow

For every new tool update:
1. Upload the new tool folder inside GitHub `/tools/`.
2. Confirm `tools/new-tool-slug/index.html` and `tools/new-tool-slug/og-image.png`.
3. Upload supporting files:
   - `assets/tools.json`
   - `assets/common.js`
   - `tools/index.html`, if included
   - `sitemap.xml`
   - `README.txt`
4. Upload root `index.html` only when homepage content/design is changed or the tool is being featured on homepage.
5. Wait for Vercel deployment to show Ready.
6. Test the new tool URL, tools listing page and sitemap URL.
7. Submit sitemap and request indexing.

## Known Issue and Fix

Sometimes GitHub browser upload misses nested folders.

Symptom:
- Tool card appears on homepage/tools page
- Direct tool URL gives 404

Cause:
- `assets/tools.json` or `common.js` updated
- Actual tool folder missing from `/tools/`

Fix:
1. Upload only the missing tool folder inside `/tools/`.
2. Confirm `index.html` and `og-image.png` exist in GitHub.
3. Wait for Vercel deployment.
4. Retest URL.

Browser cache issue:
- If old header/footer/tool data appears, hard refresh with Ctrl + Shift + R.
- Versioned `common.js` query strings may be used when needed.

## Recommended Next Workflow

Next planned tool:
1. Income Tax Calculator with Old vs New Regime Comparison

Suggested tools after Income Tax Calculator:
2. Rent Receipt Generator
3. Gratuity Calculator
4. Salary Structure / CTC to In-Hand Calculator
5. EMI Calculator
6. Advance Tax Calculator
7. GST Interest & Late Fee Calculator

## Tool Roadmap Notes

High-demand tools identified:
- GST Invoice Generator
- Salary Slip Generator
- Offer Letter Generator
- Experience Letter Generator
- Rent Receipt Generator
- Income Tax Calculator
- EMI Calculator
- GST Calculator
- HRA Calculator
- Quotation Generator
- Proforma Invoice Generator
- Payment Receipt Generator
- Gratuity Calculator
- Appointment Letter Generator
- Purchase Order Generator

Some tools should be merged into existing tools instead of separate pages:
- GST Invoice / Tax Invoice / Proforma Invoice should be handled inside Invoice Generator.
- Payslip with Company Logo should be handled inside Salary Slip Generator.
- Proposal Generator is covered by Client Proposal Generator.
