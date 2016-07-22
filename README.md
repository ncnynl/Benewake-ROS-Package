# Benewake-ROS-Package
Benewake_ros_SerialPortPackage(serial_parse_publish）

1、运行命令：roslaunch serial_parse_publish serial_parse_publish.launch

2、话题名：/scan
	type：sensor_msgs/LaserScan
	
3、launch参数：
	StrengthThreshold	Strength值的过滤阈值
	QualityThreshold	Quality Score的过滤阈值
	COM					雷达连接的串口名
	BitRate				数据传输比特率
	注：过滤规则为：当该点数据对应的测量值小于设定的过滤阈值时，其距离会被重置为上一次测量的距离。当所有过滤阈值设为0时，不进行过滤。

