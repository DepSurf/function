# Function: <code>__alloc_pages_nodemask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, struct zonelist *zonelist, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811967c0)
Location: mm/page_alloc.c:3172
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:profile_cpu_callback
  - kernel/profile.c:profile_cpu_callback
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/page_alloc.c:alloc_kmem_pages_node
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
  - mm/percpu.c:pcpu_populate_chunk
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/migrate.c:new_page_node
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:khugepaged
  - mm/memory-failure.c:new_page
  - block/blk-mq.c:blk_mq_init_rq_map
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff811967c0-ffffffff81197318: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, struct zonelist *zonelist, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811ab000)
Location: mm/page_alloc.c:3618
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
  - mm/percpu.c:pcpu_populate_chunk
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - block/blk-mq.c:blk_mq_init_rq_map
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
**Symbols:**

```
ffffffff811ab000-ffffffff811ab2fb: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, struct zonelist *zonelist, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bb680)
Location: mm/page_alloc.c:3768
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/percpu.c:pcpu_populate_chunk
  - mm/vmalloc.c:__vmalloc_node_range
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - block/blk-mq.c:blk_mq_init_rq_map
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
**Symbols:**

```
ffffffff811bb680-ffffffff811bb8dd: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c3990)
Location: mm/page_alloc.c:4100
Inline: False
Direct callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/percpu.c:pcpu_populate_chunk
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
**Symbols:**

