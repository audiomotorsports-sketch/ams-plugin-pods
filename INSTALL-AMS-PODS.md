# Cursor / Grok Bot — AMS Pods plugin

Copy everything below the line. **amspods.com only.** Screenshot phone before production.

---

You are editing **amspods.com** only. One pass. Do not open other network repos. Do not invent images. Do not rewrite the whole site.

## Job
Insert a quote plugin **immediately under the existing banner**. Offers, FAQs, SEO copy, and chat stay. Softail marketing copy can wait for a later pass unless it is inside the insert zone.

## Files
1. Save `ams-plugin-pods.css` as `/assets/css/ams-plugin-pods.css`
2. In the homepage `<head>`, after the other stylesheets, add:
   `<link rel="stylesheet" href="/assets/css/ams-plugin-pods.css">`
3. Paste `ams-plugin-pods.html` as specified below.

## HTML insert
Find this exact close on the homepage:

```
</section>
<section class="offer-cards"
```

The `</section>` belongs to `<section class="hero-banner">`.

Paste the full contents of `ams-plugin-pods.html` **between** those two tags.

## Do not
- Touch `<section class="hero-banner">`
- Touch chat (`ams-chat.js`, `#ams-chat`)
- Delete `#offers` / tickets
- Change `:root` to Beats red. This desk is gold `#C6A15B`
- Invent photos. Use existing:
  - `/assets/img/shop/ams-pods-harley.jpg`
  - `/assets/img/shop/harley-chrome.jpg`
  - `/assets/img/shop/ams-pod-install.jpg`
  - `/assets/offers/cstyle/plates/plate-01-ams-pods.png`
- Put Softail on a door
- Put a shipping claim in the plugin
- Use the word warranty / guaranteed / lifetime
- Show any price except **starting at $649 a pair**
- Invent reviews

## Sticky bar
`.ams-plug-sticky` has `right: 88px` so `#ams-chat` keeps the bottom-right corner.
Plugin CSS hides `.mobile-cta-bar` only while `#ams-plug-pods` is on the page. Do not delete the old bar HTML.

## Phone / email
- Call: `tel:+13105138800` — (310) 513-8800
- Text: `sms:+12134291092` — (213) 429-1092
- Email: audiomotorsports@gmail.com
- Copy: **Ask for Nick**

## Door URLs
- Road King → `/services/road-king-bagger-audio/`
- Street Glide → `/services/street-glide-bagger-audio/`
- Road Glide → `/services/road-glide-bagger-audio/`
- AMS pods $649 → `/build-your-own/`

## Done when
- Banner is identical
- Proof + quote sit directly under the banner
- Four cards, real shop photos, no Softail
- Offer tickets still exist below
- Phone screenshot: Text | Call left, chatbot clear bottom-right
- SMS opens to +1 213-429-1092 with year/make/model if filled
- Call is (310) 513-8800

Screenshot **phone** before production merge to branch `v1`.
