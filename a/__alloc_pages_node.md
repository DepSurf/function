# Function: <code>__alloc_pages_node</code>

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
In arch/x86/events/intel/pt.c (ffffffff810142b7)
Location: include/linux/gfp.h:430
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810345ea)
Location: include/linux/gfp.h:430
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034e69)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/profile.c (ffffffff81819057)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:profile_cpu_callback
  - kernel/profile.c:profile_cpu_callback
```
```
In kernel/trace/ring_buffer.c (ffffffff811468fe)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f6bb)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81185187)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff8118d62d)
Location: include/linux/gfp.h:430
Inline: True
```
```
In mm/page_alloc.c (ffffffff8119732e)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_kmem_pages_node
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/percpu.c (ffffffff811b0ae0)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811cf141)
Location: include/linux/gfp.h:430
Inline: True
```
```
In mm/hugetlb.c (ffffffff811daefa)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff811e02b1)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff8181f151)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff811e972f)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff811f0887)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f4d9c)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81201ee5)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In block/blk-mq.c (ffffffff813c3bf3)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff815350ce)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815357e9)
Location: include/linux/gfp.h:430
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4d1e)
Location: include/linux/gfp.h:430
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
In arch/x86/events/intel/pt.c (ffffffff81013d07)
Location: include/linux/gfp.h:441
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337b4)
Location: include/linux/gfp.h:441
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034046)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/fork.c (ffffffff81080412)
Location: include/linux/gfp.h:441
Inline: True
```
```
In kernel/profile.c (ffffffff810f14af)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f14e)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81157a46)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117cda2)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81196fe8)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811a021d)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab3d4)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/percpu.c (ffffffff811c9d07)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811ec2cd)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f906f)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81200b96)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff818995f9)
Location: include/linux/gfp.h:441
Inline: True
```
```
In mm/slub.c (ffffffff81206aaf)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8121301a)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
```
```
In mm/khugepaged.c (ffffffff812194e5)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memory-failure.c (ffffffff812262a5)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In block/blk-mq.c (ffffffff81407f6b)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff8158997e)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158d312)
Location: include/linux/gfp.h:441
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592835)
Location: include/linux/gfp.h:441
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
In arch/x86/events/intel/pt.c (ffffffff81013e87)
Location: include/linux/gfp.h:434
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810333e4)
Location: include/linux/gfp.h:434
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033c76)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/profile.c (ffffffff810f83f5)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811592ee)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81162c7c)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811889b6)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811a69f8)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811af65d)
Location: include/linux/gfp.h:434
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bb9ae)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
```
```
In mm/percpu.c (ffffffff811d9dfc)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811fd56d)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/hugetlb.c (ffffffff81209c5f)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812125b5)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff818cdcb1)
Location: include/linux/gfp.h:434
Inline: True
```
```
In mm/slub.c (ffffffff8121887f)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8122538a)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
```
```
In mm/khugepaged.c (ffffffff8122ba65)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memory-failure.c (ffffffff81238875)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In block/blk-mq.c (ffffffff81422c17)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/iommu/dmar.c (ffffffff815b703a)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82015bcc)
Location: include/linux/gfp.h:434
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c00f5)
Location: include/linux/gfp.h:434
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
In arch/x86/events/intel/pt.c (ffffffff810124da)
Location: include/linux/gfp.h:479
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810315b7)
Location: include/linux/gfp.h:479
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81031d9d)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/profile.c (ffffffff810fa429)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e8f8)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81166121)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b6ef)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811ae1e8)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811b652b)
Location: include/linux/gfp.h:479
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c3c89)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811e34c0)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff8120826c)
Location: include/linux/gfp.h:479
Inline: True
```
```
In mm/hugetlb.c (ffffffff81215ad0)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8121d8ef)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff8190515f)
Location: include/linux/gfp.h:479
Inline: True
```
```
In mm/slub.c (ffffffff81224474)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81230a77)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
```
```
In mm/khugepaged.c (ffffffff81238be4)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff814327ba)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff815cce32)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f788e)
Location: include/linux/gfp.h:479
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5c1b)
Location: include/linux/gfp.h:479
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
In arch/x86/events/intel/ds.c (ffffffff8100ded7)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810125aa)
Location: include/linux/gfp.h:464
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337fb)
Location: include/linux/gfp.h:464
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340d4)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff810803a6)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In kernel/profile.c (ffffffff81104dad)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b8f8)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811730b4)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8119919a)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811c1e58)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811ca88f)
Location: include/linux/gfp.h:464
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d8a29)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff811f8d8b)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff81221333)
Location: include/linux/gfp.h:464
Inline: True
```
```
In mm/hugetlb.c (ffffffff81230700)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81238adf)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff8198f151)
Location: include/linux/gfp.h:464
Inline: True
```
```
In mm/slub.c (ffffffff8123fad4)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff8124e7f3)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
  - mm/migrate.c:new_page_node
