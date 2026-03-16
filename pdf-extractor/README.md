# PDF Directory Extractor

## Quick Links
- [Use my pre-built GPT](https://chatgpt.com/g/g-68072ef7b3948191a6e238a6c0c29fe9-tech-tony-pdf-directory-extractor) (ChatGPT Plus required)
- [System prompt to copy](./system-prompt.md)

## What It Does

Extracts structured data from PDF directories of professionals. Turn a messy PDF roster into clean, usable data in seconds.

**Input:** PDF with professional listings (directories, rosters, membership lists)

**Output:** Clean table or JSON with:
- Name (first, last)
- Profession/Industry
- Title
- Company
- Full address (street, city, state, zip)
- Phone, email, website
- Notes (certifications, roles, awards)

## Use Cases

- Conference attendee lists → CRM import
- Professional association directories → Lead lists
- Membership rosters → Database entries
- Any PDF with contact information → Structured data

## Requirements
- ChatGPT Plus subscription ($20/month)
- PDF file to process

## Example Output

```json
{
  "first_name": "John",
  "last_name": "Smith",
  "professional": "Real Estate",
  "title": "Broker",
  "company_name": "Smith Realty Group",
  "street_address": "123 Main St, Suite 400",
  "city": "Los Angeles",
  "state": "CA",
  "zip_code": "90001",
  "phone_number": "(310) 555-1234",
  "email": "john@smithrealty.com",
  "website_address": "www.smithrealty.com",
  "record_notes": "Top Producer 2024, Executive Committee"
}
```

## Files
- `system-prompt.md` — The exact instructions to paste into your own GPT
