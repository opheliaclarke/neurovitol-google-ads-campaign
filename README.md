# NeuroVitol — Google Ads Search Campaign (US)

Full launch playbook for running Google Search ads to **neurovitol.shop** (the live SEO site doubles as the ad lander). Open **`index.html`** in any browser — every keyword list, RSA, negative list and asset is in a one-click Copy block.

## What's inside
- **3 campaigns / 17 ad groups:** Brand ($15/d) · Competitors — 15 brands cross-bid onto `vs/` pages ($50/d) · Category — memory/focus/brain-fog/nootropics ($35/d).
- **Tracking:** auto-tagging + account-level Final URL suffix `src=ggax`. The site (already live, commit `b8fc058`) hands every ads visitor to the offer as `?source_id=ggax&sub1={gclid}&sub2={gbraid}&sub3={wbraid}`; SEO/other traffic goes out as `source_id=orga`.
- **iOS:** gclid is stripped by ATT — gbraid/wbraid are captured instead and accepted by Google in the same "Google Click ID" upload column.
- **Conversions:** manual close-the-loop via Google Sheets → Google Ads "Conversions from clicks" import (daily schedule). Only upload `source_id=ggax` rows.
- **Compliance:** supplement positioning only (never cure/treat), disease terms hard-blocked in the shared negative list, no competitor trademarks in ad text.

## Keyword format (paste straight into Google Ads)
- `[keyword]` = exact match · `"keyword"` = phrase match — match types embedded, no manual setup.

Keep this repo **private** — it's the media-buying playbook, not a public page.
