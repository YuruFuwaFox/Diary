# What's batch?
定期データを取得して処理すること  
驚くほどわからなくて草  
  
流れ的にはDB（ログ保存）→スケジュールで起動→回収というシンプルなわけだが何もわからないの草  
まずはそもそもAPIのログ出力を考えるべ  
何がわからんかまず考えた方がいい気がするべし  
  
  
だいたいの流れはlogbackで出力設定（TSV?）→Interceptorでlogを出すようにする（ログを出すとlogbackの設定でファイルに保存）→Batchでファイルからデータ作成、DBに保存みたいな感じ
  
  
[logback.xmlを設定する](https://javazuki.com/articles/slf4j-logback-usage.html)  
[ログバックの手引き](https://www.codeflow.site/ja/article/logback)  
[Logback 使い方メモ](https://qiita.com/opengl-8080/items/49719f2d35171f017aa9)  
[バッチ処理をちゃんと作るための基本](https://qiita.com/utisam/items/1d15f95c933b7d39c556#%E3%83%90%E3%83%83%E3%83%81%E5%87%A6%E7%90%86%E3%81%AE%E6%8A%BD%E8%B1%A1%E5%8C%96)  
[logback機能,設定まとめ](https://qiita.com/rubytomato@github/items/93770f827e46cc7e684f#fileappender)  
非常に重要  
主に必要な事柄や、それからファイル出力についてなど  
リファレンスもまとまっている  
[第4章 アペンダー](http://logback.qos.ch/manual/appenders_ja.html)  
アペンダーなどについて  
[Logbackでファイルにログを吐く時の基本設定](https://qiita.com/joe_hrmn/items/356f1e2b05cb90241414)  
割と参考になるかも  
[Logback 使い方メモ](https://qiita.com/opengl-8080/items/49719f2d35171f017aa9)  
logbackについての大きなまとめみたいな  
[Spring Bootでlogback-spring.xmlを使ったロガーの設定](https://tomokazu-kozuma.com/setting-loggers-using-logback-spring-xml-in-spring-boot/)
[処理時間の計測](https://qiita.com/shyu/items/55a02ee79b31ca5ea97a)
[リクエストへの属性追加](https://www.javadrive.jp/servlet/dispatch/index3.html)
[HTTP リクエストとレスポンス](https://www.samuraiz.co.jp/adobeproduct/jrun/docs/jr4/docs/html/Programmers_Guide/techniques_servlet8.html)
[]()
[]()
