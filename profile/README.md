# kettle-dev

`kettle-dev` is a family of Ruby tooling gems for maintaining RubyGems with a
consistent development, test, coverage, CI, release, and templating workflow.

The organization was previously named `kettle-rb`. Older references to
`kettle-rb/*` are historical; current Kettle tooling lives under
`kettle-dev/*`.

## What Lives Here

### Development and Release Tooling

| Project | Purpose |
|---------|---------|
| [kettle-dev][kettle-dev] | Rake tasks and CLIs for RubyGem development, changelogs, pre-release checks, release automation, documentation, and CI helpers. |
| [kettle-family][kettle-family] | Coordinates install, template, state, reset, bump, and release operations across related RubyGem repositories. |
| [kettle-rb][kettle-rb] | Shared Ruby, engine, Rails, RuboCop, and RuboCop LTS compatibility matrix data used by Kettle-managed gems. |
| [nomono][nomono] | ENV-driven Gemfile macros for resolving local sibling gems during multi-repo development. |

### Testing, Coverage, and Quality

| Project | Purpose |
|---------|---------|
| [kettle-test][kettle-test] | RSpec test harness and helper bundle for Kettle-managed gems. |
| [kettle-soup-cover][kettle-soup-cover] | SimpleCov configuration and coverage reporting for local runs and CI providers. |
| [kettle-gha-pins][kettle-gha-pins] | GitHub Actions SHA pin discovery, validation, cache-backed resolution, and upgrade planning. |
| [kettle-drift][kettle-drift] | Detects repeated adjacent-line chunks that usually indicate template drift or copy/paste corruption. |
| [kettle-wash][kettle-wash] | Constant deletion and reset helpers for repeatable reload-oriented tests. |

### Shared CLI and Template Primitives

| Project | Purpose |
|---------|---------|
| [kettle-ndjson][kettle-ndjson] | NDJSON event stream primitives, filters, recorders, and payload helpers for Kettle CLIs. |
| [token-resolver][token-resolver] | PEG-based token parsing and replacement for template pipelines. |

## Related Project: StructuredMerge

The AST and structured merge gems that used to be separate repositories under
the old `kettle-rb` organization now live in the
[structuredmerge-ruby][structuredmerge-ruby] monorepo.

That includes projects such as `tree_haver`, `ast-merge`, `prism-merge`,
`markdown-merge`, `markly-merge`, `toml-merge`, `yaml-merge`, and
`kettle-jem`. Kettle still uses that toolchain, but those repositories are no
longer part of this organization profile.

## Typical Workflow

Kettle-managed gems usually combine:

- `kettle-test` for RSpec execution and test helpers.
- `kettle-soup-cover` for coverage setup and reports.
- `kettle-dev` for Rake tasks, changelog generation, pre-release checks, and
  release orchestration.
- `kettle-family` when a set of related gems needs to be installed, templated,
  reset, bumped, or released as a dependency-ordered group.
- `nomono` for switching between released gems and local sibling paths without
  hand-editing Gemfiles.

## Package Source

Kettle gems are published as RubyGems. Kettle-managed projects commonly use
`https://gem.coop` as the Bundler source, which proxies RubyGems.org for normal
Bundler installs.

[kettle-dev]: https://github.com/kettle-dev/kettle-dev
[kettle-family]: https://github.com/kettle-dev/kettle-family
[kettle-rb]: https://github.com/kettle-dev/kettle-rb
[nomono]: https://github.com/kettle-dev/nomono
[kettle-test]: https://github.com/kettle-dev/kettle-test
[kettle-soup-cover]: https://github.com/kettle-dev/kettle-soup-cover
[kettle-gha-pins]: https://github.com/kettle-dev/kettle-gha-pins
[kettle-drift]: https://github.com/kettle-dev/kettle-drift
[kettle-wash]: https://github.com/kettle-dev/kettle-wash
[kettle-ndjson]: https://github.com/kettle-dev/kettle-ndjson
[token-resolver]: https://github.com/kettle-dev/token-resolver
[structuredmerge-ruby]: https://github.com/structuredmerge/structuredmerge-ruby
