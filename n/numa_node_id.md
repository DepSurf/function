# Function: <code>numa_node_id</code>

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
Location: include/linux/topology.h:75
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034964)
Location: include/linux/topology.h:75
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81034edc)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff8114694e)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
```
```
In kernel/trace/trace_uprobe.c (ffffffff8116f778)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff811851cf)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81187655)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff8118b738)
Location: include/linux/topology.h:75
Inline: True
```
```
In mm/page_alloc.c (ffffffff81191ab8)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:alloc_kmem_pages_node
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
```
```
In mm/vmscan.c (ffffffff811a53d1)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:zone_reclaim
```
```
In mm/shmem.c (ffffffff811a67e3)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
```
```
In mm/vmstat.c (ffffffff811ad2bb)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
  - mm/vmstat.c:zone_statistics
```
```
In mm/percpu.c (ffffffff811b0b45)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff811bc496)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/vmalloc.c (ffffffff811ce8e0)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff811d2ba1)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811daf47)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811e03ed)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
```
```
In mm/sparse-vmemmap.c (ffffffff8181f14a)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff811e6d37)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff811eaa1f)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff811f3679)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff811f6376)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/memcontrol.c (ffffffff811ff42f)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/userfaultfd.c (ffffffff81207c33)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In block/blk-mq.c (ffffffff813c3c43)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/pci/pci-driver.c (ffffffff8143a848)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/iommu/dmar.c (ffffffff81535156)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81535832)
Location: include/linux/topology.h:75
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f4d17)
Location: include/linux/topology.h:75
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
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81033b16)
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340bf)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/fork.c (ffffffff810809d1)
Location: include/linux/topology.h:71
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffff8114f198)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81157ae9)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8117ce60)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/events/ring_buffer.c (ffffffff8119702a)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81199c37)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff8119e0dd)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811a65b5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_page_frag
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811bc10a)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff811bf1b3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff811c58e2)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff811c9d71)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff811dbb8c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/vmalloc.c (ffffffff811eb532)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff811f0938)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff811f90c1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81201724)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse-vmemmap.c (ffffffff818995f2)
Location: include/linux/topology.h:71
Inline: True
```
```
In mm/ksm.c (ffffffff81205d88)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81206af9)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81213517)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8121514c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff8122319c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/userfaultfd.c (ffffffff8122d58d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In block/blk-mq.c (ffffffff81407fb7)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/pci/pci-driver.c (ffffffff81486769)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/char/random.c (ffffffff81567951)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff81589a00)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8158d64f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592937)
Location: include/linux/topology.h:71
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
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103373a)
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81033cee)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff81159332)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_alloc_read_page
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81162d19)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81188a72)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811931d6)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff811a6a34)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811a9308)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811adb0e)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811b6925)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/vmscan.c (ffffffff811cc7da)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff811cf7e3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff811d5a12)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff811d9e66)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff811eb3fc)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff811f4ebb)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff811fc7a2)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff8120133a)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81209cb1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81213214)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/sparse-vmemmap.c (ffffffff818cdcaa)
Location: include/linux/topology.h:71
Inline: True
```
```
In mm/ksm.c (ffffffff81217d98)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812188c3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8122587c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8122775c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff8123568b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/userfaultfd.c (ffffffff8123fac1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In block/blk-mq.c (ffffffff81422c63)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
```
In drivers/pci/pci-driver.c (ffffffff814a7f29)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/char/random.c (ffffffff81594081)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff815b70b6)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82015bc5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c01f4)
Location: include/linux/topology.h:71
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
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810315b0)
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff81031d96)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In kernel/trace/ring_buffer.c (ffffffff8115e8f1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8116611a)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118b6e8)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff8119a1f6)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff811ae213)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811b0885)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811b4f7f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811be7e5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (ffffffff811d5438)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff811d6623)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff811de6c2)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff811e34b9)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff811f5e0f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff811ff98e)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81207414)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff8120c1e5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/hugetlb.c (ffffffff81214342)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff8121e532)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81905158)
Location: include/linux/topology.h:71
Inline: True
```
```
In mm/ksm.c (ffffffff812239a0)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8122446d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81230ee4)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8123393c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff812410a4)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff8124726c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff8124b5f3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In block/blk-mq.c (ffffffff814327b3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff815a7f81)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff815cce2b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f7887)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d5c14)
Location: include/linux/topology.h:71
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
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810337f4)
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/pci-dma.c (ffffffff810340cd)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:dma_generic_alloc_coherent
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff8108039f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:sev_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff8116b8f1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811730ad)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81199193)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811a95c6)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff811c1e83)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811c438c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811c90b7)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811d3555)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (ffffffff811ea968)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff811ebb43)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff811f4255)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff811f8d84)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff8120da6b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff812180b3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81220504)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff812258a9)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff8122a681)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8122ef02)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81239760)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff8198f149)
Location: include/linux/topology.h:71
Inline: True
```
```
In mm/ksm.c (ffffffff8123efe0)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8123facd)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8124ec8d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:new_page_node
```
```
In mm/huge_memory.c (ffffffff81251245)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff81260de4)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812673c3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff8126b92d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff8126db1f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In block/blk-mq.c (ffffffff8145e383)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff8160e881)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff81633c2b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff82700f68)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163c9c4)
Location: include/linux/topology.h:71
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
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81034b6d)
Location: include/linux/topology.h:71
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8110cdd5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_alloc
```
```
In kernel/trace/ring_buffer.c (ffffffff8117ae64)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8118208d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ae872)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811c0aa5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff811e2243)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811e4887)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811e99f5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff811f47f5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (ffffffff8120c146)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff8120d2ee)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff81215581)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff8121a776)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff8122e1d5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff81239497)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812422df)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff81247e3b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff8124b921)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81252820)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8125ccb5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff819eb9c5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81262778)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8126313d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81272ace)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8127571d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff81284dd0)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff8128bcb5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff81290349)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff81292127)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hmm.c:hmm_devmem_pages_create
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In block/blk-mq.c (ffffffff81491cba)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff816481d1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff8166ee2f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272ac7c)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel-iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81677e12)
Location: include/linux/topology.h:71
Inline: True
```
```
In net/core/page_pool.c (ffffffff818bd6f8)
Location: include/linux/topology.h:71
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
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81035d4d)
Location: include/linux/topology.h:71
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81118ad7)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811878d4)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8118fa4d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bcf06)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811d1f45)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff811f26b3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff811f56e3)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In kernel/memremap.c (ffffffff811fa4f1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/memremap.c:devm_memremap_pages
```
```
In mm/page_alloc.c (ffffffff81206c25)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/vmscan.c (ffffffff8121edc5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff8122101e)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff81228475)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff8122d726)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff812422e4)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff8124d71a)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff81256a0f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/swap_state.c (ffffffff8125c412)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff8125ffa4)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81266a83)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81271595)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81a26c48)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81276ff8)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812779cd)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff81286bf1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff8128a677)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff81299ce0)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812a0c15)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff812a52ce)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (ffffffff812a6dd5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_alloc_locked_page
```
```
In block/blk-mq.c (ffffffff814ab727)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In block/blk-zoned.c (ffffffff814cbd32)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
```
In drivers/char/random.c (ffffffff81666671)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff8168d388)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff81690270)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff81694087)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ef2)
Location: include/linux/topology.h:71
Inline: True
```
```
In net/core/xdp.c (ffffffff818e1bc8)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818e4ad6)
Location: include/linux/topology.h:71
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
Location: include/linux/topology.h:71
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81037ead)
Location: include/linux/topology.h:71
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81122f54)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81194e0e)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119d45b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cc5a9)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811e6275)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff8120a383)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8120d461)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff8122e488)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff812307f0)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff81238197)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff8123d453)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff81251483)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff8125f9f6)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff8126ac4b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (ffffffff8126cc65)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff81277600)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff8127ac25)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81281c99)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128cba5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81a974ea)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81292859)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8129411b)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812a1191)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a529d)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff812b4f99)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812bbea5)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff812c0a9f)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812c2b48)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - mm/memremap.c:devm_memremap_pages
```
```
In block/blk-mq.c (ffffffff814d9917)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff8169c3b1)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff816c4d91)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816c8410)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816cc997)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816cf864)
Location: include/linux/topology.h:71
Inline: True
```
```
In net/core/xdp.c (ffffffff81930647)
Location: include/linux/topology.h:71
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff819342cc)
Location: include/linux/topology.h:71
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
Location: include/linux/topology.h:86
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103867d)
Location: include/linux/topology.h:86
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8112f394)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811a08ce)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a8e1c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d8b74)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811f29c5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff81217663)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8121a8f1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff8123c618)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff8123ea10)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff81246427)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff8124b8a3)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff8125fa33)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff8126e206)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff81279b5d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (ffffffff8127ba75)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff812870e4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff8128a705)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812916c4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8129c7d5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81acedcc)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812a25d9)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812a43a0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812b25a1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812b675d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff812c6a89)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812cdd85)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff812d284f)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812d49fe)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814f2cd7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff816bf121)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff816e7cc1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816eb3c0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816f01d4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816f36a4)
Location: include/linux/topology.h:86
Inline: True
```
```
In net/core/xdp.c (ffffffff819627a7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81966efc)
Location: include/linux/topology.h:86
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
Location: include/linux/topology.h:86
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b0c5)
Location: include/linux/topology.h:86
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8113dd79)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b6eae)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811c10fc)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4f7a)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/helpers.c (ffffffff81214805)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff8121e33e)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81242f13)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff812472e8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff8126ad63)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/shmem.c (ffffffff8126c0d7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff81274010)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff8127984f)
Location: include/linux/topology.h:86
Inline: True
```
```
In mm/memory.c (ffffffff8128feeb)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff8129e5c9)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812aa255)
Location: include/linux/topology.h:86
Inline: True
```
```
In mm/page_alloc.c (ffffffff812adc75)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff812b95d1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff812bd4da)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812c4995)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812d050e)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81bc778e)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812d6ce4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812d7629)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812e7b41)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812eb88d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/page_isolation.c (ffffffff81304095)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff81308297)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/memremap.c (ffffffff8130a52b)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In fs/io-wq.c (ffffffff8138b0c5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_enqueue
```
```
In block/blk-mq.c (ffffffff8155329c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff817725d0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/iommu/dma-iommu.c (ffffffff81792193)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179e801)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1d863)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817a78b7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ab944)
Location: include/linux/topology.h:86
Inline: True
```
```
In net/core/xdp.c (ffffffff81a356f7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3a61c)
Location: include/linux/topology.h:86
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
Location: include/linux/topology.h:86
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103b8d5)
Location: include/linux/topology.h:86
Inline: True
```
```
In kernel/dma/direct.c (ffffffff811385bd)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff81139be8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b4a64)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bed2c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f390a)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/helpers.c (ffffffff812162e5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff812210ca)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_area_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8124d5b3)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81251964)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff812757a3)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/shmem.c (ffffffff81276b27)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff8127e864)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff812840bf)
Location: include/linux/topology.h:86
Inline: True
```
```
In mm/memory.c (ffffffff8129a96b)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812a9989)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812b5915)
Location: include/linux/topology.h:86
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b9755)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff812c5051)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff812c8ff7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812d0635)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812dc02e)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81c404c2)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812e2874)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812e4b61)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812f322c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812f693d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff81314031)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/memremap.c (ffffffff81315fdf)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/io-wq.c (ffffffff8139c325)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_enqueue
```
```
In block/blk-mq.c (ffffffff8156f92c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff8178d640)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/iommu/intel/dmar.c (ffffffff817ac551)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b57f)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff817b3757)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b7d24)
Location: include/linux/topology.h:86
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817be969)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/xdp.c (ffffffff81a37a97)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a3cb3d)
Location: include/linux/topology.h:86
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
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810340f2)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103d273)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81069155)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In kernel/dma/direct.c (ffffffff811396db)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8113ad08)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811b3e24)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811bf5fc)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e84)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff81218ff5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff81224b7e)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff81251ef3)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81255796)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff8127aac3)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/shmem.c (ffffffff8127bd5a)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff812839ca)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff81288cff)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/memory.c (ffffffff8129fe56)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812aee14)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812bb005)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/page_alloc.c (ffffffff812beb25)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff812cbd06)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff812cfa77)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff812d74d4)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812e38ab)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81c3256a)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812ea004)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812ec7f1)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812f92b1)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812fccf0)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff8131a1dc)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/memremap.c (ffffffff8131c210)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/io-wq.c (ffffffff813a3475)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_enqueue
```
```
In block/blk-mq.c (ffffffff815777dc)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff817705f1)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:extract_crng_user
  - drivers/char/random.c:extract_crng_user
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178f421)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff83215f14)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff81796887)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff8179ae93)
Location: include/linux/topology.h:87
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff817a1809)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/skbuff.c (ffffffff819d01bb)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81a1ec27)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81a245ba)
Location: include/linux/topology.h:87
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
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81039392)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff81042db0)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073495)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In kernel/dma/direct.c (ffffffff8115c6a9)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/dma/ops_helpers.c (ffffffff8115dc38)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811dddf8)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811e9ee1)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812270c1)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff8124f715)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff8125cabe)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8128d783)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81291446)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff812b8b23)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/shmem.c (ffffffff812b9eca)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff812c1cc8)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff812c878f)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/memory.c (ffffffff812e3145)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/mprotect.c (ffffffff812f0604)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812fd605)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/page_alloc.c (ffffffff813013b5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff81310e9b)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff81315047)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8131df28)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8132aaf1)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81d510ad)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff81331f24)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff81335123)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8133db12)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page_thp
```
```
In mm/huge_memory.c (ffffffff81345fef)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffffffff81367106)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/memremap.c (ffffffff813694fc)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/io-wq.c (ffffffff813f2955)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_enqueue
```
```
In block/blk-mq.c (ffffffff815dc4fc)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff817f6076)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
  - drivers/char/random.c:_get_random_bytes
