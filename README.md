# JD Comment Helper Releases

`JD Comment Helper` 是一个京东评论辅助工具，核心用途是：

- 采集其他买家的评论文案和配图
- 挑选可用素材
- 整理后发布自己的评论

这个仓库是公开发布通道，只用于提供：
- Windows 安装包
- 热更新包
- `version.json` 更新清单

主代码仓库不在这里维护。

## 软件功能

- 浏览器登录恢复与账号状态同步
- 拉取当前账号的待评论商品
- 采集商品页和评论接口里的他人评论文案
- 采集他人评论配图，并支持放大预览
- 选择评论文案和图片，组合成自己的评论内容
- 提交前将图片重新下载并上传，再发布自己的评论
- 应用内版本检查与热更新

## 下载方式

前往 Releases 页面下载最新正式版：

- [Latest Release](https://github.com/alipp3474/jd-comment-helper-releases/releases/latest)

常见文件说明：

- `JD.Comment.Helper-<version>.exe`
  - Windows 安装包
  - 适合首次安装
- `JD.Comment.Helper-<version>.zip`
  - 热更新包
  - 由程序自动下载和应用
- `version.json`
  - 更新清单文件
  - 程序会读取它判断是否有新版本

## 基本使用

1. 下载并安装最新的 `exe`
2. 启动程序
3. 按提示完成京东登录恢复或同步账号状态
4. 在商品列表中进入评论工作台
5. 从他人评论中选择合适的文案和图片
6. 确认后提交自己的评论

## 更新机制

程序默认会读取下面这个公开更新地址：

- [version.json](https://github.com/alipp3474/jd-comment-helper-releases/releases/latest/download/version.json)

更新流程是：

1. 检查版本清单
2. 发现新版本后提示用户
3. 下载热更新包
4. 重启后由启动器切换到新版本

## 当前最新版本

当前公开版本信息可直接查看：

- [version.json](https://github.com/alipp3474/jd-comment-helper-releases/releases/latest/download/version.json)

## 说明

- 这个仓库只负责发布，不处理源码问题
- 如果你是维护者，请在主仓库完成构建和发布后，再同步这里的 Release 资产

