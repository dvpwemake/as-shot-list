# American Smile — field shot list

Live (default GitHub URL, no custom domain):

**https://dvpwemake.github.io/as-shot-list/**

- City + road checklists
- Every field autosaves on the phone
- **Send report to GitHub** writes a CSV into [`reports/`](./reports)

## Admin: download CSVs

1. Open https://github.com/dvpwemake/as-shot-list/tree/main/reports
2. Click a `.csv` → **Download raw file**

## Phone: one-time send token

iPhone cannot download files from the page. Send uses the GitHub API.

1. On a computer, create a fine-grained PAT: https://github.com/settings/personal-access-tokens/new  
   - Resource owner: `dvpwemake`  
   - Only this repo: `as-shot-list`  
   - Permissions: **Contents: Read and write**
2. On the phone, open the live page → **Admin** → paste token (stays on that phone only)
3. Tap **Send report to GitHub**
