# PureScript Boggle

Boggle solver.

## Status

| Source     | Shields                                                                                                                                      |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Project    | ![release][release_shield] ![license][license_shield] ![lines][lines_shield] ![languages][languages_shield]                                  |
| Health     | ![readthedocs][readthedocs_shield] ![github_review][github_review_shield]![codacy][codacy_shield] ![codacy_coverage][codacy_coverage_shield] |
| Repository | ![issues][issues_shield] ![issues_closed][issues_closed_shield] ![pulls][pulls_shield] ![pulls_closed][pulls_closed_shield]                  |
| Activity   | ![contributors][contributors_shield] ![monthly_commits][monthly_commits_shield] ![last_commit][last_commit_shield]                           |

## Installing

```bash
spago install purescript-boggle
```

## Tests

To run tests:

```bash
grunt test
```

## Documentation

This repository's documentation is hosted on [readthedocs][readthedocs].

## Tooling

To run linters:

```bash
grunt lint
```

To run formatters:

```bash
grunt format
```

## Continuous integration

This repository uses github actions to lint and test each commit. Formatting tasks and writing/generating documentation must be done before committing new code.

## Versioning

This repository adheres to semantic versioning standards.
For more information on semantic versioning visit [SemVer][semver].

Bump2version is used to version and tag changes.
For example:

```bash
bump2version patch
```

## Changelog

Please read this repository's [changelog](CHANGELOG.md) for details on changes that have been made.

## Contributing

Please read this repository's guidelines on [contributing](CONTRIBUTING.md) for details on the process for submitting pull requests. Moreover, our [code of conduct](CODE_OF_CONDUCT.md) declares our collaboration standards.

## Contributors

- **Joel Lefkowitz** - _Initial work_ - [Joel Lefkowitz][author]

[![Buy Me A Coffee][coffee_button]][author_coffee]

## Remarks

Lots of love to the open source community!

![Be kind][be_kind]

<!-- Project links -->

[readthedocs]: https://purescript-boggle.readthedocs.io/en/latest/

<!-- External links -->

[semver]: http://semver.org/
[be_kind]: https://media.giphy.com/media/osAcIGTSyeovPq6Xph/giphy.gif

<!-- Contributor links -->

[author]: https://github.com/joellefkowitz
[author_coffee]: https://www.buymeacoffee.com/joellefkowitz
[coffee_button]: https://cdn.buymeacoffee.com/buttons/default-blue.png

<!-- Project shields -->

[release_shield]: https://img.shields.io/github/v/tag/joellefkowitz/purescript-boggle
[license_shield]: https://img.shields.io/github/license/joellefkowitz/purescript-boggle
[lines_shield]: https://img.shields.io/tokei/lines/github/joellefkowitz/purescript-boggle
[languages_shield]: https://img.shields.io/github/languages/count/joellefkowitz/purescript-boggle

<!-- Health shields -->

[readthedocs_shield]: https://img.shields.io/readthedocs/purescript-boggle
[github_review_shield]: https://img.shields.io/github/workflow/status/JoelLefkowitz/purescript-boggle/Review
[codacy_shield]: https://img.shields.io/codacy/grade/ec080f55abf241a5bc4921f349bf6264
[codacy_coverage_shield]: https://img.shields.io/codacy/coverage/ec080f55abf241a5bc4921f349bf6264

<!-- Repository shields -->

[issues_shield]: https://img.shields.io/github/issues/joellefkowitz/purescript-boggle
[issues_closed_shield]: https://img.shields.io/github/issues-closed/joellefkowitz/purescript-boggle
[pulls_shield]: https://img.shields.io/github/issues-pr/joellefkowitz/purescript-boggle
[pulls_closed_shield]: https://img.shields.io/github/issues-pr-closed/joellefkowitz/purescript-boggle

<!-- Activity shields -->

[contributors_shield]: https://img.shields.io/github/contributors/joellefkowitz/purescript-boggle
[monthly_commits_shield]: https://img.shields.io/github/commit-activity/m/joellefkowitz/purescript-boggle
[last_commit_shield]: https://img.shields.io/github/last-commit/joellefkowitz/purescript-boggle
