# G Fresh Mart — Franchise Store Profile Page
## Page structure, wireframe & content specification (template for all store pages)

**Page type:** Repeatable store profile template (one page per franchise location)
**Primary goal:** Convert franchise-curious visitors into enquiries using proof from a real store
**Secondary goals:** Local SEO ("supermarket franchise in <city>"), brand credibility, internal linking across stores
**URL pattern:** `/franchise-stores/<city>-<locality>` e.g. `/franchise-stores/indore-vijay-nagar`

---

## 1. Visual wireframe (top to bottom)

```
┌──────────────────────────────────────────────────────────────┐
│ [HEADER / NAV]  Logo | Stores | Franchise | About | Contact  │
│                                     [Enquire About Franchise]│
└──────────────────────────────────────────────────────────────┘

  Home › Franchise Stores › Madhya Pradesh › Indore › Vijay Nagar     [BREADCRUMB]

┌──────────────────────────────────────────────────────────────┐
│ [HERO]                                                       │
│  ┌────────────────────────┐   Badge: FRANCHISE STORE · LIVE  │
│  │                        │   H1  G Fresh Mart         │
│  │   LARGE STORE PHOTO    │       Vijay Nagar, Indore        │
│  │   (exterior/facade)    │   Owned by Meera Rathi · Since   │
│  │                        │   March 2024                     │
│  │                        │   2-line intro sentence          │
│  └────────────────────────┘   [Enquire About a Franchise]    │
│                               [Watch Owner's Story ▶]        │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [QUICK FACTS BAR]  2,400 sq ft │ ₹38–42 L │ 65 days │ 11,000+ │
│                    Store area  │ Investment│ To open │ Products│
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [STORE OVERVIEW]        2-column: text left, highlights right │
│  About this store (120–160 words)   ✓ Highlight  ✓ Highlight  │
│                                     ✓ Highlight  ✓ Highlight  │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [PHOTO GALLERY]   Filter: All | Exterior | Interior | Aisles  │
│  ┌──────┐ ┌──────┐ ┌──────┐ ┌──────┐   │ Checkout | Team      │
│  │      │ │      │ │      │ │      │   (click = lightbox)     │
│  └──────┘ └──────┘ └──────┘ └──────┘                          │
│  ┌──────┐ ┌──────┐ ┌──────┐ ┌──────┐                          │
│  └──────┘ └──────┘ └──────┘ └──────┘   [View all 14 photos]   │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [VIDEO TESTIMONIAL]  dark background section                  │
│   ┌───────────────────────────┐   "Why I chose G Fresh Mart" │
│   │   ▶  VIDEO (16:9)         │                               │
│   │   poster = owner in store │    Meera Rathi, Owner         │
│   └───────────────────────────┘    Vijay Nagar, Indore        │
│                                    3:42 · Hindi (subtitles)   │
│                                    3 bullet takeaways         │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [OWNER'S WRITTEN TESTIMONIAL]                                 │
│      ❝ Pull-quote, 40–70 words, large type ❞                  │
│      [photo] Meera Rathi — Owner, Vijay Nagar, Indore         │
│              Former textile distributor · Franchisee since 2024│
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [KEY STORE FACTS]   6–8 tiles, icon + number + label          │
│  ┌────┐ ┌────┐ ┌────┐ ┌────┐                                  │
│  │Area│ │Inve│ │Time│ │Form│    (mobile: 2 per row)           │
│  └────┘ └────┘ └────┘ └────┘                                  │
│  ┌────┐ ┌────┐ ┌────┐ ┌────┐                                  │
│  │SKUs│ │Staf│ │Catch│ │Open│                                 │
│  └────┘ └────┘ └────┘ └────┘                                  │
│  * footnote: figures reported by this franchise owner          │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [INVESTMENT BREAKDOWN]  (optional, owner-approved)            │
│   Table: Component | Approx. amount | What it covered         │
│   Disclaimer box: figures vary by city/size/site              │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [FRANCHISE STORY / WHY THIS STORE]                            │
│   Timeline: Enquiry → Site → Agreement → Fit-out → Training   │
│             → Launch → Today   (horizontal, 6–7 steps)        │
│   Narrative: owner background + local market context          │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [SUPPORT THIS STORE RECEIVED]  3×2 icon cards                 │
│   Site selection · Layout & fit-out · Supply chain            │
│   Staff training · Launch marketing · Ongoing ops support     │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [STORE DETAILS & MAP]    2-column                             │
│   Details list          │  ┌──────────────────────┐           │
│   Address / Hours /     │  │   MAP EMBED          │           │
│   Opened / Size /       │  │                      │           │
│   Format / Parking /    │  └──────────────────────┘           │
│   Contact               │  [Get Directions] [Call Store]      │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [TRUST STRIP]  Brand proof: 400+ stores · 22+ states ·        │
│                Google rating 4.6 (312 reviews) · Since 2016   │
│                Customer review cards (3)                      │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [FAQ — ABOUT THIS STORE]  5–7 accordion items                 │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [EXPLORE MORE STORES]  3–4 store cards → other profile pages  │
│                        [View all stores]                      │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [FRANCHISE CTA + ENQUIRY FORM]  brand-colour band             │
│   Left: headline, 3 reassurance points, what happens next     │
│   Right: short form — Name, Phone, City, Investment range,    │
│          Message (optional)   [Submit Enquiry]                │
│   Micro-copy: no obligation · reply within 2 working days     │
└──────────────────────────────────────────────────────────────┘

┌──────────────────────────────────────────────────────────────┐
│ [FOOTER]  +  Sticky mobile bar: [Call] [Enquire Now]          │
└──────────────────────────────────────────────────────────────┘
```

