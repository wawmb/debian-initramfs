# Brief introduction

嵌入式 Debian 系统 initramfs/rootfs 构建仓库，用于生成极简的内存根文件系统镜像，适配嵌入式设备运行。

# Command

- 构建基于 RAMFS 的嵌入式 Debian 根文件系统（rootfs）；
- 集成 udhcpc 自动网络配置、mdev 设备管理等嵌入式必备功能；
- 生成可直接用于内核启动的 ramdisk 镜像。