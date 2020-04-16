# sprints
Code sprints

## Events

* [2018/9/20-21](20180920) @ゼミ合宿
* [2018/1/12](20180112) @第4共同研究室 (10F) 10:00-16:00
* [2016/5/14](20160514)


## Open Source Software Projects

* [QuantEcon.py](https://github.com/QuantEcon/QuantEcon.py)
  * [Issues](https://github.com/QuantEcon/QuantEcon.py/issues)
  * [Contribute to QuantEcon.py](https://quantecon.org/python-developers/)

* [QuantEcon.jl](https://github.com/QuantEcon/QuantEcon.jl)
  * [Issues](https://github.com/QuantEcon/QuantEcon.jl/issues)
  * [Contribute to QuantEcon.jl](https://quantecon.org/julia-developers/)

* [Games.jl](https://github.com/QuantEcon/Games.jl)
  * [Issues](https://github.com/QuantEcon/Games.jl/issues)

* [QuantEcon Notes](http://notes.quantecon.org)

* [QuantEcon Open Notebook Archive](http://quantecon.org/notebooks.html)

* [MatchingMarkets.jl](https://github.com/oyamad/MatchingMarkets.jl)


## 情報

* [StudyNotes](https://github.com/OyamaZemi/StudyNotes)
* [Get Involved](https://quantecon.org/contribute/) - quantecon.org
* [初心者でもできるはじめてのPull Request](http://lv4.hateblo.jp/entry/2015/04/05/120929)
* [SourceTreeでコミットをまとめる時のメモ](http://seeku.hateblo.jp/entry/2015/10/14/091822)
* [すぐ忘れる！SourceTreeを使ったリベースとスカッシュの手順](http://qiita.com/ryounagaoka/items/7c129e98a7f81c507a61)
* [Closing issues using keywords](https://help.github.com/articles/closing-issues-using-keywords/)
* [Git関連で忘れちゃうことのまとめ](https://github.com/Yuya-Furusawa/Self-Study/blob/master/Git_cheat.md) by Yuya-Furusawa


## 作業の手順

0. 貢献先プロジェクトのレポをフォークする．
   * SourceTree でフォークの URL から新規リポジトリを作る．
   * 本家のレポを「リモートを追加」で追加する ("upstream" とか名前をつける)．
1. 作業を始める前に「フェッチ」「プル」で `master` ブランチを本家と同期させる．
2. 必ず新しいブランチを作って作業する (`master` は同期用としてのみ使う)．
3. 実際にファイルを編集する．
   * コードを書く．
   * Docstring を書く．
   * テストを書く．
   * スタイルガイドに従って書くこと．
4. コミットする．
   * コミットメッセージを内容がわかるようにちゃんと書くこと．
5. 更新版のパッケージをインストールし，テストを実行してちゃんと通るか確認する．
6. GitHub にプッシュする．
7. プルリクエストを出す．
   * 内容がわかるようにメッセージを書く．
   * 関連 issue があるときは，"Close #123" (123 のところは issue 番号を入れる) と書いておくと，マージされたときに issue も同時に閉じられる．
