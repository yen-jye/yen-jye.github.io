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
- `/guides/m4a-to-mp3.html`: Korean user guide for the M4A to MP3 Converter.
- `/_redirects`: `/m4a-to-mp3/*` redirects to the converter.

## Free tools

- M4A to MP3 Converter: https://www.m4amp3.jyelabs.com/ — separate Cloudflare Pages project built from https://github.com/yen-jye/m4a-to-mp3 (see that repo's README).

The site is static HTML/CSS/JS and has no analytics scripts or user data forms. Free tools process files in the browser and do not upload them. Store website/privacy links and AdMob verification must be configured separately in their consoles.
