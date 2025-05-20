# Function: <code>tc_fill_tclass</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81743760)
Location: net/sched/sch_api.c:1652
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tclass_notify
```
**Symbols:**

```
ffffffff81743760-ffffffff817439cc: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b0600)
Location: net/sched/sch_api.c:1654
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tclass_notify
```
**Symbols:**

```
ffffffff817b0600-ffffffff817b082b: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817dfd40)
Location: net/sched/sch_api.c:1687
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tclass_notify
```
**Symbols:**

```
ffffffff817dfd40-ffffffff817dff6b: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817ff3a0)
Location: net/sched/sch_api.c:1705
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tclass_notify
```
**Symbols:**

```
ffffffff817ff3a0-ffffffff817ff5a0: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187d110)
Location: net/sched/sch_api.c:1544
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff8187d110-ffffffff8187d316: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818cf730)
Location: net/sched/sch_api.c:1682
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818cf730-ffffffff818cf932: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818faad0)
Location: net/sched/sch_api.c:1779
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818faad0-ffffffff818faccc: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff8195a380-ffffffff8195a598: tc_fill_tclass (STB_LOCAL)
ffffffff8195cefd-ffffffff8195cf18: tc_fill_tclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81990820)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81990820-ffffffff81990a38: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a68960)
Location: net/sched/sch_api.c:1795
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81a68960-ffffffff81a68b78: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1796
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81a71070-ffffffff81a7129a: tc_fill_tclass (STB_LOCAL)
ffffffff81c3217d-ffffffff81c32195: tc_fill_tclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1796
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81a59840-ffffffff81a59a68: tc_fill_tclass (STB_LOCAL)
ffffffff81c24467-ffffffff81c2447f: tc_fill_tclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1803
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81b12900-ffffffff81b12b28: tc_fill_tclass (STB_LOCAL)
ffffffff81d38f6e-ffffffff81d38f86: tc_fill_tclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1794
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81c9aea0-ffffffff81c9b0ee: tc_fill_tclass (STB_LOCAL)
ffffffff81f0585c-ffffffff81f05874: tc_fill_tclass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e57330)
Location: net/sched/sch_api.c:1812
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81e57330-ffffffff81e57596: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb3350)
Location: net/sched/sch_api.c:1881
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81eb3350-ffffffff81eb3605: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f75e60)
Location: net/sched/sch_api.c:1910
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81f75e60-ffffffff81f76115: tc_fill_tclass (STB_LOCAL)
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
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3cac0)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffff800010c3cac0-ffff800010c3cc9c: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4e830)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
c0d4e830-c0d4ea2c: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d37b80)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
c000000000d37b80-c000000000d37dfc: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ad36a)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffe0007ad36a-ffffffe0007ad4cc: tc_fill_tclass (STB_LOCAL)
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
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81930690)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81930690-ffffffff819308a8: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818ea190)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818ea190-ffffffff818ea3a8: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81981820)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81981820-ffffffff81981a38: tc_fill_tclass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_fill_tclass(struct sk_buff *skb, struct Qdisc *q, long unsigned int cl, u32 portid, u32 seq, u16 flags, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a3da0)
Location: net/sched/sch_api.c:1785
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_class_dump
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff819a3da0-ffffffff819a3f92: tc_fill_tclass (STB_LOCAL)
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
