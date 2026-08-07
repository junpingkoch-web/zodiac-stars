# Project: zodiac-stars（生肖与星座计算器）

零构建静态站，单文件结构：全部逻辑内联在一个 ~114KB 的 `index.html` 里（比 watch-valuator 更大，
同样是单文件套路，不要主动拆分成多文件）。中国生肖 + 西方星座计算器，标题走德语
"Chinesisches Tierkreiszeichen & Sternzeichen Rechner"。

## 文件结构
- `index.html` — 唯一核心文件
- `images/` — 配图
- `ads.txt` / `robots.txt` / `sitemap.xml` / `README.md` — 已补齐，跟其他仓库对齐

## 符合的生态约定
- `data-i18n` + `localStorage` 的手搓 i18n 模式，跟其他 sibling 工具一致
- AdSense (`pub-4830421367394194`) 和 GA4 (`G-7LZZQ43QD6`) 都已正确接入

## Commands
- 无构建/测试命令
- 本地预览：共享配置在 `C:\Users\junpi\.claude\.claude\launch.json`（先确认这个仓库是否已经在里面注册了端口，没有的话要新增一条）

## 部署流程
- 改完直接 commit + push 到 `main`
- Commit 作者身份：`Junping Koch <junping.koch@gmail.com>`，仓库单独设置

## 明确禁止的事
- 不要把单文件拆成 `index.html`/`style.css`/`script.js` 三件套，除非被明确要求——这是这个工具家族里单文件类工具的既定选择

## 持续维护
每次你需要重复纠正 Claude 同一件事三次以上，就把结论补进这个文件对应章节。
