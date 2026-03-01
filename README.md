# HealthSyncJS 法务页面发布说明

已生成文件：

- `privacy.html`（隐私政策）
- `terms.html`（用户协议）

## 方案一：GitHub Pages（推荐）

1. 新建仓库，例如 `healthsync-legal-pages`
2. 上传这两个文件到仓库根目录
3. 仓库设置中开启 Pages（`Deploy from a branch`，`main` 分支 `/root`）
4. 等待 1-2 分钟后可访问：
   - `https://<你的用户名>.github.io/healthsync-legal-pages/privacy.html`
   - `https://<你的用户名>.github.io/healthsync-legal-pages/terms.html`

## 方案二：Gitee Pages

1. 新建公开仓库并上传两个文件
2. 开启 Gitee Pages 服务
3. 获取公网 URL 后填入 AGC

## 在 AGC 中填写

- 隐私政策链接：填 `privacy.html` 公网 URL
- 协议链接：填 `terms.html` 公网 URL

## 发布前请检查

- 页面能在浏览器直接打开（无需登录）
- 链接是 `https://`
- 内容中的邮箱、电话、公司主体信息与你实际信息一致
