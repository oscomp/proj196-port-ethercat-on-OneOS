# proj196-port-ethercat-on-OneOS
## 项目描述
EtherCAT作为当前主流工业总线协议，在实时性和生态方面具有优势。当前的EtherCAT主站主要运行在Linux+CPU平台上，如果将EtherCAT主站移植到RTOS+高性能MCU（比如M7内核）平台上，那么将为工业自动化提供一种高实时性、低成本的解决方案，可以满足很多多轴运动控制场景，比如工业机器人、新能源、AGV等领域。
我们的目标是移植开源EtherCAT主站（比如SOEM）到OneOS平台上，能与多台EtherCAT总线伺服电机进行通信，实现多轴同步控制，并测试出多轴情况下的总线同步周期和抖动周期，以评估系统的实时性。
- 移植开源EtherCAT主站（比如SOEM）到OneOS
- 控制6台EtherCAT总线伺服电机；
- 测试出6轴负载下的总线同步周期和抖动周期。 

## 源码

- [soem](https://openethercatsociety.github.io/doc/soem/)

## 项目导师
杨校权
- email yangxiaoquan@cmiot.chinamobile.com

## 难度
高级

## 文档
- [SOEM 参考文档](https://micro.ros.org/docs/tutorials/core/overview/)
- [OneOS 参考文件](https://github.com/acoinfo/sylixos_oscomp_2021)

## License
-	[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)

## 预期目标
注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标
第一题：移植开源EtherCAT主站到 OneOS
•	移植 soem 到 oneos操作系统，实现EtherCAT主站能力
•	实现6轴EtherCAT伺服电机的控制
•	测试出6轴负载下的总线同步周期和抖动周期

