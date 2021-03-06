# 数据分析：COVID19与其他传染病的比较
## 简介
COVID19，全称：Corona Virus Disease 2019，中文名称：2019冠状病毒病，于2019年12月第一次大面积、迅速爆发。新型冠状病毒肺炎是一种急性感染性肺炎，其病原体是一种先前未在人类中发现的新型冠状病毒，即2019新型冠状病毒SARS-CoV-2。在2020年3月11日，世界卫生组织（WHO）宣布COVID19为全球大流行病。
## 全球COVID19现状
### 整体情况
![全球](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/1.png)
- 上图为六月一日全球COVID19确诊人数、死亡人数、治愈人数，全球确诊人数即将超过七百万。经过简单的计算可以知道，COVID19死亡率约为6.0%，治愈率约为42.8%。2003年，非典型肺炎在中国大陆的死亡率约为10.0%[1]，相比之下，COVID19致死率虽然不高，但由于其传播至世界各地，所以死亡人数堪称触目惊心，是甲型H1N1流感在大流行期间死亡人数的20倍，而且就目前局势来看，这一数字仍将不断增加。
![2](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/2.png)
- 对比前60天与后60天，可以看出COVID19致死率在大幅下降。
- 目前该传染病在全球的流行仍在以较快速度传播,在COVID19爆发60天以后，全球确诊人数曲线几乎为一条倾斜度约为60°的直线。
### 各大洲情况
![3](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/3.png)
- 上图为六月一日各大洲的确诊人数、死亡人数、治愈人数。可以清晰地看出欧洲与北美洲此时的情况最为严重，共占全球确诊人数的63.3%，可见COVID19高发地区已由亚洲逐渐转移至欧洲与北美洲。
### 各国情况
![4](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/4.png)
-上图为确诊总人数排名前十的国家，虽然美国的确诊人数是第二名巴西的2.5倍左右，后几名国家的确诊人数与美国相差6到7倍，但我们必须考虑到这些国家的人口基数，截至2019年底，印度人口约为13.6亿，美国人口约为3.3亿，英国人口约为6.7千万，秘鲁人口约为3.3千万等等，不再一一赘述，可以大致看出其实排名前十的国家除印度以外，确诊人数占总人数比例都比较接近。
![5](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/5.png)
- 上图为因COVID19死亡人数的前十个国家，美国仍为第二名的2.8倍左右。
![6](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/6.png)
- 目前为止，COVID19的治愈人数非常多，但治愈率为50%左右，在传染病中是比较高的治愈率，原因可能为SARS-CoV-2病毒虽然具有超强的感染能力，但对人体造成的伤害仍然在可控范围内，虽然目前并没有针对COVID19的特效药，但是现代医学的许多治疗手段如使用呼吸机、使用药物等等，都可以对治愈COVID19起到积极作用。
### 中国COVID19患者年龄组成
![7](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/7.png)
- 上图为中国COVID19患者的年龄情况，呈非常明显的正态分布，且涉及的年龄段比较广，患者多为20-80岁人群，考虑到目前中国人平均年龄小于八十岁，故80岁以上老人本就人数较少，所以患者几乎是除婴幼儿、儿童、青少年以外的所有成年人群体。
## 中国甲型H1N1流感数据分析
### 简介
甲型H1N1流感为急性呼吸道传染病，其病原体是一种新型的甲型H1N1流感病毒，在人群中传播。该疾病于2009年3月首次爆发于美国、墨西哥，随后逐步向其他国家扩散，中国大陆的首例患者为境外输入型病例，出现于2009年5月。甲型H1N1流感的群间传播主要是以感染者的咳嗽和喷嚏为媒介，在人群密集的环境中更容易发生感染，感染者有可能在出现症状前感染其他人，感染后一般在一周、或一周多后发病。
### 患者年龄组成
![8](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/8.png)
- 不同于COVID19，甲型H1N1流感有明显的易感人群，主要为十到二十五岁的青少年与青年，年轻人比中年人、老年人更容易感染甲型H1N1流感。在甲型H1N1的死亡病例中五岁以下婴幼儿与十五到二十五岁的年轻人居多。整体来看，甲型H1N1的传染力比COVID19略低，易感人群比较明确，仅从患者与死亡病例的年龄组成判断，甲型H1N1与COVID19情况差异较大。
### 2009-2011传染情况
![9](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/9.png)
- 甲型H1N1流感在传染能力上虽然不足以比拟COVID19，但它的传染曲线显示了一个较为典型的传染病传播过程：在某一时期的突然、大面积爆发，随后得到一定控制，在某一阶段再次爆发，重新得到控制并短期内不再大面积爆发，但每一次爆发后感染病例都较前一次有明显减少。由上图可知，在中国，甲型H1N1流感两次爆发的季节均为冬季，而COVID19大面积爆发的开始，也是冬季，这并不是巧合。因为它们同属于呼吸道传染病。秋冬相交时期，受冷空气频频南下的影响,天气逐渐转冷，人们户外活动及体育运动减少，抵抗力下降，而且常常家里门窗紧闭，室内空气不流通，非常有利于病原微生物的滋生繁殖，如果不注意预防，很容易患各种呼吸道疾病。再加上秋冬季节人们会增大人们打喷嚏或咳嗽的概率，加速传染病的传播。从这一角度来看，COVID19与甲型H1N1流感有一定的相似性，只不过COVID19的感染力要远大于甲型H1N1流感。
## 中国传染性肝炎数据分析
### 简介
传染性肝炎一般指病毒性肝炎，是由多种肝炎病毒引起的以肝脏病变为主的一种传染病。传染性肝炎并不仅仅困扰着现代人，它的历史相当的悠久，很多古老的中医典籍例如《黄帝内经》等等均有传染性肝炎的相关记载。可以说传染性肝炎是人类所记载的历史最悠久的烈性传染病之一，而且与甲型H1N1流感不同，仅在中国，传染性肝炎每年的感染病例就仍保持在一百万人以上，人类是通过疫苗才使肝炎得到彻底控制的。
### 患者年龄组成
![10](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/10.png)
- 传染性肝炎患者的年龄组成与COVID19相似，几乎没有非常明显的易感人群，15到75人群均有大概率患病风险。不过，传染性肝炎的致死率非常低，仅为0.05%左右，其中45岁以上的中老年患者死亡率更高。仅从患者及死亡病例年龄组成来看，传染性肝炎与COVID19的相关数据较为相似。
### 2004-2017传染情况
![11](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/11.png)
- 传染性肝炎的传播并没有类似甲型H1N1流感的波动，相反的，每一年中国的传染性肝炎患者人数均超过了一百万，如果不是传染性的疫苗已经大量普及，其后果可想而知，它的感染人数恐怕会非常接近现在的COVID19。那么，传染性肝炎的传播是否也具有类似甲型H1N1流感的季节性呢？

