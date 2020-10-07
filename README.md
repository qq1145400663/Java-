# Java-
Java课程作业项目仓库

# 阅读程序
public static void main(String args[]) {
	  //����һ��CPU����
		CPU cpu =new CPU();
	  //��cpu��speed����Ϊ2200
	    cpu.setSpeed(2200);
	  //cpu�ͺ�  
	    cpu.settype("i7-9750H");
	  //����һ��HardDisk����
	    HardDisk disk=new HardDisk();
	  //��disk��amount����Ϊ200
	    disk.setAmount(200);
	  //Ӳ�̶�д�ٶ�  
	    disk.setspeed2(500);
	  //����һ��PC����
	    PC pc=new PC();
	    pc.setCPU(cpu);
	    pc.setHardDisk(disk);
	    pc.show();
	 }
## 实验目的
用类描述计算机中的CPU的速度和硬盘的容量。要求Java应用程序有4个类，名字分别是PC、CPU、HardDisk和Test，其中Test是主类。

## 实验过程
先创建PC类、CPU类、HardDisk类并将他们其中的参数赋值，在创建Test类，在main方法中创建对象并赋值及调用。
## 核心方法
1.方法的调用
2.Private的使用
3.参数的赋值

## 实验结果
![](`XQZ@5EH~7W(E4QL7P4S%)M)
## 实验感想
通过本次实验，我初步了解到了Java的基本功能，这为我之后的学习打下了很好的基础，其中也是学习到了如何创建对象，如何给对象赋值，如何调用方法等等。这也为我学习Java增添了信心，相信我会更上一步。
