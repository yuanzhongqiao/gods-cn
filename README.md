<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><a href="https://godoc.org/github.com/emirpasic/gods" rel="nofollow"><img src="https://camo.githubusercontent.com/d44a2141fcea4a88fb38d252a03b133774b6aba7515ddf9972d8fd41af4da60a/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f656d697270617369632f676f64733f7374617475732e737667" alt="戈多克" data-canonical-src="https://godoc.org/github.com/emirpasic/gods?status.svg" style="max-width: 100%;"></a>
<a href="https://circleci.com/gh/emirpasic/gods?branch=master" rel="nofollow"><img src="https://camo.githubusercontent.com/22092a2f1e1a434149f1edda1768418a51150ce3411b1962d430341d7bbbb7b3/68747470733a2f2f636972636c6563692e636f6d2f67682f656d697270617369632f676f64732f747265652f6d61737465722e7376673f7374796c653d736869656c64" alt="构建状态" data-canonical-src="https://circleci.com/gh/emirpasic/gods/tree/master.svg?style=shield" style="max-width: 100%;"></a>
<a href="https://goreportcard.com/report/github.com/emirpasic/gods" rel="nofollow"><img src="https://camo.githubusercontent.com/a43e7b995803648eaf559555119f411e183f991574529dd5889939d05b9fdf90/68747470733a2f2f676f7265706f7274636172642e636f6d2f62616467652f6769746875622e636f6d2f656d697270617369632f676f6473" alt="去报告卡" data-canonical-src="https://goreportcard.com/badge/github.com/emirpasic/gods" style="max-width: 100%;"></a>
<a href="https://codecov.io/gh/emirpasic/gods" rel="nofollow"><img src="https://camo.githubusercontent.com/121b54060522715e72161cc0efa6e5ebcb5ebcc539a94d8bbc0be172b11bb1e2/68747470733a2f2f636f6465636f762e696f2f67682f656d697270617369632f676f64732f6272616e63682f6d61737465722f67726170682f62616467652e737667" alt="代码科夫" data-canonical-src="https://codecov.io/gh/emirpasic/gods/branch/master/graph/badge.svg" style="max-width: 100%;"></a>
<a href="https://sourcegraph.com/github.com/emirpasic/gods?badge" rel="nofollow"><img src="https://camo.githubusercontent.com/e29e0e2175c4a92b340745a0f37bef91ac2c29cd5ae20b0903a840360552280e/68747470733a2f2f736f7572636567726170682e636f6d2f6769746875622e636f6d2f656d697270617369632f676f64732f2d2f62616467652e737667" alt="源图" data-canonical-src="https://sourcegraph.com/github.com/emirpasic/gods/-/badge.svg" style="max-width: 100%;"></a>
<a href="https://github.com/emirpasic/gods/releases"><img src="https://camo.githubusercontent.com/04fc55513530c39dd2a907c166e831fa0b95f7e6f711ca0d8193206e08f789c3/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f72656c656173652f656d697270617369632f676f64732e7376673f7374796c653d666c61742d737175617265" alt="发布" data-canonical-src="https://img.shields.io/github/release/emirpasic/gods.svg?style=flat-square" style="max-width: 100%;"></a>
<a href="https://sonarcloud.io/summary/new_code?id=gods" rel="nofollow"><img src="https://camo.githubusercontent.com/76385b5aad66d3e3dc4160d495832ffbbbca1b225c166f8b07bcba78cd2b1d87/68747470733a2f2f736f6e6172636c6f75642e696f2f6170692f70726f6a6563745f6261646765732f6d6561737572653f70726f6a6563743d676f6473266d65747269633d616c6572745f737461747573" alt="质量门状态" data-canonical-src="https://sonarcloud.io/api/project_badges/measure?project=gods&amp;metric=alert_status" style="max-width: 100%;"></a>
<a href="https://github.com/emirpasic/gods/blob/master/LICENSE"><img src="https://camo.githubusercontent.com/96ef2820404c33a84e646ca0d54fe5f85af0ff43f0564420e88ef78f777f2ba1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4253445f322d2d436c617573652d677265656e2e737667" alt="皮伊" data-canonical-src="https://img.shields.io/badge/License-BSD_2--Clause-green.svg" style="max-width: 100%;"></a></p>
<h1 tabindex="-1" dir="auto"><a id="user-content-gods-go-data-structures" class="anchor" aria-hidden="true" tabindex="-1" href="#gods-go-data-structures"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GoDS（Go 数据结构）</font></font></h1>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Go中各种数据结构和算法的实现。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-data-structures" class="anchor" aria-hidden="true" tabindex="-1" href="#data-structures"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据结构</font></font></h2>
<ul dir="auto">
<li><a href="#containers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集装箱</font></font></a>
<ul dir="auto">
<li><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表</font></font></a>
<ul dir="auto">
<li><a href="#arraylist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组列表</font></font></a></li>
<li><a href="#singlylinkedlist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单链表</font></font></a></li>
<li><a href="#doublylinkedlist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">双向链表</font></font></a></li>
</ul>
</li>
<li><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套</font></font></a>
<ul dir="auto">
<li><a href="#hashset"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希集</font></font></a></li>
<li><a href="#treeset"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树集</font></font></a></li>
<li><a href="#linkedhashset"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接哈希集</font></font></a></li>
</ul>
</li>
<li><a href="#stacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆栈</font></font></a>
<ul dir="auto">
<li><a href="#linkedliststack"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链表栈</font></font></a></li>
<li><a href="#arraystack"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组栈</font></font></a></li>
</ul>
</li>
<li><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地图</font></font></a>
<ul dir="auto">
<li><a href="#hashmap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希映射</font></font></a></li>
<li><a href="#treemap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树形图</font></font></a></li>
<li><a href="#linkedhashmap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接哈希映射</font></font></a></li>
<li><a href="#hashbidimap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希比迪映射</font></font></a></li>
<li><a href="#treebidimap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树比迪地图</font></font></a></li>
</ul>
</li>
<li><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树木</font></font></a>
<ul dir="auto">
<li><a href="#redblacktree"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红黑树</font></font></a></li>
<li><a href="#avltree"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AVL树</font></font></a></li>
<li><a href="#btree"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B树</font></font></a></li>
<li><a href="#binaryheap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二叉堆</font></font></a></li>
</ul>
</li>
<li><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">队列</font></font></a>
<ul dir="auto">
<li><a href="#linkedlistqueue"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链表队列</font></font></a></li>
<li><a href="#arrayqueue"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组队列</font></font></a></li>
<li><a href="#circularbuffer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">循环缓冲区</font></font></a></li>
<li><a href="#priorityqueue"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优先队列</font></font></a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#functions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能</font></font></a>
<ul dir="auto">
<li><a href="#comparator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比较器</font></font></a></li>
<li><a href="#iterator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迭代器</font></font></a>
<ul dir="auto">
<li><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带索引的迭代器</font></font></a></li>
<li><a href="#iteratorwithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带键迭代器</font></font></a></li>
<li><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带索引的反向迭代器</font></font></a></li>
<li><a href="#reverseiteratorwithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带键的反向迭代器</font></font></a></li>
</ul>
</li>
<li><a href="#enumerable"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可枚举</font></font></a>
<ul dir="auto">
<li><a href="#enumerablewithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带索引的枚举</font></font></a></li>
<li><a href="#enumerablewithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带键枚举</font></font></a></li>
</ul>
</li>
<li><a href="#serialization"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">序列化</font></font></a>
<ul dir="auto">
<li><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSON序列化器</font></font></a></li>
<li><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSON反序列化器</font></font></a></li>
</ul>
</li>
<li><a href="#sort"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">种类</font></font></a></li>
<li><a href="#container"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></a></li>
</ul>
</li>
<li><a href="#appendix"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附录</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-containers" class="anchor" aria-hidden="true" tabindex="-1" href="#containers"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集装箱</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有数据结构都通过以下方法实现容器接口：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">Container</span> <span class="pl-k">interface</span> {
	<span class="pl-c1">Empty</span>() <span class="pl-smi">bool</span>
	<span class="pl-c1">Size</span>() <span class="pl-smi">int</span>
	<span class="pl-c1">Clear</span>()
	<span class="pl-c1">Values</span>() []<span class="pl-k">interface</span>{}
	<span class="pl-c1">String</span>() <span class="pl-smi">string</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type Container interface {
	Empty() bool
	Size() int
	Clear()
	Values() []interface{}
	String() string
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器可以是有序的，也可以是无序的。</font><font style="vertical-align: inherit;">所有有序容器都提供</font></font><a href="#iterator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有状态迭代器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其中一些允许可</font></font><a href="#enumerable"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">枚举函数</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<table>
<thead>
<tr>
<th align="left"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数据</font></font></strong></th>
<th align="left"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">结构</font></font></strong></th>
<th align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已订购</font></font></strong></th>
<th align="center"><strong><a href="#iterator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迭代器</font></font></a></strong></th>
<th align="center"><strong><a href="#enumerable"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可枚举</font></font></a></strong></th>
<th align="center"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用者</font></font></strong></th>
</tr>
</thead>
<tbody>
<tr>
<td align="left"><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表</font></font></a></td>
<td align="left"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#arraylist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组列表</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#singlylinkedlist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单链表</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#doublylinkedlist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">双向链表</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套</font></font></a></td>
<td align="left"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#hashset"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希集</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#treeset"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树集</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#linkedhashset"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接哈希集</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"><a href="#stacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆栈</font></font></a></td>
<td align="left"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#linkedliststack"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链表栈</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#arraystack"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组栈</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地图</font></font></a></td>
<td align="left"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#hashmap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希映射</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#treemap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树形图</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#linkedhashmap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接哈希映射</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#hashbidimap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希比迪映射</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙*</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#treebidimap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树比迪地图</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙*</font></font></td>
</tr>
<tr>
<td align="left"><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树木</font></font></a></td>
<td align="left"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#redblacktree"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红黑树</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#avltree"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AVL树</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#btree"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B树</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">钥匙</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#binaryheap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二叉堆</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">队列</font></font></a></td>
<td align="left"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
<td align="center"></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#linkedlistqueue"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链表队列</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#arrayqueue"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组队列</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#circularbuffer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">循环缓冲区</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"><a href="#priorityqueue"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优先队列</font></font></a></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是的*</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不</font></font></td>
<td align="center"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指数</font></font></td>
</tr>
<tr>
<td align="left"></td>
<td align="left"></td>
<td align="center"></td>
<td align="center"><sub><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*可逆</font></font></sup></sub></td>
<td align="center"></td>
<td align="center"><sub><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*双向</font></font></sup></sub></td>
</tr>
</tbody>
</table>
<h3 tabindex="-1" dir="auto"><a id="user-content-lists" class="anchor" aria-hidden="true" tabindex="-1" href="#lists"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表是一种存储值并且可能具有重复值的数据结构。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#containers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">List</span> <span class="pl-k">interface</span> {
	<span class="pl-c1">Get</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>) (<span class="pl-k">interface</span>{}, <span class="pl-smi">bool</span>)
	<span class="pl-c1">Remove</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>)
	<span class="pl-c1">Add</span>(<span class="pl-s1">values</span> <span class="pl-c1">...</span><span class="pl-k">interface</span>{})
	<span class="pl-c1">Contains</span>(<span class="pl-s1">values</span> <span class="pl-c1">...</span><span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>
	<span class="pl-c1">Sort</span>(<span class="pl-s1">comparator</span> utils.<span class="pl-smi">Comparator</span>)
	<span class="pl-c1">Swap</span>(<span class="pl-s1">index1</span>, <span class="pl-s1">index2</span> <span class="pl-smi">int</span>)
	<span class="pl-c1">Insert</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">values</span> <span class="pl-c1">...</span><span class="pl-k">interface</span>{})
	<span class="pl-c1">Set</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{})

	containers.<span class="pl-smi">Container</span>
	<span class="pl-c">// Empty() bool</span>
	<span class="pl-c">// Size() int</span>
	<span class="pl-c">// Clear()</span>
	<span class="pl-c">// Values() []interface{}</span>
    <span class="pl-c">// String() string</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type List interface {
	Get(index int) (interface{}, bool)
	Remove(index int)
	Add(values ...interface{})
	Contains(values ...interface{}) bool
	Sort(comparator utils.Comparator)
	Swap(index1, index2 int)
	Insert(index int, values ...interface{})
	Set(index int, value interface{})

	containers.Container
	// Empty() bool
	// Size() int
	// Clear()
	// Values() []interface{}
    // String() string
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-arraylist" class="anchor" aria-hidden="true" tabindex="-1" href="#arraylist"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组列表</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由隐式增长和收缩的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动态数组支持的</font><font style="vertical-align: inherit;">列表。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">List</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"github.com/emirpasic/gods/lists/arraylist"</span>
	<span class="pl-s">"github.com/emirpasic/gods/utils"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">list</span> <span class="pl-c1">:=</span> <span class="pl-s1">arraylist</span>.<span class="pl-en">New</span>()
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"a"</span>)                         <span class="pl-c">// ["a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"c"</span>, <span class="pl-s">"b"</span>)                    <span class="pl-c">// ["a","c","b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Sort</span>(<span class="pl-s1">utils</span>.<span class="pl-c1">StringComparator</span>)     <span class="pl-c">// ["a","b","c"]</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Get</span>(<span class="pl-c1">0</span>)                    <span class="pl-c">// "a",true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Get</span>(<span class="pl-c1">100</span>)                  <span class="pl-c">// nil,false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Contains</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>)      <span class="pl-c">// true</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Contains</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>, <span class="pl-s">"d"</span>) <span class="pl-c">// false</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Swap</span>(<span class="pl-c1">0</span>, <span class="pl-c1">1</span>)                       <span class="pl-c">// ["b","a",c"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>)                        <span class="pl-c">// ["b","a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)                        <span class="pl-c">// ["b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">0</span>)                        <span class="pl-c">// []</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">0</span>)                        <span class="pl-c">// [] (ignored)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Empty</span>()                      <span class="pl-c">// true</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Size</span>()                       <span class="pl-c">// 0</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"a"</span>)                         <span class="pl-c">// ["a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Clear</span>()                          <span class="pl-c">// []</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Insert</span>(<span class="pl-c1">0</span>, <span class="pl-s">"b"</span>)                   <span class="pl-c">// ["b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Insert</span>(<span class="pl-c1">0</span>, <span class="pl-s">"a"</span>)                   <span class="pl-c">// ["a","b"]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;github.com/emirpasic/gods/lists/arraylist&quot;
	&quot;github.com/emirpasic/gods/utils&quot;
)

func main() {
	list := arraylist.New()
	list.Add(&quot;a&quot;)                         // [&quot;a&quot;]
	list.Add(&quot;c&quot;, &quot;b&quot;)                    // [&quot;a&quot;,&quot;c&quot;,&quot;b&quot;]
	list.Sort(utils.StringComparator)     // [&quot;a&quot;,&quot;b&quot;,&quot;c&quot;]
	_, _ = list.Get(0)                    // &quot;a&quot;,true
	_, _ = list.Get(100)                  // nil,false
	_ = list.Contains(&quot;a&quot;, &quot;b&quot;, &quot;c&quot;)      // true
	_ = list.Contains(&quot;a&quot;, &quot;b&quot;, &quot;c&quot;, &quot;d&quot;) // false
	list.Swap(0, 1)                       // [&quot;b&quot;,&quot;a&quot;,c&quot;]
	list.Remove(2)                        // [&quot;b&quot;,&quot;a&quot;]
	list.Remove(1)                        // [&quot;b&quot;]
	list.Remove(0)                        // []
	list.Remove(0)                        // [] (ignored)
	_ = list.Empty()                      // true
	_ = list.Size()                       // 0
	list.Add(&quot;a&quot;)                         // [&quot;a&quot;]
	list.Clear()                          // []
	list.Insert(0, &quot;b&quot;)                   // [&quot;b&quot;]
	list.Insert(0, &quot;a&quot;)                   // [&quot;a&quot;,&quot;b&quot;]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-singlylinkedlist" class="anchor" aria-hidden="true" tabindex="-1" href="#singlylinkedlist"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">单链表</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个</font></font><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其中每个元素都指向列表中的下一个元素。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">List</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	sll <span class="pl-s">"github.com/emirpasic/gods/lists/singlylinkedlist"</span>
	<span class="pl-s">"github.com/emirpasic/gods/utils"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">list</span> <span class="pl-c1">:=</span> <span class="pl-s1">sll</span>.<span class="pl-en">New</span>()
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"a"</span>)                         <span class="pl-c">// ["a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"c"</span>, <span class="pl-s">"b"</span>)                    <span class="pl-c">// ["a","c","b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Sort</span>(<span class="pl-s1">utils</span>.<span class="pl-c1">StringComparator</span>)     <span class="pl-c">// ["a","b","c"]</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Get</span>(<span class="pl-c1">0</span>)                    <span class="pl-c">// "a",true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Get</span>(<span class="pl-c1">100</span>)                  <span class="pl-c">// nil,false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Contains</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>)      <span class="pl-c">// true</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Contains</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>, <span class="pl-s">"d"</span>) <span class="pl-c">// false</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Swap</span>(<span class="pl-c1">0</span>, <span class="pl-c1">1</span>)                       <span class="pl-c">// ["b","a",c"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>)                        <span class="pl-c">// ["b","a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)                        <span class="pl-c">// ["b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">0</span>)                        <span class="pl-c">// []</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">0</span>)                        <span class="pl-c">// [] (ignored)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Empty</span>()                      <span class="pl-c">// true</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Size</span>()                       <span class="pl-c">// 0</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"a"</span>)                         <span class="pl-c">// ["a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Clear</span>()                          <span class="pl-c">// []</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Insert</span>(<span class="pl-c1">0</span>, <span class="pl-s">"b"</span>)                   <span class="pl-c">// ["b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Insert</span>(<span class="pl-c1">0</span>, <span class="pl-s">"a"</span>)                   <span class="pl-c">// ["a","b"]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	sll &quot;github.com/emirpasic/gods/lists/singlylinkedlist&quot;
	&quot;github.com/emirpasic/gods/utils&quot;
)

