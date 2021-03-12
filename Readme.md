## 一个用于查询基金的telegram机器人

### 部署：

请将telebot文件夹下的credentials.simple.py文件重命名为credentials.py，并在其中添加telegrambot的信息；

## 命令：

- “query 基金代号” 查询指定基金的单位净值及涨跌幅, 可同时查询多个基金
- “record 基金代号” 记录基金号, 可同时记录多个基金
- “delete 基金代号” 删除记录的基金代号，可同时删除多个基金
- “buy 基金代号 购入金额 购入份数” 记录买入操作，可以同时添加多个买入记录
- “sell 基金代号 卖出金额 卖出份数” 记录卖出操作，可以同时添加多个卖出记录
- “sell 基金代号 all” 记录指定基金的清仓，可以同时进行多个基金的清仓
- “sell all” 同时记录全部基金的清仓
- “list my hold” 列出目前所有的持仓记录
- “delete all/clean” 清除所有的记录
- “list record” 列出目前所有记录
- “add schedule 分钟数” 增加一个定时器，在周一到周五的9点到15点之间按指定的间隔自动查询
- “remove schedule id” 删除一个定时器
- “list schedule” 列出所有的定时器
- “help” 显示命令帮助

PS：本bot会默认生成一个于周一到周五的每天14点50分运行的定时器，用于自动查询收盘前的涨跌幅

