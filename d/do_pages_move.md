# Function: <code>do_pages_move</code>

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
In mm/migrate.c (ffffffff811f2c0b)
Location: mm/migrate.c:1314
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
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
In mm/migrate.c (ffffffff81212892)
Location: mm/migrate.c:1495
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81224a9c)
Location: mm/migrate.c:1504
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81230187)
Location: mm/migrate.c:1492
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124de17)
Location: mm/migrate.c:1590
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
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
In mm/migrate.c (ffffffff812719b3)
Location: mm/migrate.c:1563
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
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
In mm/migrate.c (ffffffff81285fd3)
Location: mm/migrate.c:1596
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a04f0)
Location: mm/migrate.c:1591
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812a04f0-ffffffff812a0a5d: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b1890)
Location: mm/migrate.c:1594
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812b1890-ffffffff812b1e61: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e7150)
Location: mm/migrate.c:1634
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812e7150-ffffffff812e7354: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f26d0)
Location: mm/migrate.c:1755
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812f26d0-ffffffff812f28b0: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f8a70)
Location: mm/migrate.c:1737
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812f8a70-ffffffff812f8c57: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81343110)
Location: mm/migrate.c:1781
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff81343110-ffffffff81343316: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b58b0)
Location: mm/migrate.c:1711
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff813b58b0-ffffffff813b5b4d: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814359b0)
Location: mm/migrate.c:1821
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff814359b0-ffffffff81435c5e: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8146b6c0)
Location: mm/migrate.c:2157
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8146b6c0-ffffffff8146b921: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8149a660)
Location: mm/migrate.c:2173
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8149a660-ffffffff8149a8fc: do_pages_move (STB_LOCAL)
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
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010351ea0)
Location: mm/migrate.c:1594
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffff800010351ea0-ffff8000103525c8: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000438740)
Location: mm/migrate.c:1594
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
c000000000438740-c000000000438f14: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a9e70)
Location: mm/migrate.c:1594
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812a9e70-ffffffff812aa441: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129b7d0)
Location: mm/migrate.c:1594
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff8129b7d0-ffffffff8129bda1: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7c80)
Location: mm/migrate.c:1594
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812a7c80-ffffffff812a8251: do_pages_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_pages_move(struct mm_struct *mm, nodemask_t task_nodes, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b7f80)
Location: mm/migrate.c:1594
Inline: False
Direct callers:
  - mm/migrate.c:kernel_move_pages
```
**Symbols:**

```
ffffffff812b7f80-ffffffff812b8551: do_pages_move (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
