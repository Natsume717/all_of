# all_of
predicateのall_ofに関するデータパックサンプルになります。

詳しくはブログ記事『[【マイクラ】all_ofで複数の項目をまとめる【predicate】](https://natsumake.com/predicate_all_of/)』を参考にしてください。

<h3>使い方</h3>

導入後、スコアボードが自動的に生成され、サイドバーに10という値が確認できるはずです。<br>
生成されなかった場合は```/reload```を実行してください。

平野にいる状態でスコアボードの値が10以上100以下の場合に```/execute if predicate sample:test run give @a diamond 1```を実行すると、ダイヤモンドが付与されます。

「平野にいない」「スコアボードの値が適していない」といった場合には、ダイヤモンドが付与されません。
