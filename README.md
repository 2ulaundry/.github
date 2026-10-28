# .github

The pull request template every 2ULaundry repository starts from
([2U-2439](https://linear.app/2ulaundry/issue/2U-2439)). GitHub fills a new pull request with
`PULL_REQUEST_TEMPLATE.md` in any repository of the organization that has no template of its own, so no repository
adds one: it would replace this one there, and drift.

The format is the `2u-linear:code-standards` skill's "The pull request description", and the "PR description" check
that holds every repository to it lives in the `engineering` repository (`actions/pr-description`). A change to the
format changes all three together.

GitHub only reads organization defaults from a public repository, so this one is public: nothing else goes here.
