**学习记录**

- **搭建环境**
  文件说明
    ```
    bochs-2.1.1.exe   -- Bochs system for use in win32 environment. Must be installed on your windows system first.
	bootimage-0.11 	  -- kernel 0.11 bootimage request rootimage from floppy.
	bootimage-0.11-fd -- request rootimage in disk b: 
	bootimage-0.11-hd -- boot harddisk root file system.
	bootimage-0.12-fd -- kernel 0.12 bootimage use with floppy root iamge.
	bootimage-0.12-hd -- kernel 0.12 bootimage use with harddisk root image.
	rootimage-0.11    -- kernel 0.11 rootimage.
	hdc-0.11	      -- harddisk root filesystem image.
	diskb.img	      -- a dos format disk image. can be w/r with mtools.
	bochsrc-fd.bxrc   -- bochs rc file configured for using disk root iamge.
	bochsrc-hd.bxrc   -- bochs rc file configured for using hd root image.
	gcclib-1.40.taz   -- tar files of the gcc bins & libs.
    ```
    目前使用从软盘启动OS,使用的根文件系统在硬盘上. 需要的文件有:
    - bootimage-0.11-hd
    - hdc-0.11
    - bochsrc-hd.bxrc
    
  运行步骤
  - 安装bochs-2.1.1.exe(如果已经安装则跳过)
  - 使用bochs运行bochsrc-hd.bxrc

- **Build Kernel**



