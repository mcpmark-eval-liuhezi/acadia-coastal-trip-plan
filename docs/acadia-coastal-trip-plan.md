# Acadia Coastal Kayak & Camp Weekend — Trip Plan

- **Trip dates:** Saturday 24 – Sunday 25 October 2026
- **Drafted:** Wednesday 21 October 2026, 20:15 EDT (Bar Harbor local time)
- **Area:** Mount Desert Island / Acadia National Park, Maine
- **Purpose:** Leader sign-off document for the club's fall sea-kayak-and-camp weekend: establishes the base campground head-to-head, marine conditions at two checkpoints, the daylight window, shuttle logistics, active park alerts, and the Go/No-Go call.
- **Data sources (all live, retrieved 2026-10-21):** NPS official campground listing for Acadia (`acad`); NPS active alerts for Acadia; marine forecast checkpoints at 44.30°N, 68.30°W (south of Mount Desert Island) and 44.33°N, 68.05°W (off the Schoodic Peninsula); astronomy lookup for Bar Harbor; web sources for Island Explorer status; NWS marine zone forecasts for the weekend window.

---

## Coastal campgrounds

Both candidates were pulled from the National Park Service's official campground listing for Acadia National Park (parkCode `acad`; 4 campgrounds listed total).

### Blackwoods Campground
- **Location / access (per listing):** East side of Mount Desert Island, about 5 miles (8 km) south of Bar Harbor on Route 3 (Otter Creek). All sites are wooded and within a 10-minute walk of the ocean. Roads are paved — all vehicles OK; RVs and trailers allowed.
- **Season (per listing):** "Open seasonally, usually from early May to mid-October."
- **Sites:** 281 total, all reservable in advance (no first-come, first-served). Mix: 221 tent-only, 60 RV-only, 4 group.
- **Amenities (per listing):** trash/recycling collection; flush toilets (seasonal); potable water (seasonal); dump station; camp store; ice and firewood for sale; food storage lockers; laundry; amphitheater; staff/volunteer host onsite; internet connectivity; cell phone reception. No showers.
- **Accessibility (per listing):** 12 accessible drive-in sites (RV non-electric and tent-only); RV sites max 35 ft (10.7 m); hard-packed walkways to wheelchair-accessible restrooms and the amphitheater.
- **Fees / reservations:** $30/night tent-only or RV non-electric; $60/night group tent area. Park entrance pass required in addition. Reservations via Recreation.gov only (90% of sites released six months ahead on the 1st of the month; remaining 10% released 14 days ahead of arrival).

### Seawall Campground
- **Location / access (per listing):** West side of Mount Desert Island, about 4 miles (6 km) south of Southwest Harbor, approximately 18 miles from Bar Harbor. All sites are within a short walking distance of the coastline. Paved roads — all vehicles OK; RVs and trailers allowed (20 ft max).
- **Season (per listing):** "Open seasonally, typically from the Wednesday before Memorial Day to Columbus Day." Ranger station generally 9 am–8 pm in peak season, staffing-dependent.
- **Sites:** 202 total, all reservable in advance. Mix: 43 tent-only, 59 RV-only, 98 walk-in, 5 group.
- **Amenities (per listing):** the identical list to Blackwoods — trash/recycling collection; flush toilets (seasonal); potable water (seasonal); dump station; camp store; ice and firewood for sale; food storage lockers; laundry; amphitheater; staff/volunteer host onsite; internet connectivity; cell phone reception. No showers.
- **Accessibility (per listing):** accessible sites include 3 RV (35-ft max), 5 drive-in, 5 walk-in, and one group site; paved road to the amphitheater; accessible restroom in the C loop reached by a long, hard-packed ramp.
- **Fees / reservations:** $30/night standard, RV, or tent-only (non-electric); $22/night walk-in; $60/night group tent area. Reservations via Recreation.gov only (same release schedule as Blackwoods).

### Head-to-head

