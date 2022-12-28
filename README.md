# V2ray for Doprax
Create By ifeng<br>
Web Site: https://www.hicairo.com <br>
Telegram: https://t.me/HiaiFeng <br>

# 简介：
本项目用于在 Doprax.com 免费服务上部署 V2ray ，采用的方案为 Nginx + WebSocket + VMess/VLess + TLS。速度与 Replit 相比较慢，但是官方宣传不限流量，服务启动后永不停机。
# 注意事项：
<b>请勿滥用，账号封禁风险自负。</b>
# 部署：
<p>1、登录自己的 GitHub 账号后 Fork 该项目。</p>
<p>2、注册 <a href="https://www.doprax.com/signup/">Doprax.com</a> 账号登录后 Import 该项目。</p>
<p>详细使用方案请参考：https://replit.com/@hifeng/v2rayN?v=1</p>

# 使用方法：
<p>点击顶部的"Run"按钮后，左侧Files菜单中，程序自动创建url.txt文件，该文件包含VMess和VLess协议的链接地址，在客户端软件中导入即可。</p>
<p>同时，程序自动创建了VLess.png和VMess.png文件，分别是VLess和VMess协议的二维码，使用手机扫描即可添加节点。</p>

<p><b>更换节点中的UUID（用户ID）：</b></p>
<p>1、点击左侧Tools菜单中的Shell按钮，打开Shell窗口，运行create_UUID.sh脚本，程序会在左侧Files菜单中，创建uuid.txt文件，该文件中包含有新生成的UUID。</p>
<p>2、重启应用后生效，同时新生成的节点链接包含在url.txt文件中。</p>
<p>3、也可以使用第三方工具（ https://www.v2fly.org/awesome/tools.html ）生成UUID，然后手动打开uuid.txt文件，替换文件中的内容。</p>

<p><b>特别提醒：</b></p>
<p>服务启动，copy节点信息后，请手动删除url.txt、uuid.txt、VLess.png及VMess.png文件。否则，你的节点任何人都可以使用。</p>

# 反馈与交流：
在使用过程中，如果遇到问题，请使用Telegram与我联系。（ https://t.me/HiaiFeng ）