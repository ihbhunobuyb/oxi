# 论文精读分析报告

## 基本信息

- **PMID**: 41621245
- **标题**: Macrophage AMPK activated by oxidative stress drives profibrotic crosstalk with tubular cells to accelerate renal fibrosis after ischemic and reperfusion injury
- **期刊**: Redox Biology
- **发表日期**: 2026年3月
- **DOI**: 10.1016/j.redox.2025.104002
- **PMID**: 41621245

## 作者信息

| 作者 | 机构 |
|------|------|
| Tao Y (第1作者) | 中国人民解放军总医院儿科，高级科室，北京 |
| Zhang M | 中国人民解放军总医院肾病科，肾脏疾病国家重点实验室，国家肾病疾病临床研究中心，北京 |
| Chen L | 西安交通大学第一附属医院危重症肾病与血液净化科 |
| Jia H | 中国人民解放军总医院儿科 |
| Yang Y | 南方医科大学第二临床医学院；华南理工大学医学院第六附属医院儿科 |
| Wu Y | 中国人民解放军总医院儿科 |
| Li P | 中国人民解放军总医院儿科 |
| Wen Z | 中国人民解放军总医院儿科 |
| Zhang X | 中国人民解放军总医院儿科 |
| Chen X (通讯) | 中国人民解放军总医院肾病科 |
| Chen X (通讯) | 中国人民解放军总医院肾病科 |
| Li X | 中国人民解放军总医院泌尿外科 |
| Zhou H (通讯) | 中国人民解放军总医院儿科 |

---

# 第一部分：论文完整摘要

## 英文摘要

Ischemia-reperfusion injury (IRI) is a major cause of acute kidney injury (AKI) that significantly increases the risk of progression to chronic kidney disease (CKD). Although oxidative stress has been implicated in this transition, the precise mechanisms through which it orchestrates inflammation and fibrosis during IRI-induced AKI-CKD progression remain poorly understood. In this study, we observed sustained reactive oxygen species (ROS) production in post-IRI kidneys. ROS were found to activate AMP-activated protein kinase (AMPK) in macrophages in a calcium-dependent manner. Conditional knockout of AMPKα1 in macrophages (Lyz2-Cre; Prkaa1-fl/fl mice) significantly attenuated renal fibrosis following IRI. Single-cell RNA sequencing analysis further revealed that AMPKα1 deletion reduced the accumulation of Arg1+ MMP12+ macrophages and diminished a profibrotic tubular epithelial cell (TEC) subpopulation marked by persistent expression of PDGFB and VCAM1. These macrophages were shown to interact with PDGFB+ VCAM1+ TECs. Mechanistically, macrophage-derived TWEAK signaling through its receptor Fn14 promoted PDGFB production in TECs, driving maladaptive changes and a fibrogenic phenotype. Importantly, TWEAK neutralization effectively mitigated the AKI-to-CKD transition. Together, our results identify macrophage AMPK as a key redox sensor that, upon activation by oxidative stress, initiates maladaptive macrophage-TEC crosstalk, ultimately promoting renal fibrosis and CKD progression.

## 中文摘要

缺血-再灌注损伤（IRI）是急性肾损伤（AKI）的主要病因之一，显著增加了向慢性肾脏疾病（CKD）进展的风险。尽管氧化应激已被证实参与这一转变，但氧化应激在IRI诱导的AKI-CKD进展过程中如何协调炎症和纤维化的具体机制仍不清楚。在本研究中，我们观察到IRI后肾脏中活性氧（ROS）的持续产生。ROS以钙依赖性方式激活巨噬细胞中的AMP激活蛋白激酶（AMPK）。巨噬细胞中AMPKα1的条件性基因敲除（Lyz2-Cre; Prkaa1-fl/fl小鼠）显著减轻了IRI后的肾纤维化。单细胞RNA测序分析进一步揭示，AMPKα1缺失减少了Arg1+ MMP12+巨噬细胞的积累，并减弱了以持续表达PDGFB和VCAM1为标志的促纤维化肾小管上皮细胞（TEC）亚群的形成。研究表明，这些巨噬细胞与PDGFB+ VCAM1+ TECs相互作用。机制上，巨噬细胞来源的TWEAK信号通过其受体Fn14促进TECs中PDGFB的产生，推动适应性不良改变和纤维化表型。重要的是，TWEAK中和有效地减轻了AKI向CKD的转变。总之，我们的研究结果将巨噬细胞AMPK确定为关键的红氧传感器，一旦被氧化应激激活，就会启动适应性不良的巨噬细胞-TEC对话，最终促进肾纤维化和CKD进展。

