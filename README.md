# Redmi AX6 ImmortalWrt 编译仓库

本仓库已精简为仅保留 Redmi AX6 ImmortalWrt 的构建入口、公共脚本、配置、依赖补丁与特殊包，适用于单设备定制编译。

## 目录说明

- 构建入口：build.sh
- 设备配置：wrt_core/compilecfg/redmi_ax6_immwrt.ini
- 设备配置文件：wrt_core/deconfig/redmi_ax6_immwrt.config
- 公共构建脚本：wrt_core/modules/
- 补丁与特殊包：wrt_core/patches/

## 编译方式

直接编译：

```bash
./build.sh redmi_ax6_immwrt
```

预览配置组合：

```bash
./build.sh redmi_ax6_immwrt config_preview
```

## 说明

- 当前仓库仅保留 Redmi AX6 ImmortalWrt 相关构建内容。
- 其他路由器的固件配置和编译入口已移除。
- 如需修改默认配置，可直接编辑对应的配置文件。