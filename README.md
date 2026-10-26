# JYE LABS developer website

Source repository for https://io.jyelabs.com.

## Deployment

- Hosting: Cloudflare Pages, project `jyelabs-apps`.
- Production branch: `main` (Git integration).
- Framework preset: None.
- Build command: `exit 0`.
- Build output directory: `.` (repository root).
- Default Pages URL: https://jyelabs-apps.pages.dev.
- Custom domain: https://io.jyelabs.com.
- GitHub Pages publishing is disabled; GitHub stores the source files.

## Public files

- `/app-ads.txt`: Google AdMob authorized seller record.
- `/privacy/lotto.html`: Lotto Android app privacy notice.
- `/privacy/loan.html`: Loan calculator Android app privacy notice.
- `/privacy/site.html`: Website privacy notice.
- `/m4a-to-mp3/`: M4A to MP3 Converter (free browser tool). Build output of https://github.com/yen-jye/m4a-to-mp3 (`npm ci && npm run build`, then copy `dist/` here). Do not edit these files by hand.

The site is static HTML/CSS/JS and has no analytics scripts or user data forms. Free tools process files in the browser and do not upload them. Store website/privacy links and AdMob verification must be configured separately in their consoles.
