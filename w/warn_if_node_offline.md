# Function: <code>warn_if_node_offline</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811c1e40)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811c3881)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/filemap.c (ffffffff8135a0cd)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/slab_common.c (ffffffff813a1307)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (ffffffff813e28a5)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813ed4c3)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413c68)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff814187e8)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_alloc_folio
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/slub.c (ffffffff81427860)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In block/blk-mq.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad4846)
Location: include/linux/gfp.h:213
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da4593)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In net/core/page_pool.c (ffffffff81e1019b)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_page_order
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
In arch/x86/events/intel/ds.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811d4978)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811d63d1)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/filemap.c (ffffffff8138bb2d)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/slab_common.c (ffffffff813d4583)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (ffffffff81417460)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff814222dd)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447368)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144bd3b)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_alloc_folio
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In mm/slub.c (ffffffff8145cdd0)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_folio
```
```
In block/blk-mq.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c7c)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07d25)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f0d5)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23016)
Location: include/linux/gfp.h:213
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e131e4)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (0)
Location: include/linux/gfp.h:213
Inline: True
```
```
In net/core/page_pool.c (ffffffff81e83a37)
Location: include/linux/gfp.h:213
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_page_order
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
In arch/x86/events/intel/ds.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811e9868)
Location: include/linux/gfp.h:214
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb401)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In mm/filemap.c (ffffffff813b569d)
Location: include/linux/gfp.h:214
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In mm/vmalloc.c (ffffffff81443f70)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144f1a4)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/slub.c (ffffffff81454f21)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In mm/mempolicy.c (ffffffff81485a08)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_mpol
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_folio
```
```
In block/blk-mq.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac52)
Location: include/linux/gfp.h:214
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bd55)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b639c5)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79986)
Location: include/linux/gfp.h:214
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed03a4)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (0)
Location: include/linux/gfp.h:214
Inline: True
```
```
In net/core/page_pool.c (ffffffff81f43e57)
Location: include/linux/gfp.h:214
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
</details>
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
