# DB接続までの手順
## 必要なもの
- docker
- ubuntu
- WSL2設定
- A5M2
## 接続まで
- DBサンプルなどをVScodeで開く(gitでクローンするなど)
- .ymlと同じ場所に.envファイルを作成
- .envに各種パラメータを入力(DB_ROOT_PASSはなんでもいい)
- .gitigonreに.envを書き込む　　
    (.envはパスなども含まれるためGitHubに上げないように設定するため)  
- gitBashでdocker-compose up(DBを起動)する
- A5M2でDBが開けるか確認する