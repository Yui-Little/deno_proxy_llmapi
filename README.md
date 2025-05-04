# deno_proxy_llmapi

 利用 Deno 快速搭建多 API 代理服务

![Deno Banner](https://deno.land/logo.svg){: style="border: 2px solid #e0f2fe; border-radius: 8px;"}

##  快速开始

<div style="border: 1px solid #e0f2fe; padding: 12px; border-radius: 8px; background-color: #f8fafc; margin: 12px 0;">

### 逐步图示指南

1. ​**注册/登录**​ [Deno Deploy](https://dash.deno.com/)

2. 在 ​**Overview**​ 页面点击 `New Playground`  
   <img src="https://github.com/user-attachments/assets/2a97b627-cd98-4d90-b49f-5821e790438e" style="border: 2px solid #bae6fd; border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); max-width: 80%;">

3. 清空编辑器默认内容  
   <img src="https://github.com/user-attachments/assets/9a6048fc-fd97-4cad-8ed4-27d91d555ba8" style="border: 2px solid #bae6fd; border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); max-width: 80%;">

4. 粘贴 `ts.txt` 全部代码  
   <img src="https://github.com/user-attachments/assets/56a8ff6d-0794-4165-b488-16eabb1c5938" style="border: 2px solid #bae6fd; border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); max-width: 80%;">

5. 点击 `Save & Deploy`  
   <img src="https://github.com/user-attachments/assets/cb80816e-4e6a-4ba3-86e7-7de44772e8b1" style="border: 2px solid #bae6fd; border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); max-width: 80%;">

6. 进入 `Projects` 查看部署结果  
   <img src="https://github.com/user-attachments/assets/b35a3bcc-b0a6-4c6c-bb12-78962fbe2a37" style="border: 2px solid #bae6fd; border-radius: 6px; box-shadow: 0 2px 4px rgba(0,0,0,0.1); max-width: 80%;">

7. 访问 `你的项目名.deno.dev`  
    出现 `Service is running!` 即成功

8. 实际调用格式：  
   ```bash
   https://你的项目名.deno.dev/xai/v1
