# S2J Query Pinned Service - CHANGELOG

## unreleased

## 0.0.1 - 2026-09-28

### Added

* `package.json` を追加 (v0.0.1)。説明はクエリーループでの一覧表示時にピン留めを優先し、残りの N 件を並べ替えるロジック (WordPress 非依存)
* ドキュメント lint を追加 (`@s2j/docs-linter` ^1.0.25、`npm run lint:docs`)
* npm v12以降向けに `.npmrc` の `allow-git=all` と `package.json` の `allowScripts` を追加

### Changed

* README の見出しを `S2J Query Pinned Service` に変更
* `.gitignore` を Composer、Node、テスト成果物向けに拡張