func main() {
	list := sll.New()
	list.Add(&quot;a&quot;)                         // [&quot;a&quot;]
	list.Add(&quot;c&quot;, &quot;b&quot;)                    // [&quot;a&quot;,&quot;c&quot;,&quot;b&quot;]
	list.Sort(utils.StringComparator)     // [&quot;a&quot;,&quot;b&quot;,&quot;c&quot;]
	_, _ = list.Get(0)                    // &quot;a&quot;,true
	_, _ = list.Get(100)                  // nil,false
	_ = list.Contains(&quot;a&quot;, &quot;b&quot;, &quot;c&quot;)      // true
	_ = list.Contains(&quot;a&quot;, &quot;b&quot;, &quot;c&quot;, &quot;d&quot;) // false
	list.Swap(0, 1)                       // [&quot;b&quot;,&quot;a&quot;,c&quot;]
	list.Remove(2)                        // [&quot;b&quot;,&quot;a&quot;]
	list.Remove(1)                        // [&quot;b&quot;]
	list.Remove(0)                        // []
	list.Remove(0)                        // [] (ignored)
	_ = list.Empty()                      // true
	_ = list.Size()                       // 0
	list.Add(&quot;a&quot;)                         // [&quot;a&quot;]
	list.Clear()                          // []
	list.Insert(0, &quot;b&quot;)                   // [&quot;b&quot;]
	list.Insert(0, &quot;a&quot;)                   // [&quot;a&quot;,&quot;b&quot;]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-doublylinkedlist" class="anchor" aria-hidden="true" tabindex="-1" href="#doublylinkedlist"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">双向链表</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一个</font></font><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其中每个元素都指向列表中的下一个和上一个元素。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#lists"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">List</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	dll <span class="pl-s">"github.com/emirpasic/gods/lists/doublylinkedlist"</span>
	<span class="pl-s">"github.com/emirpasic/gods/utils"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">list</span> <span class="pl-c1">:=</span> <span class="pl-s1">dll</span>.<span class="pl-en">New</span>()
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"a"</span>)                         <span class="pl-c">// ["a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"c"</span>, <span class="pl-s">"b"</span>)                    <span class="pl-c">// ["a","c","b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Sort</span>(<span class="pl-s1">utils</span>.<span class="pl-c1">StringComparator</span>)     <span class="pl-c">// ["a","b","c"]</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Get</span>(<span class="pl-c1">0</span>)                    <span class="pl-c">// "a",true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Get</span>(<span class="pl-c1">100</span>)                  <span class="pl-c">// nil,false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Contains</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>)      <span class="pl-c">// true</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Contains</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>, <span class="pl-s">"d"</span>) <span class="pl-c">// false</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Swap</span>(<span class="pl-c1">0</span>, <span class="pl-c1">1</span>)                       <span class="pl-c">// ["b","a",c"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>)                        <span class="pl-c">// ["b","a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)                        <span class="pl-c">// ["b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">0</span>)                        <span class="pl-c">// []</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">0</span>)                        <span class="pl-c">// [] (ignored)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Empty</span>()                      <span class="pl-c">// true</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">list</span>.<span class="pl-en">Size</span>()                       <span class="pl-c">// 0</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"a"</span>)                         <span class="pl-c">// ["a"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Clear</span>()                          <span class="pl-c">// []</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Insert</span>(<span class="pl-c1">0</span>, <span class="pl-s">"b"</span>)                   <span class="pl-c">// ["b"]</span>
	<span class="pl-s1">list</span>.<span class="pl-en">Insert</span>(<span class="pl-c1">0</span>, <span class="pl-s">"a"</span>)                   <span class="pl-c">// ["a","b"]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	dll &quot;github.com/emirpasic/gods/lists/doublylinkedlist&quot;
	&quot;github.com/emirpasic/gods/utils&quot;
)

