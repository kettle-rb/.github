# kettle-rb

A collection of freeze-dried and vacuum-sealed Yak shavings for Ruby development & testing.

## AST Merging and Templating Gems

| Gem | Format | Parser | Description |
|-----|--------|--------|-------------|
| [tree_haver][tree_haver] | ASTs | ALL | Cross-Ruby adapter for the tree-sitter & citrus parsing libraries; supporting MRI Ruby, JRuby, & TruffleRuby |
| [ast-merge][ast-merge] | Text | internal | Shared infrastructure for all `*-merge` gems |
| [prism-merge][prism-merge] | Ruby | [Prism][prism] | Smart merge for Ruby source files |
| [psych-merge][psych-merge] | YAML | [Psych][psych] | Smart merge for YAML files |
| [json-merge][json-merge] | JSON | [tree-sitter-json][ts-json] | Smart merge for JSON files |
| [jsonc-merge][jsonc-merge] | JSONC | [tree-sitter-jsonc][ts-jsonc] | ⚠️ Proof of concept; Smart merge for JSON with Comments |
| [bash-merge][bash-merge] | Bash | [tree-sitter-bash][ts-bash] | Smart merge for Bash scripts |
| [rbs-merge][rbs-merge] | RBS | [RBS][rbs] | Smart merge for Ruby type signatures |
| [dotenv-merge][dotenv-merge] | Dotenv | internal ([dotenv][dotenv]) | Smart merge for `.env` files |
| [toml-merge][toml-merge] | TOML | [tree-sitter-toml][ts-toml] | Smart merge for TOML files |
| [markdown-merge][markdown-merge] | Markdown | _base classes_ | Shared foundation for Markdown mergers |
| [markly-merge][markly-merge] | Markdown | [Markly][markly] | Smart merge for Markdown (CommonMark via libcmark-gfm) |
| [commonmarker-merge][commonmarker-merge] | Markdown | [Commonmarker][commonmarker] | Smart merge for Markdown (CommonMark via comrak) |

**Example implementations** for the gem templating use case:

| Gem | Purpose | Description |
|-----|---------|-------------|
| [kettle-jem][kettle-jem] | Gem Templating | Gem template library with smart merge support |

## Dev Harness

| Gem | Purpose | Description |
|-----|---------|-------------|
| [kettle-dev][kettle-dev] | Gem Development | Complete rake & dev harness for Ruby development; tasks for coverage, GHA console, linting, debugging, etc. |

## Test Harness

| Gem | Purpose | Description |
|-----|---------|-------------|
| [kettle-test][kettle-test] | Spec Development | Complete RSpec test harness, temporal manipulation, silent output testing, block expectations, etc. |
| [kettle-soup-cover][kettle-soup-cover] | Test Coverage Harness | A Covered Kettle of SOUP. Configure SimpleCov in 4 LOC for every CI platform, w/ 12-factor ENV-based controls | 

## Ruby Utilities

| Gem | Purpose | Description |
|-----|---------|-------------|
| [kettle-wash][kettle-wash] | Spec Development | Coming soon! Runner up name: "constant_change". Provides a pattern for resetting constants for consistent deterministic results. |

[kettle-dev]: https://github.com/kettle-rb/kettle-dev
[kettle-jem]: https://github.com/kettle-rb/kettle-jem
[kettle-test]: https://github.com/kettle-rb/kettle-test
[kettle-wash]: https://github.com/kettle-rb/kettle-wash
[kettle-soup-cover]: https://github.com/kettle-rb/kettle-soup-cover

[tree_haver]: https://github.com/kettle-rb/tree_haver
[ast-merge]: https://github.com/kettle-rb/ast-merge
[prism-merge]: https://github.com/kettle-rb/prism-merge
[psych-merge]: https://github.com/kettle-rb/psych-merge
[json-merge]: https://github.com/kettle-rb/json-merge
[jsonc-merge]: https://github.com/kettle-rb/jsonc-merge
[bash-merge]: https://github.com/kettle-rb/bash-merge
[rbs-merge]: https://github.com/kettle-rb/rbs-merge
[dotenv-merge]: https://github.com/kettle-rb/dotenv-merge
[toml-merge]: https://github.com/kettle-rb/toml-merge
[markdown-merge]: https://github.com/kettle-rb/markdown-merge
[markly-merge]: https://github.com/kettle-rb/markly-merge
[commonmarker-merge]: https://github.com/kettle-rb/commonmarker-merge
[prism]: https://github.com/ruby/prism
[psych]: https://github.com/ruby/psych
[ts-json]: https://github.com/tree-sitter/tree-sitter-json
[ts-jsonc]: https://gitlab.com/WhyNotHugo/tree-sitter-jsonc
[ts-bash]: https://github.com/tree-sitter/tree-sitter-bash
[ts-toml]: https://github.com/tree-sitter-grammars/tree-sitter-toml
[rbs]: https://github.com/ruby/rbs
[dotenv]: https://github.com/bkeepers/dotenv
[markly]: https://github.com/kivikakk/markly
[commonmarker]: https://github.com/gjtorikian/commonmarker
