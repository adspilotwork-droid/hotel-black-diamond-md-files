# Hotel The Black Diamond — About Us Page Content Replacements
**Page URL:** https://lightgray-toad-464407.hostingersite.com/about-us/  
**Prepared by:** AdsPilot  
**Scope:** About Us page HTML-level find & replace — copy-paste ready for dev handoff

---

> **How to use this doc:**  
> Each block shows the exact text to **FIND** in the HTML source and what to **REPLACE WITH**.  
> Use browser Ctrl+F or VS Code search to locate each string.  
> Fields marked ⚠️ need client confirmation before publishing.

---

## META TITLE & DESCRIPTION
*(WordPress Admin → Pages → About Us → SEO Settings via Rank Math / Yoast)*

| Field | Value |
|-------|-------|
| Meta Title | `About Us – Hotel The Black Diamond, Koramangala Bengaluru` |
| Meta Description | `Learn about Hotel The Black Diamond — a warm, affordable hotel on Hosur Road, Koramangala, Bengaluru. Modern rooms, genuine hospitality, and everything you need for a comfortable stay.` |

> Title = 57 chars. Description = 185 chars — trim if needed to: "Hotel The Black Diamond, Koramangala — affordable rooms, modern comfort, and warm hospitality on Hosur Road, opp. Nexus Forum Mall, Bengaluru." = 142 chars.

---

## 🚨 CRITICAL — Page Title Tag

This is the most embarrassing one. The browser tab currently reads "Hotel The Black Stone" — wrong name entirely.

```
FIND (in <head> section):
<title>About Us – Hotel The Black Stone</title>

REPLACE WITH:
<title>About Us – Hotel The Black Diamond</title>
```

> Note: This is also likely set in WordPress under Settings > General or via Yoast/SEO plugin. Fix it there too so it doesn't revert on next save.

---

## SECTION 1 — Top Bar (Header Strip)

Same shared header as homepage. Apply the same fixes here too.

### Email

```
FIND:
<span class="elementor-icon-list-text">info@example.com</span>

REPLACE WITH:
<span class="elementor-icon-list-text">info@hoteltheblackdiamond.in</span>
```

### Location

```
FIND:
<span class="elementor-icon-list-text">King Street, AUS</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Hosur Road, Koramangala, Bengaluru</span>
```

---

## SECTION 2 — Header Phone Number

```
FIND:
<h3 class="elementskit-section-subtitle  ">24/7 HOTEL SERVICES:</h3>

REPLACE WITH:
<h3 class="elementskit-section-subtitle  ">24/7 RESERVATIONS:</h3>
```

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">+01 (977) 2599 12</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">+91 90080 77824</h2>
```

---

## SECTION 3 — Off-Canvas Sidebar Blurb

The hamburger menu sidebar has a lorem ipsum description that shows when the menu slides open.

```
FIND:
<p>Est adipisci rutrum minim hat dolorum, nobis nonummy natoque dolores delectus magna turpis.</p>

REPLACE WITH:
<p>Hotel The Black Diamond — Koramangala's most convenient boutique stay, right behind Nexus Forum Mall on Hosur Road.</p>
```

---

## SECTION 4 — About Us Main Section

### Section heading

The main heading currently reads "We can help you feel more comfortable" — this is already decent but it's copied from the homepage. Good to differentiate it.

```
FIND (in the About Us page body, not the homepage):
<h2 class="ekit-heading--title elementskit-section-title ">We can help you feel more comfortable</h2>
(context: inside elementor-88, the about-us page content)

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Where Every Guest Feels Right at Home</h2>
```

### Main intro paragraph

This one is already real content. Keep it — it's good:

```
✅ KEEP AS-IS:
<p>Welcome to The Black Diamond, where comfort feels like home and every guest is treated like family. We pride ourselves on creating a warm, inviting atmosphere paired with quality service and attention to detail. Whether you're here for a short visit or an extended stay, we aim to make every moment special.</p>
```

### Bullet point 1

```
✅ KEEP AS-IS:
<span class="elementor-icon-list-text">The Black Diamond is a symbol of strength, elegance, and rarity.</span>
```

### Bullet point 2

```
✅ KEEP AS-IS:
<span class="elementor-icon-list-text">Our hotel embodies these qualities by offering exceptional comfort, modern design, and personalized hospitality—creating a stay that's truly one of a kind.</span>
```

### Progress bar values

```
FIND:
data-value="90"
(label: Positive Reviews — on About Us page)

REPLACE WITH:
data-value="95"
```

```
FIND:
data-value="98"
(label: Happy Customers — on About Us page)

