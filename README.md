# 北大侠客行 pkuxkx MUD 新手村机器人 mudlet-lua

这个机器人旨在帮助玩家自动完成北大侠客行MUD新手村的任务，包括自动跑任务、修炼，并最终离开新手村。

## 功能

- **自动执行任务**：登录后自动开始执行新手村的任务。
- **自动修炼**：在适当的时间自动进行技能修炼。
- **自动离开新手村**：完成所有任务和修炼后，自动离开新手村。

## 组件

机器人主要由以下几个部分组成：

### 变量
- **kongfu**：用于存储当前正在修炼的功夫类型。

### 别名
1. **newuser**：用于执行新手村的上半场任务。
2. **afternew**：用于执行新手村的下半场任务。

### 触发器
- **sleep**：当需要休息时触发。
- **xuexi**：用于学习新技能。
- **sleep2**：第二阶段休息触发器。
- **putongkongfu**：普通功夫修炼触发器。
- **gaojikongfu**：高级功夫修炼触发器。
- **jifakongfu**：激发功夫修炼触发器。
- **laohu**：打老虎老虎相关触发器。
- **xiache**：下车或离开相关触发器。

## 使用方法

1. 启动北大侠客行MUD客户端并登录。
2. 激活机器人的各个组件。
3. 使用`newuser`别名开始上半场任务。
4. 触发器将在适当的时候自动执行。
5. 触发器完成后会使用`afternew`别名开始下半场任务。
6. 完成所有任务后，机器人将帮助角色离开新手村。

## 注意事项

- 确保在开始使用机器人之前已经正确设置了所有触发器和别名。
- 监控机器人的运行，以防止任何意外情况发生。
