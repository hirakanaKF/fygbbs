# 2025/01/24 #
降低遇到对手“随机对手近日无胜...”的情况，需要1小时左右起效（这个就是遇到纯PVE玩家了，对方没有近期PVP数据）。<br>
翻牌现在需要获得3枚狗牌。<br>
PVP和PVE胜利都可以获得1狗牌。<br>
现在根据段位内人数动态调整对手强度。<br>
例：SSS段标准人数100人，实际人数假设150人，PVP时对手+1强化等级。<br>
例2：BBB段标准人数500人，实际人数假设300人，PVP时自身+4强化等级。<br>
增加了PVE时野怪动态升/降级的速率，让它的等级能更迅速的匹配实时胜率。<br>

# 2025/01/13 #
现在无需狗牌就可以直接翻牌（临时，结束时间不定）<br>

# 2025/01/12 #
PVP改为影子对战，随机到的对手是“该玩家最后一场胜利的配置”（不再是该玩家当前配置），主动出击无论胜负都不再影响对手进度。<br>
PVE对战目前无法获得狗牌，但依然可以获得进度。<br>
每日翻牌现在需要至少3块狗牌才能开启（原1块）。<br>
PVP胜败进度改为增减3%（原增减5%）。<br>
升段自动获得10%进度，掉段则掉至90%进度（原升1%，掉99%）。<br><br>
进入咕咕镇增加了一个广告页面，这是原本外站的最后一个广告，在沟通后，将广告移动至这边，保证了外站0广告。<br>
（外站9月就撤销广告，而这边现在才添加这个广告，是因为个人原因离线了2个多月，鸽了人家一点点时间。）<br>

# 2024/09/16 #
修复“加点后战斗数据不刷新”的BUG。<br><br>
影子数据开始记录，待数据确认无误后，下一个更新，PVP只会匹配到影子对手。<br>
系统会记录每个玩家的特定一场战斗属性为该玩家的影子数据，PVP有人匹配到这位玩家时，就会和这个影子属性战斗，而非该玩家的实时属性。影子胜败不影响玩家。<br>
直观的说就是下一个更新后，不需要再考虑防守问题，只靠主动出击的胜负来决定段位升降，降低PVP烈度。<br>
注：影子数据的记录规则需要规避各种送分互刷的可能（早年发生过的事），所以需要对采集规则进行数据分析，所以本更新被拆分，先做采集。<br>

# 2024/08/21 #
等级融合，所有（包括以后的新增）卡片现在均统一等级、经验、品质、技能位、成长值。<br>
本次更新后第一次登录时会自动匹配自己所有卡片数值，取每一项的最高值为自己的融合结果。<br>
例：我有8张卡片，最高850级、最低200级，最高10%品质最低4%品质，融合后取全卡片850级10%品质。<br><br>

角色卡片等级上限增加为900级（测试阶段，暂时上限只加50）。<br>
争夺战斗可以获得升级经验，PVP比PVE多，胜利比失败多，段位高比段位低多。<br>
所有角色卡片在战斗时都能获得成长值，所有卡片成长值通用。<br>
当前成长值超过20W时，无法获得新的成长值增长。<br><br>

800级以下经验+400%加成。<br>
暂停灵魂药水使用，暂时无法获得品质和技能位的提升。<br><br>

光环天赋“天降花盆”改为判定“攻击方”，对防御方无效。<br><br>

PVP匹配改为“5分钟战斗（PVP/PVE）后5分钟内不会遇到被动PVP”，原“战斗同一时段（小时）内不会遇到被动PVP”。<br><br>

修正光环“致命节奏”的文字描述错误。<br>

# 2024/07/21 #
光环天赋“启程之风”、“等级挑战”、“等级压制”，对应改为“致命节奏”、“往返车票”、“天降花盆”。<br>
新的三个光环天赋属于规则天赋，双方任意一人携带时即生效。<br>
由于规则天赋属于“预设对自己有利的战场”，暂定120天赋需求。<br><br>
许愿池“强化启程之风”改为“增加仓库格子 每级+3”。<br>
红石对仓库格子的加成（预）取消。<br>
当前过渡期实际保留最大效果，如果自己红石对仓库的加成更大，就按红石加成生效。反之按照许愿格子生效。<br>

# 2024/06/15 #
修正，暴击时有1%概率不触发（装备、天赋、角色技能）对应的暴击效果。<br>
许愿池两个黄色词条（生命值上限/护盾值上限）增加阶段性奖励。<br>

# 2024/06/14 #
许愿池中“强化我的饰品容量”，在黄色词条每满100时，自动加一级，不再需要抽取。<br>
说明：如果玩家本词条的“当前等级”大于“黄色词条除以100”，则以更大的那个数字为准，直到黄色词条追上来。<br>


# 2024/06/13 #
修正许愿池的天赋加成效果无法在防守方生效的BUG。<br>
天赋“鲜血渴望”原描述错误文字修正“...10%的回血效果...”，新增“...10%的回盾效果”。<br><br>
往期更新说明：“减治疗/护盾的最小值为-100%”是最终效果不能低于-100%，举例“5000回血不会因为最终-110%减治疗，而导致每回合-500血”，这是一个防溢出设定，只针对极端情况。<br>


# 2024/06/12 #
修正最终暴击概率被降低1%的BUG。<br>
修正最终技能概率被降低1%的BUG。<br>


