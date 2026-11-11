# US government procurement portals

A census of US public-sector websites and where each one posts its bids: state agencies, counties, cities and towns, school districts, special districts and tribal governments in every state. Each row names the government, its website, the e-procurement platforms it links to (BidNet Direct, OpenGov, Bonfire, PlanetBids, QuestCDN, DemandStar and others) and its own bid or RFP pages. No contact data.

**File:** [`gov_procurement_portals.csv`](gov_procurement_portals.csv), refreshed monthly.

| column | meaning |
|---|---|
| state | two-letter state or territory |
| entity | government name |
| entity_type | `state`, `county`, `city_town`, `school_district`, `special_district` or `tribal` |
| website | the government's website |
| reached | 1 if the website answered when last crawled, 0 if not |
| platforms | e-procurement platforms the site links to, space-separated |
| bid_pages | the site's own bid, RFP or procurement pages, space-separated |

Built from public lists of US governments and a crawl of each government's own website. Released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

The open bids themselves, matched from these portals and federal, state and local boards, are at [pushbuild.com/bids](https://pushbuild.com/bids/).