func main() {
	list := dll.New()
	list.Add(&quot;a&quot;)                         // [&quot;a&quot;]
	list.Add(&quot;c&quot;, &quot;b&quot;)                    // [&quot;a&quot;,&quot;c&quot;,&quot;b&quot;]
	list.Sort(utils.StringComparator)     // [&quot;a&quot;,&quot;b&quot;,&quot;c&quot;]
	_, _ = list.Get(0)                    // &quot;a&quot;,true
	_, _ = list.Get(100)                  // nil,false
	_ = list.Contains(&quot;a&quot;, &quot;b&quot;, &quot;c&quot;)      // true
	_ = list.Contains(&quot;a&quot;, &quot;b&quot;, &quot;c&quot;, &quot;d&quot;) // false
	list.Swap(0, 1)                       // [&quot;b&quot;,&quot;a&quot;,c&quot;]
	list.Remove(2)                        // [&quot;b&quot;,&quot;a&quot;]
	list.Remove(1)                        // [&quot;b&quot;]
	list.Remove(0)                        // []
	list.Remove(0)                        // [] (ignored)
	_ = list.Empty()                      // true
	_ = list.Size()                       // 0
	list.Add(&quot;a&quot;)                         // [&quot;a&quot;]
	list.Clear()                          // []
	list.Insert(0, &quot;b&quot;)                   // [&quot;b&quot;]
	list.Insert(0, &quot;a&quot;)                   // [&quot;a&quot;,&quot;b&quot;]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-sets" class="anchor" aria-hidden="true" tabindex="-1" href="#sets"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">套</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集合是一种可以存储元素且没有重复值的数据结构。</font><font style="vertical-align: inherit;">它是有限集数学概念的计算机实现。</font><font style="vertical-align: inherit;">与大多数其他集合类型不同，通常不是从集合中检索特定元素，而是测试元素在集合中的成员资格。</font><font style="vertical-align: inherit;">此结构通常用于确保容器中不存在重复项。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Set还允许集合操作，例如</font></font><a href="https://en.wikipedia.org/wiki/Intersection_(set_theory)" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">交集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://en.wikipedia.org/wiki/Union_(set_theory)" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://proofwiki.org/wiki/Definition:Set_Difference" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">差集</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">等。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#containers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">Set</span> <span class="pl-k">interface</span> {
	<span class="pl-c1">Add</span>(<span class="pl-s1">elements</span> <span class="pl-c1">...</span><span class="pl-k">interface</span>{})
	<span class="pl-c1">Remove</span>(<span class="pl-s1">elements</span> <span class="pl-c1">...</span><span class="pl-k">interface</span>{})
	<span class="pl-c1">Contains</span>(<span class="pl-s1">elements</span> <span class="pl-c1">...</span><span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>
    <span class="pl-c">// Intersection(another *Set) *Set</span>
    <span class="pl-c">// Union(another *Set) *Set</span>
    <span class="pl-c">// Difference(another *Set) *Set</span>
	
	containers.<span class="pl-smi">Container</span>
	<span class="pl-c">// Empty() bool</span>
	<span class="pl-c">// Size() int</span>
	<span class="pl-c">// Clear()</span>
	<span class="pl-c">// Values() []interface{}</span>
	<span class="pl-c">// String() string</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type Set interface {
	Add(elements ...interface{})
	Remove(elements ...interface{})
	Contains(elements ...interface{}) bool
    // Intersection(another *Set) *Set
    // Union(another *Set) *Set
    // Difference(another *Set) *Set
	
	containers.Container
	// Empty() bool
	// Size() int
	// Clear()
	// Values() []interface{}
	// String() string
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-hashset" class="anchor" aria-hidden="true" tabindex="-1" href="#hashset"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希集</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由哈希表（实际上是 Go 的映射）支持的</font></font><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集合</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">它不保证集合的迭代顺序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Set</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/sets/hashset"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">set</span> <span class="pl-c1">:=</span> <span class="pl-s1">hashset</span>.<span class="pl-en">New</span>()   <span class="pl-c">// empty</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">1</span>)             <span class="pl-c">// 1</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">2</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">4</span>, <span class="pl-c1">5</span>) <span class="pl-c">// 3, 1, 2, 4, 5 (random order, duplicates ignored)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">4</span>)          <span class="pl-c">// 5, 3, 2, 1 (random order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>, <span class="pl-c1">3</span>)       <span class="pl-c">// 1, 5 (random order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>)        <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>, <span class="pl-c1">5</span>)     <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>, <span class="pl-c1">6</span>)     <span class="pl-c">// false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">set</span>.<span class="pl-en">Values</span>()       <span class="pl-c">// []int{5,1} (random order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Clear</span>()            <span class="pl-c">// empty</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Empty</span>()            <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Size</span>()             <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/sets/hashset&quot;

func main() {
	set := hashset.New()   // empty
	set.Add(1)             // 1
	set.Add(2, 2, 3, 4, 5) // 3, 1, 2, 4, 5 (random order, duplicates ignored)
	set.Remove(4)          // 5, 3, 2, 1 (random order)
	set.Remove(2, 3)       // 1, 5 (random order)
	set.Contains(1)        // true
	set.Contains(1, 5)     // true
	set.Contains(1, 6)     // false
	_ = set.Values()       // []int{5,1} (random order)
	set.Clear()            // empty
	set.Empty()            // true
	set.Size()             // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-treeset" class="anchor" aria-hidden="true" tabindex="-1" href="#treeset"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树集</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><a href="#redblacktree"><font style="vertical-align: inherit;">由红黑树</font></a><font style="vertical-align: inherit;">支持的</font><font style="vertical-align: inherit;">集合</font><font style="vertical-align: inherit;">，用于保持元素相对于</font><a href="#comparator"><font style="vertical-align: inherit;">比较器的</font></a></font><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有序</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><a href="#redblacktree"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="#comparator"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Set</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/sets/treeset"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">set</span> <span class="pl-c1">:=</span> <span class="pl-s1">treeset</span>.<span class="pl-en">NewWithIntComparator</span>() <span class="pl-c">// empty (keys are of type int)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">1</span>)                            <span class="pl-c">// 1</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">2</span>, <span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">4</span>, <span class="pl-c1">5</span>)                <span class="pl-c">// 1, 2, 3, 4, 5 (in order, duplicates ignored)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">4</span>)                         <span class="pl-c">// 1, 2, 3, 5 (in order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>, <span class="pl-c1">3</span>)                      <span class="pl-c">// 1, 5 (in order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>)                       <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>, <span class="pl-c1">5</span>)                    <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>, <span class="pl-c1">6</span>)                    <span class="pl-c">// false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">set</span>.<span class="pl-en">Values</span>()                      <span class="pl-c">// []int{1,5} (in order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Clear</span>()                           <span class="pl-c">// empty</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Empty</span>()                           <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Size</span>()                            <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/sets/treeset&quot;

func main() {
	set := treeset.NewWithIntComparator() // empty (keys are of type int)
	set.Add(1)                            // 1
	set.Add(2, 2, 3, 4, 5)                // 1, 2, 3, 4, 5 (in order, duplicates ignored)
	set.Remove(4)                         // 1, 2, 3, 5 (in order)
	set.Remove(2, 3)                      // 1, 5 (in order)
	set.Contains(1)                       // true
	set.Contains(1, 5)                    // true
	set.Contains(1, 6)                    // false
	_ = set.Values()                      // []int{1,5} (in order)
	set.Clear()                           // empty
	set.Empty()                           // true
	set.Size()                            // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-linkedhashset" class="anchor" aria-hidden="true" tabindex="-1" href="#linkedhashset"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接哈希集</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保留插入顺序的</font></font><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">集合</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">数据结构由用于存储值的哈希表和用于</font><font style="vertical-align: inherit;">存储插入顺序的</font></font><a href="#doublylinkedlist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">双向链表支持。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#sets"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Set</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/sets/linkedhashset"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">set</span> <span class="pl-c1">:=</span> <span class="pl-s1">linkedhashset</span>.<span class="pl-en">New</span>() <span class="pl-c">// empty</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">5</span>)                 <span class="pl-c">// 5</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">4</span>, <span class="pl-c1">4</span>, <span class="pl-c1">3</span>, <span class="pl-c1">2</span>, <span class="pl-c1">1</span>)     <span class="pl-c">// 5, 4, 3, 2, 1 (in insertion-order, duplicates ignored)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">4</span>)                 <span class="pl-c">// 5, 4, 3, 2, 1 (duplicates ignored, insertion-order unchanged)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">4</span>)              <span class="pl-c">// 5, 3, 2, 1 (in insertion-order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>, <span class="pl-c1">3</span>)           <span class="pl-c">// 5, 1 (in insertion-order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>)            <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>, <span class="pl-c1">5</span>)         <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Contains</span>(<span class="pl-c1">1</span>, <span class="pl-c1">6</span>)         <span class="pl-c">// false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">set</span>.<span class="pl-en">Values</span>()           <span class="pl-c">// []int{5, 1} (in insertion-order)</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Clear</span>()                <span class="pl-c">// empty</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Empty</span>()                <span class="pl-c">// true</span>
	<span class="pl-s1">set</span>.<span class="pl-en">Size</span>()                 <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/sets/linkedhashset&quot;

func main() {
	set := linkedhashset.New() // empty
	set.Add(5)                 // 5
	set.Add(4, 4, 3, 2, 1)     // 5, 4, 3, 2, 1 (in insertion-order, duplicates ignored)
	set.Add(4)                 // 5, 4, 3, 2, 1 (duplicates ignored, insertion-order unchanged)
	set.Remove(4)              // 5, 3, 2, 1 (in insertion-order)
	set.Remove(2, 3)           // 5, 1 (in insertion-order)
	set.Contains(1)            // true
	set.Contains(1, 5)         // true
	set.Contains(1, 6)         // false
	_ = set.Values()           // []int{5, 1} (in insertion-order)
	set.Clear()                // empty
	set.Empty()                // true
	set.Size()                 // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-stacks" class="anchor" aria-hidden="true" tabindex="-1" href="#stacks"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆栈</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表示后进先出 (LIFO) 数据结构的堆栈。</font><font style="vertical-align: inherit;">提供了常用的入栈和出栈操作，以及查看堆栈顶部项目的方法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#containers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">Stack</span> <span class="pl-k">interface</span> {
	<span class="pl-c1">Push</span>(<span class="pl-s1">value</span> <span class="pl-k">interface</span>{})
	<span class="pl-c1">Pop</span>() (<span class="pl-s1">value</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">ok</span> <span class="pl-smi">bool</span>)
	<span class="pl-c1">Peek</span>() (<span class="pl-s1">value</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">ok</span> <span class="pl-smi">bool</span>)

	containers.<span class="pl-smi">Container</span>
	<span class="pl-c">// Empty() bool</span>
	<span class="pl-c">// Size() int</span>
	<span class="pl-c">// Clear()</span>
	<span class="pl-c">// Values() []interface{}</span>
	<span class="pl-c">// String() string</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type Stack interface {
	Push(value interface{})
	Pop() (value interface{}, ok bool)
	Peek() (value interface{}, ok bool)

	containers.Container
	// Empty() bool
	// Size() int
	// Clear()
	// Values() []interface{}
	// String() string
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-linkedliststack" class="anchor" aria-hidden="true" tabindex="-1" href="#linkedliststack"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链表栈</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于</font><a href="#singlylinkedlist"><font style="vertical-align: inherit;">链表</font></a></font><a href="#stacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆栈</font><font style="vertical-align: inherit;">。</font></font><a href="#singlylinkedlist"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#stacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stack</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> lls <span class="pl-s">"github.com/emirpasic/gods/stacks/linkedliststack"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">stack</span> <span class="pl-c1">:=</span> <span class="pl-s1">lls</span>.<span class="pl-en">New</span>()  <span class="pl-c">// empty</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Push</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Push</span>(<span class="pl-c1">2</span>)       <span class="pl-c">// 1, 2</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Values</span>()      <span class="pl-c">// 2, 1 (LIFO order)</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Peek</span>() <span class="pl-c">// 2,true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Pop</span>()  <span class="pl-c">// 2, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Pop</span>()  <span class="pl-c">// 1, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Pop</span>()  <span class="pl-c">// nil, false (nothing to pop)</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Push</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Clear</span>()       <span class="pl-c">// empty</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Empty</span>()       <span class="pl-c">// true</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Size</span>()        <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import lls &quot;github.com/emirpasic/gods/stacks/linkedliststack&quot;

func main() {
	stack := lls.New()  // empty
	stack.Push(1)       // 1
	stack.Push(2)       // 1, 2
	stack.Values()      // 2, 1 (LIFO order)
	_, _ = stack.Peek() // 2,true
	_, _ = stack.Pop()  // 2, true
	_, _ = stack.Pop()  // 1, true
	_, _ = stack.Pop()  // nil, false (nothing to pop)
	stack.Push(1)       // 1
	stack.Clear()       // empty
	stack.Empty()       // true
	stack.Size()        // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-arraystack" class="anchor" aria-hidden="true" tabindex="-1" href="#arraystack"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组栈</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于</font><a href="#arraylist"><font style="vertical-align: inherit;">数组列表</font></a></font><a href="#stacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆栈</font><font style="vertical-align: inherit;">。</font></font><a href="#arraylist"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#stacks"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stack</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/stacks/arraystack"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">stack</span> <span class="pl-c1">:=</span> <span class="pl-s1">arraystack</span>.<span class="pl-en">New</span>() <span class="pl-c">// empty</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Push</span>(<span class="pl-c1">1</span>)             <span class="pl-c">// 1</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Push</span>(<span class="pl-c1">2</span>)             <span class="pl-c">// 1, 2</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Values</span>()            <span class="pl-c">// 2, 1 (LIFO order)</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Peek</span>()       <span class="pl-c">// 2,true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Pop</span>()        <span class="pl-c">// 2, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Pop</span>()        <span class="pl-c">// 1, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">stack</span>.<span class="pl-en">Pop</span>()        <span class="pl-c">// nil, false (nothing to pop)</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Push</span>(<span class="pl-c1">1</span>)             <span class="pl-c">// 1</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Clear</span>()             <span class="pl-c">// empty</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Empty</span>()             <span class="pl-c">// true</span>
	<span class="pl-s1">stack</span>.<span class="pl-en">Size</span>()              <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/stacks/arraystack&quot;

func main() {
	stack := arraystack.New() // empty
	stack.Push(1)             // 1
	stack.Push(2)             // 1, 2
	stack.Values()            // 2, 1 (LIFO order)
	_, _ = stack.Peek()       // 2,true
	_, _ = stack.Pop()        // 2, true
	_, _ = stack.Pop()        // 1, true
	_, _ = stack.Pop()        // nil, false (nothing to pop)
	stack.Push(1)             // 1
	stack.Clear()             // empty
	stack.Empty()             // true
	stack.Size()              // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-maps" class="anchor" aria-hidden="true" tabindex="-1" href="#maps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地图</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Map 是将键映射到值的数据结构。</font><font style="vertical-align: inherit;">映射不能包含重复的键，并且每个键最多可以映射到一个值。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#containers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">Map</span> <span class="pl-k">interface</span> {
	<span class="pl-c1">Put</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{})
	<span class="pl-c1">Get</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}) (<span class="pl-s1">value</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">found</span> <span class="pl-smi">bool</span>)
	<span class="pl-c1">Remove</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{})
	<span class="pl-c1">Keys</span>() []<span class="pl-k">interface</span>{}

	containers.<span class="pl-smi">Container</span>
	<span class="pl-c">// Empty() bool</span>
	<span class="pl-c">// Size() int</span>
	<span class="pl-c">// Clear()</span>
	<span class="pl-c">// Values() []interface{}</span>
	<span class="pl-c">// String() string</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type Map interface {
	Put(key interface{}, value interface{})
	Get(key interface{}) (value interface{}, found bool)
	Remove(key interface{})
	Keys() []interface{}

	containers.Container
	// Empty() bool
	// Size() int
	// Clear()
	// Values() []interface{}
	// String() string
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BidiMap 是 Map 的扩展。</font><font style="vertical-align: inherit;">双向映射（BidiMap）也称为哈希包，是一种关联数据结构，其中键值对形成一对一的关系。</font><font style="vertical-align: inherit;">这种关系在两个方向上起作用，允许值也充当键到键的键，例如一对 (a,b) 因此提供了 'a' 和 'b' 之间的耦合，以便当 'a' 时可以找到 'b' ' 用作键，当'b' 用作键时可以找到'a'。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">BidiMap</span> <span class="pl-k">interface</span> {
	<span class="pl-c1">GetKey</span>(<span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) (<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">found</span> <span class="pl-smi">bool</span>)

	<span class="pl-smi">Map</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type BidiMap interface {
	GetKey(value interface{}) (key interface{}, found bool)

	Map
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-hashmap" class="anchor" aria-hidden="true" tabindex="-1" href="#hashmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希映射</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于哈希表的</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">映射</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">键是无序的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Map</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/maps/hashmap"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">m</span> <span class="pl-c1">:=</span> <span class="pl-s1">hashmap</span>.<span class="pl-en">New</span>() <span class="pl-c">// empty</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>)      <span class="pl-c">// 1-&gt;x</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>)      <span class="pl-c">// 2-&gt;b, 1-&gt;x (random order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>)      <span class="pl-c">// 2-&gt;b, 1-&gt;a (random order)</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">2</span>)    <span class="pl-c">// b, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">3</span>)    <span class="pl-c">// nil, false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Values</span>()     <span class="pl-c">// []interface {}{"b", "a"} (random order)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Keys</span>()       <span class="pl-c">// []interface {}{1, 2} (random order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)        <span class="pl-c">// 2-&gt;b</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Clear</span>()          <span class="pl-c">// empty</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Empty</span>()          <span class="pl-c">// true</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Size</span>()           <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/maps/hashmap&quot;

func main() {
	m := hashmap.New() // empty
	m.Put(1, &quot;x&quot;)      // 1->x
	m.Put(2, &quot;b&quot;)      // 2->b, 1->x (random order)
	m.Put(1, &quot;a&quot;)      // 2->b, 1->a (random order)
	_, _ = m.Get(2)    // b, true
	_, _ = m.Get(3)    // nil, false
	_ = m.Values()     // []interface {}{&quot;b&quot;, &quot;a&quot;} (random order)
	_ = m.Keys()       // []interface {}{1, 2} (random order)
	m.Remove(1)        // 2->b
	m.Clear()          // empty
	m.Empty()          // true
	m.Size()           // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-treemap" class="anchor" aria-hidden="true" tabindex="-1" href="#treemap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树形图</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于</font><a href="#redblacktree"><font style="vertical-align: inherit;">红黑树</font></a></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">映射</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">键是根据</font><a href="#comparator"><font style="vertical-align: inherit;">比较器</font></a><font style="vertical-align: inherit;">排序的。</font></font><a href="#redblacktree"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><a href="#comparator"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Map</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/maps/treemap"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">m</span> <span class="pl-c1">:=</span> <span class="pl-s1">treemap</span>.<span class="pl-en">NewWithIntComparator</span>() <span class="pl-c">// empty (keys are of type int)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>)                       <span class="pl-c">// 1-&gt;x</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>)                       <span class="pl-c">// 1-&gt;x, 2-&gt;b (in order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>)                       <span class="pl-c">// 1-&gt;a, 2-&gt;b (in order)</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">2</span>)                     <span class="pl-c">// b, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">3</span>)                     <span class="pl-c">// nil, false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Values</span>()                      <span class="pl-c">// []interface {}{"a", "b"} (in order)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Keys</span>()                        <span class="pl-c">// []interface {}{1, 2} (in order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)                         <span class="pl-c">// 2-&gt;b</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Clear</span>()                           <span class="pl-c">// empty</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Empty</span>()                           <span class="pl-c">// true</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Size</span>()                            <span class="pl-c">// 0</span>

	<span class="pl-c">// Other:</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Min</span>() <span class="pl-c">// Returns the minimum key and its value from map.</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Max</span>() <span class="pl-c">// Returns the maximum key and its value from map.</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/maps/treemap&quot;

func main() {
	m := treemap.NewWithIntComparator() // empty (keys are of type int)
	m.Put(1, &quot;x&quot;)                       // 1->x
	m.Put(2, &quot;b&quot;)                       // 1->x, 2->b (in order)
	m.Put(1, &quot;a&quot;)                       // 1->a, 2->b (in order)
	_, _ = m.Get(2)                     // b, true
	_, _ = m.Get(3)                     // nil, false
	_ = m.Values()                      // []interface {}{&quot;a&quot;, &quot;b&quot;} (in order)
	_ = m.Keys()                        // []interface {}{1, 2} (in order)
	m.Remove(1)                         // 2->b
	m.Clear()                           // empty
	m.Empty()                           // true
	m.Size()                            // 0

	// Other:
	m.Min() // Returns the minimum key and its value from map.
	m.Max() // Returns the maximum key and its value from map.
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-linkedhashmap" class="anchor" aria-hidden="true" tabindex="-1" href="#linkedhashmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接哈希映射</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">保留插入顺序的</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">映射</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">它由哈希表支持来存储值和</font></font><a href="/emirpasic/gods/blob/master/doublylinkedlist"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">双向链表</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来存储排序。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Map</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/maps/linkedhashmap"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">m</span> <span class="pl-c1">:=</span> <span class="pl-s1">linkedhashmap</span>.<span class="pl-en">New</span>() <span class="pl-c">// empty (keys are of type int)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>)            <span class="pl-c">// 2-&gt;b</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>)            <span class="pl-c">// 2-&gt;b, 1-&gt;x (insertion-order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>)            <span class="pl-c">// 2-&gt;b, 1-&gt;a (insertion-order)</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">2</span>)          <span class="pl-c">// b, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">3</span>)          <span class="pl-c">// nil, false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Values</span>()           <span class="pl-c">// []interface {}{"b", "a"} (insertion-order)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Keys</span>()             <span class="pl-c">// []interface {}{2, 1} (insertion-order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)              <span class="pl-c">// 2-&gt;b</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Clear</span>()                <span class="pl-c">// empty</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Empty</span>()                <span class="pl-c">// true</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Size</span>()                 <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/maps/linkedhashmap&quot;

func main() {
	m := linkedhashmap.New() // empty (keys are of type int)
	m.Put(2, &quot;b&quot;)            // 2->b
	m.Put(1, &quot;x&quot;)            // 2->b, 1->x (insertion-order)
	m.Put(1, &quot;a&quot;)            // 2->b, 1->a (insertion-order)
	_, _ = m.Get(2)          // b, true
	_, _ = m.Get(3)          // nil, false
	_ = m.Values()           // []interface {}{&quot;b&quot;, &quot;a&quot;} (insertion-order)
	_ = m.Keys()             // []interface {}{2, 1} (insertion-order)
	m.Remove(1)              // 2->b
	m.Clear()                // empty
	m.Empty()                // true
	m.Size()                 // 0
}
" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-hashbidimap" class="anchor" aria-hidden="true" tabindex="-1" href="#hashbidimap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">哈希比迪映射</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于两个哈希图的</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">映射</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">键是无序的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BidiMap</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/maps/hashbidimap"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">m</span> <span class="pl-c1">:=</span> <span class="pl-s1">hashbidimap</span>.<span class="pl-en">New</span>() <span class="pl-c">// empty</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>)          <span class="pl-c">// 1-&gt;x</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">3</span>, <span class="pl-s">"b"</span>)          <span class="pl-c">// 1-&gt;x, 3-&gt;b (random order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>)          <span class="pl-c">// 1-&gt;a, 3-&gt;b (random order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>)          <span class="pl-c">// 1-&gt;a, 2-&gt;b (random order)</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">GetKey</span>(<span class="pl-s">"a"</span>)   <span class="pl-c">// 1, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">2</span>)        <span class="pl-c">// b, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">3</span>)        <span class="pl-c">// nil, false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Values</span>()         <span class="pl-c">// []interface {}{"a", "b"} (random order)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Keys</span>()           <span class="pl-c">// []interface {}{1, 2} (random order)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)            <span class="pl-c">// 2-&gt;b</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Clear</span>()              <span class="pl-c">// empty</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Empty</span>()              <span class="pl-c">// true</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Size</span>()               <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/maps/hashbidimap&quot;

func main() {
	m := hashbidimap.New() // empty
	m.Put(1, &quot;x&quot;)          // 1->x
	m.Put(3, &quot;b&quot;)          // 1->x, 3->b (random order)
	m.Put(1, &quot;a&quot;)          // 1->a, 3->b (random order)
	m.Put(2, &quot;b&quot;)          // 1->a, 2->b (random order)
	_, _ = m.GetKey(&quot;a&quot;)   // 1, true
	_, _ = m.Get(2)        // b, true
	_, _ = m.Get(3)        // nil, false
	_ = m.Values()         // []interface {}{&quot;a&quot;, &quot;b&quot;} (random order)
	_ = m.Keys()           // []interface {}{1, 2} (random order)
	m.Remove(1)            // 2->b
	m.Clear()              // empty
	m.Empty()              // true
	m.Size()               // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-treebidimap" class="anchor" aria-hidden="true" tabindex="-1" href="#treebidimap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树比迪地图</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于红黑树的</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">映射</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">该映射保证映射将按键和值的升序排列。</font><font style="vertical-align: inherit;">除了键和值排序之外，此结构的目标是避免元素重复（与</font></font><a href="#hashbidimap"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HashBidiMap</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不同），如果包含的元素很大，这可能很重要。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#maps"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BidiMap</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#enumerablewithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"github.com/emirpasic/gods/maps/treebidimap"</span>
	<span class="pl-s">"github.com/emirpasic/gods/utils"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">m</span> <span class="pl-c1">:=</span> <span class="pl-s1">treebidimap</span>.<span class="pl-en">NewWith</span>(<span class="pl-s1">utils</span>.<span class="pl-c1">IntComparator</span>, <span class="pl-s1">utils</span>.<span class="pl-c1">StringComparator</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>)        <span class="pl-c">// 1-&gt;x</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">3</span>, <span class="pl-s">"b"</span>)        <span class="pl-c">// 1-&gt;x, 3-&gt;b (ordered)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>)        <span class="pl-c">// 1-&gt;a, 3-&gt;b (ordered)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>)        <span class="pl-c">// 1-&gt;a, 2-&gt;b (ordered)</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">GetKey</span>(<span class="pl-s">"a"</span>) <span class="pl-c">// 1, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">2</span>)      <span class="pl-c">// b, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Get</span>(<span class="pl-c1">3</span>)      <span class="pl-c">// nil, false</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Values</span>()       <span class="pl-c">// []interface {}{"a", "b"} (ordered)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">m</span>.<span class="pl-en">Keys</span>()         <span class="pl-c">// []interface {}{1, 2} (ordered)</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">1</span>)          <span class="pl-c">// 2-&gt;b</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Clear</span>()            <span class="pl-c">// empty</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Empty</span>()            <span class="pl-c">// true</span>
	<span class="pl-s1">m</span>.<span class="pl-en">Size</span>()             <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;github.com/emirpasic/gods/maps/treebidimap&quot;
	&quot;github.com/emirpasic/gods/utils&quot;
)

func main() {
	m := treebidimap.NewWith(utils.IntComparator, utils.StringComparator)
	m.Put(1, &quot;x&quot;)        // 1->x
	m.Put(3, &quot;b&quot;)        // 1->x, 3->b (ordered)
	m.Put(1, &quot;a&quot;)        // 1->a, 3->b (ordered)
	m.Put(2, &quot;b&quot;)        // 1->a, 2->b (ordered)
	_, _ = m.GetKey(&quot;a&quot;) // 1, true
	_, _ = m.Get(2)      // b, true
	_, _ = m.Get(3)      // nil, false
	_ = m.Values()       // []interface {}{&quot;a&quot;, &quot;b&quot;} (ordered)
	_ = m.Keys()         // []interface {}{1, 2} (ordered)
	m.Remove(1)          // 2->b
	m.Clear()            // empty
	m.Empty()            // true
	m.Size()             // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-trees" class="anchor" aria-hidden="true" tabindex="-1" href="#trees"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树木</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树是一种广泛使用的数据数据结构，它模拟分层树结构，具有根值和子树的子树，表示为一组链接的节点；</font><font style="vertical-align: inherit;">因此没有循环链接。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#containers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">Tree</span> <span class="pl-k">interface</span> {
	containers.<span class="pl-smi">Container</span>
	<span class="pl-c">// Empty() bool</span>
	<span class="pl-c">// Size() int</span>
	<span class="pl-c">// Clear()</span>
	<span class="pl-c">// Values() []interface{}</span>
	<span class="pl-c">// String() string</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type Tree interface {
	containers.Container
	// Empty() bool
	// Size() int
	// Clear()
	// Values() []interface{}
	// String() string
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-redblacktree" class="anchor" aria-hidden="true" tabindex="-1" href="#redblacktree"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红黑树</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">红黑</font></font><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一种二叉搜索树，每个节点有一个额外的数据位，即它的颜色，可以是红色或黑色。</font><font style="vertical-align: inherit;">额外的存储位通过限制从根到叶的任何路径的节点着色方式来确保近似平衡的树。</font><font style="vertical-align: inherit;">因此，它是一种自平衡二叉搜索树的数据结构。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树的平衡并不完美，但足以保证在 O(log n) 时间内进行搜索，其中 n 是树中元素的总数。</font><font style="vertical-align: inherit;">插入和删除操作以及树的重新排列和重新着色也在 O(log n) 时间内执行。</font></font><sub><sup><a href="http://en.wikipedia.org/wiki/Red%E2%80%93black_tree" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维基百科</font></font></a></sup></sub></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tree</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/95c259e200032f405c9e84a97dfe4bdfe84488ef9525c741a27722e774b24748/687474703a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f362f36362f5265642d626c61636b5f747265655f6578616d706c652e7376672f35303070782d5265642d626c61636b5f747265655f6578616d706c652e7376672e706e67"><img src="https://camo.githubusercontent.com/95c259e200032f405c9e84a97dfe4bdfe84488ef9525c741a27722e774b24748/687474703a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f362f36362f5265642d626c61636b5f747265655f6578616d706c652e7376672f35303070782d5265642d626c61636b5f747265655f6578616d706c652e7376672e706e67" width="400px" height="200px" data-canonical-src="http://upload.wikimedia.org/wikipedia/commons/thumb/6/66/Red-black_tree_example.svg/500px-Red-black_tree_example.svg.png" style="max-width: 100%;"></a></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"fmt"</span>
	rbt <span class="pl-s">"github.com/emirpasic/gods/trees/redblacktree"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">tree</span> <span class="pl-c1">:=</span> <span class="pl-s1">rbt</span>.<span class="pl-en">NewWithIntComparator</span>() <span class="pl-c">// empty (keys are of type int)</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>) <span class="pl-c">// 1-&gt;x</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>) <span class="pl-c">// 1-&gt;x, 2-&gt;b (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b (in order, replacement)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">3</span>, <span class="pl-s">"c"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">4</span>, <span class="pl-s">"d"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">5</span>, <span class="pl-s">"e"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d, 5-&gt;e (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">6</span>, <span class="pl-s">"f"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d, 5-&gt;e, 6-&gt;f (in order)</span>

	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">tree</span>)
	<span class="pl-c">//</span>
	<span class="pl-c">//  RedBlackTree</span>
	<span class="pl-c">//  │           ┌── 6</span>
	<span class="pl-c">//	│       ┌── 5</span>
	<span class="pl-c">//	│   ┌── 4</span>
	<span class="pl-c">//	│   │   └── 3</span>
	<span class="pl-c">//	└── 2</span>
	<span class="pl-c">//		└── 1</span>

	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Values</span>() <span class="pl-c">// []interface {}{"a", "b", "c", "d", "e", "f"} (in order)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Keys</span>()   <span class="pl-c">// []interface {}{1, 2, 3, 4, 5, 6} (in order)</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>) <span class="pl-c">// 1-&gt;a, 3-&gt;c, 4-&gt;d, 5-&gt;e, 6-&gt;f (in order)</span>
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">tree</span>)
	<span class="pl-c">//</span>
	<span class="pl-c">//  RedBlackTree</span>
	<span class="pl-c">//  │       ┌── 6</span>
	<span class="pl-c">//  │   ┌── 5</span>
	<span class="pl-c">//  └── 4</span>
	<span class="pl-c">//      │   ┌── 3</span>
	<span class="pl-c">//      └── 1</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Clear</span>() <span class="pl-c">// empty</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Empty</span>() <span class="pl-c">// true</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Size</span>()  <span class="pl-c">// 0</span>

	<span class="pl-c">// Other:</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Left</span>() <span class="pl-c">// gets the left-most (min) node</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Right</span>() <span class="pl-c">// get the right-most (max) node</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Floor</span>(<span class="pl-c1">1</span>) <span class="pl-c">// get the floor node</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Ceiling</span>(<span class="pl-c1">1</span>) <span class="pl-c">// get the ceiling node</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;fmt&quot;
	rbt &quot;github.com/emirpasic/gods/trees/redblacktree&quot;
)

func main() {
	tree := rbt.NewWithIntComparator() // empty (keys are of type int)

	tree.Put(1, &quot;x&quot;) // 1->x
	tree.Put(2, &quot;b&quot;) // 1->x, 2->b (in order)
	tree.Put(1, &quot;a&quot;) // 1->a, 2->b (in order, replacement)
	tree.Put(3, &quot;c&quot;) // 1->a, 2->b, 3->c (in order)
	tree.Put(4, &quot;d&quot;) // 1->a, 2->b, 3->c, 4->d (in order)
	tree.Put(5, &quot;e&quot;) // 1->a, 2->b, 3->c, 4->d, 5->e (in order)
	tree.Put(6, &quot;f&quot;) // 1->a, 2->b, 3->c, 4->d, 5->e, 6->f (in order)

	fmt.Println(tree)
	//
	//  RedBlackTree
	//  │           ┌── 6
	//	│       ┌── 5
	//	│   ┌── 4
	//	│   │   └── 3
	//	└── 2
	//		└── 1

	_ = tree.Values() // []interface {}{&quot;a&quot;, &quot;b&quot;, &quot;c&quot;, &quot;d&quot;, &quot;e&quot;, &quot;f&quot;} (in order)
	_ = tree.Keys()   // []interface {}{1, 2, 3, 4, 5, 6} (in order)

	tree.Remove(2) // 1->a, 3->c, 4->d, 5->e, 6->f (in order)
	fmt.Println(tree)
	//
	//  RedBlackTree
	//  │       ┌── 6
	//  │   ┌── 5
	//  └── 4
	//      │   ┌── 3
	//      └── 1

	tree.Clear() // empty
	tree.Empty() // true
	tree.Size()  // 0

	// Other:
	tree.Left() // gets the left-most (min) node
	tree.Right() // get the right-most (max) node
	tree.Floor(1) // get the floor node
	tree.Ceiling(1) // get the ceiling node
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/emirpasic/gods/blob/master/examples/redblacktreeextended/redblacktreeextended.go"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以下示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示了扩展红黑树的功能</font><font style="vertical-align: inherit;">。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-avltree" class="anchor" aria-hidden="true" tabindex="-1" href="#avltree"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AVL树</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AVL</font></font><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一种自平衡二叉搜索树。</font><font style="vertical-align: inherit;">在AVL树中，任意节点的两个子子树的高度最多相差1；</font><font style="vertical-align: inherit;">如果在任何时候它们相差超过一，则进行重新平衡以恢复该属性。</font><font style="vertical-align: inherit;">在平均情况和最坏情况下，查找、插入和删除都需要 O(log n) 时间，其中 n 是操作之前树中的节点数。</font><font style="vertical-align: inherit;">插入和删除可能需要通过一次或多次树旋转来重新平衡树。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AVL 树经常与红黑树进行比较，因为两者都支持相同的操作集，并且基本操作需要 O(log n) 时间。</font><font style="vertical-align: inherit;">对于查找密集型应用程序，AVL 树比红黑树更快，因为它们更严格地平衡。</font></font><sub><sup><a href="https://en.wikipedia.org/wiki/AVL_tree" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维基百科</font></font></a></sup></sub></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tree</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/7a605e13243dda5c16252d5fa64a0af94ad3ac2e51bfd9b8c9439781cf887e59/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f612f61642f41564c2d747265652d7742616c616e63655f4b2e7376672f32363270782d41564c2d747265652d7742616c616e63655f4b2e7376672e706e67"><img src="https://camo.githubusercontent.com/7a605e13243dda5c16252d5fa64a0af94ad3ac2e51bfd9b8c9439781cf887e59/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f612f61642f41564c2d747265652d7742616c616e63655f4b2e7376672f32363270782d41564c2d747265652d7742616c616e63655f4b2e7376672e706e67" width="300px" height="180px" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ad/AVL-tree-wBalance_K.svg/262px-AVL-tree-wBalance_K.svg.png" style="max-width: 100%;"></a><br><sub><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有平衡因子的 AVL 树（绿色）</font></font></sub></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"fmt"</span>
	avl <span class="pl-s">"github.com/emirpasic/gods/trees/avltree"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">tree</span> <span class="pl-c1">:=</span> <span class="pl-s1">avl</span>.<span class="pl-en">NewWithIntComparator</span>() <span class="pl-c">// empty(keys are of type int)</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>) <span class="pl-c">// 1-&gt;x</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>) <span class="pl-c">// 1-&gt;x, 2-&gt;b (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b (in order, replacement)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">3</span>, <span class="pl-s">"c"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">4</span>, <span class="pl-s">"d"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">5</span>, <span class="pl-s">"e"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d, 5-&gt;e (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">6</span>, <span class="pl-s">"f"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d, 5-&gt;e, 6-&gt;f (in order)</span>

	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">tree</span>)
	<span class="pl-c">//</span>
	<span class="pl-c">//  AVLTree</span>
	<span class="pl-c">//  │       ┌── 6</span>
	<span class="pl-c">//  │   ┌── 5</span>
	<span class="pl-c">//  └── 4</span>
	<span class="pl-c">//      │   ┌── 3</span>
	<span class="pl-c">//      └── 2</span>
	<span class="pl-c">//          └── 1</span>


	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Values</span>() <span class="pl-c">// []interface {}{"a", "b", "c", "d", "e", "f"} (in order)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Keys</span>()   <span class="pl-c">// []interface {}{1, 2, 3, 4, 5, 6} (in order)</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>) <span class="pl-c">// 1-&gt;a, 3-&gt;c, 4-&gt;d, 5-&gt;e, 6-&gt;f (in order)</span>
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">tree</span>)
	<span class="pl-c">//</span>
	<span class="pl-c">//  AVLTree</span>
	<span class="pl-c">//  │       ┌── 6</span>
	<span class="pl-c">//  │   ┌── 5</span>
	<span class="pl-c">//  └── 4</span>
	<span class="pl-c">//      └── 3</span>
	<span class="pl-c">//          └── 1</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Clear</span>() <span class="pl-c">// empty</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Empty</span>() <span class="pl-c">// true</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Size</span>()  <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;fmt&quot;
	avl &quot;github.com/emirpasic/gods/trees/avltree&quot;
)

func main() {
	tree := avl.NewWithIntComparator() // empty(keys are of type int)

	tree.Put(1, &quot;x&quot;) // 1->x
	tree.Put(2, &quot;b&quot;) // 1->x, 2->b (in order)
	tree.Put(1, &quot;a&quot;) // 1->a, 2->b (in order, replacement)
	tree.Put(3, &quot;c&quot;) // 1->a, 2->b, 3->c (in order)
	tree.Put(4, &quot;d&quot;) // 1->a, 2->b, 3->c, 4->d (in order)
	tree.Put(5, &quot;e&quot;) // 1->a, 2->b, 3->c, 4->d, 5->e (in order)
	tree.Put(6, &quot;f&quot;) // 1->a, 2->b, 3->c, 4->d, 5->e, 6->f (in order)

	fmt.Println(tree)
	//
	//  AVLTree
	//  │       ┌── 6
	//  │   ┌── 5
	//  └── 4
	//      │   ┌── 3
	//      └── 2
	//          └── 1


	_ = tree.Values() // []interface {}{&quot;a&quot;, &quot;b&quot;, &quot;c&quot;, &quot;d&quot;, &quot;e&quot;, &quot;f&quot;} (in order)
	_ = tree.Keys()   // []interface {}{1, 2, 3, 4, 5, 6} (in order)

	tree.Remove(2) // 1->a, 3->c, 4->d, 5->e, 6->f (in order)
	fmt.Println(tree)
	//
	//  AVLTree
	//  │       ┌── 6
	//  │   ┌── 5
	//  └── 4
	//      └── 3
	//          └── 1

	tree.Clear() // empty
	tree.Empty() // true
	tree.Size()  // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-btree" class="anchor" aria-hidden="true" tabindex="-1" href="#btree"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B树</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">B 树是一种自平衡树数据结构，可保持数据排序并允许在对数时间内搜索、顺序访问、插入和删除。</font><font style="vertical-align: inherit;">B 树是二叉搜索树的推广，其中一个节点可以有两个以上的子节点。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据Knuth的定义，m阶B树是满足以下性质的树：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个节点最多有 m 个子节点。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个非叶节点（根除外）至少有 ⌈m/2⌉ 个子节点。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果根不是叶节点，则它至少有两个子节点。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">具有 k 个子节点的非叶节点包含 k−1 个键。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有叶子都出现在同一级别</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个内部节点的键充当分隔其子树的分隔值。</font><font style="vertical-align: inherit;">例如，如果一个内部节点有 3 个子节点（或子树），那么它必须有 2 个键：a1 和 a2。</font><font style="vertical-align: inherit;">最左边子树中的所有值都将小于 a1，中间子树中的所有值将在 a1 和 a2 之间，最右边子树中的所有值将大于 a2。</font></font><sub><sup><a href="http://en.wikipedia.org/wiki/Red%E2%80%93black_tree" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维基百科</font></font></a></sup></sub></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tree</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/20c6209744d15728e1833e57aded8ffdda9122e22849b9a523aa16ee0168b88a/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f362f36352f422d747265652e7376672f38333170782d422d747265652e7376672e706e67"><img src="https://camo.githubusercontent.com/20c6209744d15728e1833e57aded8ffdda9122e22849b9a523aa16ee0168b88a/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f362f36352f422d747265652e7376672f38333170782d422d747265652e7376672e706e67" width="400px" height="111px" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/B-tree.svg/831px-B-tree.svg.png" style="max-width: 100%;"></a></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/trees/btree"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">tree</span> <span class="pl-c1">:=</span> <span class="pl-s1">btree</span>.<span class="pl-en">NewWithIntComparator</span>(<span class="pl-c1">3</span>) <span class="pl-c">// empty (keys are of type int)</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"x"</span>) <span class="pl-c">// 1-&gt;x</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">2</span>, <span class="pl-s">"b"</span>) <span class="pl-c">// 1-&gt;x, 2-&gt;b (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">1</span>, <span class="pl-s">"a"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b (in order, replacement)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">3</span>, <span class="pl-s">"c"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">4</span>, <span class="pl-s">"d"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">5</span>, <span class="pl-s">"e"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d, 5-&gt;e (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">6</span>, <span class="pl-s">"f"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d, 5-&gt;e, 6-&gt;f (in order)</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Put</span>(<span class="pl-c1">7</span>, <span class="pl-s">"g"</span>) <span class="pl-c">// 1-&gt;a, 2-&gt;b, 3-&gt;c, 4-&gt;d, 5-&gt;e, 6-&gt;f, 7-&gt;g (in order)</span>

	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">tree</span>)
	<span class="pl-c">// BTree</span>
	<span class="pl-c">//         1</span>
	<span class="pl-c">//     2</span>
	<span class="pl-c">//         3</span>
	<span class="pl-c">// 4</span>
	<span class="pl-c">//         5</span>
	<span class="pl-c">//     6</span>
	<span class="pl-c">//         7</span>

	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Values</span>() <span class="pl-c">// []interface {}{"a", "b", "c", "d", "e", "f", "g"} (in order)</span>
	<span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Keys</span>()   <span class="pl-c">// []interface {}{1, 2, 3, 4, 5, 6, 7} (in order)</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Remove</span>(<span class="pl-c1">2</span>) <span class="pl-c">// 1-&gt;a, 3-&gt;c, 4-&gt;d, 5-&gt;e, 6-&gt;f, 7-&gt;g (in order)</span>
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">tree</span>)
	<span class="pl-c">// BTree</span>
	<span class="pl-c">//     1</span>
	<span class="pl-c">//     3</span>
	<span class="pl-c">// 4</span>
	<span class="pl-c">//     5</span>
	<span class="pl-c">// 6</span>
	<span class="pl-c">//     7</span>

	<span class="pl-s1">tree</span>.<span class="pl-en">Clear</span>() <span class="pl-c">// empty</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Empty</span>() <span class="pl-c">// true</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Size</span>()  <span class="pl-c">// 0</span>

	<span class="pl-c">// Other:</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Height</span>() <span class="pl-c">// gets the height of the tree</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Left</span>() <span class="pl-c">// gets the left-most (min) node</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">LeftKey</span>() <span class="pl-c">// get the left-most (min) node's key</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">LeftValue</span>() <span class="pl-c">// get the left-most (min) node's value</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">Right</span>() <span class="pl-c">// get the right-most (max) node</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">RightKey</span>() <span class="pl-c">// get the right-most (max) node's key</span>
	<span class="pl-s1">tree</span>.<span class="pl-en">RightValue</span>() <span class="pl-c">// get the right-most (max) node's value</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/trees/btree&quot;
)

func main() {
	tree := btree.NewWithIntComparator(3) // empty (keys are of type int)

	tree.Put(1, &quot;x&quot;) // 1->x
	tree.Put(2, &quot;b&quot;) // 1->x, 2->b (in order)
	tree.Put(1, &quot;a&quot;) // 1->a, 2->b (in order, replacement)
	tree.Put(3, &quot;c&quot;) // 1->a, 2->b, 3->c (in order)
	tree.Put(4, &quot;d&quot;) // 1->a, 2->b, 3->c, 4->d (in order)
	tree.Put(5, &quot;e&quot;) // 1->a, 2->b, 3->c, 4->d, 5->e (in order)
	tree.Put(6, &quot;f&quot;) // 1->a, 2->b, 3->c, 4->d, 5->e, 6->f (in order)
	tree.Put(7, &quot;g&quot;) // 1->a, 2->b, 3->c, 4->d, 5->e, 6->f, 7->g (in order)

	fmt.Println(tree)
	// BTree
	//         1
	//     2
	//         3
	// 4
	//         5
	//     6
	//         7

	_ = tree.Values() // []interface {}{&quot;a&quot;, &quot;b&quot;, &quot;c&quot;, &quot;d&quot;, &quot;e&quot;, &quot;f&quot;, &quot;g&quot;} (in order)
	_ = tree.Keys()   // []interface {}{1, 2, 3, 4, 5, 6, 7} (in order)

	tree.Remove(2) // 1->a, 3->c, 4->d, 5->e, 6->f, 7->g (in order)
	fmt.Println(tree)
	// BTree
	//     1
	//     3
	// 4
	//     5
	// 6
	//     7

	tree.Clear() // empty
	tree.Empty() // true
	tree.Size()  // 0

	// Other:
	tree.Height() // gets the height of the tree
	tree.Left() // gets the left-most (min) node
	tree.LeftKey() // get the left-most (min) node's key
	tree.LeftValue() // get the left-most (min) node's value
	tree.Right() // get the right-most (max) node
	tree.RightKey() // get the right-most (max) node's key
	tree.RightValue() // get the right-most (max) node's value
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-binaryheap" class="anchor" aria-hidden="true" tabindex="-1" href="#binaryheap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二叉堆</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二叉堆是</font><font style="vertical-align: inherit;">使用二叉树创建的</font></font><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">树。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它可以被视为具有两个附加约束的二叉树：</font></font></p>
<ul dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">形状属性：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">二叉堆是一棵完全二叉树；</font><font style="vertical-align: inherit;">也就是说，树的所有级别（可能除了最后一层（最深的）之外）都已完全填充，并且如果树的最后一层未完成，则从左到右填充该级别的节点。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">堆属性：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据为堆定义的比较谓词，所有节点都大于或等于或小于或等于其每个子节点。</font></font><sub><sup><a href="http://en.wikipedia.org/wiki/Binary_heap" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">维基百科</font></font></a></sup></sub></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#trees"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tree</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#reverseiteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/e69ae617fceb4855289cda1499a41c35c11576881253318e2655753305f0a78a/687474703a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f332f33382f4d61782d486561702e7376672f35303170782d4d61782d486561702e7376672e706e67"><img src="https://camo.githubusercontent.com/e69ae617fceb4855289cda1499a41c35c11576881253318e2655753305f0a78a/687474703a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f332f33382f4d61782d486561702e7376672f35303170782d4d61782d486561702e7376672e706e67" width="300px" height="200px" data-canonical-src="http://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Max-Heap.svg/501px-Max-Heap.svg.png" style="max-width: 100%;"></a></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"github.com/emirpasic/gods/trees/binaryheap"</span>
	<span class="pl-s">"github.com/emirpasic/gods/utils"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {

	<span class="pl-c">// Min-heap</span>
	<span class="pl-s1">heap</span> <span class="pl-c1">:=</span> <span class="pl-s1">binaryheap</span>.<span class="pl-en">NewWithIntComparator</span>() <span class="pl-c">// empty (min-heap)</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Push</span>(<span class="pl-c1">2</span>)                              <span class="pl-c">// 2</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Push</span>(<span class="pl-c1">3</span>)                              <span class="pl-c">// 2, 3</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Push</span>(<span class="pl-c1">1</span>)                              <span class="pl-c">// 1, 3, 2</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Values</span>()                             <span class="pl-c">// 1, 3, 2</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">heap</span>.<span class="pl-en">Peek</span>()                        <span class="pl-c">// 1,true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">heap</span>.<span class="pl-en">Pop</span>()                         <span class="pl-c">// 1, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">heap</span>.<span class="pl-en">Pop</span>()                         <span class="pl-c">// 2, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">heap</span>.<span class="pl-en">Pop</span>()                         <span class="pl-c">// 3, true</span>
	<span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">heap</span>.<span class="pl-en">Pop</span>()                         <span class="pl-c">// nil, false (nothing to pop)</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Push</span>(<span class="pl-c1">1</span>)                              <span class="pl-c">// 1</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Clear</span>()                              <span class="pl-c">// empty</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Empty</span>()                              <span class="pl-c">// true</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Size</span>()                               <span class="pl-c">// 0</span>

	<span class="pl-c">// Max-heap</span>
	<span class="pl-s1">inverseIntComparator</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span> {
		<span class="pl-k">return</span> <span class="pl-c1">-</span><span class="pl-s1">utils</span>.<span class="pl-en">IntComparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span>)
	}
	<span class="pl-s1">heap</span> <span class="pl-c1">=</span> <span class="pl-s1">binaryheap</span>.<span class="pl-en">NewWith</span>(<span class="pl-s1">inverseIntComparator</span>) <span class="pl-c">// empty (min-heap)</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Push</span>(<span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">1</span>)                              <span class="pl-c">// 3, 2, 1 (bulk optimized)</span>
	<span class="pl-s1">heap</span>.<span class="pl-en">Values</span>()                                   <span class="pl-c">// 3, 2, 1</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;github.com/emirpasic/gods/trees/binaryheap&quot;
	&quot;github.com/emirpasic/gods/utils&quot;
)

func main() {

	// Min-heap
	heap := binaryheap.NewWithIntComparator() // empty (min-heap)
	heap.Push(2)                              // 2
	heap.Push(3)                              // 2, 3
	heap.Push(1)                              // 1, 3, 2
	heap.Values()                             // 1, 3, 2
	_, _ = heap.Peek()                        // 1,true
	_, _ = heap.Pop()                         // 1, true
	_, _ = heap.Pop()                         // 2, true
	_, _ = heap.Pop()                         // 3, true
	_, _ = heap.Pop()                         // nil, false (nothing to pop)
	heap.Push(1)                              // 1
	heap.Clear()                              // empty
	heap.Empty()                              // true
	heap.Size()                               // 0

	// Max-heap
	inverseIntComparator := func(a, b interface{}) int {
		return -utils.IntComparator(a, b)
	}
	heap = binaryheap.NewWith(inverseIntComparator) // empty (min-heap)
	heap.Push(2, 3, 1)                              // 3, 2, 1 (bulk optimized)
	heap.Values()                                   // 3, 2, 1
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-queues" class="anchor" aria-hidden="true" tabindex="-1" href="#queues"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">队列</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">表示先进先出 (FIFO) 数据结构的队列。</font><font style="vertical-align: inherit;">提供了常用的入队和出队操作，以及查看队列中第一项的方法。</font></font></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/a1c137ec6b46a0ada5870c86efeb33ccc545aa18465880fac994ad3fd7aa6aaa/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f352f35322f446174615f51756575652e7376672f33303070782d446174615f51756575652e7376672e706e67"><img src="https://camo.githubusercontent.com/a1c137ec6b46a0ada5870c86efeb33ccc545aa18465880fac994ad3fd7aa6aaa/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f352f35322f446174615f51756575652e7376672f33303070782d446174615f51756575652e7376672e706e67" width="200px" height="120px" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Data_Queue.svg/300px-Data_Queue.svg.png" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#containers"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">Queue</span> <span class="pl-k">interface</span> {
	<span class="pl-c1">Enqueue</span>(<span class="pl-s1">value</span> <span class="pl-k">interface</span>{})
	<span class="pl-c1">Dequeue</span>() (<span class="pl-s1">value</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">ok</span> <span class="pl-smi">bool</span>)
	<span class="pl-c1">Peek</span>() (<span class="pl-s1">value</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">ok</span> <span class="pl-smi">bool</span>)

	containers.<span class="pl-smi">Container</span>
	<span class="pl-c">// Empty() bool</span>
	<span class="pl-c">// Size() int</span>
	<span class="pl-c">// Clear()</span>
	<span class="pl-c">// Values() []interface{}</span>
	<span class="pl-c">// String() string</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type Queue interface {
	Enqueue(value interface{})
	Dequeue() (value interface{}, ok bool)
	Peek() (value interface{}, ok bool)

	containers.Container
	// Empty() bool
	// Size() int
	// Clear()
	// Values() []interface{}
	// String() string
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-linkedlistqueue" class="anchor" aria-hidden="true" tabindex="-1" href="#linkedlistqueue"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链表队列</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于</font><a href="#singlylinkedlist"><font style="vertical-align: inherit;">链表</font></a></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">队列</font><font style="vertical-align: inherit;">。</font></font><a href="#singlylinkedlist"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Queue</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> llq <span class="pl-s">"github.com/emirpasic/gods/queues/linkedlistqueue"</span>

<span class="pl-c">// LinkedListQueueExample to demonstrate basic usage of LinkedListQueue</span>
<span class="pl-k">func</span> <span class="pl-en">main</span>() {
    <span class="pl-s1">queue</span> <span class="pl-c1">:=</span> <span class="pl-s1">llq</span>.<span class="pl-en">New</span>()     <span class="pl-c">// empty</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">2</span>)       <span class="pl-c">// 1, 2</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Values</span>()     <span class="pl-c">// 1, 2 (FIFO order)</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Peek</span>()    <span class="pl-c">// 1,true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// 1, true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// 2, true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// nil, false (nothing to deque)</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Clear</span>()          <span class="pl-c">// empty</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Empty</span>()          <span class="pl-c">// true</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Size</span>()       <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import llq &quot;github.com/emirpasic/gods/queues/linkedlistqueue&quot;

// LinkedListQueueExample to demonstrate basic usage of LinkedListQueue
func main() {
    queue := llq.New()     // empty
    queue.Enqueue(1)       // 1
    queue.Enqueue(2)       // 1, 2
    _ = queue.Values()     // 1, 2 (FIFO order)
    _, _ = queue.Peek()    // 1,true
    _, _ = queue.Dequeue() // 1, true
    _, _ = queue.Dequeue() // 2, true
    _, _ = queue.Dequeue() // nil, false (nothing to deque)
    queue.Enqueue(1)       // 1
    queue.Clear()          // empty
    queue.Empty()          // true
    _ = queue.Size()       // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-arrayqueue" class="anchor" aria-hidden="true" tabindex="-1" href="#arrayqueue"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">数组队列</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于</font><a href="#arraylist"><font style="vertical-align: inherit;">数组列表</font></a></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">队列</font><font style="vertical-align: inherit;">。</font></font><a href="#arraylist"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Queue</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> aq <span class="pl-s">"github.com/emirpasic/gods/queues/arrayqueue"</span>

<span class="pl-c">// ArrayQueueExample to demonstrate basic usage of ArrayQueue</span>
<span class="pl-k">func</span> <span class="pl-en">main</span>() {
    <span class="pl-s1">queue</span> <span class="pl-c1">:=</span> <span class="pl-s1">aq</span>.<span class="pl-en">New</span>()      <span class="pl-c">// empty</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">2</span>)       <span class="pl-c">// 1, 2</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Values</span>()     <span class="pl-c">// 1, 2 (FIFO order)</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Peek</span>()    <span class="pl-c">// 1,true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// 1, true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// 2, true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// nil, false (nothing to deque)</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Clear</span>()          <span class="pl-c">// empty</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Empty</span>()          <span class="pl-c">// true</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Size</span>()       <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import aq &quot;github.com/emirpasic/gods/queues/arrayqueue&quot;

// ArrayQueueExample to demonstrate basic usage of ArrayQueue
func main() {
    queue := aq.New()      // empty
    queue.Enqueue(1)       // 1
    queue.Enqueue(2)       // 1, 2
    _ = queue.Values()     // 1, 2 (FIFO order)
    _, _ = queue.Peek()    // 1,true
    _, _ = queue.Dequeue() // 1, true
    _, _ = queue.Dequeue() // 2, true
    _, _ = queue.Dequeue() // nil, false (nothing to deque)
    queue.Enqueue(1)       // 1
    queue.Clear()          // empty
    queue.Empty()          // true
    _ = queue.Size()       // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-circularbuffer" class="anchor" aria-hidden="true" tabindex="-1" href="#circularbuffer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">循环缓冲区</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">循环缓冲区、循环</font></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">队列</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、循环缓冲区或环形缓冲区是一种使用单个固定大小缓冲区的数据结构，就好像它是端到端连接的一样。</font><font style="vertical-align: inherit;">这种结构很容易缓冲数据流。</font></font></p>
<p align="center" dir="auto"><animated-image data-catalyst="" style="width: 300px;"><a target="_blank" rel="noopener noreferrer nofollow" href="https://camo.githubusercontent.com/846b014c84436d35a62ca91add4a69e78b097ece07719ed76c486e811fd492db/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966" data-target="animated-image.originalLink"><img src="https://camo.githubusercontent.com/846b014c84436d35a62ca91add4a69e78b097ece07719ed76c486e811fd492db/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966" height="300px" data-canonical-src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/Circular_Buffer_Animation.gif/400px-Circular_Buffer_Animation.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://camo.githubusercontent.com/846b014c84436d35a62ca91add4a69e78b097ece07719ed76c486e811fd492db/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966" class="AnimatedImagePlayer-animatedImage" src="https://camo.githubusercontent.com/846b014c84436d35a62ca91add4a69e78b097ece07719ed76c486e811fd492db/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966" height="300px" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="300" height="300"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play 68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play 68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open 68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966 in new window" class="AnimatedImagePlayer-button" href="https://camo.githubusercontent.com/846b014c84436d35a62ca91add4a69e78b097ece07719ed76c486e811fd492db/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f7468756d622f662f66642f43697263756c61725f4275666665725f416e696d6174696f6e2e6769662f34303070782d43697263756c61725f4275666665725f416e696d6174696f6e2e676966" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Queue</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> cb <span class="pl-s">"github.com/emirpasic/gods/queues/circularbuffer"</span>

<span class="pl-c">// CircularBufferExample to demonstrate basic usage of CircularBuffer</span>
<span class="pl-k">func</span> <span class="pl-en">main</span>() {
    <span class="pl-s1">queue</span> <span class="pl-c1">:=</span> <span class="pl-s1">cb</span>.<span class="pl-en">New</span>(<span class="pl-c1">3</span>)     <span class="pl-c">// empty (max size is 3)</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">2</span>)       <span class="pl-c">// 1, 2</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">3</span>)       <span class="pl-c">// 1, 2, 3</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Values</span>()     <span class="pl-c">// 1, 2, 3</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">3</span>)       <span class="pl-c">// 4, 2, 3</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Peek</span>()    <span class="pl-c">// 4,true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// 4, true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// 2, true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// 3, true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>() <span class="pl-c">// nil, false (nothing to deque)</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-c1">1</span>)       <span class="pl-c">// 1</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Clear</span>()          <span class="pl-c">// empty</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Empty</span>()          <span class="pl-c">// true</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Size</span>()       <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import cb &quot;github.com/emirpasic/gods/queues/circularbuffer&quot;

// CircularBufferExample to demonstrate basic usage of CircularBuffer
func main() {
    queue := cb.New(3)     // empty (max size is 3)
    queue.Enqueue(1)       // 1
    queue.Enqueue(2)       // 1, 2
    queue.Enqueue(3)       // 1, 2, 3
    _ = queue.Values()     // 1, 2, 3
    queue.Enqueue(3)       // 4, 2, 3
    _, _ = queue.Peek()    // 4,true
    _, _ = queue.Dequeue() // 4, true
    _, _ = queue.Dequeue() // 2, true
    _, _ = queue.Dequeue() // 3, true
    _, _ = queue.Dequeue() // nil, false (nothing to deque)
    queue.Enqueue(1)       // 1
    queue.Clear()          // empty
    queue.Empty()          // true
    _ = queue.Size()       // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-priorityqueue" class="anchor" aria-hidden="true" tabindex="-1" href="#priorityqueue"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优先队列</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">优先级队列是一种特殊类型的</font></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">队列</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，其中每个元素都与一个优先级值相关联。</font><font style="vertical-align: inherit;">并且，元素是根据其优先级提供服务的。</font><font style="vertical-align: inherit;">也就是说，优先级较高的元素首先得到服务。</font><font style="vertical-align: inherit;">但是，如果出现具有相同优先级的元素，则按照它们在队列中的顺序提供服务。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">实现</font></font><a href="#queues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Queue</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ReverseIteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="#jsonserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONSerializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="#jsondeserializer"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSONDeserializer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
  pq <span class="pl-s">"github.com/emirpasic/gods/queues/priorityqueue"</span>
  <span class="pl-s">"github.com/emirpasic/gods/utils"</span>
)

<span class="pl-c">// Element is an entry in the priority queue</span>
<span class="pl-k">type</span> <span class="pl-smi">Element</span> <span class="pl-k">struct</span> {
    <span class="pl-c1">name</span>     <span class="pl-smi">string</span>
    <span class="pl-c1">priority</span> <span class="pl-smi">int</span>
}

<span class="pl-c">// Comparator function (sort by element's priority value in descending order)</span>
<span class="pl-k">func</span> <span class="pl-en">byPriority</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span> {
    <span class="pl-s1">priorityA</span> <span class="pl-c1">:=</span> <span class="pl-s1">a</span>.(<span class="pl-smi">Element</span>).<span class="pl-c1">priority</span>
    <span class="pl-s1">priorityB</span> <span class="pl-c1">:=</span> <span class="pl-s1">b</span>.(<span class="pl-smi">Element</span>).<span class="pl-c1">priority</span>
    <span class="pl-k">return</span> <span class="pl-c1">-</span><span class="pl-s1">utils</span>.<span class="pl-en">IntComparator</span>(<span class="pl-s1">priorityA</span>, <span class="pl-s1">priorityB</span>) <span class="pl-c">// "-" descending order</span>
}

<span class="pl-c">// PriorityQueueExample to demonstrate basic usage of BinaryHeap</span>
<span class="pl-k">func</span> <span class="pl-en">main</span>() {
    <span class="pl-s1">a</span> <span class="pl-c1">:=</span> <span class="pl-smi">Element</span>{<span class="pl-c1">name</span>: <span class="pl-s">"a"</span>, <span class="pl-c1">priority</span>: <span class="pl-c1">1</span>}
    <span class="pl-s1">b</span> <span class="pl-c1">:=</span> <span class="pl-smi">Element</span>{<span class="pl-c1">name</span>: <span class="pl-s">"b"</span>, <span class="pl-c1">priority</span>: <span class="pl-c1">2</span>}
    <span class="pl-s1">c</span> <span class="pl-c1">:=</span> <span class="pl-smi">Element</span>{<span class="pl-c1">name</span>: <span class="pl-s">"c"</span>, <span class="pl-c1">priority</span>: <span class="pl-c1">3</span>}
    
    <span class="pl-s1">queue</span> <span class="pl-c1">:=</span> <span class="pl-s1">pq</span>.<span class="pl-en">NewWith</span>(<span class="pl-s1">byPriority</span>) <span class="pl-c">// empty</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-s1">a</span>)                <span class="pl-c">// {a 1}</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-s1">c</span>)                <span class="pl-c">// {c 3}, {a 1}</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Enqueue</span>(<span class="pl-s1">b</span>)                <span class="pl-c">// {c 3}, {b 2}, {a 1}</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Values</span>()              <span class="pl-c">// [{c 3} {b 2} {a 1}]</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Peek</span>()             <span class="pl-c">// {c 3} true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>()          <span class="pl-c">// {c 3} true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>()          <span class="pl-c">// {b 2} true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>()          <span class="pl-c">// {a 1} true</span>
    <span class="pl-s1">_</span>, <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Dequeue</span>()          <span class="pl-c">// &lt;nil&gt; false (nothing to dequeue)</span>
    <span class="pl-s1">queue</span>.<span class="pl-en">Clear</span>()                   <span class="pl-c">// empty</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Empty</span>()               <span class="pl-c">// true</span>
    <span class="pl-s1">_</span> <span class="pl-c1">=</span> <span class="pl-s1">queue</span>.<span class="pl-en">Size</span>()                <span class="pl-c">// 0</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
  pq &quot;github.com/emirpasic/gods/queues/priorityqueue&quot;
  &quot;github.com/emirpasic/gods/utils&quot;
)

// Element is an entry in the priority queue
type Element struct {
    name     string
    priority int
}

// Comparator function (sort by element's priority value in descending order)
func byPriority(a, b interface{}) int {
    priorityA := a.(Element).priority
    priorityB := b.(Element).priority
    return -utils.IntComparator(priorityA, priorityB) // &quot;-&quot; descending order
}

// PriorityQueueExample to demonstrate basic usage of BinaryHeap
func main() {
    a := Element{name: &quot;a&quot;, priority: 1}
    b := Element{name: &quot;b&quot;, priority: 2}
    c := Element{name: &quot;c&quot;, priority: 3}
    
    queue := pq.NewWith(byPriority) // empty
    queue.Enqueue(a)                // {a 1}
    queue.Enqueue(c)                // {c 3}, {a 1}
    queue.Enqueue(b)                // {c 3}, {b 2}, {a 1}
    _ = queue.Values()              // [{c 3} {b 2} {a 1}]
    _, _ = queue.Peek()             // {c 3} true
    _, _ = queue.Dequeue()          // {c 3} true
    _, _ = queue.Dequeue()          // {b 2} true
    _, _ = queue.Dequeue()          // {a 1} true
    _, _ = queue.Dequeue()          // <nil> false (nothing to dequeue)
    queue.Clear()                   // empty
    _ = queue.Empty()               // true
    _ = queue.Size()                // 0
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-functions" class="anchor" aria-hidden="true" tabindex="-1" href="#functions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">功能</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">整个库中使用的各种辅助函数。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-comparator" class="anchor" aria-hidden="true" tabindex="-1" href="#comparator"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比较器</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">某些数据结构（例如 TreeMap、TreeSet）需要比较器函数来自动保持其元素在插入时排序。</font><font style="vertical-align: inherit;">该比较器在初始化期间是必需的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比较器定义为：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">返回值（整数）：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">negative</span> , <span class="pl-s1">if</span> <span class="pl-s1">a</span> <span class="pl-c1">&lt;</span> <span class="pl-s1">b</span>
<span class="pl-s1">zero</span>     , <span class="pl-s1">if</span> <span class="pl-s1">a</span> <span class="pl-c1">==</span> <span class="pl-s1">b</span>
<span class="pl-s1">positive</span> , <span class="pl-s1">if</span> <span class="pl-s1">a</span> <span class="pl-c1">&gt;</span> <span class="pl-s1">b</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="negative , if a < b
zero     , if a == b
positive , if a > b" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">比较器签名：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">type</span> <span class="pl-smi">Comparator</span> <span class="pl-k">func</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="type Comparator func(a, b interface{}) int" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内置类型的所有常见比较器都包含在库中：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">func</span> <span class="pl-en">StringComparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">IntComparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">Int8Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">Int16Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">Int32Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">Int64Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">UIntComparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">UInt8Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">UInt16Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">UInt32Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">UInt64Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">Float32Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">Float64Comparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">ByteComparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">RuneComparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span>

<span class="pl-k">func</span> <span class="pl-en">TimeComparator</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="func StringComparator(a, b interface{}) int

func IntComparator(a, b interface{}) int

func Int8Comparator(a, b interface{}) int

func Int16Comparator(a, b interface{}) int

func Int32Comparator(a, b interface{}) int

func Int64Comparator(a, b interface{}) int

func UIntComparator(a, b interface{}) int

func UInt8Comparator(a, b interface{}) int

func UInt16Comparator(a, b interface{}) int

func UInt32Comparator(a, b interface{}) int

func UInt64Comparator(a, b interface{}) int

func Float32Comparator(a, b interface{}) int

func Float64Comparator(a, b interface{}) int

func ByteComparator(a, b interface{}) int

func RuneComparator(a, b interface{}) int

func TimeComparator(a, b interface{}) int" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编写自定义比较器很容易：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/sets/treeset"</span>
)

<span class="pl-k">type</span> <span class="pl-smi">User</span> <span class="pl-k">struct</span> {
	<span class="pl-c1">id</span>   <span class="pl-smi">int</span>
	<span class="pl-c1">name</span> <span class="pl-smi">string</span>
}

<span class="pl-c">// Custom comparator (sort by IDs)</span>
<span class="pl-k">func</span> <span class="pl-en">byID</span>(<span class="pl-s1">a</span>, <span class="pl-s1">b</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">int</span> {

	<span class="pl-c">// Type assertion, program will panic if this is not respected</span>
	<span class="pl-s1">c1</span> <span class="pl-c1">:=</span> <span class="pl-s1">a</span>.(<span class="pl-smi">User</span>)
	<span class="pl-s1">c2</span> <span class="pl-c1">:=</span> <span class="pl-s1">b</span>.(<span class="pl-smi">User</span>)

	<span class="pl-k">switch</span> {
	<span class="pl-k">case</span> <span class="pl-s1">c1</span>.<span class="pl-c1">id</span> <span class="pl-c1">&gt;</span> <span class="pl-s1">c2</span>.<span class="pl-c1">id</span>:
		<span class="pl-k">return</span> <span class="pl-c1">1</span>
	<span class="pl-k">case</span> <span class="pl-s1">c1</span>.<span class="pl-c1">id</span> <span class="pl-c1">&lt;</span> <span class="pl-s1">c2</span>.<span class="pl-c1">id</span>:
		<span class="pl-k">return</span> <span class="pl-c1">-</span><span class="pl-c1">1</span>
	<span class="pl-k">default</span>:
		<span class="pl-k">return</span> <span class="pl-c1">0</span>
	}
}

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">set</span> <span class="pl-c1">:=</span> <span class="pl-s1">treeset</span>.<span class="pl-en">NewWith</span>(<span class="pl-s1">byID</span>)

	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-smi">User</span>{<span class="pl-c1">2</span>, <span class="pl-s">"Second"</span>})
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-smi">User</span>{<span class="pl-c1">3</span>, <span class="pl-s">"Third"</span>})
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-smi">User</span>{<span class="pl-c1">1</span>, <span class="pl-s">"First"</span>})
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-smi">User</span>{<span class="pl-c1">4</span>, <span class="pl-s">"Fourth"</span>})

	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">set</span>) <span class="pl-c">// {1 First}, {2 Second}, {3 Third}, {4 Fourth}</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/sets/treeset&quot;
)

type User struct {
	id   int
	name string
}

// Custom comparator (sort by IDs)
func byID(a, b interface{}) int {

	// Type assertion, program will panic if this is not respected
	c1 := a.(User)
	c2 := b.(User)

	switch {
	case c1.id > c2.id:
		return 1
	case c1.id < c2.id:
		return -1
	default:
		return 0
	}
}

func main() {
	set := treeset.NewWith(byID)

	set.Add(User{2, &quot;Second&quot;})
	set.Add(User{3, &quot;Third&quot;})
	set.Add(User{1, &quot;First&quot;})
	set.Add(User{4, &quot;Fourth&quot;})

	fmt.Println(set) // {1 First}, {2 Second}, {3 Third}, {4 Fourth}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-iterator" class="anchor" aria-hidden="true" tabindex="-1" href="#iterator"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">迭代器</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有有序容器都有状态迭代器。</font><font style="vertical-align: inherit;">通常，迭代器是通过</font><font style="vertical-align: inherit;">有序容器的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Iterator()函数获得的。</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获得后，迭代器的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Next()</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数将迭代器移动到下一个元素，如果存在下一个元素，则返回 true。</font><font style="vertical-align: inherit;">如果有元素，则可以通过迭代器的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Value()</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数获取该元素。</font><font style="vertical-align: inherit;">根据排序类型，它的位置可以通过迭代器的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Index()</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Key()</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数获得。</font><font style="vertical-align: inherit;">有些容器甚至提供可逆迭代器，本质上是相同的，但提供另一个额外的</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Prev()</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数，该函数将迭代器移动到前一个元素，如果存在前一个元素，则返回 true。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：迭代时从容器中删除元素是不安全的。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-iteratorwithindex" class="anchor" aria-hidden="true" tabindex="-1" href="#iteratorwithindex"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带索引的迭代器</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其元素由索引引用的</font><font style="vertical-align: inherit;">迭代</font></font><a href="#iterator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">器。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">it</span> <span class="pl-c1">:=</span> <span class="pl-s1">list</span>.<span class="pl-en">Iterator</span>()
<span class="pl-k">for</span> <span class="pl-s1">it</span>.<span class="pl-en">Next</span>() {
	<span class="pl-s1">index</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Index</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="it := list.Iterator()
for it.Next() {
	index, value := it.Index(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他用途：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">if</span> <span class="pl-s1">it</span>.<span class="pl-en">First</span>() {
	<span class="pl-s1">firstIndex</span>, <span class="pl-s1">firstValue</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Index</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="if it.First() {
	firstIndex, firstValue := it.Index(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">for</span> <span class="pl-s1">it</span>.<span class="pl-en">Begin</span>(); <span class="pl-s1">it</span>.<span class="pl-en">Next</span>(); {
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="for it.Begin(); it.Next(); {
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻找特定元素：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">// Seek function, i.e. find element starting with "b"</span>
<span class="pl-s1">seek</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
    <span class="pl-k">return</span> <span class="pl-s1">strings</span>.<span class="pl-en">HasSuffix</span>(<span class="pl-s1">value</span>.(<span class="pl-smi">string</span>), <span class="pl-s">"b"</span>)
}

<span class="pl-c">// Seek to the condition and continue traversal from that point (forward).</span>
<span class="pl-c">// assumes it.Begin() was called.</span>
<span class="pl-k">for</span> <span class="pl-s1">found</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">NextTo</span>(<span class="pl-s1">seek</span>); <span class="pl-s1">found</span>; <span class="pl-s1">found</span> <span class="pl-c1">=</span> <span class="pl-s1">it</span>.<span class="pl-en">Next</span>() {
    <span class="pl-s1">index</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Index</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
    <span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Seek function, i.e. find element starting with &quot;b&quot;
seek := func(index int, value interface{}) bool {
    return strings.HasSuffix(value.(string), &quot;b&quot;)
}

// Seek to the condition and continue traversal from that point (forward).
// assumes it.Begin() was called.
for found := it.NextTo(seek); found; found = it.Next() {
    index, value := it.Index(), it.Value()
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-iteratorwithkey" class="anchor" aria-hidden="true" tabindex="-1" href="#iteratorwithkey"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带键迭代器</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其元素由键引用的</font><font style="vertical-align: inherit;">迭代</font></font><a href="#iterator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">器。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">it</span> <span class="pl-c1">:=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Iterator</span>()
<span class="pl-k">for</span> <span class="pl-s1">it</span>.<span class="pl-en">Next</span>() {
	<span class="pl-s1">key</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Key</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="it := tree.Iterator()
for it.Next() {
	key, value := it.Key(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他用途：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">if</span> <span class="pl-s1">it</span>.<span class="pl-en">First</span>() {
	<span class="pl-s1">firstKey</span>, <span class="pl-s1">firstValue</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Key</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="if it.First() {
	firstKey, firstValue := it.Key(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">for</span> <span class="pl-s1">it</span>.<span class="pl-en">Begin</span>(); <span class="pl-s1">it</span>.<span class="pl-en">Next</span>(); {
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="for it.Begin(); it.Next(); {
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从当前迭代器位置查找特定元素：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">// Seek function, i.e. find element starting with "b"</span>
<span class="pl-s1">seek</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
    <span class="pl-k">return</span> <span class="pl-s1">strings</span>.<span class="pl-en">HasSuffix</span>(<span class="pl-s1">value</span>.(<span class="pl-smi">string</span>), <span class="pl-s">"b"</span>)
}

<span class="pl-c">// Seek to the condition and continue traversal from that point (forward).</span>
<span class="pl-c">// assumes it.Begin() was called.</span>
<span class="pl-k">for</span> <span class="pl-s1">found</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">NextTo</span>(<span class="pl-s1">seek</span>); <span class="pl-s1">found</span>; <span class="pl-s1">found</span> <span class="pl-c1">=</span> <span class="pl-s1">it</span>.<span class="pl-en">Next</span>() {
    <span class="pl-s1">key</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Key</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
    <span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Seek function, i.e. find element starting with &quot;b&quot;
seek := func(key interface{}, value interface{}) bool {
    return strings.HasSuffix(value.(string), &quot;b&quot;)
}

// Seek to the condition and continue traversal from that point (forward).
// assumes it.Begin() was called.
for found := it.NextTo(seek); found; found = it.Next() {
    key, value := it.Key(), it.Value()
    ...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-reverseiteratorwithindex" class="anchor" aria-hidden="true" tabindex="-1" href="#reverseiteratorwithindex"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带索引的反向迭代器</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其元素由索引引用的</font><font style="vertical-align: inherit;">迭代</font></font><a href="#iterator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">器。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供所有函数为</font></font><a href="#iteratorwithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IteratorWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但也可用于反向迭代。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反向迭代的典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">it</span> <span class="pl-c1">:=</span> <span class="pl-s1">list</span>.<span class="pl-en">Iterator</span>()
<span class="pl-k">for</span> <span class="pl-s1">it</span>.<span class="pl-en">End</span>(); <span class="pl-s1">it</span>.<span class="pl-en">Prev</span>(); {
	<span class="pl-s1">index</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Index</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="it := list.Iterator()
for it.End(); it.Prev(); {
	index, value := it.Index(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他用途：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">if</span> <span class="pl-s1">it</span>.<span class="pl-en">Last</span>() {
	<span class="pl-s1">lastIndex</span>, <span class="pl-s1">lastValue</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Index</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="if it.Last() {
	lastIndex, lastValue := it.Index(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻找特定元素：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">// Seek function, i.e. find element starting with "b"</span>
<span class="pl-s1">seek</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
    <span class="pl-k">return</span> <span class="pl-s1">strings</span>.<span class="pl-en">HasSuffix</span>(<span class="pl-s1">value</span>.(<span class="pl-smi">string</span>), <span class="pl-s">"b"</span>)
}

<span class="pl-c">// Seek to the condition and continue traversal from that point (in reverse).</span>
<span class="pl-c">// assumes it.End() was called.</span>
<span class="pl-k">for</span> <span class="pl-s1">found</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">PrevTo</span>(<span class="pl-s1">seek</span>); <span class="pl-s1">found</span>; <span class="pl-s1">found</span> <span class="pl-c1">=</span> <span class="pl-s1">it</span>.<span class="pl-en">Prev</span>() {
    <span class="pl-s1">index</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Index</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Seek function, i.e. find element starting with &quot;b&quot;
seek := func(index int, value interface{}) bool {
    return strings.HasSuffix(value.(string), &quot;b&quot;)
}

// Seek to the condition and continue traversal from that point (in reverse).
// assumes it.End() was called.
for found := it.PrevTo(seek); found; found = it.Prev() {
    index, value := it.Index(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-reverseiteratorwithkey" class="anchor" aria-hidden="true" tabindex="-1" href="#reverseiteratorwithkey"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带键的反向迭代器</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其元素由键引用的</font><font style="vertical-align: inherit;">迭代</font></font><a href="#iterator"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">器。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供所有功能作为</font></font><a href="#iteratorwithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IteratorWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，但也可用于反向迭代。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">反向迭代的典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">it</span> <span class="pl-c1">:=</span> <span class="pl-s1">tree</span>.<span class="pl-en">Iterator</span>()
<span class="pl-k">for</span> <span class="pl-s1">it</span>.<span class="pl-en">End</span>(); <span class="pl-s1">it</span>.<span class="pl-en">Prev</span>(); {
	<span class="pl-s1">key</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Key</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="it := tree.Iterator()
for it.End(); it.Prev(); {
	key, value := it.Key(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他用途：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">if</span> <span class="pl-s1">it</span>.<span class="pl-en">Last</span>() {
	<span class="pl-s1">lastKey</span>, <span class="pl-s1">lastValue</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Key</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="if it.Last() {
	lastKey, lastValue := it.Key(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">// Seek function, i.e. find element starting with "b"</span>
<span class="pl-s1">seek</span> <span class="pl-c1">:=</span> <span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
    <span class="pl-k">return</span> <span class="pl-s1">strings</span>.<span class="pl-en">HasSuffix</span>(<span class="pl-s1">value</span>.(<span class="pl-smi">string</span>), <span class="pl-s">"b"</span>)
}

<span class="pl-c">// Seek to the condition and continue traversal from that point (in reverse).</span>
<span class="pl-c">// assumes it.End() was called.</span>
<span class="pl-k">for</span> <span class="pl-s1">found</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">PrevTo</span>(<span class="pl-s1">seek</span>); <span class="pl-s1">found</span>; <span class="pl-s1">found</span> <span class="pl-c1">=</span> <span class="pl-s1">it</span>.<span class="pl-en">Prev</span>() {
    <span class="pl-s1">key</span>, <span class="pl-s1">value</span> <span class="pl-c1">:=</span> <span class="pl-s1">it</span>.<span class="pl-en">Key</span>(), <span class="pl-s1">it</span>.<span class="pl-en">Value</span>()
	<span class="pl-c1">...</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Seek function, i.e. find element starting with &quot;b&quot;
seek := func(key interface{}, value interface{}) bool {
    return strings.HasSuffix(value.(string), &quot;b&quot;)
}

// Seek to the condition and continue traversal from that point (in reverse).
// assumes it.End() was called.
for found := it.PrevTo(seek); found; found = it.Prev() {
    key, value := it.Key(), it.Value()
	...
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-enumerable" class="anchor" aria-hidden="true" tabindex="-1" href="#enumerable"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可枚举</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于实现</font></font><a href="#enumerablewithindex"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithIndex</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="#enumerablewithkey"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">EnumerableWithKey</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">接口的有序容器的枚举函数。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-enumerablewithindex" class="anchor" aria-hidden="true" tabindex="-1" href="#enumerablewithindex"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带索引的枚举</font></font></h4>
<p dir="auto"><a href="#enumerable"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于有序容器的枚举</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数，其值可以通过索引获取。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为每个元素调用一次给定函数，并传递该元素的索引和值。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">Each</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}))</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Each(func(index int, value interface{}))" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地图</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为每个元素调用一次给定函数，并返回一个包含给定函数返回值的容器。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">Map</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-k">interface</span>{}) <span class="pl-s1">Container</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Map(func(index int, value interface{}) interface{}) Container" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">返回一个新容器，其中包含给定函数返回真值的所有元素。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">Select</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) <span class="pl-s1">Container</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Select(func(index int, value interface{}) bool) Container" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将容器的每个元素传递给给定函数，如果该函数对任何元素返回 true，则返回 true。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">Any</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) <span class="pl-s1">bool</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Any(func(index int, value interface{}) bool) bool" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将容器的每个元素传递给给定函数，如果该函数对所有元素都返回 true，则返回 true。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">All</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) <span class="pl-s1">bool</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="All(func(index int, value interface{}) bool) bool" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻找</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将容器的每个元素传递给给定函数，并返回该函数为 true 的第一个 (index,value) 或 -1,nil，否则如果没有元素匹配条件。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">Find</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) (<span class="pl-s1">int</span>, <span class="pl-k">interface</span>{})}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Find(func(index int, value interface{}) bool) (int, interface{})}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></strong></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/sets/treeset"</span>
)

<span class="pl-k">func</span> <span class="pl-en">printSet</span>(<span class="pl-s1">txt</span> <span class="pl-smi">string</span>, <span class="pl-s1">set</span> <span class="pl-c1">*</span>treeset.<span class="pl-smi">Set</span>) {
	<span class="pl-s1">fmt</span>.<span class="pl-en">Print</span>(<span class="pl-s1">txt</span>, <span class="pl-s">"[ "</span>)
	<span class="pl-s1">set</span>.<span class="pl-en">Each</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Print</span>(<span class="pl-s1">value</span>, <span class="pl-s">" "</span>)
	})
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"]"</span>)
}

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">set</span> <span class="pl-c1">:=</span> <span class="pl-s1">treeset</span>.<span class="pl-en">NewWithIntComparator</span>()
	<span class="pl-s1">set</span>.<span class="pl-en">Add</span>(<span class="pl-c1">2</span>, <span class="pl-c1">3</span>, <span class="pl-c1">4</span>, <span class="pl-c1">2</span>, <span class="pl-c1">5</span>, <span class="pl-c1">6</span>, <span class="pl-c1">7</span>, <span class="pl-c1">8</span>)
	<span class="pl-en">printSet</span>(<span class="pl-s">"Initial"</span>, <span class="pl-s1">set</span>) <span class="pl-c">// [ 2 3 4 5 6 7 8 ]</span>

	<span class="pl-s1">even</span> <span class="pl-c1">:=</span> <span class="pl-s1">set</span>.<span class="pl-en">Select</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)<span class="pl-c1">%</span><span class="pl-c1">2</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span>
	})
	<span class="pl-en">printSet</span>(<span class="pl-s">"Even numbers"</span>, <span class="pl-s1">even</span>) <span class="pl-c">// [ 2 4 6 8 ]</span>

	<span class="pl-s1">foundIndex</span>, <span class="pl-s1">foundValue</span> <span class="pl-c1">:=</span> <span class="pl-s1">set</span>.<span class="pl-en">Find</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)<span class="pl-c1">%</span><span class="pl-c1">2</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span> <span class="pl-c1">&amp;&amp;</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)<span class="pl-c1">%</span><span class="pl-c1">3</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span>
	})
	<span class="pl-k">if</span> <span class="pl-s1">foundIndex</span> <span class="pl-c1">!=</span> <span class="pl-c1">-</span><span class="pl-c1">1</span> {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"Number divisible by 2 and 3 found is"</span>, <span class="pl-s1">foundValue</span>, <span class="pl-s">"at index"</span>, <span class="pl-s1">foundIndex</span>) <span class="pl-c">// value: 6, index: 4</span>
	}

	<span class="pl-s1">square</span> <span class="pl-c1">:=</span> <span class="pl-s1">set</span>.<span class="pl-en">Map</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-k">interface</span>{} {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">*</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)
	})
	<span class="pl-en">printSet</span>(<span class="pl-s">"Numbers squared"</span>, <span class="pl-s1">square</span>) <span class="pl-c">// [ 4 9 16 25 36 49 64 ]</span>

	<span class="pl-s1">bigger</span> <span class="pl-c1">:=</span> <span class="pl-s1">set</span>.<span class="pl-en">Any</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">&gt;</span> <span class="pl-c1">5</span>
	})
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"Set contains a number bigger than 5 is "</span>, <span class="pl-s1">bigger</span>) <span class="pl-c">// true</span>

	<span class="pl-s1">positive</span> <span class="pl-c1">:=</span> <span class="pl-s1">set</span>.<span class="pl-en">All</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">&gt;</span> <span class="pl-c1">0</span>
	})
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"All numbers are positive is"</span>, <span class="pl-s1">positive</span>) <span class="pl-c">// true</span>

	<span class="pl-s1">evenNumbersSquared</span> <span class="pl-c1">:=</span> <span class="pl-s1">set</span>.<span class="pl-en">Select</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)<span class="pl-c1">%</span><span class="pl-c1">2</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span>
	}).<span class="pl-en">Map</span>(<span class="pl-k">func</span>(<span class="pl-s1">index</span> <span class="pl-smi">int</span>, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-k">interface</span>{} {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">*</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)
	})
	<span class="pl-en">printSet</span>(<span class="pl-s">"Chaining"</span>, <span class="pl-s1">evenNumbersSquared</span>) <span class="pl-c">// [ 4 16 36 64 ]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/sets/treeset&quot;
)

func printSet(txt string, set *treeset.Set) {
	fmt.Print(txt, &quot;[ &quot;)
	set.Each(func(index int, value interface{}) {
		fmt.Print(value, &quot; &quot;)
	})
	fmt.Println(&quot;]&quot;)
}

func main() {
	set := treeset.NewWithIntComparator()
	set.Add(2, 3, 4, 2, 5, 6, 7, 8)
	printSet(&quot;Initial&quot;, set) // [ 2 3 4 5 6 7 8 ]

	even := set.Select(func(index int, value interface{}) bool {
		return value.(int)%2 == 0
	})
	printSet(&quot;Even numbers&quot;, even) // [ 2 4 6 8 ]

	foundIndex, foundValue := set.Find(func(index int, value interface{}) bool {
		return value.(int)%2 == 0 &amp;&amp; value.(int)%3 == 0
	})
	if foundIndex != -1 {
		fmt.Println(&quot;Number divisible by 2 and 3 found is&quot;, foundValue, &quot;at index&quot;, foundIndex) // value: 6, index: 4
	}

	square := set.Map(func(index int, value interface{}) interface{} {
		return value.(int) * value.(int)
	})
	printSet(&quot;Numbers squared&quot;, square) // [ 4 9 16 25 36 49 64 ]

	bigger := set.Any(func(index int, value interface{}) bool {
		return value.(int) > 5
	})
	fmt.Println(&quot;Set contains a number bigger than 5 is &quot;, bigger) // true

	positive := set.All(func(index int, value interface{}) bool {
		return value.(int) > 0
	})
	fmt.Println(&quot;All numbers are positive is&quot;, positive) // true

	evenNumbersSquared := set.Select(func(index int, value interface{}) bool {
		return value.(int)%2 == 0
	}).Map(func(index int, value interface{}) interface{} {
		return value.(int) * value.(int)
	})
	printSet(&quot;Chaining&quot;, evenNumbersSquared) // [ 4 16 36 64 ]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-enumerablewithkey" class="anchor" aria-hidden="true" tabindex="-1" href="#enumerablewithkey"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">带键枚举</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于有序容器的枚举函数，其值的元素是键/值对。</font></font></p>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">每个</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为每个元素调用一次给定函数，并传递该元素的键和值。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">Each</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}))</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Each(func(key interface{}, value interface{}))" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">地图</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为每个元素调用一次给定函数，并返回一个容器，其中包含给定函数以键/值对形式返回的值。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">Map</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) (<span class="pl-k">interface</span>{}, <span class="pl-k">interface</span>{})) <span class="pl-s1">Container</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Map(func(key interface{}, value interface{}) (interface{}, interface{})) Container" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">选择</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">返回一个新容器，其中包含给定函数返回真值的所有元素。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">Select</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) <span class="pl-s1">Container</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Select(func(key interface{}, value interface{}) bool) Container" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">任何</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将容器的每个元素传递给给定函数，如果该函数对任何元素返回 true，则返回 true。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">Any</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) <span class="pl-s1">bool</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Any(func(key interface{}, value interface{}) bool) bool" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">全部</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将容器的每个元素传递给给定函数，如果该函数对所有元素都返回 true，则返回 true。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">All</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) <span class="pl-s1">bool</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="All(func(key interface{}, value interface{}) bool) bool" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">寻找</font></font></strong></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将容器的每个元素传递给给定函数，并返回该函数为 true 的第一个 (key,value) 或 nil,nil，否则如果没有元素匹配条件。</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-en">Find</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span>) (<span class="pl-k">interface</span>{}, <span class="pl-k">interface</span>{})</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="Find(func(key interface{}, value interface{}) bool) (interface{}, interface{})" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">例子：</font></font></strong></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/maps/treemap"</span>
)

<span class="pl-k">func</span> <span class="pl-en">printMap</span>(<span class="pl-s1">txt</span> <span class="pl-smi">string</span>, <span class="pl-s1">m</span> <span class="pl-c1">*</span>treemap.<span class="pl-smi">Map</span>) {
	<span class="pl-s1">fmt</span>.<span class="pl-en">Print</span>(<span class="pl-s1">txt</span>, <span class="pl-s">" { "</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Each</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Print</span>(<span class="pl-s1">key</span>, <span class="pl-s">":"</span>, <span class="pl-s1">value</span>, <span class="pl-s">" "</span>)
	})
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"}"</span>)
}

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">m</span> <span class="pl-c1">:=</span> <span class="pl-s1">treemap</span>.<span class="pl-en">NewWithStringComparator</span>()
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"g"</span>, <span class="pl-c1">7</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"f"</span>, <span class="pl-c1">6</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"e"</span>, <span class="pl-c1">5</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"d"</span>, <span class="pl-c1">4</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"c"</span>, <span class="pl-c1">3</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"b"</span>, <span class="pl-c1">2</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"a"</span>, <span class="pl-c1">1</span>)
	<span class="pl-en">printMap</span>(<span class="pl-s">"Initial"</span>, <span class="pl-s1">m</span>) <span class="pl-c">// { a:1 b:2 c:3 d:4 e:5 f:6 g:7 }</span>

	<span class="pl-s1">even</span> <span class="pl-c1">:=</span> <span class="pl-s1">m</span>.<span class="pl-en">Select</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">%</span> <span class="pl-c1">2</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span>
	})
	<span class="pl-en">printMap</span>(<span class="pl-s">"Elements with even values"</span>, <span class="pl-s1">even</span>) <span class="pl-c">// { b:2 d:4 f:6 }</span>

	<span class="pl-s1">foundKey</span>, <span class="pl-s1">foundValue</span> <span class="pl-c1">:=</span> <span class="pl-s1">m</span>.<span class="pl-en">Find</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">%</span> <span class="pl-c1">2</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span> <span class="pl-c1">&amp;&amp;</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">%</span> <span class="pl-c1">3</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span>
	})
	<span class="pl-k">if</span> <span class="pl-s1">foundKey</span> <span class="pl-c1">!=</span> <span class="pl-c1">nil</span> {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"Element with value divisible by 2 and 3 found is"</span>, <span class="pl-s1">foundValue</span>, <span class="pl-s">"with key"</span>, <span class="pl-s1">foundKey</span>) <span class="pl-c">// value: 6, index: 4</span>
	}

	<span class="pl-s1">square</span> <span class="pl-c1">:=</span> <span class="pl-s1">m</span>.<span class="pl-en">Map</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) (<span class="pl-k">interface</span>{}, <span class="pl-k">interface</span>{}) {
		<span class="pl-k">return</span> <span class="pl-s1">key</span>.(<span class="pl-smi">string</span>) <span class="pl-c1">+</span> <span class="pl-s1">key</span>.(<span class="pl-smi">string</span>), <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">*</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)
	})
	<span class="pl-en">printMap</span>(<span class="pl-s">"Elements' values squared and letters duplicated"</span>, <span class="pl-s1">square</span>) <span class="pl-c">// { aa:1 bb:4 cc:9 dd:16 ee:25 ff:36 gg:49 }</span>

	<span class="pl-s1">bigger</span> <span class="pl-c1">:=</span> <span class="pl-s1">m</span>.<span class="pl-en">Any</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">&gt;</span> <span class="pl-c1">5</span>
	})
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"Map contains element whose value is bigger than 5 is"</span>, <span class="pl-s1">bigger</span>) <span class="pl-c">// true</span>

	<span class="pl-s1">positive</span> <span class="pl-c1">:=</span> <span class="pl-s1">m</span>.<span class="pl-en">All</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">&gt;</span> <span class="pl-c1">0</span>
	})
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s">"All map's elements have positive values is"</span>, <span class="pl-s1">positive</span>) <span class="pl-c">// true</span>

	<span class="pl-s1">evenNumbersSquared</span> <span class="pl-c1">:=</span> <span class="pl-s1">m</span>.<span class="pl-en">Select</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) <span class="pl-smi">bool</span> {
		<span class="pl-k">return</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">%</span> <span class="pl-c1">2</span> <span class="pl-c1">==</span> <span class="pl-c1">0</span>
	}).<span class="pl-en">Map</span>(<span class="pl-k">func</span>(<span class="pl-s1">key</span> <span class="pl-k">interface</span>{}, <span class="pl-s1">value</span> <span class="pl-k">interface</span>{}) (<span class="pl-k">interface</span>{}, <span class="pl-k">interface</span>{}) {
		<span class="pl-k">return</span> <span class="pl-s1">key</span>, <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>) <span class="pl-c1">*</span> <span class="pl-s1">value</span>.(<span class="pl-smi">int</span>)
	})
	<span class="pl-en">printMap</span>(<span class="pl-s">"Chaining"</span>, <span class="pl-s1">evenNumbersSquared</span>) <span class="pl-c">// { b:4 d:16 f:36 }</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/maps/treemap&quot;
)

