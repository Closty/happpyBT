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

