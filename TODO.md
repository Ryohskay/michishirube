# TODO - minimal/
- 一部のページについてminimal-mistakesのデモサイトのようなメニューを実装する

# TODO_done
- :white_check_mark: まずはリンクを`{{ site.baseurl }}{% link permalink %}`におきかえる
  - :arrow_right: 完了
- :white_check_mark: すべての \_pages/ のpermalinkが`.html`で終わるようにする
  - \_posts/ に関してはpermalinkをいじる必要はない
  - :arrow_right: `_pages/` を collections に登録した結果 `page.html` でルーティングされている(はず).
    - NB: There might be some broken links due to this change (somehow it works differently on the local `jekyll serve` and on the real remote server).