---

## 2. Visitor journey mapping

| Stage | Sections | Visitor's question |
|---|---|---|
| Discovery | Header, Breadcrumb, Hero | "Which store is this and where?" |
| Credibility | Quick Facts Bar, Store Overview | "Is this a real, serious store?" |
| Experience | Photo Gallery | "What does it actually look like?" |
| Owner's experience | Video + Written Testimonial | "Would a real person recommend this?" |
| Investment info | Key Store Facts, Investment Breakdown | "What would this cost me?" |
| Business details | Franchise Story, Support, Store Details | "How does it work, and who helped?" |
| Trust | Trust Strip, FAQ, Other Stores | "Can I believe this brand?" |
| Enquiry | Franchise CTA + Form | "How do I start?" |

---

## 3. Section-by-section specification

### Section 0 — Header & Breadcrumb
**Purpose:** Orientation and a persistent path to conversion.
**Content:** Logo, main nav (Stores, Franchise Opportunity, About, Contact), one primary button "Enquire About Franchise". Breadcrumb: Home › Franchise Stores › State › City › Locality.
**Layout:** Sticky, slim (64px), white with a subtle shadow on scroll. Breadcrumb sits directly under it in small grey text.
**Example:** `Home › Franchise Stores › Madhya Pradesh › Indore › Vijay Nagar`
**CTA:** Enquire About Franchise (secondary weight — the hero carries the main ask).

### Section 1 — Hero
**Purpose:** Instantly answer "which store, where, who runs it" and set the tone: a real, operating store.
**Content:** Eyebrow badge ("Franchise Store · Operating since 2024"), H1 store name + locality, one-line owner + since line, 2-line intro, two CTAs, optional small trust row (Google rating, footfall or store format).
**Layout:** Split 50/50 on desktop — photo right, text left (or full-bleed photo with a left text card). Stacked on mobile with the photo first at 4:3. Photo must be the real storefront, not stock.
**Example:**
> **FRANCHISE STORE · OPERATING SINCE MARCH 2024**
> # G Fresh Mart — Vijay Nagar, Indore
> Owned and run by Meera Rathi · 2,400 sq ft · Open 7 days
> A neighbourhood supermarket serving around 900 families a week, built in a residential pocket of Vijay Nagar with parking for 12 vehicles and a full fresh-produce section.
> `[Enquire About a Franchise]`  `[Watch Owner's Story ▶]`
**CTA:** Primary — "Enquire About a Franchise". Secondary — "Watch Owner's Story" (anchor-scrolls to the video).

### Section 2 — Quick Facts Bar
**Purpose:** Give the four numbers a franchise prospect looks for before they read anything else.
**Content:** Store area, total investment (range), time to open, product count (or catchment/footfall).
**Layout:** Full-width strip directly below the hero, 4 columns divided by thin vertical rules, number in bold 28–32px, label in 13px uppercase grey. Two-by-two on mobile. No icons here — keep it typographic and calm.
**Example:** `2,400 sq ft — Store area | ₹38–42 lakh — Total investment | 65 days — Enquiry to opening | 11,000+ — Products stocked`
**CTA:** None. This bar is information, not persuasion.

