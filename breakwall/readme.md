- Linux环境下：
1. 在发行版安装libsodium库
2. 安装最新的shadowsocks python 库 pip install git+https://github.com/shadowsocks/shadowsocks.git@master
3. 下载run_ss.py, 启动run_ss.py -s {n} n为服务器编号，地址，加密方式，密码等全在该代码中，可修改。成功后1080端口为代理地址，注意防火墙得打开1080的tcp和udp
4. 配置chrome插件，SwitchyOmega.crx并加载配置文件OmegaOptions.bak
