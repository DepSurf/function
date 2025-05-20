# Function: <code>alloc_pages_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *alloc_pages_node(int nid, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810142ae)
Location: include/linux/gfp.h:443
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810345df)
Location: include/linux/gfp.h:443
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034e69)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff811468f9)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f6bb)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81185182)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff81197320)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_kmem_pages_node
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
Direct callers:
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811b0ae0)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811cf141)
Location: include/linux/gfp.h:443
Inline: True
```
```
In mm/hugetlb.c (ffffffff811daefa)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/sparse-vmemmap.c (ffffffff8181f145)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/migrate.c (ffffffff811f325a)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff813c3bf3)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff815350c5)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815357e1)
Location: include/linux/gfp.h:443
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4d12)
Location: include/linux/gfp.h:443
Inline: True
```
**Symbols:**

```
ffffffff81197320-ffffffff81197368: alloc_pages_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *alloc_pages_node(int nid, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81013cfe)
Location: include/linux/gfp.h:454
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337a9)
Location: include/linux/gfp.h:454
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034046)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/fork.c (ffffffff81080412)
Location: include/linux/gfp.h:454
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f149)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81157a3d)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117cda2)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81196fe3)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff811ab3d4)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
Direct callers:
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811c9d07)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811ec2cd)
Location: include/linux/gfp.h:454
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f906f)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/sparse-vmemmap.c (ffffffff818995ed)
Location: include/linux/gfp.h:454
Inline: True
```
```
In mm/slub.c (ffffffff81206aaa)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff81213010)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff81407f6b)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff81589975)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158d309)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8159282c)
Location: include/linux/gfp.h:454
Inline: True
```
**Symbols:**

```
ffffffff811ab300-ffffffff811ab348: alloc_pages_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct page *alloc_pages_node(int nid, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81013e7e)
Location: include/linux/gfp.h:447
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810333d9)
Location: include/linux/gfp.h:447
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033c76)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff811592e9)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81162c73)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811889b6)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811a69f3)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff811bb9ae)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
Direct callers:
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811d9dfc)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811fd56d)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/hugetlb.c (ffffffff81209c5f)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/sparse-vmemmap.c (ffffffff818cdca5)
Location: include/linux/gfp.h:447
Inline: True
```
```
In mm/slub.c (ffffffff8121887a)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff81225380)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff81422c17)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff815b7035)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82015bc0)
Location: include/linux/gfp.h:447
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c00ec)
Location: include/linux/gfp.h:447
Inline: True
```
**Symbols:**

```
ffffffff811bb8e0-ffffffff811bb928: alloc_pages_node (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (ffffffff810124ce)
Location: include/linux/gfp.h:492
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810315a9)
Location: include/linux/gfp.h:492
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81031d91)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e8ec)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81166115)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b6e3)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811ae1e3)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff811c3c89)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811e34b4)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff8120826c)
Location: include/linux/gfp.h:492
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81905150)
Location: include/linux/gfp.h:492
Inline: True
```
```
In mm/slub.c (ffffffff81224465)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff81230a6d)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814327aa)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff815cce26)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f7882)
Location: include/linux/gfp.h:492
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5c0f)
Location: include/linux/gfp.h:492
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
In arch/x86/events/intel/pt.c (ffffffff8101259e)
Location: include/linux/gfp.h:477
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337ea)
Location: include/linux/gfp.h:477
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340c8)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108039a)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b8ec)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811730a8)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8119918e)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811c1e53)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff811d8a29)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811f8d7f)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff81221333)
Location: include/linux/gfp.h:477
Inline: True
```
```
In mm/mempolicy.c (ffffffff81235df1)
Location: include/linux/gfp.h:477
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff8198f13f)
Location: include/linux/gfp.h:477
Inline: True
```
```
In mm/slub.c (ffffffff8123fac5)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff8124e7e9)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:new_page_node
```
```
In block/blk-mq.c (ffffffff8145e37a)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff81633c26)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700f63)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c9bf)
Location: include/linux/gfp.h:477
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
In arch/x86/events/intel/pt.c (ffffffff81012f6b)
Location: include/linux/gfp.h:477
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b66)
Location: include/linux/gfp.h:477
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8110cdd0)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff8117ad5c)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81182088)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae86d)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811e2213)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff811f9bb6)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff8121a771)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff812431f3)
Location: include/linux/gfp.h:477
Inline: True
```
```
In mm/mempolicy.c (ffffffff81258e6a)
Location: include/linux/gfp.h:477
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff819eb9bf)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff81263138)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812725f2)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff81491cb3)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff8166edc5)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272ac77)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677e0d)
Location: include/linux/gfp.h:477
Inline: True
```
```
In net/core/page_pool.c (ffffffff818bd6f3)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff8101393b)
Location: include/linux/gfp.h:494
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d46)
Location: include/linux/gfp.h:494
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81118ad2)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811877cc)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8118fa48)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcf01)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811f2683)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page_alloc.c (ffffffff8120c256)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff8122d721)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff812578fe)
Location: include/linux/gfp.h:494
Inline: True
```
```
In mm/mempolicy.c (ffffffff8126d25c)
Location: include/linux/gfp.h:494
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a26c42)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812779c8)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff81286bec)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814ab720)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/blk-zoned.c (ffffffff814cbd29)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/iommu/dmar.c (ffffffff8168d319)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81690265)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff81694082)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696eed)
Location: include/linux/gfp.h:494
Inline: True
```
```
In net/core/xdp.c (ffffffff818e1bc8)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818e4ad1)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff81014dab)
Location: include/linux/gfp.h:494
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037ea6)
Location: include/linux/gfp.h:494
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81122f4a)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81194cfc)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119d456)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc5a4)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120a353)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8123d44e)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff8126a650)
Location: include/linux/gfp.h:494
Inline: True
```
```
In mm/page_alloc.c (ffffffff812724b9)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff81288a09)
Location: include/linux/gfp.h:494
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a974e4)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff81294116)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812a118c)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814d9910)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816c4d23)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c8405)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc992)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf85f)
Location: include/linux/gfp.h:494
Inline: True
```
```
In net/core/xdp.c (ffffffff81930647)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff819342c7)
Location: include/linux/gfp.h:494
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff810156fb)
Location: include/linux/gfp.h:523
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038676)
Location: include/linux/gfp.h:523
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112f38a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811a07bc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a8e17)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8b6f)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81217633)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8124b89e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff81279561)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (ffffffff81281319)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff81298579)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81acedc6)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812a439b)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812b259c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814f2cd0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816e7c53)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eb3b5)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f01cf)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f369f)
Location: include/linux/gfp.h:523
Inline: True
```
```
In net/core/xdp.c (ffffffff819627a7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81966ef7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff81016bfb)
Location: include/linux/gfp.h:530
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b0c3)
Location: include/linux/gfp.h:530
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8113dd6f)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6d9c)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c10f7)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4f75)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e335)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81242ee3)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8127984a)
Location: include/linux/gfp.h:530
Inline: True
```
```
In mm/vmalloc.c (ffffffff812ac3b3)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812b37fa)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff812cbce9)
Location: include/linux/gfp.h:530
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7788)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812d7623)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812e7b3c)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff81553293)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dma-iommu.c (ffffffff8179218e)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e793)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1d85e)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a78b2)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab93f)
Location: include/linux/gfp.h:530
Inline: True
```
```
In net/core/xdp.c (ffffffff81a356f7)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3a617)
Location: include/linux/gfp.h:530
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff8101709b)
Location: include/linux/gfp.h:532
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b8d3)
Location: include/linux/gfp.h:532
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811385b4)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff81139be3)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4953)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bed27)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3905)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff812210c1)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8124d583)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff812840ba)
Location: include/linux/gfp.h:532
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b7945)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812bf2ca)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/sparse-vmemmap.c (ffffffff81c404bc)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812e4b5c)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812f2f2b)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff8156f923)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac4ea)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b57a)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b3752)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7d1f)
Location: include/linux/gfp.h:532
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be964)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81a37a97)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3cb38)
Location: include/linux/gfp.h:532
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff8101818b)
Location: include/linux/gfp.h:557
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810340eb)
Location: include/linux/gfp.h:557
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d26d)
Location: include/linux/gfp.h:557
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811396d2)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ad03)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3d13)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bf5f7)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e7f)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff81224b75)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81251ec3)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81288cfa)
Location: include/linux/gfp.h:557
Inline: True
```
```
In mm/vmalloc.c (ffffffff812bd325)
Location: include/linux/gfp.h:557
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c4371)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/sparse-vmemmap.c (ffffffff81c32564)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812ec7ec)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812f92ac)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff815777d3)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178f3ba)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff83215f0f)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81796882)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179ae8e)
Location: include/linux/gfp.h:557
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1804)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81a1ec27)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a24736)
Location: include/linux/gfp.h:557
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff81019a6f)
Location: include/linux/gfp.h:578
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8103938b)
Location: include/linux/gfp.h:578
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042daa)
Location: include/linux/gfp.h:578
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8115c6a0)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8115dc33)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811ddce7)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811e9edc)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812270bc)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff8125cab5)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8128d750)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff812c878a)
Location: include/linux/gfp.h:578
Inline: True
```
```
In mm/vmalloc.c (ffffffff812ffa7b)
Location: include/linux/gfp.h:578
Inline: True
```
```
In mm/page_alloc.c (ffffffff8130822d)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/sparse-vmemmap.c (ffffffff81d510a7)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
```
```
In mm/slub.c (ffffffff8133511e)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff8133db05)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page_thp
```
```
In block/blk-mq.c (ffffffff815dc4f3)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816cda)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a387)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e812)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818239be)
Location: include/linux/gfp.h:578
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182ae74)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81ad3ced)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81ad8dae)
Location: include/linux/gfp.h:578
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff8101bf7f)
Location: include/linux/gfp.h:604
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810401ff)
Location: include/linux/gfp.h:604
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104aebe)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff8118642b)
Location: include/linux/gfp.h:604
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff81187bf3)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81214e31)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81221d1b)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81266c03)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff812a6942)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff812e24f0)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81326139)
Location: include/linux/gfp.h:604
Inline: True
```
```
In mm/vmalloc.c (ffffffff81360721)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_area_alloc_pages
```
```
In mm/page_alloc.c (ffffffff8137052f)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/sparse-vmemmap.c (ffffffff81f212d0)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
```
```
In mm/slub.c (ffffffff813a4858)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In block/blk-mq.c (ffffffff81689e54)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957ce0)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195bd69)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195eb89)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962e2e)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c291)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81c5207d)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81c59ded)
Location: include/linux/gfp.h:604
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff810202cf)
Location: include/linux/gfp.h:254
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049469)
Location: include/linux/gfp.h:254
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056936)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811c1e2b)
Location: include/linux/gfp.h:254
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811c386e)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e4f1)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8126cca2)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8889)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81304e02)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8134ac60)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8139c89c)
Location: include/linux/gfp.h:254
Inline: True
```
```
In mm/slab_common.c (ffffffff813a12ef)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (ffffffff813e2898)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813ed4b2)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413c61)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/sparse-vmemmap.c (ffffffff820cb16e)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In block/blk-mq.c (ffffffff817483d7)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abeca0)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac3585)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:copy_context_table
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/iommu.c:iommu_context_addr
```
```
In drivers/iommu/intel/pasid.c (ffffffff81ac6624)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbe9c)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad4832)
Location: include/linux/gfp.h:254
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da4580)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (ffffffff81e0730d)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e10185)
Location: include/linux/gfp.h:254
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
In arch/x86/events/intel/pt.c (ffffffff8102001f)
Location: include/linux/gfp.h:254
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810496c2)
Location: include/linux/gfp.h:254
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057906)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811d4963)
Location: include/linux/gfp.h:254
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811d63be)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff812756d1)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81283e32)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dbec9)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81333792)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8137bc90)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff813cf97c)
Location: include/linux/gfp.h:254
Inline: True
```
```
In mm/slab_common.c (ffffffff813d456f)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (ffffffff81417459)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff814222cc)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447202)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/sparse-vmemmap.c (ffffffff8214f3fe)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In block/blk-mq.c (ffffffff81784ae4)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c70)
Location: include/linux/gfp.h:254
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07ad8)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b640)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f0c4)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b13216)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18a1c)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23002)
Location: include/linux/gfp.h:254
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e131d4)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (ffffffff81e79b1d)
Location: include/linux/gfp.h:254
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e83a25)
Location: include/linux/gfp.h:254
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
In arch/x86/events/intel/pt.c (ffffffff8102610f)
Location: include/linux/gfp.h:255
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050aaa)
Location: include/linux/gfp.h:255
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105eba6)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811e9853)
Location: include/linux/gfp.h:255
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb3ee)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fd8b)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8129edc2)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9fa9)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81357e82)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff813a4ed0)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff813fa57c)
Location: include/linux/gfp.h:255
Inline: True
```
```
In mm/vmalloc.c (ffffffff81443f69)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144f193)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/slub.c (ffffffff81454f0b)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/hugetlb_vmemmap.c (ffffffff814807db)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
```
```
In mm/sparse-vmemmap.c (ffffffff822322ce)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In block/blk-mq.c (ffffffff817c6ff4)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b57553)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac46)
Location: include/linux/gfp.h:255
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb08)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f6df)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b639b4)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67e45)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e38b)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79972)
Location: include/linux/gfp.h:255
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed0394)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (ffffffff81f39c3d)
Location: include/linux/gfp.h:255
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81f43e45)
Location: include/linux/gfp.h:255
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
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (ffff800010194df8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffff800010219fa4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffff800010225b74)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffff800010259bc8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffff8000102a2064)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffff8000102e1b84)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffff80001030ffc0)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (ffff800010318fd4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffff800010338910)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/sparse-vmemmap.c (ffff800010da09d4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffff800010345798)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffff800010352de4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffff8000105f2528)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000106713c0)
Location: include/linux/gfp.h:523
Inline: True
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
  - drivers/irqchip/irq-gic-v3-its.c:its_probe_one
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca584)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb3c4)
Location: include/linux/gfp.h:523
Inline: True
```
```
In net/core/xdp.c (ffff800010c070c4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffff800010c0cef8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffff8000106713c0-ffff8000106713f8: alloc_pages_node.constprop.0 (STB_LOCAL)
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
In init/do_mounts.c (c1501710)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/arm/kernel/signal.c (c030ec98)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:get_signal_page
```
```
In arch/arm/mm/dma-mapping.c (c031e24c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
```
```
In arch/arm/mm/fault-armv.c (c1507da8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
```
```
In kernel/fork.c (c03522bc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/power/snapshot.c (c03bfbb4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/dma/direct.c (c03e1bfc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/kexec_core.c (c040f70c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (c044ab20)
Location: include/linux/gfp.h:523
Inline: True
```
```
In kernel/trace/ring_buffer.c (c0457490)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (c0465234)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (c048bb58)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (c04d2694)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (c04d66ac)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c04de244)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
```
```
In mm/mempool.c (c04e2294)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/readahead.c (c04eaff8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/shmem.c (c04fa8f4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
```
```
In mm/percpu.c (c0505d44)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/slab_common.c (c0509cbc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (c051b708)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (c052c464)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (c0533abc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (c053a308)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (c053fd9c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/ksm.c (c0547d7c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (c05495fc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/swap_cgroup.c (c055dcfc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (c055f970)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (c0560b8c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (c0563168)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In mm/userfaultfd.c (c0563cf4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (c0576ebc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (c06b5a6c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (c06bf990)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (c06c2a0c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (c06c7c74)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (c06cfbc0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (c06f0050)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (c071ed7c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (c078a9e0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In block/blk-mq.c (c079e608)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In lib/scatterlist.c (c07d3684)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (c07d4360)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081babc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7c8c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/mv_xor.c (c0925378)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
```
```
In drivers/virtio/virtio_balloon.c (c09478b0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (c09af088)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (c09b3ef8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (c09b6360)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (c09b6ab0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (c09b7d38)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/io-pgtable-arm.c (c09bff08)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/tegra-smmu.c (c09c8880)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
```
```
In drivers/lightnvm/core.c (c09cddb8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (c09f6044)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (c0a08f10)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/sg.c (c0a63350)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/md/md.c (c0bccd4c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (c0bd9f34)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (c0be9408)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (c0c3d6fc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (c15a8b14)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (c0cc8fa8)
Location: include/linux/gfp.h:523
Inline: True
```
```
In net/core/skbuff.c (c0cd2a9c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (c0d19fa4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c0d202ac)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (c0d24c08)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/powerpc/kernel/iommu.c (c000000000052f00)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_alloc_coherent
  - arch/powerpc/kernel/iommu.c:iommu_init_table
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bf0bc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d6308)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000dadd8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_alloc_tce_level
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012c23c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:thread_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
```
```
In kernel/dma/direct.c (c0000000001f50d4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (c00000000029c094)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (c0000000002ab318)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (c0000000002fd448)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (c000000000353dd0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (c0000000003a19fc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (c0000000003e12f4)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (c0000000003eba10)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (c00000000041173c)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/sparse-vmemmap.c (c000000000eed7c8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (c0000000004229a4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (c000000000439968)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (c0000000007897e0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In net/core/xdp.c (c000000000cf1968)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (c000000000cf7bb4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In init/do_mounts.c (ffffffe0000013dc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffe0000bfd7a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/dma/direct.c (ffffffe000126cbe)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/relay.c (ffffffe00016d3de)
Location: include/linux/gfp.h:523
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000177d1c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffe0001824b2)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffe0001d167c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffe0001d6f7c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
```
```
In mm/mempool.c (ffffffe0001d9f4e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/readahead.c (ffffffe0001e16e4)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/shmem.c (ffffffe0001ed7d8)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/percpu.c (ffffffe0001f88e0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/slab_common.c (ffffffe0001fb954)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/memory.c (ffffffe0002092c0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__pte_alloc
```
```
In mm/vmalloc.c (ffffffe0002184a8)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021ee2a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffe000222d2a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffe0002286fa)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/sparse-vmemmap.c (ffffffe000048d82)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffe00023629c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffe00023805e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/swap_cgroup.c (ffffffe000249c64)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffe00024c03c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffe00024e896)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffe00024f7da)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In mm/userfaultfd.c (ffffffe00024ff6c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffe00025fc9e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffe000366b54)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffe00036f122)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffe000372b14)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffe000377058)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffe00037e516)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffe00039814c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffe0003bffd8)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffe00042064c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In block/blk-mq.c (ffffffe000430da6)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In lib/scatterlist.c (ffffffe00045cc26)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffe00045d598)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8b7a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffe0005203a6)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffe0005657fc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b514)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056f052)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_auto_startup
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation
  - drivers/char/tpm/tpm2-cmd.c:tpm2_probe
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_shutdown
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_tpm_pt
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_seal_trusted
  - drivers/char/tpm/tpm2-cmd.c:tpm2_flush_context
  - drivers/char/tpm/tpm2-cmd.c:tpm2_get_random
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_extend
  - drivers/char/tpm/tpm2-cmd.c:tpm2_pcr_read
```
```
In drivers/char/tpm/tpm2-space.c (ffffffe00056fa74)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffe000570f3e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/lightnvm/core.c (ffffffe000574f12)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffe000591c0a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffe0005a2446)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/sg.c (ffffffe0005f4cc2)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/md/md.c (ffffffe0006de17e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffe0006eb1e0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f8d1a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In net/core/sock.c (ffffffe00073de0c)
Location: include/linux/gfp.h:523
Inline: True
```
```
In net/core/skbuff.c (ffffffe0007459ae)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffe00077d284)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffe0007854a6)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffe0007899a2)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff810156fb)
Location: include/linux/gfp.h:523
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387d6)
Location: include/linux/gfp.h:523
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81127a95)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81198ddc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a1437)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d118f)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120fc83)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81243eee)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff81271bb1)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (ffffffff81279969)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff81290b59)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dc36)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8129c97b)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812aab7c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814eb2b0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816ad733)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b0ce5)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b59bf)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8e8f)
Location: include/linux/gfp.h:523
Inline: True
```
```
In net/core/xdp.c (ffffffff81902777)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81906ec7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff810149cb)
Location: include/linux/gfp.h:523
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810281a5)
Location: include/linux/gfp.h:523
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8111a3ca)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c61c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81194407)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3f5f)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81202a13)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81236ebe)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff81263b21)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126b859)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff812827d9)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a17d)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8128e50b)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff8129c4d9)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814db800)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff8168b093)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e7e5)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816935ff)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696acf)
Location: include/linux/gfp.h:523
Inline: True
```
```
In drivers/hv/channel.c (ffffffff81850ed9)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_alloc_ring
```
```
In net/core/xdp.c (ffffffff818bc5a7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818c0cd7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff810156bb)
Location: include/linux/gfp.h:523
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038636)
Location: include/linux/gfp.h:523
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112585a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81196bac)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119f207)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cef5f)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120da23)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81241c8e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff8126f951)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (ffffffff81277709)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff8128e969)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81ada046)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8129a78b)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812a898c)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814e7340)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816db913)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816df075)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3e8f)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e735f)
Location: include/linux/gfp.h:523
Inline: True
```
```
In net/core/xdp.c (ffffffff819537a7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81957ef7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In arch/x86/events/intel/pt.c (ffffffff810158fb)
Location: include/linux/gfp.h:523
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039636)
Location: include/linux/gfp.h:523
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81131e9a)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811a47bc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811acf56)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd1ef)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8121c8d3)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8125142e)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff8127f353)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/page_alloc.c (ffffffff812872f9)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff8129e869)
Location: include/linux/gfp.h:523
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81ae64fc)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812aa66b)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
```
```
In mm/migrate.c (ffffffff812b8cac)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff815002e0)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816f5ee3)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f9685)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe555)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701a5f)
Location: include/linux/gfp.h:523
Inline: True
```
```
In net/core/xdp.c (ffffffff819752c7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81979fe7)
Location: include/linux/gfp.h:523
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
</ul>
