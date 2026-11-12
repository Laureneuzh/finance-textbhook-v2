# 审稿意见

## 一、出版规范问题

章末体例不一致

在 “How to Use This Book”（前言 iv）一节中， 明确说明教学板块设计包括
Discussion Questions、Applied Problems、Data Applications、Case
Analysis、Financial AI
Lab，但教材实际并未贯彻。而是”板块按章节内容需要选配”。

检查同一板块在不同章的先后顺序，统一为固定顺序，例如 Summary → Mind Map
→ Key Terms → AI Lab → Discussion Questions → Applied Problems → Data
Application → Case Analysis → Further Reading。

统一标题层级的英文大小写，采用“Title case”

## 二、上下文逻辑结构

1.  Part V 与 Part III 章 11 的关系。第 11 章（Derivatives
    Markets）名义上属于 Part III Financial
    Markets，但内容已涉及大量衍生工具的风险转移与定价；Part V 第 17–18
    章又以 Linear/Nonlinear Derivatives
    为题。建议在两编扉页的引言中说明”Part III
    关注市场机制（场内/场外、清算、流动性），Part V
    关注工具构造（远期、期货、互换、期权、信用衍生品）“。

2.  第 16 章 Shadow Banking 与第 12 章 Commercial Banks
    的耦合。两章大量涉及流动性创造、批发融资、抵押品、顺周期性，但 Part
    IV 引言并未显式建立这两章之间的递进，在第 16
    章开篇添加导引，把”传统银行 → 非传统/影子/平台”的演进逻辑显式化。

3.  第 24 章 “Future Architecture of Finance” 篇幅较大（5 节、24
    个三级小节），覆盖
    AI、央行数字货币、稳定币、代币化、DeFi。该章位于全书最后一章，但其内容均属前沿议题；补一段内容强调该章与全书基础框架（特别是第
    1 章四类摩擦、第 21 章系统风险）的回应关系，把”未来架构”作为前 23
    章分析视角的再检验而非孤立展望。

## 三、 案例使用

### 1. 虚拟案例未声明性质

举例如下（包括但不限于）：

- 第 1 章：使用”Li Wei, an engineer in Suzhou”和”Wang
  Cheng”中文姓名撰写虚构故事，未声明 Hypothetical / Teaching
  illustration，也未给出”any resemblance to actual persons is purely
  coincidental”声明。

- 第 17 章：“A copper-products manufacturer expects to purchase 1,000
  tonnes of copper”——典型教学示例，无任何”示例用虚构”声明。

- 第 18 章：“An exporter expects to receive USD 10 million in three
  months”——同上。

- 第 22 章：虽引用 Lehman Brothers 真实事件，但未给来源，读者无法溯源。

学术教材出版规范要求：

教育性案例（含虚构、改编、合成案例）必须在案例首段或末段明确标注性质，否则易被读者当作实际事件引用，造成误导。

要求：根据实际情况· 在案例首段左上角加注 \[Teaching Illustration\] /
\[教学示例\] 或 \[Hypothetical Case Based on Public
Information\]，并在案例末或脚注增加 Note: Names, figures, and events in
this case are hypothetical and are used solely for pedagogical purposes.
句式。

- 若案例以现实事件为依据（如第 4 章公司发债、银行贷款差异），在文末附“
  Source:” 一行，标明数据/事件来源。

### 2. 真实事件未独立列出”Primary sources”

- 第 4 章：引用”大公司发行债券、小公司向银行贷款”对比，应明确数据来源。

- 第 22 章：引用 2008 年 9 月雷曼事件与 FedSwap 互换额度，应给出 BIS /
  FOMC / Federal Reserve Archive 一手来源。

数据型章节（第 4、8、11 章）

含统计图表的章节（数据型案例）应在图表脚注标注数据来源、采集日期、口径；与
Opening Case 类似的虚构示例应在每张图下方注明 Illustrative 字样。

案例的选取

本书中所有涉及的案件、案例，考虑到其存在风险性，为了规避可能产生的版权或学术纠纷，请按以下要求统一修改：

请筛选出最经典、最具有教学性且为人熟知的案例(有些案件可能由于政策的更改而不具时效性，要考虑教材的实用性)，其他重复、不必要的案件、案例请作删除处理。

所有真实案件、案例的来源必须为官方发布的权威报道。

所有真实的案件、案例，均需写明涉事公司的名称、涉事金额、处罚结果，确保以上符合客观事实，不要掺杂任何主观评价。注意:隐去所有人名，只保留公司名。

所有案件、案例，均需添加脚注，补充资料来源。注意:务必保证信息完整，格式同国标。

若对真实案件进行匿名化处理，则建议将主要元素虚拟化，所有数据、处罚结果均需修改为虚假事实，不可出现人名，不能使读者依据上述信息锁定涉事企业。同时，针对已有的虚拟案例，请按本部分1.的要求进行修改。

术语规范

缩写首现未定义

学术出版规范要求：缩写第一次出现时须给出全称，其后统一使用缩写。

