# Platform Specs

## Postgres → GitHub Backup Action

Forked from [simonw/simonwillisonblog-backup](https://github.com/simonw/simonwillisonblog-backup)

Uses [db-to-sqlite](https://github.com/simonw/db-to-sqlite) and [sqlite-diffable](https://github.com/simonw/sqlite-diffable) to pull a backup of the content_item platform-specs PostgreSQL database used by the [platform-specs project](https://vercel.com/edelman-trust/media-scrape) to store the most recently scraped versions of the platform specs sites and stores it as newline-delimited JSON in this GitHub repository.

Runs automatically as a GitHub Actions workflow at 09:00 EDT / 13:00 UTC every day of the week from Monday to Friday. See [.github/workflows/backup.yml](https://github.com/Edelman-AI-Solutions/db-backups-platform-specs/.github/workflows/backup.yml).


Related builds on this fork future build outs and related use cases:

- [Scraping Action] (https://github.com/simonw/git-scraper-template?tab=readme-ov-file)
