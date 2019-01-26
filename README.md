# d3js
プログラムを走らせる時は：
<ul>
  <li>どこかのディレクトリにクローン</li>
  <li>ローカルでサーバーを立ち上げる(そのディレクトリで　$python3 -m http.server 8000 とか)</li>
  <li>ブラウザでlocalhost:8000とか入れる</li>
</ul>

<ul>
  <li>drag_zoom_treeはSFCのメディアセンターの蔵書の分類を可視化したもの。</li>
  <li>force_directed_graphは、SFCの１４学則の科目間の関連科目（青色）、推奨および必須科目（赤色、矢印あり）を可視化したもの</li>
  <li>visTakefujiは、<a href="http://web.sfc.keio.ac.jp/~takefuji/list.html">http://web.sfc.keio.ac.jp/~takefuji/list.html</a>におけるプログラムの更新を可視化したもの。</li>
</ul>

<ul>
  <li>drag_zoom_treeとforce_directed_graphはインタラクティブ。</li>
  <li>ドラッグで移動。スクロールで拡大、縮小</li>
  <li>force_directed_graphとvisTakefujiの中のPythonコードはデータ取得用。いつでも更新できる。</li>
  <li>d3jsをGithub Pagesで動かすやり方が知りたかった</li>
  <li><a href="https://scrapbox.io/sfc-vis2018/13._P5.jsとD3.js" target="_blank">Scrapboxから実行するやつ</a>で、HTMLファイルも扱えるとそっち経由で動かせた可能性があった（欲しい）</li>
</ul>

<ul>
  <li>drag_zoom_tree</li>
  <img src="https://github.com/GoNishimura/images/blob/master/books.png">

  <li>force_directed_graph</li>
  <img src="https://github.com/GoNishimura/images/blob/master/courses.png">

  <li>visTakefuji</li>
  <img src="https://github.com/GoNishimura/images/blob/master/take.png">
</ul>
