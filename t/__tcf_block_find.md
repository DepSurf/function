# Function: <code>__tcf_block_find</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff8195d4b0)
Location: net/sched/cls_api.c:1241
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff8195d4b0-ffffffff8195d52e: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819939b0)
Location: net/sched/cls_api.c:1155
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819939b0-ffffffff81993a2e: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a6cd90)
Location: net/sched/cls_api.c:1118
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a6cd90-ffffffff81a6ce4c: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a75740)
Location: net/sched/cls_api.c:1119
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a75740-ffffffff81a757fc: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a5dd60)
Location: net/sched/cls_api.c:1119
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a5dd60-ffffffff81a5de3d: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b16f20)
Location: net/sched/cls_api.c:1120
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81b16f20-ffffffff81b16ffd: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81c9e950)
Location: net/sched/cls_api.c:1137
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81c9e950-ffffffff81c9ea76: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5b100)
Location: net/sched/cls_api.c:1139
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81e5b100-ffffffff81e5b226: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81eb6ec0)
Location: net/sched/cls_api.c:1244
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81eb6ec0-ffffffff81eb6fe6: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f79c60)
Location: net/sched/cls_api.c:1246
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81f79c60-ffffffff81f79d86: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c40760)
Location: net/sched/cls_api.c:1155
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffff800010c40760-ffff800010c40864: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d52ab8)
Location: net/sched/cls_api.c:1155
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c0d52ab8-c0d52b70: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3b6a0)
Location: net/sched/cls_api.c:1155
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c000000000d3b6a0-c000000000d3b7b8: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b0096)
Location: net/sched/cls_api.c:1155
Inline: True
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffe0007b0096-ffffffe0007b0130: __tcf_block_find (STB_LOCAL)
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
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81933820)
Location: net/sched/cls_api.c:1155
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81933820-ffffffff8193389e: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ed320)
Location: net/sched/cls_api.c:1155
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818ed320-ffffffff818ed39e: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819849b0)
Location: net/sched/cls_api.c:1155
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819849b0-ffffffff81984a2e: __tcf_block_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tcf_block *__tcf_block_find(struct net *net, struct Qdisc *q, long unsigned int cl, int ifindex, u32 block_index, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819a71a0)
Location: net/sched/cls_api.c:1155
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819a71a0-ffffffff819a721e: __tcf_block_find (STB_LOCAL)
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
