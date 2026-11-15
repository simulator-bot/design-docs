# design-docs
inner design docs


connection layer: 用于bot通过信号/视觉/日志等方式去阅读设备，并支持反向控制设备。这是连接了bot和物理世界的桥梁

simulator layer：用于仿真，一方面把学习过来的进行在平台上映射，另一方面支持在仿真平台设计全新的自动化

model layer: 用于学习理解和泛化自动化业务

agent layer：用于持续执行和持续学习

bot platform：用于整合agent、设备、自动化、调度等。