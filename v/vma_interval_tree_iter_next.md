# Function: <code>vma_interval_tree_iter_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b8a00)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:huge_pmd_share
  - mm/memory-failure.c:memory_failure
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
**Symbols:**

```
ffffffff811b8a00-ffffffff811b8a69: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2ca0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:memory_failure
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff811d2ca0-ffffffff811d2d09: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2b60)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:memory_failure
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff811e2b60-ffffffff811e2bc9: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ecfd0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_writeback_mapping_range
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff811ecfd0-ffffffff811ed039: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812033b0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_writeback_mapping_range
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812033b0-ffffffff81203419: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81224070)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_writeback_mapping_range
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81224070-ffffffff812240d9: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812370b0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812370b0-ffffffff81237119: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81248620)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81248620-ffffffff81248689: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256a70)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81256a70-ffffffff81256ad9: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81285400)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:collect_procs_file
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81285400-ffffffff8128546f: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f6e0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:collect_procs_file
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8128f6e0-ffffffff8128f74f: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294d40)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81294d40-ffffffff81294dac: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d53a0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812d53a0-ffffffff812d540c: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81334550)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_wp
  - mm/khugepaged.c:retract_page_tables
  - fs/dax.c:dax_writeback_one
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81334550-ffffffff813345fc: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813ab200)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_wp
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:mf_dax_kill_procs
  - fs/dax.c:dax_writeback_one
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
**Symbols:**

```
ffffffff813ab200-ffffffff813ab2ac: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df5a0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_wp
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:mf_dax_kill_procs
  - fs/dax.c:dax_writeback_one
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
**Symbols:**

```
ffffffff813df5a0-ffffffff813df64c: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409cb0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_wp
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:mf_dax_kill_procs
  - fs/dax.c:dax_writeback_one
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
  - fs/hugetlbfs/inode.c:hugetlb_unmap_file_folio
```
**Symbols:**

```
ffffffff81409cb0-ffffffff81409d5c: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ee2c0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffff8000102ee2c0-ffff8000102ee374: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0512140)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
```
**Symbols:**

```
c0512140-c05121d4: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b2300)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
c0000000003b2300-c0000000003b2398: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe0002024ca)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffe0002024ca-ffffffe00020254a: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124f0c0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8124f0c0-ffffffff8124f129: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81242060)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81242060-ffffffff812420c9: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124ce60)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8124ce60-ffffffff8124cec9: vma_interval_tree_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_next(struct vm_area_struct *node, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c820)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8125c820-ffffffff8125c889: vma_interval_tree_iter_next (STB_GLOBAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
