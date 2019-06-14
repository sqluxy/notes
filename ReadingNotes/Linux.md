## Linux目录结构及文件基本操作
#### **1. FHS标准**
 Linux目录结构遵循FHS(_Filesystem Hierarchy Standard_)  
 FHS定义了两层规范  
  1. **/** 下面的各个目录该放什么文件数据, 如 **/etc** 应该放置设置文件， **/bin /sbin** 应该放置可执行文件.
  2. 针对 **/usr /var** 这两个目录的子目录来定义, 如 **/var/log** 放置系统登录文件, **/usr/share** 放置共享数据.
#### **2. 目录路径**
 * 路径  
  **cd** (_Change Directory_)用来切换路径.  
  **.** 表示当前目录, **..** 表示上一级目录(以 **.** 开头的文件都是隐藏文件，所以这两个文件目录也是隐藏的，可用 **ls -a** 来查看隐藏文件.  
  **-** 表示上一次所在目录.  
  **~** 通常表示当前用户的 **home** 目录.  
  **pwd** (_Print Working Directory_)可以获取用户当前所在路径.  
 * 绝对路径  
  绝对路径就是以根 "**/**" 为起点, 以所要到的目录为终点的完整路径.  
  如 **/usr/local/bin**  
 * 相对路径  
  相对路径就是以当前目录 **.** 为起点, 以所要到的目录为重点的完整路径.  
  如 **../../usr/local/bin**
  
  _Note: 在进行目录切换过程中多使用**Tab**键自动补全，可避免输入错误._  
#### **3. Linux文件的基本操作**  
 * 新建  
 
 