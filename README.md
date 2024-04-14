

# 使用指南

## 创建工作空间 tianbot_mini_ws

mkdir tianbot_mini_ws/src -p  
cd ~/tianbot_mini_ws/src  

## 部署 tianbot_mini_zoo

cd ~/tianbot_mini_ws/src  
git clone https://github.com/tianbot/tianbot_mini.git  

## 编译工作空间 tianbot_mini_ws

source /opt/ros/melodic/setup.bash  
cd ~/tianbot_mini_ws/  
catkin_make  
echo "source ~/tianbot_mini_ws/devel/setup.bash --extend" >> ~/.bashrc  

