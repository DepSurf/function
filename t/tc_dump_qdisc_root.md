# Function: <code>tc_dump_qdisc_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81743e40)
Location: net/sched/sch_api.c:1430
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81743e40-ffffffff81743f90: tc_dump_qdisc_root.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b0e50)
Location: net/sched/sch_api.c:1432
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff817b0e50-ffffffff817b0fa0: tc_dump_qdisc_root.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e0590)
Location: net/sched/sch_api.c:1450
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff817e0590-ffffffff817e0723: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817ffa00)
Location: net/sched/sch_api.c:1456
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff817ffa00-ffffffff817ffb8b: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187d7a0)
Location: net/sched/sch_api.c:1433
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff8187d7a0-ffffffff8187d92b: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818cfff0)
Location: net/sched/sch_api.c:1571
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff818cfff0-ffffffff818d018c: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fb230)
Location: net/sched/sch_api.c:1667
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff818fb230-ffffffff818fb3cc: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195ac60)
Location: net/sched/sch_api.c:1673
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff8195ac60-ffffffff8195ae16: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81991110)
Location: net/sched/sch_api.c:1673
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81991110-ffffffff819912c6: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a69120)
Location: net/sched/sch_api.c:1683
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81a69120-ffffffff81a692d3: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a71860)
Location: net/sched/sch_api.c:1684
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81a71860-ffffffff81a71a13: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a5a220)
Location: net/sched/sch_api.c:1684
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81a5a220-ffffffff81a5a3d3: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b13350)
Location: net/sched/sch_api.c:1690
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81b13350-ffffffff81b13529: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c99f30)
Location: net/sched/sch_api.c:1681
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81c99f30-ffffffff81c9a14f: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e56290)
Location: net/sched/sch_api.c:1699
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81e56290-ffffffff81e564af: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb2650)
Location: net/sched/sch_api.c:1768
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81eb2650-ffffffff81eb2875: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f75100)
Location: net/sched/sch_api.c:1797
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81f75100-ffffffff81f75325: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3d5a0)
Location: net/sched/sch_api.c:1673
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffff800010c3d5a0-ffff800010c3d75c: tc_dump_qdisc_root.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4f0bc)
Location: net/sched/sch_api.c:1673
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
c0d4f0bc-c0d4f27c: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (c000000000d36ed0)
Location: net/sched/sch_api.c:1673
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
c000000000d36ed0-c000000000d37140: tc_dump_qdisc_root.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ada02)
Location: net/sched/sch_api.c:1673
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffe0007ada02-ffffffe0007adb46: tc_dump_qdisc_root.isra.0 (STB_LOCAL)
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
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81930f80)
Location: net/sched/sch_api.c:1673
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81930f80-ffffffff81931136: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818eaa80)
Location: net/sched/sch_api.c:1673
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff818eaa80-ffffffff818eac36: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81982110)
Location: net/sched/sch_api.c:1673
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff81982110-ffffffff819822c6: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_dump_qdisc_root(struct Qdisc *root, struct sk_buff *skb, struct netlink_callback *cb, int *q_idx_p, int s_q_idx, bool recur, bool dump_invisible);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a4650)
Location: net/sched/sch_api.c:1673
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc
  - net/sched/sch_api.c:tc_dump_qdisc
```
**Symbols:**

```
ffffffff819a4650-ffffffff819a4806: tc_dump_qdisc_root (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dump_invisible</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
