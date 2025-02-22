# 开放注册规则

DAS 账户作为一种公共资源，应避免在社会影响力不足时被少数人所囤积。DAS 账户注册采取逐步开放的策略。

| 账户字符长度 | 开放注册规则 |
| :--- | :--- |
| 10位及以上 | 全部开放注册。 |
| 4～9位 | 上线当日开放5%；9 月 17 日 2:00 (UTC+0) 开放至 35 %；剩余的 65% 将在 24 周内逐步开放。 逐步开放规则如下：从 9 月 26 日起，每周日的 00:00 (UTC+0) 开始开放，周日当天每整点开放一批，24 周后释放完毕。（即每周日 00:00、01:00、02:00、...、23:00 会有一批 DAS 账户开放） |
| 1~3位 | 待定。 |

账户的可注册时间，由[公开的算法](https://github.com/DeAccountSystems/das-contracts/blob/fca9bfafb79950c7c5d4a86cb379f114b0188ccd/contracts/pre-account-cell-type/src/entry.rs#L579-L584)计算而来，取决于账户名本身。你可以在注册页面搜索某个账户，获取它的可注册时间。

