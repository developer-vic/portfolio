# KmerBus Logistics & Courier Platform: Live Deploy

![KmerBus Logistics & Courier Platform: Live Deploy](../images/kmerbus-logistics-courier-platform-live-deploy.png)

> A transport marketplace is only useful once it is live and pricing parcels correctly.

For KmerBus, an intercity transport and logistics marketplace in Cameroon, I handled the production deploy and built the courier engine.

## What I delivered

1. SSH production deploy, environment setup, and GitHub sync
2. 6 courier services with distance and weight pricing, zone logic, and multi-parcel discounts
3. Dispatch flow and courier mobile screens
4. Every rate driven by admin configs, so the team changes pricing without code
5. Fixes for post-deploy regressions in seat locking and ad queues, verified on the live site

**Stack:** Nuxt, Laravel, PostgreSQL with PostGIS and OSRM, as a PWA.

[Back to all projects](../README.md)
