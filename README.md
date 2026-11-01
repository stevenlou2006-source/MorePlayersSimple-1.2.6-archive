> 🔗 仓库地址（Repository）：https://github.com/stevenlou2006-source/MorePlayersSimple-1.2.6-archive

# More Players Simple / 更多玩家精简版

突破 REPO 公共房间默认 6 人联机上限，支持 **1–20 人**自定义（私人房间默认 6，可调到 10）。

｜ 编译于 **Unity 6（6000.3.17f1）** ｜ **仅支持 2026-10-29 之后的游戏版本**
（旧版游戏请用 v1.2.3；1.2.6 及更早为 GPL-3.0 源码归档）

---

## 📜 版权声明与使用条款（完整版）

> Copyright (C) 2026 cn_xc. All rights reserved. / 版权所有，保留一切权利。
> 本声明同时适用于本项目的**源代码、二进制文件、文档、字符串资源与美术资源**。

### 一、作品来源

本项目**并非衍生作品**，与《LateJoinNow》等其它模组**没有任何代码或授权关系**：

- **本作品**：**MorePlayersSimple（更多玩家精简版）**，由 **cn_xc** 独立开发与维护。
- 所使用的第三方组件仅为运行所需的基础库（**BepInEx**、**Harmony**、Photon 相关库），
  均按其各自的许可证使用，不改变本作品自身的著作权归属。
- 本声明的范围覆盖**本项目的全部成果**（代码、二进制、文档、字符串、图标等）。

### 二、授权范围（按版本区分）

| 版本 | 许可证 | 授权内容 |
|---|---|---|
| **1.2.6 及更早** | **GNU GPL-3.0**（源码见归档仓库 `MorePlayersSimple-1.2.6-archive`） | 依 GPL-3.0 条款使用、修改与分发 |
| **1.2.7 及之后** | **闭源**（不提供源代码） | 仅授权在 **R.E.P.O.（REPO）游戏内以未经修改的形式运行** |

Licence granted for 1.2.7+: a limited, non-exclusive, non-transferable licence to
run this work, **unmodified**, inside the game "R.E.P.O." only.

### 三、注明出处

**① 闭源版本（1.2.7 及之后）**

> ⚠️ 分发、整合、引用、介绍时**必须**在显著位置注明作者与出处：
> - 必须保留 **作者署名（cn_xc）**；
> - 必须写明出处（Thunderstore 页面或 GitHub 仓库地址）；
> - **移除、遮盖、篡改版权标识或作者信息，均视为违反本授权。**

**② GPL 版本（1.2.6 及更早）**

本项目 **1.2.6 及其之前的各个版本**均以 **GNU GPL-3.0** 授权发布；该授权**不因作者此后变更条款而失效**（被许可人违约时依 **GPL-3.0 第 8 条**可终止），使用者享有以下权利：

1. **运行** —— 可用于任何目的（含商业用途）；
2. **修改** —— 可自由修改、改编；
3. **分发** —— **可以再分发，但必须同样以 GPL-3.0 发布衍生作品**
   （即：修改后的版本也必须开源，并附带完整 GPL-3.0 条款）；
4. **获取源码** —— 获得二进制者有权获取对应源码
   （本仓库即为其源码来源：`MorePlayersSimple-1.2.6-archive`）。

分发时须保留**版权声明与 GPL-3.0 许可文本**（GPL-3.0 §5）；除此之外，本条款**不额外附加任何限制**。

### 四、未经许可明确禁止（1.2.7 及之后）

1. **反编译、反汇编、逆向工程、脱壳、内存转储**，或以任何方式**提取实现逻辑**；
2. **复制、改编、翻译、演绎**，或基于本作品创作衍生作品（含“换皮改名”后发布）；
3. **二次打包、重新分发、上架第三方平台**，或用于任何**商业用途**（含付费整合、付费代装）；
4. 移除或篡改版权标识、作者署名与本条款；
5. 通过反射、钩子、补丁等方式调用本作品内部实现，用于构建替代品或商业产品。

