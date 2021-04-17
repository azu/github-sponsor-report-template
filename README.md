# GitHub Sponsor Report 

GitHub Sponsors reporting page.

## Sponsors Count

![sponsors count](./docs/img/sponsors_count.svg)

## Monthly Estimated Income(Dollar)

![estimatedIncomeDollar](docs/img/estimated_income_dollar.svg)

## Usage

1. [Use this Template](https://github.com/azu/github-sponsor-report-template/generate)
2. Set `PERSONAL_GITHUB_TOKEN` to your repo's secrets
   - [New personal access token](https://github.com/settings/tokens/new) →　select `read:org` and `user` permission
   - <https://github.com/{yourname}/{repo}/settings/secrets/actions>
3. Update data manually
   1. Go to <https://github.com/{yourname}/{repo}/actions/workflows/update-data.yml>
   2. Run workflow

After the setup, update data every hour by GitHub Actions.

Based on <https://github.com/azu/github-sponsor-report-template>