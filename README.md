# 前期准备

## 安装python
1.安装前查看当前系统下的python版本号

python -V

2.获取python3.x的官方软件包

`wget https://www.python.org/ftp/python/3.6.5/Python-3.6.5.tgz`

3.解压缩该软件包

tar -zxvf Python-3.6.5.tgz

4.在解压目录下安装配置

`cd Python-3.6.5`

`./configure`

5.编译并安装

`make`

`make install`

6.验证当前系统下安装的python版本号

`python3 -V`

## 安装pip
1.用脚本安装pip<br>
`curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`<br>
`python get-pip.py`   #会看到Successfully.....等安装成功的字样<br>

2.yum安装pip<br>
2.1 首先安装拓展源<br>

`yum -y install epel-release`<br>
2.2安装pip<br>

`yum -y install python-pip`

# 7.0.2版本（适用内存足的服务器）

<h1>脚本简介</h1>
<div>
<p>本次面板版本：7.0.2<br>本脚本支持一键安装开心版宝塔面板 以及 已经安装宝塔面板升级开心版！<br>
感谢大家使用该脚本，本脚本未加密，有没有后门大家自己看就知道了，仅仅将书记的脚本本地化了，未经任何修改，请放心使用！<br>
本次脚本支持：Centos 7、Debian、Ubuntu！<br>
</p>
</div>
</div>
<div>
<h2>脚本特点</h2>
<div>
<blockquote>
<p>
1. 优化了防火墙安装失败问题！<br>
2. 优化了脚本无法安装面板，不兼容centos8问题！<br>
3. 面板升级为7.0.2！！<br>
4. 修复了若干已知BUG！<br>

</p></blockquote>
</div>
</div>
<div>
<h2>面板日志</h2>
<div>
<blockquote>
<p>
1、修正一处面板被某些恶意攻击而导致的面板不稳定问题<br>
2、调整CPU信息显示格式<br>
3、修正Ubuntu下计划任务失效问题<br>
4、修正Ubuntu下文件重命名误操作导致的文件覆盖问题<br>
5、优化面板加载逻辑，启动速度提升3倍<br>
6、优化数据加密模块兼容性<br>
7、优化网站/数据库/FTP的搜索功能<br>
8、修正开启目录保护后指定目录无法运行PHP的问题<br>
9、重构【宝塔终端】模块<br>
10、增加PHP-FPM日志清理机制<br>
11、其它细节调整<br>
注意：本次更新为紧急可靠性更新，建议所有用户更新<br>
</p></blockquote>
</div>
</div>
<div>
<h2>升级方法（已安装宝塔 7.0.2 免费面板）</h2>
<div>
1.大家之前安装了 6X 开心版宝塔的 直接 输入 bt命令 选择 0或者18 升到最新 7.0.2 开心版 或者 输入：<code>curl https://52bt.cn/install/update6.sh|bash</code><br><br>
2.如果 你是免费的 6.x 宝塔面板 可以使用脚本 升到最新的开心版 7.0.2 面板 或者 输入：<code>curl https://52bt.cn/install/update6.sh|bash</code><br>
<br>


<p></p>
</div>
</div>
<div>
<h2>脚本拉黑去除</h2>
<div>
Centos -1 拉黑解决<code>yum -y install e2fsprogs && wget -O ovo.sh https://52bt.cn/install/ovo.sh && bash ovo.sh</code><br><br>
Ubuntu/Debian -1 拉黑解决<code>apt-get install e2fsprogs && wget -O ovo.sh https://52bt.cn/install/ovo.sh && bash ovo.sh</code><br>
<br>


<p></p>
</div>
</div>
<div>
<h2>安装 7.0.2 面板</h2>
<div>
<h4>5合1 安装命令（宝塔 7.0.2 开心版面板）：<span>Ubuntu/Debian需安装<code>apt-get install wget</code> <code>apt-get install e2fsprogs</code></span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>yum -y install wget &amp;&amp; yum -y install e2fsprogs &amp;&amp; wget https://52bt.cn/install/diyu.sh &amp;&amp; bash diyu.sh</code></strong>
</pre></div></div>
</div>
</div>
<div>
<h4>Bt_Panel_Pro 腳本（Centos）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>yum -y install wget;wget https://52bt.cn/install/install_6.0.sh &amp;&amp; bash install_6.0.sh</code></strong>
</pre></div></div>
</div>
</div>

