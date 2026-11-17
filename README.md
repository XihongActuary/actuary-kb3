# 精算思维知识库（actuary-kb3 · 西红精算第三季）

《精算思维，不止于保险——像精算师一样思考》25 页知识库，水墨宣纸五色设计系统，与第一季 [actuary-kb](https://xihongactuary.github.io/actuary-kb/)、第二季 [actuary-kb2](https://xihongactuary.github.io/actuary-kb2/) 姊妹站同构互链。

## 结构（25 页正文 + 3 张框架页）

- 开卷：00 序言
- 第一部分 · 跨期折现力（01–04 章 + 05 部分总结）
- 第二部分 · 动态修正与反馈力（06 经验分析、07 滚动预测、08 随机模拟与反馈闭环 + 09 部分总结）
- 第三部分 · 安全边际与兜底力（10 风险边际、11 偿付能力资本、12 审慎原则与关键风险、13 黑天鹅准备）
- 第四部分 · 风险优先级力（14–16 章）
- 第五部分 · 沟通翻译力（17–19 章）
- 第六部分 · 人生全局平衡力（20–22 章）
- 收官：23 结语（30 天打卡表）、24 全书总结
- index.html / resources.html / xihong.html

全书 20 章统一编号（1–20），原连载缺失的第 5 章（经验分析）、第 9 章（偿付能力资本）由 AI 依据部分总结的事实口径补写；重复源文件已剔除。

## 构建 / 部署

- 源文件：`../《精算思维，不止于保险》——像精算师一样思考/`（公众号导出 HTML）
- 构建：`python _notes/_build.py`（清洗尾部样板、修复源文件表格标签损坏、嵌套框展开、注入 SVG 配图、生成 index/resources/xihong）
- 自检：链接可达、无残留样板、div 配平、js 进度 key `actuary-kb3-v1`
- 部署：`GITHUB_TOKEN=xxx python _notes/deploy_github.py`，仓库 `actuary-kb3`，main 根目录；`_notes/` 不上传

_ notes 目录不上线。
