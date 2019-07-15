# はなまる手帳

あなたにとって大事なひとに  
こころのこもった「はなまる」を

## TL; DR
1. アカウント登録します
1. フレンド登録します
1. ブラウザから「はなまる」を送ります
1. あなたの大事なひとに「はなまる」が届きます

…となる予定です。のんびりつくります。

## docker-compose
コンテナをビルド
`$ docker-compose build`
コンテナを起動
`$ docker-compose up -d`
データベース作成
`$ docker-compose run web rails db:create`

コンテナ停止
`$ docker-compose down`

Dockerfileやdocker-compose.ymlの変更を反映、railsサーバーを再起動
`$ docker-compose up --build`

bundle installなどのコマンドを実行したい
`$ docker-compose run web bundle install`
