# BlackDragon Meridian

---
> ### 1.gdm_jd_analytics_online
>> * task_id:322922	
>> * 启动项：gdm_jd_analytics_online.sh
>> * 任务描述：gdm基础表加工
> ### 2.gdm_jd_analytics_wireless 
>> * task_id:322783	
>> * 启动项：gdm_jd_analytics_wireless.sh
>> * 任务描述：gdm基础表加工
> ### 3.app_zwx_page_d_b
>> * task_id:325590	
>> * 启动项：app_zwx_page_d_b.py
>> * 任务描述：app_zwx_page_d_b
> ### 4.create_table_sql
>> * 黑珑子午线相关hive表建表语句
> ### 5.execute_scripts
>> * python执行脚本
> ### 6.HttpToHdfs
>> * 任务名称：bdm_Analytics_data_extract
>> * task_id:321909
>> * 任务描述：从服务器读取文件并放入集市
>> * 主类名:Http2Hdfs
>>> * usages：java -jar HttpToHdfs.jar http://172.20.165.130/mercury_logs/clickstream_m.log-20181217_08-172.20.165.130 /user/mart_tra/Jd_Analytics/20181217/clickstream_m.log-20181217_08-172.20.165.130 3 300
> ### 7.outsideDataParser
>> * 任务描述：同用户、同一日志类型、同访次进行排序，根据uuid对pin补全、ip地址解析、页面访问序号、驻留时间，解析完成后输出文本文件，并入fdm表
>>* task_id:322718
>>> 启动项：bdm_Analytics_data_parse_js.py 
>>* task_id:322701
>>> 启动项：bdm_Analytics_data_parse_sdk.py 