### Section 3 — Store Overview
**Purpose:** Turn numbers into a human picture of the store in under 30 seconds of reading.
**Content:** 120–160 word description (location character, what the store sells, who shops there, what makes the format work) plus 4–6 scannable highlights.
**Layout:** Two columns — description 60%, highlight checklist 40% in a light grey card. Single column on mobile, highlights after the text.
**Example:**
> **About this store**
> G Fresh Mart Vijay Nagar sits on the ground floor of a residential complex on Scheme 54 Road, about 400 metres from the main market. The store opened in March 2024 in a 2,400 sq ft unit and stocks around 11,000 products — daily groceries, fresh fruit and vegetables, dairy, packaged foods, personal care, and a small home-and-kitchen section. Most customers live within two kilometres and shop two or three times a week, so the store is built around fast daily-needs shopping: wide aisles, two billing counters, and a fresh section refilled every morning. Nine people work here, including the owner, who is on the floor most mornings.
> **Store highlights:** ✓ 2,400 sq ft on ground floor · ✓ 11,000+ products across 14 categories · ✓ Dedicated fresh fruit & vegetable section · ✓ 2 billing counters, UPI and card accepted · ✓ Parking for 12 vehicles · ✓ Team of 9, trained by the brand
**CTA:** None (keep the reading flow uninterrupted).

### Section 4 — Photo Gallery
**Purpose:** Prove the store is real and show the standard of the format. This is the most-scrolled section on pages like this, so it earns generous space.
**Content:** 10–16 real photographs, captioned, grouped: Exterior & signage, Entrance & billing, Grocery aisles, Fresh produce, Dairy & frozen, Personal care/home, Staff/team, Launch day.
**Layout:** Filter chips above a masonry or 4-column grid (2 columns on mobile). First image larger. Click opens a lightbox with caption and arrow navigation. Lazy-load everything below the first row; use WebP at ~1600px wide with 4:3 or 3:2 crops for consistency.
**Example captions:** "Main entrance and signage on Scheme 54 Road" · "Grocery aisle — 1.4 m aisles for trolley movement" · "Fresh fruit and vegetable section, restocked every morning" · "Two billing counters at peak evening hours" · "The store team on launch day, March 2024"
**CTA:** Soft text link — "See how a G Fresh Mart store is planned and set up →".

### Section 5 — Franchise Owner Video Testimonial
**Purpose:** The single strongest trust element on the page — a real owner speaking in their own words.
**Content:** Owner intro (name, background, store, since when), embedded video 2–4 minutes, 3 bullet takeaways of what the video covers, subtitle/language note.
**Layout:** Dark section (deep charcoal or brand dark) so the video pops. Video 16:9 on the left at ~60% width, text block right. Use a custom poster frame of the owner inside their store, a large play button, and facade-loading (click-to-load YouTube/Vimeo) so the page stays fast. Full-width video above text on mobile.
**Example:**
> ### "I had never run a retail store before this."
> **Meera Rathi** — Owner, G Fresh Mart Vijay Nagar, Indore
> 3:42 · Hindi with English subtitles
> In this video: why they picked a supermarket over other businesses · how the site was chosen and the store was set up in about nine weeks · what running the store looks like on an ordinary day.
**CTA:** Below the video — "Talk to our franchise team →".

### Section 6 — Owner's Written Testimonial
**Purpose:** Capture the video's message for the majority who will not press play, and give a quotable line.
**Content:** One pull-quote of 40–70 words, owner photo, name, role, store/location, one line of background, and the date of the quote.
**Layout:** Centred, narrow measure (max ~700px), quote in 24–28px serif or medium-weight sans with a large opening quotation mark. Circular owner photo (96px) below the quote with attribution beside it. Generous white space — this section should feel like a pause.
**Example:**
> ❝ I came from a textile distribution background and knew nothing about retail shelves or billing software. What helped was that the layout, the supplier list and the staff training were already worked out. My job was to pick the right location and then be present in the store every day. Fourteen months in, this is a business I understand. ❞
> **Meera Rathi** — Owner, G Fresh Mart Vijay Nagar, Indore · Franchisee since March 2024
**CTA:** None — let the quote stand alone.

