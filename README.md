# dlkk.io（Danshiko Lab K.K / GDLKK）静的サイト

Squarespace（2026-11 で終了）から移したもの。2 ページだけ（トップ＝旧 /danshiko-lab と同じ中身、/company/）。旧サイトの /services /gallery /information /store はテンプレートの残りなので移していない。
- 画像は旧サイトから取得（写真 3 枚・取引先ロゴ 19 枚）。ビルド不要の素の HTML/CSS
- 公開先の想定: GitHub Pages（公開リポジトリ・独自ドメイン dlkk.io・CNAME ファイル同梱）
- DNS（Squarespace Domains で管理）: apex A を 185.199.108.153 / .109 / .110 / .111、www を CNAME `<owner>.github.io`。MX（Google Workspace）は触らない
