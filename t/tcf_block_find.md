# Function: <code>tcf_block_find</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block *tcf_block_find(struct net *net, struct Qdisc **q, u32 *parent, long unsigned int *cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818d2f00)
Location: net/sched/cls_api.c:444
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818d2f00-ffffffff818d30b3: tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block *tcf_block_find(struct net *net, struct Qdisc **q, u32 *parent, long unsigned int *cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818fe180)
Location: net/sched/cls_api.c:865
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818fe180-ffffffff818fe43a: tcf_block_find (STB_LOCAL)
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
In net/sched/cls_api.c (ffffffff819608ae)
Location: net/sched/cls_api.c:1315
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff8199798e)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a7145f)
Location: net/sched/cls_api.c:1192
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a79edf)
Location: net/sched/cls_api.c:1193
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81a62fe4)
Location: net/sched/cls_api.c:1193
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81b1c354)
Location: net/sched/cls_api.c:1194
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81ca1c32)
Location: net/sched/cls_api.c:1211
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81e5e4ac)
Location: net/sched/cls_api.c:1213
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81ebc194)
Location: net/sched/cls_api.c:1318
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff81f7f373)
Location: net/sched/cls_api.c:1320
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffff800010c44a2c)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (c0d563f4)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (c000000000d4166c)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffe0007b3982)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff819377fe)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff818f12fe)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff8198898e)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
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
In net/sched/cls_api.c (ffffffff819abc8e)
Location: net/sched/cls_api.c:1229
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
