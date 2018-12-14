
#### メモ

SVG画像の background-image変換用
https://blog.s0014.com/posts/2017-01-19-il-to-svg/

```css
/* background に グラデーション（RGBA指定で背景透過）と、背景画像をつけることで、双方を同時に表示できる。 */
main_background {
    background: radial-gradient(rgba(8, 18, 69, .9), rgba(8, 18, 49, 1))
    , url('data:image/svg+xml;charset=utf8,%3Csvg%20width%3D%2260px%22%20height%3D%2260px%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20enable-background%3D%22new%200%200%2060%2060%22%3E%20%3Cline%20x1%3D%220%22%20y1%3D%220%22%20x2%3D%220%22%20y2%3D%2260%22%20stroke%3D%22%23283261%22%20stroke-width%3D%221%22%20%2F%3E%20%3Cline%20x1%3D%220%22%20y1%3D%220%22%20x2%3D%2260%22%20y2%3D%220%22%20stroke%3D%22%23283261%22%20stroke-width%3D%221%22%20%2F%3E%3C%2Fsvg%3E');
}
```

アイコン取得先
<div>Icons made by <a href="https://www.flaticon.com/authors/good-ware" title="Good Ware">Good Ware</a> from <a href="https://www.flaticon.com/" 			    title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" 			    title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a></div>


スタイル変更可能なSVG画像のファイルからの取得方法
https://qiita.com/y_hokkey/items/7114728066ea88de9362

