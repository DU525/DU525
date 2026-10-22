<div align="center">

<!-- 打字机动画标题 -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=7FDBFF&center=true&vCenter=true&random=false&width=760&lines=%E5%85%B7%E8%BA%AB%E6%99%BA%E8%83%BD%20%2F%20%E4%B8%96%E7%95%8C%E6%A8%A1%E5%9E%8B%20%E7%AE%97%E6%B3%95%E5%B7%A5%E7%A8%8B%E5%B8%88;%E8%AF%84%E6%B5%8B%E4%B8%8E%E5%9B%A0%E6%9E%9C%E5%BD%92%E5%9B%A0%20%E6%96%B9%E5%90%91;125%2B%20%E9%A2%84%E6%B3%A8%E5%86%8C%E5%AE%9E%E9%AA%8C%20%C2%B7%201000%E4%B8%87%E7%BA%A7%E7%9C%9F%E5%AE%9E%E4%BB%BF%E7%9C%9F%E4%BA%A4%E4%BA%92%E6%AD%A5;Sussex%20AI%20%C2%B7%20%E5%89%8D%205%25" alt="Typing SVG" />
</a>

<!-- 身份徽章 -->
<img src="https://img.shields.io/badge/Sussex_University-AI_%26_Adaptive_Systems-7FDBFF?style=for-the-badge&logo=github&logoColor=white" />
<img src="https://img.shields.io/badge/%E4%B8%93%E4%B8%9A%E6%8E%92%E5%90%8D-Top_5%25-FF6B6B?style=for-the-badge" />
<img src="https://img.shields.io/badge/%E6%B1%82%E8%81%8C-%E5%85%B7%E8%BA%AB%E6%99%BA%E8%83%BD%20%2F%20%E4%B8%96%E7%95%8C%E6%A8%A1%E5%9E%8B%20%E7%AE%97%E6%B3%95-2ECC40?style=for-the-badge" />

<!-- 访问计数 -->
<img src="https://komarev.com/ghpvc/?username=DU525&label=Profile+Visitors&color=7FDBFF&style=flat-square" alt="Profile Views" />

---

</div>

<!-- 关于我 -->
## 🔍 关于我

- 🎓 硕士就读于英国萨塞克斯大学，专业排名前 **5%**，师从 Fernando Rosas 教授
- 🧪 硕士论文与 Cambridge (Andrea Luppi) / Imperial (Pedro Mediano) 合作，用 **PID / ΦID 信息论框架**度量并归因世界模型中的潜在协同性
- 🔬 关心的问题不是"模型看起来像不像"，而是**"它到底带来了多少可测量的价值，以及价值丢在哪一环"**
- 💼 求职方向：具身智能 / 世界模型 **算法工程师（评测与因果归因方向）**

<!-- 研究方向 -->
## 🧭 研究方向

| 方向 | 我在做什么 | 证据 |
|------|-----------|------|
| **世界模型评测** | 把"成功率"拆成 *机会* 与 *排序损失*：同一物理状态分叉执行多个候选首动作，判断瓶颈在候选集覆盖还是模型排序 | `paired-counterfactual-eval`（开源工具） |
| **信息论归因** | 用 PID / ΦID 分解潜在状态的协同、冗余、独有信息；四架构消融验证门控序列结构对协同性的影响 | 硕士论文工作（Sussex × Cambridge × Imperial） |
| **工程化落地** | 让评测本身可信：原子写盘 + SHA256 清单 + 单次提交点、步数预算前置计量、预注册配置哈希 | 125+ 预注册实验，629 万行 OOF 预测重放误差 0 |

<!-- 精选项目 -->
## 🚀 精选项目

<div align="center">

<table>
<tr>
<td width="100%" align="center">

### 🧪 paired-counterfactual-eval
**世界模型配对反事实评测**

<img src="https://img.shields.io/badge/python-3.9%2B-7FDBFF?style=flat-square" />
<img src="https://img.shields.io/badge/License-MIT-2ECC40?style=flat-square" />
<img src="https://img.shields.io/badge/CI-passing-2ECC40?style=flat-square" />
<img src="https://img.shields.io/badge/tests-28-FF6B6B?style=flat-square" />

*"价值增益 = 机会 − 排序损失"——把一句判断拆成可以分别归因的两项*

> 同一状态分叉执行多个候选首动作 · origin-cluster bootstrap 置信区间 · 崩溃安全产物包 + 离线校验 · 确定性 toy 环境覆盖三种判决