REPLACE WITH:
data-value="92"
```

> ⚠️ Confirm both percentages with client.

---

## SECTION 5 — Second Text Block (below photo carousel)

This block appears after the image carousel and before the counters.

```
✅ KEEP AS-IS — Already real content:
<p>The Black Diamond is more than a place to stay—it's an experience. Designed for travelers who appreciate style, comfort, and exceptional service, our hotel delivers a seamless blend of modern amenities and timeless design. From relaxing spaces to vibrant surroundings, we provide the perfect setting to unwind, connect, and explore.</p>
```

---

## SECTION 6 — Stats Counters (About Us version)

This page has 3 counters with different IDs than the homepage. Fix all 3:

```
FIND:    data-to-value="25"   (label: YEARS EXPERIENCE)
REPLACE: data-to-value="10"
```

```
FIND:    data-to-value="420"  (label: LUXURY ROOMS)
REPLACE: data-to-value="20"
```

```
FIND:    data-to-value="23"   (label: SATISFIED GUEST)
REPLACE: data-to-value="500"
```

> ⚠️ All 3 values need client confirmation. "420 luxury rooms" and "25 years experience" are obviously demo placeholders for a hotel that appears to have opened recently.

---

## SECTION 7 — OUR VALUES Section

### Section heading

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">Visit Our Natural Paradise &amp; Reconnect With Yourself</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">What Makes The Black Diamond Different</h2>
```

### OUR VALUES paragraph

```
✅ KEEP AS-IS — Already good content:
<p>At The Black Diamond, we redefine modern luxury with a bold edge. Inspired by the rarity and strength of the black diamond, our hotel blends refined elegance with contemporary comfort. Every detail—from our thoughtfully designed rooms to our personalized service—is crafted to create an unforgettable stay. Whether you're visiting for business or leisure, The Black Diamond offers a sanctuary where sophistication meets warmth.</p>
```

### YouTube Video Link

The page has a YouTube video widget embedded. Current link:
```
https://www.youtube.com/embed/VhBl3dHT5SY
```

This is a placeholder YouTube video (not the hotel's). Ask the client if they have a hotel walkthrough/reel video and replace the `href` accordingly:

```
FIND:
href="https://www.youtube.com/embed/VhBl3dHT5SY?feature=oembed?playlist=VhBl3dHT5SY&amp;mute=0&amp;autoplay=0&amp;loop=no&amp;controls=0&amp;start=0&amp;end="

REPLACE WITH:
href="[CLIENT'S YOUTUBE VIDEO URL]"
```

> ⚠️ If no video is available, hide this section in Elementor or replace with a static image.

---

## SECTION 8 — Footer (Shared — same fixes as Homepage)

The footer on this page is the same shared footer template. Apply the same replacements as the homepage doc.

### Footer logo (still demo site)

```
FIND:
<img class="bew-site-logo-img" src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/main-logo-2.png" alt="default-logo">

REPLACE WITH:
<img class="bew-site-logo-img" src="https://lightgray-toad-464407.hostingersite.com/wp-content/uploads/2026/04/resized_logo_no_stretch.png" alt="Hotel The Black Diamond">
```

> Note: The About Us page already uses the correct logo (`resized_logo_no_stretch.png`) in the header and sidebar — only the footer still pulls from the demo site.

### Footer about blurb

```
FIND:
<p>Laboriosam blandit suspendisse ducimus voluptate commodi, itaque. Veritatis iac ulisarchitecto, eiusmillo ea eleifendte mpore,debitis! Atque hac. Veritatis commodi, itaque.</p>

REPLACE WITH:
<p>Hotel The Black Diamond — Koramangala, Bengaluru. Budget-friendly rooms with modern amenities, complimentary breakfast, and warm hospitality right in the city's most vibrant neighbourhood.</p>
```

### Footer address

```
FIND:
<span class="elementor-icon-list-text">Address : 22th Streets, Colorado</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Address : Hosur Rd, Tavarekere, opp. Nexus Forum Mall, Koramangala, Bengaluru 560095</span>
```

### Footer email

```
FIND:
<span class="elementor-icon-list-text">Email : info@example.com</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Email : info@hoteltheblackdiamond.in</span>
```

### Footer phone

```
FIND:
<span class="elementor-icon-list-text">Phone : +988-256-266-88</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Phone : +91 90080 77824</span>
```

### Footer fax → WhatsApp

```
FIND:
<span class="elementor-icon-list-text">Fax : (+01)125-365-88</span>

REPLACE WITH:
<span class="elementor-icon-list-text">WhatsApp : +91 90080 77824</span>
```

---

## What's Good — No Changes Needed

These sections on the About Us page are already well-written with real content:

| Section | Status |
|---|---|
| Main intro paragraph | ✅ Keep — real, well-written content |
| Both bullet points | ✅ Keep — accurate brand messaging |
| "The Black Diamond is more than a place..." paragraph | ✅ Keep — real content |
| OUR VALUES paragraph | ✅ Keep — good brand copy |
| Photo carousel (4 hotel photos) | ✅ Keep — real hotel images uploaded |

---

## Summary — Items Requiring Client Confirmation Before Publishing

| # | Item | Current Value | Action Required |
|---|---|---|---|
| 1 | Page title tag | "Hotel The Black Stone" | Fix to "Hotel The Black Diamond" in WordPress |
| 2 | Positive Reviews % | 90% | Confirm real value |
| 3 | Happy Customers % | 98% | Confirm real value |
| 4 | Years Experience counter | 25 | Confirm actual years in business |
| 5 | Luxury Rooms counter | 420 | Confirm actual room count |
| 6 | Satisfied Guest counter | 23 | Confirm realistic number |
| 7 | YouTube video | Placeholder video | Provide hotel's own video URL or hide section |
| 8 | Client email | info@example.com | Confirm real email |

---

*Document prepared by AdsPilot | Hotel The Black Diamond — About Us Page Dev Handoff*
