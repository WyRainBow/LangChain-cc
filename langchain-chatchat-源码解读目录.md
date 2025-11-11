# Langchain-Chatchat 源码解读目录

## Langchain–Chatchat
- 模型启动
  - 模型启动脚本
  - 与大模型对话
  - 知识库
- 流式输出设计
  - 知识问答返回结果解析
  - 对话返回结果解析

## langchain
- 扩展文档分割器
- 扩展模型 model
- 扩展 callback 回调
- 扩展 chain
- OpenAI 的 API 有哪些 resource 模块可用

## 重点的模块包
- fastchat
  - 总体介绍
  - FastChat 框架源码解析之 controller 介绍
  - fastchat 的 controller.py、model 相关实现
  - fastchat 的 chat 加载和调用流程
  - fastchat 的 event 事件
- fastAPI
  - FastAPI
  - 关于 Uvicorn
  - 中间件（add_middleware 函数）
- SQLAlchemy
