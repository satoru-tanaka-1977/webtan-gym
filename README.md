# Design Fitness（フィットネスジムサイト模写）

WEB鍛の課題として、フィットネスジムのウェブサイトを実装しました。
デザインカンプ・仕様書・デモサイトを見ながら、答えのコードを参照せず自力でコーディングしました。

---

## 使用技術

- HTML5
- CSS3（Flexbox / position / float / background-attachment）
- JavaScript / jQuery
- レスポンシブ対応（@media screen and (max-width: 768px)）

---

## 実装内容

- デザインカンプからのコーディング（答えコード参照なし）
- `background-attachment: fixed`によるパララックス背景の実装
- `position: fixed`を使ったヘッダー・ボタン・ハンバーガーメニューの固定配置
- `float`を使ったテキスト回り込みレイアウト
- jQueryを使ったハンバーガーメニューの実装（上から降りてくるアニメーション）
- `linear-gradient`によるグラデーションフッター
- FLOCSSを意識したCSS設計

---

## 学んだこと

- `background-attachment: fixed`でスクロールしても背景が動かないパララックス効果を実装できた
- `position: fixed`を使った要素の固定配置を実践的に理解できた
- `float`による画像とテキストの回り込みを初めて実装した
- ハンバーガーメニューのアニメーションを自力で実装できた
- デザインカンプから自分でクラス名や構造を考える力がついてきた

---

## 感想

今回は答えのコードを参照せず、デモサイトと検証ツールを見ながらコーディングに挑戦しました。この課題を選んだ理由は`background-attachment: fixed`による背景固定の動きに惹かれたからです。実際に実装してみて、使ったことのないプロパティへの理解が深まりました。ハンバーガーメニューは一番難しかったですが、何とか自力で書くことができて達成感がありました。

---

## 公開URL

👉 https://satoru-tanaka-1977.github.io/webtan-gym/
