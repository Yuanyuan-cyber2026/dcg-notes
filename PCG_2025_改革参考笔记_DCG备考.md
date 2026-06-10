# PCG 2025 改革参考笔记（DCG备考用）

> **用途：** 做DCG真题时，遇到涉及改革变动的科目或规则，Claude应参考本文件调整答案。
>
> **生效日期：** 2025年1月1日起（适用于2025年1月1日及之后开始的会计年度）
>
> **法规依据：** Règlement ANC n° 2022-06 du 4 novembre 2022，修改 Règlement ANC n° 2014-03

---

## 一、未受影响的科目（与公司设立相关）

以下科目在新旧PCG中**编号和名称完全一致**，无需调整：

| 科目编号 | 名称 | 状态 |
|---|---|---|
| 1011 | Capital souscrit – non appelé | ✅ 不变 |
| 1012 | Capital souscrit – appelé, non versé | ✅ 不变 |
| 1013 | Capital souscrit – appelé, versé | ✅ 不变 |
| 109 | Actionnaires : capital souscrit – non appelé | ✅ 不变 |
| 1041 | Primes d'émission | ✅ 不变 |
| 1042 | Primes de fusion | ✅ 不变 |
| 1043 | Primes d'apport | ✅ 不变 |
| 211 | Terrains | ✅ 不变 |
| 261 | Titres de participation | ✅ 不变 |
| 467 | Divers comptes débiteurs et produits à recevoir（2025改名） | ✅ 编号不变，名称微调 |
| 512 | Banques | ✅ 不变 |

---

## 二、主要变动（2025年起）

### 2.1 资产处置科目重新分类（影响重大）

**旧规则（2024及以前）：** 固定资产处置归入特殊损益（67x/77x）
- 675 Valeurs comptables des éléments d'actif cédés（已售资产账面价值）
- 775 Produits des cessions d'éléments d'actif（资产处置收入）

**新规则（2025起）：** 拆分为经常损益和金融损益

| 旧科目 | 新科目 | 新名称 | 分类 |
|---|---|---|---|
| 675（非金融资产部分） | **657** | Valeurs comptables des immob. incorporelles et corporelles cédées | 经常损益（65x） |
| 675（金融资产部分） | **6671** | Valeurs comptables des immobilisations financières cédées | 金融损益（66x） |
| 775（非金融资产部分） | **757** | Produits des cessions d'immob. incorporelles et corporelles | 经常损益（75x） |
| 775（金融资产部分） | **7671** | Produits des cessions d'immobilisations financières | 金融损益（76x） |
| 671 | **删除** | 仅保留672和678 | — |
| 771 | **删除** | 仅保留772和778 | — |

### 2.2 删除"费用转移"科目（Suppression des transferts de charges）

| 旧科目 | 旧名称 | 新处理方式 |
|---|---|---|
| 791 | Transferts de charges d'exploitation | **删除** |
| 796 | Transferts de charges financières | **删除** |
| 797 | Transferts de charges exceptionnelles | **删除** |

替代方案示例：
- 社保报销（remboursements de charges sociales）→ 贷记 **649**
- 人员借调收入（mise à disposition de personnel）→ 贷记 **7084**
- 保险赔偿（indemnités d'assurance）→ 贷记 **7587**
- 附属活动收入（produits des activités annexes）→ 贷记 **706**

### 2.3 重新定义"特殊损益"（Résultat exceptionnel）

**旧规则：** 特殊损益范围较宽泛

**新规则：** 仅限以下三类：
1. 与重大且非经常性事件直接相关的收支（événement majeur et inhabituel）——如出售不动产、重大诉讼、自然灾害
2. 纯粹出于税务目的的会计分录（écritures d'origine purement fiscale）——如税务加速折旧
3. 未直接冲减权益的前期差错更正（corrections d'erreurs）

### 2.4 科目总数精简

- 旧PCG：约2 000个科目
- 新PCG：约1 600个科目（削减约20%）
- 新增区分：**强制科目**（comptes obligatoires）vs **可选科目**（comptes facultatifs），在官方文件中分别以正体和斜体标注

