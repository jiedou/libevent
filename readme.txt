ubuntu 编译步骤
1.git clone https://github.com/libevent/libevent.git

2. mkdir build && cd build
   cmake -DEVENT__DISABLE_MBEDTLS=ON ../

如果报错openssh没找到 则使用下列命令安装即可
sudo apt-get install libssl-dev -y

3. make
4. make verify
   运行测试用例
