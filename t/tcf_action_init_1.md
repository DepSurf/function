# Function: <code>tcf_action_init_1</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81747c70)
Location: net/sched/act_api.c:504
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81747c70-ffffffff81747e52: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b4e10)
Location: net/sched/act_api.c:521
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff817b4e10-ffffffff817b4fd8: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e4760)
Location: net/sched/act_api.c:551
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff817e4760-ffffffff817e498a: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818040c0)
Location: net/sched/act_api.c:602
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff818040c0-ffffffff81804584: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81882dd0)
Location: net/sched/act_api.c:618
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81882dd0-ffffffff8188329e: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d6780)
Location: net/sched/act_api.c:638
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff818d6780-ffffffff818d6c47: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81902a90)
Location: net/sched/act_api.c:812
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81902a90-ffffffff81902fd3: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81963ce0)
Location: net/sched/act_api.c:834
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81963ce0-ffffffff81964182: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199a860)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff8199a860-ffffffff8199ace2: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a73ac0)
Location: net/sched/act_api.c:905
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81a73ac0-ffffffff81a73f73: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, struct tc_action_ops *a_o, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7c950)
Location: net/sched/act_api.c:992
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81a7c950-ffffffff81a7cc20: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, struct tc_action_ops *a_o, int *init_res, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a65600)
Location: net/sched/act_api.c:1005
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81a65600-ffffffff81a65957: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, struct tc_action_ops *a_o, int *init_res, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1e810)
Location: net/sched/act_api.c:1014
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81b1e810-ffffffff81b1eaca: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, struct tc_action_ops *a_o, int *init_res, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca6270)
Location: net/sched/act_api.c:1337
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ca6270-ffffffff81ca6561: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, struct tc_action_ops *a_o, int *init_res, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e62750)
Location: net/sched/act_api.c:1363
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81e62750-ffffffff81e62a41: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, struct tc_action_ops *a_o, int *init_res, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebe7e0)
Location: net/sched/act_api.c:1358
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81ebe7e0-ffffffff81ebead1: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, struct tc_action_ops *a_o, int *init_res, u32 flags, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f81950)
Location: net/sched/act_api.c:1390
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate_ex
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff81f81950-ffffffff81f81c7a: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c47ae0)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffff800010c47ae0-ffff800010c47e90: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d58b60)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
c0d58b60-c0d58f24: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d44ad0)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
c000000000d44ad0-c000000000d45024: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b5762)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffe0007b5762-ffffffe0007b5a6c: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193a6d0)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff8193a6d0-ffffffff8193ab52: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f41d0)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff818f41d0-ffffffff818f4652: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198b860)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff8198b860-ffffffff8198bce2: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tc_action *tcf_action_init_1(struct net *net, struct tcf_proto *tp, struct nlattr *nla, struct nlattr *est, char *name, int ovr, int bind, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ae0d0)
Location: net/sched/act_api.c:842
Inline: False
Direct callers:
  - net/sched/cls_api.c:tcf_exts_validate
  - net/sched/act_api.c:tcf_action_init
```
**Symbols:**

```
ffffffff819ae0d0-ffffffff819ae552: tcf_action_init_1 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tcf_proto *tp</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, nla, est, name, ovr, bind</code> ➡️ <code>net, tp, nla, est, name, ovr, bind</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, tp, nla, est, name, ovr, bind, extack</code> ➡️ <code>net, tp, nla, est, name, ovr, bind, rtnl_held, extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tc_action_ops *a_o</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, tp, nla, est, name, ovr, bind, rtnl_held, extack</code> ➡️ <code>net, tp, nla, est, name, ovr, bind, a_o, rtnl_held, extack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *init_res</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, tp, nla, est, name, ovr, bind, a_o, rtnl_held, extack</code> ➡️ <code>net, tp, nla, est, name, ovr, bind, a_o, init_res, rtnl_held, extack</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>int ovr</code>
</li>
<li>
<b>Param removed. </b>
<code>int bind</code>
</li>
<li>
<b>Param removed. </b>
<code>bool rtnl_held</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, tp, nla, est, name, ovr, bind, a_o, init_res, rtnl_held, extack</code> ➡️ <code>net, tp, nla, est, a_o, init_res, flags, extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
