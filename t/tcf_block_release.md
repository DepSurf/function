# Function: <code>tcf_block_release</code>

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
void tcf_block_release(struct Qdisc *q, struct tcf_block *block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818ffe50)
Location: net/sched/cls_api.c:976
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818ffe50-ffffffff818ffe87: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819607a0)
Location: net/sched/cls_api.c:1349
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819607a0-ffffffff819607ee: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81997880)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81997880-ffffffff819978ce: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a713e2)
Location: net/sched/cls_api.c:1226
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a6f8d0-ffffffff81a6f91e: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a79e62)
Location: net/sched/cls_api.c:1227
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a782d0-ffffffff81a7831e: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81a63182)
Location: net/sched/cls_api.c:1227
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81a61100-ffffffff81a6114e: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81b1c4f2)
Location: net/sched/cls_api.c:1228
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81b1a310-ffffffff81b1a35e: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ca1dd1)
Location: net/sched/cls_api.c:1245
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81ca14d0-ffffffff81ca1538: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81e5e64b)
Location: net/sched/cls_api.c:1247
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81e5d550-ffffffff81e5d5b8: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81ebc3f3)
Location: net/sched/cls_api.c:1352
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81eba110-ffffffff81eba178: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81f7f610)
Location: net/sched/cls_api.c:1354
Inline: True
Inline callers:
  - net/sched/cls_api.c:tc_ctl_chain
Direct callers:
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81f7d380-ffffffff81f7d3e8: tcf_block_release (STB_LOCAL)
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
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffff800010c44900)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffff800010c44900-ffff800010c44978: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c0d551cc)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c0d551cc-c0d55230: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (c000000000d3fc40)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
c000000000d3fc40-c000000000d3fcf0: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffe0007b2948)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffe0007b2948-ffffffe0007b29b4: tcf_block_release (STB_LOCAL)
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
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819376f0)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819376f0-ffffffff8193773e: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff818f11f0)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff818f11f0-ffffffff818f123e: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff81988880)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff81988880-ffffffff819888ce: tcf_block_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcf_block_release(struct Qdisc *q, struct tcf_block *block, bool rtnl_held);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/cls_api.c (ffffffff819aa800)
Location: net/sched/cls_api.c:1263
Inline: False
Direct callers:
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_ctl_chain
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
```
**Symbols:**

```
ffffffff819aa800-ffffffff819aa84e: tcf_block_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool rtnl_held</code>
</li>
</ul>
</details>
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