![12](https://github.com/JCM-lsy/COVID19_H1N1_HV_DataAnalyze/blob/master/images/12.png)
- 为了保证比对的科学性，同样选择传染性肝炎在2009到2011年每个月的患病人数。由上图可以看出，传染性肝炎并不具有明显的季节性传播，每个月的传播都在九万例以上，每年春季的病例略多于秋冬季节。不过，在上世纪八十年代，传染性肝炎的高发季为秋冬季，直到九十年代初，其高发季才逐渐向春季漂移，可见传染病的季节性也不是一成不变的，会随着环境的变化而变化。可见，传染性肝炎传播的季节性与COVID19差异较大。
# 结论
前文中之所以将COVID19与甲型H1N1流感与传染性肝炎作对比，首先是因为这两种传染病的传染能力都比较强，其次是因为它们分别代表了两种人类战胜传染病的方式，也隐含了COVID19疫情的两种走向。
1. 与甲型H1N1流感类似，COVID19在经历若干次反复的、感染病例递减的季节性爆发后，短期内不再有大面积爆发，这是比较理想的一种结果。想要让COVID19达到这一结果，我们必须尽快研究出有效的疫苗并将其迅速普及，才能避免其反复爆发却难以有效降低感染率。
2. 与传染性肝炎类似，COVID19将不再具有明显的反复爆发的特征，而是感染病例最终稳定在某一数量级，但同时治愈率大幅提高，即死亡率明显降低。相对来说这种情况就不太理想了，我们或许必须面对每年、甚至每天都有人感染COVID19的可能。在这种情况下，我们能做的就不仅仅是着力研制有效疫苗了，我们还要不断地研制针对COVID19的特效药与特效疗法，才能最大可能的减少COVID19对人类健康的威胁。

- 不过，笔者毕竟不是医学专业学生，上述推论仅为来源于数据的猜测。如有不妥，可联系我进行改进。
- 无论如何，希望人类能尽快打赢这场没有硝烟的战争。
