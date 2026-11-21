# hello-git

Git 与 GitHub 连通性测试仓库。

## 用途

验证本机 Git 环境与 GitHub 账号（`meihuashuo666`）的 SSH 认证链路是否完整可用。

## 本机环境

| 项 | 值 |
| --- | --- |
| Git 版本 | 2.56.1.windows.1（PortableGit） |
| 安装位置 | `D:\tools\PortableGit` |
| 认证方式 | SSH（ed25519，端口 22） |
| 提交署名 | meihuashuo666 &lt;3256790872@qq.com&gt; |

## 说明

首次提交由本地通过 SSH 推送，用于确认读（clone / fetch）与写（push）双向通路均正常。

## 提交签名

本仓库启用 SSH 方式签名提交，签名密钥与认证密钥为同一把 ed25519 公钥，对应的 GitHub 侧需登记为 **Signing Key** 后，提交才会显示 Verified 徽章。