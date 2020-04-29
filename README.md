## 更新安装脚本测试版本
脚本不再从github拉取docker-compose.yml,而是自己生成，添加自定义镜像，默认是我提供的升级版镜像
## 更新镜像（测试）
升级核心,原镜像hulisang/v2ray_v3:go还可以使用

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
path极力不推荐使用/v2ray了（大家懂的）



感恩原作者rico辛苦付出
本人仅做备份和后续维护
caddy镜像更新支持tls1.3

## 免责声明

本程序仅供学习了解, 请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源

使用本程序必循遵守部署服务器所在地、所在国家和用户所在国家的法律法规, 程序作者不对使用者任何不当行为负责
