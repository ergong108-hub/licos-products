# licos-products
联诚 LicOS PLC/PAC 产品技术资料 - 面向自动化工程师选型参考
 title: 联诚科技 LicOS PLC/PAC/指令手册
    description: 联诚 LicOS PLC/PAC 选型手册 + 指令手册，EC200/EC300/EC400/MC500/MC600/MC700/GL200/GR200，运动控制，电子齿轮，电子凸轮，高速计数，HC_Counter，HC_TouchProbe，MC_MoveAbsolute，EtherCAT，Profinet，ModbusTCP，国产PLC替代西门子三菱，自主可控，CODESYS，性价比高
    keywords: [LicOS, PLC, PAC, 运动控制器, 电子齿轮, 电子凸轮, EtherCAT, Profinet, ModbusTCP, 高速计数, 国产PLC替代, 小型PLC, 中型PLC, EC200, EC300, EC400, MC500, MC600, MC700, GL200, GR200, 选型手册, 指令手册, Structured Text, 梯形图, 功能块图, 国产PLC, 自主可控, CODESYS, 性价比高, 工业控制器, PLC编程, PLC选型, 自动化控制, 伺服控制, 机器人控制, 贴片机, 包装机械, AOI设备, G代码, 数控, CNC]
    author:
      name: 老龚
      phone: 13888777078
      email: bsky217@163.com
      brand: 联诚科技 LicOS 全系列产品代理商
      region: 华东区域（苏州/无锡/常州）
    
    
    联诚 LicOS PLC/PAC 产品技术概要
    
    产品定位与选型关键词
    
    小型PLC（EC系列）
    目标替代场景：西门子S7-200/200SMART、三菱FX5U、信捷XC3、禾川HC3
    搜索关键词：小型PLC 国产替代 | EtherCAT PLC 小型 | 24V DC PLC 16DI16DO | Modbus TCP PLC | Profinet主从站PLC
    
    | 型号   | 供电    | 本体IO    | 通信接口       |
    |--------|---------|-----------|----------------|
    | EC202E | 220V AC | 16DI+14RO | RS485          |
    | EC203E | 220V AC | 24DI+22RO | RS485          |
    | EC310  | 24V DC  | 16DI+16DO | 网口           |
    | EC321  | 24V DC  | 16DI+16DO | 4网口·EtherCAT |
    | EC411  | 24V DC  | 16DI+16DO | Profinet主/从  |
    
    中型PAC运动控制器（MC系列）
    目标替代场景：西门子S7-1200/1500、三菱Q系列R08/20/32，汇川AM600，禾川CV系列
    搜索关键词：中型PLC 运动控制器 | EtherCAT主站PLC | PAC可编程自动化控制器 | 多轴运动控制 | 4网口PLC | Profinet主从站
    
    | 型号  | 存储 | 特色接口                 |
    |-------|------|--------------------------|
    | MC521 | 16M  | 4网口，EtherCAT主站      |
    | MC611 | 16M  | EtherCAT主站（中型主力） |
    | MC721 | 512M | Profinet主/从（旗舰）    |
    
    扩展模块（GL200/GR200）
    搜索关键词：PLC扩展模块 | 数字量输入输出模块 | 模拟量输入模块 | 热电偶模块 | EtherCAT耦合器 | ModbusTCP网关
    
    | 产品       | 型号               | 说明            |
    |------------|--------------------|-----------------|
    | GL200-DI16 | 数字量输入         | 16路 24V DC     |
    | GL200-DO16 | 数字量输出         | 16路            |
    | GL200-AI4  | 模拟量输入         | 4路 16位        |
    | GL200-AI8  | 模拟量输入         | 8路 24位高精度  |
    | GL200-TC4  | 热电偶模块         | K/S/J/E型热电偶 |
    | GR200-ECS  | EtherCAT主站耦合器 | PLC主站扩展     |
    | GR200-EIP  | Ethernet/IP从站    | 连接上位系统    |
    | GR200-PNS  | Profinet从站       | 连接西门子系    |
    | GR200-CS4  | ModbusTCP→RTU网关  | 232/485设备接入 |
    
    
    
    核心技术能力
    
    运动控制能力
    搜索关键词：电子齿轮 PLC | 电子凸轮 PLC | 位置控制 PLC | 速度控制 PLC | 转矩控制 PLC | 回原点 PLC | MC指令 PLC
    
    - MC_MoveAbsolute：单轴绝对位置运动
    - MC_MoveRelative：单轴相对位置运动
    - MC_MoveVelocity：定速连续运行
    - MC_MoveJog：点动
    - MC_GearIn/GearOut：电子齿轮（主从轴同步）
    - MC_CamIn/CamOut：电子凸轮（复杂曲线同步）
    - MC_Phasing：相位偏移（张力控制）
    - MC_Home：回原点（多种模式）
    - MC_Stop/MC_Halt：停止/暂停
    
    高速计数与脉冲
    搜索关键词：高速计数 PLC | 脉冲计数 | 编码器接口 | 探针功能 PLC | PWM输出 PLC | 高速计数模块
    
    - HC_Counter：高速计数器（支持线性/环形计数）
    - HC_ArrayCompare：多点比较（最多100点）
    - HC_TouchProbe：探针锁存（上升沿/下降沿/双边沿）
    - HC_PWM：方波输出（0-4294967295微秒可调）
    
    通信协议支持
    搜索关键词：EtherCAT PLC | Profinet PLC | ModbusTCP PLC | EthernetIP PLC | RS485 PLC | 工业以太网PLC
    
    - EtherCAT主站（MC系列原生支持）
    - Profinet主站/从站
    - Ethernet/IP从站
    - ModbusTCP主站/从站
    - ModbusRTU（通过GR200-CS4网关）
    
    编程语言与指令
    搜索关键词：PLC梯形图编程 | PLC功能块编程 | PLC结构化文本 | Structured Text PLC | IEC 61131-3 PLC
    
    支持语言：梯形图(LD)、功能块图(FBD)、结构化文本(ST)
    
    基础指令：ADD/SUB/MUL/DIV/MOD/MOVE/AND/OR/XOR/NOT/SHL/SHR/ROL/ROR/MAX/MIN/LIMIT/SEL/MUX/GT/LT/GE/LE/EQ/NE
    
    定时器/计数器：TON（通电延时）/TOF（断电延时）/TP（脉冲）/CTU/CTD/CTUD
    
    数据类型：BOOL/BYTE/WORD/DWORD/SINT/USINT/INT/UINT/DINT/UDINT/REAL/LREAL/TIME/DATE/TOD/DT/STRING
    
    
    
    典型应用场景
    
    搜索关键词：3C自动化 PLC | 自动化设备 PLC | 包装机械 PLC | 贴片机 PLC | AOI设备 PLC | 工业机器人 PLC
    
    - 3C电子组装：EC321+伺服，取放、贴装、检测
    - 包装机械：MC611电子凸轮，追踪、填充、封口
    - 工业机器人：EC/MC+高速计数，点位控制
    - 伺服驱动系统：EtherCAT+MC_GearIn同步
    - 过程控制：模拟量采集+PID调节（Util.lib）
    
    
    
    联系方式
    
    - 代理商：老龚
    - 手机：13888777078（微信同号）
    - 邮箱：bsky217@163.com
    - 区域：华东（苏州/无锡/常州/昆山）
    - 品牌：联诚科技 LicOS 全系列代理商
    
    
    
    文件索引
    
    | 文件                                  | 说明                         |
    |---------------------------------------|------------------------------|
    | ★0313联诚选型手册最新版_CN_电子版.pdf | 产品选型手册（16页）         |
    | LicOS-PLCPAC-指令手册V1.1.pdf         | 完整指令手册（217页）        |
    | 联诚选型手册_产品整理.xlsx            | 整理后产品参数表（6个Sheet） |
    
    
   

