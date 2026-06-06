# 📡 AI Event System

AI事件系统工具，支持事件设计、事件驱动、事件处理。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🏗️ 事件系统设计
- 🔄 事件驱动架构
- 💻 事件处理器生成
- 🗄️ 事件存储设计
- 🔗 Saga模式设计
- 📋 事件Schema生成

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_event_system import create_tools

tools = create_tools()

# 事件系统设计
system = tools.design_event_system("电商")

# 事件驱动架构
architecture = tools.design_event_driven_architecture(["订单服务", "支付服务"])

# 事件处理器
handler = tools.generate_event_handler("订单创建", "python")

# 事件存储
store = tools.design_event_store("订单系统")

# Saga模式
saga = tools.design_saga_pattern("订单处理", ["创建订单", "扣减库存", "支付"])

# 事件Schema
schema = tools.generate_event_schema("订单创建", ["订单ID", "金额", "商品"])
```

## 📁 项目结构

```
ai-event-system/
├── tools.py       # 事件系统工具核心
└── README.md
```

## 📄 许可证

MIT License
