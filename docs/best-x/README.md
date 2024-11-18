# prompt-collection-quickstart

```
group together the pro and con cases for each arguement 
```

```
请把下面代码里的prompt抽取出来，并转化成易于中国人阅读和理解的格式,花括号里面内容保持原文。只需要提供prompt原文，不要说其他无关内容。
```


---------

# 生成图片 - 1
```
用 DALL-E 给文章配图我是这么用的：

首选选择 DALL-E 的 GPT 而不是 ChatGPT，这是 OpenAI 官方的专业做图的 GPT，不容易幻觉去做其他任务，从 GPT Store 可以很容易找到，链接：https://chatgpt.com/g/g-2fkFE8rbu-dall-e

然后从底部选择风格和尺寸比例，或者自己直接 Prompt 写什么风格也可以

提示词我比较偷懒，直接把全文贴进去让其生成，通常都还不错
“Kawaii, wide aspect ratio，请根据下面文章内容生成一张配图： <全文>”

生成的结果点击后可以二次编辑，局部修改
```


# 总结 - 1
```
将三个引号之间的文本摘要成大约50个字。

"""insert text here"""
```
# 总结 - 2
```
总结两段中用三引号分隔的文本。

"""insert text here"""
```

# 总结 -3 
```
将由三引号分隔的文本总结为 3 个要点。

"""insert text here"""
```

# RAG答案合成 - 1
```
使用提供的由三重引号引起来的文章来回答问题。 如果在文章中找不到答案，请写“我找不到答案”。

<插入文章，每篇文章均由三引号分隔>

问题：<在此插入问题>
```
# RAG答案合成 - 例子
```
使用提供的由三重引号引起来的文章来回答问题。 如果在文章中找不到答案，请写“我找不到答案”。

"""小红喜欢牡丹花"""
"""小白也喜欢牡丹花"""
"""小唐喜欢小红"""

问题：小红被什么喜欢？
```

