# Function: <code>qdisc_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81744850)
Location: net/sched/sch_api.c:296
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff81744850-ffffffff817448e2: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b16d0)
Location: net/sched/sch_api.c:294
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff817b16d0-ffffffff817b1764: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817e0e50)
Location: net/sched/sch_api.c:298
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff817e0e50-ffffffff817e0e95: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81800390)
Location: net/sched/sch_api.c:306
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff81800390-ffffffff818003d5: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187e130)
Location: net/sched/sch_api.c:300
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/cls_api.c:tc_dump_tfilter
  - net/sched/cls_api.c:tc_ctl_tfilter
```
**Symbols:**

```
ffffffff8187e130-ffffffff8187e183: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818d0bc0)
Location: net/sched/sch_api.c:300
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff818d0bc0-ffffffff818d0c12: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fbf10)
Location: net/sched/sch_api.c:299
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff818fbf10-ffffffff818fbf62: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195b8c0)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff8195b8c0-ffffffff8195b913: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81991d70)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81991d70-ffffffff81991dc3: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a6a3a4)
Location: net/sched/sch_api.c:297
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81a6b560-ffffffff81a6b5b3: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a72ad4)
Location: net/sched/sch_api.c:298
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81a73d10-ffffffff81a73d63: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a5b5f0)
Location: net/sched/sch_api.c:298
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81a5c8b0-ffffffff81a5c903: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b147b0)
Location: net/sched/sch_api.c:298
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81b15a60-ffffffff81b15ab3: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c9b99f)
Location: net/sched/sch_api.c:298
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81c9ce40-ffffffff81c9ceb2: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e57ebb)
Location: net/sched/sch_api.c:300
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81e592a0-ffffffff81e59312: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb385d)
Location: net/sched/sch_api.c:300
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81eb4cd0-ffffffff81eb4d42: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f7628e)
Location: net/sched/sch_api.c:300
Inline: True
Inline callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
Direct callers:
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81f77990-ffffffff81f77a02: qdisc_lookup (STB_GLOBAL)
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
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3e328)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffff800010c3e328-ffff800010c3e394: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4fd48)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
c0d4fd48-c0d4fd9c: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d383a0)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
c000000000d383a0-c000000000d3844c: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ae3f0)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffe0007ae3f0-ffffffe0007ae454: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81931be0)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81931be0-ffffffff81931c33: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818eb6e0)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff818eb6e0-ffffffff818eb733: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81982d70)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff81982d70-ffffffff81982dc3: qdisc_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct Qdisc *qdisc_lookup(struct net_device *dev, u32 handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a52b0)
Location: net/sched/sch_api.c:295
Inline: True
Direct callers:
  - net/sched/sch_api.c:tc_ctl_tclass
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_modify_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:tc_get_qdisc
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_create
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/cls_api.c:tc_dump_chain
  - net/sched/cls_api.c:tc_dump_tfilter
```
**Symbols:**

```
ffffffff819a52b0-ffffffff819a5303: qdisc_lookup (STB_GLOBAL)
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
