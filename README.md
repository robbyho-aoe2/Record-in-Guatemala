# Casa 13 Studio: website

A one-page site for Casa 13 recording retreats. Plain HTML, no build step, ready for GitHub Pages.

## 1. Fill in your details

Open `index.html` and search for `YOUR_`. Replace:

| Placeholder | Replace with |
|---|---|
| `YOUR_HANDLE` | Your Instagram handle (no @) |
| `YOUR_NUMBER` | WhatsApp number, digits only with country code, e.g. `50212345678` |
| `YOUR_EMAIL` | Your email (it appears twice) |
| `YOUR_FORM_ID` | Your Formspree form ID (see step 3) |

Also edit the three **Past work** tracks: titles, artist names and genres.

## 2. Add photos and audio

Create two folders next to `index.html` and drop files in with these exact names. Any that are missing fall back to a colored gradient, so the site still looks fine without them.

```
images/hero.jpg      big background at the top (volcano view or studio shot, wide, ~2000px)
images/volcano.jpg   volcano hike
images/antigua.jpg   Antigua street
images/night.jpg     night out
images/lake.jpg      Lake Atitlán
images/food.jpg      meals
audio/track1.mp3     past-work clips (30-60 sec previews are ideal)
audio/track2.mp3
audio/track3.mp3
```

Keep photos under about 500 KB each so the page loads fast. Squoosh.app is a free compressor.

## 3. Make the inquiry form work

GitHub Pages can't process forms by itself, so the form uses Formspree (the free tier gives 50 submissions a month).

1. Sign up at formspree.io and create a new form.
2. Copy the form ID, the part after `/f/` in the endpoint URL.
3. Paste it in place of `YOUR_FORM_ID`.

Inquiries will arrive in your email.

## 4. Put it on GitHub Pages

The site lives in this repo, `robbyho-aoe2/Record-in-Guatemala`.

1. Make sure `index.html` (plus `images/` and `audio/` once you have them) is on the `main` branch. On github.com you can use **Add file → Upload files**.
2. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
3. After a minute the site is live at `https://robbyho-aoe2.github.io/Record-in-Guatemala/`.

## 5. Custom domain (recommended)

1. Buy a domain such as `casa13studio.com` (Cloudflare, Namecheap or Porkbun, about $10-15/year).
2. In **Settings → Pages → Custom domain**, enter the domain and save.
3. At your domain registrar, add these DNS records:
   - Four `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153` and `185.199.111.153`
   - A `CNAME` record for `www` pointing to `robbyho-aoe2.github.io`
4. Once it's verified, tick **Enforce HTTPS**.

## Updating prices or text

Edit `index.html` directly on GitHub (click the file, then the pencil icon) and commit. The live site updates within a minute or two.
