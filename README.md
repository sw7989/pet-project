This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.For more information, please check Tuya Developer Website.

一、方案标题
==
     智能宠物喂食器

二、方案应用场景
==

    产品描述： 
            宠物，已经逐渐成为打工人的家庭成员之一，是打工人下班后疲惫身心的心灵安慰，抚摸宠物的毛发，心中的阴霾可以一扫而光。
            但是受到疫情后时代和工作以及各种事件的影响，铲屎官们并不能每天都在家陪伴他们的小可爱。因此，宠物的喂食问题就成了
            每个铲屎官头疼的问题，
            送往宠物医院寄养？ 有些生性胆小的宠物到了陌生的环境会过于害怕导致不吃不喝。
            请人上门喂养？如果是亲朋好友倒也可以，如果是同城上找的，家里的安全无法得到保证。
            结合以上的痛点，本DEMO应运而生。
            本DEMO旨在解决家庭中养有宠物的喂食问题，每日根据铲屎官制定的计划定时定量喂养家中的宠物。
            本DEMO带有一个433MHz遥控器，宠物可通过一定的练习，按动遥控器实现宠物自行投食，亦可作为铲屎官的手动投食遥控器使用。
          
    应用地点:  
            室内以及各种WIFI网络覆盖场所。
          
    功能: 
            1）用户在手机APP端设置每日的喂食计划，智能宠物喂食器会根据制定的计划每日定时定量喂养宠物；
            2）用户可以使用手机APP端实现WIFI远程手动投食；
            3）允许宠物通过按压外置的433MHZ遥控器给自己加餐，用户可以设置允许加餐的次数和数量；
            4）喂食盆状态监测，每次喂食自动伸出喂食盆，进食完毕后自动收回，避免宠物毛发掉落在喂食盆中；
            5）电池电量检测，低电量远程通知；
            6）粮食储量监测，低粮远程通知；
            7）超长待机，智能宠物喂食器在无需工作时，会进入休眠模式，减少电池电量消耗，达到更长的续航时间
            8）供电方式切换，在家里突发没有电的情况下会自动切换为电池供电，保障宠物的喂食计划不受影响

三、开发计划
==
    1）3月9号完成整体SDK移植
    2）3月10-12号完成整体PCB设计，本次设计采用底板加各种模块的组合
    3）3月13号准备本次设计所需要的的所有物料和模块
    3）3月16号完成电路板的焊接
    4）3月21号开始调试程序
    5）3月26号完成设计

四、预计使用硬件
==
    1）STM32F103C8T6核心板（喂食器用）
    2）九齐NY8A051F单片机（遥控器用）
    2）通信板（ Wi-Fi MCU 通信板（WB3S））
    3）H桥直流电机驱动功能板
    4）直流供电电源板
    5）锂电池以及充电模块
    6）红外对管模块
    7）433MHZ无线发射模块
    8）433MHZ无线接收模块
    9）霍尔检测模块
    10）减速电机
