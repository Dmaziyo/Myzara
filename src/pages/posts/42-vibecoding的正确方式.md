---
date: 2025/10/18
---

<img src="https://cdn.jsdelivr.net/gh/Dmaziyo/blog-img@main/myzara-cover42.jpg?raw=true" width="500" />

<small>封面图是我去哈尔滨最后一天选的一个青旅，人生第一次住青旅。体验非常好，环境没想象中那种脏乱差，人也非常友善，并且我本来只是打算过夜就走，结果洗漱完就被拉着去唱ktv了，之后去旅游我也会去找找当地的青旅体验一下了。</small>   


> **记录自己的%2,aka每周摸到的🐟(不定期更新**


## vibe coding的正常方式
在油管上刷到一个[The "right way" to vibe code (engineers, please watch)](https://www.youtube.com/watch?v=6TMPWvPG5GA),我觉得里面讲的很多点我都很认可，我想分享一下他在视频中的take：   
大家都在讨论vibe coding，但是很多人讨论基于的上下文是不同的
<img src="https://cdn.jsdelivr.net/gh/Dmaziyo/blog-img@main/myzara42-1.jpg?raw=true" width="600" />
有人会说vibe coding很方便，也有人会说vibe coding浪费时间只是玩具。而我关于vibe coding的定义是vibe coding更多的是你不怎么需要去阅读代码，或者只需要把报错复制上去，然后cv就行了。   

#### 1. 你仍需要知道代码是怎么运行的，如果你想成为一名开发者的话
The problem with vibe coding is that it was invented by engineers for engineers  
#### 2. 大多数的代码是值得拥有但不值得阅读或者编写的
大多数开发者会对自己写的代码情有独钟，很难接受那些对自己有用的代码并不值得自己一行行去写,而这正是vibe coding存在的意义，帮我们快速去创建一些throwaway code，is the shit you don't wanna to deal with it。而不去看的原因并不是因为你不知道怎么回事，而是因为不值得。  

#### 3. 你不可能对vibe coding生气的同时对left-pad生气  

left pad是一个第三方库，用于拼接字符串的，本质上vibe coding也是一种第三方库，但是这个库我们可以自己进行快速定制。所以你不可能对vibe coding生气的同时又对自己正在使用的第三方库生气  

#### 4. vibe code就是throwaway code   
如果你在给产品做新功能，确实值得先好好设计。但绝大多数时候，你完全可以先拼个“垃圾”原型——代码烂到不会合并、不会上线，只想快速放到用户面前试反应。只要提前看清方向，就能避免把“好代码”浪费在“错需求”上，省下的麻烦远超想象。"好代码"有两个要点，第一是解决了对的问题，第二个是能够让人读懂。但大多数人花时间花在了第二点，而不是第一点。  
#### 5. 如果这些工具比你更厉害，那么停止使用他们。  
如果你是因为你不知道怎么写才使用ai，you're screwed。大多数人不希望自己无知，面对问题时而无能为力的感觉很糟糕，而这时候ai工具跳出来说：使用我吧，你都不需要理解它就能解决。 这些ai工具的好处不是说"不需要知道如何写代码"，而是你可以用一堆随手生成的代码去解决那些原本你"懒得动手"，最后不了了之的小问题,并不是**把知识外包出去，而是把‘为了学这东西该问什么问题’给外包出去。**

#### 6. 如果你看不到vide coding可以怎么帮助你，那么你是没有想象力的
vibe coding使得那些为一个人或者几个人量身定制的软件成为可能，而这些软件本来就不会有工程师去写，它不需要多么的优秀或者可拓展，只要能解决几个人的问题那就够了。
   





## 音乐分享
**《Really love》**  
无意间看到黄宣弹唱的这首歌，然后就去听了原版，这种异域风情好好听。rip
<iframe data-testid="embed-iframe" style="border-radius:12px" src="https://open.spotify.com/embed/track/2RcanAJpudPNDkyIe9DzKS?utm_source=generator" width="100%" height="152" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>


## 有趣的产品和工具
**[hexclock](https://www.jacopocolo.com/hexclock/)**  
用十六进制颜色值显示当前时间，什么时间就显示什么颜色  
<iframe
  src="https://www.jacopocolo.com/hexclock/" width="100%" height="300px" allowfullscreen loading="lazy"
  style="border-radius: 15px; background-color: #eeeeee; border: 3px dashed #111111;"
  sandbox="allow-scripts allow-same-origin"
  referrerpolicy="no-referrer-when-downgrade"
  tabindex="0"
></iframe>

## 播客和文章

**[《关于破解加拿大航空飞机网络限制的一件小事》](https://ramsayleung.github.io/zh/post/2025/%E5%85%B3%E4%BA%8E%E7%A0%B4%E8%A7%A3%E5%8A%A0%E6%8B%BF%E5%A4%A7%E8%88%AA%E7%A9%BA%E9%A3%9E%E6%9C%BA%E7%BD%91%E7%BB%9C%E9%99%90%E5%88%B6%E7%9A%84%E4%B8%80%E4%BB%B6%E5%B0%8F%E4%BA%8B/)**  
作者和他的舍友通过远端架设一台电脑暴露53端口伪装成dns服务器，然后绕过了飞机上的网络限制，免费使用上了网络。damn，原来学计算机网络真的能有用啊！  
<img src="https://cdn.jsdelivr.net/gh/Dmaziyo/blog-img@main/myzara42-2.jpg?raw=true" width="600" />

**[《Your Biggest Customer Might Be Your Biggest Bottleneck 》](https://densumesh.dev/blog/fair-queue/)**  
传统的队列有点像去政府办理业务，每个人都井然有序排队，按顺序处理。这没什么问题，但是倘若其中的一个人拿着100份文件去办理，那么就会出现阻塞了。这时候作者就提出了使用循环队列的方式来确保真正的公平，round-robin-schedule。  
<img src="https://cdn.jsdelivr.net/gh/Dmaziyo/blog-img@main/myzara42-3.jpg?raw=true" width="600" />    
