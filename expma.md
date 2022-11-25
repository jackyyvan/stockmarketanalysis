
指数平均数也叫EXPMA[指标](https://baike.baidu.com/item/%E6%8C%87%E6%A0%87/19950696?fromModule=lemma_inlink)，它是一种[趋向类指标](https://baike.baidu.com/item/%E8%B6%8B%E5%90%91%E7%B1%BB%E6%8C%87%E6%A0%87/5376630?fromModule=lemma_inlink),[指数平均数指标](https://baike.baidu.com/item/%E6%8C%87%E6%95%B0%E5%B9%B3%E5%9D%87%E6%95%B0%E6%8C%87%E6%A0%87/1847442?fromModule=lemma_inlink)是以指数式递减[加权](https://baike.baidu.com/item/%E5%8A%A0%E6%9D%83/91816?fromModule=lemma_inlink)的[移动平均](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87/12730589?fromModule=lemma_inlink)。其构造[原理](https://baike.baidu.com/item/%E5%8E%9F%E7%90%86/85014?fromModule=lemma_inlink)是对[股票](https://baike.baidu.com/item/%E8%82%A1%E7%A5%A8/22647?fromModule=lemma_inlink)[收盘价](https://baike.baidu.com/item/%E6%94%B6%E7%9B%98%E4%BB%B7/648023?fromModule=lemma_inlink)进行算术平均，并根据计算结果来进行分析，用于判断价格未来走势的变动趋势。

## 指标概述



[EXPMA指标](https://baike.baidu.com/item/EXPMA%E6%8C%87%E6%A0%87/8517919?fromModule=lemma_inlink)简称EMA，中文名字[指数平均数指标](https://baike.baidu.com/item/%E6%8C%87%E6%95%B0%E5%B9%B3%E5%9D%87%E6%95%B0%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)，一种[趋向类指标](https://baike.baidu.com/item/%E8%B6%8B%E5%90%91%E7%B1%BB%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)，从统计学的观点来看，只有把移动平均线（MA)绘制在价格时间跨度的中点，才能够正确地反映价格的运动趋势，但这会使信号在时间上滞后，而EXPMA指标是对移动平均线的弥补，EXPMA指标由于其计算公式中**着重考虑了价格当天（当期）**[行情](https://baike.baidu.com/item/%E8%A1%8C%E6%83%85?fromModule=lemma_inlink)的权重，因此在使用中可克服[MACD](https://baike.baidu.com/item/MACD?fromModule=lemma_inlink)其他指标信号对于价格走势的滞后性。同时也在一定程度中消除了[DMA指标](https://baike.baidu.com/item/DMA%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)在某些时候对于价格走势所产生的信号提前性，是一个非常有效的分析指标。

## 原理



与[MACD指标](https://baike.baidu.com/item/MACD%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)、[DMA指标](https://baike.baidu.com/item/DMA%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)相比，EXPMA指标由于其计算公式中着重考虑了价格当天（当期）行情的[权重](https://baike.baidu.com/item/%E6%9D%83%E9%87%8D/10245966?fromModule=lemma_inlink)，因此指标自身的计算公式决定了作为一类趋势分析指标，它在使用中克服了[MACD指标](https://baike.baidu.com/item/MACD%E6%8C%87%E6%A0%87/6271283?fromModule=lemma_inlink)信号对于价格走势的滞后性。同时也在一定程度中消除了[DMA指标](https://baike.baidu.com/item/DMA%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)在某些时候对于价格走势所产生的信号提前性，是一个非常有效的分析指标。

我们先来看一下EXPMA指标的计算公式，并以此对指标的特征作进一步的了解：

EXPMA=（当日或当期[收盘价](https://baike.baidu.com/item/%E6%94%B6%E7%9B%98%E4%BB%B7?fromModule=lemma_inlink)－上一日或上期EXPMA）/N+上一日或上期EXPMA，其中，首次上期EXPMA值为上一期收盘价，N为天数。

实际上，从EXPMA指标的构造原理和它的使用原则来看，这一[指标](https://baike.baidu.com/item/%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)更接近于[均线](https://baike.baidu.com/item/%E5%9D%87%E7%BA%BF?fromModule=lemma_inlink)指标，而且由于EXPMA指标通过对参数进行有效地设定，可以发挥出比均线指标更为直观和有用的[信息](https://baike.baidu.com/item/%E4%BF%A1%E6%81%AF?fromModule=lemma_inlink)。

在技术分析软件中，EXPMA指标由三条线构成，价格K线、短期EXPMA线（以白色线条或其他稍浅色的线条表示）、长期EXPMA线（以黄色线条或其他稍深色的线条表示），EXPMA指标的坐标图上，纵坐标代表价格运行的价位，横坐标代表价格运行的时间，这一点也和均线指标保持了一致。 [1] 

## 基础算法



若求X的N日[指数](https://baike.baidu.com/item/%E6%8C%87%E6%95%B0?fromModule=lemma_inlink)平滑移动平均，则表达式为：EMA（X，N）

算法是：若Y=EMA(X，N)，则Y=[2*X+(N-1)*Y’]/(N+1)，其中Y’表示上一周期的Y值。

不举例的话，比较难理解，举例说明一下:

X是变量，每天的X值都不同，从远到近地标记，它们分别记为X1，X2，X3，….，Xn

如果N=1，则EMA(X，1)=[2*X1+(1-1)*Y’]/(1+1)=X1

如果N=2，则EMA(X，2)=[2*X2+(2-1)*Y’]/(2+1)=(2/3)*X2+(1/3)X1

如果N=3，则EMA(X，3)=[2*X3+(3-1)*Y’]/(3+1)=[2*X3+2*((2/3)*X2+2*(1/3)*X1)]/4=(1/2)*X3+(1/3)*X2+(1/6)*X1

如果N=4，则EMA(X，4)=[2*X4+(4-1)*Y’]/(4+1)=2/5*X4+3/5*((1/2)*X3+(1/3)*X2+(1/6)*X1)=2/5*X4+3/10*X3+1/5*X2+1/10*X1

.....

X1

(2/3)*X2+(1/3)X1

(3/6)*X3+(2/6)*X2+(1/6)*X1

(4/10)*X4+(3/10)*X3+(2/10)*X2+(1/10)*X1

...

这里可以看出系数值和恒为1

我们可以看到时间周期越近的X值它的权重越大，说明EMA函数对附近期间的X值加强了权重比，更能及时反映附近期间X值的波动情况。

## 计算公式



1.EXPMA=[当日或当期[收盘价](https://baike.baidu.com/item/%E6%94%B6%E7%9B%98%E4%BB%B7?fromModule=lemma_inlink)*2 + 上日或上期EXPMA*(N-1)] / (N+1)

2.首次计算，上期EXPMA值为昨天的EXPMA值，N为天数。

3.可设置多条指标线，参数为12，50（12日，50日）。

4. 函数：

MA1：EMA(CLOSE,P1)；

MA2：EMA(CLOSE,P2)；

MA3：EMA(CLOSE,P3)；

MA4：EMA(CLOSE,P4)

EMA和EXPMA计算原理是一样的

更细的解释：

当天EMA=昨天的EMA+加权因子*（当天的收盘价-昨天的EMA）

= 加权因子*当天的[收盘价](https://baike.baidu.com/item/%E6%94%B6%E7%9B%98%E4%BB%B7?fromModule=lemma_inlink)+（1-加权因子）*昨天的EMA

加权因子=2/(N+1);

N就是上面所说的周期 ，比如周期12 则加权的因子就是 2/13；

当天EMA=2/13*当天的收盘价+11/13*昨天的EMA

计算过程：（每日你看到的EMA计算结果是从上市第一天就开始累积了）

股票上市第一天：当天EMA1 = 当天收盘价

第二天：EMA2 = 2/13 * 当天收盘价+11/13 * EMA1

第三天：EMA3 = 2/13 * 当天收盘价+ 11/13* EMA2

.................

## 特征



第一，[EXPMA指标](https://baike.baidu.com/item/EXPMA%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)由白线和黄线构成。当白线从下往上冲破黄线时，就代表价格会上升。因此当白线和黄线形成金叉的时候就是买入的好时机。

第二，当一只个股的价格和白线远离之后，该股的股价之后很快会下降，然后再上行。由此可见白线是一个支撑点。

第三，当白线从上到下冲破黄线时，价格通常已经发生逆转，将来就会以下降为主，因此当这两根线交叉的时候就是卖出的好时机。 [2] 

## 注意要点



1.关于EXPMA指标的其他使用原则，可根据不同[基期](https://baike.baidu.com/item/%E5%9F%BA%E6%9C%9F?fromModule=lemma_inlink)的[指数](https://baike.baidu.com/item/%E6%8C%87%E6%95%B0?fromModule=lemma_inlink)参数设置来进一步总结。在众多的[技术分析](https://baike.baidu.com/item/%E6%8A%80%E6%9C%AF%E5%88%86%E6%9E%90?fromModule=lemma_inlink)软件中，EXPMA指标参数默认为（12，50），客观讲有较高的使用价值。而经过技术分析人士的研究，发现（5，35）与（10，60）有更好的实战效果。

2.EXPMA指标比较适合与[SAR指标](https://baike.baidu.com/item/SAR%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)配合使用。

## 应用原则



1 在[多头](https://baike.baidu.com/item/%E5%A4%9A%E5%A4%B4?fromModule=lemma_inlink)趋势中，价格K线、短天期天数线（例如（12，50）中的12[日线](https://baike.baidu.com/item/%E6%97%A5%E7%BA%BF?fromModule=lemma_inlink)）、长天期天数线（50日线）按以上顺序从高到低排列，视为多头特征；在空头趋势中，长天期天数线、短天期天数线、价格K线按以上顺序从高到低排列，视为空头特征。

 [![指数平均数](https://bkimg.cdn.bcebos.com/pic/d009b3de9c82d158569e62c3800a19d8bc3e42a7?x-bce-process=image/resize,m_lfit,w_440,limit_1)](https://baike.baidu.com/pic/%E6%8C%87%E6%95%B0%E5%B9%B3%E5%9D%87%E6%95%B0/3334858/0/c856613efd28c77f70cf6cc0?fr=lemma&fromModule=lemma_content-image&ct=single "指数平均数")指数平均数

2当短天期天数线从下而上穿越长天期天数线时，是一个值得注意的买入信号；此时短天期天数线对价格走势将起到助涨的作用，当短天期天数线从上而下穿越长天期天数线时，是一个值得注意的[卖出信号](https://baike.baidu.com/item/%E5%8D%96%E5%87%BA%E4%BF%A1%E5%8F%B7?fromModule=lemma_inlink)，此时长天期天数对价格走势将起到助跌的作用。

3一般来说，价格在[多头市场](https://baike.baidu.com/item/%E5%A4%9A%E5%A4%B4%E5%B8%82%E5%9C%BA?fromModule=lemma_inlink)中将处于短天期天数线和长天期天数线上方运行，此时这两条线将对价格走势形成支撑。在一个明显的[多头趋势](https://baike.baidu.com/item/%E5%A4%9A%E5%A4%B4%E8%B6%8B%E5%8A%BF?fromModule=lemma_inlink)中，价格将沿短天期天数线移动，价格反复的最低点将位于长天期天数线附近；相反地，价格在空头市场中将处于短天期天数线和长天期天数线下方运行，此时这两条线将对价格走势形成压力。在一个明显的空头趋势中，价格也将沿短天期天数线移动，价格反复的最高点将位于长天期天数线附近。

4一般地，当价格K线在一个多头趋势中跌破短天期天数线，必将向长天期天数线靠拢，而长天期天数线将对价格走势起到较强的支撑作用，当价格跌破长天期天数线时，往往是绝好的买入时机；相反地，当价格K线在一个空头趋势中突破短天期天数线后，将有进一步向长天期天数线冲刺的希望，而长天期天数线将对价格走势起到明显的阻力作用，当价格突破长天期天数线后，往往会形成一次[回抽确认](https://baike.baidu.com/item/%E5%9B%9E%E6%8A%BD%E7%A1%AE%E8%AE%A4?fromModule=lemma_inlink)，而且第一次突破失败的机率较大，因此应视为一次绝好的卖出时机。

5第三条的特例是：当价格K线在一个多头趋势中跌破短天期天数线，并继而跌破长天期天数线，而且使得短天期天数开始转头向下运行，甚至跌破长天期 天数线，此时意味着多头趋势发生变化，应作[止蚀](https://baike.baidu.com/item/%E6%AD%A2%E8%9A%80?fromModule=lemma_inlink)处理；相反地，当价格K线在一个空头趋势中突破短天期天数线，并继而突破长天期天数线，而且使得短天期天数 开始转头向上运行，甚至突破长天期天数线，此时意味着空头趋势已经改变成多头趋势，应作[补仓](https://baike.baidu.com/item/%E8%A1%A5%E4%BB%93?fromModule=lemma_inlink)处理。

6价格对于长天期天数线的突破次数越多越表明突破有效，第一次突破一般会以失败而告终；价格对于长天期天数线的突破时间越长越表明突破有效。一般来说，在价格日K线[技术指标](https://baike.baidu.com/item/%E6%8A%80%E6%9C%AF%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)体系中的EXPMA指标长天期天数线被价格突破之后，需要两到三个交易日的时间来确认突破的有效性。

7当短期天数线向上交叉长期天数线时，[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)会先形成一个短暂的高点，然后微幅回档至长期天数线附近，此时为最佳买入点；当短期天数线向下交叉长期天数线时，股价会先形成一个短暂的低点，然后微幅反弹至长期天数线附近，此时为最佳卖出点。

如何活用EXPMA指标

 [![指数平均数](https://bkimg.cdn.bcebos.com/pic/91ef76c6a7efce1be222f3b8af51f3deb48f65b2?x-bce-process=image/resize,m_lfit,w_440,limit_1)](https://baike.baidu.com/pic/%E6%8C%87%E6%95%B0%E5%B9%B3%E5%9D%87%E6%95%B0/3334858/0/48151723a260580c925807d3?fr=lemma&fromModule=lemma_content-image&ct=single "指数平均数")指数平均数

在一般情况下，许多投资者均以[KDJ指标](https://baike.baidu.com/item/KDJ%E6%8C%87%E6%A0%87/6328421?fromModule=lemma_inlink)和[MACD指标](https://baike.baidu.com/item/MACD%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)作为买卖的重要指示，当[大盘](https://baike.baidu.com/item/%E5%A4%A7%E7%9B%98?fromModule=lemma_inlink)或[个股](https://baike.baidu.com/item/%E4%B8%AA%E8%82%A1?fromModule=lemma_inlink)的KDJ指标和MACD指标在高位形成[死叉](https://baike.baidu.com/item/%E6%AD%BB%E5%8F%89?fromModule=lemma_inlink)后，他们通常会卖出。但是，由于市场的[主力](https://baike.baidu.com/item/%E4%B8%BB%E5%8A%9B?fromModule=lemma_inlink)经常进行反向操作，所以常常导致“顶在顶上”和“底在底下”的情况发生，因此这种指标常常会失灵。

据于上述现象，许多投资者于是用移动平[均线](https://baike.baidu.com/item/%E5%9D%87%E7%BA%BF?fromModule=lemma_inlink)来作为买卖股票的主要依据，意思是当月线指标（即5天均线、10天均线和20天均线）形成[多头排列](https://baike.baidu.com/item/%E5%A4%9A%E5%A4%B4%E6%8E%92%E5%88%97?fromModule=lemma_inlink)时，他们通常会买进。反之，当月线指标形成[空头排列](https://baike.baidu.com/item/%E7%A9%BA%E5%A4%B4%E6%8E%92%E5%88%97?fromModule=lemma_inlink)时，他们通常会卖出。但是，由于市场主力经常会进行反技术的操作，故意令[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)连连[破位](https://baike.baidu.com/item/%E7%A0%B4%E4%BD%8D?fromModule=lemma_inlink)，从而打穿上述均线，这样做会令很多人的[筹码](https://baike.baidu.com/item/%E7%AD%B9%E7%A0%81?fromModule=lemma_inlink)因此而脱手。

## 指标优势



 [![指数平均数](https://bkimg.cdn.bcebos.com/pic/aa64034f78f0f73646f377730a55b319ebc413b6?x-bce-process=image/resize,m_lfit,w_440,limit_1)](https://baike.baidu.com/pic/%E6%8C%87%E6%95%B0%E5%B9%B3%E5%9D%87%E6%95%B0/3334858/0/b110e6196f283838dab4bdd0?fr=lemma&fromModule=lemma_content-image&ct=single "指数平均数")指数平均数

为了克服上述缺点，我们在此介绍EXPMA指标，该指标的主要优势是：对[移动平均线](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF?fromModule=lemma_inlink)进行了取长补短，同时又具备了KDJ指标和MACD指标的“金叉”和“死叉”等功能。因此该指标具有较高的成功率和准确性，对于[个股](https://baike.baidu.com/item/%E4%B8%AA%E8%82%A1?fromModule=lemma_inlink)的[抄底](https://baike.baidu.com/item/%E6%8A%84%E5%BA%95?fromModule=lemma_inlink)和[逃顶](https://baike.baidu.com/item/%E9%80%83%E9%A1%B6?fromModule=lemma_inlink)提供了较好的点位，是投资者采用中[短线](https://baike.baidu.com/item/%E7%9F%AD%E7%BA%BF?fromModule=lemma_inlink)决策的好帮手。

### 图形特征

1. EXPMA指标由EXPMA1（白线）和EXPMA2（黄线）组成，当白线由下往上穿越黄线时，[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)随后通常会不断上升，那么这两根线形成[金叉](https://baike.baidu.com/item/%E9%87%91%E5%8F%89?fromModule=lemma_inlink)之日便是买入良机。

2. 当一只[个股](https://baike.baidu.com/item/%E4%B8%AA%E8%82%A1?fromModule=lemma_inlink)的股价远离白线后，该股的股价随后很快便会回落，然后再沿着白线上移，可见白线是一大支撑点。

3. 同理，当白线由上往下击穿黄线时，股价往往已经发生转势，日后将会以下跌为主，则这两根线的交叉之日便是卖出时机。

### 市场意义

1. 该指标一般为中[短线](https://baike.baidu.com/item/%E7%9F%AD%E7%BA%BF?fromModule=lemma_inlink)选股指标，比较符合以中短线为主的投资者，据此信号买入者均有获利机会，但对中线投资者来说，其参考意义似乎更大，主要是因为该指标稳定性大，波动性小。

2. 若白线和黄线始终保持距离地上行，则说明该股后市将继续看好，每次[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)回落至白线附近，只要不击穿黄线，则这种回落现象便是良好的买入时机。

3、对于卖出时机而言，个人认为还是不要以EXPMA指标形成[死叉](https://baike.baidu.com/item/%E6%AD%BB%E5%8F%89?fromModule=lemma_inlink)为根据，因为该指标有一定的滞后性，可以超级短线指标为依据，一旦某只[个股](https://baike.baidu.com/item/%E4%B8%AA%E8%82%A1?fromModule=lemma_inlink)形成死叉时，则是中线离场信号。
