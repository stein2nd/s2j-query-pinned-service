# S2J Query Pinned Service - CHANGELOG

## unreleased

## 0.0.1 - 2026-09-29

### Added

* 確定前のサービス仕様 `docs_mod/service_spec.md` を追加 (クエリーループでの一覧表示時にピン留めを優先し、残りを別条件で並べ替える。WordPress 非依存)
* `docs_mod/` に概要、コンセプト、設計原則、アーキテクチャー、実装タスク、実装状況、テスト仕様、テスト結果の文書枠を追加

### Changed

* `docs_mod/specs.md` からサービス仕様への参照を追加
* `.textlintrc.json` の allowlist に `kis-wordpress`、`s2j-query-pinned-service`、`s2j-content-dates-service` 等を追加

## 0.0.1 - 2026-09-28

### Added

* `composer.json` を追加 (v0.0.1、`s2j/query-pinned-service`)。PHP `>=8.0`、オートロードは `S2J\QueryPinnedService\` → `src/`
* 開発用依存に `phpunit/phpunit` ^13.1、`phpstan/phpstan` ^2.1、`squizlabs/php_codesniffer` ^4.0を追加

* `package.json` を追加 (v0.0.1)。説明はクエリーループでの一覧表示時にピン留めを優先し、残りの N 件を並べ替えるロジック (WordPress 非依存)
* ドキュメント lint を追加 (`@s2j/docs-linter` ^1.0.25、`npm run lint:docs`)
* npm v12以降向けに `.npmrc` の `allow-git=all` と `package.json` の `allowScripts` を追加

### Changed

* README の見出しを `S2J Query Pinned Service` に変更
* `.gitignore` を Composer、Node、テスト成果物向けに拡張