### Section 7 — Key Store Facts
**Purpose:** The reference block a serious prospect screenshots or shares with family.
**Content:** 6–8 tiles: Store area · Total investment (range) · Time from enquiry to opening · Store format · Products stocked · Team size · Catchment served · Opening date. Plus a footnote.
**Layout:** 4×2 grid of bordered tiles, line icon at top, number in 26–30px bold, label below in small caps. 2 per row on mobile. Keep one visual style only — no coloured backgrounds on individual tiles.
**Example:** `2,400 sq ft` Store area · `₹38–42 lakh` Total investment · `65 days` Enquiry to opening · `Neighbourhood format` Store type · `11,000+` Products stocked · `9` Team members · `~2 km` Primary catchment · `March 2024` Opened
**Footnote:** *Figures reported by this franchise owner for this specific store. Investment, timelines and store performance differ by city, store size, rent and site conditions.*
**CTA:** None.

### Section 8 — Investment Breakdown *(optional per store, only with the owner's consent)*
**Purpose:** Answer the "where does the money actually go?" question transparently — the question that otherwise triggers a phone call the visitor never makes.
**Content:** 5–7 line table of components with approximate amounts and what each covered, a total range, and a clear variability disclaimer. State what is **not** included (rent, deposits, working capital) if those sit outside the figure.
**Layout:** Simple two- or three-column table, alternating row shading, total row emphasised. Disclaimer in a bordered note box directly beneath. Stack into label/value pairs on mobile.
**Example:**
> | Component | Approx. amount | What it covered |
> |---|---|---|
> | Franchise fee | ₹5 lakh | Brand rights, territory, launch support |
> | Interiors & fit-out | ₹11 lakh | Flooring, ceiling, lighting, signage, billing counters |
> | Racking & equipment | ₹9 lakh | Gondola racks, chillers, freezer, POS hardware |
> | Opening inventory | ₹12 lakh | First full stock across 14 categories |
> | Branding & launch | ₹2 lakh | Signage, launch campaign, opening offers |
> | **Total (as reported)** | **₹38–42 lakh** | Excludes rent, security deposit and working capital |
**Disclaimer box:** *This is what this owner spent at this location in 2024. It is shared as a real example, not as a quotation or a projection. We do not promise any level of sales, profit or recovery of investment.*
**CTA:** "Get an indicative investment estimate for your city →".

### Section 9 — Franchise Story / Why This Store
**Purpose:** Show the path from enquiry to open store, so the prospect can picture themselves walking it.
**Content:** A 6–7 step timeline with dates or durations, plus 150–200 words on the owner's background and the local market logic of the site.
**Layout:** Horizontal timeline on desktop (numbered nodes on a connecting line, short label + date under each), vertical on mobile. Narrative paragraph below in a two-column text block, or beside a secondary photo.
**Example timeline:** `Enquiry — Dec 2023` → `Site shortlisting — Jan 2024` → `Agreement signed — Jan 2024` → `Fit-out begins — Feb 2024` → `Staff training — Feb 2024` → `Stocking & trial run — Mar 2024` → `Store opens — 14 Mar 2024`
**Example narrative:**
> Meera Rathi ran a textile distribution business in Indore for eleven years before looking for something less seasonal. Vijay Nagar has added several residential towers since 2019, but the nearest organised supermarket was more than three kilometres away, so most households were splitting their shopping between a kirana store and a monthly drive to a big-format store. The site on Scheme 54 Road was picked for that gap: ground floor, 2,400 sq ft, a residential catchment of roughly 4,000 households within two kilometres, and parking. From the first enquiry to the opening day was about nine weeks.
**CTA:** None mid-section; the page's momentum should carry to the details below.

### Section 10 — Support This Store Received
**Purpose:** Move the prospect from "that owner is impressive" to "I could do this too, because I would not be alone."
**Content:** Six support areas, each with a one-line description of what actually happened at *this* store: site selection, store design and fit-out, supply chain and stocking, staff hiring and training, launch marketing, ongoing operations support.
**Layout:** 3×2 card grid, line icon, bold label, one sentence. Light background section to separate it from the story above.
**Example:** **Site selection** — Two locations surveyed with the brand's regional team before the final site was approved. · **Store design** — Layout, racking plan and signage supplied by the brand and executed by a local contractor. · **Supply chain** — Onboarded to the regional distribution centre before opening; weekly replenishment cycle. · **Staff training** — Nine team members trained on billing, stock handling and customer service over 10 days. · **Launch marketing** — Local leaflet drop, opening offers and a WhatsApp catalogue set up for the first month. · **Ongoing support** — A regional manager visits monthly; category and pricing updates are shared centrally.
**CTA:** None.

