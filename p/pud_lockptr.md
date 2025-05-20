# Function: <code>pud_lockptr</code>

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
In mm/gup.c (0)
Location: include/linux/mm.h:1842
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1842
Inline: True
```
```
In mm/huge_memory.c (ffffffff812345ac)
Location: include/linux/mm.h:1842
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:1944
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:1944
Inline: True
```
```
In mm/huge_memory.c (ffffffff812524ac)
Location: include/linux/mm.h:1944
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:2033
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2033
Inline: True
```
```
In mm/huge_memory.c (ffffffff812768c5)
Location: include/linux/mm.h:2033
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2103
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2103
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128b7d5)
Location: include/linux/mm.h:2103
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2098
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2098
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a63e5)
Location: include/linux/mm.h:2098
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b78b5)
Location: include/linux/mm.h:2070
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2341
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2341
Inline: True
```
```
In mm/huge_memory.c (ffffffff812eca75)
Location: include/linux/mm.h:2341
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:2357
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2357
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:2357
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f7b13)
Location: include/linux/mm.h:2357
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:2365
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2365
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:2365
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fe0c3)
Location: include/linux/mm.h:2365
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:2394
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2394
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:2394
Inline: True
```
```
In mm/huge_memory.c (ffffffff81347c63)
Location: include/linux/mm.h:2394
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:2472
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2472
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:2472
Inline: True
```
```
In mm/huge_memory.c (ffffffff813be0ce)
Location: include/linux/mm.h:2472
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:2636
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2636
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:2636
Inline: True
```
```
In mm/huge_memory.c (ffffffff814408fe)
Location: include/linux/mm.h:2636
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
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
In mm/gup.c (0)
Location: include/linux/mm.h:2961
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2961
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:2961
Inline: True
```
```
In mm/huge_memory.c (ffffffff814761ae)
Location: include/linux/mm.h:2961
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:3066
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:3066
Inline: True
```
```
In mm/mremap.c (0)
Location: include/linux/mm.h:3066
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a5a5e)
Location: include/linux/mm.h:3066
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
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
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/hugetlbpage.c (c0000000000a569c)
Location: include/linux/mm.h:2070
Inline: True
Inline callers:
  - arch/powerpc/mm/hugetlbpage.c:huge_pte_alloc
```
```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/huge_memory.c (ffffffff812afe95)
Location: include/linux/mm.h:2070
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a1375)
Location: include/linux/mm.h:2070
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/huge_memory.c (ffffffff812adca5)
Location: include/linux/mm.h:2070
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/mm.h:2070
Inline: True
```
```
In mm/huge_memory.c (ffffffff812be005)
Location: include/linux/mm.h:2070
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
```
</details>
</li>
</ul>

## Differences
