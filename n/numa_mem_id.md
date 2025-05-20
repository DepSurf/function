# Function: <code>numa_mem_id</code>

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
In arch/x86/events/intel/pt.c (ffffffff81014353)
Location: include/linux/topology.h:166
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034964)
Location: include/linux/topology.h:166
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034edc)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff8114694e)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f778)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811851cf)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/memremap.c (ffffffff8118b738)
Location: include/linux/topology.h:166
Inline: True
```
```
In mm/page_alloc.c (ffffffff8119735d)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_kmem_pages_node
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/percpu.c (ffffffff811b0b45)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:166
Inline: True
```
```
In mm/hugetlb.c (ffffffff811daf47)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811e1ce1)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff8181f14a)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff811eaa1f)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff811f3679)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff813c3c43)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff81535156)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535832)
Location: include/linux/topology.h:166
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4d17)
Location: include/linux/topology.h:166
Inline: True
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
In arch/x86/events/intel/pt.c (ffffffff81013da9)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033b16)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340bf)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/fork.c (ffffffff810809d1)
Location: include/linux/topology.h:162
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f198)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81157ae9)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117ce60)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8119702a)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/memremap.c (ffffffff8119e0dd)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811ab3ef)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/percpu.c (ffffffff811c9d71)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f90c1)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff812006d3)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff818995f2)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/slub.c (ffffffff81206af9)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81213517)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff81407fb7)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff81589a00)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158d64f)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592937)
Location: include/linux/topology.h:162
Inline: True
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
In arch/x86/events/intel/pt.c (ffffffff81013f26)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103373a)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033cee)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff81159332)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81162d19)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188a72)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811a6a34)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/memremap.c (ffffffff811adb0e)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811bb9c9)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/percpu.c (ffffffff811d9e66)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/hugetlb.c (ffffffff81209cb1)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81212033)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff818cdcaa)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/slub.c (ffffffff812188c3)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8122587c)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff81422c63)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff815b70b6)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82015bc5)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c01f4)
Location: include/linux/topology.h:162
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
In arch/x86/events/intel/pt.c (ffffffff810124d3)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810315b0)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81031d96)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e8f1)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8116611a)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b6e8)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811ae213)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/memremap.c (ffffffff811b4f7f)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811c3c96)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811e34b9)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/hugetlb.c (ffffffff81214342)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff8121d3f3)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81905158)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/slub.c (ffffffff8122446d)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81230ee4)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814327b3)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff815cce2b)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f7887)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5c14)
Location: include/linux/topology.h:162
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
In arch/x86/events/intel/pt.c (ffffffff810125a3)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337f4)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340cd)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108039f)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b8f1)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811730ad)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199193)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811c1e83)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/memremap.c (ffffffff811c90b7)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811d8a36)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811f8d84)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/hugetlb.c (ffffffff8122ef02)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff812385e3)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff8198f149)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/slub.c (ffffffff8123facd)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8124ec8d)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:new_page_node
```
```
In mm/hmm.c (ffffffff8126db1f)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_pages_create
```
```
In block/blk-mq.c (ffffffff8145e383)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff81633c2b)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700f68)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c9c4)
Location: include/linux/topology.h:162
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
In arch/x86/events/intel/pt.c (ffffffff81012f73)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b6d)
Location: include/linux/topology.h:162
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8110cdd5)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff8117ae64)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8118208d)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae872)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811e2243)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/memremap.c (ffffffff811e99f5)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811f9bb6)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff8121a776)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/hugetlb.c (ffffffff81252820)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8125baf5)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff819eb9c5)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8126313d)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81272ace)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/hmm.c (ffffffff81292127)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_pages_create
```
```
In block/blk-mq.c (ffffffff81491cba)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff8166ee2f)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272ac7c)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677e12)
Location: include/linux/topology.h:162
Inline: True
```
```
In net/core/page_pool.c (ffffffff818bd6f8)
Location: include/linux/topology.h:162
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
In arch/x86/events/intel/pt.c (ffffffff81013943)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d4d)
Location: include/linux/topology.h:162
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81118ad7)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811878d4)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8118fa4d)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcf06)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811f26b3)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/memremap.c (ffffffff811fa4f1)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff8120c256)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff8122d726)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/hugetlb.c (ffffffff81266a83)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812703b5)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81a26c48)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812779cd)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81286bf1)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffffffff814ab727)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/blk-zoned.c (ffffffff814cbd32)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/iommu/dmar.c (ffffffff8168d388)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81690270)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff81694087)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ef2)
Location: include/linux/topology.h:162
Inline: True
```
```
In net/core/xdp.c (ffffffff818e1bc8)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818e4ad6)
Location: include/linux/topology.h:162
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
In arch/x86/events/intel/pt.c (ffffffff81014db3)
Location: include/linux/topology.h:162
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037ead)
Location: include/linux/topology.h:162
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81122f54)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81194e0e)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119d45b)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc5a9)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120a383)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8123d453)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:162
Inline: True
```
```
In mm/page_alloc.c (ffffffff812724b9)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff81281c99)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128bca5)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81a974ea)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8129411b)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812a1191)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff812c2b48)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/blk-mq.c (ffffffff814d9917)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816c4d91)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c8410)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc997)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf864)
Location: include/linux/topology.h:162
Inline: True
```
```
In net/core/xdp.c (ffffffff81930647)
Location: include/linux/topology.h:162
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff819342cc)
Location: include/linux/topology.h:162
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
In arch/x86/events/intel/pt.c (ffffffff81015703)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103867d)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112f394)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811a08ce)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a8e1c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8b74)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81217663)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8124b8a3)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff81281319)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff812916c4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8129b875)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81acedcc)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812a43a0)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812b25a1)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff812d49fe)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814f2cd7)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816e7cc1)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eb3c0)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f01d4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f36a4)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/xdp.c (ffffffff819627a7)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81966efc)
Location: include/linux/topology.h:177
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
In arch/x86/events/intel/pt.c (ffffffff81016c03)
Location: include/linux/topology.h:167
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b0c5)
Location: include/linux/topology.h:167
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8113dd79)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6eae)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c10fc)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4f7a)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e33e)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81242f13)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8127984f)
Location: include/linux/topology.h:167
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:167
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b37fa)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff812c4995)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812cf425)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81bc778e)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812d7629)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812e7b41)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff8130a52b)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff8155329c)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dma-iommu.c (ffffffff81792193)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e801)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1d863)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a78b7)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab944)
Location: include/linux/topology.h:167
Inline: True
```
```
In net/core/xdp.c (ffffffff81a356f7)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3a61c)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In arch/x86/events/intel/pt.c (ffffffff810170a3)
Location: include/linux/topology.h:167
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b8d5)
Location: include/linux/topology.h:167
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811385bd)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff81139be8)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4a64)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bed2c)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f390a)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff812210ca)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8124d5b3)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff812840bf)
Location: include/linux/topology.h:167
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:167
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bf2ca)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff812d0635)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812daef5)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81c404c2)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812e4b61)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812f322c)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff81315fdf)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In block/blk-mq.c (ffffffff8156f92c)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac551)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b57f)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b3757)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7d24)
Location: include/linux/topology.h:167
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be969)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81a37a97)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3cb3d)
Location: include/linux/topology.h:167
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In arch/x86/events/intel/pt.c (ffffffff81018193)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810340f2)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d273)
Location: include/linux/topology.h:168
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811396db)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ad08)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3e24)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bf5fc)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e84)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff81224b7e)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81251ef3)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81288cff)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/vmalloc.c (ffffffff812bd32c)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c4371)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff812d74d4)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812e2755)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81c3256a)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812ec7f1)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812f92b1)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff8131c210)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In block/blk-mq.c (ffffffff815777dc)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178f421)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff83215f14)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81796887)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179ae93)
Location: include/linux/topology.h:168
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1809)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/skbuff.c (ffffffff819d01bb)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81a1ec27)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a245ba)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In arch/x86/events/intel/pt.c (ffffffff81019a74)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039392)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042db0)
Location: include/linux/topology.h:168
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8115c6a9)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8115dc38)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811dddf8)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811e9ee1)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812270c1)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff8125cabe)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8128d783)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff812c878f)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/page_alloc.c (ffffffff8130822d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff8131df28)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81329a45)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81d510ad)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff81335123)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8133db12)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page_thp
```
```
In mm/memremap.c (ffffffff813694fc)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In block/blk-mq.c (ffffffff815dc4fc)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816d41)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a38c)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e817)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818239c3)
Location: include/linux/topology.h:168
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182ae79)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/skbuff.c (ffffffff81a80824)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81ad3ced)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81ad8bf8)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In arch/x86/events/intel/pt.c (ffffffff8101bf84)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81040206)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104aec8)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff81186434)
Location: include/linux/topology.h:168
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff81187bf8)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81214e36)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81221d20)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81266c08)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff812a6949)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff812e252f)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8132613e)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/page_alloc.c (ffffffff8137052f)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff813897ae)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81398e85)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81f212d6)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff813a4861)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/memremap.c (ffffffff813e7641)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In block/blk-mq.c (ffffffff81689e5b)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957d46)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195bd6e)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195eb8e)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81963025)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c296)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/skbuff.c (ffffffff81bf4f73)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81c5207d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81c59c09)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In arch/x86/events/intel/pt.c (ffffffff810202d4)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049470)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105693d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811c1e34)
Location: include/linux/topology.h:168
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811c3873)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e4f6)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8126cca7)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b888e)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81304e09)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8134ac9f)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8139c8a1)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/slab_common.c (ffffffff813a12f5)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/page_alloc.c (ffffffff813ed4b2)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff8140839d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/mempolicy.c (ffffffff81418cf5)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff820cb1b9)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8142a4d7)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/memremap.c (ffffffff8146f2c1)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In block/blk-mq.c (ffffffff817483de)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abed06)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac358a)
Location: include/linux/topology.h:168
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
In drivers/iommu/intel/pasid.c (ffffffff81ac6629)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbfed)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad4837)
Location: include/linux/topology.h:168
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da4580)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81e0730d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e103ec)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In arch/x86/events/intel/pt.c (ffffffff81020024)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810496c9)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105790d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811d496c)
Location: include/linux/topology.h:168
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811d63c3)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff812756d6)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81283e37)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dbece)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81333799)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8137bccf)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff813cf981)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/slab_common.c (ffffffff813d4575)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/page_alloc.c (ffffffff814222cc)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff8143b2ad)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/mempolicy.c (ffffffff8144c1c5)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff8214f449)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8145f8d8)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/memremap.c (ffffffff814a3aa4)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/splice.c (ffffffff814fa7a7)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In block/blk-mq.c (ffffffff81784aeb)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c75)
Location: include/linux/topology.h:168
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07add)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b6a6)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f0c9)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b1321b)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18b73)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23007)
Location: include/linux/topology.h:168
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e131d4)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81e79b1d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e83c8c)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In arch/x86/events/intel/pt.c (ffffffff81026114)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050ab1)
Location: include/linux/topology.h:168
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ebad)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811e985c)
Location: include/linux/topology.h:168
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb3f3)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fd90)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8129edc7)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9fae)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81357e89)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff813a4f0f)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff813fa581)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144f193)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/slub.c (ffffffff81454f10)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/hugetlb.c (ffffffff8147509d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_fresh_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/topology.h:168
Inline: True
```
```
In mm/mempolicy.c (ffffffff81485545)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff82232319)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/memremap.c (ffffffff814d4945)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/splice.c (ffffffff8152f199)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In block/blk-mq.c (ffffffff817c6ffb)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b57553)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac4b)
Location: include/linux/topology.h:168
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb0d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f77c)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b639b9)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67e4a)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e4e2)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79977)
Location: include/linux/topology.h:168
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed0394)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81f39c3d)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81f4435c)
Location: include/linux/topology.h:168
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
  - net/core/page_pool.c:__page_pool_alloc_page_order
  - net/core/page_pool.c:page_pool_refill_alloc_cache
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
In kernel/dma/direct.c (ffff800010194edc)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffff80001021a098)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffff800010225b7c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffff800010259bd0)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffff8000102a20a4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffff8000102e1b88)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (ffff800010318fd4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffff80001032f4f8)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffff80001033a7cc)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffff800010da09d8)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffff80001034579c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffff800010352de8)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In block/blk-mq.c (ffff8000105f2540)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000106713d4)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca588)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb420)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/xdp.c (ffff800010c070c4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffff800010c0cf00)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
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
In init/do_mounts.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/arm/kernel/signal.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/arm/mm/fault-armv.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/zbud.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/topology.h:177
Inline: True
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
In arch/powerpc/kernel/iommu.c (c000000000052f08)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_alloc_coherent
  - arch/powerpc/kernel/iommu.c:iommu_init_table
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bf0c4)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d6318)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000daddc)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_alloc_tce_level
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012c2d0)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:thread_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
```
```
In kernel/dma/direct.c (c0000000001f50d8)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (c00000000029c1f0)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (c0000000002ab320)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (c0000000002fd450)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (c000000000353e20)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (c0000000003a1a00)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:152
Inline: True
```
```
In mm/page_alloc.c (c0000000003eba10)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (c0000000004079ac)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (c00000000041509c)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (c000000000eed7cc)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (c0000000004229a8)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (c00000000043996c)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (c00000000046e320)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (c0000000007897e4)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In net/core/xdp.c (c000000000cf1968)
Location: include/linux/topology.h:152
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (c000000000cf7bbc)
Location: include/linux/topology.h:152
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
In init/do_mounts.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/zbud.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/topology.h:177
Inline: True
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
In arch/x86/events/intel/pt.c (ffffffff81015703)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387dd)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81127ac9)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81198eee)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a143c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d1194)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120fcb3)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81243ef3)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff81279969)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff81289ca4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81293e55)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dc3c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8129c980)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812aab81)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff812ccfde)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814eb2b7)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816ad7a1)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b0cf0)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b59c4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8e94)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/xdp.c (ffffffff81902777)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81906ecc)
Location: include/linux/topology.h:177
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
In arch/x86/events/intel/pt.c (ffffffff810149d3)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810281ae)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8111a3d4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c72e)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119440c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3f64)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81202a43)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81236ec3)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126b859)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff8127bad4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81285a65)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a183)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8128e510)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8129c4de)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff812bde4e)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814db807)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff8168b101)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e7f0)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693604)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ad4)
Location: include/linux/topology.h:177
Inline: True
```
```
In drivers/hv/channel.c (ffffffff81850ede)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_alloc_ring
```
```
In net/core/xdp.c (ffffffff818bc5a7)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818c0cdc)
Location: include/linux/topology.h:177
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
In arch/x86/events/intel/pt.c (ffffffff810156c3)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103863d)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81125864)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81196cbe)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119f20c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cef64)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120da53)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81241c93)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff81277709)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff81287ab4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81291c65)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81ada04c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8129a790)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812a8991)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff812cadee)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814e7347)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816db981)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816df080)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3e94)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e7364)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/xdp.c (ffffffff819537a7)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81957efc)
Location: include/linux/topology.h:177
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
In arch/x86/events/intel/pt.c (ffffffff81015903)
Location: include/linux/topology.h:177
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103963d)
Location: include/linux/topology.h:177
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81131ea4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811a48ce)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811acf5b)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd1f4)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8121c903)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81251433)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:177
Inline: True
```
```
In mm/page_alloc.c (ffffffff812872f9)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb.c (ffffffff81298050)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812a1a75)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/mempolicy.c:mempolicy_slab_node
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6502)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812aa670)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812b8cb1)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/memremap.c (ffffffff812dbb2c)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff815002e7)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816f5f51)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f9690)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe55a)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701a64)
Location: include/linux/topology.h:177
Inline: True
```
```
In net/core/xdp.c (ffffffff819752c7)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81979fec)
Location: include/linux/topology.h:177
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
</ul>

## Differences
