# 服务端详解

服务器端开发是系统整体功能的重要组成部分，无论是C/S还是B/S的系统架构，都会有一个服务器端即Server。Server的核心就是根据应用根据业务需求进行计算，包括操作数据库，最终返回计算结果。在C/C的云+端服务模式中，实现最终业务与逻辑的也是服务器端应用程序。
 
iuap 平台服务端基于Spring成熟框架，对应用操作做了规范化的配置和示例，包括数据库连接池、事务处理、持久化设计等，让业务操作更方便简洁。同时针对云化的后端服务，使用分布式服务框架实现了线上部署环境的服务弹性扩容缩容，更有力的支撑系统运维自动化。