### 监控后台部署教程

node版本号： 10.6.0  (node安装教程自行搜索)

mysql版本号. 5.6.45  (mysql 安装教程自行搜索)

  1. 下载或者克隆代码到本地

  2. 在项目根目录下，进入 config/db.js ，配置mysql数据库的连接配置

  3. 配置完成后， 在根目录下执行命令$: npm run start, 本地服务完成启动。

  4. 如需启动生产服务，需安装PM2, 然后运行命令$: npm run prd, 即可启动生产服务。
