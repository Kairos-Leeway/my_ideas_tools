# 突发灵感开发的一些小工具, 目前有HTML(打开即用, 轻量\方便), 后续可能有更多....
需要网络，因为js是通过CDN引入的，有前端基础的同学也可以自己修改成离线版
### DNF金币汇率计算

  因为自己玩DNF, 群里很多人买卖金币都需要计算汇率, 我只知道在一些交易网站能算, 但是只能算固定比例的, 而且点来点去进到页面很麻烦, 加载页面也得花时间!
  所以开发了现在这个点开即用的HTML工具

![image](https://github.com/user-attachments/assets/1c856ba8-58d5-48d7-9fee-4c0a7e81291b)


### 信息记录工具
一开始觉得这个越做越像低配版的Excel, 甚至不如Excel的一毛, 所以, 经过和ChatGPT的深入讨论, 对代码改了N版, 也接入了AI, 目前我自己用的是DeepSeek

- 功能描述: 历史记录、新建记录、保存记录、AI对记录分析、自定义扩展类型的列等、数据备份和恢复（数据是存在前端localStorage中的，导出为json）

- 做这个也是因为玩DNF, 觉得很多东西(比如材料,消耗品,竞拍币啥的我不知道哪些角色身上有)太多太乱了, 所以想着记一下, 否则要找来找去, 有时候找到了, 用掉了, 自己之后可能又忘记了

直接上图吧：
#### 概览：
![image](https://github.com/user-attachments/assets/62939b4a-a585-49b9-a3dd-0176aff8f2b6)

#### 自定义扩展列:
目前加上的列的扩展类型不是很多, 可以自定义列名, 列类型, 列顺序等等

![image](https://github.com/user-attachments/assets/045f72b5-61db-44b8-a65d-3db557b6d083)



加完之后的demo效果:
![image](https://github.com/user-attachments/assets/8604c828-a844-43e1-a764-4f073ae40fd1)



#### 上面提到的为了DNF做的事情:
玩完了就记一下(当然, 所有的列都是可以自定义的, 这个 应该会有用吧 哈哈😅):
如果有的同学能定义出很实用的记录页面, 不妨也分享一下备份文件!~~~~
![image](https://github.com/user-attachments/assets/b994778f-c0df-4a8d-9659-09c4eefa8c37)


#### AI部分：
- 比如工作方面，每天记录一下，到了周报日让deepseek总结😁
![image](https://github.com/user-attachments/assets/a3ff5306-8cc5-44f8-8796-21042f2bdba8)
