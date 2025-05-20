# Function: <code>is_zero_pfn</code>

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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:602
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:602
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:602
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/asm-generic/pgtable.h:602
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:615
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:615
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/asm-generic/pgtable.h:615
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/asm-generic/pgtable.h:615
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:638
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:638
Inline: True
```
```
In mm/ksm.c (0)
Location: include/asm-generic/pgtable.h:638
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/asm-generic/pgtable.h:638
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/asm-generic/pgtable.h:638
Inline: True
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
In mm/gup.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In mm/ksm.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
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
Location: include/asm-generic/pgtable.h:788
Inline: True
```
```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:788
Inline: True
```
```
In mm/ksm.c (0)
Location: include/asm-generic/pgtable.h:788
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:788
Inline: True
```
```
In mm/khugepaged.c (0)
Location: include/asm-generic/pgtable.h:788
Inline: True
```
```
In fs/proc/page.c (0)
Location: include/asm-generic/pgtable.h:788
Inline: True
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
In mm/gup.c (ffffffff81228145)
Location: include/asm-generic/pgtable.h:831
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81229ccd)
Location: include/asm-generic/pgtable.h:831
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:_vm_normal_page
```
```
In mm/ksm.c (ffffffff81260524)
Location: include/asm-generic/pgtable.h:831
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff8126dfeb)
Location: include/asm-generic/pgtable.h:831
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8127cfff)
Location: include/asm-generic/pgtable.h:831
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/page.c (ffffffff8132a771)
Location: include/asm-generic/pgtable.h:831
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff8123b965)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8123d2b5)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:_vm_normal_page
```
```
In mm/ksm.c (ffffffff81274c8a)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/migrate.c (ffffffff81282e5b)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff81291b71)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
```
In fs/proc/page.c (ffffffff81341ace)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff8124ce53)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8124ef57)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff8128f76e)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/khugepaged.c (ffffffff812abe2b)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (ffffffff81369f02)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff8125b383)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8125d539)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff8129f4f3)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812aec35)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812bd63b)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (ffffffff81382122)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff8128944c)
Location: include/linux/pgtable.h:1043
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8128ce59)
Location: include/linux/pgtable.h:1043
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff812d3b41)
Location: include/linux/pgtable.h:1043
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812e4243)
Location: include/linux/pgtable.h:1043
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812f2d56)
Location: include/linux/pgtable.h:1043
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_copy
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/hmm.c (ffffffff8130af42)
Location: include/linux/pgtable.h:1043
Inline: True
```
```
In fs/proc/page.c (ffffffff813cc752)
Location: include/linux/pgtable.h:1043
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff8129312c)
Location: include/linux/pgtable.h:1133
Inline: True
Inline callers:
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81297e59)
Location: include/linux/pgtable.h:1133
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff812df541)
Location: include/linux/pgtable.h:1133
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812efce6)
Location: include/linux/pgtable.h:1133
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812fd38d)
Location: include/linux/pgtable.h:1133
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/hmm.c (ffffffff81316e12)
Location: include/linux/pgtable.h:1133
Inline: True
```
```
In fs/proc/page.c (ffffffff813de3ba)
Location: include/linux/pgtable.h:1133
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff81296f0c)
Location: include/linux/pgtable.h:1134
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff8129d500)
Location: include/linux/pgtable.h:1134
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/hugetlb.c (ffffffff812d6911)
Location: include/linux/pgtable.h:1134
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff812e7e5e)
Location: include/linux/pgtable.h:1134
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812f566a)
Location: include/linux/pgtable.h:1134
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813040fa)
Location: include/linux/pgtable.h:1134
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff8131d03a)
Location: include/linux/pgtable.h:1134
Inline: True
```
```
In fs/proc/page.c (ffffffff813e5196)
Location: include/linux/pgtable.h:1134
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff812d78bc)
Location: include/linux/pgtable.h:1153
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812ddc00)
Location: include/linux/pgtable.h:1153
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/hugetlb.c (ffffffff8131c6da)
Location: include/linux/pgtable.h:1153
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8132fd8e)
Location: include/linux/pgtable.h:1153
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff8133fc61)
Location: include/linux/pgtable.h:1153
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8134de2a)
Location: include/linux/pgtable.h:1153
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff8136a4bd)
Location: include/linux/pgtable.h:1153
Inline: True
```
```
In fs/proc/page.c (ffffffff81436d66)
Location: include/linux/pgtable.h:1153
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff81337b09)
Location: include/linux/pgtable.h:1215
Inline: True
Inline callers:
  - mm/gup.c:check_and_migrate_movable_pages
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8133dbc5)
Location: include/linux/pgtable.h:1215
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/hugetlb.c (ffffffff813877ec)
Location: include/linux/pgtable.h:1215
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff813a0157)
Location: include/linux/pgtable.h:1215
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff813b72c6)
Location: include/linux/pgtable.h:1215
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff813c708a)
Location: include/linux/pgtable.h:1215
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff813e8677)
Location: include/linux/pgtable.h:1215
Inline: True
```
```
In fs/proc/page.c (ffffffff814b1793)
Location: include/linux/pgtable.h:1215
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/vmscan.c (ffffffff8137823a)
Location: include/linux/pgtable.h:1251
Inline: True
```
```
In mm/gup.c (ffffffff813ae9c8)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813b6c9e)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/hugetlb.c (ffffffff81405c07)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/ksm.c (ffffffff8141f03e)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff81438da3)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8144aefa)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In mm/hmm.c (ffffffff814705a3)
Location: include/linux/pgtable.h:1251
Inline: True
```
```
In fs/proc/page.c (ffffffff81547edf)
Location: include/linux/pgtable.h:1251
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/vmscan.c (ffffffff813aba8a)
Location: include/linux/pgtable.h:1236
Inline: True
```
```
In mm/gup.c (ffffffff813e32c8)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff813eb672)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/hugetlb.c (ffffffff81439144)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/ksm.c (ffffffff81453bee)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate_device.c (ffffffff8146f5e8)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff8147ec31)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/hmm.c (ffffffff814a4d7e)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/page.c (ffffffff8157fae1)
Location: include/linux/pgtable.h:1236
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/vmscan.c (ffffffff813d61aa)
Location: include/linux/pgtable.h:1346
Inline: True
```
```
In mm/gup.c (ffffffff8140da7c)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - mm/gup.c:collect_longterm_unpinnable_pages
  - mm/gup.c:get_gate_page
  - mm/gup.c:follow_page_pte
  - mm/gup.c:folio_add_pin
  - mm/gup.c:try_grab_page
  - mm/gup.c:gup_put_folio
  - mm/gup.c:try_grab_folio
  - mm/gup.c:try_grab_folio
```
```
In mm/memory.c (ffffffff8141634f)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:zap_pte_range
  - mm/memory.c:vm_normal_page
```
```
In mm/hugetlb.c (ffffffff81472c74)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/ksm.c (ffffffff8148e434)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
  - mm/ksm.c:break_ksm_pmd_entry
```
```
In mm/migrate_device.c (ffffffff8149d4a8)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff814af919)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:release_pte_pages
```
```
In mm/hmm.c (ffffffff814d5dce)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_handle_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159d260)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_hugetlb_category
  - fs/proc/task_mmu.c:pagemap_thp_category
  - fs/proc/task_mmu.c:pagemap_page_category
```
```
In fs/proc/page.c (ffffffff815b84f1)
Location: include/linux/pgtable.h:1346
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffff8000102f1c7c)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102f4b88)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffff80001033ed40)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/khugepaged.c (ffff80001035eb68)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (ffff800010450298)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (c0514b0c)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
```
```
In mm/memory.c (c0516d3c)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (c0544f80)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In fs/proc/page.c (c0613298)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (c0000000003b6390)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003bb828)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (c00000000041accc)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (c000000000434878)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (c000000000447fa8)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (c0000000005682d0)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffe0002048b0)
Location: include/asm-generic/pgtable.h:869
Inline: True
```
```
In mm/memory.c (ffffffe00020605c)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffe00023495a)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In fs/proc/page.c (ffffffe0002e3396)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff812539d3)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81255b89)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff81297ad3)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a7215)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812b5c1b)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (ffffffff8137a702)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
Location: include/asm-generic/pgtable.h:869
Inline: True
```
```
In mm/memory.c (ffffffff81248262)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff81289681)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff81298c17)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812a6de5)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (ffffffff8136b1d2)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff81251773)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff81253929)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff812958e3)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812a5025)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812b3a2b)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (ffffffff813781d2)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In mm/gup.c (ffffffff81261116)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff812632e5)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
  - mm/memory.c:vm_normal_page_pmd
  - mm/memory.c:vm_normal_page
```
```
In mm/ksm.c (ffffffff812a56fb)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/ksm.c:replace_page
```
```
In mm/migrate.c (ffffffff812b5b7f)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_collect_pmd
```
```
In mm/khugepaged.c (ffffffff812c3e6e)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:__collapse_huge_page_isolate
  - mm/khugepaged.c:__collapse_huge_page_isolate
```
```
In fs/proc/page.c (ffffffff8138bc82)
Location: include/asm-generic/pgtable.h:869
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