**🔗 [查看项目 →](https://github.com/DU525/paired-counterfactual-eval)**

</td>
</tr>
<tr>
<td width="50%" align="center">

### 🛡️ AegisRAG
**透明检索增强问答引擎**

<img src="https://img.shields.io/badge/RAGAS_Faithfulness-0.90-2ECC40?style=flat-square" />
<img src="https://img.shields.io/badge/recall%405-92%25-7FDBFF?style=flat-square" />
<img src="https://img.shields.io/badge/QPS-5%2C100-FF6B6B?style=flat-square" />

*"Aegis"（神盾）— 引用溯源防幻觉，检索过程全透明*

> 用 RAGAS 指标替代直觉决策 · 12万+条规则数据

**🔗 [查看项目 →](https://github.com/DU525/ocg-rulebook-qa)**

</td>
<td width="50%" align="center">

### 🔨 DreamForge
**AI 视频锻造工坊**

<img src="https://img.shields.io/badge/AI_Pipeline-%E5%AE%9A%E5%A6%86%E2%86%92%E9%A2%84%E8%A7%88%E2%86%92%E8%A7%86%E9%A2%91-7FDBFF?style=flat-square" />
<img src="https://img.shields.io/badge/%E8%BF%90%E9%95%9C%E6%A8%A1%E6%9D%BF-10%E7%A7%8D-2ECC40?style=flat-square" />
<img src="https://img.shields.io/badge/%E9%94%99%E8%AF%AF%E5%BD%92%E5%9B%A0-4%E7%B1%BB-FF6B6B?style=flat-square" />

*"DreamForge"（梦工厂）— 从 Prompt 到成片的完整锻造链路*

> 双 Provider 抽象层 · 预览确认降低试错成本

**🔗 [查看项目 →](https://github.com/DU525/dreamforge-ai-video)**

</td>
</tr>
</table>

</div>

---

### 🧪 paired-counterfactual-eval — 为什么做这个

具身团队报"成功率"时，一个问题被漏掉了：**这是世界模型的功劳，还是策略本身的功劳？**

我把这个问题变成一个配对反事实实验：恢复**同一个完整物理状态**，把多个候选首动作分别真实执行一遍，再比较实际发生了什么。

| 量 | 定义 | 回答的问题 |
|---|---|---|
| **机会** `A` | `max Y(a_i) − Y(a_b)` | 更好的动作**存在过**吗 |
| **排序损失** `L` | `max Y(a_i) − Y(a_w)` | 模型**错过**了它吗 |
| **价值增益** `G` | `Y(a_w) − Y(a_b)` | 世界模型的**净**贡献 |

且恒有 `G = A − L`。这是代数恒等式，不是发现；它的用处是**诊断**：

- `A > 0` 且 `L > A` → **排序受限**：好动作存在但没被选中，该修排序而不是加大模型
- `A ≤ 0` → **覆盖受限**：没有候选优于基线，再训练也换不来增益
- 区间跨 0 → **inconclusive**：这就是结论，不是"没做出结论"

**工程约束**（负结果只有在管线不可作弊时才有意义）：分支必须成对恢复、崩溃的 run 不能看起来像跑完的 run（原子写 + 单次提交点）、产物带 SHA256 清单可离线复核、步数预算先计费后执行、协议配置先哈希后运行。

---

### 🛡️ AegisRAG — 性能数据

| 指标 | 数值 | 对比 |
|------|------|------|
| RAGAS Faithfulness | 0.90 | 超行业基准 0.80 |
| recall@5 | 92% | 超 FastGPT(90%) / Dify(88%) |
| QPS | 5,100 | Flask→FastAPI 异步升级 (+2,733%) |
| p99 延迟 | 45ms | Cross-Encoder 精排的精度-延迟 trade-off |
| 缓存命中率 | 85% | L1 内存 LRU + L2 Redis + L3 SimHash 语义缓存 |

**技术决策亮点**
- **多路检索融合**：向量检索 + BM25 关键词检索 + RRF 融合 + Cross-Encoder 精排，recall@5 从 78% 提升至 92%
- **检索溯源面板**：每条 AI 回复下方可折叠展示 Top-3 检索片段 + 各路得分，检索过程全透明
- **对话记忆侧栏**：短期工作记忆 + 长期事实记忆 + 遗忘曲线，用户可感知系统"记住了什么"
- **量化驱动优化**：用 RAGAS 4 项指标自动化评估替代直觉决策，每一步优化都有数据支撑
- **优雅降级设计**：Cross-Encoder / Redis / Whoosh 依赖缺失时自动降级，系统始终可用
- **生产级部署**：Docker Compose 一键启动 + K8s 清单 (HPA 自动扩缩) + Prometheus 4 级告警

---

### 🔨 DreamForge — 产品亮点

- **全栈架构**：FastAPI + WebSocket 实时进度推送 + React 18 双模式 UI + SQLAlchemy ORM
- **AI Pipeline 编排**：角色定妆图生成 → 预览确认 → 首帧注入 → 图生视频 → 轮询 → 下载，完整闭环
- **双 Provider 设计**：可灵 Kling (裸 HTTP + 自签 JWT) / 即梦 Jimeng (火山方舟 SDK)，抽象层统一接口
- **预览确认机制**：先生成角色定妆图供用户确认，避免"等 3 分钟发现不是想要的"，降低试错成本
- **智能错误归因**：4 类错误自动分类（超时/鉴权/内容审核/服务不可用），每类配人话建议 + 一键重试
- **10 种运镜模板**：静态/推/拉/摇/俯仰/跟随/环绕/升降/手持/航拍，点击即填充，降低 Prompt 门槛

---

### 📝 硕士论文 — 动作条件世界模型中潜在协同性的度量与归因
> Sussex × Cambridge × Imperial 合作 · PID / ΦID 框架下的信息论实验

- **核心发现**：世界模型训练后，随机潜在状态的极大对协同性显著降低；门控 / 选择性序列结构（Mamba）使该效应更强且更稳定
- **实验设计**：4 种序列核心（0-gate SSM → 1-gate Mamba-lite → 2-gate SSM → trueMamba）消融对比，四架构 Δz 均为负且跨 12/12、12/12、11/12、18/24 个种子成立
- **方法论价值**：为模型鲁棒性与可解释性提供信息论审计框架

<!-- 技术栈 -->
## 🛠️ 技术栈

<div align="center">

<img src="https://skillicons.dev/icons?i=py,pytorch,cpp,linux,docker,kubernetes,fastapi,react,ts,git,githubactions,bash&perline=12&theme=dark" alt="Skill Icons" />

</div>

| 领域 | 技术 |
|------|------|
| **世界模型 / 评测** | RSSM 系列 (DreamerV3) · 配对反事实评测 · 预注册协议 · origin-cluster bootstrap · 因果归因 (PID / ΦID) |
| **实验工程** | 崩溃安全产物包 (原子写/哈希清单/提交点) · 步数预算计量 · 可复现性与完整性审计 · MuJoCo / dm_control |
| **模型与加速** | PyTorch · TorchScript (p95 1.399→0.677 ms) · OOF 预测重放 (629 万行，误差 0) |
| **AI 工程化** | RAG 全链路 · BM25 + RRF 多路融合 · Cross-Encoder 精排 · RAGAS 量化评估 · LLM API 降级策略 |
| **后端 / 部署** | Python · FastAPI 异步架构 · WebSocket · SQLAlchemy · Docker Compose · Kubernetes (HPA) · Prometheus + Grafana |
| **前端** | TypeScript · React 18 · Vite · TailwindCSS · Zustand · Framer Motion |

<!-- GitHub 统计卡片 -->
<div align="center">

### 📊 GitHub 统计

<img height="165" src="https://github-readme-stats.vercel.app/api?username=DU525&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7FDBFF&icon_color=2ECC40&text_color=C9D1D9" alt="GitHub Stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DU525&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=7FDBFF&icon_color=2ECC40&text_color=C9D1D9" alt="Top Languages" />

<img width="680" src="https://github-readme-activity-graph.vercel.app/graph?username=DU525&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=7FDBFF&line=2ECC40&point=FF6B6B&area=true&custom_title=%F0%9F%93%88%20%E8%BF%91%E6%9C%9F%E6%B4%BB%E8%B7%83%E5%BA%A6" alt="Activity Graph" />

</div>

<!-- 联系方式 -->
## 📫 联系方式

<div align="center">

<a href="mailto:dujinbo007@163.com">
  <img src="https://img.shields.io/badge/Email-dujinbo007%40163.com-7FDBFF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<img src="https://img.shields.io/badge/Location-%E5%8D%97%E4%BA%AC%20%2F%20%E8%8B%B1%E5%9B%BD%20Brighton-2ECC40?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />

---

*"没有度量，你无法证明优化有效。世界模型也一样。"*

</div>
