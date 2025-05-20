# Function: <code>i_mmap_lock_read</code>

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
In kernel/events/uprobes.c (ffffffff81187b19)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff811cbf73)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk
```
```
In mm/memory-failure.c (ffffffff81202cd4)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/dax.c (ffffffff8125e2e1)
Location: include/linux/fs.h:507
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
In kernel/events/uprobes.c (ffffffff8119a1c9)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff811e6cb2)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812178ac)
Location: include/linux/fs.h:510
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81227348)
Location: include/linux/fs.h:510
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
In kernel/events/uprobes.c (ffffffff811a9939)
Location: include/linux/fs.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff811f8052)
Location: include/linux/fs.h:461
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff81229e5c)
Location: include/linux/fs.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81239908)
Location: include/linux/fs.h:461
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/dax.c (ffffffff8129b8bc)
Location: include/linux/fs.h:461
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
In kernel/events/uprobes.c (ffffffff811b0fa9)
Location: include/linux/fs.h:472
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff812035c6)
Location: include/linux/fs.h:472
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff81235a7f)
Location: include/linux/fs.h:472
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81244dba)
Location: include/linux/fs.h:472
Inline: True
```
```
In fs/dax.c (ffffffff812aa7f5)
Location: include/linux/fs.h:472
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
In kernel/events/uprobes.c (ffffffff811c4b89)
Location: include/linux/fs.h:476
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8121c111)
Location: include/linux/fs.h:476
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812547e7)
Location: include/linux/fs.h:476
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81264caa)
Location: include/linux/fs.h:476
Inline: True
```
```
In fs/dax.c (ffffffff812ce027)
Location: include/linux/fs.h:476
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
In kernel/events/uprobes.c (ffffffff811e50d2)
Location: include/linux/fs.h:478
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8123e129)
Location: include/linux/fs.h:478
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff8127864a)
Location: include/linux/fs.h:478
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81288ce4)
Location: include/linux/fs.h:478
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff812f85a3)
Location: include/linux/fs.h:478
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
In kernel/events/uprobes.c (ffffffff811f5a56)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff812526be)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff8128ccae)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8129dc34)
Location: include/linux/fs.h:515
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff8130c355)
Location: include/linux/fs.h:515
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
In kernel/events/uprobes.c (ffffffff8120d7dd)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff81264849)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812a79c5)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812b8d9a)
Location: include/linux/fs.h:527
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff81333895)
Location: include/linux/fs.h:527
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
In kernel/events/uprobes.c (ffffffff8121ae0d)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff812730b9)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812b8e94)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812cac8a)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff81347435)
Location: include/linux/fs.h:534
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
In kernel/events/uprobes.c (ffffffff81245798)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812a40e9)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff812ca603)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812eda30)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81300c98)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
```
```
In mm/userfaultfd.c (ffffffff81308941)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c62c)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff8138d835)
Location: include/linux/fs.h:542
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
In kernel/events/uprobes.c (ffffffff8124fdb8)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812af9b9)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff812d6233)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812f9100)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8130ce38)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
```
```
In mm/userfaultfd.c (ffffffff8131471f)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131856c)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff8139f2b5)
Location: include/linux/fs.h:506
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
In kernel/events/uprobes.c (ffffffff81254698)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812b4c77)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff812dd3d3)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff812ff70b)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff813134d0)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In mm/userfaultfd.c (ffffffff8131b269)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e75c)
Location: include/linux/fs.h:507
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff813a6025)
Location: include/linux/fs.h:507
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
In kernel/events/uprobes.c (ffffffff812900c8)
Location: include/linux/fs.h:514
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/rmap.c (ffffffff812f6ac7)
Location: include/linux/fs.h:514
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff8132455f)
Location: include/linux/fs.h:514
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff8134931f)
Location: include/linux/fs.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff8135ff90)
Location: include/linux/fs.h:514
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In mm/userfaultfd.c (ffffffff8136856e)
Location: include/linux/fs.h:514
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bb3c)
Location: include/linux/fs.h:514
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff813f5a95)
Location: include/linux/fs.h:514
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
In kernel/events/uprobes.c (ffffffff812e5188)
Location: include/linux/fs.h:469
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff81342622)
Location: include/linux/fs.h:469
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff8135bd8b)
Location: include/linux/fs.h:469
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff813929f7)
Location: include/linux/fs.h:469
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_handle_userfault
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/huge_memory.c (ffffffff813bf6df)
Location: include/linux/fs.h:469
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff813dad41)
Location: include/linux/fs.h:469
Inline: True
```
```
In mm/userfaultfd.c (ffffffff813e5d55)
Location: include/linux/fs.h:469
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9ccf)
Location: include/linux/fs.h:469
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff8146955a)
Location: include/linux/fs.h:469
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
In kernel/events/uprobes.c (ffffffff8134eb38)
Location: include/linux/fs.h:484
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff813ba7b2)
Location: include/linux/fs.h:484
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff813d6a43)
Location: include/linux/fs.h:484
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff8140e190)
Location: include/linux/fs.h:484
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff81441c3b)
Location: include/linux/fs.h:484
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff81460dfa)
Location: include/linux/fs.h:484
Inline: True
Inline callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471d3f)
Location: include/linux/fs.h:484
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff814f9ffa)
Location: include/linux/fs.h:484
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
In kernel/events/uprobes.c (ffffffff8137fcc8)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff813ef172)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff8140b839)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff814415b5)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff814775e2)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff8147fd11)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In mm/memory-failure.c (ffffffff8149792a)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a668f)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff81531478)
Location: include/linux/fs.h:499
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
In kernel/events/uprobes.c (ffffffff813a8ee2)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - kernel/events/uprobes.c:build_map_info
```
```
In mm/memory.c (ffffffff8141aae2)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
```
```
In mm/rmap.c (ffffffff81438126)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/hugetlb.c (ffffffff8147b893)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pmd_share
```
```
In mm/huge_memory.c (ffffffff814a6d57)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/khugepaged.c (ffffffff814ade1d)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
```
```
In mm/memory-failure.c (ffffffff814c7041)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d75df)
Location: include/linux/fs.h:532
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_shared_mapping_range
  - mm/mapping_dirty_helpers.c:wp_shared_mapping_range
