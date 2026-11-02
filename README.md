# 狐文视觉素材资源市场

本仓库是该类资源的唯一维护入口。资源按需下载，不进入应用安装包；导出作品可以携带用户选用的字体。

- 主仓库：https://gitcode.com/wendao-ai/wendao-ai-material-market
- GitHub 镜像：https://github.com/wendaoai/wendao-ai-material-market
- Gitee 镜像：https://gitee.com/wendaoai/wendao-ai-material-market

由 GitCode 原生 Push 镜像同步完整 Git 内容，不在镜像仓库独立编辑。应用通过提示词市场中的统一索引访问本仓库。

资源 ID、版本、文件字节和授权沿用原市场。修改资源后运行 `npm run sync-metadata`、`npm run sync-index`、`npm run validate`，再提交到 GitCode。
随后在统一索引工作副本运行 `npm run sync-index`，复核分类版本、数量与 SHA-256 后推送索引。发布时先推送资源，确认三个镜像提交一致，再推送索引。

校验命令完全读取本地文件，不下载市场资源。详细授权见每项资源声明、`LICENSE`、`NOTICE.md` 和 `licenses/`。