### 五、人工智能（AI）相关限制（仅适用于 1.2.7 及之后）—— 重要

以下限制**仅适用于 1.2.7 及之后的闭源版本**；1.2.6 及更早的 GPL 版本以其 GPL 授权为准。

未经作者**书面许可**，明确禁止下列**人工智能相关**行为：

1. **训练用途**：禁止将本项目的源代码、字符串、文档、注释或任何部分，
   用于**训练、微调、蒸馏、评测**任何机器学习模型（含大语言模型、代码生成模型，
   以及以此构建的数据集），无论该行为发生在本地、私有集群还是云端服务。
2. **生成式还原**：禁止将本项目的内容输入 AI 工具（对话模型、代码助手、Agent 等），
   用以**生成功能等价的实现**，再以“原创”名义发布、分发或用于任何产品。
3. **AI 批量“换皮”**：禁止借助 AI 改写、重命名、重构本项目的实现后发布，
   该行为本质上仍是对本作品的复制与改编。
4. **规避授权**：禁止通过“让 AI 代为阅读/提取/改写”的方式，
   绕过本条款对反编译与复制改编的限制。
5. **声明**：AI 生成物**不改变**本作品的著作权归属，**不构成独立创作**；
   由 AI 辅助产生的、与本作品实质相似的成果，同样受本条款约束。

> 说明：使用 AI 工具**阅读公开文档、撰写评测、翻译说明文字**不受限制；
> 上述限制针对的是**代码与实现层面的提取、再现与再发布**。

### 六、反规避与身份保护

1. 禁止绕过、破坏或规避本作品的任何授权校验、标识或技术措施
   （依 **WCT 第 11 条**及各缔约国国内法，规避有效技术措施本身即可被追究）；
2. 禁止以他人名义发布本作品，或伪称获得作者授权、官方合作、官方发行；
3. 禁止发布经修改的版本却**沿用本项目名称、图标或作者署名**，造成来源混淆。

### 七、需要另行申请授权的情形

- 查看 **1.2.7 及之后版本**的代码细节或进行代码审查；
- 将本模组加入**整合包（modpack）**，或以任何非“原样运行”的方式使用；
- 任何形式的**商业用途**（含直播平台付费内容、代装服务、付费整合）。

如需以上授权，请**联系作者申请**；**获准后仍须标明出处**

### 八、条款变更、可分性与准据法

1. 作者**保留随时更新本条款的权利**；更新后的条款自发布之日起适用于**新版本**，
   已发布版本的授权不因条款更新而回溯改变。
2. 本条款任一条款被认定无效或不可执行，**不影响其余条款的效力**。
3. 本条款的解释与争议适用**中华人民共和国法律**   **伯尔尼保护文学和艺术作品公约**。
 
### 九、免责声明

本模组按“现状”提供，不附带任何明示或暗示的担保（含适销性、特定用途适用性）。
因使用或无法使用本模组导致的任何损失（含存档损坏、联机异常、游戏崩溃、数据丢失等），
**作者不承担责任**。请在了解风险的前提下自行决定是否使用。

### 十、法律依据与后果

**（一）自动保护与保护期限**
本作品自创作完成之日起**自动**受版权保护，无需登记或任何手续。
作为计算机程序，依中国《著作权法》：
**自然人作品**的保护期为**作者终生加死后 50 年**；
**法人或非法人组织作品**的保护期为**首次发表后 50 年**
（未发表的不予保护）。其他国家的保护期以其国内法为准。

**（二）国际条约**（对各条约**缔约方**有效；中国、美国、欧盟均为缔约方）

1. **《伯尔尼保护文学和艺术作品公约》**（Berne Convention）
   - **国民待遇**：作为缔约方国民，本作品在其他缔约方享有与当地国民同等的保护。
   - **专有权利**：复制权、发行权、公开传播权等；未经许可复制或分发即构成侵权。
   - 说明：伯尔尼公约 1971 年巴黎文本**未直接列出计算机程序**；
     “计算机程序按文字作品保护”这一规则是由 **WCT 第 4 条**
     （伯尔尼公约的特别协议）与 **TRIPS 第 10 条第 1 款**予以明确的。

