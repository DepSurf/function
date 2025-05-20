# Function: <code>tcf_generic_walker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct sk_buff *skb, struct netlink_callback *cb, int type, struct tc_action *a);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817481b0)
Location: net/sched/act_api.c:166
Inline: True
```
**Symbols:**

```
ffffffff817481b0-ffffffff817485e2: tcf_generic_walker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817b5340)
Location: net/sched/act_api.c:160
Inline: True
```
**Symbols:**

```
ffffffff817b5340-ffffffff817b5702: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff817e4d40)
Location: net/sched/act_api.c:166
Inline: True
```
**Symbols:**

```
ffffffff817e4d40-ffffffff817e5102: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81804910)
Location: net/sched/act_api.c:193
Inline: True
```
**Symbols:**

```
ffffffff81804910-ffffffff81804c66: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81883620)
Location: net/sched/act_api.c:205
Inline: True
```
**Symbols:**

```
ffffffff81883620-ffffffff81883984: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818d7070)
Location: net/sched/act_api.c:241
Inline: True
```
**Symbols:**

```
ffffffff818d7070-ffffffff818d73d7: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81903400)
Location: net/sched/act_api.c:301
Inline: True
```
**Symbols:**

```
ffffffff81903400-ffffffff819037af: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (ffffffff819648ca)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffffffff81965659-ffffffff8196568d: tcf_generic_walker.cold (STB_LOCAL)
ffffffff81964580-ffffffff81964953: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8199b0e0)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffffffff8199b0e0-ffffffff8199b4bc: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a74690)
Location: net/sched/act_api.c:331
Inline: True
```
**Symbols:**

```
ffffffff81a74690-ffffffff81a746e6: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7d480)
Location: net/sched/act_api.c:383
Inline: True
```
**Symbols:**

```
ffffffff81a7d480-ffffffff81a7d4d6: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a661d0)
Location: net/sched/act_api.c:395
Inline: True
```
**Symbols:**

```
ffffffff81a661d0-ffffffff81a66232: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81b1f490)
Location: net/sched/act_api.c:395
Inline: True
```
**Symbols:**

```
ffffffff81b1f490-ffffffff81b1f4f2: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/act_api.c (ffffffff81ca71e1)
Location: net/sched/act_api.c:639
Inline: True
```
**Symbols:**

```
ffffffff81f05af4-ffffffff81f05b0c: tcf_generic_walker.cold (STB_LOCAL)
ffffffff81ca70c0-ffffffff81ca7316: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81e63620)
Location: net/sched/act_api.c:640
Inline: True
Direct callers:
  - net/sched/act_api.c:__tcf_generic_walker
```
**Symbols:**

```
ffffffff81e63620-ffffffff81e6388e: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81ebf6d0)
Location: net/sched/act_api.c:635
Inline: True
Direct callers:
  - net/sched/act_api.c:__tcf_generic_walker
```
**Symbols:**

```
ffffffff81ebf6d0-ffffffff81ebf93e: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81f82850)
Location: net/sched/act_api.c:635
Inline: True
Direct callers:
  - net/sched/act_api.c:__tcf_generic_walker
```
**Symbols:**

```
ffffffff81f82850-ffffffff81f82ae8: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c482b8)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffff800010c482b8-ffff800010c4868c: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d59300)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
c0d59300-c0d596fc: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c000000000d455e0)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
c000000000d455e0-c000000000d45b60: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffe0007b5d60)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffffffe0007b5d60-ffffffe0007b605a: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8193af50)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffffffff8193af50-ffffffff8193b32c: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff818f4a50)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffffffff818f4a50-ffffffff818f4e2c: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff8198c0e0)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffffffff8198c0e0-ffffffff8198c4bc: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tcf_generic_walker(struct tc_action_net *tn, struct sk_buff *skb, struct netlink_callback *cb, int type, const struct tc_action_ops *ops, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff819ae970)
Location: net/sched/act_api.c:327
Inline: True
```
**Symbols:**

```
ffffffff819ae970-ffffffff819aed4c: tcf_generic_walker (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tc_action_net *tn</code>
</li>
<li>
<b>Param added. </b>
<code>const struct tc_action_ops *ops</code>
</li>
<li>
<b>Param removed. </b>
<code>struct tc_action *a</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, cb, type, a</code> ➡️ <code>tn, skb, cb, type, ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