### 2.5 财务报表格式变化

- 资产负债表（bilan）：统一采用**表格形式**（présentation en tableau）
- 利润表（compte de résultat）：统一采用**列表形式**（présentation en liste）
- 附注（annexe）：新增标准化表格（tableaux normés），分为强制类和参考类

### 2.6 溢价科目小改

| 旧名称 | 新名称 |
|---|---|
| 104 Primes liées au capital **social** | 104 Primes liées au capital（去掉了"social"） |

---

## 二bis、2026年版更新（Version au 1er Janvier 2026）

### 第16类（借款与债务）重新分类

2026版对第16类科目进行了结构性调整，将"不可偿还资金"和"有条件预付款"单独归类：

| 科目 | 2025版 | 2026版 |
|---|---|---|
| 16（总标题） | Emprunts et dettes assimilées | Emprunts et dettes assimilées, **fonds non remboursables et avances conditionnées** |
| 161/162/163/164 | 原名 | 加限定语 "si non-inscrits dans le compte 167" |
| 167 | Emprunts et dettes assortis de conditions particulières | **Fonds non remboursables et avances conditionnées**（完全重构） |
| 1671 | Émissions de titres participatifs | **Fonds non remboursables montant principal** |
| 16711 | 不存在 | **新增** Titres participatifs montant principal |
| 16712 | 不存在 | **新增** Autres fonds non remboursables montant principal |
| 1673 | 不存在 | **新增** Avances conditionnées montant principal |
| 1674 | Avances conditionnées de l'État | **改为** Avances conditionnées intérêts courus |
| 1675 | Emprunts participatifs | **删除**，移至1682 |
| 1682 | 不存在 | **新增** Emprunts participatifs |
| 1045 | Bons de souscription d'actions | Bons de souscription **de titres en capital**（改名） |

**核心变化：** 167科目从"附条件借款"变为"不可偿还资金与有条件预付款"的专用科目，对应资产负债表新增的"其他权益（autres fonds propres）"栏目。

---

## 三、对DCG做题的影响

| 题目背景年份 | 应使用的PCG版本 |
|---|---|
| 2024年及以前 | 旧PCG |
| 2025年 | PCG 2025 |
| 2026年及以后 | PCG 2026（含167重分类） |

**实务影响总结：**
- 公司设立（constitution）、增资（augmentation de capital）、减资（réduction de capital）的分录 → **不受影响**
- 涉及费用转移（791/796/797）的题目 → **需按新规则调整**（2025起）
- 涉及特殊损益分类的题目 → **需按新定义判断**（2025起）
- 涉及资产处置（675/775）的题目 → **需改用657/757**（2025起）
- 涉及借款与债券（16x）的题目 → **需注意167重分类**（2026起）
- 财务报表编制题 → **需注意新格式要求**（2025起）

---

## 四、官方来源（供核实）

1. **ANC官方新版科目表（PDF）：**
   https://www.anc.gouv.fr/files/anc/files/1_Normes_fran%C3%A7aises/Plans%20comptables/Plan-de-comptes-PCG-2025.pdf

2. **新旧科目对照表（EBP发布）：**
   https://infos.ebp.com/hubfs/pdf/Fiches-Nouveautes/Tableau_comparatif_des_nomenclatures_de_comptes_2025.pdf

3. **PCG 2025教学指南及对照表（Groupe FIBA）：**
   https://www.groupe-fiba.fr/wp-content/uploads/2025/02/Guide-PCG-2025-et-tableau-de-correspondance-PDC-compresse.pdf

4. **Pennylane改革概述：**
   https://www.pennylane.com/fr/fiches-pratiques/plan-comptable/reforme-du-plan-comptable-2025

5. **Sage改革分析：**
   https://www.sage.com/fr-fr/blog/pcg-plan-comptable-general-reforme-2025/

---

*最后更新：2026年6月*
*注意：本文件基于公开资料整理，请以ANC官方发布为准。*