2. **《与贸易有关的知识产权协定》**（TRIPS，WTO 框架）
   - 对全部 **WTO 成员**具约束力，设定**最低保护标准**，
     并可通过 **WTO 争端解决机制**保障执行（该机制为**国家间**程序；
     平台责任与跨境内容处置由**各成员国内法**规定）。
   - 再次确认计算机程序按《伯尔尼公约》作为文字作品保护。
   - **表达与思想的界限（第 9 条第 2 款）**：版权保护的是**代码的表达**，
     不保护思想、程序、操作方法或数学概念本身 —— 他人可以学习设计思路，
     但**不得复制代码的表达**。
   - 要求成员建立**有效执法程序**，权利人可据此制止侵权。

3. **《世界知识产权组织版权条约》**（WCT）
   - 明确计算机程序（含 **DLL 等目标代码形态**）作为《伯尔尼公约》第 2 条项下的
     文字作品受保护，**不论其表达方式或形式**。
   - **发行权**：授权通过销售或转让方式向公众提供作品复制品。
   - **向公众传播权**：授权以有线或无线方式向公众传播作品
     （含通过互联网提供，使公众可在其选定的地点和时间获取）。
   - **技术措施保护（第 11 条）**：缔约方须立法禁止规避权利人为保护作品
     而使用的**有效技术措施**；各法域通常设有法定例外
     （如互操作性、安全研究、加密研究），具体适用**以该国国内法为准**。

4. **欧盟《计算机程序保护指令》**（2009/24/EC）
   - 在欧盟境内将软件作为文学作品保护，禁止未经授权的复制与发行；
     其第 6 条允许“为互操作性”的有限反编译，本条款不排除该法定情形。

**（三）国内法**
《中华人民共和国著作权法》《计算机软件保护条例》，
以及《中华人民共和国刑法》第二百一十七条（侵犯著作权罪）。
其中**技术措施**相关保护见《著作权法》相关规定（2020 年修订；**具体条号以现行法为准**）。

**（四）如何适用**
⚠️ 上述条约通过各**缔约国国内法**实施；**实际维权以该国国内法及法院管辖为准**。
本声明引用条约，用于说明本作品在国际层面的保护依据。

**（五）后果**
对上述禁止行为的实施者，**作者 cn_xc** 有权依据
《中华人民共和国著作权法》《计算机软件保护条例》
要求**停止侵害、消除影响、赔偿损失**；情节严重、以营利为目的的，
可能承担刑事责任。

> **说明**：本条款旨在明确作者的授权边界，**不排除法律强制赋予的权利**。
> 例如：《计算机软件保护条例》**第十七条**规定——“为了学习和研究软件内含的设计思想和原理，
> 通过安装、显示、传输或者存储等方式**使用**软件的，可以不经软件著作权人许可，
> 不向其支付报酬”（该条针对的是**使用**行为，复制、发行等仍受限制）；
> 欧盟 **2009/24/EC 第 6 条**允许“为互操作性”的有限反编译。
> 对本项目 **1.2.6 及其之前的各个版本**（均以 **GPL-3.0** 授权发布）：
> 其授权**不因作者此后变更条款而失效**；但被许可人违反 GPL-3.0 时，
> 授权可依 **GPL-3.0 第 8 条**终止。本条款中的禁止性规定不适用于这些版本。

---

## 📜 English Version (full)

> Copyright (C) 2026 cn_xc. All rights reserved.

### 1. Origin

This project is **NOT a derivative work** and has **no code or licensing
relationship** with *LateJoinNow* or other mods. It is independently developed and
maintained by **cn_xc**. Third-party components are only the runtime base
libraries (BepInEx, Harmony, Photon libraries), each under its own licence.

### 2. Licence granted (by version)

| Version | Licence | Granted |
|---|---|---|
| **1.2.6 and earlier** | **GNU GPL-3.0** (source: archive repository) | Use, modify, distribute under GPL-3.0 |
| **1.2.7 and later** | **Closed source** | Run **unmodified** inside "R.E.P.O." only |

