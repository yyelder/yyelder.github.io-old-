<blockquote>
<p>参考<a href="https://blog.csdn.net/u012513463/article/details/123679206">docker</a></p>
<p>参考<a href="https://www.vediotalk.com/?p=4184">nps教程</a></p>
</blockquote>
<p>‍</p>
<p>问题</p>
<pre><code class="language-c">出现问题，这个地方
http_proxy_ip=0.0.0.0
http_proxy_port=8888
https_proxy_port=443
https_just_proxy=true
</code></pre>
<h2>服务端运行</h2>
<pre><code class="language-c">docker run -d --name=nps --restart=always --net=host -v /home/nps/conf:/conf ffdfgdfg/nps
</code></pre>
<h2>客户端运行</h2>
<pre><code class="language-c">nohup ./npc -server=124.220.55.6:8024 -vkey=123465 -type=tcp &gt; errorLog.txt 2&gt;&amp;1 &amp;
</code></pre>
<p>‍</p>
