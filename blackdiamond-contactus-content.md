# Hotel The Black Diamond — Contact Us Page Content Replacements

**Page URL:** /contact-us/  
**Method:** FIND & REPLACE in HTML + WordPress Admin settings  
**Page ID:** 84

---

## META TITLE & DESCRIPTION
*(WordPress Admin → Pages → Contact Us → SEO Settings via Rank Math / Yoast)*

| Field | Value |
|-------|-------|
| Meta Title | `Contact Us – Hotel The Black Diamond, Koramangala Bengaluru` |
| Meta Description | `Get in touch with Hotel The Black Diamond. Call us at +91 90080 77824, email info@hoteltheblackdiamond.in, or visit us on Hosur Road, opp. Nexus Forum Mall, Koramangala, Bengaluru.` |

> Title = 57 chars. Description = 175 chars (slightly long — trim to: "Reach Hotel The Black Diamond on Hosur Road, Koramangala. Call +91 90080 77824 or email info@hoteltheblackdiamond.in. We're always here to help." = 144 chars)

---

## PAGE SEO TITLE FIX
*(WordPress Admin → Pages → Contact Us → SEO Title)*

| Find | Replace With |
|------|-------------|
| `Contact Us – Hotel The Black Stone` | `Contact Us – Hotel The Black Diamond` |

> The browser tab and page title currently read "Hotel The Black Stone" — fix in WordPress SEO settings.

---

## GLOBAL HEADER REPLACEMENTS
*(Fix once in Elementor header template — same across all pages)*

| Find | Replace With |
|------|-------------|
| `info@example.com` | `info@hoteltheblackdiamond.in` |
| `King Street, AUS` | `Hosur Road, Koramangala, Bengaluru` |
| `+01 (977) 2599 12` | `+91 90080 77824` |

---

## HEADER PHONE SECTION
*(The large phone number displayed next to the phone icon in the main navigation bar)*

| Find | Replace With |
|------|-------------|
| `+01 (977) 2599 12` | `+91 90080 77824` |

---

## CONTACT US BODY — IMAGE REPLACEMENT

**Section: Left image next to "Reception Always Open"**

The image currently loads from the demo server:
```
src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-20.jpg"
```

| Find | Replace With |
|------|-------------|
| `https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/image-20.jpg` | *(Replace with a real hotel photo uploaded to the site)* |

> ⚠️ Client to provide image. Upload to WordPress Media and use the new URL here.

---

## CONTACT US BODY — CONTENT REPLACEMENTS

All body text on the Contact page is **already correct** from the HTML — the real hotel address, phone, and descriptions are present. Only the **email address in the "Mail Address" icon box** needs to be fixed.

### Mail Address Icon Box

| Find | Replace With |
|------|-------------|
| `info@example.com, domain@example.com` | `info@hoteltheblackdiamond.in` |

---

## CONTACT DETAILS SUMMARY (Already Correct in HTML — No Change Needed)

The following info was found correctly populated in the HTML already:

- **Our Location:** Hotel the BLACK DIAMOND, Hosur Rd, Tavarekere, BACKSIDE, opp. The Forum Mall, Koramangala, Bengaluru, Bangalore 560095 ✅
- **Our Phone:** +91 90080 77824 ✅
- **Map embed:** Searches "hotel the black diamond" ✅
- **Reception Always Open** section text ✅
- **Online Reservations** section text ✅
- **"Drop A Line" / "Feel Free To Contact Us"** section text ✅

> ⚠️ One minor fix: The location address says "opp. The Forum Mall" — confirm with client if it should be "Nexus Forum Mall" (which is the confirmed name). Update accordingly.

---

## GLOBAL FOOTER REPLACEMENTS
*(Fix once in Elementor footer template — same across all pages)*

| Find | Replace With |
|------|-------------|
| `src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/main-logo-2.png"` | Use the logo already uploaded to the site |
| `Laboriosam blandit suspendisse ducimus voluptate commodi, itaque. Veritatis iac ulisarchitecto, eiusmillo ea eleifendte mpore,debitis! Atque hac. Veritatis commodi, itaque.` | `Your comfort is our commitment. Located in the heart of Koramangala, Hotel The Black Diamond offers modern rooms and warm hospitality at every budget.` |
| `Address : 22th Streets, Colorado` | `Address : Hosur Rd, Tavarekere, opp. Nexus Forum Mall, Koramangala, Bengaluru – 560095` |
| `Email : info@example.com` | `Email : info@hoteltheblackdiamond.in` |
| `Phone : +988-256-266-88` | `Phone : +91 90080 77824` |
| `Fax : (+01)125-365-88` | *(delete this line entirely)* |
| `Copyright © 2026 Bosa Hotel. Powered by` | `Copyright © 2026 Hotel The Black Diamond. Website by` |

---

## OFF-CANVAS SIDEBAR REPLACEMENT
*(The slide-out menu from the hamburger icon — fix once globally)*

| Find | Replace With |
|------|-------------|
| `Est adipisci rutrum minim hat dolorum, nobis nonummy natoque dolores delectus magna turpis.` | `Your comfort is our commitment. Located in the heart of Koramangala, Hotel The Black Diamond offers modern rooms and warm hospitality at every budget.` |

---

## SUMMARY CHECKLIST FOR DEVELOPER / ADMIN

- [ ] Fix Contact Us page SEO title (Black Stone → Black Diamond) in WordPress
- [ ] Set meta title & description for Contact Us page (Rank Math / Yoast)
- [ ] Fix header email, location, phone (global template — if not already done)
- [ ] Fix large phone number in header nav bar: `+01 (977) 2599 12` → `+91 90080 77824`
- [ ] Fix Mail Address icon box email: `info@example.com, domain@example.com` → `info@hoteltheblackdiamond.in`
- [ ] Replace demo image next to "Reception Always Open" with real hotel photo (client to provide)
- [ ] Fix footer logo (demo.bosathemes.com → site logo)
- [ ] Fix footer body text (lorem ipsum → real description)
- [ ] Fix footer address, email, phone (if not already done)
- [ ] Delete Fax line from footer
- [ ] Fix footer copyright line (Bosa Hotel → Hotel The Black Diamond)
- [ ] Fix off-canvas sidebar blurb (if not already done)
- [ ] ⚠️ Confirm with client: "opp. The Forum Mall" or "opp. Nexus Forum Mall" in location box

---

*Prepared by AdsPilot | April 2026*
