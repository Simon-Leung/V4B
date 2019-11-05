# V4B Q&A
BUG问题反馈请到[Issues](https://github.com/Simon-Leung/V4B/issues)提交。

Q: 终端离线了怎么处理？  
A: 查看是否整机跳闸；对于V1.12版本，请提供SIM卡的ICCID给SIM卡供应商，查看SIM卡状态，若机卡分离，提供SIM卡供应商ICCID及要求绑定到新的IMEI，请交绑定；对于V1.11及以往版本，查看是否ID变为1，按“修改ID流程说明.pdf”处理。

Q: 终端断电后重新上传不运行怎么处理？  
A: 断电后放电5到10分钟再上电，若不能运行，重新烧录程序，若仍不运行，返厂处理。

Q: 如何本地修改终端ID?  
A: 请参考“终端烧录及命令操作说明.pdf”。

Q: 怎么查看终端是否连接到省厅测试服务器？  
A: 无法确认，可以直接修改终端服务器地址，看终端在省厅平台是否能变为“已登录”状态。

Q: 如何修改终端省厅IP地址？  
A: 请登录到厂商平台，修改终端参数，修改“省厅服务器地址”及“省厅服务器端口”，需先把这两个参数改成别的，再改回来。这两个参数默认为121.33.200.99:10001。

Q: 省厅平台后台管理网址是多少？  
A: 链接为: [岸电设备管理](http://www.gdport.gov.cn:10000/nettysocket/shorePower/index "岸电设备管理")

Q: 不能扫码怎么处理？  
A: 确认是否使用官方小程序生成的二维码，确认二维码头是否损坏，确认二维码头连接线是否损坏，确认终端是否在线。上述确认后仍不能扫码，请返厂检修。

Q: 厂商平台网址是多少？  
A: 链接为: [内河岸电管理系统](http://www.andianwang.com "内河岸电管理系统")，帐号密码请找易总提供。

Q: 收款二维码为什么不能下发？  
A: 请确认收款二维码是否太复杂，太复杂的二维码，终端没有空间储存。目前确认只支持微住收款二维码。
