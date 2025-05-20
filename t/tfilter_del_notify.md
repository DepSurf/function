# Function: <code>tfilter_del_notify</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8188112f)
Location: net/sched/cls_api.c:657
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d40a3)
Location: net/sched/cls_api.c:1009
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81900b1a)
Location: net/sched/cls_api.c:1455
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819616ba)
Location: net/sched/cls_api.c:1913
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81998823)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
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
In net/sched/cls_api.c (ffffffff81a6d8f0)
Location: net/sched/cls_api.c:1880
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81a6d8f0-ffffffff81a6da48: tfilter_del_notify.constprop.0 (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff81a762b0)
Location: net/sched/cls_api.c:1882
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81a762b0-ffffffff81a76408: tfilter_del_notify.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a619e8)
Location: net/sched/cls_api.c:1883
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b1abf8)
Location: net/sched/cls_api.c:1878
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca3920)
Location: net/sched/cls_api.c:1897
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5f2d3)
Location: net/sched/cls_api.c:1899
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ebaa51)
Location: net/sched/cls_api.c:2054
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tfilter_del_notify(struct net *net, struct sk_buff *oskb, struct nlmsghdr *n, struct tcf_proto *tp, struct tcf_block *block, struct Qdisc *q, u32 parent, void *fh, bool *last, bool rtnl_held, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7a920)
Location: net/sched/cls_api.c:2107
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
**Symbols:**

```
ffffffff81f7a920-ffffffff81f7ab31: tfilter_del_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c456f0)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d57298)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d42984)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b4538)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81938693)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f2193)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81989823)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819acbe3)
Location: net/sched/cls_api.c:1858
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_del_tfilter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