| Factor | Blackwoods | Seawall |
|---|---|---|
| Side of island / nearest town | East side; 5 mi south of Bar Harbor | West side; 4 mi south of Southwest Harbor, ~18 mi from Bar Harbor |
| Coast access | All sites within a 10-minute walk of the ocean | All sites a short walking distance from the coastline |
| Sites | 281 (221 tent-only, 60 RV-only, 4 group) | 202 (43 tent-only, 59 RV-only, 98 walk-in, 5 group) |
| Amenities | Identical lists (no showers at either) | Identical lists (no showers at either) |
| RV / trailer limits | RV sites to 35 ft | RV/trailer max 20 ft |
| Nightly fee | $30 tent/RV; $60 group | $30 standard; $22 walk-in; $60 group |

**Season flag (decisive this year):** the listing's seasonal dates put both campgrounds' close of season *before* our 24–25 October weekend — Seawall typically closes on Columbus Day (Monday 12 October 2026) and Blackwoods usually runs "early May to mid-October." Per the official listing, neither campground should be assumed open for this trip. Leaders must confirm current availability directly with the park / Recreation.gov (Blackwoods campground 232508; Seawall campground 234674) before finalizing the base. If both are in fact closed, Duck Harbor (below) is the listing's other genuinely coastal option, though it is a different class of trip.

### Other coastal option worth flagging
**Duck Harbor Campground (Isle au Haut)** — five lean-to shelter sites on a rugged island off Stonington, linked to the mainland by mailboat and inaccessible to automobiles; the listing describes it as "a great launch point for paddling excursions." $20/night, reservations required (released 10 am April 1 for the whole season), max 3 nights, six people per site, one stay per calendar year, no pets, no generators, pack-out trash. Remote and logistically heavier — but the most paddler-specific coastal campground in the listing.

## Marine forecast

Two checkpoints were queried on 2026-10-21 via the marine forecast API. Weekend daylight window (Bar Harbor): Saturday 06:59–17:34, Sunday 07:00–17:32.

**Checkpoint 1 — water just off the southern coast of Mount Desert Island (≈44.30°N, 68.30°W)**
- Significant wave height: **0.6–0.8 m**
- Swell: **0.4–0.5 m from the SE (≈135–137°) at 8.8–8.9 s**
- Water temperature: **12 °C (53.6 °F)**

**Checkpoint 2 — water off the Schoodic Peninsula (≈44.33°N, 68.05°W)**
- Significant wave height: **1.2–1.4 m**
- Swell: **0.9–1.0 m from the SE (≈136–139°) at 8.7–8.9 s**
- Water temperature: **11.7 °C (53 °F)**

**Reporting note (transparency for reviewers):** the marine feed's hourly payload was cut off partway through and did not reach the 24–25 October hours; the figures above are the checkpoint values the forecast actually returned, and these are the numbers applied to the Go/No-Go rule. For the weekend days themselves, NWS marine zone forecasts retrieved the same evening corroborate the pattern: the Schoodic Point–Stonington coastal/intracoastal zone covering the southern MDI checkpoint shows light and variable winds with seas around 1 ft on Saturday, building Sunday to an east wind 9–12 kt becoming SE with seas around 3 ft and showers likely; the Eastport–Schoodic Point zone covering the Schoodic checkpoint shows Saturday NW winds 11–14 kt with gusts to 23–25 kt. Weekend water temperature is consistent with the checkpoint values at roughly **11–12 °C (52–54 °F)** — cold-water immersion conditions; drysuits or full wetsuits per club cold-water policy regardless of the Go/No-Go outcome.

## Shuttle access

