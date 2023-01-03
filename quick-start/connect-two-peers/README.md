node  quick-start/connect-two-peers/server.mjs
node quick-start/connect-two-peers/client.mjs 0e952ed9b498d2b3dccddada28b7233ce4147ca972890290021e9f9fe8d84ba9
server.mjs tạo cặp key, dùng pub key trong console để khơi tạo client.mjs kết nối vào server.mjs
Client và Server kết nối qua DHT table, chỉ cần biết pubkey chúng có thể kết nối với nhau, trong trường hợp 
các peer randomizing NATs, có thể cần relay để kết nối giữa các peers, bản thân peer đã kết nối cũng
có thể trở thành một relay