### Section 11 — Store Details & Map
**Purpose:** Serve two audiences at once — franchise prospects verifying the store exists (and wanting to visit it), and local shoppers finding it. Drives local SEO.
**Content:** Full address with pincode, opening hours, opening date, store area, store format, parking, payment modes, store phone (if the owner allows), and an embedded map.
**Layout:** Two columns — definition list left, map embed right at ~16:10. Buttons under the map. Stack on mobile with map first. Lazy-load the map iframe.
**Example:**
> **Address** Shop 3–6, Ground Floor, Shree Residency, Scheme 54 Road, Vijay Nagar, Indore, Madhya Pradesh 452010
> **Opening hours** 8:00 AM – 10:00 PM, all seven days
> **Opened on** 14 March 2024 · **Store area** 2,400 sq ft (carpet) · **Format** Neighbourhood supermarket
> **Parking** 12 vehicles · **Payments** Cash, UPI, debit/credit cards
**CTA:** `[Get Directions]` and `[Visit This Store]` — an in-person visit is a powerful conversion step; consider a "Request a store visit" link that pre-fills the enquiry form with this store.

### Section 12 — Trust Strip
**Purpose:** Zoom out from one store to the brand, so credibility is not resting on a single testimonial.
**Content:** Brand numbers (stores, states, years operating), the store's public rating and review count, and 2–3 short customer reviews of this store.
**Layout:** Slim stats row, then three compact review cards with star rating, quote, first name and month. Keep it low-key — small type, lots of air.
**Example:** `400+ stores · 22+ states · Operating since 2016 · 4.6 ★ from 312 Google reviews for this store`
> ★★★★★ "Fresh vegetables every morning and billing is quick even in the evening rush." — Ankit, Aug 2025
**CTA:** None.

### Section 13 — FAQ About This Store
**Purpose:** Remove the last specific objections at the exact moment they surface, and capture long-tail search queries.
**Content:** 5–7 store-specific questions, not generic brand FAQs.
**Layout:** Single-column accordion, max ~800px wide, first item open by default. Mark up with FAQPage schema.
**Example questions:** "How big is this store and what does a store this size need?" · "How long did this store take to open?" · "What does the ₹38–42 lakh investment include?" · "Did the owner have retail experience before?" · "Can I visit this store before I enquire?" · "Is a similar store possible in my city?"
**CTA:** At the end — "Still have a question? Talk to our franchise team →".

### Section 14 — Explore More Stores
**Purpose:** Keep the visitor on-site if this store is not the right comparison for them, and build internal links across hundreds of store pages.
**Content:** 3–4 cards for other stores — ideally in the same state, a similar size, or a different format for contrast. Each card: photo, store name, area, investment range, year opened.
**Layout:** Horizontal card row (scrollable on mobile), plus a "View all stores" button to the store directory.
**Example:** `G Fresh Mart — Bhawarkua, Indore · 1,800 sq ft · Opened 2023` · `G Fresh Mart — Ujjain Road, Dewas · 3,100 sq ft · Opened 2025`
**CTA:** `[View all G Fresh Mart stores]`.

### Section 15 — Franchise CTA & Enquiry Form
**Purpose:** The conversion point. Everything above exists to make this form feel like a small, safe next step.
**Content:** Headline referencing the journey just read, 3 reassurance bullets, a "what happens next" micro-sequence, and a short form. Keep to 5 fields — every extra field costs completion. Hidden field capturing the source store.
**Layout:** Full-width brand-colour band. Left column: headline + reassurance. Right column: white form card with visible labels, large tap targets, one primary button. Single column on mobile with the form below the copy. Show a success state in place, not a page reload.
**Example:**
> ## Interested in opening a G Fresh Mart?
> Tell us your city and preferred store size, and our franchise team will share the format options, space requirements and an indicative investment range for your location.
> ✓ No obligation — an enquiry is just a conversation
> ✓ We respond within 2 working days
> ✓ You can visit an operating store before deciding
> **What happens next:** You enquire → We call to understand your city, budget and timeline → We share format options and space requirements → You visit a store → You decide.
> **Form fields:** Full name* · Phone/WhatsApp* · City & state* · Space available (owned / rented / still looking) · Investment range you are considering (dropdown) · Message (optional)
**CTA:** `[Submit Franchise Enquiry]` — plus `[WhatsApp Us]` as a lower-friction alternative.
**Compliance line under the form:** *G Fresh Mart does not guarantee any level of sales, profit, or return on investment. Store performance depends on location, rent, operating costs and day-to-day management.*