# 2024/06/11 #
去掉一个错误出现的调试数据。<br>
现在减治疗/护盾的最小值为-100%，而非之前的无下限。<br>
许愿池前2个词条（附加物理/魔法伤害）增加阶段性奖励。<br>
<br>
<span class="text-muted">家里大人又发烧了一个，不确定是被孩子传染还是上班被传染，又是深夜从医院回家的一天，我昨天就睡了2个半小时，今天没有战斗力熬到3点多了，于是许愿池只能拆开更新了。。</span><br>

# 2024/06/10 #
"艾"的技能“星火宝石”增加新效果“每次攻击降低对方1%的物理/魔法伤害”。<br>
说明：对艾的尝试性改动，保守为主，所以本效果暂不受星火层数影响，无法被匕首的神秘属性加成。<br><br>
“薇”的技能“闪避突袭”改为“主动技能触发概率+10%...”，原“主动技能触发概率+固定10%(不可抵消)...”。<br>
说明：+10%是指“战斗前计算双方实际技能触发几率后，增加概率的0.1倍”，例如技能几率为70%，则增加后为77%。<br><br>
护身符属性“固定技能几率”改名为“技能几率加成”，效果同上，改为对实际技能触发几率的倍数加成。<br><br>
装备属性“生命偷取”的等级提升效果改为“基础%+每20级+1%”，原“基础%+每15级+1%”。<br>
生命偷取需要本人登录后数据刷新，所以PVP可能遇到对手属性未刷新的情况，这个刷新的老问题后续更新，对不起！<br>
<br>
<span class="text-muted">今天医生再次加计量孩子还是高烧不退，晚上回家喂药从8点到0点，更新只能这么点了。</span><br>

# 2024/06/09 #
吸血机制改动，当前吸血机制改为“计算自己的本回合被防御前伤害”（原计算对方实际掉血掉盾），物理伤害计算生命回复，魔法伤害计算护盾回复，绝对伤害同时计算。新机制尝试期间为避免数值爆炸，整体降低50%吸血效果。<br>
<br>
“霞”的技能“澄空之心”改为“...每(5000成长值)增加1%魔法攻击和1%最大护盾值...”，原“...增加(成长值x1)的最大护盾值...”。<br>
“默”的技能“抗拒接触”改为“护盾能量最大值+25%...”，原“护盾能量最大值+40%...”。<br>
“琳”的技能“爆裂双刃”改为“造成(220%物理攻击力)的物理伤害和(220%物理攻击力)的魔法伤害”，原“造成(300%物理攻击力)的物理伤害和(300%物理攻击力)的魔法伤害”。<br>
<br>
装备“反叛者的刺杀弓”神秘属性改为“攻击附带(对方当前护盾值\*18%)的物理伤害”，原“攻击附带(对方当前护盾值\*30%)的物理伤害”。<br>
装备“饮血魔剑”神秘属性改为“攻击附带(对方当前生命值\*18%)的魔法伤害”，原“攻击附带(对方当前生命值\*30%)的魔法伤害”。<br>
<br>
<span class="text-muted">今天孩子挂号换了个主任，发现之前用药有点问题，又很晚才从医院回来，今天依然无法做许愿池的阶段奖励，明天再这样就把许愿池的阶段奖励拆开一条条的更新。</span><br>

# 2024/06/08 #
“希”的技能“残忍冲动”改为“吸血+10%...”，原“生命值+10%...”。<br>
“希”的技能“血之狂暴”改为“每(2000成长值)增加1%最大生命值...”，原“增加(成长值x1)的最大生命值...”。<br>
<br>
<span class="text-muted">许愿池今天本来是要加阶段性奖励的，晚上九点才从医院回来，只能先这么多了。</span><br>

# 2024/06/07 #
修复装备“凶神耳环”的神秘效果不对“雅”生效的BUG。<br>
增加许愿池基础属性的上限。<br><br>
尝试一下新的更新方式，最近一段时间会为了防鸽每天都做小幅度更新（当天写多少更多少，避免未完成计划就无限鸽），但由于本地文件这几个月为更新做了很多改动，如果一些未完成更新的被错误放出变成BUG，请提出让我修正。<br>
为了避免意外，每次更新都会在定时备份之外再做一次手动全站备份，避免恶性BUG无最后一秒数据回档，所以虽然更新很小，但每次更新停机时间都会比较长。<br>

# 2024/04/23 #
战斗记录不再显示对手装备。<br>
装备“凶神耳环”的第三条属性描述错误修正。<br>
装备“凶神耳环”的神秘效果不再能在“雅”以外的角色生效。<br>

# 2024/02/27 #
装备“折光戒指”第四条属性整体降低28.5%。<br>
天赋“荧光护盾”改为“受到的伤害减免20%”，原“受到的物理/魔法伤害减免20%”。<br>
"命"的“恩赐解脱”改为“计算暴击后伤害提升55%”，原“计算暴击后伤害提升65%”。<br>
2-3周后开始测试PVE，这段时间内只有微调。<br>

# 2024/01/29 -2 #
修正争夺等级加成的上限显示错误，实际加成是没有此错误的。<br>

# 2024/01/29 #
重写争夺等级加成，现在加成不再限定加点方式，而是等级达到则自动满足所有加成。<br>
本次改动为临时过渡，暂时去掉一些不可控的极端加成，后续会改为天赋选择的形式。<br>
PS：依然准备PVE模式中，PVE会是一个更加挂机的模式，甚至不需要每天进入咕咕镇。<br>