```
```
In fs/dax.c (ffffffff81566358)
Location: include/linux/fs.h:532
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
In kernel/events/uprobes.c (ffff8000102a6498)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffff800010308df4)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffff80001035958c)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffff80001036ed24)
Location: include/linux/fs.h:534
Inline: True
```
```
In fs/dax.c (ffff800010407658)
Location: include/linux/fs.h:534
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
In kernel/events/uprobes.c (c04d55fc)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (c05259b4)
Location: include/linux/fs.h:534
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
In kernel/events/uprobes.c (c000000000359420)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (c0000000003d80c0)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (c000000000442ae0)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (c00000000045f1d4)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (c0000000005125b8)
Location: include/linux/fs.h:534
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
In mm/rmap.c (ffffffe000213494)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In fs/dax.c (ffffffe0002b2cc0)
Location: include/linux/fs.h:534
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
In kernel/events/uprobes.c (ffffffff8121345d)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8126b709)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812b1474)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812c326a)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff8133fa15)
Location: include/linux/fs.h:534
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
In kernel/events/uprobes.c (ffffffff812061cd)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff8125d9a9)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812a2844)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812b42aa)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff813306d5)
Location: include/linux/fs.h:534
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
In kernel/events/uprobes.c (ffffffff812111fd)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff812694a9)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812af284)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812c107a)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff8133d4e5)
Location: include/linux/fs.h:534
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
In kernel/events/uprobes.c (ffffffff8122014d)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
```
In mm/rmap.c (ffffffff81278fd9)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
```
```
In mm/huge_memory.c (ffffffff812bf5d4)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In mm/memory-failure.c (ffffffff812d1b3a)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
```
```
In fs/dax.c (ffffffff81350425)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
</details>
</li>
</ul>

## Differences
