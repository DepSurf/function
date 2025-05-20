# Function: <code>tc_dump_tclass_qdisc</code>

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
In net/sched/sch_api.c (ffffffff817434c0)
Location: net/sched/sch_api.c:1732
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
```
**Symbols:**

```
ffffffff817434c0-ffffffff817435ba: tc_dump_tclass_qdisc.isra.24 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff817b0360)
Location: net/sched/sch_api.c:1734
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
```
**Symbols:**

```
ffffffff817b0360-ffffffff817b045a: tc_dump_tclass_qdisc.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff817dfa60)
Location: net/sched/sch_api.c:1769
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
```
**Symbols:**

```
ffffffff817dfa60-ffffffff817dfb5a: tc_dump_tclass_qdisc.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff817fea60)
Location: net/sched/sch_api.c:1787
Inline: True
```
**Symbols:**

```
ffffffff817fea60-ffffffff817feb5d: tc_dump_tclass_qdisc.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187c6e0)
Location: net/sched/sch_api.c:1849
Inline: True
```
**Symbols:**

```
ffffffff8187c6e0-ffffffff8187c7e3: tc_dump_tclass_qdisc.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818cef50)
Location: net/sched/sch_api.c:1992
Inline: True
```
**Symbols:**

```
ffffffff818cef50-ffffffff818cf04e: tc_dump_tclass_qdisc.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fa2f0)
Location: net/sched/sch_api.c:2090
Inline: True
```
**Symbols:**

```
ffffffff818fa2f0-ffffffff818fa3ee: tc_dump_tclass_qdisc.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81959b90)
Location: net/sched/sch_api.c:2107
Inline: True
```
**Symbols:**

```
ffffffff81959b90-ffffffff81959c93: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81990030)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
ffffffff81990030-ffffffff81990133: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a679b0)
Location: net/sched/sch_api.c:2138
Inline: False
```
**Symbols:**

```
ffffffff81a679b0-ffffffff81a67ab1: tc_dump_tclass_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a700c0)
Location: net/sched/sch_api.c:2139
Inline: False
```
**Symbols:**

```
ffffffff81a700c0-ffffffff81a701c1: tc_dump_tclass_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a589c0)
Location: net/sched/sch_api.c:2140
Inline: False
```
**Symbols:**

```
ffffffff81a589c0-ffffffff81a58ac1: tc_dump_tclass_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b119d0)
Location: net/sched/sch_api.c:2141
Inline: False
```
**Symbols:**

```
ffffffff81b119d0-ffffffff81b11ad1: tc_dump_tclass_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c98e10)
Location: net/sched/sch_api.c:2132
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
```
**Symbols:**

```
ffffffff81c98e10-ffffffff81c98f49: tc_dump_tclass_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e54ce0)
Location: net/sched/sch_api.c:2146
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
```
**Symbols:**

```
ffffffff81e54ce0-ffffffff81e54e19: tc_dump_tclass_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb0590)
Location: net/sched/sch_api.c:2220
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
```
**Symbols:**

```
ffffffff81eb0590-ffffffff81eb06cd: tc_dump_tclass_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f73000)
Location: net/sched/sch_api.c:2277
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
  - net/sched/sch_api.c:tc_dump_tclass_root
```
**Symbols:**

```
ffffffff81f73000-ffffffff81f7313d: tc_dump_tclass_qdisc (STB_LOCAL)
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
In net/sched/sch_api.c (ffff800010c3bfe0)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
ffff800010c3bfe0-ffff800010c3c118: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_dump_tclass_qdisc(struct Qdisc *q, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4d940)
Location: net/sched/sch_api.c:2128
Inline: False
```
**Symbols:**

```
c0d4d940-c0d4da70: tc_dump_tclass_qdisc (STB_LOCAL)
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
In net/sched/sch_api.c (c000000000d35b60)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
c000000000d35b60-c000000000d35cc4: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffe0007ad0d4)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
ffffffe0007ad0d4-ffffffe0007ad1ac: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff8192fea0)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
ffffffff8192fea0-ffffffff8192ffa3: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff818e99a0)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
ffffffff818e99a0-ffffffff818e9aa3: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81981030)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
ffffffff81981030-ffffffff81981133: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a35b0)
Location: net/sched/sch_api.c:2128
Inline: True
```
**Symbols:**

```
ffffffff819a35b0-ffffffff819a36b3: tc_dump_tclass_qdisc.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
