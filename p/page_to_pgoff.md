# Function: <code>page_to_pgoff</code>

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
In mm/rmap.c (ffffffff811ca5cd)
Location: include/linux/pagemap.h:395
Inline: True
Inline callers:
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
  - mm/rmap.c:rmap_walk
```
```
In mm/memory-failure.c (ffffffff81202891)
Location: include/linux/pagemap.h:395
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
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
In mm/filemap.c (ffffffff811a1cad)
Location: include/linux/pagemap.h:370
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/truncate.c (ffffffff811b43ce)
Location: include/linux/pagemap.h:370
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/debug.c (ffffffff811d44a1)
Location: include/linux/pagemap.h:370
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/rmap.c (ffffffff811e6b71)
Location: include/linux/pagemap.h:370
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81226f58)
Location: include/linux/pagemap.h:370
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/filemap.c (ffffffff811b1abe)
Location: include/linux/pagemap.h:400
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/debug.c (ffffffff811e44f6)
Location: include/linux/pagemap.h:400
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff811f6d7d)
Location: include/linux/pagemap.h:400
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff811f7f11)
Location: include/linux/pagemap.h:400
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_mapped_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8123951d)
Location: include/linux/pagemap.h:400
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
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
In mm/filemap.c (ffffffff811b7d2a)
Location: include/linux/pagemap.h:416
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/debug.c (ffffffff811ee952)
Location: include/linux/pagemap.h:416
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812021dc)
Location: include/linux/pagemap.h:416
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8120347b)
Location: include/linux/pagemap.h:416
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81244b0e)
Location: include/linux/pagemap.h:416
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
In mm/filemap.c (ffffffff811cc392)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/debug.c (ffffffff81204dc2)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff8121addc)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8121bfbb)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812649fe)
Location: include/linux/pagemap.h:429
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
In mm/filemap.c (ffffffff811ed74e)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/debug.c (ffffffff81225c68)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff8123cc2c)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8123e0d6)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff81288d1b)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
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
In mm/filemap.c (ffffffff811fedae)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/filemap.c:find_get_pages_contig
```
```
In mm/debug.c (ffffffff81239332)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812510fc)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81252669)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8129dc6b)
Location: include/linux/pagemap.h:429
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
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
In mm/debug.c (ffffffff8124a392)
Location: include/linux/pagemap.h:413
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812633dc)
Location: include/linux/pagemap.h:413
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812647f6)
Location: include/linux/pagemap.h:413
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812b8df7)
Location: include/linux/pagemap.h:413
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/debug.c (ffffffff812587fc)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81271b8c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81273066)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812cace7)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
long unsigned int page_to_pgoff(struct page *page);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/debug.c (ffffffff81287111)
Location: include/linux/pagemap.h:464
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
Direct callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812a21bc)
Location: include/linux/pagemap.h:464
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812a4096)
Location: include/linux/pagemap.h:464
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/hugetlb.c (ffffffff812c4082)
Location: include/linux/pagemap.h:464
Inline: True
```
```
In mm/memory-failure.c (ffffffff81300cdc)
Location: include/linux/pagemap.h:464
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
**Symbols:**

