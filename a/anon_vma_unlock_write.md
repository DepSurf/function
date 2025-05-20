# Function: <code>anon_vma_unlock_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811baa86)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bd352)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811c5090)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:mm_drop_all_locks
```
```
In mm/mremap.c (ffffffff811c9973)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811cb65a)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff811f544e)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:copy_huge_pmd
  - mm/huge_memory.c:__pmd_trans_huge_lock
  - mm/huge_memory.c:split_huge_page_to_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e43bb)
Location: include/linux/rmap.h:120
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_adjust
```
```
In mm/mremap.c (ffffffff811e5e09)
Location: include/linux/rmap.h:120
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e886d)
Location: include/linux/rmap.h:120
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812178f2)
Location: include/linux/rmap.h:120
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8121a3c2)
Location: include/linux/rmap.h:120
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f43ff)
Location: include/linux/rmap.h:121
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff811f6100)
Location: include/linux/rmap.h:121
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811f9bcd)
Location: include/linux/rmap.h:121
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81229ea2)
Location: include/linux/rmap.h:121
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122e7c6)
Location: include/linux/rmap.h:121
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811ff37f)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81200ef2)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8120492c)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81235c27)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812384cc)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff8121797f)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81219843)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8121d8dc)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812549db)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81259334)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
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
In mm/mmap.c (ffffffff81238cea)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8123b169)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8123f7d3)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812787fa)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8127c2c5)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff8124c6aa)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8124e9e2)
Location: include/linux/rmap.h:123
Inline: True
```
```
In mm/rmap.c (ffffffff81253ed3)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff8128cea7)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81290961)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff8125eada)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81260d32)
Location: include/linux/rmap.h:123
Inline: True
```
```
In mm/rmap.c (ffffffff81266183)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812a7d04)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812ab9b0)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff8126d2eb)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8126f4c2)
Location: include/linux/rmap.h:123
Inline: True
```
```
In mm/rmap.c (ffffffff81274aa3)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812b91d9)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812bd1bf)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff8129d4eb)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812a06f6)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812a5eb3)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812edbf5)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812f28d5)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff812a88fc)
Location: include/linux/rmap.h:122
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812abcd0)
Location: include/linux/rmap.h:122
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b1333)
Location: include/linux/rmap.h:122
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812f92b3)
Location: include/linux/rmap.h:122
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812fcf05)
Location: include/linux/rmap.h:122
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff812adda9)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812b10b7)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b6a03)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812ff8bc)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81303c7a)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff812ef51f)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812f2918)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812f8e23)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff813494d7)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8134d9b8)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff813529d0)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81356aca)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135f697)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff813bf984)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c6c1d)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff813ccaa9)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
```
```
In mm/mremap.c (ffffffff813d106c)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813da4f7)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81441e6d)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8144bff1)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff81401379)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_complete
```
```
In mm/mremap.c (ffffffff81405a4f)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140ec37)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81477713)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81481801)
Location: include/linux/rmap.h:124
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff8142d9c9)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_complete
```
```
In mm/mremap.c (ffffffff81431eb0)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8143b5f7)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff814a6efa)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814af4b8)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff814d2cc8)
Location: include/linux/rmap.h:129
Inline: True
Inline callers:
  - mm/userfaultfd.c:move_pages_pte
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
In mm/mmap.c (ffff80001030439c)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffff80001030650c)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff80001030a714)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffff8000103596e8)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffff80001035e4ec)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0522b08)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (c0524138)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0526c28)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
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
In mm/mmap.c (c0000000003d11b0)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (c0000000003d4258)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0000000003da388)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (c000000000442c54)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (c0000000004479e8)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffe000210be8)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffe000211d90)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe00021435a)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
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
In mm/mmap.c (ffffffff8126593b)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81267b12)
Location: include/linux/rmap.h:123
Inline: True
```
```
In mm/rmap.c (ffffffff8126d0f3)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812b17b9)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b579f)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff81257d5b)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81259e62)
Location: include/linux/rmap.h:123
Inline: True
```
```
In mm/rmap.c (ffffffff8125f123)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812a2b89)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812a67ed)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff812636db)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812658b2)
Location: include/linux/rmap.h:123
Inline: True
```
```
In mm/rmap.c (ffffffff8126ae93)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812af5c9)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b35af)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/mmap.c (ffffffff8127309b)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/mmap.c:mm_drop_all_locks
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81275262)
Location: include/linux/rmap.h:123
Inline: True
```
```
In mm/rmap.c (ffffffff8127a808)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812bf917)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812c3a01)
Location: include/linux/rmap.h:123
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
</ul>

## Differences