```
```
In drivers/iommu/intel/dmar.c (ffffffff81816d41)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8181a38c)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8181e817)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff818239c3)
Location: include/linux/topology.h:87
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff8182ae79)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/skbuff.c (ffffffff81a80824)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81ad3ced)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81ad8bf8)
Location: include/linux/topology.h:87
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
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81040206)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8104aec8)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081305)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In kernel/dma/direct.c (ffffffff81186434)
Location: include/linux/topology.h:87
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff81187bf8)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81214e36)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81221d20)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff81266c08)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff812968f5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff812a6949)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff812e252f)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff81300129)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
```
```
In mm/vmscan.c (ffffffff813145cd)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/vmstat.c (ffffffff8131ee46)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff8132613e)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/memory.c (ffffffff81344482)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
```
```
In mm/mprotect.c (ffffffff81353b42)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff81364555)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/page_alloc.c (ffffffff81368bd5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff813805bd)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff813897ae)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8139a49a)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
```
```
In mm/sparse-vmemmap.c (ffffffff81f212d6)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff813a4861)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/memremap.c (ffffffff813e7641)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In block/blk-mq.c (ffffffff81689e5b)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In io_uring/io-wq.c (ffffffff816db4d5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
```
```
In drivers/iommu/intel/dmar.c (ffffffff81957d46)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff8195bd6e)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_domain_alloc
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:iommu_alloc_root_entry
  - drivers/iommu/intel/iommu.c:pfn_to_dma_pte
