# TikTok 爆款关键词搜索流

双击 `index.html` 即可使用，无需安装或 API Key。也可以部署为静态网址供多人访问。

- 页面首次打开没有任何账号；每个人自行新增、选择和删除账号
- 账号配置只保存在使用者当前浏览器的 `localStorage`，不会上传服务器
- 自动覆盖 `how to / tutorial / trend / original / template / edit / filter / effect`
- 可选英语、西班牙语、葡萄牙语搜索变体、人物/IP 变体与工具词
- 每个账号自动切换钩子、贴纸、文字位置、颜色、特效
- 一键复制单条或全部结果；最近生成记录保存在浏览器 `localStorage`

把 `index.html` 发给同事即可离线使用。部署到静态网站后，所有同事也可以打开同一个网址使用，但彼此的账号和生成历史互不共享。

## GitHub Pages 部署

1. 在 GitHub 新建一个公开仓库，例如 `tiktok-search-flow`。
2. 将根目录的 `index.html`、`.nojekyll` 和 `README.md` 推送到 `main` 分支。
3. 打开仓库的 `Settings > Pages`，选择 `Deploy from a branch`，分支选 `main`，目录选 `/ (root)`。
4. 网址格式为 `https://你的GitHub用户名.github.io/tiktok-search-flow/`。

公开仓库中不包含任何默认账号。账号和最近生成记录只写入访问者自己的浏览器本地存储。
