嗯，博客写着外出七天取材写代码，说七天就是七天！基本功能已经实现了，先说下有什么吧。
first: 用户模块 数据库的增删改查 
second: 模块管理模块 调用了ansible-playbook，通过勾选复选框以及输入的IP地址 来达成按钮完成部署环境，当然是在已经写好的多个的模块里面进行匹配拉
third: 资产管理模块-资产信息 通过过滤ansible的setup 得到对应的值入库之后取出来渲染到模版里
-批量命令 通过多线程ssh来实现批量命令，返回结果抽取写入的日志   
- 批量授权 通过多线程ssh来实现密钥种植，返回结果抽取写入的日志
- 批量录入 录入setup 过滤的信息入库
fifth: 上传下载模块 通过多线程和sftp 实现批量上传下载
sixth: 监控现在写(租的宽带说多了都是泪。白天写面试题晚上拆人家轮子，从zabbix把图片抓下来渲染到监控栏目那。。。太low了，在看看一些图库吧)

一共会更新三个版本，现在第一个版本很烂（个人水平太低...），先上班之后开始重构优化代码添加新功能升级为第二个版本（时间不确定），通过大半年的沉淀将在明年今日推出第三个版本^_^

![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/1.png)
![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/2.png)
![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/3.png)
![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/4.png)
![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/5.png)
![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/6.png)
![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/7.png)
![image](https://github.com/jinjin123/-Development-of-an-automatic-platform/blob/master/img-read/8.png)
