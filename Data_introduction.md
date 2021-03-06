## 数据介绍

### 数据集统计
| quesion type | train set | dev set | test set |
|---|---|---|---|
| Description | 116382 | 6378 | 6356 |
| Entity | 51026 | 2825 | 2845 |
| Yes No | 14166 | 797 | 799 |
| Main | 181574 | 10000 | 10000 |


### 字段及意义

* **question**: 问题
* **answers**: 人工标注答案的列表 
* **question_type**:实体型/描述型/是非型
* **fact_or_opinion**:fact
* **question_id** 问题的编号
* **documents**  相关文档
    * **bs_rank_pos**: 文档的搜索排序  
    * **is_selected**: 文档是否被选中
    * **title**: 文档的标题 
    * **paragraphs**: 文档的所有段落列表  
   
### 示例

```
{
　　"documents":[
　　　　{
　　　　　　"bs_rank_pos":0,
　　　　　　"is_selected":true,
　　　　　　"paragraphs":[
　　　　　　　　"导读:绣眉有哪几种方法?小编带来绣眉的基本方法,喜欢绣眉的MM看看吧。",
　　　　　　　　"绣眉可以让MM的五官看起来更加的清秀有立体感,绣眉有哪几种方法?绣眉的基本方法分享给大家。",
　　　　　　　　"绣眉有哪几种方法?",
　　　　　　　　"绣眉的五种基本方法:",
　　　　　　　　"1、雕润眉 2、平面绣眉 3、点状绣眉 4、立体绣眉",
　　　　　　　　"5、仿真立体绣眉",
　　　　　　　　"绣眉的基本方法:",
　　　　　　　　"1、雕润眉 雕润眉是完美医学纹绣为载体,根据人的眉毛生长而雕刻出来的眉形,根据肤色来选料,这样的眉形看起来很靓丽好看,与传统的绣眉方法相比,雕润眉是如丝发般的精细雕刻眉毛,具有三维立体感,而且纹眉后不痛不肿,不脱色,不变色,不晕色,一般半个小时就能完成的绣眉。》》》99.99%人都关注的绣眉结痂问题 2、平面绣眉 平面绣眉是传统的绣眉方式,是通过过将复合自身形象的图案纹绘在眉毛上,经过改良而形成的平面绣眉,是标准眉型图案,颜色深浅平均,跟一般的眉形没太大区别。 3、点状绣眉 点状绣眉是独具设计性的绣眉,是一种改良的损伤最小的平面绣眉,需要用针点上药水刺其眉毛的毛囊口着色,稍微比较痛,看上去的眉毛比较粗,适合眉形好,眉毛少的女生。 4、立体绣眉 立体绣眉是利用排针,一排12只,运用不同的针法衔接在眉毛上,绣出二种深浅不一的咖啡色,这样的眉形看起来很自然立体,具有长短不齐、粗细不一的毛发线条特点,,让MM看起来更秀气漂亮。 5、仿真立体绣眉 仿真立体绣眉是比较流行的绣眉方式哦,是利用排针,一排12只,运用不同的针法进行绣眉,以咖啡色为基础,这样的眉形看起来很自然动态美。",
　　　　　　　　"绣眉的五种基本方法,选择适合自己的绣眉方法,打造出秀气漂亮的眉形哦。",
　　　　　　　　"(想知道自己适合什么发型吗?微信添加公众号爱靓网,发型师为您解答!)"
　　　　　　],
　　　　　　"title":"绣眉有哪几种方法?绣眉的基本方法_绣眉_妆美扮靓_爱靓网"
　　　　},
　　　　{
　　　　　　"bs_rank_pos":1,
　　　　　　"is_selected":false,
　　　　　　"paragraphs":[
　　　　　　　　"2016-09-30 10:04",
　　　　　　　　"对于美的追求是很多人的天性,对于爱美的女生来说好看的眉型不但能提升气质,还能修饰脸型,绣眉也早已成为女生完善美化眉形的一种方式。绣眉有哪几种常见方法?一般绣眉得花多少钱?一起和小编了解一种吧。",
　　　　　　　　"绣眉有哪几种常见方法?一起来了解下:",
　　　　　　　　"A、平面绣眉:这是一款传统的绣眉方式,是以标准的眉型为图案,通过绣眉技术纹绘在眉毛上,色泽均匀上色,给人的感觉就好像刚刚画完眉毛一样。 B、点状绣眉:点状绣眉相对来说,会更有设计性。通过药水的渗透,将有色的染料对这眉毛的毛囊口进行点刺上色,还能按照眉毛的整体轮廓勾勒出眉型,不过眉毛过粗的美眉们则不适合点状绣眉喔! C、仿真立体绣眉:这种绣眉方式是利用排针和不同的针法衔接在眉毛上,出来的眉形效果是一把一把的形状,而且常用的色料是深浅不一的咖啡色来呈现,在着色上后的眉形效果就会像自己长出来的眉毛一样自然好看。 D、立体绣眉:立体绣眉也是利用排针来进行纹绣,采取了由浅至深的形式绣出眉形,而整体的效果会呈现出雾状,非常地有立体感。",
　　　　　　　　"绣眉一般要多少钱?",
　　　　　　　　"一般来说,绣眉的价钱在800到5000元之间,每家的医美诊所价格都是不同,会因规模以及技术相互关联。绣眉使用的材料也是决定价格的高低,一般分为有机色料及无机色料,以及绣眉的方式也是能决定价格的关键喔!由于绣上的眉型都是因人而异的,也会导致绣眉价格的差异。",
　　　　　　　　"想必经过了小编的介绍,大家都对绣眉有哪几种常见方法?以及其价格有了一定的了解!如果你也想眉形好看也不妨尝试一下绣眉,选择好的技术以及医美医院才能保证绣眉的完美效果喔!(图片来源:视觉中国)",
　　　　　　　　"(责任编辑:陆薇)",
　　　　　　　　"全世界都在安利的“举重妖精”李圣经,凭什么成为男神收割机? 同是新疆美女 为啥迪丽热巴观众缘最好? 从晴儿到楚乔 赵丽颖是怎么越来越美的? 滨崎步发福or水肿?3分钟快速消水肿 学刘诗诗掀起刘海 气场2米8一点也不难",
　　　　　　　　"梦幻的粉嫩无瑕肌 怎能不被吸引? 怀疑自己画了个假妆?那是用错了气垫 水润透亮 让肌肤呼吸一整天 伊夫黎雪植物焕颜抚纹系列 倒春寒 给肌肤加个完整的保湿屏障",
　　　　　　　　"周末好心情 慵懒 露天趴音乐节妆容",
　　　　　　　　"六月护肤爱用品 春季护肤五款高颜值萌物 开启焕肤撩春模式 实用百搭口罩妆容",
　　　　　　　　"包贝尔新剧曝光表情冷 姜至鹏出轨被曝私密图 咘咘公园跳钢管舞萌翻 白百何学龅牙兔神表情 黄晓明胖了一圈曝真相 周冬雨再出表情包搞笑"
　　　　　　],
　　　　　　"title":"绣眉有哪几种常见方法?绣眉一般要多少钱【图】_彩妆资讯百科_美容_"
　　　　},
　　　　{
　　　　　　"bs_rank_pos":2,
　　　　　　"is_selected":false,
　　　　　　"paragraphs":[
　　　　　　　　"平面绣眉 平面绣眉是最为传统的绣眉方法。这种方法起源于古代,古时候人们将符合自身形象的图案描绘在眉毛和额头之间,最为有名的就是杨贵妃在眉毛和额头之间绘上了花朵。平面绣眉就是采用的这种方法。经过现代人的改良之后,平面绣眉出来的效果就像是刚刚画好的眉毛,还是比较逼真的。 点状绣眉 相对于平面绣眉来说,点状绣眉是比较疼的,不过这种方式更具有独特的设计性。点状绣眉适合眉毛细而且淡的人选择,它是采用针沾上药水有粗有细的对毛囊进行着色。采用这种方法能够绣出更加自然逼真的眉毛。 仿真立体绣眉 这种绣眉方法有点类似于点状绣眉,不过这种方法使用的是排针。目前比较常见的是使用一排十二根针。由于针的排布原因,使用这种方法绣出来的眉毛是一把一把的。而且美容院会采用深浅不同的颜色来表现眉毛的特点,因此,绣",
　　　　　　　　"有平面绣眉,点状绣眉,仿真立体绣眉,立体绣眉"
　　　　　　],
　　　　　　"title":"绣眉有哪几种_百度知道"
　　　　},
　　　　{
　　　　　　"bs_rank_pos":3,
　　　　　　"is_selected":false,
　　　　　　"paragraphs":[
　　　　　　　　"有平面绣眉,点状绣眉,仿真立体绣眉,立体绣眉"
　　　　　　],
　　　　　　"title":"绣眉有几种,哪种比较好看?_百度知道"
　　　　},
　　　　{
　　　　　　"bs_rank_pos":4,
　　　　　　"is_selected":false,
　　　　　　"paragraphs":[
　　　　　　　　"有线条眉,就是跟真的眉毛很像,一根一根的;还有那种雾状眉,像化妆了一样;还有一种就是线条加雾的感觉。",
　　　　　　　　"1、平面绣眉:传统的绣眉方式。在古代,绣眉技术是通过将复合自身形象的图案纹绘在眉额之间。后经过现代美容师的改良而形成如今的平面绣眉。以标准的眉型为图案,色泽均匀,宛如刚刚画完眉。 2、点状绣眉:此种方法相对于平面绣眉更加具有设计性,但是人体疼痛感要稍微强烈一点。在针点上通过药水的浸透,再对眉毛的毛囊口进行点刺并着色。可以按照眉毛的粗细变化,从而勾勒出漂亮的眉型。但是对于眉毛相对比较粗、浓者来说,是不适合进行点状绣眉的。 3、仿真立体绣眉:这种绣眉的方法利用排针,一排12只,运用不同的针法衔接在眉毛上,所绣出来的眉型现出一把一把的,而且须用二种深浅不一的咖啡色来表现色差,就像自己长的眉毛一样立体自然。 4、立体绣眉:这种绣眉的方法利用排针单一颜色由浅至深,绣出雾状,表现出立体"
　　　　　　],
　　　　　　"title":"绣眉分哪几种_百度知道"
　　　　}
　　],
　　"question":"绣眉有哪几种",
　　"answers":[
　　　　"绣眉的五种基本方法：1、雕润眉；2、平面绣眉；3、点状绣眉；4、立体绣眉；5、仿真立体绣眉。"
　　],
　　"entity_answers":[
　　　　[
　　　　　　"雕润眉",
　　　　　　"平面绣眉",
　　　　　　"点状绣眉",
　　　　　　"立体绣眉",
　　　　　　"仿真立体绣眉"
　　　　]
　　],
　　"question_type":"ENTITY",
　　"fact_or_opinion":"FACT",
　　"question_id":0
}

```
