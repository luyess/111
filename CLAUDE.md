# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 仓库状态

仓库目前为空。项目初始化后请在此补充技术栈、常用命令和架构说明。

## 工作约定

- 默认用中文回复；commit message 用英文。
- 回答简洁直接，优先给出可用结果；不确定就明说，不要补造。
- 修改已有文件前，先简要说明改哪些文件、改什么。
- 临时脚本和中间产物放入 `tmp/` 等明确目录，不堆在根目录。
- 完成后说明：做了什么、文件在哪、哪些未验证。

## 高风险操作（先询问）

- 批量删除源代码或不可再生文件（构建产物、依赖、临时目录可直接批量清理）。
- `git push --force`、`git reset --hard` 等可能丢失提交的操作。
- 对外发布：创建 PR、发评论、向外部服务写入数据。
