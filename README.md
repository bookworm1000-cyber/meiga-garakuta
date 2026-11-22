# 名画かガラクタか

絵を見て値段をつける鑑定ゲームの試作です。675億円の名画から、0円の子どもの絵や無料写真まで、10点が出てきます。

## 遊び方

1. 額に入った作品を見て、電卓で値段を入れます。「42」→「億」で42億円です。
2. 作者や来歴はヒントで見られます。1つ使うごとに得点が15%減ります。
3. 実際の値打ちとの差は「何倍ずれたか」で採点します。ぴったりなら1000点、10倍ずれると600点です。
4. 10点を鑑定し終えると、和紙の認定証がもらえます。

## 作品と価格について

10点のうち8点は、このゲームのために描いた架空の作品で、価格もそれらしい例です。実在するのは次の2点です。

| 作品 | 実際の値打ち | 出典 |
|---|---|---|
| レオナルド・ダ・ヴィンチ(とされる)『サルバトール・ムンディ』(1500年ごろ) | 4億5,030万ドル。2017年11月15日、クリスティーズ・ニューヨークでの落札額(手数料込み)。ゲーム内では1ドル=150円で換算し、約675億円 | [NPR](https://www.npr.org/sections/thetwo-way/2017/11/16/564527819/da-vinci-portrait-of-christ-sells-for-record-shattering-450-million) |
| 夕焼けの写真『Oslo sunset』 | 0円(CC0で無料公開) | 下記の画像出典 |

## 出典

| ファイル | 元の画像 | ライセンス |
|---|---|---|
| `images/salvator-mundi.jpg` | [Leonardo da Vinci, Salvator Mundi, c.1500](https://commons.wikimedia.org/wiki/File:Leonardo_da_Vinci,_Salvator_Mundi,_c.1500,_oil_on_walnut,_45.4_%C3%97_65.6_cm.jpg)(Wikimedia Commons) | パブリックドメイン |
| `images/sunset-oslo.jpg` | [Oslo sunset (Unsplash)](https://commons.wikimedia.org/wiki/File:Oslo_sunset_(Unsplash).jpg) 撮影 Kristofer Selbekk(Wikimedia Commons) | CC0 |
| そのほかの `images/*.jpg` | このゲームのためにプログラムで描いた画像 | - |

どちらも表示用に縮小しています。フォントはGoogle Fontsから読み込んでいます(Yuji Syuku、Klee One、Shippori Mincho B1、Zen Kaku Gothic New)。
