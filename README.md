# Hakoilonga Panduleni Hamalwa

**Portfolio Manager · Financial Engineering · Quantitative Finance · Financial Technology**

A responsive professional portfolio covering expertise, selected work, career experience, education and professional designations. Content is grounded in the self-authored `agent-profile.json`; incomplete degrees are explicitly labelled.

## Preview

No installation or build step is required. From the repository directory:

```sh
python -m http.server 8080
```

Open http://localhost:8080. The site also works as static files and is compatible with GitHub Pages.

## Files

- `index.html`: accessible page, navigation, metadata and embedded Person JSON-LD.
- `styles.css`: responsive layout, keyboard focus, reduced-motion and print styles.
- `favicon.svg`: local monogram icon.
- `agent-profile.json`: detailed professional facts and disclosure boundaries.
- `person.jsonld`: standalone Schema.org identity record.
- `llms.txt`, `robots.txt`, `sitemap.xml`: discovery resources.

Keep visible content, the embedded JSON-LD and the structured records consistent when updating professional information. Credentials are self-reported and can be independently checked through the linked issuer wallet.

[LinkedIn](https://www.linkedin.com/in/hakoilonga-hamalwa-94a401177/) · [Credential wallet](https://credentials.corporatefinanceinstitute.com/profile/hakoilongapandulenihamalwa761618/wallet) · [Digital CV](https://personalcv-6lh.pages.dev/) · [Professional page](https://hakoilonga.github.io/HAKOILONGA/)

Employer names, institutional information and confidential work are intentionally excluded.

## Search and AI discovery

The full name is the primary heading. The page includes a canonical URL, title and description, Open Graph and Twitter sharing metadata, and a local 1200 x 630 social image. A JSON-LD graph connects WebSite, ProfilePage and Person entities. The standalone Person record matches the embedded entity.

Professional-record and structured-identity links appear only in HTML head metadata, not visible navigation. JSON resources remain publicly retrievable; this is presentation, not access control. No hidden keyword text or alternate crawler-only page is used. `llms.txt` is a supplemental discovery resource, not an indexing standard or guarantee.

### Production follow-through

These changes must be deployed to GitHub Pages before search engines can see them. After deployment, verify the canonical site in Google Search Console and Bing Webmaster Tools using the owner's account, submit the sitemap URL, and request inspection of the home page. No verification tokens are fabricated or included here.

GitHub project Pages are hosted beneath `/HAKOILONGA/`. Crawlers use the host-root `https://hakoilonga.github.io/robots.txt`; the project-local `robots.txt` cannot set host-wide policy. Check that root file for restrictions. Submit the project sitemap directly through the webmaster tools. If moving to a custom domain, update all canonical, schema, sitemap, social-image and discovery URLs together.

Validate the deployed page with Google's Rich Results Test and URL Inspection. Local checks cover structure and consistency; indexing status, rankings and Core Web Vitals require production measurements. Search engines and AI systems choose whether to index, display or cite content.

References: [Google AI search guidance](https://developers.google.com/search/docs/appearance/ai-features), [ProfilePage structured data](https://developers.google.com/search/docs/appearance/structured-data/profile-page).
