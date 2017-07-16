# SourceBlockchain

## 项目模块路径说明

    .
    ├── LICENSE       许可协议
    ├── README.md     说明文档
    ├── cmd           命令行，在服务器端开启根源链服务
    ├── console       控制台，服务器端开启rpc功能和执行根源链初始设置使用
    ├── contracts     智能合约
    ├── core          根源链业务核心，这部分涉及到发送物联网信息上链和电子凭证的基础实现
    ├── miner         记账者，实现记账者挖矿和记账的功能，实现物联网数据到根源链的存储
    ├── node          节点，实现记账者节点的管理
    ├── p2p           点对点连接，实现p2p协议
    ├── pow           pow共识，实现pow共识算法
    └── rpc           rpc接口，将溯源功能封装成rpc接口便于上层系统远程调用
