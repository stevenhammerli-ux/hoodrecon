# Hood Recon LLC website

One-page site for Hood Recon LLC, a mobile paintless dent repair business serving the DFW Metroplex.

## How it's put together

- `index.html` is the design and layout. It loads all words, photos and links from the files in `content/`.
- `content/*.json` holds everything the owner can change, one file per part of the page: contact info and hours, social links, the top of the page, services, steps, gallery, about, service area, FAQ and photo tips.
- `admin/` is the editor (Decap CMS) at `/admin`. It's styled to match the site, and it shows a live preview of the real page while you edit. Uploaded photos go in `img/uploads/`.
- `netlify.toml` tells Netlify to serve the folder as-is (no build step).

## Editing without code

Go to `https://hoodreconllc.com/admin` and sign in with GitHub. Pick **Business info** or **Page sections**, then open the part you want to change. The preview on the right updates as you type. Click **Publish** when you're done, and the live site updates in about a minute.
