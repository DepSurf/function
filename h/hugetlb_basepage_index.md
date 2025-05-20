# Function: <code>hugetlb_basepage_index</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int hugetlb_basepage_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d8f00)
Location: mm/hugetlb.c:1589
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff812d8f00-ffffffff812d8fb4: hugetlb_basepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_basepage_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1780
Inline: False
Direct callers:
  - kernel/futex.c:get_futex_key
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff81cbf6da-ffffffff81cbf6ee: hugetlb_basepage_index.cold (STB_LOCAL)
ffffffff8131f900-ffffffff8131f9c6: hugetlb_basepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_basepage_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:1892
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:vma_address
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff81e71a6c-ffffffff81e71a84: hugetlb_basepage_index.cold (STB_LOCAL)
ffffffff8138c370-ffffffff8138c566: hugetlb_basepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_basepage_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2088
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:page_address_in_vma
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff82066545-ffffffff82066565: hugetlb_basepage_index.cold (STB_LOCAL)
ffffffff8140ae40-ffffffff8140b03b: hugetlb_basepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int hugetlb_basepage_index(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2115
Inline: False
Direct callers:
  - kernel/futex/core.c:get_futex_key
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:filemap_cachestat
  - mm/debug.c:__dump_page
  - mm/page_vma_mapped.c:vma_address
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_make_device_exclusive_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:folio_referenced_one
  - mm/rmap.c:vma_address
  - mm/ksm.c:write_protect_page
  - mm/migrate.c:remove_migration_pte
  - mm/memory-failure.c:collect_procs_anon
  - mm/page_idle.c:page_idle_clear_pte_refs_one
```
**Symbols:**

```
ffffffff820e5d1e-ffffffff820e5d34: hugetlb_basepage_index.cold (STB_LOCAL)
ffffffff8143e4f0-ffffffff8143e65d: hugetlb_basepage_index (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
