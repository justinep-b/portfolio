# Justine Bermillo — YouTube-inspired portfolio

A responsive dark-purple portfolio built with **Next.js 15**, React, and vanilla CSS. Includes a YouTube-style channel banner, channel navigation, searchable/filterable project library, project detail modal, skills, career timeline, and contact page.

## Run locally

1. Install Node.js 20 or later.
2. Open a terminal in this folder.
3. Run `npm install` and then `npm run dev`.
4. Open http://localhost:3000.

## Publish to GitHub and Vercel

1. Create a new **public** GitHub repository, e.g. `portfolio`, under `justinep-b`.
2. Upload the **contents** of this folder to that repository (not the ZIP itself). Do not upload `node_modules` or `.next`.
3. Go to https://vercel.com/new and choose **Import Git Repository**.
4. Select the repo. Vercel should recognize **Next.js** automatically.
5. Click Deploy. Future pushes to GitHub will trigger a new deployment.

## Customize

- `app/data.ts`: change categories, work samples, project details, skill groups, and URLs.
- `app/page.tsx`: change your headline, bio, social/contact links, and page layout.
- `app/globals.css`: change colors and typography.
- `public/`: place your own headshot, banners, and approved portfolio thumbnail images here. Use `/filename.png` as an image URL in `app/data.ts`.

## Important before publishing

- Four YouTube channel links were provided as portfolio references; only descriptions confirmed by Justine should be published as personal contributions. **Do not imply sole ownership or authorship.**
- Client-specific email campaigns, GoHighLevel screenshots, team/project processes, and operational results remain placeholders until permission or anonymization.
- The Google Drive folder may not be publicly accessible to every portfolio visitor. Consider exporting a curated set of **approved** samples into `public/`, or making only those specific Drive files publicly viewable with permission.
- Add a professional contact email or contact form before public launch. GitHub is the temporary contact link.
- No invented growth metrics, client testimonials, or private analytics have been included.

## License

Portfolio source supplied for Justine's use. Existing linked client work remains the property of its respective rights holders.
