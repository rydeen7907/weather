=====

気象情報データダウンロード

・get_amedas_data.py

アメダス観測所リストダウンロード

・get_amedas_station_url.py


・気象情報データをダウンロードする前に

  観測所リストのダウンロードを先に行う
  
  観測所番号4桁と5桁に対応


・データのダウンロードに入力する事項(ターミナルに入力)

  観測所リストに記載された都道府県と観測所名
  
    日毎：daily
    1時間毎：hourly
    10分毎：10min  
  
  期間
    
    日毎：1ヶ月単位
    1時間・10分毎：1日単位
    それぞれ選択し開始と終了を入力
    
  ※入力ミスをするとエラーを起こしプログラムがその場で停止する
  
  ※インデントを2からデフォルトの4にするとインデントエラーが多発するので注意


・ダウンロードファイルはcsv形式で同一フォルダに保管され

  気象庁のサイトに準拠した内容で表示されるように項目を設定
  
  ファイルはEXCELで確認可能


・詳細は気象庁のサイトを参照

=====