### 3. Attribution

**Closed-source versions (1.2.7+):** you **must** credit the author (**cn_xc**) and
the source wherever the work is distributed, integrated or referenced. Removing,
obscuring or altering copyright notices or author information is a licence violation.

**GPL versions (1.2.6 and earlier):** keep the copyright and licence notices as
required by **GPL-3.0 §5** — this notice adds no further restrictions. Crediting the
source is strongly requested, but not required.

### 4. Prohibited without prior written permission (1.2.7+)

Decompiling / disassembling / reverse engineering / unpacking / memory dumping or
extracting the implementation; copying, adapting, translating or creating
derivative works (including renamed "reskins"); repacking, redistributing,
publishing on third-party platforms or any commercial use; removing or altering
this notice; calling internal implementations via reflection/hooks/patching to
build substitutes or commercial products.

### 5. Artificial intelligence restrictions (1.2.7 and later only) — important

These restrictions apply **only to 1.2.7 and later (closed source)**; versions 1.2.6
and earlier are governed solely by the GPL.

Without prior written permission you may **NOT**:

1. use any part of this project (source, strings, docs, comments) to **train,
   fine-tune, distil or benchmark** any machine-learning model, including LLMs and
   code-generation models, or to build datasets for that purpose;
2. feed this project into AI tools to **generate functionally equivalent
   implementations** and then publish or distribute them as "original" work;
3. use AI to rewrite, rename or restructure this project's implementation and
   publish the result — this remains copying and adaptation;
4. circumvent these terms by having an AI read, extract or rewrite the work.

AI-generated output **does not change** the authorship of this work and does **not**
constitute independent creation. Using AI to **read public documentation, write
reviews or translate descriptions** is not restricted; the restrictions target
extraction, reproduction and redistribution at the code level.

### 6. Anti-circumvention

No bypassing licence checks or technical measures; no publishing under another
name or falsely claiming authorisation, partnership or official release; no
releasing modified versions under this project's name, icon or author credit.

### 7. Separate permission required

Reviewing 1.2.7+ code details; including this mod in a modpack; any commercial use.
Contact the author; if granted, credit the source, and the permission covers only
what was granted in writing.

### 8. Changes, severability, governing law

The author may update these terms at any time; updates apply to new versions only.
Invalidity of one clause does not affect the others. These terms are governed by
the laws of the People's Republic of China.

### 9. Disclaimer

Provided "as is" without warranty of any kind. The author is not liable for any
loss arising from use of, or inability to use, this mod.

### 10. Legal basis and consequences

**(a) Automatic protection and term** — protected from the moment of creation, with
no formality required. Under the PRC Copyright Law: for a **natural person** the term
is the author's life plus **50 years**; for a **work of a legal person** it is **50
years from first publication**. Other jurisdictions apply their own terms.

**(b) International treaties** (binding on the **parties** to each treaty; China,
the United States and the EU are parties)

1. **Berne Convention** — national treatment; exclusive rights of reproduction,
   distribution and communication to the public. Note: the 1971 Paris Act does **not**
   itself mention computer programs; the rule that programs are protected as
   **literary works** is set out in **WCT Article 4** (a special agreement under
   Berne) and **TRIPS Article 10(1)**.
2. **TRIPS Agreement (WTO)** — minimum standards binding on all WTO members,
   enforceable through the **WTO dispute settlement mechanism** (an
   **inter-State** process; platform liability and cross-border content handling are
   governed by **domestic law**). **Article 9(2)**: copyright protects
   **expression, not ideas**, procedures, methods or mathematical concepts.
3. **WIPO Copyright Treaty (WCT)** — programs, **including DLL/object-code form**,
   are literary works under Berne Art. 2. Grants a **right of distribution** and a
   **right of communication to the public** (including online). **Article 11**
   requires parties to prohibit circumvention of **effective technological
   measures**; most jurisdictions provide statutory exceptions (interoperability,
   security research, cryptography research) — applicability is **governed by
   domestic law**.
