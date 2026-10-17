# Vagamon Tour Operators: Research Summary

Workbook: `Vagamon_Specific_Tour_Operators_500_Verified_Emails.xlsx` · Verification date: 2026-10-17

## Headline result

**The 500-email target was not reached.** After 60+ searches, the results had saturated and the same operators kept coming back. That left **30 Kerala-based operators with Vagamon package evidence**, publishing **39 unique business email addresses**. No addresses were guessed or invented.

| Metric | Count |
|---|---|
| Unique eligible operators | 30 |
| Unique business email addresses | 39 |
| Official-source confirmed | 31 |
| Cross-source confirmed | 5 |
| Technical verification passed (MX/SMTP) | 0 (not possible, see below) |
| Unverified, kept but flagged yellow | 3 |
| Candidates excluded (all reasons) | 42 (1 invalid syntax) |
| Duplicate addresses removed | 0 |
| Operators advertising 2N/3D | 10 |
| Operators advertising 3N/4D | 4 |

## Vagamon 2N/3D operators

| Operator | Email | Status |
|---|---|---|
| Kerala.com Travel Division (Vagamon.com), Kochi | reservation@keralatravels.com | Cross-source |
| Lumiere Holidays, Kochi | info@lumiereholidays.com | Official-source |
| Paradise Kerala, Aluva | info@paradise-kerala.com | Official-source |
| Ripples Holidays (vagamonhomestays.com), Ernakulam | ripplesholidays@gmail.com | Cross-source |
| Happy Chutti, Fort Kochi | myhappychutti0@gmail.com | Official-source |
| Anamika Kerala Holidays, Kumily | info@anamikakeralaholidays.com | Official-source |
| Eco Green Kerala Holidays | keralahost@gmail.com | Cross-source |
| Great Indian Tours, Kochi | mail@greatindiantours.com | Official-source |
| Goaroundtheglobe | info@goarountheglobe.in | **Unverified** (email domain differs from website domain) |
| Travelnote Holidays, Kattappana | holidays@travelnotehotels.com | **Unverified** (page has placeholder data) |

## Vagamon 3N/4D operators

| Operator | Email | Status |
|---|---|---|
| Kerala.com Travel Division (Vagamon.com), Kochi | reservation@keralatravels.com | Cross-source |
| Sun and Mist Holidays (keralahouseboat.in), Udayamperoor | info@keralahouseboat.in | Official-source |
| Tranquil Greens Resort, Ramakkalmedu (own Vagamon tour) | bookings@tranquilgreens.com | Official-source |
| Great Indian Tours, Kochi | mail@greatindiantours.com | Official-source |

The other 24 operators, with custom, 1N/2D, 4N/5D or longer multi-destination Vagamon packages, are on the **Other Vagamon Packages** sheet.

## Verification method

1. **Evidence.** For each operator I recorded the package or itinerary URL and the URL where the email appears. Both are clickable in the workbook.
2. **How pages were read.** This research environment's network policy blocked direct page fetches, DNS and SMTP. Page content was therefore read through the web-search engine's extraction of each public page.
3. **Official-source confirmed.** The email is shown on the operator's own website.
4. **Cross-source confirmed.** The same email also appears on a second, different domain, such as a directory, social page or sister site.
5. **Technical verification.** No MX lookup or SMTP probe could be run, so **no address is labelled deliverable**. Run the list through a mailbox-verification service before any outreach.
6. **Unverified.** Kept in the database but highlighted yellow, with the reason in Research Notes.
7. **Syntax.** Every retained address passed a regex syntax check.

## Why the total is low

- Most aggregator listings (TourTravelWorld, Hellotravel, TripClap, Justdial, IndiaMART) mask operator emails.
- Many local Vagamon operators publish only phone or WhatsApp numbers.
- Many sites that rank for "Vagamon package" are based outside Kerala: Delhi, Noida, Chennai, Bengaluru, Kolkata, Himachal and Tamil Nadu. All 42 rejected candidates are listed on the **Excluded Candidates** sheet with reasons.

## Suggested next steps

- Re-run discovery from a network that allows direct page fetches. Use it to unmask directory emails and check live pages, since several source pages are 1–4 years old.
- Verify every address with a mailbox-verification service.
- Follow applicable anti-spam and data-protection rules, such as India's DPDP Act, when contacting these businesses.
