# Jehovah Shaama Revelation Church — build notes

## Phase 1 (v1)
Generated via `generate.py`, palette `purple`, theme "abiding presence worship light dwelling city".
Real service times (Sunday Revelation Service, Midweek Bible Study, Prayer & Intercession) were supplied
up front and used from the start — not template placeholders.

## Phase 2 (refine — Lovable rebuild)
Source of truth: screenshots of the church's real site, https://jehovahshaamarevelationchurch.lovable.app/,
supplied by the operator (2026-07-19).

**Name correction:** the v1 build's copy used "Jehovah Shaamarevelation Church" (no space, matching how the
original brief typed it). The real site's own header/crest render it as two lines — "Jehovah Shaama" +
"Revelation Church" — so all display copy was corrected to **"Jehovah Shaama Revelation Church"**. The
folder/slug/domain (`jehovah-shaamarevelation-church`) is unchanged, per the slug rule.

**Real assets carried across** (cropped from the operator's screenshots, since no separate image files were
provided — see `assets/img/CREDITS.txt`):
- `crest.png` / `crest-plaque.png` — their real crest (crown + cross + globe). Used in the nav, the Welcome
  section (as a seal overlapping the photo corner), and the footer.
- `congregation-worship.jpg` — their real hero photo (hands raised in worship), now anchoring the Welcome
  section in place of a stock photo.
- `bible-altar.jpg` — their real "Bible open on the altar" photo. Used as a band behind the Ezekiel 48:35
  verse, echoing how their own site presented it. Note: this is a very wide/short crop (2880×260, taken from
  a full-width banner on their site) — it's deliberately shown as a fixed-height band (300–360px), not a
  full-bleed section background, because stretching it to cover a tall section over-magnifies and blurs it.

**Content carried across verbatim:** tagline, hero sub-line, the meaning-of-the-name statement, vision,
mission, "Rooted, revealed, radiant." (Our Calling section), the real per-service descriptions, and the
Ezekiel 48:35 quote in full.

**Wording correction (confirmed 2026-07-20):** the mission statement on the church's own site read
"a faith-storing, God-driven community" — flagged as a likely slip for "faith-restoring" and left verbatim
pending confirmation. Confirmed and corrected to **"faith-restoring"** in the Mission card, `#calling` section.

**Contact info — what's real vs. deliberately left out:**
- `hello@jehovahshaama.church` — confirmed real (visible on their own site's contact section), so it's used
  in the Times & Place panel and as the Visit CTA's "Email the church" link.
- No address and no phone number exist anywhere on their real site either — their own copy just says
  "Contact us for our current meeting location," which is carried across verbatim. Nothing was invented.
  The old template's Google Maps embed (a generic city-level pin) was removed in favour of this honest
  "Gather with us" panel, since a map implies more location precision than the church actually claims.
  The old placeholder `tel:` link was removed for the same reason — replaced with the real mailto.

**Design pass:** kept the existing Fraunces/Inter + purple/gold system from Phase 1 (it already fits
"abiding presence / light"). Auto-picked **Void Editorial** in spirit (dark, atmospheric, editorial serif)
over Raw Form/Super Travel/Cinematic/Aurora Glass, since the church's own branding is already dark,
regal, and theatrical (crown-and-cross crest, maroon/gold). Swapped the base template's 🔥 eyebrow icon and
favicon (leftover from the shared "fire" template) for a ✦ mark and a 👑 favicon, since fire didn't fit this
church's "presence/light" identity. Added one deliberate signature moment tailored to this brief specifically
("the name IS the whole idea"): a giant faded "SHAAMA" wordmark behind the Our Calling section.