---

# 第二部分：氧化应激与AMPK调控机制分析

## 1. 缺血-再灌注损伤（IRI）概述

### 1.1 IRI的病理生理基础

缺血-再灌注损伤（Ischemia-Reperfusion Injury, IRI）是肾脏疾病中一个重要的病理过程，也是急性肾损伤（Acute Kidney Injury, AKI）的主要原因之一。IRI的病理生理机制涉及多个相互关联的细胞和分子过程：

**缺血期（Ischemia Phase）**:
- 血液供应减少导致肾脏组织缺氧
- ATP合成减少导致细胞能量危机
- 细胞内钙离子超载
- 代谢产物累积（乳酸、次黄嘌呤等）

**再灌注期（Reperfusion Phase）**:
- 血液再供应带来大量氧气
- 活性氧（ROS）大量爆发式产生
- 炎症细胞浸润
- 细胞凋亡和坏死

### 1.2 IRI与CKD的关联

本研究发现IRI显著增加从AKI向慢性肾脏疾病（CKD）进展的风险。这一临床转化路径已得到广泛认可：

- AKI事件是CKD发展的重要独立危险因素
- 反复的AKI发作加速CKD进展
- 即使是单一的严重AKI事件也可能导致不可逆的肾脏损伤

## 2. 氧化应激在IRI中的作用

### 2.1 ROS的持续产生

本研究的一个重要发现是在IRI后肾脏中观察到**持续性ROS产生**。这一发现具有重要意义：

**持续性ROS产生的重要性**:
- 不同于急性期的ROS爆发
- 提示ROS不仅是损伤介质，更是持续性病理过程的驱动因素
- 为氧化应激作为"红氧传感器"提供功能基础

### 2.2 ROS介导的信号传导

ROS不仅是直接的细胞毒性分子，更是重要的信号分子：

**ROS作为信号分子的作用机制**:
- 氧化修饰蛋白质，改变其功能
- 调节转录因子活性（如NF-κB, Nrf2）
- 激活氧化还原敏感性激酶（如MAPK, AMPK）
- 调控离子通道功能

## 3. AMPK的激活机制

### 3.1 AMPK概述

AMP激活蛋白激酶（AMPK）是细胞能量代谢的关键调节器：

**AMPK的基本特征**:
- 异源三聚体复合物：α催化亚基 + β和γ调节亚基
- α1和α2两种催化亚基亚型
- 响应AMP/ATP比例变化
- 协调细胞能量平衡

### 3.2 钙依赖性AMPK激活

本研究揭示ROS以**钙依赖性方式**激活巨噬细胞中的AMPK：

**钙-AMPK信号通路**:
```
ROS → 钙离子内流/释放 → CaMKKβ激活 → AMPKα1磷酸化 → 下游效应
```

**具体机制**:
1. ROS诱导细胞内钙离子浓度升高
2. 钙离子激活钙调蛋白依赖性蛋白激酶β（CaMKKβ）
3. CaMKKβ磷酸化AMPKα1的Thr172位点
4. 活化的AMPK启动下游信号级联

### 3.3 巨噬细胞特异性AMPKα1的意义

研究采用**Lyz2-Cre; Prkaa1-fl/fl**条件性基因敲除小鼠模型：

- Lyz2启动子驱动Cre重组酶在髓系细胞（巨噬细胞）中表达
- Prkaa1（AMPKα1编码基因）被条件性敲除
- 在蛋白质水平验证AMPKα1缺失

---

# 第三部分：巨噬细胞-肾小管上皮细胞对话机制

## 1. 单细胞RNA测序揭示的细胞亚群

### 1.1 Arg1+ MMP12+巨噬细胞亚群

单细胞RNA测序分析揭示了**Arg1+ MMP12+巨噬细胞**在IRI后肾脏中的显著积累：

**Arg1（精氨酸酶1）**:
- M2型巨噬细胞标志物
- 促进脯氨酸合成和胶原沉积
- 参与组织重塑和纤维化

**MMP12（基质金属蛋白酶12）**:
- 弹性蛋白酶活性
- 参与细胞外基质重塑
- 与炎症和纤维化相关

### 1.2 PDGFB+ VCAM1+ TEC亚群

同样鉴定出以**PDGFB和VCAM1持续表达**为特征的促纤维化肾小管上皮细胞亚群：