```
您将获得一份由三重引号和一个问题分隔的文档。 您的任务是仅使用提供的文档回答问题，并引用用于回答问题的文档段落。 如果文档不包含回答此问题所需的信息，则只需写：“信息不足”。 如果提供了问题的答案，则必须附有引文注释。 使用以下格式引用相关段落（{“引用”：…}）。

"""中国人口和56个民族
 

中华民族有着悠久的历史。从遥远的古代起，中华各民族人民的祖先就劳动、生息、繁衍在中华大地上，共同为中华文明和建立统一的多民族国家而贡献自己的才智。

 

据中国政府考察统计正式确认的中华人民共和国民族共有56个，其他为未识别的民族。

 

据第六次全国人口普查主要数据：汉族人口比重最大，约占全国人口总数的91.51%左右，其它55个民族总人口偏少，约占全国总人口的8.49%左右，故称其为少数民族。

 

全国55个少数民族中人口最多的是壮族，人口超过1600万（2000年）；最少的是珞巴族，人口不足3000人（2000年）（未包括中印争议的藏南地区60万珞巴族人）。

 

分布特点
  

 中国各民族分布的特点是：大杂居、小聚居、相互交错居住。汉族地区有少数民族聚居，少数民族地区有汉族居住。这种分布格局是长期历史发展过程中，各民族间相互交往、流动而形成的。中国少数民族人口虽少，但分布很广。全国各省、自治区、直辖市都有少数民族居住，绝大部分县级单位都有两个以上的民族居住。中国的少数民族，主要分布在内蒙古、新疆、宁夏、广西、西藏、云南、贵州、青海、四川、甘肃、黑龙江、辽宁、吉林、湖南、湖北、海南、台湾等省、自治区。中国民族成分最多的是云南省，有25个民族。
 
 
地理资源
 

中国地域辽阔，资源丰富。民族区域自治制度是国家的一项基本政治制度，中国政府一直致力于推进民族区域自治制度，保证少数民族当家做主管理本民族内部事务的权利。据《中国的民族区域自治》白皮书载，中国的55个少数民族中，有44个建立了自治地方，实行区域自治的少数民族人口占少数民族总人口的71%。中国民族自治地方的面积占全国国土总面积的64%左右；草原面积占全国的75%，中国著名的5大天然牧区，都在少数民族地区；森林面积占全国的43.9%；林木蓄积量占全国的55.9%；水力资源蕴藏量占全国的65.9%。此外，还有大量的矿藏资源，以及丰富的动植物资源和旅游资源。

 

各民族人口
 

新中国成立后，中国政府对少数民族实行了宽于汉族的生育政策。

 

为提高少数民族人口素质，加快民族自治地方的经济社会发展，中国各民族自治地方的人民代表大会，根据国家有关少数民族也要实行计划生育的精神，制定了该地区少数民族的计划生育政策，但其政策宽于汉族的生育政策。这使得少数民族人口的增长速度高于全国平均水平。

 

全国五次人口普查结果表明，中国少数民族：1953年7月1日为3532万人，1964年7月1日为4000万人，1982年7月1日为6724万人，1990年7月1日为9120万人，2000年11月1日为10643万人。

 

据2000年第五次全国人口普查统计，中国大陆31个省、自治区、直辖市共有12.9533亿人。其中汉族115940万人，占91.59%；少数民族10643万占8.41%（同1990年第四次全国人口普查相比，汉族人口增加了11692万人，增长了11.22%；各少数民族人口增加了1523万人，增长了16.70%）。

 

第六次全国人口普查显示：大陆31个省、自治区、直辖市和现役军人的人口中，汉族人口为1225932641人，占91.51%；各少数民族人口为113792211人，占8.49%。同2000年第五次全国人口普查相比，汉族人口增加66537177人，增长5.74%；各少数民族人口增加7362627人，增长6.92%。
"""

"""
政区类型
播报
编辑
中华人民共和国省级行政区是中央人民政府直接管辖的最高一级地方行政区域，包括四种类型：省、自治区、直辖市和特别行政区。《中华人民共和国宪法》第三十条规定：全国分为省、自治区、直辖市。自治区是省级民族自治地方。第三十一条规定：国家在必要时得设立特别行政区。在特别行政区内实行的制度按照具体情况由全国人民代表大会以法律规定。 [2] [4]
省，是中国国家地方一级行政区域，名称起源于元代，一直沿用至今，已有六、七百年的历史。 [1-2]
自治区，是中华人民共和国少数民族聚居地方实行民族区域自治而建立的相当于省的行政区域。 [1-2]
直辖市，即中央直辖市，由国务院直接管辖。是人口比较集中，在政治、经济、文化等方面具有特别重要地位的大城市。 [1-2]
特别行政区，是为“一国两制”的实施而设立的享有高度自治权的地方行政区域。与省、自治区、直辖市同属直辖于中央人民政府的地方行政区域。 [2] [12]
中华人民共和国成立初期，除了省、自治区、直辖市，还设有相当于省级行政区的行署区、地方、地区；在省级行政区之上，还有6个大行政区，作为一级地方行政单位，即东北、华北、华东、中南、西北、西南六大行政区。 [3] [5]
"""

"""
中华民族有着悠久的历史。从遥远的古代起，中华各民族人民的祖先就劳动、生息、繁衍在中华大地上，共同为中华文明和建立统一的多民族国家而贡献自己的才智。 [2]
据中国政府考察统计正式确认的中华人民共和国民族共有56个，其他为未识别的民族 [1]。 [2]
据第六次全国人口普查主要数据：汉族人口比重最大，约占全国人口总数的91.51%左右，其它55个民族总人口偏少，约占全国总人口的8.49%左右，故称其为少数民族。 [6]
全国55个少数民族中人口最多的是壮族，人口超过1600万（2000年） [3]；最少的是珞巴族，人口不足3000人（2000年） [4]（未包括中华人民共和国的固有领土藏南地区的60万珞巴族人）。
"""

问题：中国有多少个省份和民族?
```



