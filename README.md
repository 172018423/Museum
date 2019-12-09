# PRD_智能博物馆小程序

---

## PRD 价值主张设计 15%


### PRD1.加值宣言 3%

运用人工智能技术(**语音合成**,**知识图谱**)来加持智能博物馆小程序，解决用户痛点


---

### PRD2.核心价值 3%

* 解决了博物馆导览员人手不足的问题。

* 让游客能在最短的时间内清晰地了解到文物的相关信息并形成系统的知识结构。

---

### PRD3.用户痛点 3%

* 博物馆工作人员有限，不能及时得为每一个游览者提供有效的服务，服务的缺失影响了游客的体验，也影响了游客享受博物馆的社会教育功能。很多时候，游客会在博物馆迷路，同时也不能得到有效的知识讲解

* 博物馆场地复杂，展品繁多，如果用户想将全部展品游览且消化是一件很难的事情。没有目的的在博物馆逛可能会降低游客的游览效率，不能形成系统的知识学习

---

### PRD4.人工智能概率性与用户痛点 3%

* **语音合成**：准确率一般能保持到99%，出错的机率较小

* **知识图谱**：当前知识图谱发展还处于初级阶段，面临众多挑战和难题，如：知识库的自动扩展、异构知识处理、推理规则学习、跨语言检索等

---

### PRD5.需求列表与人工智能API加值 3%

* **科大讯飞API**：语音合成
* **百度API**：知识图谱

* 接口描述：

1.**语音合成**-通过导览小程序，使用语音合成技术为访客提供多种发音人的朗读功能与多种语言模式，释放双手和双眼，获得更极致的阅读体验。支持多种参数配置，可根据场景需求对发音人的语速、音调、音量进行灵活设置，满足个性化需求

2.**知识图谱**-当用户搜索某个藏品的时候，不仅有该藏品的信息介绍，还有同系列的藏品或相关作者的其他作品推荐。


* 接口地址：
1.[语音合成](https://www.xfyun.cn/services/online_tts)

2.[知识图谱](https://cloud.baidu.com/product/cognitive)

* 请求方法：POST



---

## 原型 20%

### 原型1.交互及界面设计与信息设计

![语音合成](https://images.gitee.com/uploads/images/2019/1209/125127_300ad85e_1829822.png "语音合成原型.PNG")

![知识图谱](https://images.gitee.com/uploads/images/2019/1209/125143_c3e86249_1829822.png "知识图谱原型.PNG")

### 原型3.原型文档

* [完整原型](http://127.0.0.1:32767/start.html#p=%E5%B0%8F%E7%A8%8B%E5%BA%8F%E9%A6%96%E9%A1%B5&g=1)

* [Github下载链接](https://github.com/172018423/-)



---

## API 产品使用关键AI或机器学习之API的输出入展示 15%

### API输入输出尝试

![输入图片说明](https://images.gitee.com/uploads/images/2019/1209/125524_06ba52ab_1829822.png "语音合成.PNG")

---

### API2.使用比较分析 5%

* 参考链接：[语音合成哪家强？](http://www.sohu.com/a/246325979_99932778)：

1.讯飞留声制作完整音库只需10句话声音录入，远低于微软采集的500句，亦低于谷歌的30句，采集量只有行业平均的百分之一，合成效果更好

2.科大讯飞除智能语音技术全球领先外，在自然语言理解上同样属业界翘楚。随着语义和语音的融合交叉发展，科大讯飞或将率先解决语音合成情感表达难题，将语音合成技术发展推向新的阶段

3.百度完全从搜索出发基于十多年沉淀的知识图谱、用户数据，利用擅长的大数据和深度学习算法，反而可以把知识图谱做得更加全面、精准和完备。目前百度的知识图谱已经涵盖十几大领域，数十个类别，拥有上亿实体量。

---

### API3.使用后风险报告（参考链接:[语音合成技术应用的安全风险分析](https://www.xzbu.com/1/view-14900336.htm)）


* 发展性：

1.从2016年下半年语音交互市场突然爆发，语音合成的技术手段和解决方案不断更新迭代，几乎每隔一个多月，语音交互的效果都会出现较大的提升

2.目前国内外市场上，语音合成技术已经成功应用在很多领域，包括语音导航、信息播报、有声阅读、广告促销、游戏娱乐等。语音合成以贴近场景需求的合成效果，主要在语音交互、阅读教育、泛娱乐化三大场景中得以应用

3.知识图谱可以最有效、最直观地表达出实体间的关系。简单地说，就是把大量不同种类的信息连接在一起而得到一个关系网络，为人们提供了从“关系”的角度分析问题的能力



* 风险：

1.语音合成应用于诈骗。骗子通过盗取微信号和外挂软件，制作“克隆微信”，不仅能够完全盗取并复制用户在微信平台留存的语音信息，通过语音合成软件加以处理实施诈骗，通过熟人的声音进行诈骗的成功率更高一些

2.语音合成应用于造假信息传播。个人声纹是一种强生物特征，能够在一定程度上区分不同人物，因此也同个人指纹一样被应用于加密领域。曾有人利用美国前总统奥巴马的声音，合成出一段批评特朗普总统的虚假视频，引起轩然大波。这意味着音频可以伪造的，音视频已经不再能够成为直接证据。