**PDGFB（血小板衍生生长因子B）**:
- 强效的成纤维细胞增殖因子
- 刺激肌成纤维细胞分化
- 促进细胞外基质沉积

**VCAM1（血管细胞粘附分子1）**:
- 细胞表面糖蛋白
- 介导细胞间粘附
- 参与炎症细胞浸润

## 2. 巨噬细胞-TEC相互作用

### 2.1 空间邻近关系

研究表明Arg1+ MMP12+巨噬细胞与PDGFB+ VCAM1+ TECs存在直接相互作用：

- 单细胞测序数据分析揭示两群细胞的空间邻近
- 细胞间通讯分析证实直接的配体-受体相互作用

### 2.2 通讯信号网络

这种细胞间对话涉及多个信号分子和受体：

```
巨噬细胞                    肾小管上皮细胞
   |                            ↑
   | TWEAK                     |
   ↓                    Fn14受体
   |                            |
   ↓                            ↓
  促进PDGFB表达 ←←←←←←←←←←←
   ↓
  肌成纤维细胞活化
   ↓
  纤维化
```

## 3. TWEAK/Fn14信号通路

### 3.1 TWEAK信号分子

**TWEAK（TNF-like weak inducer of apoptosis）**:
- TNF超家族成员
- 多效性细胞因子
- 可由多种细胞产生，包括巨噬细胞

### 3.2 Fn14受体

**Fn14（TNFRSF12A）**:
- TWEAK的特异性受体
- 跨膜受体
- 在多种组织细胞中表达，包括肾小管上皮细胞

### 3.3 TWEAK-Fn14信号传导机制

**信号级联**:
1. 巨噬细胞分泌TWEAK
2. TWEAK结合TEC表面的Fn14受体
3. Fn14激活下游信号通路（NF-κB, MAPK等）
4. 促进PDGFB转录和分泌
5. 诱导TEC向纤维化表型转化

---

# 第四部分：关键分子机制与信号通路

## 1. 核心发现： macrophage AMPK作为红氧传感器

本研究的核心发现是鉴定**巨噬细胞AMPK作为关键的红氧传感器**：

### 1.1 红氧传感器的特征

作为有效的红氧传感器需要满足以下条件：

| 特征 | 描述 |
|------|------|
| ROS敏感性 | 能够响应ROS变化 |
| 信号转换 | 将氧化信号转化为细胞内信号 |
| 效应启动 | 触发下游生物效应 |
| 病理相关性 | 参与疾病发生发展 |

### 1.2 AMPK作为红氧传感器的证据

本研究中AMPK作为红氧传感器的证据：

1. **ROS激活AMPK**：IRI后ROS持续产生伴随AMPK激活
2. **钙依赖性**：AMPK激活依赖钙离子介导
3. **功能相关性**：AMPK激活驱动促纤维化表型
4. **干预有效性**：抑制AMPK可减轻纤维化

## 2. AKI-CKD转化的分子机制

### 2.1 适应性不良修复（Maladaptive Repair）

本研究揭示了IRI后适应性不良修复的分子机制：

**适应性不良的特征**:
- 持续炎症状态
- 异常细胞增殖
- 成纤维细胞活化
- 细胞外基质过度沉积

### 2.2 纤维化进展的信号网络

```
IRI损伤
   ↓
ROS持续产生
   ↓
巨噬细胞AMPK激活
   ↓
TWEAK分泌增加
   ↓
TEC表面Fn14受体表达/激活
   ↓
TEC中PDGFB表达上调
   ↓
成纤维细胞活化
   ↓
胶原沉积和纤维化
   ↓
CKD进展
```

## 3. 干预靶点验证

### 3.1 AMPKα1基因敲除的保护作用

**条件性基因敲除效果**:
- 显著减轻IRI后的肾纤维化
- 减少Arg1+ MMP12+巨噬细胞浸润
- 降低PDGFB+ VCAM1+ TEC亚群比例

### 3.2 TWEAK中和的治疗潜力

**中和抗体治疗**:
- 有效减轻AKI向CKD的转变
- 阻断巨噬细胞-TEC相互作用
- 为临床干预提供新策略

---

# 第五部分：研究创新与意义

## 1. 科学创新

### 1.1 概念创新

本研究的概念创新在于：

1. **红氧传感器鉴定**：首次将AMPK鉴定为巨噬细胞中的红氧传感器
2. **细胞对话机制**：揭示氧化应激通过调控细胞间通讯驱动纤维化
3. **转化桥梁**：连接AKI与CMD的分子 link

### 1.2 技术创新

