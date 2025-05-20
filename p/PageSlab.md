# Function: <code>PageSlab</code>

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
In arch/x86/mm/gup.c (ffffffff810716c0)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In kernel/resource.c (ffffffff81086803)
Location: include/linux/page-flags.h:217
Inline: True
```
```
In mm/swap.c (ffffffff8119d324)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/swap.c:__get_page_tail
  - mm/swap.c:__get_page_tail
  - mm/swap.c:__get_page_tail
```
```
In mm/util.c (ffffffff811ac0e5)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/gup.c (ffffffff811ba6d7)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/hugetlb.c (ffffffff811df5c8)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/sparse.c (ffffffff811e38f5)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff811e8aa0)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/slub.c:ksize
  - mm/slub.c:check_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:kfree
```
```
In mm/huge_memory.c (ffffffff811f6336)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/huge_memory.c:follow_trans_huge_pmd
```
```
In mm/memory-failure.c (ffffffff81201fb7)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In fs/proc/page.c (ffffffff81287ffc)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
  - fs/proc/page.c:stable_page_flags
```
```
In lib/scatterlist.c (ffffffff813fa225)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff815dc818)
Location: include/linux/page-flags.h:217
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff81089845)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In mm/util.c (ffffffff811c47f7)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff811d447e)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/sparse.c (ffffffff8120233c)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff8120ae07)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff81226e06)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:shake_page
```
```
In mm/usercopy.c (ffffffff8122e6a0)
Location: include/linux/page-flags.h:265
Inline: True
```
```
In fs/proc/page.c (ffffffff812b5427)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff81441273)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81636591)
Location: include/linux/page-flags.h:265
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff8108e78f)
Location: include/linux/page-flags.h:275
Inline: True
```
```
In mm/util.c (ffffffff811d48e7)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff811e44d8)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/sparse.c (ffffffff81214176)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff8121ce51)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:kmem_cache_free_bulk
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff812393a2)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:shake_page
```
```
In mm/usercopy.c (ffffffff81240bca)
Location: include/linux/page-flags.h:275
Inline: True
```
```
In fs/proc/page.c (ffffffff812cac87)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff8145e413)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81667630)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff8108b783)
Location: include/linux/page-flags.h:275
Inline: True
```
```
In mm/util.c (ffffffff811dd667)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff811ee92e)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/sparse.c (ffffffff8121f56d)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81228f31)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff8124430b)
Location: include/linux/page-flags.h:275
Inline: True
```
```
In mm/usercopy.c (ffffffff8124c8cd)
Location: include/linux/page-flags.h:275
Inline: True
```
```
In fs/proc/page.c (ffffffff812d8117)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff81463425)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff8167bdcb)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff81092503)
Location: include/linux/page-flags.h:276
Inline: True
```
```
In mm/util.c (ffffffff811f30e7)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff81204d9e)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/sparse.c (ffffffff8123a7a3)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81242e21)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff8126418b)
Location: include/linux/page-flags.h:276
Inline: True
```
```
In mm/usercopy.c (ffffffff8126cd8d)
Location: include/linux/page-flags.h:276
Inline: True
```
```
In fs/proc/page.c (ffffffff812fc817)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff8148f335)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff816e5471)
Location: include/linux/page-flags.h:276
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff81095ef3)
Location: include/linux/page-flags.h:283
Inline: True
```
```
In mm/util.c (ffffffff81214124)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff81225c4e)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/sparse.c (ffffffff8125dd21)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff81268801)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff812883eb)
Location: include/linux/page-flags.h:283
Inline: True
```
```
In mm/usercopy.c (ffffffff812919eb)
Location: include/linux/page-flags.h:283
Inline: True
```
```
In fs/proc/page.c (ffffffff8132a421)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff814c3f45)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81721d11)
Location: include/linux/page-flags.h:283
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff8109e263)
Location: include/linux/page-flags.h:294
Inline: True
```
```
In mm/util.c (ffffffff81226ff4)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff8123931c)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/sparse.c (ffffffff81272577)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/slub.c (ffffffff8127d2a1)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:ksize
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff8129d3bb)
Location: include/linux/page-flags.h:294
Inline: True
```
```
In mm/usercopy.c (ffffffff812a6a28)
Location: include/linux/page-flags.h:294
Inline: True
```
```
In fs/proc/page.c (ffffffff81341741)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff814d866a)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff817443e1)
Location: include/linux/page-flags.h:294
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff810a27c4)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffffffff81236da4)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff8124a37c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81255f46)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffff81298904)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffffffff812b25b3)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812b84ab)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (ffffffff812c210d)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffffffff81369b61)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff81504661)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff817801c1)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff810a8d94)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffffffff81244f64)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff812587be)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812644d6)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffff812a8764)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffffffff812c6f17)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812ca38b)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (ffffffff812d403d)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffffffff81381d81)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff81522bc5)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff817a3e81)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff810b01c4)
Location: include/linux/page-flags.h:333
Inline: True
```
```
In mm/util.c (ffffffff81272c14)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff8128709a)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81292ef1)
Location: include/linux/page-flags.h:333
Inline: True
```
```
In mm/slub.c (ffffffff812ddaf7)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
  - mm/slub.c:cache_from_obj
