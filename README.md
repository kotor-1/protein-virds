# NEXT-18 PROTEIN 会員価格のご案内（HappinessAC・VIRDS）

HappinessAC と VIRDS の会員向けのご案内ページです。ページの中身は `index.html` の1ファイルだけです（写真も中に入っています）。

## 書きかえる場所

`index.html` のいちばん上にある、次の2行だけです。`""` の間にURLをそのまま貼ります。

```
var YOUTUBE_URL = "";   // インタビュー動画（YouTube）のURL
var ORDER_URL   = "";   // 注文フォームのURL
```

- `YOUTUBE_URL` を入れると、ページの中でインタビュー動画が再生されます。
- `ORDER_URL` を入れると、「注文フォームを開く」ボタンがそのフォームを開きます。

## 公開のしかた（GitHub Pages）

1. このリポジトリの **Settings** を開く
2. 左のメニューの **Pages** を開く
3. **Branch** を `main`、フォルダを `/ (root)` にして **Save** を押す
4. 1〜2分待つと、次のURLで見られるようになります
   `https://kotor-1.github.io/protein-virds/`

## 知っておくこと

- パスワードはかかりません。URLを知っている人は誰でも見られます。
- 検索には出ない設定にしてあります。
