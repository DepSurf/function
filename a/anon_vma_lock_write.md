# Function: <code>anon_vma_lock_write</code>

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
In mm/gup.c (ffffffff811baa73)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/gup.c:follow_page_mask
```
```
In mm/memory.c (ffffffff811bd33f)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/memory.c:__pte_alloc
```
```
In mm/mmap.c (ffffffff811c4ddf)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:expand_downwards
```
```
In mm/mremap.c (ffffffff811c9937)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811cb651)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff811f502e)
Location: include/linux/rmap.h:111
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff811e2b9b)
Location: include/linux/rmap.h:115
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:vma_adjust
```
```
In mm/mremap.c (ffffffff811e5dd3)
Location: include/linux/rmap.h:115
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811e8864)
Location: include/linux/rmap.h:115
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81217962)
Location: include/linux/rmap.h:115
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81219fa5)
Location: include/linux/rmap.h:115
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff811f2b56)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff811f60c3)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff811f9bc4)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81229f12)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8122e338)
Location: include/linux/rmap.h:116
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff811fdb15)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81200eb7)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff81204923)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81235c8b)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8123814c)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff812160c5)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8121980c)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8121d8d3)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81254859)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81258bcc)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff81236e7d)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8123b12a)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8123f7ca)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81278b36)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8127bfc8)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff8124a726)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8124e9ba)
Location: include/linux/rmap.h:118
Inline: True
```
```
In mm/rmap.c (ffffffff81253eca)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff8128d1e0)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81290634)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff8125ca96)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81260d0a)
Location: include/linux/rmap.h:118
Inline: True
```
```
In mm/rmap.c (ffffffff8126617a)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812a7ccb)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812ab809)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff8126b1f6)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8126f49a)
Location: include/linux/rmap.h:118
Inline: True
```
```
In mm/rmap.c (ffffffff81274a9a)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812b91a0)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812bd009)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff8129a8f7)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812a069f)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812a5eaa)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812edabb)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812f271f)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff812a5ac7)
Location: include/linux/rmap.h:117
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812abc96)
Location: include/linux/rmap.h:117
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b132a)
Location: include/linux/rmap.h:117
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812f9184)
Location: include/linux/rmap.h:117
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812fcd43)
Location: include/linux/rmap.h:117
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff812ac206)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812b108c)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812b69fa)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812ff782)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff81303ab8)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff812ed956)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff812f2e20)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff812f8e1a)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff813493b1)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8134d7f1)
Location: include/linux/rmap.h:114
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff81350cfa)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81356a97)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8135f68e)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff813bf954)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff813c6a57)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff813ca94c)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
  - mm/mmap.c:vma_expand
```
```
In mm/mremap.c (ffffffff813d103d)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff813da4ee)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff81441e41)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8144bfc1)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/mmap.c (ffffffff813ff8d0)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mremap.c (ffffffff81405a23)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8140ec2e)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff814776e7)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814817d1)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_pte_mapped_thp
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
In mm/mmap.c (ffffffff8142be46)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
```
```
In mm/mremap.c (ffffffff81431fd1)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffff8143b5ee)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff814a6eca)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:move_pages_huge_pmd
```
```
In mm/khugepaged.c (ffffffff814af36a)
Location: include/linux/rmap.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff814d2bc8)
Location: include/linux/rmap.h:119
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
In mm/mmap.c (ffff800010302928)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffff8000103064c0)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffff80001030a70c)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffff8000103597a0)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffff80001035e3ac)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (c0520fec)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (c0524118)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0526c20)
Location: include/linux/rmap.h:118
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
In mm/mmap.c (c0000000003cefc0)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (c0000000003d4218)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (c0000000003da380)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (c000000000442ed8)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (c000000000447800)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffe00020f768)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffe000211d7c)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/rmap.c (ffffffe000214350)
Location: include/linux/rmap.h:118
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
In mm/mmap.c (ffffffff81263846)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81267aea)
Location: include/linux/rmap.h:118
Inline: True
```
```
In mm/rmap.c (ffffffff8126d0ea)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812b1780)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b55e9)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff81255c66)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff81259e3a)
Location: include/linux/rmap.h:118
Inline: True
```
```
In mm/rmap.c (ffffffff8125f11a)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812a2b50)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812a6669)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff812615e6)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8126588a)
Location: include/linux/rmap.h:118
Inline: True
```
```
In mm/rmap.c (ffffffff8126ae8a)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812af590)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812b33f9)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
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
In mm/mmap.c (ffffffff81270fb6)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/mmap.c:expand_downwards
  - mm/mmap.c:__vma_adjust
```
```
In mm/mremap.c (ffffffff8127523a)
Location: include/linux/rmap.h:118
Inline: True
```
```
In mm/rmap.c (ffffffff8127a7fe)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/huge_memory.c (ffffffff812bf8de)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff812c3861)
Location: include/linux/rmap.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
</ul>

## Differences
