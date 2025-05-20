# Function: <code>i_mmap_unlock_read</code>

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
In kernel/events/uprobes.c (ffffffff81187c31)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/memory.c (ffffffff811bfffb)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/rmap.c (ffffffff811cc055)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
```
```
In mm/memory-failure.c (ffffffff81202c93)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/dax.c (ffffffff8125e305)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
  - fs/dax.c:__dax_fault
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
In kernel/events/uprobes.c (ffffffff8119a2e9)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff811e6c81)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff8121790d)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8122731c)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In kernel/events/uprobes.c (ffffffff811a9a59)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff811f8021)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff81229ebd)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812398dd)
Location: include/linux/fs.h:466
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/dax.c (ffffffff8129b9e7)
Location: include/linux/fs.h:466
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
In kernel/events/uprobes.c (ffffffff811b109c)
Location: include/linux/fs.h:477
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8120353b)
Location: include/linux/fs.h:477
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff81235a9b)
Location: include/linux/fs.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81244c4b)
Location: include/linux/fs.h:477
Inline: True
```
```
In fs/dax.c (ffffffff812aa9c1)
Location: include/linux/fs.h:477
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In kernel/events/uprobes.c (ffffffff811c4c7c)
Location: include/linux/fs.h:481
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8121c086)
Location: include/linux/fs.h:481
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff81254807)
Location: include/linux/fs.h:481
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81264b3b)
Location: include/linux/fs.h:481
Inline: True
```
```
In fs/dax.c (ffffffff812ce16a)
Location: include/linux/fs.h:481
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In kernel/events/uprobes.c (ffffffff811e51f2)
Location: include/linux/fs.h:483
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8123e112)
Location: include/linux/fs.h:483
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff8127881d)
Location: include/linux/fs.h:483
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81288dc3)
Location: include/linux/fs.h:483
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff812f8712)
Location: include/linux/fs.h:483
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In kernel/events/uprobes.c (ffffffff811f5b68)
Location: include/linux/fs.h:520
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff812526a7)
Location: include/linux/fs.h:520
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff8128cecf)
Location: include/linux/fs.h:520
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8129dd13)
Location: include/linux/fs.h:520
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff8130c48f)
Location: include/linux/fs.h:520
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff8120d8ca)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff81264832)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812a7b22)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812b8fec)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff813339ca)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff8121aefa)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff812730a2)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812b9004)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812caedc)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff81347594)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff8124587a)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812a40d2)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff812ca842)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812eda5b)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81300da2)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
```
```
In mm/userfaultfd.c (ffffffff813089dd)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c658)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff8138d974)
Location: include/linux/fs.h:547
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff8124fe9a)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812af9a2)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff812d6472)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812f9127)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8130cf41)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
```
```
In mm/userfaultfd.c (ffffffff813147ba)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff81318598)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff8139f3f4)
Location: include/linux/fs.h:511
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff8125477a)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812b4c60)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff812dd61c)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812ff732)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff813134b8)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In mm/userfaultfd.c (ffffffff8131b2ff)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e788)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff813a6161)
Location: include/linux/fs.h:512
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff812901aa)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812f6ab0)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff813247bf)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff81349361)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8135ff78)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In mm/userfaultfd.c (ffffffff81368604)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bb68)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff813f5bd1)
Location: include/linux/fs.h:519
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff812e526a)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff81342638)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff8135bdbd)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff8139318a)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff813bf82d)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff813dad17)
Location: include/linux/fs.h:474
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e5ded)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9d02)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff814695b9)
Location: include/linux/fs.h:474
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
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
In kernel/events/uprobes.c (ffffffff8134ec14)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff813ba7c8)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff813d6a75)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff8140e2be)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff81441d21)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81460ebc)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471d72)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff814fa059)
Location: include/linux/fs.h:489
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
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
In kernel/events/uprobes.c (ffffffff8137fdb0)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff813ef188)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff8140b86b)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff814416ce)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff81477628)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814801bd)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff814979ef)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a66c2)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff815314d7)
Location: include/linux/fs.h:504
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
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
In kernel/events/uprobes.c (ffffffff813a8fff)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff8141aaf8)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff814380ba)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff8147b9b0)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff814a6f16)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814ae17f)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
```
```
In mm/memory-failure.c (ffffffff814c7113)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7612)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff815663b7)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
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
In kernel/events/uprobes.c (ffff8000102a6580)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffff800010308e18)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffff800010359718)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffff80001036ee5c)
Location: include/linux/fs.h:539
Inline: True
```
```
In fs/dax.c (ffff80001040773c)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (c04d56e4)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (c05259a8)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
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
In kernel/events/uprobes.c (c00000000035951c)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (c0000000003d8148)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (c000000000442e94)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (c00000000045f50c)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (c000000000512738)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In mm/rmap.c (ffffffe000213472)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In fs/dax.c (ffffffe0002b2e38)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff8121354a)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8126b6f2)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812b15e4)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812c34bc)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff8133fb74)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff812062ba)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8125d992)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812a29b4)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812b44fc)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff813307f2)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff812112ea)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff81269492)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812af3f4)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812c12cc)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff8133d644)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In kernel/events/uprobes.c (ffffffff8122023a)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff81278fc2)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812bf744)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812d1d8a)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff81350553)
Location: include/linux/fs.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
</details>
</li>
</ul>

## Differences
