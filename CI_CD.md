# CI/CD Documentation

## Github Workflows

[styfle/cancel-workflow-action](https://github.com/styfle/cancel-workflow-action)

* cancels previous workflows to save processing time

[tj-actions/branch-names](https://github.com/tj-actions/branch-names)

* get branch name for checkout step

* saved to `steps.branch-name.outputs.[branch_type]`
  (see [docs](https://github.com/tj-actions/branch-names#usage) for more info)

[actions/checkout](https://github.com/actions/checkout)

* checks out a branch

[paulo-ferraz-oliveira/parse-tool-versions](https://github.com/paulo-ferraz-oliveira/parse-tool-versions)

* parse tool versions

* available at `steps.tool-versions.outputs.[tool]`

[erlef/setup-beam](https://github.com/erlef/setup-beam)

* sets up beam environment for running elixir

* configured to read elixir/otp versions from `.tool-versions`.

* why?  asdf also uses `.tool-versions` to ensure that the correct version of
  elixir and erlang are installed.  this limits versions to a single source of
  truth for CI/CD purposes :)