```
```
In mm/khugepaged.c (ffffffff81258a92)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
```
```
In block/blk-mq.c (ffffffff8145e38a)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff81633c32)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700f6f)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c9cb)
Location: include/linux/gfp.h:464
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
In arch/x86/events/intel/ds.c (ffffffff8100e697)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81012f7a)
Location: include/linux/gfp.h:464
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b74)
Location: include/linux/gfp.h:464
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8110cddc)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/profile.c (ffffffff8110fb4d)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8117ad65)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81182094)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae879)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811e2218)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811eb8df)
Location: include/linux/gfp.h:464
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f9bcd)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff8121a788)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff812431f3)
Location: include/linux/gfp.h:464
Inline: True
```
```
In mm/mempolicy.c (ffffffff8125bfeb)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff819eb9cd)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff81263144)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff812725fc)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff8127a8a5)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In block/blk-mq.c (ffffffff81491cc1)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff8166edca)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272ac83)
Location: include/linux/gfp.h:464
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677e19)
Location: include/linux/gfp.h:464
Inline: True
```
```
In net/core/page_pool.c (ffffffff818bd6ff)
Location: include/linux/gfp.h:464
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
In arch/x86/events/intel/ds.c (ffffffff8100eb67)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101394a)
Location: include/linux/gfp.h:481
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d54)
Location: include/linux/gfp.h:481
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81118ade)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff8111b23d)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811877d5)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8118fa54)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcf0d)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811f2688)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811fc45f)
Location: include/linux/gfp.h:481
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120c25d)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/percpu.c (ffffffff8122d738)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff812578fe)
Location: include/linux/gfp.h:481
Inline: True
```
```
In mm/mempolicy.c (ffffffff812708ab)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81a26c50)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812779d4)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/migrate.c (ffffffff81286bf8)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff8128eea5)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In block/blk-mq.c (ffffffff814ab72e)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/blk-zoned.c (ffffffff814cbd39)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/iommu/dmar.c (ffffffff8168d325)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81690277)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff8169408e)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ef9)
Location: include/linux/gfp.h:481
Inline: True
```
```
In net/core/xdp.c (ffffffff818e1bcf)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818e4add)
Location: include/linux/gfp.h:481
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
In arch/x86/events/intel/ds.c (ffffffff81010a27)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81014dba)
Location: include/linux/gfp.h:481
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037eb4)
Location: include/linux/gfp.h:481
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81122f5b)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff81125907)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff81194d05)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119d462)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc5b0)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120a358)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff81213b33)
Location: include/linux/gfp.h:481
Inline: True
```
```
In mm/percpu.c (ffffffff8123d465)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (ffffffff8124a6a2)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (ffffffff8126a650)
Location: include/linux/gfp.h:481
Inline: True
```
```
In mm/page_alloc.c (ffffffff812724d0)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff81288a16)
Location: include/linux/gfp.h:481
Inline: True
```
```
In mm/sparse-vmemmap.c (ffffffff81a974f2)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff81294122)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812a1198)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812aa941)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff814d991e)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816c4d2f)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c8417)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc99e)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf86b)
Location: include/linux/gfp.h:481
Inline: True
```
```
In net/core/xdp.c (ffffffff81930657)
Location: include/linux/gfp.h:481
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff819342d3)
Location: include/linux/gfp.h:481
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
In arch/x86/events/intel/ds.c (ffffffff81011107)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101570a)
Location: include/linux/gfp.h:510
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038684)
Location: include/linux/gfp.h:510
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112f39b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff811318d7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811a07c5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a8e23)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8b7b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81217638)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff81221303)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (ffffffff8124b8b5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (ffffffff81258b72)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (ffffffff81279561)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (ffffffff81281330)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff8129b618)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81acedd4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812a43a7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812b25a8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812bbedf)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff814f2cde)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816e7c5f)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eb3c7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f01db)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f36ab)
Location: include/linux/gfp.h:510
Inline: True
```
```
In net/core/xdp.c (ffffffff819627b7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81966f03)
Location: include/linux/gfp.h:510
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
In arch/x86/events/intel/ds.c (ffffffff81010dce)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81016c0a)
Location: include/linux/gfp.h:517
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b0cf)
Location: include/linux/gfp.h:517
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8113dd80)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff81140c47)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6da5)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c1103)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4f81)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e345)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81242ee8)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff8124e33f)
Location: include/linux/gfp.h:517
Inline: True
```
```
In mm/percpu.c (ffffffff81279856)
Location: include/linux/gfp.h:517
Inline: True
```
```
In mm/vmalloc.c (ffffffff812ac3b3)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812b3807)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff812cf196)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81bc7796)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812d7631)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812e7b48)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812f13d6)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff815532a3)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dma-iommu.c (ffffffff8179219a)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e79f)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1d86a)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a78be)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab94b)
Location: include/linux/gfp.h:517
Inline: True
```
```
In net/core/xdp.c (ffffffff81a35707)
Location: include/linux/gfp.h:517
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3a623)
Location: include/linux/gfp.h:517
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
In arch/x86/events/intel/ds.c (ffffffff81010427)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810170aa)
Location: include/linux/gfp.h:519
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b8df)
Location: include/linux/gfp.h:519
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811385c4)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff81139bf5)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (ffffffff8113cf77)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811b495c)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bed33)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3911)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff812210d1)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8124d588)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff81258750)
Location: include/linux/gfp.h:519
Inline: True
```
```
In mm/percpu.c (ffffffff812840c6)
Location: include/linux/gfp.h:519
Inline: True
```
```
In mm/vmalloc.c (ffffffff812b7945)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff812bf2e1)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff812dac16)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81c404ca)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812e4b68)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f2f35)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812fd954)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff8156f933)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac4ef)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b586)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b375e)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7d2b)
Location: include/linux/gfp.h:519
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be976)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81a37aa7)
Location: include/linux/gfp.h:519
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3cb44)
Location: include/linux/gfp.h:519
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
In arch/x86/events/intel/ds.c (ffffffff810113ac)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101819a)
Location: include/linux/gfp.h:544
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810340f9)
Location: include/linux/gfp.h:544
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d27d)
Location: include/linux/gfp.h:544
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811396e2)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ad15)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (ffffffff8113e1b7)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3d1c)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bf603)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e8b)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff81224b85)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81251ec8)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff8125cdda)
Location: include/linux/gfp.h:544
Inline: True
```
```
In mm/percpu.c (ffffffff81288d06)
Location: include/linux/gfp.h:544
Inline: True
```
```
In mm/vmalloc.c (ffffffff812bd333)
Location: include/linux/gfp.h:544
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c4388)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff812e2476)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81c32572)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812ec7f8)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff812f92b8)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff813046a6)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff815777e3)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178f3bf)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff83215f1b)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8179688e)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179ae9a)
Location: include/linux/gfp.h:544
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1816)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81a1ec37)
Location: include/linux/gfp.h:544
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a24742)
Location: include/linux/gfp.h:544
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
In arch/x86/events/intel/ds.c (ffffffff810121ac)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff81019a7b)
Location: include/linux/gfp.h:565
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039399)
Location: include/linux/gfp.h:565
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042dba)
Location: include/linux/gfp.h:565
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8115c6b0)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8115dc45)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (ffffffff8116152d)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811ddcf0)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811e9ee8)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812270c8)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff8125cac5)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8128d755)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff81298d57)
Location: include/linux/gfp.h:565
Inline: True
```
```
In mm/percpu.c (ffffffff812c8796)
Location: include/linux/gfp.h:565
Inline: True
```
```
In mm/vmalloc.c (ffffffff812ffa7b)
Location: include/linux/gfp.h:565
Inline: True
```
```
In mm/page_alloc.c (ffffffff81308244)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff8132963d)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81d510b5)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
```
```
In mm/slub.c (ffffffff8133512a)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff8133db19)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page_thp
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff8134e3dc)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff815dc503)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816cdf)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a393)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e81e)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818239ca)
Location: include/linux/gfp.h:565
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182ae86)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81ad3cfd)
Location: include/linux/gfp.h:565
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81ad8dba)
Location: include/linux/gfp.h:565
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
In arch/x86/events/intel/ds.c (ffffffff81013b39)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101bf8b)
Location: include/linux/gfp.h:582
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff8104020d)
Location: include/linux/gfp.h:582
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104aecf)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff8118643b)
Location: include/linux/gfp.h:582
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff81187bff)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (ffffffff81194390)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff81214e3d)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81221d27)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81266c0f)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/ringbuf.c (ffffffff812a6950)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff812e24f5)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff81326145)
Location: include/linux/gfp.h:582
Inline: True
```
```
In mm/vmalloc.c (ffffffff81360721)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_area_alloc_pages
```
```
In mm/page_alloc.c (ffffffff81370546)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/sparse-vmemmap.c (ffffffff81f212de)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/sparse-vmemmap.c:vmemmap_remap_alloc
```
```
In mm/slub.c (ffffffff813a4868)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/khugepaged.c (ffffffff813c4af2)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff81689e62)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957ce5)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195bd75)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195eb95)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81962e37)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c2a5)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81c5208d)
Location: include/linux/gfp.h:582
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81c59df9)
Location: include/linux/gfp.h:582
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
In arch/x86/events/intel/ds.c (ffffffff81018209)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810202db)
Location: include/linux/gfp.h:232
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049477)
Location: include/linux/gfp.h:232
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81056944)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811c1e3b)
Location: include/linux/gfp.h:232
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811c387a)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (ffffffff811d1af0)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e4fd)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8126ccae)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b8895)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81304e10)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8134ac65)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff8139c8a8)
Location: include/linux/gfp.h:232
Inline: True
```
```
In mm/slab_common.c (ffffffff813a12fd)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (ffffffff813e2898)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff813ed4c3)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413c61)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/sparse-vmemmap.c (ffffffff820cb174)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff81427859)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In block/blk-mq.c (ffffffff817483e5)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abeca5)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac3591)
Location: include/linux/gfp.h:232
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
In drivers/iommu/intel/pasid.c (ffffffff81ac6630)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbea5)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad483f)
Location: include/linux/gfp.h:232
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da4593)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (ffffffff81e0731d)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e10191)
Location: include/linux/gfp.h:232
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
In arch/x86/events/intel/ds.c (ffffffff81017ae9)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8102002b)
Location: include/linux/gfp.h:232
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810496d0)
Location: include/linux/gfp.h:232
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81057914)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811d4973)
Location: include/linux/gfp.h:232
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811d63ca)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (ffffffff811e5de0)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff812756dd)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81283e3e)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dbed5)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff813337a0)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8137bc95)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff813cf988)
Location: include/linux/gfp.h:232
Inline: True
```
```
In mm/slab_common.c (ffffffff813d457d)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/vmalloc.c (ffffffff81417459)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff814222dd)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447202)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_alloc
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/sparse-vmemmap.c (ffffffff8214f404)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8145cdc9)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In block/blk-mq.c (ffffffff81784af2)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c7c)
Location: include/linux/gfp.h:232
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07ae4)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b645)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f0d0)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b13222)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18a25)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b2300f)
Location: include/linux/gfp.h:232
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e131e4)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (ffffffff81e79b2d)
Location: include/linux/gfp.h:232
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e83a31)
Location: include/linux/gfp.h:232
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
In arch/x86/events/intel/ds.c (ffffffff8101d629)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8102611b)
Location: include/linux/gfp.h:233
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050ab8)
Location: include/linux/gfp.h:233
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ebb4)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In kernel/dma/direct.c (ffffffff811e9863)
Location: include/linux/gfp.h:233
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb3fa)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (ffffffff811fbb30)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fd97)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8129edce)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9fb5)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/ringbuf.c (ffffffff81357e90)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff813a4ed5)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/percpu.c (ffffffff813fa588)
Location: include/linux/gfp.h:233
Inline: True
```
```
In mm/vmalloc.c (ffffffff81443f69)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144f1a4)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/slub.c (ffffffff81454f1b)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/hugetlb_vmemmap.c (ffffffff814807db)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_optimize_folio
  - mm/hugetlb_vmemmap.c:__hugetlb_vmemmap_restore_folio
