# Function: <code>ptep_clear_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811d0440)
Location: mm/pgtable-generic.c:73
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811d0440-ffffffff811d049a: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811ed5f0)
Location: mm/pgtable-generic.c:73
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/ksm.c:try_to_merge_with_ksm_page
```
**Symbols:**

```
ffffffff811ed5f0-ffffffff811ed64a: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811f79e0)
Location: mm/pgtable-generic.c:73
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffff811f79e0-ffffffff811f7a3a: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202b70)
Location: mm/pgtable-generic.c:79
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81202b70-ffffffff81202bd5: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b8e0)
Location: mm/pgtable-generic.c:80
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8121b8e0-ffffffff8121b933: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d6c0)
Location: mm/pgtable-generic.c:80
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8123d6c0-ffffffff8123d719: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251c10)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:try_to_merge_one_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81251c10-ffffffff81251c6f: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263ee0)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81263ee0-ffffffff81263f41: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81272750)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81272750-ffffffff812727b1: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a3510)
Location: mm/pgtable-generic.c:90
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812a3510-ffffffff812a3575: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aedf0)
Location: mm/pgtable-generic.c:90
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812aedf0-ffffffff812aee55: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b4320)
Location: mm/pgtable-generic.c:90
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812b4320-ffffffff812b4385: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f5f00)
Location: mm/pgtable-generic.c:90
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812f5f00-ffffffff812f5f65: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81359e90)
Location: mm/pgtable-generic.c:91
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_wp
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff81359e90-ffffffff81359f11: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d48c0)
Location: mm/pgtable-generic.c:91
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_wp
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff813d48c0-ffffffff813d4941: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81409290)
Location: mm/pgtable-generic.c:93
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_wp
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff81409290-ffffffff81409311: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435a80)
Location: mm/pgtable-generic.c:94
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/hugetlb.c:hugetlb_wp
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
**Symbols:**

```
ffffffff81435a80-ffffffff81435b01: ptep_clear_flush (STB_GLOBAL)
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
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010307fb0)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - arch/arm64/mm/hugetlbpage.c:huge_ptep_clear_flush
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/ksm.c:try_to_merge_one_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffff800010307fb0-ffff80001030808c: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0525588)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/ksm.c:replace_page
  - mm/ksm.c:write_protect_page
```
**Symbols:**

```
c0525588-c05255f8: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0000000003d71b0)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/ksm.c:replace_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
c0000000003d71b0-c0000000003d72f4: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffe000212d34)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:try_to_merge_one_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffe000212d34-ffffffe000212d78: ptep_clear_flush (STB_GLOBAL)
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
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126ada0)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff8126ada0-ffffffff8126ae01: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125cdd0)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff8125cdd0-ffffffff8125ce31: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268b40)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81268b40-ffffffff81268ba1: ptep_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pte_t ptep_clear_flush(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812784d0)
Location: mm/pgtable-generic.c:81
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:wp_page_copy
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/hugetlb.c:hugetlb_cow
  - mm/ksm.c:replace_page
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff812784d0-ffffffff81278531: ptep_clear_flush (STB_GLOBAL)
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
