<a href="https://github.com/kettle-dev"><img alt="kettle-dev Logo by Aboling0, CC BY-SA 4.0" src="https://logos.galtzo.com/assets/images/kettle-dev/avatar-192px.svg" width="14%" align="right"/></a>

# kettle-dev

`kettle-dev` is a family of Ruby tooling gems for maintaining RubyGems with a
consistent development, test, coverage, CI, release, and templating workflow.

The organization was previously named `kettle-rb`. Older references to
`kettle-rb/*` are historical; current Kettle tooling lives under
`kettle-dev/*`.

## Community And Support

[![Ruby Users Forum][ruby-forum-img]][ruby-forum]
[![Live Chat on Discord][discord-img]][discord]

Use the [kettle-dev tag on RubyForum][ruby-forum] for support threads, release
workflow questions, and design notes. Discord is available for live
coordination.

### Financial Support

Support kettle-dev through [Open Collective][fund],
[GitHub Sponsors][sponsor], or [Liberapay][liberapay].

## Projects

| Project | Description | RubyGems | Current CI | Funding |
|---------|-------------|----------|------------|---------|
| [kettle-dev](https://github.com/kettle-dev/kettle-dev) | Development, release, changelog, documentation, and CI workflow tooling. | [![kettle-dev][kettle-dev-rank-img]][kettle-dev-rank] | [![CI Current][kettle-dev-ci-img]][kettle-dev-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-family](https://github.com/kettle-dev/kettle-family) | Dependency-ordered family operations across related RubyGem repositories. | [![kettle-family][kettle-family-rank-img]][kettle-family-rank] | [![CI Current][kettle-family-ci-img]][kettle-family-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-test](https://github.com/kettle-dev/kettle-test) | RSpec test harness and helper bundle for Kettle-managed gems. | [![kettle-test][kettle-test-rank-img]][kettle-test-rank] | [![CI Current][kettle-test-ci-img]][kettle-test-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-soup-cover](https://github.com/kettle-dev/kettle-soup-cover) | SimpleCov setup and coverage reporting for local runs and CI providers. | [![kettle-soup-cover][kettle-soup-cover-rank-img]][kettle-soup-cover-rank] | [![CI Current][kettle-soup-cover-ci-img]][kettle-soup-cover-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-gha-pins](https://github.com/kettle-dev/kettle-gha-pins) | GitHub Actions SHA pin discovery, validation, and upgrade planning. | [![kettle-gha-pins][kettle-gha-pins-rank-img]][kettle-gha-pins-rank] | [![CI Current][kettle-gha-pins-ci-img]][kettle-gha-pins-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-rb](https://github.com/kettle-dev/kettle-rb) | Shared Ruby, engine, Rails, RuboCop, and RuboCop LTS compatibility data. | [![kettle-rb][kettle-rb-rank-img]][kettle-rb-rank] | [![CI Current][kettle-rb-ci-img]][kettle-rb-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-ndjson](https://github.com/kettle-dev/kettle-ndjson) | NDJSON event stream primitives for Kettle CLIs. | [![kettle-ndjson][kettle-ndjson-rank-img]][kettle-ndjson-rank] | [![CI Current][kettle-ndjson-ci-img]][kettle-ndjson-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-drift](https://github.com/kettle-dev/kettle-drift) | Detect duplicated adjacent lines introduced by template drift. | [![kettle-drift][kettle-drift-rank-img]][kettle-drift-rank] | [![CI Current][kettle-drift-ci-img]][kettle-drift-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [kettle-wash](https://github.com/kettle-dev/kettle-wash) | Constant unloading helpers for Ruby test and reload workflows. | [![kettle-wash][kettle-wash-rank-img]][kettle-wash-rank] | [![CI Current][kettle-wash-ci-img]][kettle-wash-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [nomono](https://github.com/kettle-dev/nomono) | ENV-driven Gemfile macros for resolving local sibling gems. | [![nomono][nomono-rank-img]][nomono-rank] | [![CI Current][nomono-ci-img]][nomono-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |
| [token-resolver](https://github.com/kettle-dev/token-resolver) | PEG-based token parsing and replacement for template pipelines. | [![token-resolver][token-resolver-rank-img]][token-resolver-rank] | [![CI Current][token-resolver-ci-img]][token-resolver-ci] | [Open Collective][fund] / [GitHub Sponsors][sponsor] / [Liberapay][liberapay] |

## Related Project: StructuredMerge

The AST and structured merge gems that used to be separate repositories under
the old `kettle-rb` organization now live in the
[structuredmerge-ruby][structuredmerge-ruby] monorepo.

[ruby-forum]: https://www.rubyforum.org/tag/kettle-dev
[ruby-forum-img]: https://img.shields.io/discourse/topics?server=https%3A%2F%2Fwww.rubyforum.org&style=for-the-badge&logo=discourse&label=Ruby%20Users%20Forum
[discord]: https://discord.gg/3qme4XHNKN
[discord-img]: https://img.shields.io/discord/1373797679469170758?style=for-the-badge&logo=discord
[fund]: https://opencollective.com/kettle-dev
[sponsor]: https://github.com/sponsors/pboling
[liberapay]: https://liberapay.com/pboling/donate
[structuredmerge-ruby]: https://github.com/structuredmerge/structuredmerge-ruby
[kettle-dev-rank]: https://bestgems.org/gems/kettle-dev
[kettle-dev-rank-img]: https://img.shields.io/gem/rd/kettle-dev.svg
[kettle-dev-ci]: https://github.com/kettle-dev/kettle-dev/actions/workflows/current.yml
[kettle-dev-ci-img]: https://github.com/kettle-dev/kettle-dev/actions/workflows/current.yml/badge.svg?branch=main
[kettle-family-rank]: https://bestgems.org/gems/kettle-family
[kettle-family-rank-img]: https://img.shields.io/gem/rd/kettle-family.svg
[kettle-family-ci]: https://github.com/kettle-dev/kettle-family/actions/workflows/current.yml
[kettle-family-ci-img]: https://github.com/kettle-dev/kettle-family/actions/workflows/current.yml/badge.svg?branch=main
[kettle-test-rank]: https://bestgems.org/gems/kettle-test
[kettle-test-rank-img]: https://img.shields.io/gem/rd/kettle-test.svg
[kettle-test-ci]: https://github.com/kettle-dev/kettle-test/actions/workflows/current.yml
[kettle-test-ci-img]: https://github.com/kettle-dev/kettle-test/actions/workflows/current.yml/badge.svg?branch=main
[kettle-soup-cover-rank]: https://bestgems.org/gems/kettle-soup-cover
[kettle-soup-cover-rank-img]: https://img.shields.io/gem/rd/kettle-soup-cover.svg
[kettle-soup-cover-ci]: https://github.com/kettle-dev/kettle-soup-cover/actions/workflows/current.yml
[kettle-soup-cover-ci-img]: https://github.com/kettle-dev/kettle-soup-cover/actions/workflows/current.yml/badge.svg?branch=main
[kettle-gha-pins-rank]: https://bestgems.org/gems/kettle-gha-pins
[kettle-gha-pins-rank-img]: https://img.shields.io/gem/rd/kettle-gha-pins.svg
[kettle-gha-pins-ci]: https://github.com/kettle-dev/kettle-gha-pins/actions/workflows/current.yml
[kettle-gha-pins-ci-img]: https://github.com/kettle-dev/kettle-gha-pins/actions/workflows/current.yml/badge.svg?branch=main
[kettle-rb-rank]: https://bestgems.org/gems/kettle-rb
[kettle-rb-rank-img]: https://img.shields.io/gem/rd/kettle-rb.svg
[kettle-rb-ci]: https://github.com/kettle-dev/kettle-rb/actions/workflows/current.yml
[kettle-rb-ci-img]: https://github.com/kettle-dev/kettle-rb/actions/workflows/current.yml/badge.svg?branch=main
[kettle-ndjson-rank]: https://bestgems.org/gems/kettle-ndjson
[kettle-ndjson-rank-img]: https://img.shields.io/gem/rd/kettle-ndjson.svg
[kettle-ndjson-ci]: https://github.com/kettle-dev/kettle-ndjson/actions/workflows/current.yml
[kettle-ndjson-ci-img]: https://github.com/kettle-dev/kettle-ndjson/actions/workflows/current.yml/badge.svg?branch=main
[kettle-drift-rank]: https://bestgems.org/gems/kettle-drift
[kettle-drift-rank-img]: https://img.shields.io/gem/rd/kettle-drift.svg
[kettle-drift-ci]: https://github.com/kettle-dev/kettle-drift/actions/workflows/current.yml
[kettle-drift-ci-img]: https://github.com/kettle-dev/kettle-drift/actions/workflows/current.yml/badge.svg?branch=main
[kettle-wash-rank]: https://bestgems.org/gems/kettle-wash
[kettle-wash-rank-img]: https://img.shields.io/gem/rd/kettle-wash.svg
[kettle-wash-ci]: https://github.com/kettle-dev/kettle-wash/actions/workflows/current.yml
[kettle-wash-ci-img]: https://github.com/kettle-dev/kettle-wash/actions/workflows/current.yml/badge.svg?branch=main
[nomono-rank]: https://bestgems.org/gems/nomono
[nomono-rank-img]: https://img.shields.io/gem/rd/nomono.svg
[nomono-ci]: https://github.com/kettle-dev/nomono/actions/workflows/current.yml
[nomono-ci-img]: https://github.com/kettle-dev/nomono/actions/workflows/current.yml/badge.svg?branch=main
[token-resolver-rank]: https://bestgems.org/gems/token-resolver
[token-resolver-rank-img]: https://img.shields.io/gem/rd/token-resolver.svg
[token-resolver-ci]: https://github.com/kettle-dev/token-resolver/actions/workflows/current.yml
[token-resolver-ci-img]: https://github.com/kettle-dev/token-resolver/actions/workflows/current.yml/badge.svg?branch=main
