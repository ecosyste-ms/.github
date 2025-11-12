# .github

This repository contains organisation-wide files, settings and templates for ecosyste.ms repositories.

## Settings

We use [github-settings-sync](https://github.com/klcodanr/github-settings-sync) to apply common settings across all repositories. To run it:

```
cd settings
export GITHUB_TOKEN=...
rake # Performs a dry run
rake apply # Applies changes
```

`GITHUB_TOKEN` should be a GitHub Personal Access Token with `repo` and `admin:org` scopes.

Options:

* Match only particular repositories using `-n`, e.g. `-n "radar"`
