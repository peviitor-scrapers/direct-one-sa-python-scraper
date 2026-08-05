# PUBLIC.md — Repository Must Be PUBLIC

All scrapers derived from the template **MUST** be **PUBLIC** repositories.

## Why?

- Peviitor is an open-source platform
- Job data should be accessible to everyone
- Transparency builds trust

## Enforcement

Keep the repository public. The repo is public and hosted at:

- Repository: https://github.com/peviitor-scrapers/direct-one-sa-python-scraper
- GitHub Pages: https://peviitor-scrapers.github.io/direct-one-sa-python-scraper/ (`docs/` on `main`, built automatically)
- Scraper workflow: https://github.com/peviitor-scrapers/direct-one-sa-python-scraper/actions/workflows/job-seeker-ro-spider.yml
- Jobs page: `docs/jobs.md` (generated, committed, served on GitHub Pages)
- Peviitor search: https://peviitor.ro (CIF `22913844`)

## How to check

```bash
gh repo view peviitor-scrapers/direct-one-sa-python-scraper --json visibility
```