4. **EU Directive 2009/24/EC** — software protected as a literary work in the EU;
   Article 6 permits limited decompilation for interoperability, which this notice
   does not exclude.

**(c) Domestic law** — Copyright Law of the PRC, Regulations on Computer Software
Protection, Article 217 of the Criminal Law of the PRC. Technological-measure
protection is addressed in the Copyright Law (as amended in 2020; **check the
current article numbering**).

**(d) How this applies** — These treaties are implemented through **domestic law**;
**enforcement is governed by the law and courts of the relevant jurisdiction**.

**(e) Consequences** — injunctive relief, removal of infringing copies and damages;
wilful commercial infringement may carry criminal liability.

> **Note**: this notice does not exclude rights granted by mandatory law — e.g.
> **Article 17 of the Regulations on Computer Software Protection of the PRC**
> permits **using** a program (by installing, displaying, transmitting or storing)
> to study its ideas, without the rightsholder's permission; copying and
> distribution remain restricted. **EU Directive 2009/24/EC, Article 6** permits
> limited decompilation for interoperability. For **versions 1.2.6 and earlier**
> (released under **GPL-3.0**), the grant is **not** withdrawn by later changes to
> these terms, but it **may be terminated under GPL-3.0 §8** if a licensee breaches
> the licence. The prohibitions above do not apply to those versions.

---

## ⚠️ 关于私人房间（默认 6 人，最高可调到 10）

私人房间的上限**默认仍是 6 人**（配置项 `私人房人数上限`，游戏原版值），但**可自行调到 1~10**，
但**不保证第 6 人之后可以稳定加入**。原因如下：

- 游戏原版的私人房上限是 **6 人**，超过 6 人后，一部分原版流程
  （队伍槽位、房间列表人数显示、加入校验）仍按 6 人的逻辑处理；
- 因此可能出现「能看到大厅但进不去」「加入被拒」或「人数显示不对」等情况；
- 这是游戏本身的限制，不是本模组能完全绕开的。

**如果你需要一个稳定的大房间，建议：**

1. 使用**公开房**（上限 20 人），本模组对公开房的支持最完整；
2. 私人房建议仍控制在 **6 人以内**，超过时请自行测试确认可用性。

## 🎧 关于多人语音（重要）

本模组会把**语音房间**的人数上限一并提高到和主房间相同（公开 20 / 私人 10），
但**游戏自身的语音混音逻辑是按 6 人设计的**，人数越多越容易出现以下情况：

- 部分玩家**听不到**某个人说话，或只有单向能听见；
- 音量忽大忽小、串音、回声；
- 个别玩家掉线重连后语音不再恢复。

**这些属于游戏语音系统的承载限制，不是本模组能完全解决的。**

### 建议

| 场景 | 建议 |
|---|---|
| 主要靠游戏内语音沟通 | 控制在 **6~8 人**，超过时体验会明显变差 |
| 人数较多（10~20 人）| 改用 **Discord / KOOK / YY** 等外部语音，游戏内语音可关闭 |
| 语音异常排查 | 让对方**退出重进**一次，通常可恢复；仍不行则减少人数 |

> 我们没有做「限制语音人数」的功能：如果语音房间上限比主房间小，
> 超出的玩家会出现「能进游戏但没声音」，反而更难排查，所以选择如实说明。


## 🆕 本版（1.2.7）更新要点

### 许可变更
- **自 1.2.7 起，本模组改为闭源发布**（不再提供源代码）。
  仅授权在 R.E.P.O. 中以**未经修改**的形式运行；禁止反编译、复制改编、
  二次打包与重新分发、商业使用。
- 需要**查看代码细节**或**加入整合包**，请先联系作者申请授权，获准后请**标明出处**。
- **闭源版本（1.2.7+）必须注明作者（cn_xc）与出处**；GPL 版本（1.2.6−）依 GPL-3.0 保留版权声明即可（不额外附加限制）。
- 1.2.6 及更早版本仍为 GNU GPL-3.0，源码见归档仓库：
  `https://github.com/stevenlou2006-source/MorePlayersSimple-1.2.6-archive`