- **What it is:** the Island Explorer — Acadia's fare-free, propane-powered shuttle, operated by Downeast Transportation in partnership with the National Park Service, connecting the park with Bar Harbor and other Mount Desert Island communities.
- **Fare: free** (fare-free service; the route's early history included a $2 fare, but current service is free to riders).
- **Does it reach our campgrounds?** In season, yes for both candidates: Blackwoods Campground is a served stop (the campground-serving route — e.g., one-way hikes are documented ending "to Blackwoods Campground (Bus 10)"), and Seawall Campground is served by Route 7 (Southwest Harbor), which runs from Bar Harbor's Village Green and terminates at Seawall.
- **Current status for our weekend (24–25 October 2026): NOT RUNNING.** The Island Explorer's regular seasonal service ended on **12 October 2026**, so there is **no free shuttle on our trip dates**. Plan on private-vehicle shuttles for the whole weekend; do not build logistics around the bus.
- Downeast Transportation also runs other regional routes (e.g., the Bar Harbor–Bangor intercity bus, Monday–Friday, $7–$9 fare), but these do not serve the campgrounds or the park destinations relevant to this trip.

## Park alerts

Active alerts for Acadia National Park as retrieved 2026-10-21 — three posted. **None affect camping, and none close coastal launching or landing.**

1. **Eastern section of Beech Mountain Loop Trail closed for repairs** (park closure, area inaccessible). From 21 Sep 2026: from a junction just beyond the parking lot to just below the summit at the fire tower. Three alternate routes to the summit remain open (outer loop, Beech South Ridge, Beech West Ridge). *Relevance: Beech Mountain is on the quiet western side near Seawall; shoreline paddling is unaffected.*
2. **Schoodic Mountain Road closed for repairs** (park closure, area inaccessible). From 31 Aug 2026: from Schoodic Loop Road to the summit of Schoodic Head, with heavy equipment operating (resurfacing, regrading, ditching). *Relevance: affects land access on the Schoodic Peninsula (Checkpoint 2 area), not the water.*
3. **Southern section of Ocean Path closed for repairs** (park closure, area inaccessible). From 31 Aug 2026: from the trailhead across from the Otter Point parking lot to the trail's southern terminus. *Relevance: the coastal shoreline trail nearest Blackwoods/Otter Creek — affects the on-foot coastal leg only.*

No alerts are posted for either campground, for camping generally, or for coastal access by water.

## Go / No-Go call

**The rule (as agreed by the club):** if the significant wave height at **both** checkpoints stays at or below **1.0 m** through the weekend's daylight hours, the coastal paddle is **GO**; if **either** checkpoint goes above **1.0 m**, it is **NO-GO** and we stay on sheltered water.

**Applying it to the numbers actually retrieved (see "Marine forecast"):**

| Checkpoint | Significant wave height | At or below 1.0 m? |
|---|---|---|
| 1 — south of Mount Desert Island (44.30°N, 68.30°W) | 0.6–0.8 m | Yes |
| 2 — off the Schoodic Peninsula (44.33°N, 68.05°W) | **1.2–1.4 m** | **No** |

**Verdict: NO-GO for the coastal paddle.** Checkpoint 2 is running 1.2–1.4 m — above the 1.0 m threshold — so the club rule triggers regardless of how manageable the southern MDI water looks. The weekend runs on **sheltered water only**: protected harbors, coves, and island lee shores rather than the open coastal leg.

**Conditions driving the call:** SE swell of 0.9–1.0 m at ~8.8 s on the Schoodic side, with zone forecasts additionally showing NW winds 11–14 kt gusting to ~25 kt Saturday for that area and building east/SE winds with ~3 ft seas and likely showers Sunday on the southern MDI side. Water at 11–12 °C (52–54 °F) means cold-water gear, tow plan, and buddy pairs are mandatory even on sheltered water.

**Daylight window for on-water planning:** Saturday 24 Oct — sunrise 6:59 am, sunset 5:34 pm (~10 h 35 min); Sunday 25 Oct — sunrise 7:00 am, sunset 5:32 pm (~10 h 32 min).

**Trip-leader notes for sign-off:**
1. The coastal leg is off the plan for 24–25 October 2026; substitute sheltered-water routes within the daylight windows above.
2. No Island Explorer service on our dates — all shuttles by private vehicle.
3. Confirm campground availability before booking: the official listing's seasons (Blackwoods to mid-October; Seawall to Columbus Day, 12 October 2026) both end before our weekend.
4. Re-check the marine forecast Friday evening before departure. If the Schoodic checkpoint has fallen to ≤ 1.0 m with both checkpoints at or below threshold for the daylight hours, the leaders may re-run this rule; as of this draft, the call is **NO-GO**.

---
*Prepared 2026-10-21 (EDT) from live NPS, marine-forecast, astronomy, and web data. Reviewers: please leave comments on this pull request.*
