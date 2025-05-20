# Function: <code>tc_dump_tclass_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817435c0)
Location: net/sched/sch_api.c:1761
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff817435c0-ffffffff81743665: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b0460)
Location: net/sched/sch_api.c:1763
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff817b0460-ffffffff817b0505: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817dfb60)
Location: net/sched/sch_api.c:1798
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff817dfb60-ffffffff817dfc43: tc_dump_tclass_root (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff817ff19c)
Location: net/sched/sch_api.c:1816
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff817fefe0-ffffffff817ff104: tc_dump_tclass_root.part.28 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff8187ce2c)
Location: net/sched/sch_api.c:1878
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff8187cc70-ffffffff8187cd94: tc_dump_tclass_root.part.29 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff818cf6bc)
Location: net/sched/sch_api.c:2021
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff818cf500-ffffffff818cf624: tc_dump_tclass_root.part.33 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff818fa5ac)
Location: net/sched/sch_api.c:2119
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff818fa3f0-ffffffff818fa51c: tc_dump_tclass_root.part.28 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff81959e5f)
Location: net/sched/sch_api.c:2136
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81959ca0-ffffffff81959dca: tc_dump_tclass_root.part.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff819902ff)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81990140-ffffffff8199026a: tc_dump_tclass_root.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a67c80)
Location: net/sched/sch_api.c:2167
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81a67c80-ffffffff81a67da5: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t, bool recur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a70380)
Location: net/sched/sch_api.c:2168
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81a70380-ffffffff81a704a9: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t, bool recur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a58c80)
Location: net/sched/sch_api.c:2169
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81a58c80-ffffffff81a58da9: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t, bool recur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b11c90)
Location: net/sched/sch_api.c:2170
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81b11c90-ffffffff81b11de7: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t, bool recur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c98f50)
Location: net/sched/sch_api.c:2161
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81c98f50-ffffffff81c990bc: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t, bool recur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e54e30)
Location: net/sched/sch_api.c:2175
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81e54e30-ffffffff81e54f9c: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t, bool recur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb06e0)
Location: net/sched/sch_api.c:2249
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81eb06e0-ffffffff81eb084c: tc_dump_tclass_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t, bool recur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f73150)
Location: net/sched/sch_api.c:2306
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81f73150-ffffffff81f732bc: tc_dump_tclass_root (STB_LOCAL)
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
In net/sched/sch_api.c (ffff800010c3c948)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffff800010c3c118-ffff800010c3c26c: tc_dump_tclass_root.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tc_dump_tclass_root(struct Qdisc *root, struct sk_buff *skb, struct tcmsg *tcm, struct netlink_callback *cb, int *t_p, int s_t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4df74)
Location: net/sched/sch_api.c:2157
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
c0d4df74-c0d4e0a8: tc_dump_tclass_root (STB_LOCAL)
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
In net/sched/sch_api.c (c000000000d3671c)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
c000000000d35cd0-c000000000d35eac: tc_dump_tclass_root.part.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffe0007ad2fc)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffe0007ad1ac-ffffffe0007ad294: tc_dump_tclass_root.part.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff8193016f)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff8192ffb0-ffffffff819300da: tc_dump_tclass_root.part.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff818e9c6f)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff818e9ab0-ffffffff818e9bda: tc_dump_tclass_root.part.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff819812ff)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff81981140-ffffffff8198126a: tc_dump_tclass_root.part.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff819a387f)
Location: net/sched/sch_api.c:2157
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass
  - net/sched/sch_api.c:tc_dump_tclass
```
**Symbols:**

```
ffffffff819a36c0-ffffffff819a37ea: tc_dump_tclass_root.part.0 (STB_LOCAL)
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
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool recur</code>
</li>
</ul>
</details>
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