func printMap(txt string, m *treemap.Map) {
	fmt.Print(txt, &quot; { &quot;)
	m.Each(func(key interface{}, value interface{}) {
		fmt.Print(key, &quot;:&quot;, value, &quot; &quot;)
	})
	fmt.Println(&quot;}&quot;)
}

func main() {
	m := treemap.NewWithStringComparator()
	m.Put(&quot;g&quot;, 7)
	m.Put(&quot;f&quot;, 6)
	m.Put(&quot;e&quot;, 5)
	m.Put(&quot;d&quot;, 4)
	m.Put(&quot;c&quot;, 3)
	m.Put(&quot;b&quot;, 2)
	m.Put(&quot;a&quot;, 1)
	printMap(&quot;Initial&quot;, m) // { a:1 b:2 c:3 d:4 e:5 f:6 g:7 }

	even := m.Select(func(key interface{}, value interface{}) bool {
		return value.(int) % 2 == 0
	})
	printMap(&quot;Elements with even values&quot;, even) // { b:2 d:4 f:6 }

	foundKey, foundValue := m.Find(func(key interface{}, value interface{}) bool {
		return value.(int) % 2 == 0 &amp;&amp; value.(int) % 3 == 0
	})
	if foundKey != nil {
		fmt.Println(&quot;Element with value divisible by 2 and 3 found is&quot;, foundValue, &quot;with key&quot;, foundKey) // value: 6, index: 4
	}

	square := m.Map(func(key interface{}, value interface{}) (interface{}, interface{}) {
		return key.(string) + key.(string), value.(int) * value.(int)
	})
	printMap(&quot;Elements' values squared and letters duplicated&quot;, square) // { aa:1 bb:4 cc:9 dd:16 ee:25 ff:36 gg:49 }

	bigger := m.Any(func(key interface{}, value interface{}) bool {
		return value.(int) > 5
	})
	fmt.Println(&quot;Map contains element whose value is bigger than 5 is&quot;, bigger) // true

	positive := m.All(func(key interface{}, value interface{}) bool {
		return value.(int) > 0
	})
	fmt.Println(&quot;All map's elements have positive values is&quot;, positive) // true

	evenNumbersSquared := m.Select(func(key interface{}, value interface{}) bool {
		return value.(int) % 2 == 0
	}).Map(func(key interface{}, value interface{}) (interface{}, interface{}) {
		return key, value.(int) * value.(int)
	})
	printMap(&quot;Chaining&quot;, evenNumbersSquared) // { b:4 d:16 f:36 }
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-serialization" class="anchor" aria-hidden="true" tabindex="-1" href="#serialization"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">序列化</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有数据结构都可以序列化（编组）和反序列化（解组）。</font><font style="vertical-align: inherit;">目前仅支持 JSON。</font></font></p>
<h4 tabindex="-1" dir="auto"><a id="user-content-jsonserializer" class="anchor" aria-hidden="true" tabindex="-1" href="#jsonserializer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSON序列化器</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将容器输出为其 JSON 表示形式。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键值结构的典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"encoding/json"</span>
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/maps/hashmap"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">m</span> <span class="pl-c1">:=</span> <span class="pl-s1">hashmap</span>.<span class="pl-en">New</span>()
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"1"</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"b"</span>, <span class="pl-s">"2"</span>)
	<span class="pl-s1">m</span>.<span class="pl-en">Put</span>(<span class="pl-s">"c"</span>, <span class="pl-s">"3"</span>)

	<span class="pl-s1">bytes</span>, <span class="pl-s1">err</span> <span class="pl-c1">:=</span> <span class="pl-s1">json</span>.<span class="pl-en">Marshal</span>(<span class="pl-s1">m</span>) <span class="pl-c">// Same as "m.ToJSON(m)"</span>
	<span class="pl-k">if</span> <span class="pl-s1">err</span> <span class="pl-c1">!=</span> <span class="pl-c1">nil</span> {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">err</span>)
	}
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-en">string</span>(<span class="pl-s1">bytes</span>)) <span class="pl-c">// {"a":"1","b":"2","c":"3"}</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;encoding/json&quot;
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/maps/hashmap&quot;
)

func main() {
	m := hashmap.New()
	m.Put(&quot;a&quot;, &quot;1&quot;)
	m.Put(&quot;b&quot;, &quot;2&quot;)
	m.Put(&quot;c&quot;, &quot;3&quot;)

	bytes, err := json.Marshal(m) // Same as &quot;m.ToJSON(m)&quot;
	if err != nil {
		fmt.Println(err)
	}
	fmt.Println(string(bytes)) // {&quot;a&quot;:&quot;1&quot;,&quot;b&quot;:&quot;2&quot;,&quot;c&quot;:&quot;3&quot;}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅值结构的典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"encoding/json"</span>
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/lists/arraylist"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">list</span> <span class="pl-c1">:=</span> <span class="pl-s1">arraylist</span>.<span class="pl-en">New</span>()
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-s">"a"</span>, <span class="pl-s">"b"</span>, <span class="pl-s">"c"</span>)

	<span class="pl-s1">bytes</span>, <span class="pl-s1">err</span> <span class="pl-c1">:=</span> <span class="pl-s1">json</span>.<span class="pl-en">Marshal</span>(<span class="pl-s1">list</span>) <span class="pl-c">// Same as "list.ToJSON(list)"</span>
	<span class="pl-k">if</span> <span class="pl-s1">err</span> <span class="pl-c1">!=</span> <span class="pl-c1">nil</span> {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">err</span>)
	}
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-en">string</span>(<span class="pl-s1">bytes</span>)) <span class="pl-c">// ["a","b","c"]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;encoding/json&quot;
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/lists/arraylist&quot;
)

func main() {
	list := arraylist.New()
	list.Add(&quot;a&quot;, &quot;b&quot;, &quot;c&quot;)

	bytes, err := json.Marshal(list) // Same as &quot;list.ToJSON(list)&quot;
	if err != nil {
		fmt.Println(err)
	}
	fmt.Println(string(bytes)) // [&quot;a&quot;,&quot;b&quot;,&quot;c&quot;]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h4 tabindex="-1" dir="auto"><a id="user-content-jsondeserializer" class="anchor" aria-hidden="true" tabindex="-1" href="#jsondeserializer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JSON反序列化器</font></font></h4>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用输入 JSON 表示形式中的元素填充容器。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">键值结构的典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"encoding/json"</span>
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/maps/hashmap"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">hm</span> <span class="pl-c1">:=</span> <span class="pl-s1">hashmap</span>.<span class="pl-en">New</span>()

	<span class="pl-s1">bytes</span> <span class="pl-c1">:=</span> []<span class="pl-smi">byte</span>(<span class="pl-s">`{"a":"1","b":"2"}`</span>)
	<span class="pl-s1">err</span> <span class="pl-c1">:=</span> <span class="pl-s1">json</span>.<span class="pl-en">Unmarshal</span>(<span class="pl-s1">bytes</span>, <span class="pl-c1">&amp;</span><span class="pl-s1">hm</span>) <span class="pl-c">// Same as "hm.FromJSON(bytes)"</span>
	<span class="pl-k">if</span> <span class="pl-s1">err</span> <span class="pl-c1">!=</span> <span class="pl-c1">nil</span> {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">err</span>)
	}
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">hm</span>) <span class="pl-c">// HashMap map[b:2 a:1]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;encoding/json&quot;
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/maps/hashmap&quot;
)

func main() {
	hm := hashmap.New()

	bytes := []byte(`{&quot;a&quot;:&quot;1&quot;,&quot;b&quot;:&quot;2&quot;}`)
	err := json.Unmarshal(bytes, &amp;hm) // Same as &quot;hm.FromJSON(bytes)&quot;
	if err != nil {
		fmt.Println(err)
	}
	fmt.Println(hm) // HashMap map[b:2 a:1]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅值结构的典型用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"encoding/json"</span>
	<span class="pl-s">"fmt"</span>
	<span class="pl-s">"github.com/emirpasic/gods/lists/arraylist"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">list</span> <span class="pl-c1">:=</span> <span class="pl-s1">arraylist</span>.<span class="pl-en">New</span>()

	<span class="pl-s1">bytes</span> <span class="pl-c1">:=</span> []<span class="pl-smi">byte</span>(<span class="pl-s">`["a","b"]`</span>)
	<span class="pl-s1">err</span> <span class="pl-c1">:=</span> <span class="pl-s1">json</span>.<span class="pl-en">Unmarshal</span>(<span class="pl-s1">bytes</span>, <span class="pl-c1">&amp;</span><span class="pl-s1">list</span>) <span class="pl-c">// Same as "list.FromJSON(bytes)"</span>
	<span class="pl-k">if</span> <span class="pl-s1">err</span> <span class="pl-c1">!=</span> <span class="pl-c1">nil</span> {
		<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">err</span>)
	}
	<span class="pl-s1">fmt</span>.<span class="pl-en">Println</span>(<span class="pl-s1">list</span>) <span class="pl-c">// ArrayList ["a","b"]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;encoding/json&quot;
	&quot;fmt&quot;
	&quot;github.com/emirpasic/gods/lists/arraylist&quot;
)

func main() {
	list := arraylist.New()

	bytes := []byte(`[&quot;a&quot;,&quot;b&quot;]`)
	err := json.Unmarshal(bytes, &amp;list) // Same as &quot;list.FromJSON(bytes)&quot;
	if err != nil {
		fmt.Println(err)
	}
	fmt.Println(list) // ArrayList [&quot;a&quot;,&quot;b&quot;]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-sort" class="anchor" aria-hidden="true" tabindex="-1" href="#sort"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">种类</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sort 是通用排序函数。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">列表有一个就地</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sort()函数，所有容器都可以通过</font></font></em><font style="vertical-align: inherit;"></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Containers.GetSortedValues()</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">函数返回其排序元素</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在内部，这些都使用</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">utils.Sort()</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">方法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> <span class="pl-s">"github.com/emirpasic/gods/utils"</span>

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">strings</span> <span class="pl-c1">:=</span> []<span class="pl-k">interface</span>{}{}                  <span class="pl-c">// []</span>
	<span class="pl-s1">strings</span> <span class="pl-c1">=</span> <span class="pl-en">append</span>(<span class="pl-s1">strings</span>, <span class="pl-s">"d"</span>)              <span class="pl-c">// ["d"]</span>
	<span class="pl-s1">strings</span> <span class="pl-c1">=</span> <span class="pl-en">append</span>(<span class="pl-s1">strings</span>, <span class="pl-s">"a"</span>)              <span class="pl-c">// ["d","a"]</span>
	<span class="pl-s1">strings</span> <span class="pl-c1">=</span> <span class="pl-en">append</span>(<span class="pl-s1">strings</span>, <span class="pl-s">"b"</span>)              <span class="pl-c">// ["d","a",b"</span>
	<span class="pl-s1">strings</span> <span class="pl-c1">=</span> <span class="pl-en">append</span>(<span class="pl-s1">strings</span>, <span class="pl-s">"c"</span>)              <span class="pl-c">// ["d","a",b","c"]</span>
	<span class="pl-s1">utils</span>.<span class="pl-en">Sort</span>(<span class="pl-s1">strings</span>, <span class="pl-s1">utils</span>.<span class="pl-c1">StringComparator</span>) <span class="pl-c">// ["a","b","c","d"]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import &quot;github.com/emirpasic/gods/utils&quot;

func main() {
	strings := []interface{}{}                  // []
	strings = append(strings, &quot;d&quot;)              // [&quot;d&quot;]
	strings = append(strings, &quot;a&quot;)              // [&quot;d&quot;,&quot;a&quot;]
	strings = append(strings, &quot;b&quot;)              // [&quot;d&quot;,&quot;a&quot;,b&quot;
	strings = append(strings, &quot;c&quot;)              // [&quot;d&quot;,&quot;a&quot;,b&quot;,&quot;c&quot;]
	utils.Sort(strings, utils.StringComparator) // [&quot;a&quot;,&quot;b&quot;,&quot;c&quot;,&quot;d&quot;]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-container" class="anchor" aria-hidden="true" tabindex="-1" href="#container"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">容器具体操作：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">// Returns sorted container''s elements with respect to the passed comparator.</span>
<span class="pl-c">// Does not affect the ordering of elements within the container.</span>
<span class="pl-k">func</span> <span class="pl-en">GetSortedValues</span>(<span class="pl-s1">container</span> <span class="pl-smi">Container</span>, <span class="pl-s1">comparator</span> utils.<span class="pl-smi">Comparator</span>) []<span class="pl-k">interface</span>{}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="// Returns sorted container''s elements with respect to the passed comparator.
// Does not affect the ordering of elements within the container.
func GetSortedValues(container Container, comparator utils.Comparator) []interface{}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法：</font></font></p>
<div class="highlight highlight-source-go notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">package</span> main

<span class="pl-k">import</span> (
	<span class="pl-s">"github.com/emirpasic/gods/lists/arraylist"</span>
	<span class="pl-s">"github.com/emirpasic/gods/utils"</span>
)

<span class="pl-k">func</span> <span class="pl-en">main</span>() {
	<span class="pl-s1">list</span> <span class="pl-c1">:=</span> <span class="pl-s1">arraylist</span>.<span class="pl-en">New</span>()
	<span class="pl-s1">list</span>.<span class="pl-en">Add</span>(<span class="pl-c1">2</span>, <span class="pl-c1">1</span>, <span class="pl-c1">3</span>)
	<span class="pl-s1">values</span> <span class="pl-c1">:=</span> <span class="pl-en">GetSortedValues</span>(<span class="pl-s1">container</span>, <span class="pl-s1">utils</span>.<span class="pl-c1">StringComparator</span>) <span class="pl-c">// [1, 2, 3]</span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="package main

import (
	&quot;github.com/emirpasic/gods/lists/arraylist&quot;
	&quot;github.com/emirpasic/gods/utils&quot;
)

func main() {
	list := arraylist.New()
	list.Add(2, 1, 3)
	values := GetSortedValues(container, utils.StringComparator) // [1, 2, 3]
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-appendix" class="anchor" aria-hidden="true" tabindex="-1" href="#appendix"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附录</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-motivation" class="anchor" aria-hidden="true" tabindex="-1" href="#motivation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">动机</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他语言中的集合和数据结构：Java 集合、C++ 标准模板库 (STL) 容器、Qt 容器、Ruby Enumerable 等。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-goals" class="anchor" aria-hidden="true" tabindex="-1" href="#goals"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目标</font></font></h3>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速算法</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于上述其他图书馆数十年的知识和经验。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">内存高效算法</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过针对给定的一组问题使用最佳算法和数据结构来避免消耗内存，例如 TreeMap 中的红黑树，以避免在内存中保留冗余的排序键数组。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">易于使用的库</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">结构良好的库，具有简约的原子操作集，可以从中创建更复杂的操作。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">稳定的库</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仅允许添加以保持库向后兼容。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可靠的文档和示例</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过实例学习。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生产准备就绪</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于生产。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无依赖关系</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">没有外部进口。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在设计算法时，速度和内存之间经常存在拉锯战。</font><font style="vertical-align: inherit;">在大多数情况下，我们选择在合理的内存消耗限制内优化速度。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">线程安全不是这个项目所关心的问题，这应该在更高级别上处理。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-testing-and-benchmarking" class="anchor" aria-hidden="true" tabindex="-1" href="#testing-and-benchmarking"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">测试和基准测试</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这需要一段时间，因此在子包中进行测试：</font></font></p>
<p dir="auto"><code>go test -run=NO_TEST -bench . -benchmem  -benchtime 1s ./...</code></p>
<p align="center" dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://cloud.githubusercontent.com/assets/3115942/16892979/5e698d46-4b27-11e6-864b-cb2b865327b6.png"><img src="https://cloud.githubusercontent.com/assets/3115942/16892979/5e698d46-4b27-11e6-864b-cb2b865327b6.png" style="max-width: 100%;"></a></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对这个库最大的贡献是使用它并向我们提供反馈以进一步改进和添加。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于直接贡献，</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请将请求拉</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">入主分支或要求成为贡献者。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编码风格：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> Install tooling and set path:</span>
go install gotest.tools/gotestsum@latest
go install golang.org/x/lint/golint@latest
go install github.com/kisielk/errcheck@latest
<span class="pl-k">export</span> PATH=<span class="pl-smi">$PATH</span>:<span class="pl-smi">$GOPATH</span>/bin

<span class="pl-c"><span class="pl-c">#</span> Fix errors and warnings:</span>
go fmt ./... <span class="pl-k">&amp;&amp;</span>
go <span class="pl-c1">test</span> -v ./... <span class="pl-k">&amp;&amp;</span> 
golint -set_exit_status ./... <span class="pl-k">&amp;&amp;</span> 
<span class="pl-k">!</span> go fmt ./... <span class="pl-k">2&gt;&amp;1</span> <span class="pl-k">|</span> <span class="pl-c1">read</span> <span class="pl-k">&amp;&amp;</span>
go vet -v ./... <span class="pl-k">&amp;&amp;</span>
gocyclo -avg -over 15 ../gods <span class="pl-k">&amp;&amp;</span>
errcheck ./...</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# Install tooling and set path:
go install gotest.tools/gotestsum@latest
go install golang.org/x/lint/golint@latest
go install github.com/kisielk/errcheck@latest
export PATH=$PATH:$GOPATH/bin

# Fix errors and warnings:
go fmt ./... &amp;&amp;
go test -v ./... &amp;&amp; 
golint -set_exit_status ./... &amp;&amp; 
! go fmt ./... 2>&amp;1 | read &amp;&amp;
go vet -v ./... &amp;&amp;
gocyclo -avg -over 15 ../gods &amp;&amp;
errcheck ./..." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-license" class="anchor" aria-hidden="true" tabindex="-1" href="#license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">执照</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该库是根据</font></font><a href="https://github.com/emirpasic/gods/blob/master/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LICENSE</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件中的 BSD 样式许可证分发的。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-sponsors" class="anchor" aria-hidden="true" tabindex="-1" href="#sponsors"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">赞助商</font></font></h3>
<h2 tabindex="-1" dir="auto"><a id="" class="anchor" aria-hidden="true" tabindex="-1" href="#"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><a href="https://www.browserstack.com/?ref=gods" rel="nofollow"><img src="https://camo.githubusercontent.com/35a0d99a46cbef4c5eaf3bf4236545206eb3f62ff1e2f34b076d39aa4e7534ce/687474703a2f2f7777772e68616a646172657669632e6e65742f62726f77736572737461636b2e737667" alt="浏览器堆栈" width="250" data-canonical-src="http://www.hajdarevic.net/browserstack.svg" style="max-width: 100%;"></a></h2>
<p dir="auto"><a href="https://www.browserstack.com/?ref=webhook" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">BrowserStack</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个基于云的跨浏览器测试工具，使开发人员能够在不同操作系统和移动设备上跨各种浏览器测试他们的网站，而不需要用户安装虚拟机、设备或模拟器。</font></font></p>
</article></div>
