# Function: <code>tcf_chain_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81802471)
Location: net/sched/cls_api.c:726
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_dump_tfilter
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
In net/sched/cls_api.c (ffffffff81880530)
Location: net/sched/cls_api.c:949
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81880530-ffffffff818806ee: tcf_chain_dump.isra.17 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff818d32b0)
Location: net/sched/cls_api.c:1423
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff818d32b0-ffffffff818d3496: tcf_chain_dump.isra.37 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff818fe7f0)
Location: net/sched/cls_api.c:1885
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff818fe7f0-ffffffff818fe9f5: tcf_chain_dump.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195f570)
Location: net/sched/cls_api.c:2483
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff8195f570-ffffffff8195f7d9: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81996890)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81996890-ffffffff81996af9: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6e570)
Location: net/sched/cls_api.c:2471
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81a6e570-ffffffff81a6e7eb: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a76d80)
Location: net/sched/cls_api.c:2472
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81a76d80-ffffffff81a76ffb: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5f6f0)
Location: net/sched/cls_api.c:2473
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81a5f6f0-ffffffff81a5f96a: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b18900)
Location: net/sched/cls_api.c:2473
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81b18900-ffffffff81b18b7a: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9fbd0)
Location: net/sched/cls_api.c:2492
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81c9fbd0-ffffffff81c9fe7b: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5dc90)
Location: net/sched/cls_api.c:2496
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81e5dc90-ffffffff81e5df3b: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb86c0)
Location: net/sched/cls_api.c:2652
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81eb86c0-ffffffff81eb896d: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index, bool terse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7b790)
Location: net/sched/cls_api.c:2704
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81f7b790-ffffffff81f7ba3d: tcf_chain_dump (STB_LOCAL)
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
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c431e0)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffff800010c431e0-ffff800010c4342c: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d56a70)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
c0d56a70-c0d56ce8: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d41d40)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
c000000000d41d40-c000000000d42040: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b3e7a)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffe0007b3e7a-ffffffe0007b4068: tcf_chain_dump (STB_LOCAL)
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
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81936700)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81936700-ffffffff81936969: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f0200)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff818f0200-ffffffff818f0469: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81987890)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81987890-ffffffff81987af9: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tcf_chain_dump(struct tcf_chain *chain, struct Qdisc *q, u32 parent, struct sk_buff *skb, struct netlink_callback *cb, long int index_start, long int *p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819ac330)
Location: net/sched/cls_api.c:2447
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff819ac330-ffffffff819ac599: tcf_chain_dump (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool terse</code>
</li>
</ul>
</details>
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
