# Handoff: Casa 13 Studio website

**Repo:** https://github.com/robbyho-aoe2/Record-in-Guatemala
**Status:** v1 one-page site built (`index.html`), not yet deployed.
**Owner:** Robby

## Opening prompt for Claude Code

> Read HANDOFF.md and README.md in this repo. This is the marketing site for my recording retreat business. Make sure `index.html`, `README.md` and `HANDOFF.md` are committed at the repo root, then help me finish the remaining tasks listed in HANDOFF.md, starting with deploying to GitHub Pages.

---

## What this is

Casa 13 is Robby's small recording studio near Antigua, Guatemala, about 15 minutes from Antigua in Sacatepéquez. The site sells an **all-inclusive recording retreat** to US and European bands and artists: they fly in, Robby picks them up, they stay in a private house set up as a studio, record for the week, and explore Guatemala.

Until now, marketing has been Instagram and referrals. This site is the link for the Instagram bio and for DMs.

## Offer (as currently priced)

**EP Retreat: $5,900 per band** (≈ $1,475 per person for a 4-piece)

- 5 nights in a private house near Antigua
- 6 songs recorded and mixed
- Private cook and housekeeper
- Airport pickup and daily transport
- Instrumentalists and production support
- Planning call before the trip
- **Not included:** flights, mastering (add-on), excursions (add-on)

**Add-ons:** excursions (volcano hikes, tours, Lake Atitlán, nights out), mastering, extra songs or nights, live session or music video shoot.

**Payment terms:** 50% non-refundable deposit to book. Balance due 30 days before arrival. Bank transfer or Wise preferred.

**Also offered:** solo artist and duo retreats, quoted on request.

## Copy decisions (keep these)

- Don't name individual collaborators or say "producer". Use **"instrumentalists and production support"**.
- **Housekeeper** is listed as included, alongside the cook.
- Flight time reads **"2–5 hrs from the US"**. Don't claim ~3 hrs.
- Don't claim the house is "acoustically treated".
- Drums: say "We can program drums, and live drum options can be arranged." Don't promise a live drum room.
- Everything is run in English, so say so in the FAQ.
- Price comparison framing: about the same as a mid-level US city studio week, **with the trip included**. Don't claim it's cheaper than any US studio.
- Say **"private cook"**, not "chef".
- Tone: warm, short and confident. Primary CTA is "Check dates".

## Site structure (`index.html`)

Single self-contained file: inline CSS and JS, Google Fonts (Fraunces + Inter), no build step.

1. Hero: "Record your album in Guatemala." plus quick facts
2. How it works: Plan → Fly in → Settle in → Record → Explore
3. What's included: 6 cards
4. Pricing: the EP Retreat card, plus add-ons, payment, and solo/duo
5. Past work: 3 audio players (placeholders)
6. Adventures: photo gallery (placeholders with gradient fallbacks)
7. FAQ: safety, airport, visas, what to bring, drums, more songs, mastering, English
8. Contact: Instagram, WhatsApp and email links, plus the Formspree inquiry form

Design: warm dark theme with a lava-orange accent (`--lava:#e0643a`), responsive down to 390px wide.

## Remaining tasks

- [x] Commit `index.html`, `README.md` and `HANDOFF.md` to the repo root
- [ ] Enable GitHub Pages (deploy from `main`, root folder)
- [x] WhatsApp (`50245307743`) and email (`antiguarecordingstudios@gmail.com`) filled in
- [ ] Replace remaining placeholders: `YOUR_HANDLE`, `YOUR_FORM_ID` (Robby to supply)
- [ ] Add `images/` with `hero.jpg`, `volcano.jpg`, `antigua.jpg`, `night.jpg`, `lake.jpg`, `food.jpg`. Compress each to under ~500 KB.
- [ ] Add `audio/track1-3.mp3` (30–60 second previews) and update the track titles, artists and genres
- [ ] Set up the Formspree form and paste in its ID
- [ ] Optional: custom domain (e.g. `casa13studio.com`). DNS steps are in the README.
- [ ] Optional: favicon, `og:image` with an absolute URL once the domain is set, a Spanish toggle, testimonials once the first retreat runs

## Not yet decided

- Final Instagram handle and WhatsApp number to publish
- Whether the housekeeper is the same person as the cook (this affects cost, not the site)
- Longer packages (full album, 10–14 nights) and writing-camp pricing. These aren't on the site yet.
