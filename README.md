# 絵で覚える単語帳 — Picture Vocabulary

フラッシュカードをめくる方式ではなく、**絵（場面）から英単語を連想して、イメージで理解する**単語帳アプリです。

## 使い方

`index.html` をブラウザで開くだけで使えます（ビルド不要、単一ファイル）。

- **絵から連想**: 大きな絵と場面の説明を見て、頭の中で英単語を言ってから「単語を見る」で答え合わせ。単語・意味に加えて、絵と単語をつなぐ「連想メモ」と例文が表示されます。
- **絵あてクイズ**: 絵を見て、4つの選択肢から正しい単語を選びます。
- **単語から絵を選ぶ（アウトプット）**: 英単語を見て、そのイメージに合う絵を4つの絵から選びます。逆向きの出題で「分かる」から「使える・思い出せる」への練習になります。正解すると意味・場面・連想メモ・例文で答え合わせができ、スコア（正解数／挑戦数と連続正解）も表示されます。
- **単語テスト（英検の級別）**: 単語には英検の級の目安（5級〜1級）が付いています。「単語テスト」タブを開くと級の一覧が出て、級を選ぶとその級の単語だけが出題される「絵から連想」テスト（4択・最大10問）が始まります。最後にスコアと全問のふりかえり（正解・自分の答え・連想メモ）が表示されます。

## 収録単語（サンプル）

全54語を英検の目安で級分けしています。

- 5級（11語）: rainbow, apple, dog, cat, bird, fish, sun, moon, star, rain, snow
- 4級（9語）: waterfall, beach, mountain, river, bridge, cloud, leaf, key, gift
- 3級（8語）: lighthouse, blossom, forest, island, rocket, balloon, candle, mirror
- 準2級（7語）: harvest, volcano, desert, wave, cave, feather, sprout
- 2級（7語）: horizon, glacier, cliff, tide, breeze, dawn, thunder
- 準1級（6語）: eclipse, tornado, avalanche, ember, mist, aurora
- 1級（6語）: constellation, fossil, drought, tsunami, monsoon, gravity

自分で追加する単語にも、追加フォームで英検の目安を設定できます（未分類も可）。
- **絵のギャラリー**: 登録した単語を絵の一覧で眺めて復習できます。
- **単語の追加**: 単語・意味に加えて、絵文字、画像URL（任意）、場面の説明、連想メモ、例文を登録できます。画像URLを入れるとその画像が「絵」として表示されます。

登録した単語はブラウザの localStorage に保存されます。GitHub はコード管理のために使います（単語データの保存先ではありません）。

## サンプル単語

waterfall（滝）、lighthouse（灯台）、rainbow（虹）、blossom（花・開花）、harvest（収穫）、horizon（地平線）の6語が最初から入っています。不要なら一覧から削除できます。
