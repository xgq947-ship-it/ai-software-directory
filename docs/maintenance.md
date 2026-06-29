# 维护规范

每条记录至少包含：

```yaml
id:
name:
category:
vendor:
homepage:
download_page:
official_source:
platforms:
pricing:
source_type:
tags:
last_checked:
notes:
```

更新规则：

- `download_page` 优先写官网下载页、安装文档或 GitHub Release。
- `official_source` 写验证来源，方便复查。
- `last_checked` 用实际复查日期。
- 如果官方入口迁移，保留新入口，不保留失效旧入口。
- 如果项目停止维护，把 `status` 改成 `deprecated`，不要直接删除。
- 任何第三方镜像、搬运包、破解包都不进入主数据。

推荐复查周期：

- 编程 Agent：每 30 天。
- 桌面客户端：每 60 天。
- 模型权重：每 60 天。
- 网络基础工具：每 30 天。
