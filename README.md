# kabukawa.biz

Kunihisa Abukawa の入り口である。職務経歴書と、決済システムの鳥瞰図へのリンクを置いている。

履歴書そのものは `kabukawa.github.io`（https://resume.kabukawa.biz/）のままである。このリポジトリは、その履歴書を置き換えない。

## 公開

GitHub Pages は `main` ブランチのルートを HTTPS で公開する。`kabukawa.github.io` に独自ドメイン `resume.kabukawa.biz` が付いているため、独自ドメインを付ける前の URL は https://resume.kabukawa.biz/home/ になる。

`kabukawa.biz` 自体は、Value Domain（`ns1.value-domain.com`）で管理されている。apex には A レコードも AAAA レコードも無い。次のレコードを足し、このリポジトリの Pages にカスタムドメイン `kabukawa.biz` を付ければ、https://kabukawa.biz/ で開く。

| 種別 | 名前 | 値 |
| --- | --- | --- |
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| AAAA | `@` | `2606:50c0:8000::153` |
| AAAA | `@` | `2606:50c0:8001::153` |
| AAAA | `@` | `2606:50c0:8002::153` |
| AAAA | `@` | `2606:50c0:8003::153` |
| CNAME | `www` | `kabukawa.github.io` |

`www` の CNAME は、リポジトリ名を含めず `kabukawa.github.io` を向ける。既存の TXT（Google のサイト確認）はそのまま残す。