# RAG答案合成 - 2
```
您将获得一份由三重引号和一个问题分隔的文档。 您的任务是仅使用提供的文档回答问题，并引用用于回答问题的文档段落。 如果文档不包含回答此问题所需的信息，则只需写：“信息不足”。 如果提供了问题的答案，则必须附有引文注释。 使用以下格式引用相关段落（{“引用”：…}）。

"""<在此插入文档>"""

问题：<在此插入问题>
```
# RAG答案合成 - 例子
```
您将获得一份由三重引号和一个问题分隔的文档。 您的任务是仅使用提供的文档回答问题，并引用用于回答问题的文档段落。 如果文档不包含回答此问题所需的信息，则只需写：“信息不足”。 如果提供了问题的答案，则必须附有引文注释。 使用以下格式引用相关段落（{“引用”：…}）。

"""小红喜欢牡丹花"""
"""小白也喜欢牡丹花"""
"""小唐喜欢小红"""


问题：小红喜欢什么？
```

# 分解任务 - 1
```
我们将向您提供客户服务查询。 将每个查询分为主要类别和次要类别。 提供 json 格式的输出，其中包含以下键：主要和次要。

主要类别：计费、技术支持、帐户管理或一般查询。

计费二级类别：
- 取消订阅或升级
- 添加付款方式
- 收费说明
- 对收费提出争议

技术支持二级分类：
- 故障排除
- 设备兼容性
- 软件更新

账户管理二级分类：
- 重设密码
- 更新个人信息
- 关闭账户
- 账户安全

一般查询二级类别：
- 产品信息
- 价钱
- 反馈
- 与人类交谈

查询：我需要让我的互联网重新工作
```
# 分解任务 - 2
```
您将收到需要在技术支持环境中进行故障排除的客户服务查询。 通过以下方式帮助用户：

- 请他们检查所有进出路由器的电缆是否已连接。 请注意，随着时间的推移，电缆松动是很常见的。
- 如果所有电缆均已连接并且问题仍然存在，请询问他们正在使用哪种路由器型号
- 现在您将建议他们如何重新启动设备：
-- 如果型号是 MTD-327J，建议他们按下红色按钮并按住 5 秒钟，然后等待 5 分钟后再测试连接。
-- 如果型号是 MTD-327S，建议他们拔下并重新插入，然后等待 5 分钟再测试连接。
- 如果客户的问题在重新启动设备并等待 5 分钟后仍然存在，请通过输出 {“IT 支持请求”} 将他们连接到 IT 支持。
- 如果用户开始询问与此主题无关的问题，请确认他们是否想结束当前有关故障排除的聊天，并根据以下方案对他们的请求进行分类：

<在此处插入上面的主要/次要分类方案>

查询：我需要让我的互联网重新工作。
```

# 判断对错 - 1
```
确定学生的解决方案是否正确。
问题陈述：我正在建造一个太阳能发电装置，我需要帮助解决财务问题。
- 土地成本 100 美元/平方英尺
- 我可以以 250 美元/平方英尺的价格购买太阳能电池板
- 我协商了一份维护合同，每年将花费我 10 万美元，每平方英尺额外花费 10 美元
第一年运营的总成本是多少，与平方英尺数的函数关系。

学生的解决方案：设 x 为装置的尺寸（以平方英尺为单位）。
1.土地成本：100x
2.太阳能电池板成本：250x
3.维护成本：100,000 + 100x
总成本：100x + 250x + 100,000 + 100x = 450x + 100,000

Assistant：
```

```
确定学生的解决方案是否正确。
问题陈述：中国有多少个省份和民族?

学生的解决方案："""
中国有以下数量的省份和民族：

省份：中华人民共和国省级行政区包括省、自治区、直辖市和特别行政区。共有31个省、自治区、直辖市和台湾等地区。{“政区类型”：省、自治区、直辖市}
民族：中国共有56个民族，其中汉族占绝大多数，其他55个民族称为少数民族。{“中国人口和56个民族”}
"""

Assistant：
```



