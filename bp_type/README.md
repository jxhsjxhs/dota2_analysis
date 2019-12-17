###  获取方法

```
1.拿出所有英雄的id 以及名字 以及类型 做好字典
https://api.opendota.com/api/heroes

备注
Strength: 力量 : str 
Agility: 敏捷 : agi 
Intelligence:   智力 : int

2.首先拿到前100战队的 id 以及名字,全部拿出来本地做好数据查询功能
https://api.opendota.com/api/teams
3.拿到战队id 查战队近期的比赛,拿出比赛的id以及比赛的时间的数组
https://api.opendota.com/api/teams/1838315/matches
4.拿出具体战队的比赛id以及 比赛bp英雄的类型
https://api.opendota.com/api/matches/5158231096
关键字为 
radiant_team_id
dire_team_id
draft_timings
最好是用firefox看
5.分析出前100名的战队的 bp的三个类型(力量,敏捷,智力)都有的百分比
```
