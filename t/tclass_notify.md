# Function: <code>tclass_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tclass_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, struct Qdisc *q, long unsigned int cl, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81743a10)
Location: net/sched/sch_api.c:1698
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81743a10-ffffffff81743ac7: tclass_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tclass_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, struct Qdisc *q, long unsigned int cl, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b0870)
Location: net/sched/sch_api.c:1700
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff817b0870-ffffffff817b0927: tclass_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tclass_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, struct Qdisc *q, long unsigned int cl, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817dffb0)
Location: net/sched/sch_api.c:1733
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff817dffb0-ffffffff817e0067: tclass_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tclass_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, struct Qdisc *q, long unsigned int cl, int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817ff5e0)
Location: net/sched/sch_api.c:1751
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff817ff5e0-ffffffff817ff698: tclass_notify (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff8187d360)
Location: net/sched/sch_api.c:1590
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff8187d360-ffffffff8187d410: tclass_notify.constprop.33 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff818cf980)
Location: net/sched/sch_api.c:1728
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818cf980-ffffffff818cfa31: tclass_notify.isra.35.constprop.38 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff818fad10)
Location: net/sched/sch_api.c:1825
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818fad10-ffffffff818fadc1: tclass_notify.isra.37.constprop.41 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff8195a5e0)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff8195a5e0-ffffffff8195a6a8: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff81990a80)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81990a80-ffffffff81990b48: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a68bc0)
Location: net/sched/sch_api.c:1841
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81a68bc0-ffffffff81a68c78: tclass_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a712e0)
Location: net/sched/sch_api.c:1842
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81a712e0-ffffffff81a71398: tclass_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a59ab0)
Location: net/sched/sch_api.c:1842
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81a59ab0-ffffffff81a59b65: tclass_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b12b70)
Location: net/sched/sch_api.c:1849
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81b12b70-ffffffff81b12c1e: tclass_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9b140)
Location: net/sched/sch_api.c:1840
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81c9b140-ffffffff81c9b202: tclass_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e57610)
Location: net/sched/sch_api.c:1858
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81e57610-ffffffff81e576d2: tclass_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb3680)
Location: net/sched/sch_api.c:1932
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81eb3680-ffffffff81eb374a: tclass_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f76372)
Location: net/sched/sch_api.c:1961
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
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
In net/sched/sch_api.c (ffff800010c3ccf8)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffff800010c3ccf8-ffff800010c3cdcc: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (c0d4ea88)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
c0d4ea88-c0d4eb40: tclass_notify.constprop.0 (STB_LOCAL)
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
In net/sched/sch_api.c (c000000000d37e40)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
c000000000d37e40-c000000000d37f64: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffe0007ad516)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffe0007ad516-ffffffe0007ad5cc: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff819308f0)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff819308f0-ffffffff819309b8: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff818ea3f0)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff818ea3f0-ffffffff818ea4b8: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff81981a80)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff81981a80-ffffffff81981b48: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
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
In net/sched/sch_api.c (ffffffff819a3fe0)
Location: net/sched/sch_api.c:1831
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
```
**Symbols:**

```
ffffffff819a3fe0-ffffffff819a40a8: tclass_notify.isra.0.constprop.0 (STB_LOCAL)
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
</ul>
