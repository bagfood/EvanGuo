# EvanGuo
IB_jstack.sh   获取IB的PID号，并且执行jstack -l 指令
1、首先确定Jstack执行后的保存地址（默认） 当前地址+日期；
2、如果这个目录不存在将会自动建立；
3、执行alias 已经记录的contaionPIDs.sh获取PID号和子系统名称；
4、执行jastack -l PID > 保存地址
