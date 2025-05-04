# deno_proxy_llmapi
利用deno进行api代理
# Deno Playground 部署指南

快速搭建 多种 API 代理服务

## 🚀 快速开始

1. **注册/登录** [Deno Deploy](https://dash.deno.com/)

2. 在 **Overview** 页面点击 `New Playground`
![1](https://github.com/user-attachments/assets/2a97b627-cd98-4d90-b49f-5821e790438e)

3. 删除左侧编辑器全部默认内容
![2](https://github.com/user-attachments/assets/9a6048fc-fd97-4cad-8ed4-27d91d555ba8)

4. 复制粘贴本项目 `ts.txt` 文件所有代码
![ts](https://github.com/user-attachments/assets/56a8ff6d-0794-4165-b488-16eabb1c5938)

5. 点击 `Save & Deploy` 保存部署
![3](https://github.com/user-attachments/assets/cb80816e-4e6a-4ba3-86e7-7de44772e8b1)

6. 返回主界面进入 `Projects` 栏目

7. 在项目列表中可见：
   - 左侧：您的项目名（如 `xai`）
   - 右侧：生成的服务URL
![4](https://github.com/user-attachments/assets/b35a3bcc-b0a6-4c6c-bb12-78962fbe2a37)

8. 新窗口访问 `xxx.deno.dev`  xxx是你创建好的url
   👉 出现 `Service is running!` 即表示代理成功

9.最后调用时使用url `xxx.deno.dev/xai/v1` 即可使用,xai是我使用的ai
![api](https://github.com/user-attachments/assets/54bcb5cf-c09e-4375-8753-e599da406e20)


## ✨ 功能特点

- 基于 Deno 无服务器架构，秒级部署
- 轻量级 API 代理服务
- 无需复杂配置，开箱即用

## ⚠️ 注意事项

- 实际URL中的 `xxx` 需替换为您的 Deno 项目名
- 示例中的 `xai` 路径会自动匹配您的项目名称
- 首次部署通常 10 秒内完成

## 🆘 遇到问题？

欢迎在本项目提交 Issue 反馈问题  
或检查是否完整复制了 `ts.txt` 内容

---

> **提示**：部署成功后建议将 URL 加入书签备用！
喜欢的话点个Star吧~
这是我修改后的代码，能不能给图片加一个浅蓝色的边，不然和文字融为一体了
