# news_scraping

学習用教材　https://www.techpit.jp/courses/enrolled/770110

を学習しました。

スクレイピングはもっと難易度が高いものだと思っていたが、
意外と難しいと言う印象は受けなかった。

URLからHTMLを取得し
HTMLタグを辿って
目的のtextやURLをパースし
jsonファイルで保存


# 使用方法

ruby scrape.rb  で実行

option

--infile 'URL'

--outfile 'file_name'

--category 'category'

--infile と --category は同時に指定は出来ません

