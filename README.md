# README

index, find_contours, area_divisionは無視してください。俺の迷走の跡です。
<br>
Binaryzationは２値化に関するファイルです。大津の２値化やガンマ補正など、どうやって２値化するのかを試行錯誤していました。
<br>
color_categorizeはRGB値から色の判定をするファイルです(0,0,0なら黒など)。
現状ではHSVに変換してからユークリッド距離を求めていますがなかなか上手くいかない感じです。
<br>
Productionはアプリに使う処理を書くファイルです。
彩度に２値化し、ROIを決め、減色する過程が書いてあります。最終的にここのコードをサーバーに移植する予定です。