<div>
<div>
<h4>Bt_Panel_Pro 腳本（Centos/Ubuntu/Debian支持ipv6）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>curl -sSO https://52bt.cn/install/new_install.sh &amp;&amp; bash new_install.sh</code></strong>
</pre></div></div>
</div>
</div>


<div>
<div>
<h4>Bt_Panel_Pro 腳本（Ubuntu）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O install.sh https://52bt.cn/install/install-ubuntu_6.0.sh &amp;&amp; sudo bash install.sh</code></strong>
</pre></div></div>
</div>
</div>


<div>
<div>
<h4>Bt_Panel_Pro 腳本（Debian）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O install.sh https://52bt.cn/install/install-ubuntu_6.0.sh &amp;&amp; bash install.sh</code></strong>
</pre></div></div>
</div>
</div>

<div>
<div>
<h4>Bt_Panel_Pro 腳本（Fedora）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O install.sh https://52bt.cn/install/install_6.0.sh &amp;&amp; bash install.sh</code></strong>
</pre></div></div>
</div>
</div>



<h2>已经安装面板</h2>   
<div> 
<div>
<h4>Bt_Panel 脚本（升级开心版）：<span>极速安装方式  (安装时间1至10秒)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>curl https://52bt.cn/install/update6.sh|bash</code></strong>
</pre></div></div>
</div>
</div> 
  
 
<h2>Nginx防火墙脚本</h2>   
<div> 
<div>
<h4>Bt_Panel 防火墙脚本（一定要安装好Nginx环境）：<span><br>防火墙需要面板先安装，然后在使用脚本安装防火墙，请勿在面板升级防火墙！（请勿面板私自升级防火墙，否则无法使用！）</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget https://52bt.cn/install/btwaf.sh && bash btwaf.sh</code></strong>
</pre></div></div>
</div>
</div>  


<h2>Apache防火墙脚本</h2>   
<div> 
<div>
<h4>注意：防火墙需要面板先安装，然后在使用脚本安装防火墙，请勿在面板升级防火墙！（请勿面板私自升级防火墙，否则无法使用！） </span></h4>
<h4>注意：该版本是书记之前发布的最后一个版本，虽然很老旧，但是依然可以使用，欢迎大家提供Apache 7.2 - 6.9版本防火墙的文件！ </span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget https://52bt.cn/install/btwaf_httpd.sh && bash btwaf_httpd.sh</code></strong>
</pre></div></div>
</div>
</div> 

<h2>宝塔同步工具</h2>   
<div> 
<div>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>安装此插件打开可能会报错，需要重启面板就可以正常使用！</code></strong>
</pre></div></div>
</div>
</div>  

<h2>第三方插件免费脚本</h2>   
<div> 
<div>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O plugin3.sh https://52bt.cn/install/plugin3.sh && bash plugin3.sh</code></strong>
</pre></div></div>
</div>
</div>  

<div>
<div>
<h4>不想使用開心版的，直接使用官方腳本轉成免費</h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O update.sh http://download.bt.cn/install/update.sh &amp;&amp; bash update.sh free</code></strong>
</pre></div></div>
</div>
</div>

<div>

</div>
</div>

</section>

## 5.9.1（适用小机器）


