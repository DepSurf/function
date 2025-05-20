# Function: <code>pud_lock</code>

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
In mm/gup.c (ffffffff811ef674)
Location: include/linux/mm.h:1847
Inline: True
```
```
In mm/memory.c (ffffffff811f553a)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812346ef)
Location: include/linux/mm.h:1847
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff81206d8b)
Location: include/linux/mm.h:1949
Inline: True
```
```
In mm/memory.c (ffffffff8120e40a)
Location: include/linux/mm.h:1949
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812525ef)
Location: include/linux/mm.h:1949
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff812276ac)
Location: include/linux/mm.h:2038
Inline: True
```
```
In mm/memory.c (ffffffff8122ee0a)
Location: include/linux/mm.h:2038
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff81276a1e)
Location: include/linux/mm.h:2038
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff8123ae53)
Location: include/linux/mm.h:2108
Inline: True
```
```
In mm/memory.c (ffffffff8124189a)
Location: include/linux/mm.h:2108
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff8128b945)
Location: include/linux/mm.h:2108
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff8124c79d)
Location: include/linux/mm.h:2103
Inline: True
```
```
In mm/memory.c (ffffffff8125421a)
Location: include/linux/mm.h:2103
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812a6559)
Location: include/linux/mm.h:2103
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff8125accd)
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (ffffffff8126277a)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812b7a32)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff81288ffe)
Location: include/linux/mm.h:2346
Inline: True
```
```
In mm/memory.c (ffffffff8129267a)
Location: include/linux/mm.h:2346
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812ecc02)
Location: include/linux/mm.h:2346
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In mm/gup.c (ffffffff81292cde)
Location: include/linux/mm.h:2362
Inline: True
```
```
In mm/memory.c (ffffffff8129cf61)
Location: include/linux/mm.h:2362
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff812ab07f)
Location: include/linux/mm.h:2362
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f7c92)
Location: include/linux/mm.h:2362
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In mm/gup.c (ffffffff8129871e)
Location: include/linux/mm.h:2370
Inline: True
```
```
In mm/memory.c (ffffffff812a2644)
Location: include/linux/mm.h:2370
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff812b057f)
Location: include/linux/mm.h:2370
Inline: True
```
```
In mm/huge_memory.c (ffffffff812fe242)
Location: include/linux/mm.h:2370
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In mm/gup.c (ffffffff812d9160)
Location: include/linux/mm.h:2399
Inline: True
```
```
In mm/memory.c (ffffffff812e39b4)
Location: include/linux/mm.h:2399
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff812f28a4)
Location: include/linux/mm.h:2399
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff81347de2)
Location: include/linux/mm.h:2399
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In mm/gup.c (ffffffff81339134)
Location: include/linux/mm.h:2477
Inline: True
```
```
In mm/memory.c (ffffffff81344d3e)
Location: include/linux/mm.h:2477
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81356649)
Location: include/linux/mm.h:2477
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff813be271)
Location: include/linux/mm.h:2477
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In mm/gup.c (ffffffff813b0a6a)
Location: include/linux/mm.h:2641
Inline: True
Inline callers:
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813bcf6e)
Location: include/linux/mm.h:2641
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff813d0c6c)
Location: include/linux/mm.h:2641
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff81440ac1)
Location: include/linux/mm.h:2641
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In mm/gup.c (ffffffff813e4e9a)
Location: include/linux/mm.h:2966
Inline: True
Inline callers:
  - mm/gup.c:follow_p4d_mask
```
```
In mm/memory.c (ffffffff813f1cae)
Location: include/linux/mm.h:2966
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff8140569e)
Location: include/linux/mm.h:2966
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff81476376)
Location: include/linux/mm.h:2966
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
In mm/gup.c (ffffffff8140f6b6)
Location: include/linux/mm.h:3071
Inline: True
```
```
In mm/memory.c (ffffffff8141c9a6)
Location: include/linux/mm.h:3071
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/mremap.c (ffffffff81431bc3)
Location: include/linux/mm.h:3071
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/huge_memory.c (ffffffff814a5c22)
Location: include/linux/mm.h:3071
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:insert_pfn_pud
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
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (ffff8000102f99f8)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffff800010358394)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
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
Location: include/linux/mm.h:2075
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
In mm/gup.c (0)
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (c0000000003c3928)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (c000000000440c04)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/huge_memory.c:__pud_trans_huge_lock
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
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (ffffffe00020977c)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
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
In mm/gup.c (ffffffff8125331d)
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (ffffffff8125adca)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812b0012)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff81245fe4)
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (ffffffff8124d158)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812a14e2)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff812510bd)
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (ffffffff81258b6a)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812ade22)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
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
In mm/gup.c (ffffffff81260a32)
Location: include/linux/mm.h:2075
Inline: True
```
```
In mm/memory.c (ffffffff8126856a)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/memory.c:__pmd_alloc
```
```
In mm/huge_memory.c (ffffffff812be179)
Location: include/linux/mm.h:2075
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__pud_trans_huge_lock
  - mm/huge_memory.c:huge_pud_set_accessed
  - mm/huge_memory.c:copy_huge_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
```
</details>
</li>
</ul>

## Differences