```
ffffffff81286fa0-ffffffff81287007: page_to_pgoff (STB_LOCAL)
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
In mm/debug.c (ffffffff8129137a)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812adaec)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812af966)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8130ce54)
Location: include/linux/pagemap.h:527
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_file
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex.c (ffffffff811588f0)
Location: include/linux/pagemap.h:544
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/debug.c (ffffffff812968a8)
Location: include/linux/pagemap.h:544
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812b2f94)
Location: include/linux/pagemap.h:544
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812b4be4)
Location: include/linux/pagemap.h:544
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff813133ba)
Location: include/linux/pagemap.h:544
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex.c (ffffffff8117d7f7)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
```
```
In mm/debug.c (ffffffff812d70e5)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812f4b24)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff812f6a34)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff8135fe7a)
Location: include/linux/pagemap.h:543
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex/core.c (ffffffff811b2a63)
Location: include/linux/pagemap.h:793
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/debug.c (ffffffff8133696e)
Location: include/linux/pagemap.h:793
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81357d88)
Location: include/linux/pagemap.h:793
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8135bbd9)
Location: include/linux/pagemap.h:793
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/ksm.c (ffffffff813a04e8)
Location: include/linux/pagemap.h:793
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff813da5f1)
Location: include/linux/pagemap.h:793
Inline: True
Inline callers:
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In kernel/futex/core.c (ffffffff811f3903)
Location: include/linux/pagemap.h:789
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/debug.c (ffffffff813adc06)
Location: include/linux/pagemap.h:789
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff813d31c1)
Location: include/linux/pagemap.h:789
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffff813d6894)
Location: include/linux/pagemap.h:789
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
```
```
In mm/ksm.c (ffffffff8141fcf6)
Location: include/linux/pagemap.h:789
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff81460fb6)
Location: include/linux/pagemap.h:789
Inline: True
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
In kernel/futex/core.c (ffffffff8120808a)
Location: include/linux/pagemap.h:810
Inline: True
Inline callers:
  - kernel/futex/core.c:get_futex_key
```
```
In mm/debug.c (ffffffff813e1f97)
Location: include/linux/pagemap.h:810
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff814070e3)
Location: include/linux/pagemap.h:810
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff8140b3c3)
Location: include/linux/pagemap.h:810
Inline: True
Inline callers:
  - mm/rmap.c:vma_address
```
```
In mm/ksm.c (ffffffff8145490a)
Location: include/linux/pagemap.h:810
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff81497ad9)
Location: include/linux/pagemap.h:810
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
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
In mm/debug.c (ffffffff8140c7b8)
Location: include/linux/pagemap.h:900
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81433786)
Location: include/linux/pagemap.h:900
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:vma_address
```
```
In mm/rmap.c (ffffffff81437d06)
Location: include/linux/pagemap.h:900
Inline: True
Inline callers:
  - mm/rmap.c:vma_address
```
```
In mm/ksm.c (ffffffff8148fb44)
Location: include/linux/pagemap.h:900
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/memory-failure.c (ffffffff814c71e0)
Location: include/linux/pagemap.h:900
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs_anon
  - mm/memory-failure.c:collect_procs_anon
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
In mm/debug.c (ffff8000102f07c8)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffff80001030768c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffff800010308db0)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffff80001036eb28)
Location: include/linux/pagemap.h:423
Inline: True
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
In mm/debug.c (c0513d34)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (c0524ef0)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (c0525908)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
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
In mm/debug.c (c0000000003b514c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (c0000000003d61a8)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (c0000000003d804c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (c00000000045f230)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
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
In mm/debug.c (ffffffe000203fd2)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffe00021283e)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
```
```
In mm/rmap.c (ffffffe0002133e4)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
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
In mm/debug.c (ffffffff81250e4c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff8126a1dc)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8126b6b6)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812c32c7)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/debug.c (ffffffff81243d8c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff8125c3cc)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff8125d956)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812b4307)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:add_to_kill
  - mm/memory-failure.c:add_to_kill
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
In mm/debug.c (ffffffff8124ebec)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff81267f7c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81269456)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812c10d7)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
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
In mm/debug.c (ffffffff8125e56c)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
  - mm/debug.c:__dump_page
```
```
In mm/page_vma_mapped.c (ffffffff812778fc)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_mapped_in_vma
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/rmap.c (ffffffff81278f86)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_file
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:rmap_walk_anon
  - mm/rmap.c:page_address_in_vma
  - mm/rmap.c:page_address_in_vma
```
```
In mm/memory-failure.c (ffffffff812d1b97)
Location: include/linux/pagemap.h:423
Inline: True
Inline callers:
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:collect_procs
  - mm/memory-failure.c:dev_pagemap_mapping_shift
  - mm/memory-failure.c:dev_pagemap_mapping_shift
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
