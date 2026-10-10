# Soda Blitz: background for new conversations

*Paste this into a new Claude conversation so it starts with full context. Last updated 2026-10-10.*

## About me
- I own Soda Blitz, 1609 Adams Ave, La Grande, OR 97850. I bought it Aug 1, 2024 and reopened it Sept 7, 2024.
- My background is VB.NET and MS SQL, plus some LAMP on IONOS. I use VS Code on Windows. I'm strong on design and UX and appreciate help with the technical side.
- I like being asked questions rather than having Claude assume, and I like being offered choices as a prioritized list.

## The business
- **The concept:** a Swig-style "dirty soda" shop started about 6 years ago by a college student. The name is too narrow and has negative connotations outside Utah, and I never liked it.
- **Sales:** about $15,000 a month (about $180K a year), with a $9 average ticket, which is about 55 orders a day. 80% of sales are drive-thru.
- **Drinks vs food:** drinks are about 70% of sales, down from 85% a year ago. Sales of both are growing, and food is growing faster. Cross-selling seems to help both.
- **Drinks:** 60+ syrups and purees across 20+ drink bars (sodas, lemonades, teas, blended ice cream drinks).
- **Food:** hot dogs, pretzels with beer cheese, 4 assembled salads, 4 house-made winter soups, hand-dipped ice cream bars made from leftover soft serve, seasonal corn from a local farmer, plus nachos, cookies and popcorn. Food sales are up 15%.
- **Costs:** drink cost of goods is 12–30% depending on drink and size, food cost about 30%, and labor 30–40%. The P&L roughly breaks even after reinvestment, with no owner draw.
- **Kitchen:** one TurboChef and no vent hood. The underused lobby could become prep or kitchen space through tenant improvements.
- **The name problem:** customers often say "I didn't know you had food." Google and Yelp list us as a dessert or beverage shop.
- **Marketing:** Facebook ads work well. We have no DoorDash yet.
- **Systems:** our point-of-sale reporting system, **Bubble Hub**, was built with another Claude session. It has a real-time and historical data API, and we're working on connecting Claude to it.

## The building
- A 1960s former service station, converted into two units.
  - **Highstreet Insurance** rents the slightly larger unit for $1,500 a month plus some utilities.
  - **Soda Blitz** rents the other for $1,590 a month plus some utilities.
- It sits on the corner of La Grande's main roads, but the plain front makes it nearly invisible, and it's hard to drive in and out of.
- Plumbing is old and limited and not well suited to food. The A/C needs replacing.
- The county land value is about $260K, and I've been told the taxable value is in the mid-$400Ks. I'm considering buying it.

## Market study (Oct 2026): key conclusions
The full report is "La Grande soda shop market study" in the GitHub repo `ShaunHalladay/Arduino`, branch `claude/soda-blitz-water-plumbing-j0sb0p`, draft PR #1.

- **Customer count is the real problem**, not the name, kitchen or ticket size. 55 orders a day compares with 150–250 at a well-located drive-thru. Sales per labor hour are about $25, against a $45+ benchmark. Paying myself even a $3K/month draw needs about 17–22 more orders a day.
- **The market:** La Grande has about 13K people and Union County about 26K, both flat for 15 years. City poverty is 20.9% and median household income about $57K, compared with $83K for Oregon. Only 4.5% of workers commute out of the county, so growth means locals coming back more often.
- **Steady customer groups:** about 1,270 EOU students in town (late September to mid-June) and 800+ staff at Grande Ronde Hospital.
- **Closest competitor: Nells-N-Out (1704 Adams).**
  - A town icon that everyone knows. Two drive-thru windows, maxed out at about 4 cars each because more would block Adams Ave.
  - Known for being slow and expensive, with food I find mediocre and poor value, yet always busy. Very nice people.
  - The lesson: they win on familiarity, not quality. I should compete on speed, value and better food, and never knock them.
- **Other competitors:** the chains on Island Ave (McDonald's, Wendy's, DQ, Taco Bell, Starbucks, Arby's), Taco Time, Dutch Bros (2003 Q Ave), Antlers Espresso (two very busy stands that open at 5 AM) and The Local (1508 Adams).
- **Openings:** no other drive-thru soup turned up in town, and drive-thru salads only at Nells-N-Out and the chains. The 2–5 PM afternoon treat slot looks underserved.
- **Ranked options, cheapest first:**
  1. Make the food visible on Google, Yelp and the building.
  2. Redesign the menu board: about 6 signature drinks per category plus "build your own", with a QR code for the full list.
  3. Loyalty program and monthly specials aimed at slow hours.
  4. A 90-day DoorDash test on the 15% plan.
  5. Rename and relaunch, decided after a 90-day review.
  6. A second fast oven.
  7. A ventless fryer.
  8. Convert the lobby to kitchen space ($30–90K). A full vent hood isn't recommended.
- **Funding lead:** La Grande Urban Renewal grants. The Local received $64K in 2021.
- **Still to verify:** ODOT traffic counts, Census tables, Travel Oregon county figures, the county health (CHD) plan-review fee, and electrical panel capacity.

## Open threads
- Connect Claude to the Bubble Hub API, either with a read-only key in the cloud environment or a Bubble Hub connector, and turn the market study into a living document that updates on demand or weekly.
- Decide whether to buy the building and at what price.
