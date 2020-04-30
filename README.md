## 更新安装脚本测试版本
脚本不再从github拉取docker-compose.yml,而是自己生成，添加自定义镜像，默认是我提供的升级版镜像

## 增加自定义DNS，增加数据库连接
在脚本中选择即可，测试通过

## 支持对接SSRPanel
欢迎测试

教程写在了wiki里

目前实现功能有流量记录、服务器是否在线、在线人数,在线ip上报、负载、中转，后端根据前端的设定自动调用 API 增加用户，限速，审计，限制ip。

使用方法：

```
mkdir v2ray-agent  &&  \
cd v2ray-agent && \
curl https://raw.githubusercontent.com/amfiyong/v2ray-sspanel-v3-mod_Uim-plugin/dev/install.sh -o install.sh && \
chmod +x install.sh && \
bash install.sh
```



感恩原作者rico辛苦付出
和hulisang大佬的维护
caddy镜像更新支持tls1.3


