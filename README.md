# Ora Node
前置条件:拥有支持ubuntu 原生/docker desktop 设备即可，优先建议Ubuntu VPS 运行  
推荐配置:  
单核CPU、12G运行内存、50G固态硬盘、100m网络  
在跑节点前，需要先有一台电脑，可以是本地电脑也可以是云服务器（VPS），由于节点需要24小时不间断运行，个人建议购买VPS进行跑节点。 我自己用的是Contabo的VPS   
https://www.tkqlhce.com/click-101085808-13484397  
建议选购cloud 2 配置  
需要一个钱包私钥，建议使用新钱包空钱包  
需要领取Sepolia网络的测试币：  
https://www.alchemy.com/faucets/ethereum-sepolia?source=post_page-----e4975546dbaa--------------------------------  
在Alchemy创建个人RPC，需要获取Mainnet、Sepolia网络的wss、https的PRC：  
https://www.alchemy.com/  
在Linux系统运行以下脚本：  
wget -O ora.sh https://raw.githubusercontent.com/Qzy05231/ora/refs/heads/main/ora.sh && chmod +x ora.sh && ./ora.sh
  
选择要执行的操作<br>
输入各项PRC执行