# 判断对错 - 2
```
首先制定自己的问题解决方案。 然后将你的解决方案与学生的解决方案进行比较，并评估学生的解决方案是否正确。 在你自己完成问题之前，不要决定学生的解决方案是否正确。

问题陈述：我正在建造一个太阳能发电装置，我需要帮助解决财务问题。
- 土地成本 100 美元/平方英尺
- 我可以以 250 美元/平方英尺的价格购买太阳能电池板
- 我协商了一份维护合同，每年将花费我 10 万美元，每平方英尺额外花费 10 美元
第一年运营的总成本是多少，与平方英尺数的函数关系。

学生的解决方案：设 x 为装置的尺寸（以平方英尺为单位）。
1.土地成本：100x
2.太阳能电池板成本：250x
3.维护成本：100,000 + 100x
总成本：100x + 250x + 100,000 + 100x = 450x + 100,000

Assistant：
```
# 回答问题
```
请按照以下步骤回答用户的疑问。

步骤 1 - 首先找出你自己的问题解决方案。 不要依赖学生的解决方案，因为它可能是不正确的。 将这一步的所有工作用三引号 (""") 括起来。

第 2 步 - 将您的解决方案与学生的解决方案进行比较，并评估学生的解决方案是否正确。 将这一步的所有工作用三引号 (""") 括起来。

第 3 步 - 如果学生犯了错误，请确定在不泄露答案的情况下可以给学生什么提示。 将这一步的所有工作用三引号 (""") 括起来。

步骤 4 - 如果学生犯了错误，请向学生提供上一步的提示（在三重引号之外）。 不要写“步骤 4 - ...”，而写“提示：”。

问题陈述：<插入问题陈述>

学生解决方案：<插入学生解决方案>
```
# 回答问题，判断对错，并给出分析
```
将您的解决方案与学生的解决方案进行比较，并评估学生的解决方案是否正确。

问题陈述：“”“<插入问题陈述>”“”

您的解决方案：“”“<插入模型生成的解决方案>”“”

学生的解决方案：“”“<插入学生的解决方案>”“”
```

# 自动批阅答案
```
你是一名数学导师。 如果学生犯了错误，请以不透露答案的方式向学生提供提示。 如果学生没有犯错，只需给他们一个鼓励性的评论。
问题陈述：“”“<插入问题陈述>”“”

您的解决方案：“”“<插入模型生成的解决方案>”“”

学生的解决方案：“”“<插入学生的解决方案>”“”

分析：“”“<插入上一步中模型生成的分析>”“”
```


# 生成代码
```
请提供一个python函数，实际上达到的是下面shell代码同等效果。其中$OPENAI_API_KEY，$USERINPUT作为用户输入参数。
--------
{}
```


# 生成代码 - 例子.
```
请提供一个python函数，实际上达到的是下面shell代码同等效果。其中$OPENAI_API_KEY，$USERINPUT作为用户输入参数。
--------
curl https://api.openai.com/v1/moderations \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $OPENAI_API_KEY" \
  -d '{
    "input": "$USERINPUT"
  }'
```

# 评分（1-5分）
```
给定指令和输出，从 1（最低）到 5（最高）对响应是否对查询有帮助且信息丰富的答案进行评分。 我们将此分数称为感知效用。

详细标准如下：
5：响应提供了对查询的完整、高度详细且信息丰富的响应，完全满足信息需求。
4：响应大部分满足查询中的需求，同时可以进行一些小的改进，例如讨论更详细的信息、具有更好的响应结构或提高连贯性。
3：响应可以接受，但需要一些重大的补充或改进才能满足用户的需求。
2：响应仍然解决主要请求，但不完整或与查询不相关。
1：回复几乎不切题或完全不相关。
##
说明：截至 2023 年，英国现任首相是谁？
输出：鲍里斯·约翰逊 (Boris Johnson) 于 2019 年至 2022 年担任英国首相。
感知效用：2
解释：虽然输出提供了有关 2019 年至 2022 年英国首相的事实正确的陈述，但此指令询问 2023 年的首相是谁，因此它没有回答该指令。 因此，效用为2。

##
说明：根据旅游目的地的描述，推荐10个旅游景点，并逐个详细说明。 旅行目的地是日本东京。
输出：“东京是一座充满活力的城市，充满了令人兴奋的旅游景点。 一些必看景点包括东京晴空塔、东京迪士尼乐园、浅草寺、明治神宫、筑地鱼市场、原宿和新宿御苑。
感知效用：3
说明：此输出不提供每个景点的描述，并且景点的数量也少于 10 个。虽然此输出部分回答了说明，但与说明并不严格匹配。

##
指令：{指令}
输出：{输出}
```