<h1>脚本简介</h1>
<div>
<p>本次面板版本：5.9.1<br>本脚本支持一键安装开心版宝塔面板 以及 已经安装宝塔面板升级开心版！<br>
感谢大家使用该脚本，本脚本未加密，有没有后门大家自己看就知道了，仅仅将书记的脚本本地化了，未经任何修改，请放心使用！<br>
本次脚本支持：Centos 7、Debian、Ubuntu！<br>
</p>
</div>
</div>
<div>
<h2>脚本特点</h2>
<div>
<blockquote>
<p>
1. 本次脚本 放在 腾讯3m香港小鸡上，速度会很慢，大家耐心等待。。。 如果还出现 问题 把服务器 dns 改成 8.8.8.8 8.8.4.4 怎么改 谷歌！<br>
2. 杜绝盗取本脚本 非法出事 请大家使用 开心版的同时 支持正版！<br>
3. 允许转载本脚本、需留下出处！<br>
4. 为了安全考虑，面板端口已经由 8888 改 8899 若无法打开面板，请放行8899端口！<br>
5. 插件直接面板安装即可用！<br>
</p></blockquote>
</div>
</div>
<div>
<h2>面板日志</h2>
<div>
<blockquote>
<p>
1、优化验证码模块，增强可辨识度<br>
2、优化面板加载逻辑，提升面板响应速度<br>
3、修正部分服务器因升级Openssl之后导致面板异常的问题<br>
4、修正部分地区无法正常绑定小程序的问题<br>
</p></blockquote>
</div>
</div>
<div>
<h2>更新技巧</h2>
<div>
1.如果 你是免费的 5.x 宝塔面板 可以使用脚本 升到最新的开心版 5.9.1 面板（或者输入：<code>curl https://52bt.cn/install/update_pro.sh|bash</code>）！<br>
<br>
结束：该版本 完美破解版，无任何bug～！别打脸～！

<p></p>
</div>
</div>
<div>
<h2>安装 5.9.1 面板</h2>
<div>
<h4>Bt_Panel_Pro 腳本（Centos）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>yum install -y wget &amp;&amp; wget -O install.sh https://52bt.cn/install/install.sh &amp;&amp; sh install.sh</code></strong>
</pre></div></div>
</div>
</div>


<div>
<div>
<h4>Bt_Panel_Pro 腳本（Ubuntu）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O install.sh https://52bt.cn/install/install-ubuntu.sh &amp;&amp; sudo bash install.sh</code></strong>
</pre></div></div>
</div>
</div>


<div>
<div>
<h4>Bt_Panel_Pro 腳本（Debian）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O install.sh https://52bt.cn/install/install-ubuntu.sh &amp;&amp; bash install.sh</code></strong>
</pre></div></div>
</div>
</div>


<div>
<div>
<h4>Bt_Panel_Pro 腳本（Fedora）：<span>极速安装方式  (安装时间1至10分钟)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O install.sh https://52bt.cn/install/install.sh &amp;&amp; bash install.sh</code></strong>
</pre></div></div>
</div>
</div>


<h2>已经安装面板</h2>   
<div> 
<div>
<h4>Bt_Panel 脚本（升级开心版）：<span>极速安装方式  (安装时间1至10秒)</span></h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>curl https://52bt.cn/install/update_pro.sh|bash</code></strong>
</pre></div></div>
</div>
</div> 
  


<div>
<div>
<h4>不想使用開心版的，直接使用官方腳本轉成免費</h4>
<div class="highlighter-rouge"><div class="highlight"><pre class="highlight"><strong><code>wget -O update.sh http://download.bt.cn/install/update.sh &amp;&amp; bash update.sh free</code></strong>
</pre></div></div>
</div>
</div>

<div>


</div>
</div>

</section>

<p class="has-text-color has-text-align-center has-medium-font-size has-vivid-red-color">5.9.2适合低配置，小内存机器！如果机器配置足够还是推荐安装最新的破解版！最新的破解版在网站右上角！</p><h2>安装要求</h2><p>Python版本： 2.6/2.7（安装宝塔时会自动安装）<br>内存：128M以上，推荐512M以上（纯面板约占系统10M内存）<br>硬盘：100M以上可用硬盘空间（纯面板约占20M磁盘空间）<br>系统：CentOS 6.x / 7.x (Ubuntu、Debian、Fedora 请点这里)，<br>确保是干净的操作系统，不支持32位系统，没有安装过其它环境带的Apache/Nginx/php/MySQL（已有环境不可安装）<br><br><br></p><h2><strong>宝塔面板 5.9.2 安装命令</strong>&nbsp;New端口：3888</h2><p><strong>Centos安装命令：</strong></p><pre class="wp-block-code"><code>yum install -y wget &amp;&amp; wget -O install.sh https://download.ccspump.com/install/install.sh &amp;&amp; sh install.sh</code></pre><p><strong>Ubuntu/Deepin安装命令：</strong></p><pre class="wp-block-code"><code>wget -O install.sh https://download.ccspump.com/install/install-ubuntu.sh &amp;&amp; sudo bash install.sh</code></pre><p><strong>Debian安装命令：</strong></p><pre class="wp-block-code"><code>wget -O install.sh https://download.ccspump.com/install/install-ubuntu.sh &amp;&amp; bash install.sh</code></pre><p><strong>Fedora安装命令：</strong></p><pre class="wp-block-code"><code>wget -O install.sh https://download.ccspump.com/install/install.sh &amp;&amp; bash install.sh</code></pre><p><strong>更新命令：</strong></p><pre class="wp-block-code"><code>curl https://download.ccspump.com/install/update.sh|bash</code></pre><h2>免费版升级专业版</h2><p><strong>升级专业版脚本：</strong></p><pre class="wp-block-code"><code>wget -O update_pro.sh https://download.ccspump.com/install/update_pro.sh &amp;&amp; bash update_pro.sh</code></pre></article><div class="post-actions"> <a href="javascript:;" etap="like" class="post-like action action-like" data-pid="558"><i class="fa fa-thumbs-o-up"></i>