```
ffffffff811c3990-ffffffff811c3c06: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d8730)
Location: mm/page_alloc.c:4221
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
  - arch/x86/mm/mem_encrypt.c:sev_alloc
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/percpu.c:pcpu_populate_chunk
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
  - mm/migrate.c:new_page_node
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
**Symbols:**

```
ffffffff811d8730-ffffffff811d89ac: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f98f0)
Location: mm/page_alloc.c:4353
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/percpu.c:pcpu_populate_chunk
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff811f98f0-ffffffff811f9b6c: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120bf30)
Location: mm/page_alloc.c:4516
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/percpu.c:pcpu_populate_chunk
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff8120bf30-ffffffff8120c20d: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272150)
Location: mm/page_alloc.c:4683
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81272150-ffffffff81272467: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81280fb0)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81280fb0-ffffffff812812c7: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b34a0)
Location: mm/page_alloc.c:4805
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff812b34a0-ffffffff812b379f: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bef50)
Location: mm/page_alloc.c:4958
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:alloc_migration_target
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff812bef50-ffffffff812bf25a: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010318c48)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffff800010318c48-ffff800010318f78: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c053363c)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - arch/arm/kernel/signal.c:get_signal_page
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
  - kernel/fork.c:copy_process
  - kernel/power/snapshot.c:alloc_image_page
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/kexec_core.c:kimage_alloc_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/mempool.c:mempool_alloc_pages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/shmem.c:shmem_alloc_page
  - mm/percpu.c:pcpu_populate_chunk
  - mm/slab_common.c:kmalloc_order
  - mm/gup.c:new_non_cma_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__pte_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:add_swap_count_continuation
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/slub.c:alloc_slab_page
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:alloc_migrate_target
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:zs_malloc
  - mm/balloon_compaction.c:balloon_page_alloc
  - mm/userfaultfd.c:mcopy_atomic
  - fs/pipe.c:pipe_write
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_alloc_buffer
  - security/selinux/ss/status.c:selinux_kernel_status_page
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_alloc_rqs
  - lib/scatterlist.c:sgl_alloc_order
  - lib/iov_iter.c:push_pipe
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_table_entry
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_alloc_tables
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/dma/mv_xor.c:mv_chan_xor_self_test
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
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
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/iommu/io-pgtable-arm.c:__arm_lpae_alloc_pages
  - drivers/iommu/tegra-smmu.c:tegra_smmu_map
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-kcopyd.c:alloc_pl
  - drivers/firmware/efi/capsule.c:efi_capsule_update
  - drivers/firmware/efi/memmap.c:efi_memmap_alloc
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
c053363c-c053397c: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003eb5c0)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - arch/powerpc/kernel/iommu.c:iommu_alloc_coherent
  - arch/powerpc/kernel/iommu.c:iommu_init_table
  - arch/powerpc/sysdev/xive/common.c:xive_queue_page_alloc
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_iommu_bypass_supported
  - arch/powerpc/platforms/powernv/pci-ioda-tce.c:pnv_alloc_tce_level
  - arch/powerpc/perf/imc-pmu.c:trace_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:thread_imc_mem_alloc
  - arch/powerpc/perf/imc-pmu.c:ppc_core_imc_cpu_online
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:khugepaged_alloc_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
c0000000003eb5c0-c0000000003eb984: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021ea0e)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - kernel/fork.c:copy_process
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/mempool.c:mempool_alloc_pages
  - mm/readahead.c:__do_page_cache_readahead
  - mm/percpu.c:pcpu_populate_chunk
  - mm/slab_common.c:kmalloc_order
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:__pte_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__get_free_pages
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swapfile.c:add_swap_count_continuation
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/ksm.c:ksm_might_need_to_copy
  - mm/slub.c:alloc_slab_page
  - mm/slub.c:alloc_slab_page
  - mm/swap_cgroup.c:swap_cgroup_swapon
  - mm/page_isolation.c:alloc_migrate_target
  - mm/zbud.c:zbud_alloc
  - mm/zsmalloc.c:zs_malloc
  - mm/balloon_compaction.c:balloon_page_alloc
  - mm/userfaultfd.c:mcopy_atomic
  - fs/pipe.c:pipe_write
  - fs/ecryptfs/crypto.c:ecryptfs_write_metadata
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dir.c:fuse_get_link
  - fs/fuse/file.c:fuse_do_ioctl
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/keys/big_key.c:big_key_alloc_buffer
  - security/selinux/ss/status.c:selinux_kernel_status_page
  - block/bio.c:bio_copy_kern
  - block/bio.c:bio_copy_user_iov
  - block/blk-mq.c:blk_mq_alloc_rqs
  - lib/scatterlist.c:sgl_alloc_order
  - lib/iov_iter.c:push_pipe
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/char/virtio_console.c:pipe_to_sg
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_read
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_random
  - drivers/char/tpm/tpm1-cmd.c:tpm1_getcap
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pcr_extend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_timeouts
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
  - drivers/char/tpm/tpm2-space.c:tpm2_load_context
  - drivers/char/tpm/tpm-sysfs.c:pubek_show
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/base/firmware_loader/main.c:fw_grow_paged_buf
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
  - drivers/scsi/sg.c:sg_build_indirect
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:super_1_load
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
  - drivers/md/dm-kcopyd.c:alloc_pl
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:alloc_skb_with_frags
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffe00021ea0e-ffffffe00021ec76: __alloc_pages_nodemask (STB_GLOBAL)
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
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81279600)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81279600-ffffffff81279917: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126b4f0)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - drivers/hv/channel.c:vmbus_alloc_ring
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff8126b4f0-ffffffff8126b807: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812773a0)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff812773a0-ffffffff812776b7: __alloc_pages_nodemask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__alloc_pages_nodemask(gfp_t gfp_mask, unsigned int order, int preferred_nid, nodemask_t *nodemask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81286f90)
Location: mm/page_alloc.c:4701
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:dsalloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/profile.c:profile_prepare_cpu
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - mm/percpu.c:pcpu_populate_chunk
  - mm/gup.c:new_non_cma_page
  - mm/gup.c:new_non_cma_page
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:alloc_pages_exact_nid
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:alloc_slab_page
  - mm/memory_hotplug.c:new_node_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memory-failure.c:new_page
  - mm/page_isolation.c:alloc_migrate_target
  - block/blk-mq.c:blk_mq_alloc_rqs
  - drivers/iommu/dmar.c:dmar_enable_qi
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
**Symbols:**

```
ffffffff81286f90-ffffffff812872a9: __alloc_pages_nodemask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int preferred_nid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zonelist *zonelist</code>
</li>
</ul>
</details>
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