1. **单细胞测序应用**：高分辨率解析肾脏微环境细胞组成
2. **条件性基因敲除**：精确操控特定细胞类型的基因表达
3. **中和抗体策略**：验证治疗性干预的可行性

## 2. 临床意义

### 2.1 预后评估

**生物标志物潜力**:
- 循环TWEAK水平可能预测CKD进展
- 巨噬细胞浸润程度可作为纤维化风险指标

### 2.2 治疗策略

**潜在干预靶点**:
| 靶点 | 策略 | 备注 |
|------|------|------|
| AMPKα1 | 抑制剂 | 需要组织特异性 |
| TWEAK | 中和抗体 | 已验证有效 |
| Fn14 | 阻断剂 | 受体层面干预 |
| PDGFB | 中和抗体 | 下游效应 |

---

# 第六部分：研究局限与未来方向

## 1. 研究局限

### 1.1 技术局限

1. **动物模型**：小鼠IRI模型与人类疾病的差异
2. **时间尺度**：实验观察期 vs 人类疾病进程
3. **特异性**：条件性敲除的脱靶效应

### 1.2 机制研究局限

1. **细胞来源**：TWEAK的具体细胞来源需要进一步明确
2. **信号复杂性**：其他可能参与的信号通路
3. **个体差异**：遗传背景对疾病易感性的影响

## 2. 未来研究方向

### 2.1 深入机制研究

1. **AMPK下游效应**：鉴定AMPK调控的下游分子靶点
2. **表观遗传调控**：探索纤维化的表观遗传记忆机制
3. **代谢重编程**：分析代谢改变对细胞功能的影响

### 2.2 转化研究

1. **生物标志物验证**：在临床队列中验证候选标志物
2. **干预策略开发**：开发特异性靶向药物
3. **精准医疗**：基于分子分层的个体化治疗

---

# 第七部分：文献背景与研究定位

## 1. AKI-CKD转化研究现状

### 1.1 临床挑战

AKI向CKD的转化是当前肾脏病学面临的重要挑战：

- 发病率高：AKI在住院患者中发生率高达10-15%
- 预后不良：AKI患者CKD风险增加2-3倍
- 机制不清：转化过程中的分子机制尚未完全阐明

### 1.2 研究热点

当前AKI-CKD转化的研究热点包括：

1. **炎症与纤维化**：慢性炎症在纤维化中的作用
2. **细胞命运**：肾小管上皮细胞的去分化和转分化
3. **微环境**：细胞外基质和血管系统的作用
4. **代谢因素**：代谢重编程对细胞功能的影响

## 2. AMPK在肾脏疾病中的作用

### 2.1 AMPK的肾脏保护作用

传统观点认为AMPK具有肾脏保护作用：

- 能量代谢调节：维持细胞ATP水平
- 抗炎作用：抑制炎症信号通路
- 抗纤维化：调节成纤维细胞活化

### 2.2 本研究的挑战性发现

本研究揭示了AMPK在特定情境下的促纤维化作用：

- **情境依赖性**：在氧化应激条件下，AMPK激活促进纤维化
- **细胞特异性**：巨噬细胞AMPK的促纤维化作用
- **时间依赖性**：AMPK在不同疾病阶段可能发挥不同作用

## 3. TWEAK/Fn14在肾脏疾病中的作用

### 3.1 TWEAK的生物学功能

TWEAK是一种多效性细胞因子：

- 促炎作用：诱导炎症因子表达
- 细胞增殖：促进细胞增殖
- 细胞死亡：诱导细胞凋亡（在某些条件下）
- 组织修复：参与组织重塑

### 3.2 TWEAK与肾脏疾病

TWEAK在多种肾脏疾病中发挥重要作用：

- AKI：促进肾小管细胞损伤
- CKD：促进纤维化进展
- 糖尿病肾病：加重蛋白尿和纤维化

---

# 第八部分：分子机制深度解析

## 1. ROS-AMPK信号轴

### 1.1 ROS的产生与清除

**ROS来源**:
- 线粒体电子传递链泄漏
- NADPH氧化酶（NOX）活化
- 黄嘌呤氧化酶活性增加
- 过氧化物酶体功能

**ROS清除系统**:
- 超氧化物歧化酶（SOD）
- 过氧化氢酶（CAT）
- 谷胱甘肽过氧化物酶（GPx）
- 硫氧还蛋白（Trx）

### 1.2 ROS对AMPK的激活机制

**直接激活途径**:
```
氧化应激 → 钙离子动员 → CaMKKβ → AMPKα1 (Thr172)
```

