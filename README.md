# seckill
基于SSM+Mysql框架的商品秒杀案例
采用maven进行项目管理
对秒杀环节的高并发环节进行了优化:
1.用cdn存储js静态文件，
2.用redies服务器缓存热点函数
3.秒杀环节用mysql的存储过程
