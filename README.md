# toapps-site

個人事業者 **TO Apps** の公開サイト。事業者情報と、提供アプリの案内・法務文書（利用規約 / プライバシーポリシー / 特定商取引法に基づく表示）を配信する。

- **公開 URL**: <https://toapps.dev/>
- ホスティング: GitHub Pages（Custom Domain）

## ディレクトリ構成

| パス                           | 内容                                                          |
| ------------------------------ | ------------------------------------------------------------- |
| `index.md`                     | トップページ（事業者情報 / 提供アプリの案内）                 |
| `ja/sct.md`                    | 特定商取引法に基づく表示（事業者単位のためサイト直下）        |
| `shuffleep/index.md`           | Shuffleep のページ                                            |
| `shuffleep/{ja,en}/terms.md`   | Shuffleep の利用規約（ja / en・アプリ固有）                   |
| `shuffleep/{ja,en}/privacy.md` | Shuffleep のプライバシーポリシー（ja / en・アプリ固有）       |
| `shuffleep/legalManifest.json` | Shuffleep と公開法務文書の同期用メタデータ                    |
| `legalManifest.schema.json`    | legalManifest の JSON Schema（アプリ横断のためルートに置く）  |

利用規約・プライバシーポリシーはアプリ固有の文書のため、各アプリのディレクトリ（`shuffleep/`）配下に置く。特定商取引法に基づく表示は事業者単位の表示義務のため、アプリに依存せずサイト直下に置く。

## 収録文書

| 文書                     | 言語 | URL                                            |
| ------------------------ | ---- | ---------------------------------------------- |
| 利用規約                 | ja   | <https://toapps.dev/shuffleep/ja/terms.html>   |
| 利用規約                 | en   | <https://toapps.dev/shuffleep/en/terms.html>   |
| プライバシーポリシー     | ja   | <https://toapps.dev/shuffleep/ja/privacy.html> |
| プライバシーポリシー     | en   | <https://toapps.dev/shuffleep/en/privacy.html> |
| 特定商取引法に基づく表示 | ja   | <https://toapps.dev/ja/sct.html>               |

`legalManifest.json`（[配信 URL](https://toapps.dev/shuffleep/legalManifest.json) / [JSON Schema](https://toapps.dev/legalManifest.schema.json)）は、Shuffleep と公開法務文書の同期用メタデータ。各文書の `latestRevision` / `minRequiredRevision` / `versionDate` / 公開 URL を配信する。アプリは起動時に 1 回取得し、`minRequiredRevision` が同意済み revision を上回る場合に再同意フローを表示する。

## 言語の優先順位

各言語版に齟齬がある場合は、**日本語版を正本** とします（The Japanese version prevails）。

## ライセンス

法務文書本文は本サービスの法的拘束のため公開している。自由な再利用・改変・転載は許可しない。引用は出典明記のうえ可とする。

## 問い合わせ

<contact@toapps.dev>
