# Function: <code>vma_interval_tree_iter_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811b89d0)
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
ffffffff811b89d0-ffffffff811b89f8: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811d2c70)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:memory_failure
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff811d2c70-ffffffff811d2c98: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811e2b30)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:memory_failure
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff811e2b30-ffffffff811e2b58: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff811ecfa0)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_writeback_mapping_range
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff811ecfa0-ffffffff811ecfc5: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81203370)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_range
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_shmem
  - fs/dax.c:dax_writeback_mapping_range
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff81203370-ffffffff812033a2: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81224030)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff81224030-ffffffff81224062: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81237080)
Location: mm/interval_tree.c:24
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff81237080-ffffffff812370b0: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812485f0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff812485f0-ffffffff81248620: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81256a40)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff81256a40-ffffffff81256a70: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812853d0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:collect_procs_file
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff812853d0-ffffffff81285400: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f6b0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/khugepaged.c:retract_page_tables
  - mm/memory-failure.c:collect_procs_file
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff8128f6b0-ffffffff8128f6e0: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81294d10)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
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
ffffffff81294d10-ffffffff81294d40: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d5370)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_pages
  - mm/memory.c:unmap_mapping_page
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
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
ffffffff812d5370-ffffffff812d53a0: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813344f0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_wp
  - mm/khugepaged.c:retract_page_tables
  - fs/dax.c:dax_writeback_one
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffff813344f0-ffffffff81334544: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813ab190)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
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
ffffffff813ab190-ffffffff813ab1e4: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813df530)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
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
ffffffff813df530-ffffffff813df584: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409c40)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:build_map_info
  - mm/memory.c:unmap_mapping_range
  - mm/memory.c:unmap_mapping_folio
  - mm/pagewalk.c:walk_page_mapping
  - mm/rmap.c:rmap_walk_file
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
ffffffff81409c40-ffffffff81409c94: vma_interval_tree_iter_first (STB_GLOBAL)
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
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffff8000102ee238)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffff8000102ee238-ffff8000102ee2bc: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c05120e8)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
```
**Symbols:**

```
c05120e8-c0512140: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (c0000000003b22b0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:hugetlb_cow
  - mm/khugepaged.c:collapse_file
  - mm/memory-failure.c:collect_procs
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
c0000000003b22b0-c0000000003b22f8: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffe00020246c)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_cow
  - fs/dax.c:dax_entry_mkclean
  - fs/hugetlbfs/inode.c:hugetlb_vmdelete_list
```
**Symbols:**

```
ffffffe00020246c-ffffffe0002024ca: vma_interval_tree_iter_first (STB_GLOBAL)
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
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124f090)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff8124f090-ffffffff8124f0c0: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81242030)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff81242030-ffffffff81242060: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8124ce30)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff8124ce30-ffffffff8124ce60: vma_interval_tree_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_area_struct *vma_interval_tree_iter_first(struct rb_root_cached *root, long unsigned int start, long unsigned int last);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8125c7f0)
Location: mm/interval_tree.c:23
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
  - mm/memory.c:unmap_mapping_pages
  - mm/rmap.c:rmap_walk_file
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
ffffffff8125c7f0-ffffffff8125c820: vma_interval_tree_iter_first (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rb_root *root</code> ➡️ <code>struct rb_root_cached *root</code>
</li>
</ul>
</details>
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
