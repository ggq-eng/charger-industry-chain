# charger-industry-chain

> 来源分类：**原创/AI打磨** ｜ 导出批次：published

输出充电桩产业链的上中下游结构，生成含数量和规格的采购级零件清单，输出2D拆解图物料并进行生产工艺流程Excel分析。支持慢充/快充/超充三种类型，可根据型号自动识别。四大模块：产业链(A)、采购清单(B)、2D拆解图(C)、生产工艺Excel(D)。

## 安装

把本文件夹整体复制到 WorkBuddy 技能目录：

```bash
cp -r . ~/.workbuddy/skills/charger-industry-chain        # 用户级
# 或
cp -r . <项目>/.workbuddy/skills/charger-industry-chain   # 项目级
```

重启/刷新 WorkBuddy 后即可在对话中触发。

## 说明

- 本技能从本地 WorkBuddy 环境导出，**所有真实密钥已脱敏为占位符**，使用前请配置你自己的 API Key。
- 若来自技能市场（文件夹名以 `__skillhub` 结尾），版权归原作者，请遵守其许可证。
