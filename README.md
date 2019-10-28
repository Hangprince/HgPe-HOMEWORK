# LSH'S HOMEWORK
<details>
<summary>forth-assignment</summary>
 
上海强制垃圾分类措施一经颁布，就掀起全国范围内的热烈讨论，除了一些赞成或困惑的声音之外，其他城市的居民则持观望态度。

自上海7月1日起正式实施强制垃圾分类后，全国多地陆续传出即将推行垃圾分类制度的消息。垃圾分类已不再仅仅是上海的事。据住建部信息，2020年，包括北京、天津、上海、石家庄等在内的46个重点城市，将基本建成生活垃圾分类处理系统；2025年，全国地级及以上城市都将实行强制垃圾分类。

7月3日，北京市城市管理委员会透露，北京将于2020年正式对《北京市生活垃圾管理条例》进行修订，届时将实施强制垃圾分类。《北京市生活垃圾管理条例修正案（草案送审稿）》（以下简称《修正案》）日前公开征求意见。

据生态环境部公布的数据显示，中国生活垃圾的产生总量正在持续增长，2017年达到约2.15亿吨，其中，北京生活垃圾生产量最大。以京沪两地作为对比，2017年，两座城市产生的生活垃圾均在900万吨以上，与10年前相比，上海年生活垃圾产量增长了32.7%，北京的增幅更为显著，达到了37.5%。平均到每个人，2017年上海每人每天产生1.02公斤垃圾，北京则有1.17公斤。　

