#### 介绍
orangepi的gentoo系统镜像，eselect profile为default/linux/arm64/17.0/systemd/merged-usr

orangepi5的官方openwrt镜像，内核引导部分来自来自https://github.com/7Ji/orangepi5-rkloader

#### 安装教程
1.下载镜像包orangepi_5-gentoo.img.zst 
2.使用zstd工具对镜像包进行解压 使用dd命令把orangepi_5-gentoo.img镜像写入的内存卡 
3.使用前必须扩容，否则仓库创建失败

#### 使用说明
账户名称：root 密码：root 连接网络工具dhcpcd
