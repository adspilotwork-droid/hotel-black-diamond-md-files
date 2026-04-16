# Hotel The Black Diamond — Homepage Content Replacements
**Website:** https://lightgray-toad-464407.hostingersite.com/  
**Prepared by:** AdsPilot  
**Scope:** Homepage HTML-level find & replace — copy-paste ready for dev handoff

---

> **How to use this doc:**  
> Each block shows the exact text to **FIND** in the HTML source and what to **REPLACE WITH**.  
> Use browser Ctrl+F or VS Code search to locate each string.  
> Fields marked ⚠️ need client confirmation before publishing.

---

## META TITLE & DESCRIPTION
*(WordPress Admin → Pages → Home → SEO Settings via Rank Math / Yoast)*

| Field | Value |
|-------|-------|
| Meta Title | `Hotel The Black Diamond – Affordable Rooms in Koramangala, Bengaluru` |
| Meta Description | `Hotel The Black Diamond offers clean, comfortable rooms starting at ₹2,200/night in Koramangala, Bengaluru. Located on Hosur Road, opp. Nexus Forum Mall. Book directly at +91 90080 77824.` |

> Title = 65 chars. Description = 187 chars — trim if needed to: "Affordable hotel rooms in Koramangala, Bengaluru. Complimentary breakfast, free Wi-Fi, and 24/7 service. Hosur Road, opp. Nexus Forum Mall. From ₹2,200/night." = 159 chars.

---

## SECTION 1 — Top Bar (Header Strip)

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

### Phone label

```
FIND:
<h3 class="elementskit-section-subtitle  ">24/7 HOTEL SERVICES:</h3>

REPLACE WITH:
<h3 class="elementskit-section-subtitle  ">24/7 RESERVATIONS:</h3>
```

### Phone number

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">+01 (977) 2599 12</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">+91 90080 77824</h2>
```

---

## SECTION 3 — Hero Banner

### H1 Headline

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">The Luxury Experience With Beautiful &amp; Unique Place</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Your Perfect Stay in the Heart of Koramangala</h2>
```

### Hero subtext

```
FIND:
<p>&nbsp;At Black Diamond Hotel, we believe a great stay goes beyond a comfortable room. It's about creating moments that feel effortless and memorable.</p>

REPLACE WITH:
<p>At The Black Diamond, we blend modern comfort with warm hospitality — just steps from Nexus Forum Mall, right in the heart of Bengaluru.</p>
```

---

## SECTION 4 — About Us (Homepage Snippet)

### Section heading

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">We can help you feel more comfortable</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">We Make Every Stay Feel Like Home</h2>
```

### About paragraph

```
FIND:
<p>Founded with a passion for hospitality, our hotel combines modern amenities with warm, attentive service. Located in Koramangala, we provide the perfect base to explore everything koramangala has to offer.</p>

REPLACE WITH:
<p>Tucked behind Nexus Forum Mall on Hosur Road, The Black Diamond offers clean, air-conditioned rooms with free Wi-Fi, complimentary breakfast, and round-the-clock service at an honest price.</p>
```

### Bullet point

```
FIND:
<span class="elementor-icon-list-text">Our team is dedicated to making every guest feel at home — whether it's your first visit or your tenth.</span>

REPLACE WITH:
<span class="elementor-icon-list-text">Our team is here around the clock — whether it's your first visit or your fiftieth, you will always leave with a smile.</span>
```

### Progress bar values (in `data-value` attribute)

```
FIND:
data-value="90"
(label: Positive Reviews)

REPLACE WITH:
data-value="95"
```

```
FIND:
data-value="98"
(label: Happy Customers)

REPLACE WITH:
data-value="92"
```

> ⚠️ Confirm these percentages with the client before publishing.

---

## SECTION 5 — Facilities Section

### Section heading

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">Our Facilities</h2>
(inside the OUR FACILITIES block)

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Everything You Need for a Comfortable Stay</h2>
```

### Section intro paragraph

```
FIND:
<p>Each of our rooms and suites is crafted to offer a relaxing retreat after a day of travel or exploration.</p>

REPLACE WITH:
<p>From in-room dining to free Wi-Fi and complimentary breakfast, we have got everything covered so you can simply relax.</p>
```

### Facility Card 1 — Room Services

