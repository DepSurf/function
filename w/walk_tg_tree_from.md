# Function: <code>walk_tg_tree_from</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa830)
Location: kernel/sched/core.c:775
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810aa830-ffffffff810aa8f0: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad470)
Location: kernel/sched/core.c:693
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810ad470-ffffffff810ad530: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3570)
Location: kernel/sched/core.c:700
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810b3570-ffffffff810b3630: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af4b0)
Location: kernel/sched/core.c:699
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810af4b0-ffffffff810af570: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6780)
Location: kernel/sched/core.c:701
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810b6780-ffffffff810b6847: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc564)
Location: kernel/sched/core.c:679
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810bace0-ffffffff810bad94: walk_tg_tree_from.part.67 (STB_LOCAL)
ffffffff810be7a0-ffffffff810be7b0: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4d44)
Location: kernel/sched/core.c:668
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810c4230-ffffffff810c42e4: walk_tg_tree_from.part.68 (STB_LOCAL)
ffffffff810c79a0-ffffffff810c79b0: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ce250)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810ce250-ffffffff810ce304: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7e50)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
**Symbols:**

```
ffffffff810d7e50-ffffffff810d7f04: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df2d2)
Location: kernel/sched/core.c:712
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810e2090-ffffffff810e2144: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbf72)
Location: kernel/sched/core.c:801
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810df430-ffffffff810df4e4: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddf92)
Location: kernel/sched/core.c:811
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810e10c0-ffffffff810e1174: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f2c44)
Location: kernel/sched/core.c:1165
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810f7110-ffffffff810f71c4: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110ea20)
Location: kernel/sched/core.c:1235
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff811135c0-ffffffff81113689: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811357e0)
Location: kernel/sched/core.c:1223
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff8113a700-ffffffff8113a7c9: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81144939)
Location: kernel/sched/core.c:1245
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff81149aa0-ffffffff81149b69: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114fe81)
Location: kernel/sched/core.c:1290
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
Direct callers:
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff811555a0-ffffffff81155669: walk_tg_tree_from (STB_GLOBAL)
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
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010138550)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
**Symbols:**

```
ffff800010138550-ffff800010138610: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0387200)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
**Symbols:**

```
c0387200-c03872b8: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001841d0)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
**Symbols:**

```
c0000000001841d0-c0000000001842d0: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8504)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
**Symbols:**

```
ffffffe0000e8504-ffffffe0000e8580: walk_tg_tree_from (STB_GLOBAL)
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
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2320)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810d2320-ffffffff810d23d4: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c0960)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
**Symbols:**

```
ffffffff810c0960-ffffffff810c0a14: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d00d0)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
  - kernel/sched/rt.c:sched_rt_handler
  - kernel/sched/rt.c:tg_set_rt_bandwidth
```
**Symbols:**

```
ffffffff810d00d0-ffffffff810d0184: walk_tg_tree_from (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_tg_tree_from(struct task_group *from, tg_visitor down, tg_visitor up, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9a40)
Location: kernel/sched/core.c:710
Inline: False
Direct callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/fair.c:unthrottle_cfs_rq
  - kernel/sched/fair.c:throttle_cfs_rq
```
**Symbols:**

```
ffffffff810d9a40-ffffffff810d9af4: walk_tg_tree_from (STB_GLOBAL)
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
