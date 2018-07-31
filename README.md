# MY_Ubuntu
## 网络不通的问题
网咯不通时，关闭所有虚拟机，然后编辑虚拟网络————>重置网络设置

## 加入新变量
如果需要加入到所有用户的变量

$ vim /etc/profile

# 在里面加入：

export PATH=home/（用户名）/.local/bin:$PATH

# 使生效

source profile
