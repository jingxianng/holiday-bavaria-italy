# Prompt: Trip-Planning Website Generator

Reference the two attached documents (`trip-logistics.md` and `trip-activities.md`) for more information when building the website.

---

I'm planning a multi-generational family trip through Bavaria, the Swiss Alps, and northern Italy in September, and I've attached two documents: one covering all logistics (car rental, trains, transfers, nights per stop) and one covering the destinations and activities. Please build a single-page trip-planning website from them.

**Before building anything: review both documents and check their assumptions.** Flag anything that looks inconsistent, outdated, or worth verifying (train times, connections, opening constraints, booking lead times, etc.) and list your findings first. Where the documents say "verify," the site should say "we'll confirm the exact times" rather than inventing specifics. Only after that review, build the site.

**Audience:** primarily my parents (60s–70s, flying from Singapore). My father traveled extensively in Germany for business, so don't pitch Germany as exotic or novel — the Bavarian leg is anchored by staying with his former colleague, who now runs a B&B in Rettenberg. What *is* new to them is the Swiss rail crossing and Italy — put the excitement emphasis there. Secondary audience: my spouse (lower priority) — the cycling days in the Allgäu and the food/ are good hooks there. For myself, I think Venice will be a unique highlight. The site's job is buy-in: get everyone excited and confident that the logistics are smooth and taken care of. Warm and reassuring in tone, not a booking tool. English, generous font sizes and high contrast, fully mobile-friendly (they'll view it on phones).

**Structure:**
1. A hero section with the trip's one-line arc and a route overview — a simple stylized map or an elegant step-by-step visual of the stops (Munich → Rettenberg → Chur → Bernina railway → Varenna/Lake Como → Venice → Milan) with nights at each.
2. A "how we'll travel" section that reframes the logistics as comfort: one car for Bavaria only, then scenic trains everywhere — no one drives after Germany, travel days are short, and the two long rail days (Bernina; Milan–Venice) are highlights, not chores. A simple visual day-by-day timeline works well here.
3. One section per destination, in route order, drawing from the activities document: a short evocative intro, then highlights as scannable cards or a short list. For Rettenberg, include the day-trip options (Neuschwanstein, Wieskirche, Lindau) and the cycling days. Include a photo for each destination (royalty-free images from Unsplash/Pexels via direct URLs, or tasteful placeholders I can swap) — key subjects: Allgäu alpine meadows, the Bernina Express on the Landwasser or Brusio viaduct, Varenna's waterfront, Venice's Grand Canal, Milan's Duomo rooftop.
4. A short FAQ addressing likely concerns: How much walking? (moderate, own pace) Is the train travel tiring? (reserved seats, dining car, bags stay with us) Language/money? (English fine everywhere touristy, cards accepted everywhere) September weather? (mild, pack layers).
5. External links where natural: official sites for the Bernina Express/Rhaetian Railway, Neuschwanstein ticket office, Venice vaporetto info, Villa Carlotta, the Duomo — opened in new tabs.

**Design:** clean, editorial, travel-magazine feel — soft alpine-and-lake color palette, one elegant serif for headings, no clutter, no login, no forms. Smooth scroll navigation between sections. Everything self-contained in one HTML file so it can be shared as a single link or file.

Do not invent train times, prices, or hotel names beyond what the documents contain. Accuracy over embellishment.
