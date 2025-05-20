# Function: <code>compound_pincount_ptr</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/debug.c (0)
Location: include/linux/mm_types.h:229
Inline: True
```
```
In mm/gup.c (ffffffff81287de5)
Location: include/linux/mm_types.h:229
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
  - mm/gup.c:unpin_user_page
  - mm/gup.c:__unpin_devmap_managed_user_page
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:229
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:229
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:229
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/gup.c (ffffffff812919e2)
Location: include/linux/mm_types.h:232
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm_types.h:232
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/gup.c (ffffffff81296d02)
Location: include/linux/mm_types.h:232
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm_types.h:232
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm_types.h:232
Inline: True
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
In mm/vmscan.c (0)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In mm/debug.c (0)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In mm/gup.c (ffffffff812d76af)
Location: include/linux/mm_types.h:247
Inline: True
Inline callers:
  - mm/gup.c:put_compound_head
```
```
In mm/memory.c (0)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm_types.h:247
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/mm_types.h:247
Inline: True
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
In mm/debug.c (0)
Location: include/linux/mm_types.h:309
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/mm_types.h:309
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:309
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/mm_types.h:309
Inline: True
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
In mm/debug.c (0)
Location: include/linux/mm_types.h:446
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/mm_types.h:446
Inline: True
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
