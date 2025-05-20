# Function: <code>inc_lruvec_page_state</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c764e)
Location: include/linux/memcontrol.h:1021
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
```
In mm/workingset.c (ffffffff811ee521)
Location: include/linux/memcontrol.h:1021
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dc47d)
Location: include/linux/memcontrol.h:1033
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
```
In mm/workingset.c (ffffffff81204871)
Location: include/linux/memcontrol.h:1033
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fe72b)
Location: include/linux/memcontrol.h:1126
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
```
In mm/workingset.c (ffffffff81225638)
Location: include/linux/memcontrol.h:1126
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
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
In mm/page-writeback.c (ffffffff8120f01e)
Location: include/linux/memcontrol.h:1210
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffff8121eb9f)
Location: include/linux/memcontrol.h:1221
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffff8122c63f)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffff81259f4f)
Location: include/linux/memcontrol.h:1233
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089b0f)
Location: include/linux/vmstat.h:545
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/page-writeback.c (ffffffff81265700)
Location: include/linux/vmstat.h:545
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
```
In mm/memory.c (ffffffff8129cf15)
Location: include/linux/vmstat.h:545
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a7d6)
Location: include/linux/vmstat.h:533
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/page-writeback.c (ffffffff8126a1fb)
Location: include/linux/vmstat.h:533
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
```
In mm/memory.c (ffffffff812a25f5)
Location: include/linux/vmstat.h:533
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81099d56)
Location: include/linux/vmstat.h:546
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/page-writeback.c (ffffffff812a6e8e)
Location: include/linux/vmstat.h:546
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
```
In mm/memory.c (ffffffff812e3965)
Location: include/linux/vmstat.h:546
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810acd85)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff81344d1d)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c6e15)
Location: include/linux/vmstat.h:624
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff813bcf4d)
Location: include/linux/vmstat.h:624
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ca565)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pte_alloc_one
```
```
In mm/memory.c (ffffffff813f1c8d)
Location: include/linux/vmstat.h:630
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/page-writeback.c (ffff8000102bbf54)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (c04e6f90)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (c00000000037385c)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffe0001de1b2)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffff81224c8f)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffff81217e3f)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffff81222a2f)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
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
In mm/page-writeback.c (ffffffff81231c0f)
Location: include/linux/memcontrol.h:1273
Inline: True
Inline callers:
  - mm/page-writeback.c:__test_set_page_writeback
```
</details>
</li>
</ul>

## Differences
