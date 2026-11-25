# Contributing / 参与共建（真实截图 & 开关变更）

Thank you for helping keep **AI Privacy Switches** accurate, honest, and 3-second scannable!
感谢参与维护 **AI Privacy Switches**！本项目坚持 **“零假图、实拍核验、极简速查”** 原则。

---

## 📷 Most Wanted: Real UI Screenshots for Login-Walled Tools / 急缺实拍真图认领清单

We **never** use fake UI mockups. The following 7 closed-source / login-walled tools currently have verified click paths & configs, and need **genuine, redacted UI screenshots** via PR:

我们**绝不掺入伪造界面示意图**。以下 7 张卡片因设置页位于登录墙内，急需社区提供脱敏后的真实截图：

| Tool / 产品 | Needed Screen / 所需截图界面 | Target Filename / 建议文件名 |
| :--- | :--- | :--- |
| **Cursor** | `Cursor Settings → General → Privacy` (`Privacy Mode (Legacy)`) | `assets/screenshots/cursor-privacy.png` |
| **Windsurf / Devin** | `windsurf.com/settings → Privacy (ZDR)` or `app.devin.ai → Data Controls` | `assets/screenshots/windsurf-privacy.png` |
| **Notion AI** | `Settings → Notion AI` (`Share data to improve` & `Use memories`) | `assets/screenshots/notion-ai-privacy.png` |
| **Pi (`pi.ai` / `pi.dev`)** | `pi.ai Account Settings` opt-out or `pi.dev` CLI session screen | `assets/screenshots/pi-settings.png` |
| **Zhipu / ChatGLM / ZCode** | 智谱清言 `个人中心 → 数据管理`（关闭优化体验） | `assets/screenshots/chatglm-privacy.png` |
| **DeepSeek Web/App** | `设置 → 数据管理`（关闭 `Improve the model` / 数据用于优化体验） | `assets/screenshots/deepseek-data-controls.png` |
| **Perplexity / Manus / Poe** | Perplexity `Preferences → AI Data Retention` OFF | `assets/screenshots/perplexity-privacy.png` |

---

## 🛡️ Screenshot Redaction Checklist / 截图脱敏规范

Before submitting a PR with a screenshot, please ensure:
1. **Blur or crop out** personal email addresses, phone numbers, real names, API keys, organization IDs, and private repo names.
2. Prefer **PNG** format, width between `800px` and `1400px`, clear readable English or Chinese UI text.
3. Show the **exact target toggle** in its recommended privacy-hardened state (e.g., Training `OFF` or Privacy Mode `ON`).
4. Note the **capture date (YYYY-MM)** and **plan tier** (Free / Pro / Team / Enterprise) in your PR description.

---

## ✍️ Reporting Policy Changes or Adding a New AI Agent / 上报政策变更或新增工具

AI vendors frequently move privacy toggles or flip consumer opt-in defaults. When opening an Issue or PR:
- Include a link to the **official documentation, privacy policy, or release note**.
- Specify **default state by tier** (Personal/Free vs. Pro vs. Team/Enterprise vs. API).
- Keep descriptions crisp and scannable (**≤ 1–2 lines per bullet**, **≤ 4 steps** in the path).