**间接激活途径**:
```
氧化应激 → AMP/ATP比例升高 → AMPKγ亚基感知 → AMPK激活
```

## 2. TWEAK-Fn14信号转导

### 2.1 信号通路概述

**主要信号通路**:
1. **NF-κB通路**：经典炎症通路
2. **MAPK通路**：细胞增殖和分化
3. **PI3K/Akt通路**：细胞存活和代谢
4. **STAT通路**：基因转录调控

### 2.2 TWEAK诱导PDGFB表达的机制

**转录调控机制**:
1. Fn14激活 → TRAF蛋白招募
2. 下游激酶活化（NIK, IKK）
3. 转录因子激活（NF-κB, AP-1）
4. PDGFB基因启动子活化
5. PDGFB mRNA转录和蛋白分泌

## 3. 纤维化形成的细胞和分子基础

### 3.1 成纤维细胞活化

**活化的成纤维细胞特征**:
- α-SMA表达增加
- 胶原合成增加
- 增殖能力增强
- 收缩能力增强

### 3.2 TEC转分化

**肾小管上皮细胞-间充质转化（TEMT）**:
- E-cadherin表达下降
- α-SMA表达增加
- 间充质标记物表达
- 迁移和侵袭能力增强

---

# 第九部分：研究方法学分析

## 1. 实验模型

### 1.1 动物模型

**IRI模型**:
- 双侧肾蒂结扎法
- 再灌注时间：30-45分钟
- 观察时间点：多时间点追踪

### 1.2 基因修饰小鼠

**条件性基因敲除策略**:
- Cre-LoxP系统
- Lyz2-Cre驱动髓系细胞特异性敲除
- Prkaa1 floxed等位基因

## 2. 关键实验技术

### 2.1 单细胞RNA测序

**技术优势**:
- 高分辨率细胞异质性分析
- 发现新的细胞亚群
- 解析细胞间通讯网络

**数据分析**:
- 基因表达定量
- 细胞类型注释
- 轨迹分析
- 配体-受体相互作用分析

### 2.2 功能验证实验

**干预实验**:
- 基因敲除验证
- 中和抗体治疗
- 抑制剂应用

**表型分析**:
- 组织学染色（Masson, Sirius Red）
- 免疫组化/免疫荧光
- 分子生物学检测（Western Blot, qPCR）

---

# 第十部分：总结与展望

## 1. 核心发现总结

本研究的核心发现可概括为：

1. **氧化应激-Ros持续产生**：IRI后肾脏中ROS持续产生作为病理启动信号

2. **AMPK作为红氧传感器**：巨噬细胞AMPKα1被ROS以钙依赖性方式激活

3. **促纤维化细胞对话**：激活的巨噬细胞通过TWEAK-Fn14-PDGFB轴与肾小管上皮细胞对话

4. **干预有效性验证**：AMPKα1基因敲除和TWEAK中和均可有效减轻纤维化

## 2. 临床转化价值

**潜在临床应用**:
- TWEAK作为预后生物标志物
- TWEAK中和抗体作为治疗策略
- 针对AMPK的干预策略开发

## 3. 研究展望

**未来研究方向**:
- 深入解析AMPK下游效应分子
- 探索AMPK在人类肾脏疾病中的作用
- 开发特异性的干预药物
- 临床试验验证干预策略的有效性

---

# 附录：关键词汇解释

| 词汇 | 解释 |
|------|------|
| IRI | Ischemia-Reperfusion Injury，缺血-再灌注损伤 |
| AKI | Acute Kidney Injury，急性肾损伤 |
| CKD | Chronic Kidney Disease，慢性肾脏疾病 |
| ROS | Reactive Oxygen Species，活性氧 |
| AMPK | AMP-Activated Protein Kinase，AMP激活蛋白激酶 |
| TEC | Tubular Epithelial Cell，肾小管上皮细胞 |
| TWEAK | TNF-like weak inducer of apoptosis |
| Fn14 | TNFRSF12A，TNF受体超家族成员12A |
| PDGFB | Platelet-Derived Growth Factor B，血小板衍生生长因子B |
| VCAM1 | Vascular Cell Adhesion Molecule 1，血管细胞粘附分子1 |
| Arg1 | Arginase 1，精氨酸酶1 |
| MMP12 | Matrix Metalloproteinase 12，基质金属蛋白酶12 |

---

*报告生成日期：2026-04-05*
*数据来源：PubMed EFetch (PMID: 41621245)*
