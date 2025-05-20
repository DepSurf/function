# Function: <code>tc_fill_qdisc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81743ad0)
Location: net/sched/sch_api.c:1331
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/sch_api.c:qdisc_notify
```
**Symbols:**

```
ffffffff81743ad0-ffffffff81743e31: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b0ac0)
Location: net/sched/sch_api.c:1332
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/sch_api.c:qdisc_notify
```
**Symbols:**

```
ffffffff817b0ac0-ffffffff817b0e4c: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e0200)
Location: net/sched/sch_api.c:1350
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/sch_api.c:qdisc_notify
```
**Symbols:**

```
ffffffff817e0200-ffffffff817e0588: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817ff6a0)
Location: net/sched/sch_api.c:1351
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/sch_api.c:qdisc_notify
```
**Symbols:**

```
ffffffff817ff6a0-ffffffff817ff9f6: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187d410)
Location: net/sched/sch_api.c:772
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/sch_api.c:qdisc_notify
```
**Symbols:**

```
ffffffff8187d410-ffffffff8187d79d: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818cfb50)
Location: net/sched/sch_api.c:789
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff818cfb50-ffffffff818cffee: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fadd0)
Location: net/sched/sch_api.c:876
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff818fadd0-ffffffff818fb226: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:867
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff8195a7c0-ffffffff8195ac57: tc_fill_qdisc (STB_LOCAL)
ffffffff8195cf2b-ffffffff8195cf46: tc_fill_qdisc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81990c70)
Location: net/sched/sch_api.c:867
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81990c70-ffffffff8199110e: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a68c80)
Location: net/sched/sch_api.c:876
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81a68c80-ffffffff81a6911e: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:878
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81a713a0-ffffffff81a71853: tc_fill_qdisc (STB_LOCAL)
ffffffff81c32195-ffffffff81c321ad: tc_fill_qdisc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:878
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81a59d60-ffffffff81a5a215: tc_fill_qdisc (STB_LOCAL)
ffffffff81c2447f-ffffffff81c24497: tc_fill_qdisc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:884
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81b12e30-ffffffff81b13348: tc_fill_qdisc (STB_LOCAL)
ffffffff81d38fbe-ffffffff81d39013: tc_fill_qdisc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:885
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81c99a70-ffffffff81c99f27: tc_fill_qdisc (STB_LOCAL)
ffffffff81f057bb-ffffffff81f057d3: tc_fill_qdisc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e55da0)
Location: net/sched/sch_api.c:904
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81e55da0-ffffffff81e56275: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb2120)
Location: net/sched/sch_api.c:912
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81eb2120-ffffffff81eb263c: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f74bd0)
Location: net/sched/sch_api.c:912
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_get_qdisc
```
**Symbols:**

```
ffffffff81f74bd0-ffffffff81f750ec: tc_fill_qdisc (STB_LOCAL)
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
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3d1c8)
Location: net/sched/sch_api.c:867
Inline: False
```
**Symbols:**

```
ffff800010c3d1c8-ffff800010c3d5a0: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4ec90)
Location: net/sched/sch_api.c:867
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:qdisc_notify
  - net/sched/sch_api.c:qdisc_notify
```
**Symbols:**

```
c0d4ec90-c0d4f0bc: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d369a0)
Location: net/sched/sch_api.c:867
Inline: False
```
**Symbols:**

```
c000000000d369a0-c000000000d36ec8: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ad6d0)
Location: net/sched/sch_api.c:867
Inline: False
```
**Symbols:**

```
ffffffe0007ad6d0-ffffffe0007ada02: tc_fill_qdisc (STB_LOCAL)
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
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81930ae0)
Location: net/sched/sch_api.c:867
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81930ae0-ffffffff81930f7e: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818ea5e0)
Location: net/sched/sch_api.c:867
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff818ea5e0-ffffffff818eaa7e: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81981c70)
Location: net/sched/sch_api.c:867
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff81981c70-ffffffff8198210e: tc_fill_qdisc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_fill_qdisc(struct sk_buff *skb, struct Qdisc *q, u32 clid, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a41d0)
Location: net/sched/sch_api.c:867
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_qdisc_root
  - net/sched/sch_api.c:tc_dump_qdisc_root
```
**Symbols:**

```
ffffffff819a41d0-ffffffff819a464e: tc_fill_qdisc (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
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
