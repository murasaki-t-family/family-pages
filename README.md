# family-pages

社外・社内に **URL で渡すための公開ページ置き場**。GitHub Pages で配信する。

## ⚠️ このリポは public

ここに置いたものは**誰でも見られる**。次のものは絶対に入れない。

- 社員の個人名（役割名に置き換える）
- 仕入・原価・給与など社外に出せない数字
- 社内限定の資料・議事録・戦略メモ

## 使い方

1フォルダ = 1ページ。`{slug}/index.html` を置くだけ。

```
family-pages/
├── service-flow/index.html   → https://murasaki-t-family.github.io/family-pages/service-flow/
└── {次のページ}/index.html    → https://murasaki-t-family.github.io/family-pages/{次のページ}/
```

- slug は英小文字とハイフンのみ。日付・個人名は入れない（URL が相手に渡るため）
- 1ファイル完結の HTML を推奨（画像や外部 CSS を使わない＝リンク切れが起きない）
- 更新は該当ファイルを上書きして push。URL は変わらない

## 公開ページ一覧

| slug | 内容 | 初出 |
|:--|:--|:--|
| `service-flow` | 可児店サービスの人員配置と入庫の流れ（同業視察向け・個人名なし） | 2026-09 |

## なぜこのリポに集約するか

配布物ごとにリポを新設すると管理が増える。社内配布キットを `family-ai-kits` 1個に集約したのと同じ方針で、**URL 公開するページはこのリポ 1 個**にまとめる。
