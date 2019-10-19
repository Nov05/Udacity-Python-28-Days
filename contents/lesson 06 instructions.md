﻿
在这节课，我们将使用之前所学的 Python 技能来解决一个生活中真实的案例。

假设你（或你父母）最近要贷款买房，需要知道最适合自己的贷款方式。此外，你也了解到房贷的还款方式主要分为两种，分别是等额本金和等额本息。为了使问题简化，我们暂时不考虑公积金冲贷等问题。

等额本金
等额本金是指在还款期内把贷款数总额等分，每月偿还同等数额的本金和剩余贷款在该月所产生的利息，这样由于每月的还款本金额固定，而利息越来越少，借款人起初还款压力较大，但是随时间的推移每月还款数也越来越少。

计算公式：每月还款金额 = (贷款本金 / 还款月数) + (本金 — 已归还本金累计额) × 每月利率

等额本息
等额本息是指在还款期内，每月偿还同等数额的贷款（包括本金和利息）。它和等额本金不同的是，虽然刚开始还款时每月还款额可能会低于等额本金还款方式的额度，但是最终所还利息会高于等额本金还款方式。

计算公式：每月还款额 = [贷款本金 × 月利率 × (1+月利率) ^ 还款月数] ÷ [(1+月利率) ^ 还款月数－1]

对于初学者来说，勤于测试编写的代码是一个非常好的习惯！我们建议你每添加一个功能后，都进行测试以确保代码的正确。在这个项目中，你同样可以使用在线计算器计算的结果来校验你的代码是否正确：

等额本息计算器
http://zzgjj.zhengzhou.gov.cn/debx.jhtml   

等额本金计算器   
http://zzgjj.zhengzhou.gov.cn/debj.jhtml