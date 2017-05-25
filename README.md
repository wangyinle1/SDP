# SDP
```
gantt
dateFormat YYYY-MM-DD

title EDM模块开发计划

        section S1
        
        需求调研阶段                            :active,  des1, 2017-05-24, 21d
        开发框架选择                            :done  ,  edm1, 2017-05-24, 2d
        服务器的配置与安全机制设计              :active,  des2, 2017-05-24, 30d
        创建版本控制                            :active,  edm2, after edm1, 1d
        数据库初步设计                          :active,      , after edm1, 7d
        测试阿里云的EDM接口和思齐的接口         :         edm3, after edm1, 3d
        EDM的单发功能                           :         code1,after edm3, 2d
        EDM的群发功能                           :         code2,after code1,3d
        EDM的回执统计                           :         code3,after code2,3d
        系统测试                                :         code4,after code3,3d
```

---
>EDM的功能需求
1. 系统对指定用户的邮件发送
2. 系统对指定多用户的邮件发送
3. 系统对用户的回信回执管理
