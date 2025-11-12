# .github

This repository contains organisation-wide files, settings and templates for ecosyste.ms repositories.

## Settings

We use [github-settings-sync](https://github.com/klcodanr/github-settings-sync) to apply common settings across all repositories. To run it:

```
npx github-settings-sync -o ecosyste-ms -t $GITHUB_TOKEN -s settings/common.json
```

Options:

* Add `-d` to perform a dry run before making real changes.
* Match only particular repositories using `-n`, e.g. `-n "radar"`
