# lantern
## Use

	docker run -itd --restart=always --name lantern -p 3128:3128 lihaixin/lantern
	
## 开机启动，每次都是干净的，防止800M流量后限速

	docker run --rm --name lantern -p 3128:3128 lihaixin/lantern > ~/lantern.log 2>~/lantern.error