```
```
In drivers/iommu/intel/pasid.c (ffffffff8195eb8e)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81963025)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196c296)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
```
```
In net/core/skbuff.c (ffffffff81bf4f73)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81c5207d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81c59c09)
Location: include/linux/topology.h:87
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
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81049470)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105693d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093b75)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In kernel/dma/direct.c (ffffffff811c1e34)
Location: include/linux/topology.h:87
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811c3873)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8125e4f6)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8126cca7)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b888e)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/helpers.c (ffffffff812f18a5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff81304e09)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8134ac9f)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8136aa79)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
```
```
In mm/vmscan.c (ffffffff8138870d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/vmstat.c (ffffffff81392907)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff8139c8a1)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/slab_common.c (ffffffff813a12f5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/memory.c (ffffffff813bc5e2)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
```
```
In mm/mprotect.c (ffffffff813ce4ba)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff813e0095)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/page_alloc.c (ffffffff813e4b35)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff813feead)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8140839d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/mempolicy.c (ffffffff8141a4ba)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
```
```
In mm/sparse-vmemmap.c (ffffffff820cb1b9)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8142a4d7)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/memremap.c (ffffffff8146f2c1)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In block/blk-mq.c (ffffffff817483de)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In io_uring/io-wq.c (ffffffff817a75a5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_enqueue
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abed06)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81ac358a)
Location: include/linux/topology.h:87
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
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acbfed)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad4837)
Location: include/linux/topology.h:87
Inline: True
```
```
In net/core/skbuff.c (ffffffff81da4580)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81e0730d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e103ec)
Location: include/linux/topology.h:87
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
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff810496c9)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105790d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096b05)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In kernel/dma/direct.c (ffffffff811d496c)
Location: include/linux/topology.h:87
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811d63c3)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff812756d6)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff81283e37)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dbece)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/helpers.c (ffffffff8131e485)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff81333799)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff8137bccf)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff8139cc06)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
```
```
In mm/vmscan.c (ffffffff813ba89d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/vmstat.c (ffffffff813c531b)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff813cf981)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/slab_common.c (ffffffff813d4575)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/memory.c (ffffffff813f0fcd)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
```
```
In mm/mprotect.c (ffffffff81402cf7)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff81414dd5)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/page_alloc.c (ffffffff81419615)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swapfile.c (ffffffff81431ded)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8143b2ad)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/mempolicy.c (ffffffff8144da48)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
```
```
In mm/sparse-vmemmap.c (ffffffff8214f449)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/slub.c (ffffffff8145f8d8)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
```
In mm/memremap.c (ffffffff814a3aa4)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/splice.c (ffffffff814fa7a7)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In block/blk-mq.c (ffffffff81784aeb)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c75)
Location: include/linux/topology.h:87
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07add)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b0b6a6)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f0c9)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b1321b)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b18b73)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23007)
Location: include/linux/topology.h:87
Inline: True
```
```
In net/core/skbuff.c (ffffffff81e131d4)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81e79b1d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81e83c8c)
Location: include/linux/topology.h:87
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
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050ab1)
Location: include/linux/topology.h:87
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8105ebad)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
  - arch/x86/kernel/espfix_64.c:init_espfix_ap
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e075)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In kernel/dma/direct.c (ffffffff811e985c)
Location: include/linux/topology.h:87
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb3f3)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8128fd90)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8129edc7)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f9fae)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
```
```
In kernel/bpf/helpers.c (ffffffff813408a5)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/bpf/ringbuf.c (ffffffff81357e89)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_alloc
```
```
In kernel/events/ring_buffer.c (ffffffff813a4f0f)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In mm/page-writeback.c (ffffffff813c68e6)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page-writeback.c:do_writepages
```
```
In mm/vmscan.c (ffffffff813e39bd)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
```
```
In mm/shmem.c (ffffffff813e9966)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_folio
```
```
In mm/vmstat.c (ffffffff813efd12)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff813fa581)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/memory.c (ffffffff8141bce0)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memory.c:numa_migrate_prep
```
```
In mm/mprotect.c (ffffffff8142f396)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff81441875)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/page_alloc.c (ffffffff81446355)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/slub.c (ffffffff81454f10)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:___slab_alloc
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/swap_state.c (ffffffff81465b54)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff8146b1dd)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8147509d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_fresh_hugetlb_folio
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/topology.h:87
Inline: True
```
```
In mm/mempolicy.c (ffffffff8148762a)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:folio_alloc
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:vma_policy_mof
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:alloc_migration_target_by_mpol
```
```
In mm/sparse-vmemmap.c (ffffffff82232319)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/memremap.c (ffffffff814d4945)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - mm/memremap.c:pagemap_range
```
```
In fs/splice.c (ffffffff8152f199)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In block/blk-mq.c (ffffffff817c6ffb)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b57553)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac4b)
Location: include/linux/topology.h:87
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5bb0d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pgtable
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f77c)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b639b9)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67e4a)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6e4e2)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79977)
Location: include/linux/topology.h:87
Inline: True
```
```
In net/core/skbuff.c (ffffffff81ed0394)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__alloc_skb
```
```
In net/core/xdp.c (ffffffff81f39c3d)
Location: include/linux/topology.h:87
Inline: True
Inline callers:
  - net/core/xdp.c:xdpf_clone
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81f4435c)
Location: include/linux/topology.h:87
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
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffff80001021a098)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffff800010225b7c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffff800010259bd0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffff8000102767d0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffff8000102a20a4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffff8000102a5cac)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffff8000102cd678)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/shmem.c (ffff8000102d07ec)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffff8000102dadd8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffff8000102e1b88)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffff8000102fa1b0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffff800010305164)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffff800010310d4c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (ffff800010313c10)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffff800010321bfc)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffff8000103258e4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffff80001032f4f8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffff80001033b760)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffff800010da09d8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffff800010341fbc)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffff80001034579c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffff800010352de8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffff800010357460)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffff8000103697a8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffff800010372238)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffff800010378244)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In block/blk-mq.c (ffff8000105f2540)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/irqchip/irq-gic.c (ffff80001066c57c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000106713d4)
Location: include/linux/topology.h:86
Inline: True
```
```
In drivers/gpio/gpio-mxc.c (ffff8000106d2044)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
```
```
In drivers/dma/ipu/ipu_irq.c (ffff80001148f1c0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
```
```
In drivers/char/random.c (ffff8000108afcf0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca588)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/iommu/io-pgtable-arm.c (ffff8000108cb420)
Location: include/linux/topology.h:86
Inline: True
```
```
In net/core/xdp.c (ffff800010c070c4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffff800010c0cf00)
Location: include/linux/topology.h:86
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
Location: include/linux/topology.h:117
Inline: True
```
```
In arch/arm/kernel/signal.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In arch/arm/mm/dma-mapping.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In arch/arm/mm/fault-armv.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In arch/arm/mach-imx/tzic.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/power/snapshot.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/zbud.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/irqchip/irq-hip04.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/irqchip/irq-gic.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/gpio/gpio-mxc.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/dma/ipu/ipu_irq.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/iommu/tegra-smmu.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/topology.h:117
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
In arch/powerpc/kernel/smp.c (c0000000000563f4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
```
```
In kernel/bpf/helpers.c (c00000000031e800)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/uprobes.c (c000000000358cec)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (c00000000038b2a0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/shmem.c (c00000000038e2a8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (c000000000399a70)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/memory.c (c0000000003bf564)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (c0000000003d23d0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (c0000000003e1bf0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (c0000000003e445c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
```
In mm/swap_state.c (c0000000003f7410)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (c0000000003fbbfc)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/mempolicy.c (c0000000004164d8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/ksm.c (c00000000041f7fc)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (c00000000043f4f8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (c000000000458000)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (c000000000463b54)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (c00000000046b090)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In drivers/char/random.c (c000000000947eec)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
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
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/fork.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/dma/direct.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/relay.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/filemap.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/mempool.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/readahead.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/shmem.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/percpu.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/memory.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/swap_state.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/ksm.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/swap_cgroup.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/page_isolation.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/zbud.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/balloon_compaction.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/pipe.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/dir.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In fs/fuse/readdir.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In security/selinux/ss/status.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/char/tpm/tpm-sysfs.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/linux/topology.h:117
Inline: True
```
```
In net/core/page_pool.c (0)
Location: include/linux/topology.h:117
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
Location: include/linux/topology.h:86
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810387dd)
Location: include/linux/topology.h:86
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81127ac9)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81198eee)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811a143c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d1194)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811eafe5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff8120fcb3)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81212f41)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff81234c68)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff81237060)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff8123ea77)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff81243ef3)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff81258083)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff81266856)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff812721ad)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (ffffffff812740c5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff8127f734)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff81282ce5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81289ca4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81294db5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81a6dc3c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff8129abb9)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8129c980)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812aab81)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812aed3d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff812bf069)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812c6365)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff812cae2f)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812ccfde)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814eb2b7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff81684b71)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff816ad7a1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816b0cf0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816b59c4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816b8e94)
Location: include/linux/topology.h:86
Inline: True
```
```
In drivers/nvme/host/multipath.c (ffffffff81749c83)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In net/core/xdp.c (ffffffff81902777)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81906ecc)
Location: include/linux/topology.h:86
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
Location: include/linux/topology.h:86
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff810281ae)
Location: include/linux/topology.h:86
Inline: True
```
```
In kernel/dma/direct.c (ffffffff8111a3d4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff8118c72e)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119440c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3f64)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811ddda5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff81202a43)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81205cb1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff81227cd8)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff8122a0c0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff81231a77)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff81236ec3)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff8124db3a)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff81258c44)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/vmalloc.c (ffffffff8126411d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (ffffffff81266035)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff81271554)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff81274805)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff8127bad4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812869c5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81a2a183)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff8128c779)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8128e510)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff8129c4de)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812a025d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff812b0159)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812b73a5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff812bbd89)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812bde4e)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814db807)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff81662811)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff8168b101)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff8168e7f0)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff81693604)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81696ad4)
Location: include/linux/topology.h:86
Inline: True
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b863)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_ns_head_make_request
```
```
In drivers/hv/channel.c (ffffffff81850ede)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_alloc_ring
```
```
In net/core/xdp.c (ffffffff818bc5a7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff818c0cdc)
Location: include/linux/topology.h:86
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
Location: include/linux/topology.h:86
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103863d)
Location: include/linux/topology.h:86
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81125864)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff81196cbe)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff8119f20c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cef64)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811e8db5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff8120da53)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff81210ce1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff81232a08)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff81234e00)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff8123c817)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff81241c93)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff81255e23)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff812645f6)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff8126ff4d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (ffffffff81271e65)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff8127d4d4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff81280af5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81287ab4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81292bc5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81ada04c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812989c9)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff8129a790)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812a8991)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812acb4d)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff812bce79)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812c4175)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff812c8c3f)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812cadee)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff814e7347)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff816b2f61)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff816db981)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816df080)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816e3e94)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff816e7364)
Location: include/linux/topology.h:86
Inline: True
```
```
In net/core/xdp.c (ffffffff819537a7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81957efc)
Location: include/linux/topology.h:86
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
Location: include/linux/topology.h:86
Inline: True
```
```
In arch/x86/kernel/espfix_64.c (ffffffff8103963d)
Location: include/linux/topology.h:86
Inline: True
```
```
In kernel/dma/direct.c (ffffffff81131ea4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/dma/direct.c:__dma_direct_alloc_pages
```
```
In kernel/trace/ring_buffer.c (ffffffff811a48ce)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_allocate_cpu_buffer
  - kernel/trace/ring_buffer.c:__rb_allocate_pages
```
```
In kernel/trace/trace.c (ffffffff811acf5b)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_buffered_event_enable
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd1f4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:probe_event_enable
```
```
In kernel/bpf/helpers.c (ffffffff811f7165)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_numa_node_id
```
```
In kernel/events/ring_buffer.c (ffffffff8121c903)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_mmap_alloc_page
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
```
In kernel/events/uprobes.c (ffffffff8121fbf9)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/vmscan.c (ffffffff81241ec3)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
```
```
In mm/shmem.c (ffffffff81245200)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/shmem.c:shmem_alloc_page
  - mm/shmem.c:shmem_alloc_hugepage
```
```
In mm/vmstat.c (ffffffff8124bf56)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmstat.c:refresh_cpu_vm_stats
```
```
In mm/percpu.c (ffffffff81251433)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
```
In mm/memory.c (ffffffff812658b1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff81273fb4)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/vmalloc.c (ffffffff8127f943)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_map_ram
```
```
In mm/page_alloc.c (ffffffff812818c5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_alloc.c:nr_free_zone_pages
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:page_frag_alloc
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/swap_state.c (ffffffff8128d0a7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swap_state.c:__read_swap_cache_async
```
```
In mm/swapfile.c (ffffffff81290815)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
```
```
In mm/hugetlb.c (ffffffff81298050)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812a29b5)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:new_page
  - mm/mempolicy.c:new_page
```
```
In mm/sparse-vmemmap.c (ffffffff81ae6502)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/ksm.c (ffffffff812a8779)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/slub.c (ffffffff812aa670)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/slub.c:kmalloc_large_node
  - mm/slub.c:___slab_alloc
```
```
In mm/migrate.c (ffffffff812b8cb1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812bcecd)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/memcontrol.c (ffffffff812cd669)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In mm/page_isolation.c (ffffffff812d4c35)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In mm/userfaultfd.c (ffffffff812d992c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/memremap.c (ffffffff812dbb2c)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - mm/memremap.c:memremap_pages
```
```
In block/blk-mq.c (ffffffff815002e7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_alloc_rqs
```
```
In drivers/char/random.c (ffffffff816cd4c1)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:crng_backtrack_protect
  - drivers/char/random.c:extract_crng
```
```
In drivers/iommu/dmar.c (ffffffff816f5f51)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_enable_qi
```
```
In drivers/iommu/intel-iommu.c (ffffffff816f9690)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel-pasid.c (ffffffff816fe55a)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel_irq_remapping.c (ffffffff81701a64)
Location: include/linux/topology.h:86
Inline: True
```
```
In net/core/xdp.c (ffffffff819752c7)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
```
```
In net/core/page_pool.c (ffffffff81979fec)
Location: include/linux/topology.h:86
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
</details>
</li>
</ul>

## Differences
