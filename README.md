# LND-forward-event-notification-by-node-red

ここを見よ。
https://spotlight.soy/detail?article_id=4r19rsg93

ラズパイUmbrelにLNDとnode-redを入れること前提。

さらにこのパッケージもいれること。https://www.npmjs.com/package/node-red-contrib-custom-websocket/v/0.2.0

node-redはUmrelアプリストアのものでもいいし、Umbrel OSに直にいれてもよい。ただしUmbrelのnode-redを使う場合はNode-RED (Bitcoin)を選べ。

マカロンのダンプはLightning Nodeのconnect walletで表示されるmacaroonをコピペ。このmacaroonはadmin.macaroonなので注意。adminがイヤなら/lnd/data/chain/bitcoin/mainnetにあるrouter.macaroonをxxdでダンプしろ


