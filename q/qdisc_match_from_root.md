# Function: <code>qdisc_match_from_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81744860)
Location: net/sched/sch_api.c:260
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup
  - net/sched/sch_api.c:qdisc_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817b16e0)
Location: net/sched/sch_api.c:258
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_lookup
  - net/sched/sch_api.c:qdisc_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817deb50)
Location: net/sched/sch_api.c:259
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup
  - net/sched/sch_api.c:qdisc_lookup
```
**Symbols:**

```
ffffffff817deb50-ffffffff817debb4: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff817fe180)
Location: net/sched/sch_api.c:268
Inline: False
```
**Symbols:**

```
ffffffff817fe180-ffffffff817fe1f4: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187bda0)
Location: net/sched/sch_api.c:262
Inline: False
```
**Symbols:**

```
ffffffff8187bda0-ffffffff8187be14: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818ce5c0)
Location: net/sched/sch_api.c:262
Inline: False
```
**Symbols:**

```
ffffffff818ce5c0-ffffffff818ce636: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818f9810)
Location: net/sched/sch_api.c:261
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff818f9810-ffffffff818f9883: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81959080)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81959080-ffffffff819590e8: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8198f520)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff8198f520-ffffffff8198f588: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a67400)
Location: net/sched/sch_api.c:259
Inline: False
Direct callers:
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
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81a67400-ffffffff81a6745c: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a6fb20)
Location: net/sched/sch_api.c:259
Inline: False
Direct callers:
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
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81a6fb20-ffffffff81a6fb7f: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a58410)
Location: net/sched/sch_api.c:259
Inline: False
Direct callers:
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
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81a58410-ffffffff81a5846c: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81b113f0)
Location: net/sched/sch_api.c:259
Inline: False
Direct callers:
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
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81b113f0-ffffffff81b1144e: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81c984e0)
Location: net/sched/sch_api.c:259
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
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
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_tree_reduce_backlog
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81c984e0-ffffffff81c98556: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e54480)
Location: net/sched/sch_api.c:261
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
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
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81e54480-ffffffff81e544f6: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eafd20)
Location: net/sched/sch_api.c:261
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
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
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81eafd20-ffffffff81eafd96: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f72790)
Location: net/sched/sch_api.c:261
Inline: False
Direct callers:
  - net/sched/sch_api.c:tc_dump_tclass_root
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
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81f72790-ffffffff81f72806: qdisc_match_from_root (STB_LOCAL)
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
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3b3e0)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffff800010c3b3e0-ffff800010c3b490: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4d190)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
c0d4d190-c0d4d234: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d34540)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
c000000000d34540-c000000000d34614: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ac086)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffe0007ac086-ffffffe0007ac11a: qdisc_match_from_root (STB_LOCAL)
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
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8192f390)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff8192f390-ffffffff8192f3f8: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818e8e90)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff818e8e90-ffffffff818e8ef8: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81980520)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff81980520-ffffffff81980588: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct Qdisc *qdisc_match_from_root(struct Qdisc *root, u32 handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a2a90)
Location: net/sched/sch_api.c:257
Inline: False
Direct callers:
  - net/sched/sch_api.c:qdisc_lookup_rcu
  - net/sched/sch_api.c:qdisc_lookup_rcu
```
**Symbols:**

```
ffffffff819a2a90-ffffffff819a2af8: qdisc_match_from_root (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
