## 用法：

	docker run --net=host -d --restart=always --name ntopng -p 3000:3000 vank3f3/ntopng -i eth0

	docker run --net=host -d --restart=always --name ntopng -p 3000:3000 vank3f3/ntopng



第一种方法：监控指定的网卡，第二种方法，监控所有的网卡