| 缩写      | 首次出现位置                                            | 问题                                                                                                                                         |
|-----------|---------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| SPV       | 第 16.2.1 节（原书约 p.352）：“an SPV holds the assets” | 首次使用直接以缩写出现，全称 special-purpose vehicle (SPV) 迟至第 20.1.3 节（p.437）才给出，跨 4 章、约 85 页                                |
| NAV       | 目录 14.2.3 及第 14 章正文                              | 缩写首现于公式与例 14.2 中（p.312 前后），全称 net asset value 未在首现处完整定义                                                            |
| LGD / EAD | 第 8 章式 8.7–8.8（p.175）                              | 公式中已使用 $LGD$、$EAD$，但全称 loss given default、exposure at default 仅在式 8.8 之后的说明句中出现，且 $PD$ 与 $LGD$ 未在符号表统一宣告 |

整改建议：

SPV：在 16.2.1 节首次出现处改为 special-purpose vehicle (SPV)；第 20
章可直接沿用缩写。

NAV：在 14.2 节首次出现处补全 net asset value (NAV)。

LGD/EAD/PD：在第 8 章式 8.7
之前增设”符号说明”句，或全书统一在首次使用章节的 Key Terms 中给出全称。

术语统一

| 术语                                                        | 出现次数     | 建议                                                             |
|-------------------------------------------------------------|--------------|------------------------------------------------------------------|
| cash-flow (92) vs cash flow (359)                           | 并存         | 名词用 cash flow，定语用 cash-flow（当前大体遵循，但有多处误用） |
| interest-rate (60) vs interest rate (187)                   | 并存         | 同上，作定语加连字符                                             |
| risk-free (35) vs risk free (2)                             | 前者为主     | 统一为 risk-free                                                 |
| money-market (23) vs money market (60)                      | 并存         | 名词 money market，定语 money-market                             |
| principal–agent (5，en dash) vs principal-agent (1，hyphen) | 并存         | 复合形容词用 hyphen：principal-agent                             |
| P D（公式中，含空格）                                       | 式 8.8、19.x | LaTeX 源中 PD 被误拆为 $P\,D$，应改为 或 PD                      |

百分比表达混用（请统一）

全书统一为 “%”。

参考文献规范

正文零引用

全书 没有任何一处作者-年份式文内引用，也没有脚注引注。所有文献仅以章末
Further Reading 列表形式出现。

典型例证：

- 第 1.1.2 节明确引用 Knight 的风险/不确定性区分：“Knight distinguished
  risk from uncertainty in a narrower
  sense.”——但正文未给出任何年份或文献指引，仅在章末 Further Reading
  中可能有 Knight (1921)，读者无法对应。

- 第 3 章全章讲授逆向选择、信号传递、筛选、道德风险，学理完全建立在
  Akerlof (1970)、Spence (1973)、Stiglitz-Weiss (1981)、Jensen-Meckling
  (1976)、Holmström (1979)
  之上，但正文一处引注都没有，这五篇文献仅列于章末 Further Reading。

- 第 21 章讨论银行挤兑，未引 Diamond-Dybvig
  (1983)——该书经典的银行挤兑模型，虽列于进一步阅读，但正文未标引。

- 第 11 章讲授无套利与复制，未在正文标引 Black-Scholes (1973)、Merton
  (1973)、Harrison-Kreps (1979)。

学术教材（尤其是本科高年级/研究生层次）必须做到”观点有出”：凡引用他人理论、模型、实证结论、数据，均须在文内标注来源。仅提供
Further
Reading不足以替代引注——前者是推荐书目，后者是学术归属。二者功能不同，不可互相替代。

建议：

- 补正文引注：在第 1、3、11、21 章等理论密度高的章节，逐段补入 (Knight,
  1921)、(Akerlof, 1970)、(Diamond & Dybvig, 1983)、(Black &
  Scholes, 1973) 等文内引注。

- 增设 References：在全书末尾（或每编末）增设 References /
  Bibliography，收录正文引注与 Further Reading
  的全部条目，二者需交叉对应。

- 区分两类列表：Further Reading
  保留为”推荐读物”（可含未在正文引用的书），References
  专收正文引注，避免混同。

- 统一引注格式：采用 APA 7 或 Chicago Author-Date（当前 Further Reading
  已近 Chicago 风格，建议沿用以保持一致性）。

- 书末补充全书参考文献： 补充全书引用的参考文献。

数据来源

书稿中所有数据，包括出现在正文、图片、表格中的数据，凡引用他人成果的均需补充参考文献。正文需添加脚注，图片、表格需在下方补充“Source：”或“Note：”。引用格式全书统一。

图表格式

- 部分图表，正文中并未提及，且图表位置排在了解释文字的前边。

正确格式应为：先文后图表，正文中需先提到图表（如“XXX see figure
1.1”），所在段落下方紧跟图表。

## 八、对于公式前面有A simpled measure的句子去掉simple，重新改写为规范的句子

## 九、例子的renminbi 统一改为RMB，尤其是紧跟数值结果的renminbi，

## 十、去掉`\emph{}`,强调部分，或者在每一章中都设置有`\emph{}`，全书统一

十一、注意符号的统一性。
十二、注意单词不要从中间断掉，尤其是表格中的单词，调整表格格式以解决。