<h2><strong>宝塔面板 7.2.0 安装命令</strong>&nbsp;New端口：8088</h2><p><strong>Centos安装命令：</strong></p><pre class="wp-block-code"><code>yum install -y wget &amp;&amp; wget -O install.sh https://download.ccspump.com/install/install_6.0.sh &amp;&amp; sh install.sh</code></pre><p><strong>试验性Centos/Ubuntu/Debian安装命令 独立运行环境（py3.7） 可能存在少量兼容性问题 不断优化中</strong></p><pre class="wp-block-code"><code>curl -sSO https://download.ccspump.com/install/install_panel.sh &amp;&amp; bash install_panel.sh</code></pre><p><strong>Ubuntu/Deepin安装命令：</strong></p><pre class="wp-block-code"><code>wget -O install.sh https://download.ccspump.com/install/install-ubuntu_6.0.sh &amp;&amp; sudo bash install.sh</code></pre><p><strong>Debian安装命令：</strong></p><pre class="wp-block-code"><code>wget -O install.sh https://download.ccspump.com/install/install-ubuntu_6.0.sh &amp;&amp; bash install.sh</code></pre><p><strong>Fedora安装命令：</strong></p><pre class="wp-block-code"><code>wget -O install.sh https://download.ccspump.com/install/install_6.0.sh &amp;&amp; bash install.sh</code></pre><p><strong>Linux面板7.2.0升级命令：</strong></p><pre class="wp-block-code"><code>curl https://download.ccspump.com/install/update6.sh|bash</code></pre><h2><strong>插件相关脚本</strong></h2><p><strong>收费Nginx防火墙（面板先安装在执行脚本）：</strong></p><pre class="wp-block-code"><code>wget -O btwaf.sh https://download.ccspump.com/install/btwaf.sh &amp;&amp; bash btwaf.sh install</code></pre><p><strong>免费Nginx防火墙（无需面板安装）：</strong></p><pre class="wp-block-code"><code>wget -O free_btwaf.sh https://download.ccspump.com/install/free_btwaf.sh &amp;&amp; bash free_btwaf.sh install</code></pre><p><strong>收费Apache防火墙（面板先安装在执行脚本）：</strong></p><pre class="wp-block-code"><code>wget -O btwaf_httpd.sh https://download.ccspump.com/install/btwaf_httpd.sh &amp;&amp; bash btwaf_httpd.sh install</code></pre><p><strong>主机异常登录插件脚本</strong></p><pre class="wp-block-code"><code>wget -O host_login.sh https://download.ccspump.com/install/host_login.sh &amp;&amp; bash host_login.sh install</code></pre><p><strong>河马webshell查杀插件脚本</strong></p><pre class="wp-block-code"><code>wget -O hm_shell_san.sh https://download.ccspump.com/install/hm_shell_san.sh &amp;&amp; bash hm_shell_san.sh install</code></pre><h2><strong>修复工具</strong></h2><p><strong>解除拉黑、解锁文件脚本：</strong></p><pre class="wp-block-code"><code>wget -O waf.sh https://download.ccspump.com/install/waf.sh &amp;&amp; bash waf.sh</code></pre></article></div></div>
