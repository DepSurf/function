# Function: <code>queue_pages_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811dfd50)
Location: mm/mempolicy.c:634
Inline: False
Direct callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff811dfd50-ffffffff811dfddb: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811fe390)
Location: mm/mempolicy.c:666
Inline: False
Direct callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff811fe390-ffffffff811fe41b: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8120f020)
Location: mm/mempolicy.c:668
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff8120f020-ffffffff8120f0ab: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121a8a0)
Location: mm/mempolicy.c:602
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff8121a8a0-ffffffff8121a92b: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81235ae0)
Location: mm/mempolicy.c:644
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff81235ae0-ffffffff81235b6b: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81258c50)
Location: mm/mempolicy.c:619
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff81258c50-ffffffff81258cdb: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126d040)
Location: mm/mempolicy.c:645
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff8126d040-ffffffff8126d0cb: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812884b0)
Location: mm/mempolicy.c:672
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff812884b0-ffffffff8128853b: queue_pages_range (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff8129c07f)
Location: mm/mempolicy.c:680
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff812cfe80)
Location: mm/mempolicy.c:742
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff812db916)
Location: mm/mempolicy.c:742
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff812e3193)
Location: mm/mempolicy.c:742
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff8132a581)
Location: mm/mempolicy.c:723
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff81399ec7)
Location: mm/mempolicy.c:727
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff81419ef5)
Location: mm/mempolicy.c:728
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist, bool lock_vma);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81449160)
Location: mm/mempolicy.c:747
Inline: True
Inline callers:
  - mm/mempolicy.c:migrate_to_node
Direct callers:
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff81447fa0-ffffffff8144802c: queue_pages_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int queue_pages_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, nodemask_t *nodes, long unsigned int flags, struct list_head *pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81481980)
Location: mm/mempolicy.c:726
Inline: False
Direct callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
```
**Symbols:**

```
ffffffff81481980-ffffffff81481a2d: queue_pages_range (STB_LOCAL)
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
In mm/mempolicy.c (ffff80001033b0a8)
Location: mm/mempolicy.c:680
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000415ad8)
Location: mm/mempolicy.c:680
Inline: True
Inline callers:
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:migrate_to_node
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129465f)
Location: mm/mempolicy.c:680
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff8128626f)
Location: mm/mempolicy.c:680
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff8129246f)
Location: mm/mempolicy.c:680
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
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
In mm/mempolicy.c (ffffffff812a22d0)
Location: mm/mempolicy.c:680
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:migrate_to_node
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool lock_vma</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
</ul>
