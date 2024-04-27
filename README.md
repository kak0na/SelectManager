# 【UE】Select Manager Quick Start



## quick start

1.Create an optional blueprint BP_A derived from BP_OptionBase

<img src="【UE】Select Manager Quick Start/image-20240427121317279.png" alt="image-20240427121317279" style="zoom:50%;" /> ![image-20240427121338704](【UE】Select Manager Quick Start/image-20240427121338704.png) 

2. Implement related methods in BP_A

![image-20240427122636149](【UE】Select Manager Quick Start/image-20240427122636149.png) 

The other two methods do not need to be implemented, the parent class has already implemented them.

![image-20240427121900205](【UE】Select Manager Quick Start/image-20240427121900205.png) 

3.Put multiple BP_A in the scene

![image-20240427122602850](【UE】Select Manager Quick Start/image-20240427122602850.png) 

4. Derive the subclass BP_AManager of Manager and put it into the scene

<img src="【UE】Select Manager Quick Start/image-20240427122810645.png" alt="image-20240427122810645" style="zoom:50%;" /> ![image-20240427122857630](【UE】Select Manager Quick Start/image-20240427122857630.png) 

 ![image-20240427122944493](【UE】Select Manager Quick Start/image-20240427122944493.png)



5.Add options to the management class, there are many ways

Method 1: Direct quotation

<img src="【UE】Select Manager Quick Start/image-20240427123032786.png" alt="image-20240427123032786" style="zoom:67%;" /> 

Method 2: Use blueprint nodes to set entry options

![image-20240427123455847](【UE】Select Manager Quick Start/image-20240427123455847.png) 

Method 3: Add options using blueprint nodes

![image-20240427123540135](【UE】Select Manager Quick Start/image-20240427123540135.png) 



6.Set different trigger options

![image-20240427123845651](【UE】Select Manager Quick Start/image-20240427123845651.png) 



7.Set radio mode

![image-20240427123633300](【UE】Select Manager Quick Start/image-20240427123633300.png) 

Press 1：

<img src="【UE】Select Manager Quick Start/image-20240427123932352.png" alt="image-20240427123932352" style="zoom:67%;" /> 

Press 5：

<img src="【UE】Select Manager Quick Start/image-20240427123937299.png" alt="image-20240427123937299" style="zoom:67%;" /> 



9.Set multiple selection mode

![image-20240427124302862](【UE】Select Manager Quick Start/image-20240427124302862.png) 



Press 1：

![image-20240427124341053](【UE】Select Manager Quick Start/image-20240427124341053.png) 



Press 5：

![image-20240427124345743](【UE】Select Manager Quick Start/image-20240427124345743-1714194081466-21.png) 



11. Modify button 5 as a switching option

![image-20240427124420072](【UE】Select Manager Quick Start/image-20240427124420072.png) 

Press 5.

![image-20240427124345743](【UE】Select Manager Quick Start/image-20240427124345743.png)

Press 5 again：

![image-20240427124503795](【UE】Select Manager Quick Start/image-20240427124503795.png)



包含的方法：

SelectionMode：

![PixPin_2024-04-27_13-26-37](【UE】SelectManagerQuickStart\PixPin_2024-04-27_13-26-37.png)

Child：

![PixPin_2024-04-27_13-30-44](【UE】SelectManagerQuickStart\PixPin_2024-04-27_13-30-44.png)

Select：

![PixPin_2024-04-27_13-36-59](C:/Users/EasyV-Nike/Documents/GitHub/SelectManager/【UE】SelectManagerQuickStart/PixPin_2024-04-27_13-36-59.png)

EventDispatchers

![image-20240427204933817](【UE】SelectManagerQuickStart\image-20240427204933817.png) 