1. **修复新版游戏下「Steam 大厅人数上限」设置失效**：
   新版 Facepunch 把 `Lobby.MaxMembers` 从字段改成了属性，旧写法取不到 → 设置被静默跳过。
   现已改为三级回退（属性 → 字段 → `SetLobbyMemberLimit`），并在日志里写明用了哪条：
   `[MorePlayers] Steam 大厅人数上限已设为 20（属性 MaxMembers）`
2. **私人房间上限可调范围放宽到 1~10（默认仍是 6 = 游戏原版）**。想开更多人请自行把 `MaxPlayersPrivate` 调到 10；⚠️ **不保证第 6 人之后能稳定加入**，
   原因见下面的「关于私人房间」一节。
3. **README 新增「关于多人语音」说明**：语音上限会跟随房间上限，但游戏混音按 6 人设计，
   人多时容易听不到 / 音量异常（详见下文）。

---

> ⚠️ **兼容性说明**：本版本使用 **Unity 6（6000.3.17f1）** 的游戏程序集编译，
> **仅支持 2026-10-29 之后的游戏版本**。若你的游戏仍是 Unity 2022 版本，请使用更早的模组版本（v1.2.3）。

## ⚠️ 重要说明

### 本模组本身不提供中途加入功能。如需中途加入，推荐搭配 [LateJoinSimple](https://thunderstore.io/c/repo/p/cn_xc/LateJoinSimple/)（本作者维护的版本，基于 Zichen 的 LateJoinNow 修复）。

> 注意：**LateJoinNow 与 LateJoinSimple 不能同时安装** —— 两者 GUID 与房间属性键都不同，同装会出现重复 RPC 与缓存清理，导致卡加载 / 地图异常。

## ⚠️ 已知冲突
与以下模组同时使用可能导致人数上限失效，建议二选一：
- **EmpressLateJoin** 及其它修改房间加入逻辑的模组
- **LateJoinPlus / RepoLateJoin**：它们自带人数上限功能，会与本模组互相覆盖（双方都不一定提示），请只保留一边生效
- 说明：本作者的 [LateJoinSimple](https://thunderstore.io/c/repo/p/cn_xc/LateJoinSimple/) 不含人数上限功能，可放心一起用


## ✨ 功能
- 公开房间最大玩家数可自定义（1-20，默认 20）
- 私人房间最大玩家数可自定义（1-10，默认 6 = 原版；可自行调到 10）
- 仅修改房间最大玩家数，不影响游戏玩法、平衡或任何其他机制

## 安装
- 确保已安装 [BepInExPack](https://thunderstore.io/c/repo/p/BepInEx/BepInExPack/)
- 将 `MorePlayersSimple.dll` 放入 `BepInEx/plugins` 文件夹
- 启动游戏，模组会自动生成配置文件

## ⚙️ 配置
配置文件位置：`BepInEx/config/dyxc666.MorePlayersSimple.cfg`

**本版配置项名称已全部改为中文**（节名：`[常规]`）：

| 配置项 | 默认值 | 范围 | 说明 |
|---|---|---|---|
| 公开房人数上限 | 20 | 1-20 | 公开房间最大玩家数 |
| 私人房人数上限 | 6 | 1-10 | 私人房间最大玩家数（默认 6 = 游戏原版，可调到 10）|

> ⚠️ 键名从英文改成中文后，旧的 cfg 里的英文键会被忽略（设置回到默认值）。
> 如需保留原设置，手动把旧键名对应改成中文键名，或删除 cfg 让游戏重新生成。

## ❓ 常见问题

**Q：为什么我设了 20 人，别人还是进不来？**
A：请确认你是房主，并且是在创建新房间时生效。加入别人的房间时，上限由房主决定。

**Q：支持中途修改吗？**
A：不支持。房间创建后上限无法更改，需重新开房。

## 问题交流
QQ群：573485890
