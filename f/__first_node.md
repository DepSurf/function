# Function: <code>__first_node</code>

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
In arch/x86/kernel/topology.c (ffffffff81f68c89)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104310c)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/mm/init_64.c (ffffffff81f77c74)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81f78423)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f792ee)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff81097949)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/core.c (ffffffff81f7dc66)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810b3d67)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:show_numa_stats
```
```
In kernel/power/snapshot.c (ffffffff810d1eaf)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In kernel/irq/irqdesc.c (ffffffff81f7ef2a)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cpuset.c (ffffffff8111b313)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_spread_node
```
```
In mm/oom_kill.c (ffffffff81191156)
Location: include/linux/nodemask.h:251
Inline: True
```
```
In mm/page_alloc.c (ffffffff81191fbd)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/vmscan.c (ffffffff811a0ca6)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:kswapd_init
```
```
In mm/mmzone.c (ffffffff811ac2f6)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/compaction.c (ffffffff811b82e3)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811b9442)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff811cd6cb)
Location: include/linux/nodemask.h:251
Inline: True
```
```
In mm/hugetlb.c (ffffffff811d9b39)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/hugetlb.c:next_node_allowed
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_show_meminfo
```
```
In mm/mempolicy.c (ffffffff811dfc80)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:policy_zonelist
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_parse_str
```
```
In mm/slub.c (ffffffff811edb01)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff811f9745)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
```
In fs/dcache.c (ffffffff81223f39)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff81242bc8)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff81277cd5)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81286cd6)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8148b1e9)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff81fa47ce)
Location: include/linux/nodemask.h:251
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff814ed9e6)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fab6f4)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff815601e6)
Location: include/linux/nodemask.h:251
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/topology.c (ffffffff81f90b99)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810430ed)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/mm/init_64.c (ffffffff81fa03ba)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81fa145d)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_set_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa1a3e)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff81fa50f5)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/core.c (ffffffff81fa6b15)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c2735)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/power/snapshot.c (ffffffff810d7147)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff81fa7f67)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In mm/oom_kill.c (ffffffff811a5a9d)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fb0ed6)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/vmscan.c (ffffffff81fb1d64)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811c50a6)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/compaction.c (ffffffff81fb43a3)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811d3742)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff811ea7a6)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f987a)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff81201f69)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:policy_zonelist
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8120cfb1)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81fb7d11)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
```
In fs/dcache.c (ffffffff8124c686)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff8126aeea)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff812a4035)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff812b3ea6)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In lib/nodemask.c (ffffffff81433ee4)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/acpi/numa.c (ffffffff814da01d)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff81fd0d4b)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff8153e656)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81567def)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fd82ba)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff815b48a6)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/topology.c (ffffffff81fcbf37)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042bb4)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/mm/init_64.c (ffffffff81fdb924)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81fdcae4)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fdd01b)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff8109fdf9)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/core.c (ffffffff81fe2691)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c87b5)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/power/snapshot.c (ffffffff810ddcce)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff81fe3d6f)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff810ef996)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/oom_kill.c (ffffffff811b5ea0)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fed776)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/vmscan.c (ffffffff811c6da6)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811d51b6)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff81fee8cd)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
```
```
In mm/compaction.c (ffffffff81ff0d9a)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811e35f2)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_destroy
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff811fb213)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120a180)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff81213c25)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8121f011)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff8123073a)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
```
In fs/dcache.c (ffffffff8125f666)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff8127e01a)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff812b9af0)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812c9736)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In lib/nodemask.c (ffffffff81450169)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/acpi/numa.c (ffffffff814fc8e0)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff8200e6c3)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff8156acab)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff8159451f)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff8201600f)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff815e3b46)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/topology.c (ffffffff820ac652)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040cb8)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/mm/init_64.c (ffffffff820bc8fd)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff820bdab0)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff820bdf7d)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff8109d629)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810c29e5)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
```
```
In kernel/sched/topology.c (ffffffff810cbe05)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810dcdfb)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff820c4872)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff810ef94a)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/oom_kill.c (ffffffff811bd9a0)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In mm/page_alloc.c (ffffffff820cf3de)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/vmscan.c (ffffffff811cf546)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811de016)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff820d0960)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff820d31c9)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811edb01)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff81205f57)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In mm/hugetlb.c (ffffffff81215684)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8121eff0)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff8122b6c7)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
```
In mm/memcontrol.c (ffffffff8123bf58)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
```
In fs/dcache.c (ffffffff8126cec9)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff8128bbca)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff812c6d58)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812d6786)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8150cc69)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff820f0164)
Location: include/linux/nodemask.h:253
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff8157f2db)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff815a847d)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f7ce9)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff815f8816)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff818eff04)
Location: include/linux/nodemask.h:253
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff826b2e74)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043efc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/mm/init_64.c (ffffffff826c334a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff826c48e7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff826c4db7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810a3cc9)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810ca1d5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810d4608)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810e5026)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff826ccb0b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff810f8531)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/oom_kill.c (ffffffff811d25e0)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/page_alloc.c (ffffffff826d7dfe)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/vmscan.c (ffffffff811e48f6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811f3a96)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff826d9397)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff826dbbee)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81203f61)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8121ec77)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/swapfile.c (ffffffff826dce7e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff8123025a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8123a210)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff81246dd4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
```
In mm/memcontrol.c (ffffffff8125b7c8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
```
In fs/dcache.c (ffffffff8128f269)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff812ea8d8)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812fafd6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8154fbcd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff826f9959)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In drivers/tty/sysrq.c (ffffffff815e3e4b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff8160ed8d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff827013d1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff81660856)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81976354)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff826dc63c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810462bf)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/mm/init_64.c (ffffffff826ed596)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff826eeb8a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff826ef10c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff826f3c89)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/fair.c (ffffffff810d2185)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810dc1fb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810eccaf)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff826f6cf2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff81100754)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f375f)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/page_alloc.c (ffffffff8270229f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/vmscan.c (ffffffff827035ad)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81214dc5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff82703841)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff827060cc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81224af1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8124093d)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/swapfile.c (ffffffff827073af)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff812536a7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8125d7f2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff81268198)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff8270a014)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
```
```
In fs/dcache.c (ffffffff812b684c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81317dc7)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In fs/proc/kcore.c (ffffffff813285cb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff81586470)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff82723cff)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff8161d11d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff816484cb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272b0f0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff8169c041)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff819d2b19)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff82892a14)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81047d41)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810486fa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/init_64.c (ffffffff828a4128)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828a5878)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a5dfa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff828aaa71)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/fair.c (ffffffff810dbaf5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810e5e36)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810f834f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff828adc1e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff8110bf19)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/oom_kill.c (ffffffff81205707)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/page_alloc.c (ffffffff828b99be)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/vmscan.c (ffffffff828bacd6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81227ca5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff828baf6a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828bd871)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81237a61)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8125522d)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/swapfile.c (ffffffff828be781)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff812675e7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8127205f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff8127dcb7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828c11a1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_nr_lru_pages
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffffffff812cbbb8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8132eba7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff8133f813)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8159e780)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828dbee4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff8163a37d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81666996)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e397e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816bc9e1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81a0c199)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff828a9f5c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104aa6a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b4af)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/init_64.c (ffffffff828bc5be)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828bde46)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828be3d2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff828c324d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/fair.c (ffffffff810e2a9a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810eca9a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff81100911)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff828c65d3)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff8111567c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff8121c4df)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (ffffffff828d2160)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff812379e5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff828d23cb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828d4e69)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81248fdd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812672dc)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/page_alloc.c (ffffffff828d6aaa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff828d793e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff81283051)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8128d5a8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff81299b05)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828da522)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffffffff812e8a72)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81356615)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81367b08)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815cfc80)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828f67dd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff8166e6ad)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff8169c70e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828fdebc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816f7211)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81a7bafd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff828acfbf)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b4a7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104be7e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd1cf)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/mm/init_64.c (ffffffff828c2a65)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828c42a0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c482a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c93af)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/workqueue.c (ffffffff810bfa2e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810ed14a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810f853a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff8110cd71)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff828cec00)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff8112187b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff81229eaf)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (ffffffff828da5de)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81245c95)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff828da83d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828dd2f8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8125742d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff81275b4b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828def3b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff828dfdaf)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff81292b71)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8129d256)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff812a99c5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828e29c9)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffffffff812fa612)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8136e844)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff8137fd88)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815f0ef0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828ff834)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff81690ced)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff816bf47e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82906f24)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff8171b631)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81ab2e5d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff82cd236a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ec3b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:nearby_node
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104ff7b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:nearby_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1735)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff82ce5e82)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff82ce7786)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff82ce7b98)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebe5d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/workqueue.c (ffffffff82ced7fa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff810f705a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff8110256d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81117ee3)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff82cf00b2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff8112e33c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In mm/oom_kill.c (ffffffff81255818)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff82cf8970)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81273a25)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff82cf8c72)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff82cfa77d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff812859e1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812a6e7b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff82cfc324)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff82cfd1fd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff812c5eb9)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff812d0e5d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff812de565)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
```
```
In mm/memcontrol.c (ffffffff82cffaa0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
```
```
In fs/dcache.c (ffffffff813336b0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff8138a084)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_all
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
```
```
In fs/proc/task_mmu.c (ffffffff813b6476)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813ca221)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In lib/nodemask.c (ffffffff815ed6ff)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff82d16b6c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff817433bd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff817736e5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1d8e6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff817d76f1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/topology.c (ffffffff82fbe1b1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104defb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:nearby_node
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f18b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:nearby_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce4dc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff82fd3803)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff82fd51f5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff82fd558f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff82fd9e54)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff810f527a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:numa_group_count_active_nodes
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff8110118d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81114323)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff82fdca9d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff81129f2c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In mm/oom_kill.c (ffffffff81260498)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff82fe5669)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8127e295)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff82fe594a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff82fe7479)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8128fca1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812b46cb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff82fe8d3f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff82fe9c2e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff812d3121)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:allowed_mems_nr
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff812dc97d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff812ea105)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
```
```
In mm/memcontrol.c (ffffffff82fec465)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_alloc_shrinker_maps
  - mm/memcontrol.c:memcg_expand_one_shrinker_map
```
```
In fs/dcache.c (ffffffff8133f020)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff8139b00c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_cpu_online
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:__io_wq_destroy
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
```
```
In fs/proc/task_mmu.c (ffffffff813c79f6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813dbee1)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In lib/nodemask.c (ffffffff81611e2f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff830047df)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff8175f23d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff8178e6a5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b602)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff817ec151)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/topology.c (ffffffff831c88c2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8105090a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81051318)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8f78)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff831de426)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff831dfcc0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff831e0038)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff831e480b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff810f735a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff811034bb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81114b66)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff831e77ae)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff81129f18)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In mm/oom_kill.c (ffffffff81265188)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff831efd35)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff81283405)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff831eff50)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff831f1bb0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81295411)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812ba869)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff831f35b5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff831f45dc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff812d9e61)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff812e41c2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff812f1f93)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff831f6c95)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_lruvec_page_state
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In fs/dcache.c (ffffffff81345488)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813a22aa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_cpu_online
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
```
```
In fs/proc/task_mmu.c (ffffffff813ced58)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813e2e83)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In lib/nodemask.c (ffffffff815f5521)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff8320f289)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff817430ad)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81770f0b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff83215f97)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff817d0e41)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/topology.c (ffffffff832a9b00)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058c8f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81059812)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc43f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff832c16b4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff832c325f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c3624)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff832c8544)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff811118ca)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff811202c4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81134cd3)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff832cb8a0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff8114a878)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In mm/oom_kill.c (ffffffff812a19b5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff832d54ab)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff812c1605)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff832d56ca)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff832d7747)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff812d5951)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812fce69)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff832d97e7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff832da898)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff81320a51)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8132b5d4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8133af49)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff8133e2a8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff832dd82c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In fs/dcache.c (ffffffff81393098)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813f3382)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_max_workers
  - fs/io-wq.c:io_wq_cpu_affinity
  - fs/io-wq.c:__io_wq_cpu_online
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
```
```
In fs/proc/task_mmu.c (ffffffff81420106)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81434993)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In lib/nodemask.c (ffffffff81662987)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff832f81e1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff817c3add)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff817f6a49)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff832ff7a0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff8185b7e1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/cpu/amd.c (ffffffff81065613)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065eca)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dd68)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff83473d47)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff83475af7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff83475eae)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff8347b650)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff8112db49)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_utility.c (ffffffff8114a953)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81156f70)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff8347f04c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff8116fe9f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/cgroup/cpuset.c (ffffffff811d891a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff812f989d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83489cdc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff8131e655)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff83489f1a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff8348c2d8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff813352e4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff81360861)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff8348e78e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff8348f9e6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff8138d745)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff8139afc6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:policy_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff813ad2c5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:kmem_cache_init
```
```
In mm/kfence/core.c (ffffffff813af256)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/migrate.c (ffffffff813b10cb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff83493075)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff813d73c3)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff814147b8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81498071)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff814aeaea)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In io_uring/io-wq.c (ffffffff816dbf27)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_cancel_cb
```
```
In lib/nodemask.c (ffffffff8177c816)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff834b0900)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff8190082d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/intel/iommu.c (ffffffff834b8527)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff834baa48)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/cpu/amd.c (ffffffff81074914)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81075206)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81083349)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093bc7)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93abd)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b997)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff83e9e8c5)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff83e9ec1e)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff83ea64d8)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff81157949)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_utility.c (ffffffff811792cf)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81187cab)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff83eab325)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff811a62ff)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ed0c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:node_random
```
```
In mm/oom_kill.c (ffffffff8136346d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83eba5bf)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff81392155)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff83eba864)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff83ebd5de)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff813abfa4)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff813dbd71)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff83ec09c5)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff83ec218d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff83ec3a09)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8141b036)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:policy_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8142dabc)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/kfence/core.c (ffffffff8142f81a)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memory-tiers.c (ffffffff83ec699c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:next_demotion_node
```
```
In mm/khugepaged.c (ffffffff81447e2f)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff83ec6fd0)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff8145c6ec)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff8149fc98)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8152bdea)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81545180)
Location: include/linux/nodemask.h:264
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a8037)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_cancel_cb
```
```
In drivers/xen/balloon.c (ffffffff83eea6b9)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff81a5a46d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/intel/iommu.c (ffffffff83ef5240)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff83ef835c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/cpu/amd.c (ffffffff8107685c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81077376)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810857f9)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096b57)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b776d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff836bf437)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff836c2a25)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff836c2d92)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff836cac98)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
```
```
In kernel/sched/fair.c (ffffffff81167999)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_utility.c (ffffffff81189ec0)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81198e3b)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff836d030d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81234e04)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff813958bd)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff836dfbcf)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
```
```
In mm/mmzone.c (ffffffff813c4b55)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff836dfe74)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff836e2fa8)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:early_pfn_to_nid
```
```
In mm/compaction.c (ffffffff836e5a8e)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
```
```
In mm/show_mem.c (ffffffff813de776)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
```
```
In mm/list_lru.c (ffffffff813e0344)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff81410611)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff81422a94)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/swapfile.c (ffffffff836e777d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff836e8ae9)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8144e4fc)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:policy_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8146313c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/kfence/core.c (ffffffff81464a3a)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memory-tiers.c (ffffffff836eb98c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:next_demotion_node
```
```
In mm/khugepaged.c (ffffffff8147d7df)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff836ebfe0)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff8149234c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff814d4fb8)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8156415b)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff8157cd60)
Location: include/linux/nodemask.h:264
Inline: True
```
```
In lib/group_cpus.c (ffffffff818e6d32)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/xen/balloon.c (ffffffff837100aa)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff81aa4a9d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/intel/iommu.c (ffffffff8371ad9f)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff8371defc)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
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
In arch/x86/kernel/cpu/amd.c (ffffffff8107ddff)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e91c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c84b)
Location: include/linux/nodemask.h:264
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e0c7)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e80b5)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff838efed7)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff838f3445)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff838f3982)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/sched/fair.c (ffffffff81174799)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/build_utility.c (ffffffff811987c0)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff811a7dc7)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff8390172d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ea24)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff813bf67d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff8391244f)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:drop_slab
```
```
In mm/shrinker.c (ffffffff813e4bc7)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
  - mm/shrinker.c:free_shrinker_info
```
```
In mm/mmzone.c (ffffffff813ef575)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff83912724)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff83915838)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:early_pfn_to_nid
```
```
In mm/compaction.c (ffffffff839182be)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
```
```
In mm/show_mem.c (ffffffff81408566)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
```
```
In mm/list_lru.c (ffffffff8140a6a4)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff8143cf71)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff8144f884)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff8145f38c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/swapfile.c (ffffffff8391a80d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/zswap.c (ffffffff8146f198)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg
```
```
In mm/hugetlb.c (ffffffff8391c079)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:remove_pool_hugetlb_folio
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8148809c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_misplaced
  - mm/mempolicy.c:policy_nodemask
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/kfence/core.c (ffffffff8149410f)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_late
  - mm/kfence/core.c:kfence_init_late
```
```
In mm/memory-tiers.c (ffffffff8391e5bd)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:next_demotion_node
```
```
In mm/khugepaged.c (ffffffff814abbaf)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff8391efa0)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1d5c)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff815073b8)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8159afcf)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff815b5680)
Location: include/linux/nodemask.h:264
Inline: True
```
```
In lib/group_cpus.c (ffffffff8192dd52)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/acpi/numa/hmat.c (ffffffff8393f668)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/xen/balloon.c (ffffffff83943a1f)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff81af749d)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/iommu/intel/iommu.c (ffffffff8394e87f)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff839518cc)
Location: include/linux/nodemask.h:264
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
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
In arch/arm64/kernel/setup.c (ffff800011433e14)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:topology_init
```
```
In arch/arm64/mm/numa.c (ffff800011438eac)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_init
```
```
In kernel/workqueue.c (ffff800011442f5c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
```
```
In kernel/sched/fair.c (ffff80001014d7f4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffff80001015cb40)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/irq/irqdesc.c (ffff800011446598)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffff800010187b60)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffff8000102b7f3c)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (ffff8000114531a8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffff8000102d93c0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffff800011453460)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffff800011455e30)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffff8000102eeec4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffff80001030bf6c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffff800011457d30)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffff800011458f90)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffff80001033041c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffff80001033c158)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffff80001034b4bc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffff80001145bc6c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffff8000103a96d8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffff800010438408)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffff80001044da14)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffff80001077ba7c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffff800011491850)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffff800010863b40)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffff8000108affc8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/base/node.c (ffff80001090f010)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffff800010d8d0c8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (c0e875fc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/powerpc/mm/numa.c (c0000000000a31f8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:find_and_online_cpu_nid
  - arch/powerpc/mm/numa.c:find_and_online_cpu_nid
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:initmem_init
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:numa_setup_cpu
  - arch/powerpc/mm/numa.c:dump_numa_cpu_topology
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfaa0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
```
```
In arch/powerpc/platforms/powernv/memtrace.c (c0000000000e09e8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012d57c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
```
```
In kernel/workqueue.c (c000000000164f00)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (c0000000001a0758)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (c0000000001b14a0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/irq/irqdesc.c (c00000000136b3b0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (c0000000001e17e0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (c00000000036ff48)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (c00000000137b4d0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (c000000000398fcc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (c00000000137b860)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (c00000000137ed4c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (c0000000003b3568)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (c0000000003dbf94)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (c0000000013814a4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (c000000001382938)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (c00000000040910c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (c000000000417418)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (c00000000042aa50)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (c0000000013866fc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (c0000000004a41b8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (c00000000054aafc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (c000000000565180)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/tty/sysrq.c (c000000000902d30)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (c000000000949884)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/base/node.c (c0000000009afc30)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (c000000000ecf2e0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffe0008b5e10)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff8289afd1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b617)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bfee)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/init_64.c (ffffffff828ada3b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828af276)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828af800)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810b9d9e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810e72aa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810f193a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff81104f91)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff828b78f8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff81119e5b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff812224ff)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (ffffffff828c3492)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8123e2e5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff828c36f1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828c61ac)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8124fa7d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8126e19b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828c7def)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff828c8c63)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff8128b151)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff81295836)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff812a1fa5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828cb87d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffffffff812f2bf2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81366e24)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81378368)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815dfb80)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828e707a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff8165676d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81684ece)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828ee701)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816e1961)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvme/host/multipath.c (ffffffff817498bd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
```
```
In drivers/nvme/host/pci.c (ffffffff8174e420)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In lib/nodemask.c (ffffffff81a51cad)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff8289328f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103aa74)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b1ee)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/init_64.c (ffffffff828a5cd9)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828a7468)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a79f2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810a86de)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810d644a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810e19aa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810f6231)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff828afb78)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff8110aecb)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff812156af)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (ffffffff828bbbb7)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff812312e5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff828bbe16)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828be8d1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81242a1d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8126014b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828c0514)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff828c1388)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff8127cf81)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff81287446)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff81293a85)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828c3fa2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffffffff812e3822)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81357ac4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81368e38)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815cb1c0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/tty/sysrq.c (ffffffff81636afd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff81662b6e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e5b98)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816bbfa1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b4ad)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
```
```
In drivers/nvme/host/pci.c (ffffffff8172e2c0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
```
```
In lib/nodemask.c (ffffffff81a0edad)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff828adfb1)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b457)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104be2e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/init_64.c (ffffffff828c093a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828c2175)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c26ff)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810b92fe)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810e367a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810eea6a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff81103241)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff828ca834)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff81117d4b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff8122029f)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (ffffffff828d6212)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8123c085)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff828d6471)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828d8f2c)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8124d81d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8126bf3b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828dab6f)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff828db9e3)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff81288f61)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff81293646)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff8129fdb5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828de5fd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffffffff812f0a02)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff813648f4)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81375e38)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815e51d0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828fab57)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff81684b2d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff816b32be)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82902247)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff8170ee91)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81abe09d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
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
In arch/x86/kernel/topology.c (ffffffff828adfcf)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c867)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d23e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be1fc)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/mm/init_64.c (ffffffff828c3a85)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828c52c0)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c584a)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca3ec)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/workqueue.c (ffffffff810c1e18)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/sched/fair.c (ffffffff810ef269)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
```
```
In kernel/sched/topology.c (ffffffff810f9aaa)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff8110e631)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/irqdesc.c (ffffffff828cfc2d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:early_irq_init
```
```
In kernel/irq/affinity.c (ffffffff811233db)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff8122f3bf)
Location: include/linux/nodemask.h:263
Inline: True
```
```
In mm/vmscan.c (ffffffff828db633)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8124b7e5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mmzone.c:first_online_pgdat
```
```
In mm/vmstat.c (ffffffff828db892)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828de34d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8125d4dd)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8127ba7b)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828dff90)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:early_pfn_to_nid
```
```
In mm/swapfile.c (ffffffff828e0e04)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
```
```
In mm/hugetlb.c (ffffffff81298ced)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
```
```
In mm/mempolicy.c (ffffffff812a34a6)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_rebind_preferred
  - mm/mempolicy.c:mpol_rebind_preferred
```
```
In mm/slub.c (ffffffff812afef5)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828e3a14)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
```
In fs/dcache.c (ffffffff81301bc2)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81378314)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813898e8)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815ff080)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff82900888)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/tty/sysrq.c (ffffffff8169f13d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:moom_callback
```
```
In drivers/char/random.c (ffffffff816cd83e)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82907f86)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff81729c51)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81aca53d)
Location: include/linux/nodemask.h:263
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
</details>
</li>
</ul>

## Differences
