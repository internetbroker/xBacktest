# xBacktest: 基于C++的国内期货交易策略回测系统  
---
## 架构  
xBacktest是一个使用C++编写的期货交易策略回测系统，它借鉴了PyAlgoTrade的设计，采用事件驱动架构。   
## 功能
xBacktest支持以下功能：  
1. 支持多策略、多合约、多周期组合  
2. 支持多种性能分析指标  
3. 内置多种技术指标，可外接TA-Lib  
4. 支持策略参数寻优，支持遗传算法寻优  
5. 抽象DataSeries接口，方便用户使用  
6. 策略编写使用事件驱动模式
## 说明
xBacktest已停止开发，其存在的主要问题是过度设计。回测系统如果考虑太多现实中不常用的需求，会导致不必要的复杂性。  
改进版本的回测系统被集成到AlgoSE算法策略引擎中，实现回测与实盘接口的完全一致。
