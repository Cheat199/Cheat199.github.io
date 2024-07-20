阿里云近期发布[公告](https://help.aliyun.com/zh/dns/public-dns-free-version-access-speed-limit-notification)，将于2024年9月30日24时起对公共 DNS 中免费的解析请求采取**智能流量管控措施**。阿里云称，免费版服务适用于个人终端低并发使用，如流量过高，如 DoH / DoT 单 IP 访问量超过 20QPS，UDP / TCP 流量超过 2000bps，将会触发**限速策略**。个人用户也可以接入付费版服务，付费版产品每月提供 1000 万次的免费 HTTP 解析流量资源包，可基本满足个人和小型企业使用场景。

本次变动涉及云解析中的递归DNS（公共DNS）产品，根据阿里云[文档](https://help.aliyun.com/zh/dns/pricing-overview)，超过免费额度后按0.04元/万次HTTP解析计费，HTTPS（含DoH/DoT）按 5倍 HTTP流量进行计费。用户也可以提前购买流量包，1000万次的流量包价格为30元。

**个人认为**主要影响用户应该就是使用DoH查询DNS的用户，TCP/UDP限速2000bps，个人使用没啥影响，主要影响的可能是企业。

最后啰嗦一句免费好用的东西越来越少了，**且用且珍惜吧**。


**相关图片：**
<img width="610" alt="1" src="https://github.com/user-attachments/assets/d2ba493e-43f2-4e73-81f9-c004f54567e9">
