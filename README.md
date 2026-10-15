# 泽罗 ZERO · 官网

广州泽罗品牌营销策划有限公司官方网站。单文件静态站点，无需构建。

## 本地预览

直接双击 `index.html` 即可在浏览器中打开。

## 修改内容

全站只有一个文件：`index.html`。

- **公司名 / 联系方式**：搜索 `泽罗`、`ZERO`、`hello@example.com`、`your-wechat-id`
- **作品**：文件底部脚本开头的 `MEDIA` 列表，每条包含作品名、工艺说明、横竖版比例，
  补上 `src`（图片或 `.mp4` 路径）即可替换掉自动生成的占位画面
- **服务项目**：搜索 `svc__row`
- **关于我们的数据**：搜索 `class="facts"`
- **上线前**：删除底部 `id="demo-note"` 那一整块（版式示意提示）

## 部署

GitHub Pages 从 `main` 分支根目录发布。

```
git add -A
git commit -m "更新网站内容"
git push
```
