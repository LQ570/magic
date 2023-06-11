<div align=center><img src='https://s1.ax1x.com/2023/06/12/pCZ3N2F.jpg'></img></div>
<h2>安装说明</h2>
<p>选择您需要绑定的服务空间</p>
<p>部署完成后点击“继续导入到hbuilderx”</p>
<p>新建壁纸小程序项目（选择uniapp类型）</p>
<p>右击unicloud文件，关联你刚才绑定的服务空间</p>
<p>关联好服务空间点击Cloudfunctions上传云函数</p>
<p>初始化database/db_init.json 数据表！</p>
<p>进入服务空间，云数据库，找到 wx_config表单，填写你小程序的appid和密钥</p>
<p>然后用微信开发者工具打开 "前端模板" 全局搜索 "空间名字"替换成你的空间名字</p>
<p>搜索 "空间id" 替换成你的 id 搜索 "空间密钥" 替换成你的服务空间密钥</p>
<p>在开发者工具里先登录小程序，进入云服务空间数据库，点击数据表 wx_user，找到您的用户信息，点击编辑管理，添加 "system": 1, 保存。（这是设置成管理员，刷新一下小程序就能看到后台了）</p>
<p>注：hb上传云函数初始化数据库时 打开 uniCloud/cloudfunctions/place_order/place_order.param.json 把userId改成你自己的用户id 然后右击 place_order 上传部署</p>
<h2>内容介绍</h2>
<div align=center><img src='https://s1.ax1x.com/2023/06/10/pCEvNxs.jpg'></img></div>
<h2>联系客服</h2>
<h5>联系QQ：994872452 微信：hello91966</h5>
<h2>常见问题</h2>
<h5>小程序本地可以打开，真机测试就转圈无法访问</h5>
<p>开发者工具可以不校验合法域名，该问题是因为您没有在小程序宿主平台填写合法域名导致</p>