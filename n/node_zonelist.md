# Function: <code>node_zonelist</code>

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
Location: include/linux/gfp.h:402
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810345ea)
Location: include/linux/gfp.h:402
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034e69)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/profile.c (ffffffff81819057)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:create_proc_profile
  - kernel/profile.c:profile_cpu_callback
  - kernel/profile.c:profile_cpu_callback
```
```
In kernel/trace/ring_buffer.c (ffffffff811468fe)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f6bb)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81185187)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff8118d62d)
Location: include/linux/gfp.h:402
Inline: True
```
```
In mm/page_alloc.c (ffffffff81191abf)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:alloc_kmem_pages_node
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/vmscan.c (ffffffff811a53d8)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/percpu.c (ffffffff811b0ae0)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811cf141)
Location: include/linux/gfp.h:402
Inline: True
```
```
In mm/hugetlb.c (ffffffff811daefd)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff811dfcdb)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/mempolicy.c:policy_zonelist
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/sparse-vmemmap.c (ffffffff8181f151)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff811e9732)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff811f0887)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/migrate.c:new_page_node
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f4da0)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
```
In mm/memory-failure.c (ffffffff81201ee5)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In fs/buffer.c (ffffffff81242bf9)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
  - fs/buffer.c:free_more_memory
```
```
In block/blk-mq.c (ffffffff813c3bf3)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/tty/sysrq.c (ffffffff814eda0d)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/dmar.c (ffffffff815350ce)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff815357e9)
Location: include/linux/gfp.h:402
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4d1e)
Location: include/linux/gfp.h:402
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
Location: include/linux/gfp.h:413
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337b4)
Location: include/linux/gfp.h:413
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034046)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/fork.c (ffffffff81080412)
Location: include/linux/gfp.h:413
Inline: True
```
```
In kernel/profile.c (ffffffff810f14af)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f14e)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81157a46)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117cda2)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff81196fe8)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811a021d)
Location: include/linux/gfp.h:413
Inline: True
```
```
In mm/page_alloc.c (ffffffff811a65bc)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811bbea8)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/percpu.c (ffffffff811c9d07)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811ec2cd)
Location: include/linux/gfp.h:413
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f906f)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81201764)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:policy_zonelist
```
```
In mm/sparse-vmemmap.c (ffffffff818995f9)
Location: include/linux/gfp.h:413
Inline: True
```
```
In mm/slub.c (ffffffff81206aaf)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (ffffffff8120ed72)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8121301a)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
```
```
In mm/khugepaged.c (ffffffff812194e5)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memory-failure.c (ffffffff812262a5)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In fs/buffer.c (ffffffff8126af2a)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
  - fs/buffer.c:free_more_memory
```
```
In block/blk-mq.c (ffffffff81407f6b)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/tty/sysrq.c (ffffffff8153e69f)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/dmar.c (ffffffff8158997e)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158d312)
Location: include/linux/gfp.h:413
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592835)
Location: include/linux/gfp.h:413
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
Location: include/linux/gfp.h:406
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810333e4)
Location: include/linux/gfp.h:406
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033c76)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/profile.c (ffffffff810f83f5)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - kernel/profile.c:profile_prepare_cpu
```
```
In kernel/trace/ring_buffer.c (ffffffff811592ee)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81162c7c)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811889b6)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811a69f8)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/filemap.c (ffffffff811af65d)
Location: include/linux/gfp.h:406
Inline: True
```
```
In mm/page_alloc.c (ffffffff811b692c)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811cc578)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/percpu.c (ffffffff811d9dfc)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/vmalloc.c (ffffffff811fd56d)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/hugetlb.c (ffffffff81209c5f)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81213254)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_page_interleave
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:policy_zonelist
```
```
In mm/sparse-vmemmap.c (ffffffff818cdcb1)
Location: include/linux/gfp.h:406
Inline: True
```
```
In mm/slub.c (ffffffff8121887f)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:new_slab
  - mm/slub.c:new_slab
```
```
In mm/memory_hotplug.c (ffffffff81220e68)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/migrate.c (ffffffff8122538a)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:new_page_node
```
```
In mm/khugepaged.c (ffffffff8122ba65)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_alloc_page
```
```
In mm/memory-failure.c (ffffffff81238875)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - mm/memory-failure.c:new_page
```
```
In fs/buffer.c (ffffffff8127e063)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
  - fs/buffer.c:free_more_memory
```
```
In block/blk-mq.c (ffffffff81422c17)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/tty/sysrq.c (ffffffff8156acfb)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/dmar.c (ffffffff815b703a)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82015bcc)
Location: include/linux/gfp.h:406
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c00f5)
Location: include/linux/gfp.h:406
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
In mm/page_alloc.c (ffffffff811be7ec)
Location: include/linux/gfp.h:452
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811d51b2)
Location: include/linux/gfp.h:452
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/hugetlb.c (ffffffff81214416)
Location: include/linux/gfp.h:452
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8121e572)
Location: include/linux/gfp.h:452
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff812279be)
Location: include/linux/gfp.h:452
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In fs/buffer.c (ffffffff8128bc06)
Location: include/linux/gfp.h:452
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
  - fs/buffer.c:free_more_memory
```
```
In drivers/tty/sysrq.c (ffffffff8157f31d)
Location: include/linux/gfp.h:452
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/page_alloc.c (ffffffff811d355c)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/vmscan.c (ffffffff811ea6e2)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/hugetlb.c (ffffffff81230987)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8123979f)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff81243b11)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff815e3e8d)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/page_alloc.c (ffffffff811f47fd)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff8120beba)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/hugetlb.c (ffffffff8125252c)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8125cd4d)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff81266381)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff8161d129)
Location: include/linux/gfp.h:437
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/page_alloc.c (ffffffff81206c36)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff8121eb5d)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/hugetlb.c (ffffffff8126678c)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8127162d)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff8127b0bc)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff8163a389)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff8122e255)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/page_alloc.c (ffffffff8126cc6d)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81281a70)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8128cc48)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff81296aff)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff8166e6b9)
Location: include/linux/gfp.h:454
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff8123c3e5)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/page_alloc.c (ffffffff8127ba7d)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81291483)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8129c878)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff812a68c2)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff81690cf9)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff8126ab83)
Location: include/linux/gfp.h:484
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812b4145)
Location: include/linux/gfp.h:484
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff812c35b5)
Location: include/linux/gfp.h:484
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812d04c4)
Location: include/linux/gfp.h:484
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff812daff5)
Location: include/linux/gfp.h:484
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (ffffffff817433c9)
Location: include/linux/gfp.h:484
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff812755c3)
Location: include/linux/gfp.h:486
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812bfbc5)
Location: include/linux/gfp.h:486
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff812cf535)
Location: include/linux/gfp.h:486
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812dbfe4)
Location: include/linux/gfp.h:486
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff812e78e5)
Location: include/linux/gfp.h:486
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (ffffffff8175f249)
Location: include/linux/gfp.h:486
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff8127a8e3)
Location: include/linux/gfp.h:500
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff812c5325)
Location: include/linux/gfp.h:500
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff812d6715)
Location: include/linux/gfp.h:500
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812e385a)
Location: include/linux/gfp.h:500
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff812ef055)
Location: include/linux/gfp.h:500
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (ffffffff817430b9)
Location: include/linux/gfp.h:500
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff812b8929)
Location: include/linux/gfp.h:512
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81309885)
Location: include/linux/gfp.h:512
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff8131c4a5)
Location: include/linux/gfp.h:512
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8132aa10)
Location: include/linux/gfp.h:512
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff81337365)
Location: include/linux/gfp.h:512
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (ffffffff817c3ae9)
Location: include/linux/gfp.h:512
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff81314399)
Location: include/linux/gfp.h:529
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff813720e5)
Location: include/linux/gfp.h:529
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff81387625)
Location: include/linux/gfp.h:529
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8139a411)
Location: include/linux/gfp.h:529
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff813a8c65)
Location: include/linux/gfp.h:529
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (ffffffff81900839)
Location: include/linux/gfp.h:529
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff81388474)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff813ef915)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff81405a55)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff8141a431)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff81429d35)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (ffffffff81a5a479)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff813ba74c)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff81423485)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/hugetlb.c (ffffffff81438f95)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff8144d9e2)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff8145f115)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In drivers/tty/sysrq.c (ffffffff81aa4aa9)
Location: include/linux/gfp.h:165
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff813e386c)
Location: include/linux/gfp.h:166
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/page_alloc.c (ffffffff814503b5)
Location: include/linux/gfp.h:166
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_pages
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages
  - mm/page_alloc.c:__alloc_pages_bulk
```
```
In mm/slub.c (ffffffff8145a283)
Location: include/linux/gfp.h:166
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472ac5)
Location: include/linux/gfp.h:166
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/mempolicy.c (ffffffff81487631)
Location: include/linux/gfp.h:166
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In drivers/tty/sysrq.c (ffffffff81af74a9)
Location: include/linux/gfp.h:166
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/page_alloc.c (ffff800010313c24)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffff80001032e5ec)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffff80001033b808)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffff800010347bcc)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffff800010863b44)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (c04f7744)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/page_alloc.c (c05336e8)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In drivers/tty/sysrq.c (c09697bc)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/page_alloc.c (c0000000003ec870)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:local_memory_node
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (c000000000407610)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (c0000000004165d8)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (c000000000425ed4)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (c000000000902d44)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/page_alloc.c (0)
Location: include/linux/gfp.h:477
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/gfp.h:477
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/linux/gfp.h:477
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
In mm/vmscan.c (ffffffff81234a35)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/page_alloc.c (ffffffff812740cd)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81289a63)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81294e58)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff8129eea2)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff81656779)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff81227aa5)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/page_alloc.c (ffffffff8126603d)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff8127b893)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81286a68)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff812909e2)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff81636b09)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff812327d5)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/page_alloc.c (ffffffff81271e6d)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81287873)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff81292c68)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff8129ccb2)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff81684b39)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
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
In mm/vmscan.c (ffffffff81241c95)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/page_alloc.c (ffffffff812818cd)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff81297e14)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/mempolicy.c (ffffffff812a2a58)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/slub.c (ffffffff812acd19)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In drivers/tty/sysrq.c (ffffffff8169f149)
Location: include/linux/gfp.h:477
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
</details>
</li>
</ul>

## Differences