![image](https://github.com/Hangprince/LSH-S-HOMEWORK/blob/master/images/%E5%8C%97%E4%BA%AC%E4%B8%8A%E6%B5%B7%E7%94%9F%E6%B4%BB%E5%9E%83%E5%9C%BE%E6%8C%81%E7%BB%AD%E4%B8%8A%E6%B6%A8.png)

</details>

<details>
<summary>third-assignment</summary>
 
我使用的数据集是kaggle官网上的2017年世界幸福报告[link](https://www.kaggle.com/unsdsn/world-happiness)
 
《世界幸福报告》是对全球幸福状况的里程碑式调查。2017年3月20日，在庆祝国际幸福日的活动上，联合国发布了《2017年幸福世界》，按幸福等级对155个国家进行排名。随着政府，组织和民间社会越来越多地使用幸福指标来指导其决策，该报告继续获得全球认可。经济学，心理学，调查分析，国家统计，卫生，公共政策等领域的领先专家描述了如何有效地使用幸福感测度来评估国家的进步。
 
幸福分数和排名使用盖洛普世界民意调查的数据。幸福评分后面的各栏估算了六个因素（经济生产，社会支持，预期寿命，自由，没有腐败和慷慨）中每个因素在何种程度上有助于使每个国家的生活评价,还有一项辅助指标指标是反乌托邦残差。

基于上述维度的考量，我选择了堆积柱形图的图表形式，使用了tableau，鏑次元数据，数可视hanabi，图表秀，图云等可视化工具进行可视化呈现。

 - a. **tableau**
 
 呈现：
 
 [点此显示pdf](https://github.com/Hangprince/LSH-S-HOMEWORK/blob/master/images/tableau.pdf)
 
使用体会：由于是线下的软件，tableau使用感受较好。软件操作简单，易上手，使用者不需要任何编程或者数理统计知识的基础。 软件的操作界面简明，可直接导入Excel数据，大量基本的操作过程可以直接通过对报表的拖拽实现，结果简单明白，逻辑清晰。与其他的可视化软件相比， 功能算不上强大， 但是非常实用， 数据可视化效果简洁明了,易于分析，报表清晰易读。可视化效果不华丽但很出色，没有 3D 或其他立体效果视图。同时因为其易用性，使得我在对数据进行相对基础的处理时效率很高。

- b.  **鏑次元数据**

呈现：

![image](https://github.com/Hangprince/LSH-S-HOMEWORK/blob/master/images/%E9%8F%91%E6%95%B0.jpg)

使用体会：镝次元数据图表类型也比较多样，比较不同的是，它有信息图表模板。使用感受中等，可能由于我数据量比较大的原因，y轴上国家的名称一开始是重叠的，图表画布的大小需要我自己调整，还有一点就是对于轴上文字的数据比较难调整，我按照幸福指数高低导入，排序为降序，但是默认呈现的却是升序，我在编辑数据一栏中调整降序，它却以首字母排序，最后只能呈现降序升序的图。可视化效果中规中矩，调整好参数，还是比较清晰明了的。

修改意见：1.数据量过于庞大，可以适当减少数据量（选取前几十名）
2.字体排布过于紧密，信息传达不清晰，适当增大左侧国家字体的间距
3.配色考虑不够严谨，各个维度的色差不大

 - c. **数可视hanabi**
 
 呈现：
 
 ![image](https://github.com/Hangprince/LSH-S-HOMEWORK/blob/master/images/%E6%95%B0%E5%8F%AF%E8%A7%86.jpg)
 
使用体会：数可视hanabi作为线上可视化工具的使用感受还是很好的。除了常见的图表类型之外，它还涉及一些数据动态图。图表上的标题是和tableau一样是可以直接编辑的，而鏑数和图表秀不可以。此外，还有一些细节给我留下深刻的影响，图表上是需要标注单位和数据来源的，这一点体现出数据可视化呈现应当持有的严谨。在我选择正确地图表形式，导入数据之后，数可视会根据我数据量的多少和呈现的大小直接给我拓宽拓长画布，这一点让我觉得很便利。可视化效果也是很不错的，简洁干净们很清爽。
 
 - d. **图表秀**
 
 呈现：
 
 ![image](https://github.com/Hangprince/LSH-S-HOMEWORK/blob/master/images/%E5%9B%BE%E8%A1%A8%E7%A7%80.png)
 
 使用体会：图表秀给我的使用感觉是中等偏下，数据图表类型也是中规中矩，比较常用的。可能是后台支撑不够的原因，图表秀在发出指令做出修改后，要顿一会才会显示效果。它和前两个线上工具不同的是，它在导入数据后，需要自己建立数据关系，进行数据匹配，例如是交叉表还是列表，横线数据还是纵向数据。此外，对于数据量比较大的可视化呈现来说，图表秀所能呈现的最大画布是不够的的，以至于我的图例无法完全呈现。从便利性和实用性上来说，可能稍微欠缺一些。
 
 - e. **图说**（值得一提）
 
使用体会：这一款可视化工具的使用感受是不太好的，以至于我的可视化图无法呈现。它的画布大小也有一定的限制，对于数据图表的参数修改比较难操作，更鸡肋的是我需要制作的堆积柱形图，它只允许5个系列堆积，我有两个系列被排除在外，单独成柱。呈现的效果也不是很好。

 - f. **BDP**
 
 呈现：
 
 ![image](https://github.com/Hangprince/LSH-S-HOMEWORK/blob/master/images/BDP.png)
 
 使用体会：BDP给我的使用感受中等，数据图表类型也是比较多样的，色系多以绿色为主，导入数据比较方便，可以直接上传Excel文件，生成图表也没有出现特别卡顿的现象，建立图表关系和tableau类似。不足的是，参数设置不够灵活，同样是无法排序，升序降序还是依据首字母，对于数据量较大的可视化，它也有一定呈现的压力，呈现效果也是走的简约风，这方面没什么可过多诟病的。
 
 *我还尝试使用了一些其他的国内外软件，例如1. LucidChart，Gliffy等，但是这两款偏向于制作流程图，与我需要呈现的形式不匹配，包括还有些线下工具，可能由于一些下载上的问题，未能实现。*
 
 </details>
 
<details>
<summary>second-assignment</summary>
 
1.搜索并阅读《上海市公共数据开放暂行办法》

《上海市公共数据开放暂行办法》
[link](http://www.shanghai.gov.cn/nw2/nw2314/nw2319/nw12344/u26aw62638.html)

2.搜索并回答：我国还有哪些关于公共数据开放的条例或法规？国内外有哪些政府开放数据平台？
- a. 《中华人民共和国政府信息公开条例》
[link](https://duxiaofa.baidu.com/detail?searchType=statute&from=aladdin_28231&originquery=%E4%B8%AD%E5%8D%8E%E4%BA%BA%E6%B0%91%E5%85%B1%E5%92%8C%E5%9B%BD%E6%94%BF%E5%BA%9C%E4%BF%A1%E6%81%AF%E5%85%AC%E5%BC%80%E6%9D%A1%E4%BE%8B&count=56&cid=27bf8b3a94630d68e58719938ec39bba_law)
- b.《贵阳市政府数据共享开放条例》
[link](https://www.gysrd.gov.cn/News_show.aspx?xid=3&lmid=203&&nid=7081)
- c.《浙江省公共数据和电子政务管理办法》
[link](http://www.zj.gov.cn/art/2017/3/24/art_12455_290865.html)
- d.《沈阳市政务数据资源共享开放条例》
[link](http://www.shenyang.gov.cn/html/SY/154700104418245/154700104418245/null/0441824526425348.html)
- e.《江门市政务数据资源共享和开放管理暂行办法》
[link](http://www.jiangmen.gov.cn/gzhd/wsdc/201806/t20180615_1494896.html)
- f.《苏州市政务信息资源共享管理暂行办法》
[link](http://www.zfxxgk.suzhou.gov.cn/sxqzf/szsrmzf/201907/t20190712_1185977.html)

- A.纽约政府开放数据平台
[link](https://opendata.cityofnewyork.us/)
- B.美国官网数据超市
[link](https://www.data.gov/)
- C.新加坡政府开放数据平台
[link](https://data.gov.sg/)
- D.休斯顿市开放数据门户网站
[link](http://data.houstontx.gov/)
- E.北京市政府数据资源网
[link](https://www.bjdata.gov.cn/)
- F.常州市政府数据开放平台
[link](http://opendata.changzhou.gov.cn/)
- G.泰州市政务数据开放平台
[link](http://opendata.taizhou.gov.cn/)

3.在国家统计局数据库找到全国GDP数据，回答：2012-2018年各季度GDP增速（列出选取的统计指标、数据页面、计算步骤及答案）

统计指标：国内生产总值当季值（现价），国内生产总值当季值（不变价），时间（2011-2018年（因为要计算2012年各季度增速）），国内生产总值环比增长速度

数据页面：

![image](https://github.com/Hangprince/second-assignment/blob/master/images/1.png)

计算步骤：由于环比增长率在国家统计局数据库中已经给出，所以我计算的是同比增速，例如计算2018年第四季度的增速，是拿2018年第四季度当季的国内生产总值减去2017年第四季度当季的国内生产总值的差除以2017年第四季度当季的国内生产总值乘以100%，以此类推。

计算公式：同比增长率=（本期数-同期数）/|同期数|×100%

答案：国内生产总值环比增长速度（官方给出，按不变价计算）

2018年第四季度	1.5%

2018年第三季度	1.6%

2018年第二季度	1.7%

2018年第一季度	1.5%

2017年第四季度	1.5%

2017年第三季度	1.7%

2017年第二季度	1.8%

2017年第一季度	1.5%

2016年第四季度	1.6%

2016年第三季度	1.7%

2016年第二季度	1.9%

2016年第一季度	1.4%

2015年第四季度	1.5%

2015年第三季度	1.7%

2015年第二季度	1.8%

2015年第一季度	1.8%

2014年第四季度	1.7%

2014年第三季度	1.8%

2014年第二季度	1.8%

2014年第一季度	1.8%

2013年第四季度	1.6%

2013年第三季度	2.1%

2013年第二季度	1.8%

2013年第一季度	1.9%

2012年第四季度	2%

2012年第三季度	1.8%

2012年第二季度	2.1%

2012年第一季度	2%

时间          当季值（亿元）     国内生产总值（现价）同比增长率	

2018年第四季度	253598.6	9.15%

2018年第三季度	229495.5	9.38%

2018年第二季度	219295.4	10.10%

2018年第一季度	197920	10.32%

2017年第四季度	232349	10.71%

2017年第三季度	209824.1	10.82%

2017年第二季度	199177.8	10.73%

2017年第一季度	179403.4	11.45%

2016年第四季度	209877.2	9.47%

2016年第三季度	189337.6	7.70%

2016年第二季度	179878.7	7.15%

2016年第一季度	160967.3	6.89%

2015年第四季度	191720.8	6.40%

2015年第三季度	175803.8	6.61%

2015年第二季度	167874.5	7.67%

2015年第一季度	150593.8	7.36%

2014年第四季度	180190.3	7.40%

2014年第三季度	164897.8	8.33%

2014年第二季度	155922.3	8.64%

2014年第一季度	140270.2	8.36%

2013年第四季度	167772.3	10.51%

2013年第三季度	152222.7	10.23%

2013年第二季度	143518.7	9.29%

2013年第一季度	129449.6	10.30%

2012年第四季度	151812	10.00%

2012年第三季度	138089.6	9.11%

2012年第二季度	131320.6	10.45%

2012年第一季度	117357.6	12.34%


时间         当季值（亿元）    国内生产总值（不变价） 同比增长率

2018年第四季度	232264.9	6.35%

2018年第三季度	213043.8	6.45%

2018年第二季度	204077.2	6.69%

2018年第一季度	183613	6.84%

2017年第四季度	218393.3	6.66%

2017年第三季度	200133.4	6.74%

2017年第二季度	191284.6	6.81%

2017年第一季度	171852.5	6.85%

2016年第四季度	204764.2	20.81%

2016年第三季度	187498.6	22.45%

2016年第二季度	179089.5	21.91%

2016年第一季度	160837.9	21.39%

2015年第四季度	169488.4	6.82%

2015年第三季度	153127.4	6.86%

2015年第二季度	146898.4	6.99%

2015年第一季度	132491.5	6.98%

2014年第四季度	158668.8	7.23%

2014年第三季度	143294.9	7.14%

2014年第二季度	137305	7.48%

2014年第一季度	123850.1	7.38%

2013年第四季度	147965.2	7.71%

2013年第三季度	133751.6	7.94%

2013年第二季度	127743.9	7.57%

2013年第一季度	115342.5	7.86%

2012年第四季度	137370.4	8.13%

2012年第三季度	123917	7.54%

2012年第二季度	118757.4	7.65%
</details>

<details>
<summary>first-assignment</summary>
由于前几日突然得到爷爷去世的噩耗，匆匆归家导致作业提交较晚，望老师见谅！

![image](https://github.com/Hangprince/first-assignment/blob/master/images/%E4%BA%8C%E8%83%A1%E3%81%AE%E6%97%85.jpg)

 - a. 数据搜集创作手记
 
 题目：《二胡の旅手记》
 
搜集数据内容：幼时学习二胡五年所有曲子表达的情绪，难度，类型等

搜集时间范围：五年

搜集方法：按二胡乐曲考级等级查找乐谱内容，按照维度进行分类分析

找到旧时之物，我做完了所有的数据统计工作，之后，我花了很长时间思考用什么形式呈现比较好看而直观。

我首先确定了我需要强调什么内容。数据一共有这些维度：曲目等级、曲目难度（对于当时的我来说）、曲目情绪基调、曲目种类数量以及曲调类型。我最初设想一只曲子画一根线，竖直排列。但这样无法找到既分等级又分曲目类别的排布方式。于是想到将多维度进行拆分处理，将每一等级的曲目数量设计为单个组。想用音符的形状凑成花瓣比较贴合主题，于是有了作品的雏形。

我用不同的颜色来表示曲目的情绪基调，绿色代表清新盎然的，红色代表激情澎湃的，玫粉色代表优美动听的，橙色代表童真童趣的，蓝色代表沉郁悲伤的，灰黑色代表深重悲痛的。线段尾部是圆形代表曲目类型是练习曲，小旗帜（音符状）为乐曲。线的长度代表曲目的难度，每一条线的末尾是这一首曲子的曲调，我将整理的结果放在了中间。

完善数据处理、进行各种思考过程、做完所有的设计以及将其呈现于纸面之后，成品还是很美观的，我比较满意。

仔细阅读《二胡の旅手记》这一作品，可以看出这样几个结论：

1、学习二胡的曲目是由易到难的，曲谱长度也越来越长，每年时间有限，因此，后期学习曲目的数量也有所减少，这也是学习技艺的趋势与过程。

2、二胡的高阶曲目多以悲伤沉重为主，且曲目等级越高，乐曲表达的情感也更复杂，层次也更多。由于二胡悠远缠绵的声音特性，高阶曲目的情绪大多抒发哀怨，悲痛之情为主，调式层次也更鲜明。

3、我更偏向于学习乐曲，因为相较于练习曲，乐曲的意涵显得更加丰沛，曲调的变换更加灵活，演奏的方式也更多元。

4、曲目的曲调多以D调为主，这也是二胡最常采用的调式。

总结来看，这个作品就是一份“怀念手记”，根据作品可以回忆起那几年学习二胡的点点滴滴，每一支曲子仿佛就是我的一个挚友，很怀念，也很有意义。

 - b Q：你认为日常生活中那些个人数据被谁搜集？
 
我们每下载一款软件第一次打开的时候会有欢迎界面。最大的字：立即使用（体验）下方就会有一排小字，默认是框里是打勾了。这个用户协议里是基本没有人去看的。而这里面就默认了这款软件可以收集你的一些信息的，比如你的定位，短信。比如大家晒支付宝账单的时候也是有个小勾勾让你点了才能看，结果里面的服务条款就有一条支付宝将会把你的账单等信息给第三方。结果被爆了出来，支付宝官方道歉。但是这个套路我们日常生活中太多了。

还有一些针对用户进行私人订制的app，通过后台的算法获取个人喜好等方面的数据，例如，淘宝首页推荐的商品是根据用户近期搜索的商品而生成的，今日头条的推送也是根据每天的阅读兴趣而推出。包括一些手机地图软件，通过GPS系统定位，收集位置信息，路程信息。

由车辆的刹车，引擎和其它系统生成的全部信息，汽车制造商都充斥着数据， 而这种信息能够帮助改善性能和汽车的安全性。这可能非常难保障驾驶者的隐私权。比如，即使该公司所提供的驱动程序在他们的数据收集中有一些控制，他们没有让消费者请求的历史位置信息被删除。

员工的电子邮件和聊天记录能够提供老板的线索，工作人员是否从事不良行为。但有，也是被监控的不太明显的活动——当你的胸卡进入建筑物。刷身份证进入或退出一个安全设施的简单行为是那些正在寻找欺诈行为偏差吸纳算法的关键信号。人们往往坚持预测的模式，让员工遵从规范动向，在晚上或周末突然意外记录前往办公室，能够触发怀疑。胸卡是通过一个因素寻找内幕交易的行为。

这种数据搜集泄露行为，不仅只发生在手机中，像智能电视也会泄露自己的信息，当我们下载某个盗版软件后，有时会填写个人信息，这时就将个人信息彻底的暴露给不法分子了，尤其是会摆弄智能电视的老年人，对于这种突然弹出的窗口，没有什么警惕性，很容易点进去，将老年人的联系暴露给不法分子进行出售。
</details>

