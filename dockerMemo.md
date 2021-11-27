# Dockerのコマンドまとめ
## docker-compose
- up  
    docker上でDBを起動、ctrl+Cで表示をやめる  
    -dでバックグラウンド起動
- stop  
    起動しているDBを止める
- down  
    起動しているDBを落とす(stopを含む)
- ps  
    起動中のDBを表示
## docker(単体)
- ps(prosess)  
    起動中のDB一覧の表示
- images  
    DBを起動した際に使用したイメージの一覧を表示する 
    -qでimage idのみを表示できる
    (mysqlなど)
- rmi(removeImages)
    imagesで表示されたimage idを指定して削除する  
    `docker images -q`で全てのイメージを指定できる  
- builder prune
    DBを起動した際に使用したすべてのビルドを削除する
