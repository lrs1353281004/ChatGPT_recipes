# ChatGPT 技术/市场资料汇总

>此页面持续追踪ChatGPT相关的技术资料和行业进展。
>
>指标说明：
>
>整体推荐指数:⭐~⭐⭐⭐⭐⭐
>
>技术难度指数:❗~❗❗❗
>
>主观评估，仅供参考~

分类：
* [技术原理](#技术原理)
* [技术迭代与追踪](#技术迭代与追踪)
* [行业趋势](#行业趋势)
* [行业应用与探索](#行业应用与探索)
* [行业规范与法律法规](#行业规范与法律法规)
* [openAI发展思考](#openai发展思考)
* [业界跟进-同类产品信息](#业界跟进-同类产品信息)


## 技术原理
>关注ChatGPT背后的技术方案、实现细节。

|资料链接|来源|发布时间点|内容概述|整体推荐指数|技术难度指数|
| :-----| :-----| :-----| :-----| :-----| :-----|
|[关于ChatGPT的思考-李理](http://fancyerii.github.io/2023/02/20/about-chatgpt/)|个人博客|2023-02-20|业界从业者关于ChatGPT思考的长文，包括NLP领域范式演进的详细历程，ChatGPT的技术细节介绍、应用思考、未来趋势等。信息量很丰富。|⭐⭐⭐⭐⭐|❗❗❗|
| [Chat GPT (可能)是怎么炼成的 - GPT社会化的过程 (李宏毅)](https://www.bilibili.com/video/BV1U84y167i3/?spm_id_from=333.337.search-card.all.click&vd_source=087bfe4fe2563ec34568ba8623437eae)                                                                                                                         | 李宏毅              | 2022-12-7    | 台大李宏毅教授的ChatGPT技术介绍视频，讲解通俗易懂、简洁明了。推荐观看。                                                                                           |⭐⭐⭐⭐⭐        | ❗            |
| [GPT，GPT\-2，GPT\-3 论文精读【论文精读】\_李沐](https://www.bilibili.com/video/BV1AF411b7xQ/?spm_id_from=333.999.0.0)                                                                                                                                                                                              | 李沐                | 2022\-03\-04 | 沐神的**GPT系列论文解读**，质量很高，推荐对技术细节感兴趣的同学观看。                                                                                             | ⭐⭐⭐⭐         | ❗❗           |
| [后GPT 3\.0时代，主流大模型技术精要详解，走向AGI之路的大门已开](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650865591&idx=4&sn=8ec5728ba31e1dfa1aa83f7dfba1de69&chksm=84e53bc9b392b2df6ae36372b456747a1f231c0cb144aaba75f32b2e6e022ebfd4595f9f5e07&token=1087000475&lang=zh_CN&scene=21#wechat_redirect) | 张俊林              | 2023\-01\-10 | 三万字的篇幅，张俊林深入回顾了**大型语言模型（LLM）**的发展历程、技术迭代更新以及未来走向等方方面面的内容，并探讨了通过超大 LLM 实现通用人工智能（AGI）的可能性。 | ⭐⭐⭐⭐         | ❗❗❗          |
| [InstructGPT 论文精读](https://www.bilibili.com/video/BV1hd4y187CR/?spm_id_from=333.999.0.0&vd_source=087bfe4fe2563ec34568ba8623437eae)                                                                                                                                                                             | 李沐                | 2022\-12\-29 | 沐神对**InstructGPT的论文解读**（ChatGPT的技术方案基本与InstructGPT一致）。推荐对技术细节感兴趣的同学观看。                                                       | ⭐⭐⭐⭐         | ❗❗           |
| [ChatGPT数据集之谜](https://mp.weixin.qq.com/s/9vOc-OyqvzrO_w5LApurbg)                                                                                                                                                                                                                                              | OneFlow公众号       | 2023\-02\-14 | 本文作者整理分析了2018年到2022年初从GPT\-1到Gopher的相关**大型语言模型**的所有**数据集**相关信息。                                                                | ⭐️⭐⭐️          | ❗❗           |
| [ChatGPT/InstructGPT详解](https://zhuanlan.zhihu.com/p/590311003)                                                                                                                                                                                                                                                   | 知乎                | 2023\-02\-06 | 对**ChatGPT/InstructGPT**背后的**技术原理**和**训练过程**进行详细解读。                                                                                           | ⭐⭐⭐          | ❗❗❗          |
| [GPT1到ChatGPT的技术演进](https://mp.weixin.qq.com/s/IDDhb-qRypVJHhRzzFl5iw)                                                                                                                                                                                                                                        | DataFunSummit公众号 | 2022\-12\-28 | 介绍了从GPT1\-GPT3、Codex、InstructGPT以及ChatGPT的关键技术点，描述了技术演进的历程。                                                                             | ⭐⭐⭐          | ❗❗     |
| [从word2vec开始，说下GPT庞大的家族系谱](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650798946&idx=1&sn=7ab78e435d1dfe671168e915b42aa98b&chksm=871a3f1cb06db60aa5f0bc4ab5bb9d220ac4cb189fc81b89df0ef9db6a59f3c33770a93b83bd&token=1087000475&lang=zh_CN&scene=21#wechat_redirect)                         | 机器之心公众号      | 2020\-10\-04 | 深入介绍了从**word2vec**到transformer，一直到**GPT3**的一系列**技术演进历程**。                                                                  |⭐⭐⭐|❗❗❗|
|[\[DLHLP 2020\] 來自獵人暗黑大陸的模型 GPT\-3 \-\-by Hung\-yi Lee 李宏毅](https://www.bilibili.com/video/BV1xv411C7af/?vd_source=087bfe4fe2563ec34568ba8623437eae)|李宏毅|2020\-06\-28|台大李宏毅教授的关于**GPT3的介绍视频**。|⭐️⭐⭐️|❗❗|
|[解读 ChatGPT 背后的技术重点：RLHF、IFT、CoT、红蓝对抗](https://mp.weixin.qq.com/s/Xd5VtRP-ziH-PYFOci65Hg)|Hugging Face|2023\-02\-01|拆解介绍了**ChatGPT**背后使用的各类**重点技术**。亮点：横向对比了各种类ChatGPT工作的重点技术方案。|⭐️⭐|❗❗❗|
|[深入浅出，解析ChatGPT背后的工作原理](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650865278&idx=4&sn=9448126707078657cd369c48d64c4f1b&chksm=84e53a00b392b3167d88940702d7b3301d8842129b7c833b04ba701aa9fc8a61f561641109bc&token=1087000475&lang=zh_CN&scene=21#wechat_redirect)|机器之心公众号|2023\-01\-06|简要介绍了**ChatGPT**背后的主要**技术方案**。|⭐⭐|❗❗|
|[In\-Context Learning玩法大全](https://mp.weixin.qq.com/s/NLWCuzcCdwljQfzu-Jd9lQ)|李rumor公众号|2023\-01\-06|介绍了一篇**优秀综述**，内容是关于ChatGPT背后的__In\-Context Learning__技术方向。|⭐⭐|❗❗|
|[被GPT带飞的In\-Context Learning为什么起作用？模型在秘密执行梯度下降](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650864545&idx=2&sn=cba397f55eb950da0fd794ae67c5c050&chksm=84e53fdfb392b6c9e2a7e360ac6d61c174691bdfdf5641f25d6caeb6adca80c5e99b50651b67&token=1087000475&lang=zh_CN&scene=21#wechat_redirect)|机器之心公众号|2022\-12\-27|介绍了一篇学术论文，旨在探究GPT背后的**In\-Context Learning**究竟如何对模型产生作用。提供了**对其工作机制的一种解释**。|⭐⭐|❗❗❗|
|[chatgpt官方blog](https://openai.com/blog/chatgpt/)|openai官网|2022\-11\-30|**ChatGPT官方Blog**|⭐⭐|❗❗|
|[OpenAI Codex 论文精读【论文精读】\_哔哩哔哩\_bilibili](https://www.bilibili.com/video/BV1iY41137Zi/?spm_id_from=333.880.my_history.page.click)|李沐|2022\-03\-11|沐神对**Codex模型的解读**，Codex是GPT3模型在代码数据上进行优化的模型版本，GitHub的Copilot功能背后使用到了Codex的能力。|⭐⭐|❗❗|
|[从零谈ChatGPT相关技术](https://mp.weixin.qq.com/s/6zwPdcoaFCEGJXelmJkIJg)|AINLP|2023\-01\-15|介绍了从**语言模型一直到ChatGPT**发展路线中的**关键技术点。**|⭐|❗❗❗|

## 技术迭代与追踪
>关注以ChatGPT为代表的大语言模型的发展历程，持续追踪前沿的技术进展。

|资料链接|来源|发布时间点|内容概述|整体推荐指数|技术难度指数|
| :-----| :-----| :-----| :-----| :-----| :-----|
|[万字拆解！追溯ChatGPT各项能力的起源](https://mp.weixin.qq.com/s/VYv8BRgGnp9ZTuXxaSuFwg)|符尧|2022\-12\-20|业内研究者符尧出品的关于**ChatGPT能力起源**的博客，讲解很清晰，对于关注技术的同学推荐阅读。|⭐⭐⭐⭐⭐|❗❗❗|
|[超越ChatGPT：大模型的智能极限](https://mp.weixin.qq.com/s/PteNTHckNAP1iVq10JuONQ)|符尧|2023-03-01|作者以终为始分析了大模型的智能极限及其演进维度。不同于刻舟求剑式只追求复现ChatGPT的经典互联网产品思维，而是指出了OpenAI组织架构和尖端人才密度的重要性，更重要的是，分享了模型演化与产品迭代及其未来，思考了如何把最深刻、最困难的问题，用最创新的方法来解决。|⭐⭐⭐⭐|❗❗|
|[开源方案复现ChatGPT流程！1\.62GB显存即可体验，单机训练提速7\.73倍](https://mp.weixin.qq.com/s/j8gvD_4ViRE4WQaQlcnmrQ)|机器之心公众号|2023\-02\-15|**Colossal\-AI** 的**开源项目**介绍，首个开源低成本**复现 ChatGPT** 完整流程。Colossal\-AI 已收获开源社区 GitHub Star 近万颗。该项目的主要亮点是提供更低成本、更高效率的**训练**、**部署**方案。|⭐⭐⭐⭐|❗❗❗|
|[ChatGPT出来后，我们是否真的面临范式转变?](https://mp.weixin.qq.com/s/60_h5biTOlBAa3Rt2tMn6A)|符尧|2022\-12\-29|业内研究者符尧出品的关于**ChatGPT**的出现会对**NLP范式**造成什么影响的分析。|⭐⭐⭐⭐|❗❗❗|
|[ChatGPT 中文调教指南](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)|Github|2022\-12\-12|**ChatGPT 中文调教指南**。各种场景使用指南。学习怎么让它听你的话。|⭐⭐⭐⭐|❗❗|
|[Meta开源的ChatGPT平替到底好不好用？测试结果、加料改装方法已出炉，2天5.2k星](https://mp.weixin.qq.com/s/kImwfWWtXMmEDVOhJZ4dJg)|机器之心公众号|2023-03-05|1)Meta 开源的大模型系列LLaMA 评测出炉，对比结果显示，和 ChatGPT 还有一些差距。2)初创公司 Nebuly AI 开源了 RLHF 版 LLaMA（ChatLLaMA）的训练方法。|⭐⭐⭐|❗||
|[单卡就能跑的大模型等效GPT-3！Meta发布大语言模型LLaMA](https://mp.weixin.qq.com/s/PEc12gEzIgv2RKxfj57FOA)|量子位公众号|2023\-02\-25|Meta一次性发布四种尺寸的大语言模型**LLaMA**：7B、13B、33B和65B，模型均开源，可以进行申请。|⭐⭐⭐|❗||
|[万字长文解析！复现和使用GPT\-3/ChatGPT，你所应该知道的](https://mp.weixin.qq.com/s/ILpbRRNP10Ef1z3lb2CqmA)|PaperWeekly公众号|2023\-02\-19|业内技术人士杨靖锋基于一系列大语言模型论文进行了归纳总结，给出了关于**复现**GPT\-3系列模型与**微调**相对小体量模型的选择的个人思考。|⭐⭐⭐|❗❗|
|[追赶ChatGPT的难点与平替](https://mp.weixin.qq.com/s/eYmssaPFODjC7xwh1jHydQ)|李rumor|2023\-02\-19|业内技术人士rumor的个人思考，关于**复现ChatGPT的难点与平替方案**。|⭐⭐⭐|❗❗|
|[ChatGPT发展历程、原理、技术架构详解和产业未来](https://zhuanlan.zhihu.com/p/590655677)|知乎|2023\-02\-11|华为前NLP首席科学家陈巍博士的一篇综述，介绍**ChatGPT的特点、功能、技术架构、局限、产业应用、投资机会和未来**。|⭐⭐⭐|❗❗|
|[Prompt设计影响ChatGPT效果](https://mp.weixin.qq.com/s/a8hjzZ_Rzl6pOU1PRAARJQ)|NewBeeNLP公众号|2023\-02\-07|ChatGPT效果不好，可能是因为**Prompt**设计的不好。|⭐⭐⭐|❗❗|
|[理工科神器Wolfram-Alpha注入超强计算知识，补足ChatGPT短板](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650866941&idx=1&sn=f0b1ea690d183dbe7233816920c3cdf0&chksm=84e4c083b3934995725df6229d87fcb8e752934e8cda5605630f4e2acbe45323dfe9a2598cb8&scene=21#wechat_redirect)|机器之心公众号|2023\-01\-27|**数学能力不足**是目前ChatGPT的一个短板，将**ChatGPT 与 Wolfram Alpha **（一个语言和计算知识搜索引擎） 相结合，可能能够弥补这一缺陷。|⭐⭐⭐|❗❗|
|[开发ChatGPT微信小程序](https://mp.weixin.qq.com/s/xVTHSMEfhwlPm2S9fug66Q)|腾讯云开发者公众号|2022\-12\-13|介绍开发接入ChatGPT的微信小程序的基本步骤。|⭐⭐⭐|❗❗❗|
|[python调用GPT\-3](https://mp.weixin.qq.com/s?__biz=MzA3ODE4NzExOA==&mid=2657735525&idx=1&sn=7c0f2ba4a070c4bfb8d42c5efe2158d4&chksm=84dbec64b3ac6572cb33b7ccaf21157dde2b47077da9474d154685156d1e1244f5970ffac931&mpshare=1&scene=24&srcid=0211bwGnCB9CPOd74eFORjay&sharer_sharetime=1676096855829&sharer_shareid=05c613ceeb202e6c66f322aff9786f90#rd)|老奇教师公众号|2023\-02\-11|使用OpenAI **API**调用**GPT3**方法。|⭐⭐|❗❗|
|[Yann LeCun：ChatGPT缺乏创新，没什么革命性；网友：早点离开Meta做出点突破吧](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650866823&idx=1&sn=3c265a169d52c20be8779ce1610d0345&chksm=84e4c0f9b39349efafe671b9a882137cbc8e23be34cd45a93ba70220f672f0e6241f334778b9&scene=21#wechat_redirect)|机器之心公众号|2023\-01\-25|在外界看来，ChatGPT 是一项巨大突破，但图灵奖得主、Meta 首席人工智能科学家 **Yann LeCun** 不这么认为。|⭐⭐|❗❗|
|[大语言模型成本分析](https://hub.baai.ac.cn/view/24047)|智源社区|2023\-02\-10|介绍OpenAI在**部署ChatGPT的成本**以及分析将ChatGPT用于**搜索引擎的成本和影响**。|⭐⭐|❗❗|
|[类ChatGPT大模型生成文本的检测方法综述](https://mp.weixin.qq.com/s/FcEscGHEaZpq7deUVZln7g)|机器之心公众号|2023\-02\-08|最近由ChatGPT生成的文本泛滥，文本介绍了**检测大模型生成文本的综述方法**：黑盒检测和白盒检测|⭐⭐|❗❗❗|
|[多模态版本ChatGPT](https://mp.weixin.qq.com/s/YkvXyjhN8vVrJdKvV0C6hA)|深度学习与图网络公众号|2023\-02\-08|介绍了多模态类ChatGPT版本**BLIP\-2**。|⭐⭐|❗❗❗|
|[nanoGPT库训练小型ChatGPT](https://mp.weixin.qq.com/s/RxoR7kdkpBT0i7HTlIO6vA)|Andrej Karpathy|2023\-01\-18|使用**nanoGPT**可以实现从头训练GPT系列模型，提供了对应的视频教程和开源项目链接。|⭐⭐|❗❗|
|[ChatGPT背后的开源AI框架Ray，现在值10亿美元](https://www.jiqizhixin.com/articles/2023-01-03-2)|机器之心公众号|2023\-01\-03|介绍了ChatGPT背后的**开源AI框架Ray**。|⭐⭐|❗❗|
|[够快！爆火的ChatGPT等价开源项目来了，网友：我担心跑不起来](https://www.jiqizhixin.com/articles/2022-12-29-11)|机器之心公众号|2022\-12\-29|介绍了一个**开源项目PaLM\-rlhf\-pytorch**。可以作为给语言模型进行RLHF训练的技术参考。|⭐⭐|❗❗❗|
|[无需人工标注，自生成指令框架打破ChatGPT等LLM的成本瓶颈](https://www.jiqizhixin.com/articles/2022-12-29-6)|机器之心公众号|2022\-12\-28|介绍了学术界的一个研究成果：**SELF\-INSTRUCT**，提供了一种几乎不需要人工标注的方法，实现了预训练语言模型与指令对齐。可以作为**减低模型训练成本**的一个参考。|⭐⭐|❗❗❗|

## 行业趋势
>ChatGPT的经济成本、商业逻辑，对不同行业会带来怎样的冲击？

|资料链接|来源|发布时间点|内容概述|整体推荐指数|技术难度指数|
| :-----| :-----| :-----| :-----| :-----| :-----|
|[万字长文，AI产品经理视角的ChatGPT全解析](https://mp.weixin.qq.com/s/InqfLtzX8F5bQnEwOp3vaA)|做产品的马丁|2023\-02\-11|一个AI产品经理出品的**ChatGPT深度解析文章**，包括技术原理、应用场景趋势的分析，以及从**AI产品经理视角的应对和思考**。|⭐⭐⭐⭐⭐|❗❗|
|[甲小姐对话李志飞：聊聊这场疯狂的AI大模型炼丹大会 甲子光年](https://mp.weixin.qq.com/s/xv78jRedygvUPOphMc00pw)|甲子光年|2023-03-10|甲子光年对出门问问CEO李志飞的深度访谈，对于AI大模型技术演进、应用场景、AGI的未来等话题表述了自己的独到见解。|⭐⭐⭐⭐|❗❗❗|
|[OpenAI逆天发布ChatGPT API！100万个单词才18元，价格打骨折](https://mp.weixin.qq.com/s/Ei0xFOBS49MulHk0rQE-7w)|新智元|2023-03-02|openAI 正式开放ChatGPT API，每输出100万个单词，价格才2.7美元（约18元人民币），比之前的GPT-3.5，成本直接降低90%。|⭐⭐⭐⭐|❗|
|[【安安访谈录】思必驰联合创始人俞凯：ChatGPT是继Alpha Go之后最大的里程碑](https://mp.weixin.qq.com/s/qhvfI6xNXzSMnUlAJLIj8Q)|安安访谈录|2023\-02\-10|对**思必驰俞凯**的访谈，谈及思必驰在**大模型**方面的**积累和规划**，谈及国内外的相关技术布局以及AIGC的未来的挑战。|⭐⭐⭐⭐|❗❗|
|[ChatGPT背后的经济账](https://mp.weixin.qq.com/s/aAg1ptEkQ6ahdjs-3s_g3A)| OneFlow公众号|2023\-02\-07|从经济学切入，对类ChatGPT模型搜索、训练GPT3以及绘制**大语言模型成本**轨迹的通用框架进行了**量化分析**，为探讨大语言模型成本结构和其未来发展提供了非常有价值的参考视角。|⭐⭐⭐⭐|❗❗❗|
|[浅谈AIGC商业化（四千字长文）](https://mp.weixin.qq.com/s/HeAmy169U7O6QEM5pWtfQQ)|AIGC产品说公众号|2023\-02\-08|从**产品经理**的角度，讲述下**AIGC**的技术和商业化现状，以及对未来发展前景的展望。|⭐⭐⭐|❗|
|[ChatGPT 真能抢走你的饭碗？我帮你问了律师、编剧、程序员。。。](https://mp.weixin.qq.com/s/7jX7ACiJScFdjpBvlyNTPQ)|差评公众号|2023\-02\-13|与各行业从业人员的讨论，ChatGPT在**各行业**的**能力边界**在哪里？对于律师、编剧、程序员等行业人员会有怎么样的冲击？|⭐⭐⭐|❗|
|[Google搜索被Chatgpt颠覆的可能性](https://blockcast.it/2023/02/08/how-much-should-google-worry-about-chatgpt/)|blockcast\.it|2023\-02\-08|关于Google搜索的商业本质，ChatGPT可能**对搜索带来的冲击和变化**的分析。|⭐⭐⭐|❗❗|
|[张俊林：ChatGPT会成为下一代搜索引擎吗](https://zhuanlan.zhihu.com/p/589533490)|张俊林|2022\-12\-06|知名深度学习Blog作者出品的关于ChatGPT技术以及**对搜索影响**的介绍。|⭐⭐⭐|❗❗|
|[ChatGPT 会取代人的哪些工作？哪些人群的职业规划需要转变？](https://www.zhihu.com/question/582809884/answer/2883146417)|知乎|2023\-02\-08|关于ChatGPT对**各行业工作**造成的**影响**的讨论。|⭐⭐|❗|
|[ChatGPT可能马上取代你！这是它能做的十个工作](https://wallstreetcn.com/articles/3681094)|华尔街见闻|2023\-02\-06|媒体网站 Insider 在与专家交谈和进行研究后，整理了一份被人工智能技术**取代风险**最高的**工作类型清单**。|⭐⭐|❗|
|[ChatGPT 爆火，谷歌投资其竞品公司，谷歌创始人亲自下场改代码，这场 AI 风暴对巨头们有何冲击？](https://www.zhihu.com/question/582114806)|知乎|2023\-02\-05|ChatGPT的爆火，引起**科技巨头**们的担忧，这项技术会引领下一项**技术革命**吗？会对他们发展产生怎样的影响？|⭐⭐|❗|
|[普通用户玩不起的GPT\-3 API，已在300多个应用中部署了](https://www.jiqizhixin.com/articles/2021-03-26-4)|机器之心公众号|2021\-03\-26|早期对于**GPT3**的**应用场景**的介绍，可供参考。|⭐⭐|❗|

## 行业应用与探索
>关注ChatGPT的应用方向探索，其对搜索引擎等方向可能带来巨大变革。

|资料链接|来源|发布时间点|内容概述|整体推荐指数|技术难度指数|
| :-----| :-----| :-----| :-----| :-----| :-----|
| [58AI\-lab: ChatGPT应用思考](https://mp.weixin.qq.com/s/ldRCykw7jvuIusmsk7QhKQ) | 58AIlab公众号 | 2023\-02\-21 | **58同城AI lab**发表的文章，介绍了在多个**实际业务场景**中使用ChatGPT来优化业务的经验，也与微调模型的方法进行了**对比**，有一定的参考价值。 | ⭐⭐⭐⭐ | ❗❗ |
| [让ChatGPT长“手”！Meta爆火新论文，让语言模型学会自主使用工具](https://mp.weixin.qq.com/s/tcuj-f6-2sP4DoiKRsVAMw) | 机器学习算法与自然语言处理公众号 | 2023\-02\-14 | **Meta**发布的一篇论文，瞄准ChatGPT的“软肋”，让大语言模型自行学会了**使用工具（API）** ！<br> 给我们的提示：通过设计prompt让ChatGPT可以调用外部接口，**扩展其能力边界**。 | ⭐⭐⭐⭐ | ❗❗ |
| [不出所料，自动驾驶向ChatGPT下手了！](https://mp.weixin.qq.com/s/a5A2mfG8WQElIuo5vT2s7w) | 机器之心公众号 | 2023\-02\-10 | ChatGPT 的技术思路与**自动驾驶**能碰撞出什么样的火花呢？ | ⭐⭐⭐⭐ | ❗❗ | 
| [今天，微软重新发明搜索引擎：首款ChatGPT搜索来了](https://www.jiqizhixin.com/articles/2023-02-08) | 机器之心公众号 | 2023\-02\-08 | 通过与 ChatGPT 发明者 OpenAI 合作，**微软**给自己的**搜索引擎**加入了先进的 AI 对话模型，以支持**全新版本**的**必应（Bing）** 和 Edge。 | ⭐⭐⭐⭐ | ❗❗ | 
| [ChatGPT版搜索引擎登场](https://mp.weixin.qq.com/s/MRmgIyw_SQNi9nNHsRtyfg) | 智东西公众号 | 2023\-02\-08 | 关于微软推出的**新Bing**搜索引擎的**功能特性**及**亮点**的详细介绍。 | ⭐⭐⭐⭐ | ❗❗ | 
| [ChatGPT讲故事，DALLE\-2负责画出来，两AI合作出绘本](https://www.jiqizhixin.com/articles/2022-12-12-2) | 机器之心公众号 | 2022\-12\-10 | 来自斯坦福大学计算机科学系的博士生 Eric Zelikman 先用 ChatGPT 写了儿童故事，然后让之前火了大半年的 DALLE\-2 将其画了出来。初步尝试了用两个 **AI 合作**做出一本绘本的实验。 | ⭐⭐⭐⭐ | ❗ | 
|[Prompt Engineering全面自动化：LeCun看了沉默，ChatGPT看了直呼内行](https://mp.weixin.qq.com/s/aj8Ls463jpF92ssn6Acwzg)|机器之心公众号|2023-03-08|jina.ai 发布的 promptperfect，帮助你生成可以更好让机器执行任务的prompt，包括语言模型、以及文生图系列模型（stable diffusion）等。|⭐⭐⭐|❗|
|[ChatPDF也来了！一键上传文件即可解读，复制粘贴都省了](https://mp.weixin.qq.com/s/XINHbYX-K6v0J7Zu3W3swQ)|量子位公众号|2023-03-07|基于ChatGPT的衍生应用ChatPDF,ChatPDF的操作很简单，把自己的PDF上传到页面上，它就会开始加载分析，然后切换到提问界面。|⭐⭐⭐|❗|
| [别只骂谷歌Bard了，ChatGPT加持的微软New Bing也错误频出](https://mp.weixin.qq.com/s/euMIkTWOoqRrbL8rZ8-KIA) | 机器之心公众号 | 2023\-02\-13 | ChatGPT并非完美，ChatGPT加持的微软**New Bing**在评测中也暴露出了很多**问题**，体现了其**能力边界**，值得关注。 | ⭐⭐⭐ | ❗ | 
| [ChatGPT竟有9岁小孩心智？斯坦福教授逆天发现](https://mp.weixin.qq.com/s/cIs6BV0XOVtq_HeXoNmJzQ) | 新智元公众号 | 2023\-02\-12 | 一位斯坦福教授在上周发布的论文中证实通过实验得出**GPT\-3\.5**（davinci\-003）和**GPT\-3**（2022年1月新版，davinci\-002）具有心智的理论。 | ⭐⭐⭐ | ❗❗ | 
| [ChatGPT版必应被华人小哥攻破，一句话「催眠」问出所有Prompt](https://mp.weixin.qq.com/s/izeryOoUI8qe4jjBypk2Rw) | 转载自量子位 | 2023\-02\-11 | 一个华人用户贴出的对**新版必应**（引入ChatGPT）的一个测试case，通过引入**特殊的提示**，似乎使其内部的**配置泄露**了。之前也有过不少大家通过配置一些特殊的提示，让ChatGPT突破其默认设置的安全边界的案例。 | ⭐⭐⭐ | ❗❗ ❗| 
| [ChatGPT还有什么不会？招行信用卡用它写出金融业首篇AIGC](https://mp.weixin.qq.com/s/ZYpeHJE4vJLPwNCaSJ30cg) | 机器之心公众号 | 2023\-02\-06 | ChatGPT首秀**金融界**，**招行信用卡**用ChatGPT诠释什么是亲情。 | ⭐⭐⭐ | ❗ | 
| [再记公式弱爆了！用ChatGPT处理Excel问题，效率狂升](https://zhuanlan.zhihu.com/p/604195485) | 机器之心公众号 | 2023\-02\-06 | AI 爱好者使用 ChatGPT 写**Excel 公式**，工作效率妥妥提高 10 倍。 | ⭐⭐⭐ | ❗ | 
| [微软又出大招，ChatGPT将加入云服务](https://www.jiqizhixin.com/articles/2023-01-17-4) | 机器之心公众号 | 2023\-01\-17 | ChatGPT 计划接入**微软云服务**，将和**Bing**和**Office**进行整合，实现强强联合。 | ⭐⭐⭐ | ❗ | 
| [B站UP主硬核自制智能音箱：有ChatGPT加持，才是真・智能](https://www.jiqizhixin.com/articles/2023-01-16-3) | 机器之心公众号 | 2023\-01\-16 | 用ChatGPT 改造一下音箱，自制一款智能且强大的**语音助理**。 | ⭐⭐⭐ | ❗ | 
| [我用ChatGPT写神经网络：一字不改，结果竟然很好用](https://www.jiqizhixin.com/articles/2023-01-13-7) | 机器之心公众号 | 2023\-01\-13 | 用AI写AI，ChatGPT生成**手写字识别代码**，使用 Keras 解决 MNIST 问题。 | ⭐⭐⭐ | ❗❗❗ | 
| [爆火的ChatGPT太强了！写代码、改bug，网友：可取代Stack Overflow了](https://zhuanlan.zhihu.com/p/589418353) | 机器之心公众号 | 2022\-12\-05 | ChatGPT 具备与**编程相关**的基础知识，可以帮你写代码，还能修改代码中bug。 | ⭐⭐⭐ | ❗ | 

## 行业规范与法律法规
>ChatGPT使用中应遵循的行业规范以及潜在的法律风险

|资料链接|来源|发布时间点|内容概述|整体推荐指数|技术难度指数|
| :-----| :-----| :-----| :-----| :-----| :-----|
| [ChatGPT内容商业使用的法律风险及应对](https://mp.weixin.qq.com/s/8fzvmnyhEbIwWVTAVm8WWA) | 天元律师事务所 | 2023\-02\-13 | 对于**国内公司**而言，是否可以使用ChatGPT作为生产力工具，这过程中又存在哪些**法律风险**，本文中予以解读及提示。 | ⭐⭐⭐⭐ | ❗❗ | 
| [ChatGPT让Nature一周发两文探讨：学术圈使用不可避免，是时候明确使用规范](https://mp.weixin.qq.com/s/lBltp0oi2dvVVF6uyiKw2w) | Nature |2023\-02\-11 | **Nature**发布的关于ChatGPT的**使用风险**和**规范**的建议。 | ⭐⭐⭐ | ❗ | 

## openAI发展思考
>为什么openAI能够抢占先机，在google之前掀起通用人工智能的热潮，其背后的原因是什么？

|资料链接|来源|发布时间点|内容概述|整体推荐指数|技术难度指数|
| :-----| :-----| :-----| :-----| :-----| :-----|
| [OpenAI 何以掀翻 Google 布局多年的AI大棋？](https://mp.weixin.qq.com/s/qWQ6xVfQVEOJriYRVFWCrQ) | 出门问问李志飞 | 2023\-02\-08 | 关于**OpenAI**与**Google**今年的技术布局，Google错失的关键节点以及OpenAI成功原因的深入思考。 | ⭐⭐⭐⭐ | ❗❗ | 
| [为什么说openai的ceo是下一代的商业领袖](https://mp.weixin.qq.com/s/SA1LKzoZoivbb76UqwZ5VQ) | 做AI做的事儿公众号 | 2023\-02\-03 | 关于OpenAI的CEO **Sam Altman** 的个人人生经历和观点输出的深入介绍。 | ⭐⭐⭐ | ❗❗ | 
| [OpenAI CEO谈GPT\-4：今年发不发不确定，我们没有AGI，或许让大家失望](https://www.jiqizhixin.com/articles/2023-01-19-3) | The Verge | 2023\-01\-19 | 在最近的一次采访中，OpenAI 的 CEO Sam Altman 谈到关于 **GPT\-4** 的发布问题时，明确**否认了网传的发布时间**。 | ⭐⭐⭐ | ❗❗ | 
| [百倍利润封顶：OpenAI宣布转型为营利公司，Sam Altman任CEO](https://www.jiqizhixin.com/articles/2019-03-12-3) | 机器之心公众号 | 2019\-03\-12 | OpenAI宣布成立**OpenAI LP**，转型为盈利公司，以此快速增加对于计算和人才的投资。 | ⭐⭐⭐ | ❗ | 
| [向OpenAI追资数十亿美元，微软押注AI突破，瞄准与谷歌竞争](https://www.jiqizhixin.com/articles/2023-01-24-2) | 机器之心公众号 | 2023\-01\-24 | **微软**宣布将向 OpenAI **追加投资数十亿美元**，加深与后者合作，为与谷歌母公司 Alphabet 展开更多竞争奠定基础。 | ⭐⭐ | ❗ | 
| [微软10亿美元入局，拥有无限算力的OpenAI，真的能实现AGI吗？](https://www.jiqizhixin.com/articles/2019-07-23-4) | 机器之心公众号 | 2019\-07\-23 | **微软**向 OpenAI 投资 **10 亿美元**，并成为 OpenAI 的独家云计算服务提供商，二者将合作开发新技术。 | ⭐⭐ | ❗ | 
| [OpenAI：马斯克发起10亿美元非营利AI研究项目](https://www.jiqizhixin.com/articles/2015-12-12-2) | Popsci | 2015\-12\-12 | OpenAI早期的**发展目标**和**研究方向**。 | ⭐⭐ | ❗ | 

## 业界跟进-同类产品信息
>ChatGPT对国内外的科技企业带来巨大的心灵冲击，关注业界的跟进节奏、产品信息。

|资料链接|来源|发布时间点|内容概述|整体推荐指数|技术难度指数|
| :-----| :-----| :-----| :-----| :-----| :-----|
| [颠覆历史！「ChatGPT搜索引擎」发布，微软市值一夜飙涨5450亿](https://mp.weixin.qq.com/s/03EDC_Vl8SAM52oJvkX5SA) | 新智元 | 2023\-02\-08 | 微软Bing、Google的Bard、百度的文心一言。ChatGPT将给**搜索引擎**带来**巨大变革**。 | ⭐⭐⭐⭐ | ❗ | 
| [挑战ChatGPT，谷歌正式发布Bard，CEO亲自下场邀请测试](https://mp.weixin.qq.com/s/GUlsUH3i0h8x675RqB5-Dw) | 机器之心公众号 | 2023\-02\-07 | 为应对ChatGPT带来的巨大冲击，谷歌发布下一代对话AI系统**Bard**并邀请测试。 | ⭐⭐⭐⭐ | ❗ | 
| [ChatGPT还在2G冲浪？新模型「youChat」：我已能够解说2022世界杯](https://mp.weixin.qq.com/s/HQDfdgtDhRvSWSdiPQEPcg) | 机器之心公众号 | 2022\-12\-24 | 搜索引擎**You\.com** 公司 发布**youChat**，其具有与 ChatGPT 类似的功能，用户可以在搜索引擎的「Chat」选项栏进行对话。 | ⭐⭐⭐⭐ | ❗ ||
|[立即体验！直接可用的中文版ChatGPT来了](https://mp.weixin.qq.com/s/uV4rjy3aBaHLnT5RsLqbZA)|机器之心公众号|2023-02-28|秘塔加入了打造中国版 ChatGPT 的战局，推出了一款新产品 ——「对话写作猫」，是目前首个可以直接使用的国产自研版本。可以免费体验。https://xiezuocat.com/chat |⭐⭐⭐|❗||
| [小冰CEO李笛：小冰链不是中国版ChatGPT](https://mp.weixin.qq.com/s/ErujYGRmvsfGSttkjCHukQ) | 新智元公众号 | 2023\-02\-21 | 小冰推出的**小冰链**，和ChatGPT的核心区别：<br> 1. 小冰链的**数据来源**是实时的，而ChatGPT是从训练数据中总结的；<br> 2. 小冰链能展现**逻辑思维过程**，更透明、可观测，而ChatGPT完全是个黑盒子；<br> 3. 最本质的区别是，小冰链会自己进行**下一步的行动**，比如上网搜索，而ChatGPT只是对话生成，并没有行动。 | ⭐⭐⭐| ❗❗ | 
| [复旦团队发布国内首个类 ChatGPT 模型 MOSS，将为国内大语言模型的探索和应用带来哪些影响?](https://www.zhihu.com/question/585248111/answer/2903113992) | 知乎 | 2023\-02\-21 | 国内第一个对话式大型语言模型MOSS已由复旦大学**邱锡鹏**教授团队发布至公开平台（[https://moss\.fastnlp\.top/](https://link.zhihu.com/?target=https%3A//moss.fastnlp.top/)），邀公众参与内测。后续有**开源**代码和模型参数的计划，值得关注。（ps:由于访问超负荷，目前无法体验。） | ⭐⭐⭐ | ❗ | 
| [昆仑万维CEO方汉：ChatGPT的开源来得有多快？](https://mp.weixin.qq.com/s/hGyJlwUGSO9llWAP30FfQQ) | 昆仑万维 | 2023\-02\-13 | **昆仑万维CEO**方汉的访谈记录，提及了对ChatGPT的看法，昆仑万维在AIGC的积累，宣布将与奇点智源合作，在今年内发布**中国版类ChatGPT代码开源**，防止大公司技术垄断。 | ⭐⭐⭐ | ❗ | 
| [谷歌版ChatGPT首秀，第一个Demo就大翻车，市值暴跌7000亿](https://zhuanlan.zhihu.com/p/604771292) | 机器之心公众号 | 2023\-02\-09 | **Bard **是现在在科技界爆红、给谷歌搜索带来巨大威胁的 ChatGPT 的**竞品**，备受期待的 Bard 却出师不利。 | ⭐⭐⭐ | ❗ | 
| [ChatGPT原班人马成立的公司，被谷歌紧急投了4亿美元](https://zhuanlan.zhihu.com/p/603621519)| 机器之心公众号 | 2023\-02\-04 | 谷歌投资了一家由前 OpenAI 员工创立的公司: **Anthropic**。而该公司推出的生成式 AI 模型 **「Claude」 ** ，被认为是 ChatGPT 的有力竞争者。 | ⭐⭐⭐ | ❗ | 
| [对标ChatGPT，新聊天机器人Claude来了](https://mp.weixin.qq.com/s/GNEhSbmIqlflpbAtJ3e33A) | 腾讯技术工程 | 2023\-02\-02 | 详细介绍了**Claude**模型背后的**技术方案**，以及与ChatGPT方案的差异。 | ⭐⭐⭐ | ❗ | 
| [OpenAI新老员工对决！「叛徒」团队发布Claude模型：ChatGPT的RLHF过时啦！](https://mp.weixin.qq.com/s/si2M52H1qKnyHd0IHVJR8g) | 新智元 | 2023\-01\-29 | 脱胎于OpenAI的初创公司**Anthropic**推出新产品**Claude**模型，对标ChatGPT。 | ⭐⭐⭐ | ❗❗❗ | 
| [美团大佬连夜冲向ChatGPT风口！自带3\.5亿进场，只有一个判断：必须参与](https://mp.weixin.qq.com/s/aFL0fLIgi78yzjqYuGzwDA) | 量子位 | 2023\-02\-11 | 国内公司对ChatGPT的跟进，原美团联合创始人**王慧文**以及**周鸿祎**等对ChatGPT都很重视。 | ⭐⭐ | ❗ | 
| [科大讯飞被曝加紧开发中国版ChatGPT，具体发布时间已确定](https://mp.weixin.qq.com/s/o8D9GGlkmJ_RvaDL9filEQ) | 量子位 | 2023\-02\-10 | 关于国内打造ChatGPT相关产品的**条件思考**、**可能性评估**，以及**国内外相关产品**落地的差异。 | ⭐⭐ | ❗ | 
| [阿里版ChatGPT已进入测试！中文聊天截图曝光，达摩院出品](https://mp.weixin.qq.com/s/xQmX9EnrKLAUxsEoCZXJVg) | 量子位 | 2023\-02\-09 | 关于**阿里版ChatGPT**的介绍，国内科技厂商都加大了对ChatGPT相关产品的投入。 | ⭐⭐ | ❗ | 
| [首个中文版ChatGPT来了：大模型的中国元“Yuan”](https://www.jiqizhixin.com/articles/2023-02-07-3) | 机器之心公众号 | 2023\-02\-07 | 国内通用人工智能初创公司**元语智能**，推出国内首个基于大模型的功能型对话产品 **ChatYuan**。 | ⭐⭐ | ❗❗ | 
