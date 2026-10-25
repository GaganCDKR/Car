# Plano Car Notebook

Inventory snapshot checked October 24, 2026. Rubric updated October 25, 2026. Free public sources only. No paid reports, trials, inquiries, credit applications or dealer messages.

151 listing records: Toyota24, Chevrolet34, Kia47, Hyundai46. Also62 model/powertrain guides,261 model-year trim references,15 dealer entries and five archived expired leads. Named buying contacts are role-based contacts, not unsupported performance rankings. This is a saved public-source research snapshot, not a complete live inventory census or phone-confirmed stock list. Asking prices are not MSRP or out-the-door quotes. Price dates, fees, incentives, equipment ambiguity and incoming status stay visible.

## Your six-category evaluation

The website now uses the buyer's1–5 rubric: vehicle history25%, mechanical condition20%, model track record15%, mileage15%, safety12.5%, and features12.5%. Every category displays its grade or unknown status, evidence, scope and source links.

No default75, zero or assumed pristine new-car score is used. Unknown categories remain null. A research grade averages only assessed categories, with at least two categories and25% of rubric weight required. Coverage is filled rubric weight, not a probability of accuracy. The full final grade remains blank until all six categories are assessed. The possible full-grade range fills unknowns with1 and5; it is not a forecast and does not control sorting. Default sort uses evidence coverage; partial research grade is an optional sort.

A full title/owner/accident/service record and a VIN-specific mechanical inspection were not verified for these cars. Therefore no final grade or unconditional buy recommendation is issued. CPO and clean-CARFAX claims are identified as claims, not treated as proof. Public free history findings and links are retained for30 non-new listings. Current owner-quality benchmarks remain separate from generational longevity grades. New generations are not assumed to inherit old awards. Missing long-term data does not mean poor reliability.

NHTSA uses stars; IIHS uses test grades and awards. Editorial safety grades preserve applicable model year, powertrain, seat, equipment and build-date conditions. Features earn credit from documented useful equipment, not trim prestige or presumed working condition. Safety assistance is not counted twice as a comfort feature. Mileage grades use explicit recorded-mileage bands for this2025+ search without inferring first-use dates, highway driving or completed maintenance. Serious documented history, condition or safety concerns cannot be canceled by luxury features.

Price and value sit beside the vehicle grade. At least three other fresh primary-source records matching year/model/trim/powertrain/drivetrain/listing condition are needed for a peer asking-price median. Packages, mileage, fees and dealer-specific samples still limit the comparison. No market-wide appraisal or negotiated out-the-door price is invented. The original35k–50k target and55k ceiling remain.

## Photos, seating and navigation

52 listings have1,300 distinct retrieved image URLs. Nine galleries are explicitly dealer-provided OEM/stock imagery;43 are galleries from the matching dealer listing.99 listings have no accessible matched gallery. Dealer galleries may include graphics or stock renders. No unrelated car photos are substituted. Images remain on source servers and can expire or be blocked. Cover clicks open galleries with thumbnails, next/previous controls and arrow-key support. Original dealer links remain available.

Supported seat options drive cards, details, comparison and filters. A7/8-seat configuration matches both filters; model options are distinguished from exact VIN verification. Search model/trim/dealer/VIN/stock, filter brand/model/trim/powertrain/condition/seating/price/photos/evidence, save a local shortlist and compare up to three cars. Dealer buttons clear hidden constraints. No live update service runs.

## Files and deployment

The browser reads dist/data/dataset.json. CSV tables and SQLite contain the same evaluated data. rubric_categories.csv/SQLite table normalize every listing and guide category, including null grades and evidence links. Research sources and rubric definitions are also stored in research/ and included in the full dataset.

For Vercel, copy the contents of dist to the repository root and keep data/ intact. Include index.html, app.js, expand.js, media.js, rubric.js, style.css and expanded.css. Use preset Other, no build command, output directory '.', no environment variables. Source changes must be committed and pushed to the user's GitHub repository to update their Vercel deployment. The separate Sites deployment does not update that repository.

## Verification

Scoring tests cover the weighted formula, unknowns, partial-grade coverage/ranges, critical-risk gates, model-year/powertrain/trim scope and comparable-price eligibility. Functional checks cover filters, sorting, reset, VIN search, shortlist, gallery navigation, comparisons, dealer links, model guides and evidence dialogs. SQLite integrity and unique identities are checked. Browser visual QA remains unverified because managed preview infrastructure is unavailable.

Replace all root website files and data/ in GitHub. Include rubric.js. Commit and push to trigger your Vercel deployment.
