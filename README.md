# McPherson Specialty Welding Services - Website

Hand-coded static site. No build step, no framework, no dependencies. Ready for GitHub Pages, Netlify, Cloudflare Pages, or any static host.

## Structure

```
msws-site/
  index.html          # the whole site (one page)
  css/style.css       # all styles, red + black industrial
  img/
    logo-mark-white.png    # welder mark, white (hero + nav)
    logo-mark-black.png     # welder mark, black (for light backgrounds)
    logo-full-white.png     # full logo lockup, white (footer)
    logo-full-black.png     # full logo lockup, black (light backgrounds, social share)
    favicon.ico / favicon-32 / favicon-16 / apple-touch-icon
  RESEARCH-NOTES.md   # competitor research findings
  README.md           # this file
```

The logo was extracted from the real McPherson Specialty Welding letterhead and cleaned to transparent PNGs (mark only and full lockup, black and white versions).

## Sections

Hero, Code Work (the heart: pressure vessel + boiler repairs and alterations), Capabilities, Fab Work (with a fab-request email flow), Certified / Why It Matters, How a Job Runs, trust banner, Contact, footer.

## Before it goes live (confirm list)

These are also listed as a comment at the top of `index.html`.

1. **National Board "R" certificate number + a scan image.** Biggest trust upgrade. Not shown anywhere yet because the number is not on file here. Add it.
2. **Contact email.** Currently Ronnie's personal Gmail so it works today. Once the domain is bought, switch to a domain email (e.g. ronnie@mcphersonweldingservices.com). Search `EMAIL` in `index.html` to swap.
3. **Phone (910) 373-7197** is public on the letterhead and records. Confirm OK to publish.
4. **Address: DONE.** Confirmed 756 Treaty Ct, Myrtle Beach SC 29588 (Ronnie + company letterhead). Shown in Contact, footer, and JSON-LD.
5. **Scope, welding processes, fab capabilities** listed are standard for an R-Stamp shop but not individually verified. Confirm and trim.
6. **No invented numbers** (years, vessels repaired) are claimed. Add real ones where they fit.
7. **No 24/7 claim.** Add only if the shop offers emergency response.
8. **Photos: PARTLY DONE.** The "Real Work" gallery (`img/work-1..6.jpg`) is real shop footage pulled from Ronnie's phone (June 2026) at preview resolution. iCloud blocks full-res headless export, so for crisp originals: AirDrop them or favorite them in Photos and we swap in. Still to add: the gray-Jeep "first job" heritage photo (favorite it in Photos and I'll grab it), and optional welder/Ronnie people shots (need the welder's OK to publish his face).

## Domain

`mcphersonweldingservices.com` is **available** (checked via whois) and is the recommended pick: exact business name, clean, the `.com` a code buyer trusts. Under $20/year at any major registrar.

Other available fallbacks: mcphersonspecialtywelding.com, mcphersoncodewelding.com, mswswelding.com, mcphersonweld.com, mcphersonweldingsc.com. (`mcphersonwelding.com` is taken.)

## Deploy (GitHub Pages)

1. Create a repo, e.g. `msws-site`.
2. Put these files at the repo root.
3. Repo Settings > Pages > Build from branch > `main` / root.
4. Point the custom domain at it (CNAME) once the domain is purchased.

HTTPS is automatic on GitHub Pages and is non-negotiable for a code-shop site (buyers bounce on "Not Secure").
