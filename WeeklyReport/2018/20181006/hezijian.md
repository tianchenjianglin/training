#20181007

决定还是来补一补上周的和今天的事

### Oct 1
说好的不敲代码，不写bug 摸鱼一天的，结果还是把dns 从 dnspod 迁移到了 cloudxns， 他家提供了免费的线路细分，能作为一部分CDN调度来使用， 在dnspref上的测速表现也还可以（相对于国内其他厂商），然后使用 [acme.sh](https://acme.sh) 这个脚本给自己的一些域名签发证书。

### Oct 7
写了一早上的bug， 只是为了解决 acme.sh 签发证书后同步到CDN 的问题，腾讯云的API 比较难用，踩了几个坑。下午在国外部署了 ipv6 反代，至此 [boxjan.com](https://boxjan.com) 提供双栈服务，腾讯云服务器不提供IPv6， 阿里云呢 视金钱如上帝，只能在国外部署了，然后同时还部署了一台镜像CDN在美国，用以就近提供服务，回头想在英国和日本各部署一台。回头把这个整理到博客上

周五又要跑出去玩了~~~