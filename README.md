# Hood Recon LLC website

One-page site for Hood Recon LLC, a mobile paintless dent repair business serving the DFW Metroplex.

## How it's put together

- `index.html` is the design and layout. It loads all words, photos and links from `content/site.json`.
- `content/site.json` holds everything the owner can change: contact info, headline, services, steps, gallery, about, service area towns, FAQ, photo tips and social links.
- `admin/` is the editor (Decap CMS). The owner signs in at `/admin` and edits `content/site.json` through forms. Uploaded photos go in `img/uploads/`.
- `netlify.toml` tells Netlify to serve the folder as-is (no build step).

## Editing without code

Go to `https://hoodreconllc.com/admin`, sign in with GitHub, click **Edit my website**, change what you need, then click **Publish**. The live site updates in about a minute.
