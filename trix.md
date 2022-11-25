[三重指数平滑平均线](https://baike.baidu.com/item/%E4%B8%89%E9%87%8D%E6%8C%87%E6%95%B0%E5%B9%B3%E6%BB%91%E5%B9%B3%E5%9D%87%E7%BA%BF/15749345?fromModule=lemma_inlink)（TRIX）属于中长线指标。它过滤掉许多不必要的波动来反映股价的长期波动趋势。在使用均线系统的交叉时，有时会出现骗线的情况，有时还会出现频繁交叉的情况，通常还有一个时间上的确认。为了解决这些问题，因而发明了TRIX这个指标把均线的数值再一次地算出平均数，并在此基础上算出第三重的平均数。这样就可以比较有效地避免频繁出现交叉信号。 TRIX指标又叫三重指数平滑移动平均指标，其英文全名为“Triple Exponentially Smoothed Average”，是一种研究股价趋势的长期**技术分析**工具。

## 指标原理



TRIX指标是根据**[移动平均线](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF?fromModule=lemma_inlink)**理论，对一条平均线进行三次平滑处理，再根据这条移动平均线的变动情况来预测股价的长期走势。与TRMA等[趋向类指标](https://baike.baidu.com/item/%E8%B6%8B%E5%90%91%E7%B1%BB%E6%8C%87%E6%A0%87/5376630?fromModule=lemma_inlink)一样，TRIX指标一方面忽略价格短期波动的干扰，除去移动平均线频繁发出假信号的缺陷，以最大可能地减少主力“骗线行为”的干扰，避免由于交易行为过于频繁而造成较大交易成本的浪费，二则保留移动平均线的效果，凸现[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7/9079155?fromModule=lemma_inlink)未来长期运动趋势，使投资者对未来较长时间内股价运动趋势有个直观、准确地了解，从而降低投资者深度套牢和跑丢“黑马”的风险。因此，对于稳健型的长期投资者来说，TRIX指标对实战提供有益的参考。

## 计算公式



1. TR=收盘价的N日指数移动平均；

2.TRIX=(TR-昨日TR)/昨日TR*100；

3.MATRIX=TRIX的M日简单移动平均；

4.参数N设为12，参数M设为20；

5.函数：TR := EMA(EMA(EMA(CLOSE,N),N),N);TRIX := (TR-REF(TR,1))/REF(TR,1)*100;TRMA := MA(TRIX,M)。

## 实战技巧



TRIX线基本用法

TRIX指标是属于中长线**[技术指标](https://baike.baidu.com/item/%E6%8A%80%E6%9C%AF%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)**，其最大的优点就是可以过滤短期波动的干扰，以避免频繁操作而带来的失误和损失。因此TRIX指标最适合于对行情的中长期走势的研判。在股市软件上TRIX指标有两条线，一条线为TRIX线，另一条线为TRMA线。TRIX指标的一般研判标准主要集中在TRIX线和TRMA线的交叉情况的考察上。其基本分析内容如下：

1、当TRIX线一旦从下向上突破TRMA线，形成“金叉”时，预示着股价开始进入强势拉升阶段，投资者应及时买进股票。

2、当TRIX线向上突破TRMA线后，TRIX线和TRMA线同时向上运动时，预示着股价强势依旧，投资者应坚决持股待涨。

3、当TRIX线在高位有走平或掉头向下时，可能预示着股价强势特征即将结束，投资者应密切注意股价的走势，一旦K线图上的股价出现大跌迹象，投资者应及时卖出股票。

4、当TRIX线在高位向下突破TRMA线，形成“死叉”时，预示着股价强势上涨行情已经结束，投资者应坚决卖出余下股票，及时离场观望。

5、当TRIX线向下突破TRMA线后，TRIX线和TRMA线同时向下运动时，预示着股价弱势特征依旧，投资者应坚决持币观望。

6、当TRIX线在TRMA下方向下运动很长一段时间后，并且股价已经有较大的跌幅时，如果TRIX线在底部有走平或向上勾头迹象时，一旦股价在大的成交量的推动下向上攀升时，投资者可以及时少量地中线建仓。

7、当TRIX线再次向上突破TRMA线时，预示着股价将重拾升势，投资者可及时买入，持股待涨。

8、TRIX指标不适用于对股价的盘整行情的研判。

TRIX线与股价

一般而言，在一个股票的完整的升势和跌势过程中，TRIX指标中的TRIX线和TRMA线会出现两次或以上的“黄金交叉”和“[死亡交叉](https://baike.baidu.com/item/%E6%AD%BB%E4%BA%A1%E4%BA%A4%E5%8F%89?fromModule=lemma_inlink)”情况。

1、当[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)经过一段很长时间的下跌[行情](https://baike.baidu.com/item/%E8%A1%8C%E6%83%85?fromModule=lemma_inlink)后，TRIX线开始向上突破TRMA线时，表明股市即将转强，股价跌势已经结束，将止跌朝上，可以开始买进股票，进行中长线[建仓](https://baike.baidu.com/item/%E5%BB%BA%E4%BB%93?fromModule=lemma_inlink)。这是TRIX指标“黄金交叉”的一种形式。

2、当股价经过一段时间的上升过程中的盘整行情后，TRIX线开始再次向上突破TRMA线，成交量再度放出时，表明股市处于一种强势之中，股价将再次上涨，可以加码买进股票或[持股待涨](https://baike.baidu.com/item/%E6%8C%81%E8%82%A1%E5%BE%85%E6%B6%A8?fromModule=lemma_inlink)，这就是TRIX指标“黄金交叉”的一种形式。

3、当[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)经过前期一段很长时间的上升[行情](https://baike.baidu.com/item/%E8%A1%8C%E6%83%85?fromModule=lemma_inlink)后，股价[涨幅](https://baike.baidu.com/item/%E6%B6%A8%E5%B9%85?fromModule=lemma_inlink)已经很大的情况下，一旦TRIX线向下突破TRMA时，表明股市即将由强势转为弱势，股价将大跌，这时应卖出大部分股票而不能买股票，这就是TRMA指标的“[死亡交叉](https://baike.baidu.com/item/%E6%AD%BB%E4%BA%A1%E4%BA%A4%E5%8F%89?fromModule=lemma_inlink)”的一种形式。

4、当股价经过一段时间的下跌后，而股价向上上涨的动力缺乏，各种[均线](https://baike.baidu.com/item/%E5%9D%87%E7%BA%BF?fromModule=lemma_inlink)对股价形成较强的压力时，一旦TRIX线再次向下突破TRMA线时，表明股市将再次进入极度弱市中，股价还将下跌，可以再卖出股票或观望，这是TRMA指标“死亡交叉”的另一种形式。

TRIX指标曲线的形态

当TRIX指标在[高位盘整](https://baike.baidu.com/item/%E9%AB%98%E4%BD%8D%E7%9B%98%E6%95%B4?fromModule=lemma_inlink)或[低位](https://baike.baidu.com/item/%E4%BD%8E%E4%BD%8D?fromModule=lemma_inlink)[横盘](https://baike.baidu.com/item/%E6%A8%AA%E7%9B%98?fromModule=lemma_inlink)时所出现的各种形态也是判断[行情](https://baike.baidu.com/item/%E8%A1%8C%E6%83%85?fromModule=lemma_inlink)，决定买卖行动的一种分析方法。

1、当TRIX曲线在高位形成M头或[三重顶](https://baike.baidu.com/item/%E4%B8%89%E9%87%8D%E9%A1%B6?fromModule=lemma_inlink)等高位[反转形态](https://baike.baidu.com/item/%E5%8F%8D%E8%BD%AC%E5%BD%A2%E6%80%81?fromModule=lemma_inlink)时，意味着[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)的上升动能已经衰竭，股价有可能出现长期反转行情，投资者应及时地卖出股票。如果股价走势曲线也先后出现同样形态则更可确认，股价下跌的幅度和过程可参照M头或三重顶等顶部反转形态的研判。

2、当TRIX曲线在低位形成W低或三重低等低位反转形态时，意味着股价的下跌动能已经减弱，股价有可能构筑中长期底部，投资者可逢低[分批建仓](https://baike.baidu.com/item/%E5%88%86%E6%89%B9%E5%BB%BA%E4%BB%93?fromModule=lemma_inlink)。如果股价走势曲线也先后出现同样形态则更可确认，股价的上涨幅度及过程可参照W底或

[三重底](https://baike.baidu.com/item/%E4%B8%89%E9%87%8D%E5%BA%95?fromModule=lemma_inlink)等底部[反转形态](https://baike.baidu.com/item/%E5%8F%8D%E8%BD%AC%E5%BD%A2%E6%80%81?fromModule=lemma_inlink)的研判。

3、TRIX曲线顶部反转形态对[行情](https://baike.baidu.com/item/%E8%A1%8C%E6%83%85?fromModule=lemma_inlink)判断的准确性要高于底部形态

TRIX指标的背离

TRIX指标的背离是指TRIX指标的曲线的走势正好和[股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)K线图上的走势正好相 反。和其他技术分析指标一样，TRIX指标的背离也分为[顶背离](https://baike.baidu.com/item/%E9%A1%B6%E8%83%8C%E7%A6%BB?fromModule=lemma_inlink)和[底背离](https://baike.baidu.com/item/%E5%BA%95%E8%83%8C%E7%A6%BB?fromModule=lemma_inlink)两种。

1、 顶背离

当股价K线图上的股票走势一峰比一峰高，股价在一直向上涨，而TRIX指标图 上的TRIX曲线的走势是在高位一峰比一峰低，这叫顶背离现象。顶背离现象一 般是股价将高位反转的信号，表明股价短期内即将下跌，是比较强烈的[卖出信号](https://baike.baidu.com/item/%E5%8D%96%E5%87%BA%E4%BF%A1%E5%8F%B7?fromModule=lemma_inlink)。

2、底背离

当股价K线图上的股票走势一峰比一峰低，股价在向下跌，而TRIX指标图上的 TRIX曲线的走势是在[低位](https://baike.baidu.com/item/%E4%BD%8E%E4%BD%8D?fromModule=lemma_inlink)一底比一底高，这叫[底背离现象](https://baike.baidu.com/item/%E5%BA%95%E8%83%8C%E7%A6%BB%E7%8E%B0%E8%B1%A1?fromModule=lemma_inlink)。底背离现象一般是 [股价](https://baike.baidu.com/item/%E8%82%A1%E4%BB%B7?fromModule=lemma_inlink)将低位反转的信号，表明股价短期内即将上涨，是比较强烈的买入信号。 [指标背离](https://baike.baidu.com/item/%E6%8C%87%E6%A0%87%E8%83%8C%E7%A6%BB?fromModule=lemma_inlink)一般出现在强势[行情](https://baike.baidu.com/item/%E8%A1%8C%E6%83%85?fromModule=lemma_inlink)中比较可靠。即股价在高位时，通常只需出现一次 [顶背离](https://baike.baidu.com/item/%E9%A1%B6%E8%83%8C%E7%A6%BB?fromModule=lemma_inlink)的形态即可确认行情的顶部反转，而股价在低位时，一般要反复出现多次 [底背离](https://baike.baidu.com/item/%E5%BA%95%E8%83%8C%E7%A6%BB?fromModule=lemma_inlink)后才可确认行情的底部反转。

参数的修改

从TRIX指标的计算方法可以看出TRIX指标也是以时间为参数，构成参数的的时 间周期可以是日、月或周、年、分钟等，而这些时间周期又根据股票上市时间的 长短和投资者的取舍，理论上可以采取任意的时间长度，在大部分主流的股市分

析软件（如钱龙、[分析家](https://baike.baidu.com/item/%E5%88%86%E6%9E%90%E5%AE%B6?fromModule=lemma_inlink)）上，各种时间周期的变动范围又大多数都被限定在 1——99内，如1日——99日、1周——99周等。虽然也有一些股市分析软件对 参数的设定扩大到1——999的范围，但这部分的软件比较少，因此，本节的TRIX

指标的参数设定还是限定在1——99的范围内。

TRIX为股价之[三重指数平滑平均线](https://baike.baidu.com/item/%E4%B8%89%E9%87%8D%E6%8C%87%E6%95%B0%E5%B9%B3%E6%BB%91%E5%B9%B3%E5%9D%87%E7%BA%BF/15749345?fromModule=lemma_inlink)，此指标类似MACD，属于长期趋势指标，在盘整或短期波动较剧烈的行情中，容易产生假讯号。本指标于长期趋势中，可过滤掉许多不必要的波动，配合一条TRIX的平均线使用，其效果相当良好。

**买卖原则**

⑴盘整行情本指标不适用。

⑵TRIX向上交叉其TMA线，买进；TRIX向下交叉其TMA线，卖出。

⑶TRIX与股价产生背离时，应注意随时会反转。

⑷TRIX是一种三重指数平滑平均线。

[1] 

特殊分析方法

TRIX指标的特殊[研判](https://baike.baidu.com/item/%E7%A0%94%E5%88%A4?fromModule=lemma_inlink)主要集中在三点，一是TRIX线和TRMA线的几次[交叉](https://baike.baidu.com/item/%E4%BA%A4%E5%8F%89/36234?fromModule=lemma_inlink)情况的研判，二是[均线](https://baike.baidu.com/item/%E5%9D%87%E7%BA%BF?fromModule=lemma_inlink)先行原则，三是TRIX不同[参数](https://baike.baidu.com/item/%E5%8F%82%E6%95%B0?fromModule=lemma_inlink)的修改及使用范围上。 [2] 

## 指标优势



1、[TRIX指标](https://baike.baidu.com/item/TRIX%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)和其他一些诸如TRMA指标一样，TRIX指标可以帮助投资人在进行指标分析的时候排除一些来自于价格短期波动的干扰[信号](https://baike.baidu.com/item/%E4%BF%A1%E5%8F%B7/32683?fromModule=lemma_inlink)，能有效的解决[移动平均线理论](https://baike.baidu.com/item/%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF%E7%90%86%E8%AE%BA/5770811?fromModule=lemma_inlink)经常会发出的一些假信号的情况，最大可能的帮助投资人更好的看清汇市，避免造成亏损。

2、[TRIX指标](https://baike.baidu.com/item/TRIX%E6%8C%87%E6%A0%87?fromModule=lemma_inlink)也可能保留移动平均线的使用效果，TRIX指标和移动均线一样也可以显现出[汇价](https://baike.baidu.com/item/%E6%B1%87%E4%BB%B7?fromModule=lemma_inlink)在接下来一段时间内的波动趋势，使得投资者对于接下来的时间内价格的[波动](https://baike.baidu.com/item/%E6%B3%A2%E5%8A%A8/26938?fromModule=lemma_inlink)趋势有一个简单直观的了解，很好的提高投资人投资的成功率。