```
FIND:
<p>Enjoy the convenience of our in-room dining service, available to bring freshly prepared meals مباشرة to your door.</p>

REPLACE WITH:
<p>Hot meals and snacks delivered fresh to your room, available any time of the day.</p>
```

### Facility Card 2 — Swimming Pool

```
FIND (first instance of this lorem ipsum):
<p>Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.</p>

REPLACE WITH:
<p>Cool off and unwind in our clean, well-maintained outdoor pool area after a long day.</p>
```

### Facility Card 3 — Tea & Breakfast

```
FIND (second instance of this lorem ipsum):
<p>Proin odio quis harum mi unde nostrum totam soluta natoque fermentum irure pretium vero laudantium tellus expe.</p>

REPLACE WITH:
<p>Start your morning right with our complimentary breakfast served fresh daily for all guests.</p>
```

---

## SECTION 6 — Stats Bar (4 Counters)

These are controlled by the `data-to-value` attribute in each counter widget.

```
FIND:    data-to-value="23"   (label: Happy Clients)
REPLACE: data-to-value="500"

FIND:    data-to-value="600"  (label: Our Staffs)
REPLACE: data-to-value="15"

FIND:    data-to-value="420"  (label: LUXURY ROOMS)
REPLACE: data-to-value="20"

FIND:    data-to-value="40"   (label: Win Awards)
REPLACE: data-to-value="5"
```

> ⚠️ All 4 values need client confirmation. Demo numbers are wildly inflated (600 staff, 420 rooms) for a boutique hotel.

---

## SECTION 7 — Rooms Section

### Section intro paragraph

```
FIND:
<p>Laboris eum eligendi dapibus euismod proin, vivamus, rutrum iusto minim, delectus tempore corrupti elementum cubilia rerum. Conubia officiis, eges fugiat error natoque libero.</p>
(inside the BEST LUXURY ROOM heading block)

REPLACE WITH:
<p>Choose from our well-appointed rooms — each designed for comfort, cleanliness, and a restful night's sleep in Koramangala.</p>
```

### Room card descriptions

All 6 cards currently show the same lorem ipsum. Replace each in document order:

```
FIND (all 6 instances):
<p>Purus cumque consectetuer facere cubilia urna nostra aliquip, eum suscipit.</p>
```

**Card 1 — Deluxe Single Room**
```
REPLACE WITH:
<p>A cozy, air-conditioned room with a comfortable single bed and complimentary Wi-Fi.</p>
```

**Card 2 — Deluxe Double Room**
```
REPLACE WITH:
<p>Spacious double room with modern furnishings, flat-screen TV, and daily housekeeping.</p>
```

**Card 3 — Super Deluxe Single Person**
```
REPLACE WITH:
<p>An upgraded single room with premium bedding and enhanced in-room amenities.</p>
```

**Card 4 — Super Deluxe 2 Person**
```
REPLACE WITH:
<p>Perfect for couples — a well-furnished room with all modern comforts included.</p>
```

**Card 5 — Super Deluxe 3 Person**
```
REPLACE WITH:
<p>Ideal for small groups, with ample space, premium amenities, and a relaxed vibe.</p>
```

**Card 6 — Single Sweet Room**
```
REPLACE WITH:
<p>Our most spacious room — a suite-style stay with luxury finishing and extra comfort.</p>
```

