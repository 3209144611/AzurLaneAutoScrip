# Alas修改版
- 修改战斗等待时长为三分钟，而非一分钟
- 将GamePageUnknownError和RequestHumanTakeover写入重启，重启一次后再运行上次未完成的任务如果依旧报错则抛出错误并用OnePush通知(如果有设置OnePush的话)