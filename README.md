# SpringCloud
SpringCloud 搭建的简易项目
|  项目名称   | 用途   | 端口号 |
|  ----  | ----  | ----  |
|  eureka-server    | 服务注册中心    | 8081  |
|  compute1-service、compute2-service、compute3-service    | 服务单元   |  7071、7072、7073  |
|  feign-consumer    | 负载均衡器    | 8082  |
|  service-ribbon    | 负载均衡器    | 8083  |
|  service-zuul     | 网关   |  8084  |
|  service-gateway    | 网关    | 8087  |
|  eureka-config-server    | 配置中心    | 8085  |
|  hystrix-dashboard Hystrix    | 仪表盘     | 8086  |

该项目参考了方志朋[史上最简单的 SpringCloud](https://blog.csdn.net/forezp/article/details/70148833)来进行搭建。
详细文档描述建议参考这位大佬的博客即可，不做多余描述。
后期打算自己的微服务注册分别使用 mybatise 、mybatise plus、hibernate、Springdate jpa搭建微服务方便自己学习对比

项目运行工具推荐使用Run dashbord ，项目运行视图更加清晰客观