### Fix wrong currency on last room

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title "><span><span>$100</span></span>/NIGHT</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title "><span><span>Rs. 4500</span></span>/NIGHT</h2>
```

> ⚠️ Confirm actual price with client. Rs. 4500 is a suggested value based on the pricing ladder (2200 → 2500 → 2600 → 3000 → 3500 → 4500).

---

## SECTION 8 — Feature Icons (4 Mini Highlights)

### Value For Money

```
FIND (first instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Quality rooms at honest, budget-friendly prices you can count on.</p>
```

### Store Luggage

```
FIND (second instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Safe luggage storage available for early arrivals and late checkouts.</p>
```

### Passionate Room — rename heading + description

```
FIND heading:
<h2 class="ekit-heading--title elementskit-section-title ">Passionate Room</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Well-Kept Rooms</h2>
```

```
FIND (third instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Every room is cleaned and prepared with careful attention to detail.</p>
```

### Diverse Destination

```
FIND (fourth instance):
<p>Deleniti nulla class primis corporis proin dignissim.</p>

REPLACE WITH:
<p>Steps from Nexus Mall, restaurants, Christ University, and more.</p>
```

---

## SECTION 9 — Testimonials

### Section intro paragraph

```
FIND:
<p>Laboris eum eligendi dapibus euismod proin, vivamus, rutrum iusto minim, delectus tempore corrupti elementum cubilia rerum. Conubia officiis, eges fugiat error natoque libero.</p>
(inside the OUR TESTIMONIAL heading block)

REPLACE WITH:
<p>Don't just take our word for it — hear what our guests say about their stay at The Black Diamond.</p>
```

### Review 1 — Text

```
FIND:
<p>I had an excellent experience at this hotel. From check-in to check-out, everything was smooth and professional. The room was spotless, well-maintained, and very comfortable. The staff went above and beyond to make sure my stay was enjoyable. The amenities were great, especially the breakfast and pool area. Highly recommend this place for anyone looking for quality and comfort.</p>

REPLACE WITH:
<p>The Black Diamond was exactly what I needed — clean rooms, helpful staff, and a great location. The complimentary breakfast was a lovely touch. Being right behind Forum Mall made everything so convenient. I will definitely stay here again on my next Bengaluru visit.</p>
```

### Review 1 — Reviewer name

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">Deepak Kumar</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Rajesh M.</h2>
```

### Review 2 — Text

```
FIND:
<p>The hotel overall was nice and in a convenient location. The room was clean, and the staff were polite. However, the Wi-Fi was a bit slow, and the check-in process took longer than expected. With a few improvements, this could be an excellent place to stay.</p>

REPLACE WITH:
<p>Good value for money in Koramangala. The room was tidy, the bed was comfortable, and check-in was quick. Staff were helpful throughout. Wi-Fi worked well and the location is hard to beat — plenty of restaurants and cafes within walking distance.</p>
```

### Review 2 — Reviewer name

```
FIND:
<h2 class="ekit-heading--title elementskit-section-title ">pooja kumari</h2>

REPLACE WITH:
<h2 class="ekit-heading--title elementskit-section-title ">Ananya S.</h2>
```

> ⚠️ Strongly recommend replacing both reviews with real Google review text + actual reviewer names for credibility. Get these from the client's Google Maps listing.

---

## SECTION 10 — Blog Section

### Section intro paragraph

```
FIND:
<p>Laboris eum eligendi dapibus euismod proin, vivamus, rutrum iusto minim, delectus tempore corrupti elementum cubilia rerum. Conubia officiis, eges fugiat error natoque libero.</p>
(inside the RECENT BLOG heading block)

REPLACE WITH:
<p>Travel tips, local guides, and hospitality insights from our team at The Black Diamond, Koramangala.</p>
```

---

## SECTION 11 — Footer

### Footer logo (still pointing to demo site)

```
FIND:
<img class="bew-site-logo-img" src="https://demo.bosathemes.com/bosa/hotel/wp-content/uploads/sites/124/2024/07/main-logo-2.png" alt="default-logo">

REPLACE WITH:
<img class="bew-site-logo-img" src="https://lightgray-toad-464407.hostingersite.com/wp-content/uploads/2026/03/cropped-cropped_black_diamond-300x42.png" alt="Hotel The Black Diamond">
```

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

### Footer fax (remove / repurpose)

```
FIND:
<span class="elementor-icon-list-text">Fax : (+01)125-365-88</span>

REPLACE WITH:
<span class="elementor-icon-list-text">WhatsApp : +91 90080 77824</span>
```

---

## Summary — Items Requiring Client Confirmation Before Publishing

| # | Item | Current Value | Suggested Value |
|---|---|---|---|
| 1 | Positive Reviews % | 90% | 95% |
| 2 | Happy Customers % | 98% | 92% |
| 3 | Happy Clients counter | 23 | 500 |
| 4 | Our Staffs counter | 600 | 15 |
| 5 | Luxury Rooms counter | 420 | 20 |
| 6 | Win Awards counter | 40 | 5 |
| 7 | Single Sweet Room price | $100 USD | Rs. 4500? |
| 8 | Client email | info@example.com | Confirm real email |
| 9 | Review 1 name + text | Deepak Kumar (fake) | Real Google reviewer |
| 10 | Review 2 name + text | Pooja Kumari (fake) | Real Google reviewer |

---

*Document prepared by AdsPilot | Hotel The Black Diamond — Homepage Dev Handoff*
