# Function: <code>tc_chain_notify</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fec10)
Location: net/sched/cls_api.c:2079
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff818fec10-ffffffff818fed0d: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195e610)
Location: net/sched/cls_api.c:2691
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff8195e610-ffffffff8195e710: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81994ee0)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81994ee0-ffffffff81994fe0: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6dc10)
Location: net/sched/cls_api.c:2691
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81a6dc10-ffffffff81a6dd0f: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a765e0)
Location: net/sched/cls_api.c:2692
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81a765e0-ffffffff81a766df: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5e4e0)
Location: net/sched/cls_api.c:2693
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81a5e4e0-ffffffff81a5e5dc: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b176c0)
Location: net/sched/cls_api.c:2693
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81b176c0-ffffffff81b177b0: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9f480)
Location: net/sched/cls_api.c:2712
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81c9f480-ffffffff81c9f5aa: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5b6d0)
Location: net/sched/cls_api.c:2716
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81e5b6d0-ffffffff81e5b7fa: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb7e30)
Location: net/sched/cls_api.c:2878
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81eb7e30-ffffffff81eb7f5d: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7ae40)
Location: net/sched/cls_api.c:2931
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81f7ae40-ffffffff81f7afa4: tc_chain_notify (STB_LOCAL)
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
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c41a50)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffff800010c41a50-ffff800010c41b6c: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d53884)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
c0d53884-c0d53970: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3d790)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
c000000000d3d790-c000000000d3d904: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b13b6)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffe0007b13b6-ffffffe0007b149a: tc_chain_notify (STB_LOCAL)
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
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81934d50)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81934d50-ffffffff81934e50: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ee850)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff818ee850-ffffffff818ee950: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81985ee0)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff81985ee0-ffffffff81985fe0: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tc_chain_notify(struct tcf_chain *chain, struct sk_buff *oskb, u32 seq, u16 flags, int event, bool unicast);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a8ee0)
Location: net/sched/cls_api.c:2655
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:__tcf_chain_get
```
**Symbols:**

```
ffffffff819a8ee0-ffffffff819a8fe0: tc_chain_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