### Section 16 — Footer & Sticky Mobile Bar
**Purpose:** Catch anyone who scrolls past the form, and keep conversion one tap away on mobile throughout.
**Content:** Standard footer (store directory by state, franchise links, contact, legal). Sticky bottom bar on mobile appearing after ~40% scroll: `[Call]` and `[Enquire Now]`.
**Layout:** Two-button sticky bar, 56px tall, dismissible.

---

## 4. Design principles for the template

- **One accent colour** (brand green/red) used only for CTAs and small highlights. Everything else in a neutral scale with plenty of white space.
- **Alternate section backgrounds** white → light grey → white, and use exactly one dark section (the video) so it becomes the visual anchor.
- **Typographic hierarchy:** H1 40–48px, H2 30–34px, body 16–17px at 1.65 line height, max text measure ~70 characters.
- **Consistent image crops** so hundreds of store pages look like one system even with photos of varying quality. Shoot to a checklist (see fields below).
- **Performance:** WebP images, lazy loading, click-to-load video and map. Target LCP under 2.5s — most prospects arrive on mid-range phones.
- **Mobile first:** 70–80% of this traffic will be mobile; the page must be fully usable as a single column with the sticky CTA bar.
- **Accessibility:** alt text on every store photo, captions/subtitles on the video, 4.5:1 contrast minimum, keyboard-operable lightbox and accordion.
- **Claims discipline:** describe what happened at this store, attributed to the owner, in past tense. Never state or imply guaranteed returns, profit, payback period or "assured" anything. Avoid publishing revenue or profit figures at all; if a store's sales are ever shown, label them clearly as this store's reported past performance with a prominent disclaimer.
- **Consent:** written consent from each franchise owner for their name, photo, video, quote and any financial figures. Keep a record of the consent date in the CMS.
- **SEO:** unique title/description per store, `LocalBusiness`/`GroceryStore` schema with address, geo, hours and aggregateRating, `VideoObject` schema for the testimonial, `FAQPage` schema, and `BreadcrumbList`. Link every store page from the state/city directory pages.

---

## 5. Recommended store data fields (reusable schema)

Every field below should be a structured field in the CMS so one template renders hundreds of pages consistently. `*` = required for the page to publish.

**Identity & location**
| Field | Type | Example |
|---|---|---|
| store_id* | string | GFM-MP-IND-014 |
| store_name* | string | G Fresh Mart — Vijay Nagar |
| locality* | string | Vijay Nagar |
| city* | string | Indore |
| state* | string | Madhya Pradesh |
| region_zone | enum | West |
| full_address* | text | Shop 3–6, Ground Floor, Shree Residency, Scheme 54 Road… |
| pincode* | string | 452010 |
| latitude / longitude* | number | 22.7533 / 75.8937 |
| google_maps_url* | url | … |
| slug* | string | indore-vijay-nagar |

**Store profile**
| Field | Type | Example |
|---|---|---|
| store_status* | enum | Operating / Coming soon / Relocated |
| opening_date* | date | 2024-03-14 |
| store_area_sqft* | number | 2400 |
| area_type | enum | Carpet / Built-up |
| store_format* | enum | Neighbourhood / Standard / Large format / Express |
| floor_level | string | Ground floor |
| product_count | number | 11000 |
| category_count | number | 14 |
| team_size | number | 9 |
| operating_hours* | string | 8:00 AM – 10:00 PM, all days |
| parking_capacity | string | 12 vehicles |
| payment_modes | multi-select | Cash, UPI, Card |
| special_sections | multi-select | Fresh produce, Dairy, Frozen, Home & kitchen |
| catchment_radius_km | number | 2 |
| households_served_estimate | number | 4000 |
| store_phone | string | +91 … |
| store_email | string | … |

