---
# 微服务改造之路经验与教训

回顾过去几年微服务改造之路，感慨颇深，其间经历的酸甜苦辣以及徘徊、纠结和妥协，不是身在其中真的很难体会。总之单体到微服务改造绝非某些微服务布道师或书本上讲的那样简单明了，引入一套微服务框架辅以一套微服务基础设施就能在企业中快速落地完成。下面是我对如何快速落地微服务架构改造几个重要因素的一些拙见：

- 时机很重要，技术架构需要具备一定的前瞻性给技术团队留足够的缓冲空间，当业务已经倒逼技术退无可退的时候，这就给后续不得已的架构升级埋下了更多的缺失规划、妥协方案、仓促落地的坑。
- 技术话事人的远见、决心和决断力，架构改造升级一定会有成本，人力不足、业务delay、线上不稳定时如何经受住来自老板、业务方等各个方面的压力；技术团队内部组织架构调整时的各种阻力；长期架构升级成果与短期业务绩效的妥协和抉择。
- 技术团队内部（至少leader层面）达成初步共识，技术团队应该对微服务架构应该形成相对一致的画面感，充分认识到业务改造升级中面临的各种困难和代价。
- 架构升级落地步骤的制定，落地方案需要充分考虑公司的业务、技术现状与近期规划。
- 把架构升级工作当做技术团队的核心任务来抓落地进度，三天打鱼两天晒网不仅仅影响进度更会打击技术团队成员对完成架构升级的自信心。
- 工欲善其事，必先利其器，打造一套符合公司业务和技术现状的微服务架构和基础设施，尤其是要充分关注底层技术人员的需求。
