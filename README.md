# JAVA-
java课程作业项目仓库

## 实验目的
用类描述计算机中CPU的速度和硬盘的容量

## 实验过程
CPU类要求getspeed（）返回speed的值，要求setspeed（int m）方法将参数ｍ的值赋给speed；harddisk类要求getamount（）返回amount的值，要求setamount（int m）方法将参数m的值赋值给amount；PC类要求setCPU（CPU c）将参数c的值赋值给cpu，要求setharddisk（harddisk h）方法将参数h的值赋给HD，要求show（）方法能显示cpu的速度和硬盘的容量。

## 核心方法

核心：CPU cpu=new CPU();
		HardDisk HD=new HardDisk();
		cpu.setSpeed(2200);
		HD.setAmount(200);
		PC pc=new PC();
		pc.setCPU(cpu);
		pc.setHardDisk(HD);
		pc.show();
    
## 实验结果
CPU speed2200
HD amount200


## 实验感想
1.了解类和包
2.了解在不同包中import的用法
3.了解构造类型
4.了解基本数据类型
