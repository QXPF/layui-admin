# layuiAdmin
 + 基于layui的后台模版
## git过滤规则
+ /target/ ：过滤文件设置，表示过滤这个文件夹
+ *.mdb  ，*.ldb  ，*.sln 表示过滤某种类型的文件
+ /mtk/do.c ，/mtk/if.h  表示指定过滤某个文件下具体文件
+ !*.c , !/dir/subdir/     !开头表示不过滤
+  *.[oa]    支持通配符：过滤repo中所有以.o或者.a为扩展名的文件
##测试