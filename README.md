/*********************************************************************************************************
**
**                                 中国软件开源组织
**
**                                   虚拟军事仿真平台
**
**                           	Ksnail(TM)  VMS：virtual military simulation
**
**                               Copyright All Rights Reserved
**
**--------------文件信息--------------------------------------------------------------------------------
**
** 文   件   名: ReadMe.md
**
** 创   建   人: Kael.Wang (王梦求)
**
** 文件创建日期: 2018 年 07 月 17 日
**
** 描        述: 记录版本更新.
*********************************************************************************************************/

/*********************************************************************************************************
** 日	期 : 2018.07.17
** 功能描述: 创建项目计划以及版本控制SVN
** 
** 内  容  : 创建第一个项目；采用标准的强命名规范以及项目模块划分；整个军事仿真系统分为：三维仿真、二维仿真、
			系统架构采用C/S模式：插件化、脚本化、模块化异构系统原型
			
			2/3d studio	
			vbs : virtual battle system
			
*********************************************************************************************************/
1.工程规范目录划分: dist(程序输出目录)；build(程序编译目录)；doc(文档)；ext(第三方库)：source(源码目录)
2.doc中添加程序编码规范说明文档(包括c/c++规范说明)

/*********************************************************************************************************
** 日	期 : 2018.07.25
** 功能描述: 创建KsCore模块
** 
** 内  容  : 创建Ksnail系统核心模块.
			采用qt/corelib目录结构加上VBS/Essence目录结构（将Error Prop\Essencecommon\ReportStack\\合并到
			global文件目录下）
			提供ARCH，基本数学库运算，容器，文件IO访问，内存管理，信号，线程，json\xml操作库，智能指针

** LOG:
2018.07.25  使用 __errno 作为函数名.
			
** BUG:
2011.03.04  使用 __errno 作为函数名.
*********************************************************************************************************/
1.

















































/*********************************************************************************************************
  END
*********************************************************************************************************/
