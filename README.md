### 如何用代码实现一个龙与魔法的游戏世界的（极简）规则？

https://zhuanlan.zhihu.com/p/373294034

#### 基础配置如下：

 * 玩家（Player）可以是战士（Fighter）、法师（Mage）、龙骑（Dragoon）
 * 怪物（Monster）可以是兽人（Orc）、精灵（Elf）、龙（Dragon），怪物有血量
 * 武器（Weapon）可以是剑（Sword）、法杖（Staff），武器有攻击力
 * 玩家可以装备一个武器，武器攻击可以是物理类型（0），火（1），冰（2）等，武器类型决定伤害类型。攻击规则如下：


 * 兽人对物理攻击伤害减半
 * 精灵对魔法攻击伤害减半
 * 龙对物理和魔法攻击免疫，除非玩家是龙骑，则伤害加倍

#### 加一个限制条件：

战士只能装备剑
法师只能装备法杖

#### 规则增加再一条：

战士和法师都能装备匕首（dagger）
