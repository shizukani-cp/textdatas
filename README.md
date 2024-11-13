# textdatas
## このリポジトリの目的
自然言語処理をする際、トレーニングデータが必要になります。  
そこで、私は青空文庫から持ってくるのですが、ルビがあったりなど、少々自然言語処理には使いづらくなっています。  
だったら、そういう場所を作ればいい！として、このリポジトリを作りました。
## 使い方
### 1. 複数の作品を使う場合
複数の作品をまとめて使う場合、
1. リポジトリ(datasフォルダのみでもよい)をクローン
2. findなどを組み合わせて結合したり、お好みの言語で追加の処理をする
3. 自然言語処理を実行する
という手順を踏みます。
### 2. 特定の作品のみ使う場合
特定の作品のみ使う場合は、
1. リポジトリのファイル検索で、作品の名前を検索し、作品の情報のJSONを見つける
2. JSONの中のpathから、作品自体のファイルを特定する
3. 特定したファイルをダウンロードする
4. (ある場合は)お好みの言語で追加の処理をする
5. 自然言語処理を実行する
という手順を踏みます。
## 貢献したい方
このリポジトリは、皆さんにデータを持ってきていただくことで成長します！  
ただし、作品の利用しやすさを第一にしたリポジトリであるため、次のことを守ってデータを持ってきてください。
- **データを機械的に収集しないこと。** ほかのサイト利用者に迷惑が掛かります。
- **作品自体のファイルには本文のみが書かれるようにすること。** 目次やルビなどがあると、自然言語処理の邪魔になります。
- **作品自体のファイルと作品の情報のJSONが必ずリンクされるようにすること。** これをしないと、せっかくクローンしたのに使われない作品が出てきたりします。
また、場合によっては以下のことをしてください
- ファイルサイズが大きくなる場合は、適宜git lfsを使用してください。pushできなくなると、せっかくデータを作った意味すらなくなってしまいます。ただし、git lfsは、push
この条件を守ったうえで、このリポジトリを成長させましょう！
## ライセンス
このリポジトリは、MITライセンスで公開しています。煮るなり焼くなり自由に使ってください。喜んでいただけると本望です。