```
```
In mm/mempolicy.c (ffffffff814859ff)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_mpol
```
```
In mm/sparse-vmemmap.c (ffffffff822322d4)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In block/blk-mq.c (ffffffff817c7002)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b57563)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac52)
Location: include/linux/gfp.h:233
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb14)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f6e8)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b639c0)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67e51)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e394)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7997f)
Location: include/linux/gfp.h:233
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed03a4)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (ffffffff81f39c4d)
Location: include/linux/gfp.h:233
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81f43e51)
Location: include/linux/gfp.h:233
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194e00)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffff800010198a28)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffff800010219fac)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffff800010225b3c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffff800010259bd8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffff8000102a206c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffff8000102adfc0)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (ffff8000102e1b54)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (ffff8000102f0c98)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (ffff80001030ffc0)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (ffff800010318fe8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffff80001033a550)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffff800010da09e8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffff8000103457ac)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffff800010352df8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffff80001035c75c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In block/blk-mq.c (ffff8000105f2528)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000106713e4)
Location: include/linux/gfp.h:510
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca598)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb3cc)
Location: include/linux/gfp.h:510
Inline: True
```
```
In net/core/xdp.c (ffff800010c070d0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffff800010c0cf10)
Location: include/linux/gfp.h:510
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
In init/do_mounts.c (c1501710)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/arm/kernel/signal.c (c030ec98)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:get_signal_page
```
```
In arch/arm/mm/dma-mapping.c (c031e24c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
```
```
In arch/arm/mm/fault-armv.c (c1507da8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
```
```
In kernel/fork.c (c0351d50)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/power/snapshot.c (c03bfbb4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/power/snapshot.c:alloc_image_page
```
```
In kernel/dma/direct.c (c03e1bfc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (c03e3bbc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/kexec_core.c (c040f70c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_pages
```
```
In kernel/relay.c (c044ab20)
Location: include/linux/gfp.h:510
Inline: True
```
```
In kernel/trace/ring_buffer.c (c0457490)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (c0465234)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (c048bb58)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (c04d2694)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (c04d66ac)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/filemap.c (c04de244)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
```
```
In mm/mempool.c (c04e2294)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/readahead.c (c04eaff8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/shmem.c (c04fa8f4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
```
```
In mm/percpu.c (c0505d44)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/slab_common.c (c0509cbc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/gup.c (c05140a8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
```
```
In mm/memory.c (c051b708)
Location: include/linux/gfp.h:510
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
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (c0533abc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (c053a308)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (c053fd9c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/ksm.c (c0547d7c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (c05495fc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/swap_cgroup.c (c055dcfc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (c055f970)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (c0560b8c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (c0563168)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In mm/userfaultfd.c (c0563cf4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (c0576ebc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (c06b5a6c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (c06bf990)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (c06c2a0c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (c06c7c74)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (c06cfbc0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (c06f0050)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (c071ed7c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (c078a9e0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In block/blk-mq.c (c079e608)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In lib/scatterlist.c (c07d3684)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (c07d4360)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081babc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (c08b7c8c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/dma/mv_xor.c (c0925378)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
```
```
In drivers/virtio/virtio_balloon.c (c09478b0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (c09af088)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (c09b3ef8)
Location: include/linux/gfp.h:510
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
Location: include/linux/gfp.h:510
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
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (c09b7d38)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/iommu/io-pgtable-arm.c (c09bff08)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
```
```
In drivers/iommu/tegra-smmu.c (c09c8880)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
```
```
In drivers/lightnvm/core.c (c09cddb8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (c09f6044)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (c0a08f10)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/sg.c (c0a63350)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/md/md.c (c0bccd4c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (c0bd9f34)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (c0be9408)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/firmware/efi/capsule.c (c0c3d6fc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/firmware/efi/capsule.c:efi_capsule_update
```
```
In drivers/firmware/efi/memmap.c (c15a8b14)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
```
```
In net/core/sock.c (c0cc8fa8)
Location: include/linux/gfp.h:510
Inline: True
```
```
In net/core/skbuff.c (c0cd2a9c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (c0d19fa4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c0d202ac)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (c0d24c08)
Location: include/linux/gfp.h:510
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
In arch/powerpc/kernel/iommu.c (c000000000052f18)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_alloc_coherent
  - arch/powerpc/kernel/iommu.c:iommu_init_table
```
```
In arch/powerpc/sysdev/xive/common.c (c0000000000bf0d4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc
```
```
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d6328)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
```
```
In arch/powerpc/platforms/powernv/pci-ioda-tce.c (c0000000000dadec)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_alloc_tce_level
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012c240)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:thread_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
```
```
In kernel/dma/direct.c (c0000000001f50e8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (c0000000001f9060)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (c00000000029c09c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (c0000000002ab2dc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (c0000000002fd4c4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (c000000000353dd8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (c0000000003630a4)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (c0000000003a19c8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (c0000000003b57fc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (c0000000003e12f4)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (c0000000003eba28)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (c000000000414d10)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (c000000000eed7dc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (c0000000004229b8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (c00000000043997c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (c000000000445cc4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In block/blk-mq.c (c0000000007897a0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In net/core/xdp.c (c000000000cf1984)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (c000000000cf7bcc)
Location: include/linux/gfp.h:510
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
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In kernel/fork.c (ffffffe0000bfd7c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/dma/direct.c (ffffffe000126cbe)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffe0001299b0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/relay.c (ffffffe00016d3de)
Location: include/linux/gfp.h:510
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000177d1c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace.c (ffffffe0001824b2)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffe0001d167c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffe0001d6f7c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
```
```
In mm/mempool.c (ffffffe0001d9f4e)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempool.c:mempool_alloc_pages
```
```
In mm/readahead.c (ffffffe0001e16e4)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/readahead.c:__do_page_cache_readahead
```
```
In mm/shmem.c (ffffffe0001ed7d8)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (ffffffe0001f88e0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/slab_common.c (ffffffe0001fb954)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_order
```
```
In mm/gup.c (ffffffe00020441c)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/memory.c (ffffffe0002092c0)
Location: include/linux/gfp.h:510
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
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021ee2a)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffe000222d2a)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffe0002286fa)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_count_continuation
```
```
In mm/sparse-vmemmap.c (ffffffe000048d90)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffe00023629c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffe00023805e)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
```
```
In mm/swap_cgroup.c (ffffffe000249c64)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/swap_cgroup.c:swap_cgroup_swapon
```
```
In mm/zbud.c (ffffffe00024c03c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/zbud.c:zbud_alloc
```
```
In mm/zsmalloc.c (ffffffe00024e896)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
```
In mm/balloon_compaction.c (ffffffe00024f7da)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_alloc
```
```
In mm/userfaultfd.c (ffffffe00024ff6c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/pipe.c (ffffffe00025fc9e)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ecryptfs/crypto.c (ffffffe000366b54)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
```
```
In fs/fuse/dev.c (ffffffe00036f122)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_fill
```
```
In fs/fuse/dir.c (ffffffe000372b14)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In fs/fuse/file.c (ffffffe000377058)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
```
In fs/fuse/readdir.c (ffffffe00037e516)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
```
In security/keys/big_key.c (ffffffe00039814c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - security/keys/big_key.c:big_key_alloc_buffer
```
```
In security/selinux/ss/status.c (ffffffe0003bffd8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - security/selinux/ss/status.c:selinux_kernel_status_page
```
```
In block/bio.c (ffffffe00042064c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
```
```
In block/blk-mq.c (ffffffe000430da6)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In lib/scatterlist.c (ffffffe00045cc26)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - lib/scatterlist.c:sgl_alloc_order
```
```
In lib/iov_iter.c (ffffffe00045d598)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - lib/iov_iter.c:push_pipe
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e8b7a)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
```
In drivers/virtio/virtio_balloon.c (ffffffe0005203a6)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
```
In drivers/char/virtio_console.c (ffffffe0005657fc)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:pipe_to_sg
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b514)
Location: include/linux/gfp.h:510
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
Location: include/linux/gfp.h:510
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
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
```
```
In drivers/char/tpm/tpm-sysfs.c (ffffffe000570f3e)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
```
```
In drivers/lightnvm/core.c (ffffffe000574f12)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
```
```
In drivers/base/firmware_loader/main.c (ffffffe000591c0a)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
```
```
In drivers/block/loop.c (ffffffe0005a2446)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/scsi/sg.c (ffffffe0005f4cc2)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_build_indirect
```
```
In drivers/md/md.c (ffffffe0006de17e)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
```
```
In drivers/md/md-bitmap.c (ffffffe0006eb1e0)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f8d1a)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In net/core/sock.c (ffffffe00073de0c)
Location: include/linux/gfp.h:510
Inline: True
```
```
In net/core/skbuff.c (ffffffe0007459ae)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
```
```
In net/core/filter.c (ffffffe00077d284)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffffffe0007854a6)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffe0007899aa)
Location: include/linux/gfp.h:510
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
In arch/x86/events/intel/ds.c (ffffffff81011107)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101570a)
Location: include/linux/gfp.h:510
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387e4)
Location: include/linux/gfp.h:510
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81127a9c)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff8112a087)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff81198de5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a1443)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d119b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120fc88)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff81219953)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (ffffffff81243f05)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (ffffffff812511c2)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (ffffffff81271bb1)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (ffffffff81279980)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff81293bf8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dc44)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8129c987)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812aab88)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812b44bf)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff814eb2be)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816ad73f)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b0cf7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b59cb)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8e9b)
Location: include/linux/gfp.h:510
Inline: True
```
```
In net/core/xdp.c (ffffffff81902787)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81906ed3)
Location: include/linux/gfp.h:510
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
In arch/x86/events/intel/ds.c (ffffffff8100fea7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810149da)
Location: include/linux/gfp.h:510
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810281c6)
Location: include/linux/gfp.h:510
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8111a3db)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff8111c917)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c625)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81194413)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3f6b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81202a18)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff8120cb63)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (ffffffff81236ed5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (ffffffff812440b2)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (ffffffff81263b21)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126b870)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff81285808)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a18b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8128e517)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff8129c4e5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812a553f)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff814db80e)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff8168b09f)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e7f7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff8169360b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696adb)
Location: include/linux/gfp.h:510
Inline: True
```
```
In drivers/hv/channel.c (ffffffff81850ee5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_alloc_ring
```
```
In net/core/xdp.c (ffffffff818bc5b7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818c0ce3)
Location: include/linux/gfp.h:510
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
In arch/x86/events/intel/ds.c (ffffffff810110c7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff810156ca)
Location: include/linux/gfp.h:510
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81038644)
Location: include/linux/gfp.h:510
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112586b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff81127da7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff81196bb5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119f213)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cef6b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8120da28)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff812176f3)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (ffffffff81241ca5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (ffffffff8124ef62)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (ffffffff8126f951)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (ffffffff81277720)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff81291a08)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81ada054)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8129a797)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812a8998)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812b22cf)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff814e734e)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816db91f)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816df087)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3e9b)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e736b)
Location: include/linux/gfp.h:510
Inline: True
```
```
In net/core/xdp.c (ffffffff819537b7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81957f03)
Location: include/linux/gfp.h:510
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
In arch/x86/events/intel/ds.c (ffffffff810112d7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
```
```
In arch/x86/events/intel/pt.c (ffffffff8101590a)
Location: include/linux/gfp.h:510
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81039644)
Location: include/linux/gfp.h:510
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81131eab)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/profile.c (ffffffff81134427)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811a47c5)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811acf62)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd1fb)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8121c8d8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff812267a3)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/percpu.c (ffffffff81251445)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/gup.c (ffffffff8125e8d2)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
```
```
In mm/vmalloc.c (ffffffff8127f353)
Location: include/linux/gfp.h:510
Inline: True
```
```
In mm/page_alloc.c (ffffffff81287310)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/mempolicy.c (ffffffff812a1818)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/sparse-vmemmap.c (ffffffff81ae650a)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff812aa677)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
```
```
In mm/migrate.c (ffffffff812b8cb8)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
```
```
In mm/khugepaged.c (ffffffff812c26cf)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
```
```
In block/blk-mq.c (ffffffff815002ee)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/dmar.c (ffffffff816f5eef)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f9697)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe561)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701a6b)
Location: include/linux/gfp.h:510
Inline: True
```
```
In net/core/xdp.c (ffffffff819752d7)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81979ff3)
Location: include/linux/gfp.h:510
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
</ul>

## Differences
