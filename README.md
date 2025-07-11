Broken Link Checker with Lychee

This repository uses [Lychee](https://github.com/lycheeverse/lychee) in a GitHub Action workflow to automatically check for broken links in Markdown and HTML files.

 Features
- Automatically scans files on every push or daily schedule
- Reports broken links in GitHub Actions logs
- Creates a GitHub Issue when broken links are found

 File Types Scanned
- .md (Markdown)
- .html
- You can customize it via the workflow args

 Workflow Location
```bash
.github/workflows/link-check.yml
