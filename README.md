# AI智能对话应用 - webapp-keneng

## 项目简介
基于 Dify 工作流 + Next.js 构建的 AI 对话应用，实现流式输出、多轮对话、Markdown渲染。

## 我的角色
- 前端架构（Next.js + React + TypeScript）
- Dify 工作流设计与 API 集成
- AI 交互体验优化（加载状态、错误处理、流式展示）

## 技术栈
前端：Next.js 14 / React / TypeScript / Tailwind CSS
AI后端：Dify 工作流 / OpenAI API / SSE 流式输出
部署：Docker / Vercel

## 核心功能
1. AI多轮对话（Dify工作流编排）
2. SSE流式输出（打字机效果）
3. Markdown渲染（代码高亮、表格）
4. 响应式设计（移动端适配）

## 运行方式

```bash
npm install
npm run dev

## 项目截图

<img width="756" height="1680" alt="首页" src="https://github.com/user-attachments/assets/0c69f4fa-96fc-44bc-901a-3215fc796fec" />


<img width="1197" height="488" alt="image" src="https://github.com/user-attachments/assets/60609a52-ff83-4ad9-b469-798927f78f86" />

<img width="1862" height="733" alt="image" src="https://github.com/user-attachments/assets/4b952870-3584-475a-b9e4-2162b51ab0fb" />




## 开始
First, install dependencies:
```bash
npm install
# or
yarn
# or
pnpm install
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Docker

```
docker build . -t <DOCKER_HUB_REPO>/webapp-conversation:latest
# now you can access it in port 3000
docker run -p 3000:3000 <DOCKER_HUB_REPO>/webapp-conversation:latest
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

