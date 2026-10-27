# Lucky Lindy: The Long Way to Paris

A Jekyll static site for the Lindbergh 1927 Centennial campaign. It is organized around focused pages so each team lead can be sent directly to their working area.

## Pages

- **Overview** — purpose, audience, editorial standards, campaign rhythm, roles.
- **Radio scripts** — launch audio draft, reusable script format, production notes.
- **Social media** — sample posts, recurring post formats, publishing guidance.
- **YouTube & Reels** — long-form and vertical-video storyboards.
- **Weekly releases** — historical milestones grouped into weekly releases from November 3, 2026 through May 21, 2027.

## Publish with GitHub Pages

1. Copy the contents of this folder into the root of `cmacq/lucky-lindy`.
2. In GitHub, open **Settings → Pages** and select **GitHub Actions** as the source.
3. Push to the `main` branch. The workflow in `.github/workflows/pages.yml` builds the Jekyll site and deploys it.
4. The project site URL will be `https://cmacq.github.io/lucky-lindy/`.

The workflow runs Jekyll directly through GitHub Pages' official build and deploy actions. No local Ruby setup is needed.

## Editing

Each page is a Markdown file in the repository root and has a stable URL:

- `/` — overview
- `/radio/`
- `/social/`
- `/video/`
- `/releases/`

The schedule is a planning calendar. Historical claims, precise dates, quotations, images, and rights should be checked against the source ledger before publication. The November 3 launch teaser is a modern dramatization; never present staged material as genuine archival news or real-time reporting.
