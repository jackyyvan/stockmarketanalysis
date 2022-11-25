https://baike.baidu.com/item/KDJ%E6%8C%87%E6%A0%87/6328421?fromtitle=kdj&fromid=3423560&fr=aladdin

随机指标KDJ一般是用于股票分析的统计体系，根据[统计学原理](https://baike.baidu.com/item/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E5%8E%9F%E7%90%86/2010)，通过一个特定的周期（常为9日、9周等）内出现过的最高价、最低价及最后一个计算周期的收盘价及这三者之间的比例关系，来计算最后一个计算周期的[未成熟随机值](https://baike.baidu.com/item/%E6%9C%AA%E6%88%90%E7%86%9F%E9%9A%8F%E6%9C%BA%E5%80%BC/12754795)RSV，然后根据[平滑移动平均线](https://baike.baidu.com/item/%E5%B9%B3%E6%BB%91%E7%A7%BB%E5%8A%A8%E5%B9%B3%E5%9D%87%E7%BA%BF/5876987)的方法来计算K值、D值与J值，并绘成曲线图来研判股票走势。

## 计算方法



KDJ的计算比较复杂，首先要选择周期（_n_日、_n_周等），再计算当天的[未成熟随机值](https://baike.baidu.com/item/%E6%9C%AA%E6%88%90%E7%86%9F%E9%9A%8F%E6%9C%BA%E5%80%BC/12754795)（即RSV值），然后再计算_K_值、_D_值、_J_值等。

**(1)** RSV的计算公式为：

![](https://bkimg.cdn.bcebos.com/formula/03f4195e9c60a1d157cf41a14ab0c418.svg)

公式中，

_C_为当天的收盘价；

_L__n_为之前_n_日内的最低价；

_H__n_为之前_n_日内的最高价。

**(2)** 某一天的K值=2/3×前一日K值+1/3×当日RSV，即

![](https://bkimg.cdn.bcebos.com/formula/58e65cf9a827ee1e61dfd494be8cb7f5.svg)

_K__i_和RSV_i_分别表示某一天当天的_K_值和RSV值；

_K__i_-1表示前一天的_K_值，若无前一天的_K_值，则用50来代替。

**(3)** 某一天当天的_D_值=2/3×前一日D值+1/3×当日K值，即

![](https://bkimg.cdn.bcebos.com/formula/09e149978cf3b8f4a326cf15470ea265.svg)

_D__i_和_K__i_分别表示当天的_D_值和_K_值；

_D__i_-1表示前一天的_D_值，若无前一天的_D_值，则用50来代替。

**(4)** _J_值=3×当日K值-2×当日D值，即

![](https://bkimg.cdn.bcebos.com/formula/fd7a2cf5ffc23101680348b0fc0e3e81.svg)

例：手中有某只股票30日的数据，以9日为周期，想计算第9天的KDJ值，计算方法为

(1) 先计算第9天当天的RSV值：

RSV = (_C_−_L_) ÷ (_H_−_L_) × 100

公式中

_C_为第9天当天的[收盘价](https://baike.baidu.com/item/%E6%94%B6%E7%9B%98%E4%BB%B7)；

_L_为从第1天到第9天这9天内的[最低价](https://baike.baidu.com/item/%E6%9C%80%E4%BD%8E%E4%BB%B7)；

_H_为从第1天到第9天这9天内的最高价。

(2) 计算第9天的_K_值：

_K_值=2/3×第8日K值+1/3×第9日RSV

第8日_K_值用50代替

(3) 计算第9天的_D_值：

_D_值=2/3×第8日D值+1/3×第9日K值

第8日_D_值用50代替

(4) 计算第9天的J值：

_J_值=3×第9日K值-2×第9日D值

[![](https://bkimg.cdn.bcebos.com/pic/c2cec3fdfc039245a80f93448f94a4c27c1e25c6?x-bce-process=image/resize,m_lfit,w_440,limit_1/format,f_auto)](https://baike.baidu.com/pic/KDJ%E6%8C%87%E6%A0%87/6328421/0/c2cec3fdfc039245a80f93448f94a4c27c1e25c6?fr=lemma&ct=single)

(5) 有了第9天的_K_值和_D_值，则可以进一步计算第10天的_K_值、_D_值和_J_值，再用第10天的_K_值和_D_值计算出第11天的_K_值、_D_值和_J_值，以此类推。

[![](https://bkimg.cdn.bcebos.com/pic/3801213fb80e7bec646f71aa272eb9389a506bc7?x-bce-process=image/resize,m_lfit,w_440,limit_1/format,f_auto)](https://baike.baidu.com/pic/KDJ%E6%8C%87%E6%A0%87/6328421/0/3801213fb80e7bec646f71aa272eb9389a506bc7?fr=lemma&ct=single)

[![](https://bkimg.cdn.bcebos.com/pic/960a304e251f95cad1c88df6bc5c683e6709c93df412?x-bce-process=image/resize,m_lfit,w_440,limit_1/format,f_auto)](https://baike.baidu.com/pic/KDJ%E6%8C%87%E6%A0%87/6328421/0/960a304e251f95cad1c88df6bc5c683e6709c93df412?fr=lemma&ct=single)

## 使用技巧



1.K与D值永远介于0到100之间。D大于80时，行情呈现超买现象。D小于20时，行情呈现超卖现象。

2.上涨趋势中，K值大于D值，K线向上突破D线时，为买进信号。下跌趋势中，K值小于D值，K线向下跌破D线时，为卖出信号。

3.KD指标不仅能反映出市场的超买超卖程度，还能通过交叉突破发出买卖信号。

4.KD指标不适于发行量小、交易不活跃的股票，但是KD指标对大盘和热门大盘股有极高准确性。

5.当随机指标与股价出现背离时，一般为转势的信号。

6.K值和D值上升或者下跌的速度减弱，倾斜度趋于平缓是短期转势的预警信号。

K线与D线的交叉突破在80以上或20以下时较为准确。当这种交叉突破在50左右发生时，表明市场走势陷入盘局，正在寻找突破方向。此时，K线与D线的交叉突破所提供的买卖信号无效。