```
```
In mm/memcontrol.c (ffffffff812fc837)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff813000a5)
Location: include/linux/page-flags.h:333
Inline: True
```
```
In mm/usercopy.c (ffffffff81309d9a)
Location: include/linux/page-flags.h:333
Inline: True
```
```
In fs/proc/page.c (ffffffff813cc3b1)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff81585c05)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81869415)
Location: include/linux/page-flags.h:333
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff810ab8e4)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In mm/util.c (ffffffff8127d2c4)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff8129134f)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8129d78f)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In mm/slub.c (ffffffff812e6909)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff8130c3d5)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In mm/usercopy.c (ffffffff81315bba)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In fs/proc/page.c (ffffffff813ddff1)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff815a2ce5)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81878225)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
```
```
In net/socket.c (ffffffff819de925)
Location: include/linux/page-flags.h:342
Inline: True
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
In kernel/resource.c (ffffffff810acc64)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In mm/util.c (ffffffff81282458)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/slab_common.c (ffffffff8128d53f)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/debug.c (ffffffff8129687d)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812a2e40)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffff812ee0c9)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff81312b35)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In mm/usercopy.c (ffffffff8131bdaa)
Location: include/linux/page-flags.h:342
Inline: True
```
```
In fs/proc/page.c (ffffffff813e4de1)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff815a9c15)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff8185b697)
Location: include/linux/page-flags.h:342
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In net/socket.c (ffffffff819c48e2)
Location: include/linux/page-flags.h:342
Inline: True
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
In kernel/resource.c (ffffffff810be7d4)
Location: include/linux/page-flags.h:356
Inline: True
```
```
In mm/util.c (ffffffff812c04c8)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/slab_common.c (ffffffff812cc9e3)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_dump_obj
```
```
In mm/debug.c (ffffffff812d70b6)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff812dd40e)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/memory.c:validate_page_before_insert
```
```
In mm/slub.c (ffffffff813364a7)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:build_detached_freelist
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memory-failure.c (ffffffff813603c5)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/usercopy.c (ffffffff8136908a)
Location: include/linux/page-flags.h:356
Inline: True
```
```
In fs/proc/page.c (ffffffff814369b1)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/ata/libata-sff.c (ffffffff818ea1c7)
Location: include/linux/page-flags.h:356
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_xfer
```
```
In net/socket.c (ffffffff81a73d48)
Location: include/linux/page-flags.h:356
Inline: True
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
In kernel/resource.c (ffffffff810d5d11)
Location: include/linux/page-flags.h:506
Inline: True
```
```
In mm/debug.c (ffffffff8133693d)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff81345222)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
```
In mm/memory-failure.c (ffffffff813dcd11)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff814b1141)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/ata/libata-sff.c (ffffffff81a3b8d6)
Location: include/linux/page-flags.h:506
Inline: True
```
```
In net/socket.c (ffffffff81be77e8)
Location: include/linux/page-flags.h:506
Inline: True
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
In kernel/resource.c (ffffffff810f4fc1)
Location: include/linux/page-flags.h:485
Inline: True
```
```
In mm/debug.c (ffffffff813adbcb)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813bd44c)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
```
In mm/migrate.c (ffffffff81433457)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/migrate.c:isolate_movable_page
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memory-failure.c (ffffffff8146223b)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff81547b01)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/ata/libata-sff.c (ffffffff81bc0f56)
Location: include/linux/page-flags.h:485
Inline: True
```
```
In net/socket.c (ffffffff81d93ff8)
Location: include/linux/page-flags.h:485
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
In kernel/resource.c (ffffffff811013f5)
Location: include/linux/page-flags.h:479
Inline: True
```
```
In mm/debug.c (ffffffff813e1f5b)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff813f2160)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In mm/memory-failure.c (ffffffff81498452)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In fs/proc/page.c (ffffffff8157f721)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/ata/libata-sff.c (ffffffff81c18b05)
Location: include/linux/page-flags.h:479
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e14b5c)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
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
In kernel/resource.c (ffffffff8110ab21)
Location: include/linux/page-flags.h:481
Inline: True
```
```
In mm/debug.c (ffffffff8140c783)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory-failure.c (ffffffff814c872f)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:hwpoison_user_mappings
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
```
In fs/proc/page.c (ffffffff815b8161)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In drivers/ata/libata-sff.c (ffffffff81c6d855)
Location: include/linux/page-flags.h:481
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed215c)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
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
In kernel/resource.c (ffff8000101000b4)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffff8000102d7fb8)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffff8000102f0790)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffff8000102fb1d0)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffff80001034a10c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffff800010369cc4)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffff80001036dc90)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (ffff80001037a0b0)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffff80001044ff88)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In crypto/scatterwalk.c (ffff8000105bb11c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (ffff8000105bc638)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (ffff8000105bd560)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (ffff8000105bee58)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In lib/scatterlist.c (ffff80001062c06c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffff8000109af744)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (c035cc7c)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (c04ff420)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (c0513cf8)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0519a1c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:insert_page
```
```
In mm/slub.c (c054e9fc)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (c055b02c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/usercopy.c (c05652c4)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (c061320c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In crypto/scatterwalk.c (c0769400)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c076a72c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c076b308)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c076ce80)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In lib/scatterlist.c (c07d2da8)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (c0a7f148)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (c000000000147cc0)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (c000000000397abc)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (c0000000003b5108)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (c0000000003c5f2c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (c000000000429000)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (c000000000458848)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (c00000000045e3cc)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (c00000000046d474)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (c000000000567f9c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In crypto/scatterwalk.c (c000000000741820)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/scatterwalk.c:scatterwalk_copychunks
```
```
In crypto/ablkcipher.c (c0000000007435b4)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/ablkcipher.c:ablkcipher_walk_done
```
```
In crypto/blkcipher.c (c000000000744690)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/blkcipher.c:blkcipher_walk_done
```
```
In crypto/skcipher.c (c000000000746518)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_walk_done
```
```
In lib/scatterlist.c (c0000000007ce88c)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (c000000000a77bc0)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffe0000c803e)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffffffe0001f288a)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffe000203fa4)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffe00020a986)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffe00023ba8a)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffffffe000247556)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/usercopy.c (ffffffe00025128c)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffffffe0002e318e)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffe00045c266)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffe00060cb76)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff810a26b4)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffffffff8123d5b4)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff81250e0e)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8125cb26)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffff812a0d44)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffffffff812bf4f7)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812c296b)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (ffffffff812cc61d)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffffffff8137a361)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff8151b1a5)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81768f41)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff81091094)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffffffff812305b4)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff81243d4e)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8124f005)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffff81292824)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffffffff812b05e7)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812b39bb)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (ffffffff812bd48d)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffffffff8136ae31)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff8150b495)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81748da1)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff810a2664)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffffffff8123b354)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff8124ebae)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8125a8c6)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffff8129eb54)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffffffff812bd307)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812c077b)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (ffffffff812ca42d)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffffffff81377e31)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff81517235)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff81798d01)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
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
In kernel/resource.c (ffffffff810aa6a4)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/util.c (ffffffff8124aa64)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/util.c:page_mapping
```
```
In mm/debug.c (ffffffff8125e52e)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/debug.c:__dump_page
```
```
In mm/memory.c (ffffffff8126a2a6)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In mm/slub.c (ffffffff812aec34)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:__ksize
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:check_slab
```
```
In mm/memcontrol.c (ffffffff812cdb67)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/memory-failure.c (ffffffff812d123b)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In mm/usercopy.c (ffffffff812db12d)
Location: include/linux/page-flags.h:325
Inline: True
```
```
In fs/proc/page.c (ffffffff8138b8e1)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:stable_page_flags
  - fs/proc/page.c:kpagecount_read
```
```
In lib/scatterlist.c (ffffffff8153099d)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
```
In drivers/ata/libata-sff.c (ffffffff817b2b81)
Location: include/linux/page-flags.h:325
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
```
</details>
</li>
</ul>

## Differences
