# LND-forward-event-notification-by-node-red

ラズパイUmbrelにLNDとnode-redを入れること前提。
さらにこのパッケージもいれること。https://www.npmjs.com/package/node-red-contrib-custom-websocket/v/0.2.0

node-redはUmrelアプリストアのものでもいいし、Umbrel OSに直にいれてもよい。

Umbrelのnode-redを使う場合はNode-RED (Bitcoin)を選ぶ。

マカロンのダンプはLightning Nodeのconnect walletで表示されるmacaroonをコピペ。このmacaroonはadmin.macaroonなので注意。adminがイヤなら/lnd/data/chain/bitcoin/mainnetにあるrouter.macaroonをxxdでダンプしろ


