# Handoff: Casa 13 Studio website

**Repo:** https://github.com/robbyho-aoe2/Record-in-Guatemala
**Status:** v1 one-page site built (`index.html`), not yet deployed.
**Owner:** Robby

## Working agreement

- Merge and publish changes to `main` without asking first. Robby wants every change live right away.

## Opening prompt for Claude Code

> Read HANDOFF.md and README.md in this repo. This is the marketing site for my recording retreat business. Make sure `index.html`, `README.md` and `HANDOFF.md` are committed at the repo root, then help me finish the remaining tasks listed in HANDOFF.md, starting with deploying to GitHub Pages.

---

## What this is

Casa 13 is Robby's small recording studio near Antigua, Guatemala, about 15 minutes from Antigua in Sacatepéquez. The site sells an **all-inclusive recording retreat** to US and European bands and artists: they fly in, Robby picks them up, they stay in a private house set up as a studio, record for the week, and explore Guatemala.

Until now, marketing has been Instagram and referrals. This site is the link for the Instagram bio and for DMs.

## Offer (as currently priced)

**EP Retreat: $5,900 per band** (≈ $1,475 per person for a 4-piece)

- 5 nights in a private house near Antigua
- 6 songs recorded, mixed and mastered (streaming-ready), with stems, full mix and master delivered for each
- Private cook and housekeeper
- Airport pickup and daily transport
- Instrumentalists and production support
- Planning call before the trip
- **Not included:** flights, excursions (add-on)

**Add-ons:** excursions (volcano hikes, tours, Lake Atitlán, nights out), extra songs or nights, live session or music video shoot.

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
5. Past work: 4 audio players in a 2×2 grid
6. Adventures: photo gallery (volcano, Antigua, nights out, Lake Atitlán, food)
7. FAQ: safety, airport, visas, what to bring, drums, more songs, mastering (included), deliverables (stems, mix, master), English
8. Contact: Instagram, WhatsApp and email links, plus the Formspree inquiry form

Design: warm dark theme with a lava-orange accent (`--lava:#e0643a`), responsive down to 390px wide.

## Remaining tasks

- [x] Commit `index.html`, `README.md` and `HANDOFF.md` to the repo root
- [x] Enable GitHub Pages (deploy from `main`, root folder). Live at https://robbyho-aoe2.github.io/Record-in-Guatemala/
- [x] WhatsApp (`50245307743`) and email (`antiguarecordingstudios@gmail.com`) filled in
- [x] Instagram: @casatrecerecordingstudio
- [x] Add `images/` (hero uses the Lake Atitlán shot for now; swap in a studio or house photo when there is one)
- [x] Add `audio/track1-4.mp3` (45-second previews: Up In The Air, Penina Pie, JNIX, Goodnight)
- [ ] Artist names for Up In The Air (YouTube @77shani1) and Goodnight. Penina Pie and JNIX are Eden Naor (YouTube @Eden33Naor). No genres shown.
- [x] Formspree form `xnpjylnj` connected (sends to antiguarecordingstudios@gmail.com; submits in-page with a thank-you message)
- [ ] Optional: custom domain (e.g. `casa13studio.com`). DNS steps are in the README.
- [ ] Optional: favicon, `og:image` with an absolute URL once the domain is set, a Spanish toggle, testimonials once the first retreat runs

## Not yet decided

- Final Instagram handle and WhatsApp number to publish
- Whether the housekeeper is the same person as the cook (this affects cost, not the site)
- Longer packages (full album, 10–14 nights) and writing-camp pricing. These aren't on the site yet.
