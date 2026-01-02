# 斐讯n1
修改了飞牛官方刷入emmc的脚本
适合给n1扩容了32g，64g，128g及以上的设备使用

# 两个脚本：
install-16.sh 设置系统空间为16g(实际没有，系统内置占用2g旁边)，其他空间可作为储存空间使用

install-32.sh 设置系统空间为32g(实际没有，系统内置占用2g旁边)，其他空间可作为储存空间使用
# 在按照教程（自行查找）从u盘启动飞牛系统后。不要输入（bash install-to-emmc.sh ）,使用下面脚本
# 设置系统空间为16g
curl https://github.com/lezhengqiuyuan/n1/blob/main/install-16.sh

chomd +x install-16.sh

sudo bash install-16.sh
# 设置系统空间为32g
curl https://github.com/lezhengqiuyuan/n1/blob/main/install-32.sh

chomd +x install-32.sh

sudo bash install-32.sh