**Franchise & investment**
| Field | Type | Example |
|---|---|---|
| owner_name* | string | Meera Rathi |
| owner_photo | image | … |
| owner_background | text | Textile distribution, 11 years |
| franchisee_since* | date | 2024-03 |
| total_investment_range* | string | ₹38–42 lakh |
| investment_breakdown | repeater (component, amount, covers) | see Section 8 |
| investment_inclusions_note | text | Excludes rent, deposit, working capital |
| time_to_open_days* | number | 65 |
| timeline_milestones | repeater (label, date) | Enquiry — Dec 2023 … |
| support_provided | repeater (area, description) | Site selection — … |
| financials_consent* | boolean + date | true, 2025-11-02 |

**Content & media**
| Field | Type | Example |
|---|---|---|
| hero_image* | image (3:2, ≥1600px) | Storefront |
| hero_image_alt* | string | G Fresh Mart storefront, Vijay Nagar, Indore |
| short_intro* | text (2 lines, ≤180 chars) | … |
| store_description* | rich text (120–160 words) | … |
| store_highlights* | repeater (6 bullets) | … |
| gallery* | repeater (image, category, caption, alt) — min 10 | Exterior / Interior / Aisles / Fresh / Checkout / Team |
| video_url | url (YouTube/Vimeo) | … |
| video_thumbnail | image | Owner inside the store |
| video_duration | string | 3:42 |
| video_language | string | Hindi, English subtitles |
| video_takeaways | repeater (3 bullets) | … |
| written_testimonial* | text (40–70 words) | … |
| testimonial_date | date | 2025-08 |
| franchise_story | rich text (150–200 words) | … |
| local_market_context | rich text | … |
| customer_reviews | repeater (rating, quote, name, month) | … |
| google_rating / review_count | number | 4.6 / 312 |
| store_faqs | repeater (question, answer) — 5–7 | … |
| related_store_ids | relation (3–4) | GFM-MP-IND-009 … |

**Meta & governance**
| Field | Type | Example |
|---|---|---|
| meta_title* | string (≤60 chars) | G Fresh Mart Vijay Nagar, Indore — Franchise Store |
| meta_description* | string (≤155 chars) | … |
| og_image | image | … |
| owner_consent_media* | boolean + date | true, 2025-11-02 |
| content_last_verified* | date | 2026-09-01 |
| page_status | enum | Draft / Published / Needs update |
| enquiry_source_tag* | string | store_indore_vijay_nagar |

**Photo shoot checklist (so every store page looks consistent):** storefront with signage (daylight) · entrance from inside · two grocery aisles · fresh produce section · dairy/frozen · personal care or home section · billing counters in use · a wide interior shot from the back · the team · owner in-store portrait · one launch-day or customer-activity shot.

---

## 6. Five additional elements worth adding

1. **"Is a store like this possible in your city?" mini-qualifier** — three taps (city, space available, investment range) that end in the enquiry form pre-filled. It converts better than a static form because the visitor is already answering questions, and it gives the franchise team a pre-qualified lead. Place it just before the main CTA.

2. **A day in this store (timeline)** — a short horizontal strip: 7:00 AM fresh delivery arrives · 8:00 AM doors open · 11 AM–1 PM senior citizens and home deliveries · 6–9 PM peak evening rush · 10 PM stock count. It answers the unasked question "what would my day actually look like?" better than any paragraph, and takes very little space.

3. **Store visit request** — a distinct, low-commitment CTA to visit this store and meet the owner (subject to the owner's consent and scheduled through the franchise team). An in-person visit is the highest-converting step in franchise sales, and offering it signals the store is genuinely real.

4. **"What this owner would tell a new franchisee" — 3 practical lessons** — three short, honest lines in the owner's voice (e.g. on picking a site, on staffing, on the first three months). Honesty about what is hard builds more trust than uniform positivity, and it differentiates these pages from typical franchise marketing.

5. **Verified content badge with a last-verified date** — a small "Store details verified: September 2026" line near the key facts. It costs nothing, signals that hundreds of store pages are actively maintained rather than published once, and reduces the risk of stale investment figures being read as current quotes.

*(Consider also, if the brand is willing: a downloadable one-page PDF of this store profile for prospects to share with family or a banker — franchise decisions in this segment are usually made by more than one person.)*
