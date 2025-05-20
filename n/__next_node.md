# Function: <code>__next_node</code>

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
In arch/x86/kernel/topology.c (ffffffff81f68ca0)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff81f77c79)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81f78429)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_set_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f79332)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810979b0)
Location: include/linux/nodemask.h:257
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
In kernel/sched/core.c (ffffffff81f7dcd4)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810b3d9d)
Location: include/linux/nodemask.h:257
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
In kernel/power/snapshot.c (ffffffff810d1f00)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:snapshot_write_next
```
```
In kernel/cpuset.c (ffffffff8111b2c6)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_spread_node
```
```
In mm/oom_kill.c (ffffffff81191176)
Location: include/linux/nodemask.h:257
Inline: True
```
```
In mm/page_alloc.c (ffffffff81191ff2)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/vmscan.c (ffffffff811a0cda)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:kswapd_init
```
```
In mm/mmzone.c (ffffffff811ac336)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/compaction.c (ffffffff811b8309)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811b945b)
Location: include/linux/nodemask.h:257
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
In mm/vmalloc.c (ffffffff811cd6f4)
Location: include/linux/nodemask.h:257
Inline: True
```
```
In mm/hugetlb.c (ffffffff811d9b06)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/hugetlb.c:next_node_allowed
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_show_meminfo
```
```
In mm/mempolicy.c (ffffffff811dfc26)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff811edc44)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff811f97b4)
Location: include/linux/nodemask.h:257
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
In mm/page_isolation.c (ffffffff812040de)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - mm/page_isolation.c:alloc_migrate_target
```
```
In fs/dcache.c (ffffffff81223f73)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff81242c3a)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff81277cef)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81286d21)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8148b208)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff81fa47da)
Location: include/linux/nodemask.h:257
Inline: True
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fab70d)
Location: include/linux/nodemask.h:257
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff8156025d)
Location: include/linux/nodemask.h:257
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
In arch/x86/kernel/topology.c (ffffffff81f90bb0)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff81fa03bf)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81fa1597)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_set_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa1a82)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff81fa5133)
Location: include/linux/nodemask.h:259
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
In kernel/sched/core.c (ffffffff81fa6b83)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c27d7)
Location: include/linux/nodemask.h:259
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
In kernel/power/snapshot.c (ffffffff810d715a)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In mm/oom_kill.c (ffffffff811a5ad2)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fb0eef)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff81fb1d69)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811c50e6)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/compaction.c (ffffffff81fb43ba)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811d375b)
Location: include/linux/nodemask.h:259
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
In mm/vmalloc.c (ffffffff811ea7bf)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In mm/hugetlb.c (ffffffff811f98ac)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
```
```
In mm/mempolicy.c (ffffffff81fb60ec)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff8120d0f4)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff81fb7d5d)
Location: include/linux/nodemask.h:259
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
In fs/dcache.c (ffffffff8124c6e5)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff8126af43)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff812a404f)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff812b3efa)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In lib/nodemask.c (ffffffff81433eb1)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/acpi/numa.c (ffffffff814da03c)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff81fd0d57)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In drivers/char/random.c (ffffffff81567e08)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff81fd82d3)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff815b491d)
Location: include/linux/nodemask.h:259
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
In arch/x86/kernel/topology.c (ffffffff81fcbf4e)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff81fdb929)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81fdcaff)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fdd063)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff8109fe6a)
Location: include/linux/nodemask.h:259
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
In kernel/sched/core.c (ffffffff81fe2702)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c885c)
Location: include/linux/nodemask.h:259
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
In kernel/power/snapshot.c (ffffffff810ddce1)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff810ef9fe)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/oom_kill.c (ffffffff811b5ee0)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In mm/page_alloc.c (ffffffff81fed78f)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811c6de8)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811d51f6)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff81fee8e8)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
```
```
In mm/compaction.c (ffffffff81ff0db5)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811e360d)
Location: include/linux/nodemask.h:259
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
In mm/vmalloc.c (ffffffff811fb22e)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120a1b6)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
```
```
In mm/mempolicy.c (ffffffff81ff2a7d)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff8121f154)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff812307a8)
Location: include/linux/nodemask.h:259
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
In fs/dcache.c (ffffffff8125f6ca)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff8127e07c)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff812b9b0c)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812c978e)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In lib/nodemask.c (ffffffff81450131)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/acpi/numa.c (ffffffff814fc901)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff8200e6cf)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In drivers/char/random.c (ffffffff8159453a)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff8201602a)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff815e3bc2)
Location: include/linux/nodemask.h:259
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
In arch/x86/kernel/topology.c (ffffffff820ac66b)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff820bc902)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff820bdacb)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff820bdfc5)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff8109d6a0)
Location: include/linux/nodemask.h:259
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
In kernel/sched/fair.c (ffffffff810c2a8b)
Location: include/linux/nodemask.h:259
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
In kernel/sched/topology.c (ffffffff810cbe53)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810dce2e)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff810ef975)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/oom_kill.c (ffffffff811bd9df)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In mm/page_alloc.c (ffffffff820cf3f7)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811cf587)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811de056)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff820d097b)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff820d31e4)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff811edb26)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff81205f7d)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In mm/hugetlb.c (ffffffff812156ba)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
```
```
In mm/mempolicy.c (ffffffff820d50d7)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff8122b6d8)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
```
In mm/memcontrol.c (ffffffff8123bff3)
Location: include/linux/nodemask.h:259
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
In fs/dcache.c (ffffffff8126cf21)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/buffer.c (ffffffff8128bc00)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/buffer.c:free_more_memory
```
```
In fs/proc/task_mmu.c (ffffffff812c6d7f)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812d67de)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8150cc94)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff820f0170)
Location: include/linux/nodemask.h:259
Inline: True
```
```
In drivers/char/random.c (ffffffff815a84a2)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff820f7d04)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff815f888a)
Location: include/linux/nodemask.h:259
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff818efee1)
Location: include/linux/nodemask.h:259
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
In arch/x86/kernel/topology.c (ffffffff826b2e8d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff826c334f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff826c4902)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff826c4dff)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810a3d40)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810ca27b)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810d4656)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810e5059)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff810f855c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/oom_kill.c (ffffffff811d25fc)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/page_alloc.c (ffffffff826d7e17)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff811e4937)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff811f3ad6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff826d93b2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff826dbc09)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81203f86)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8121ec9d)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/swapfile.c (ffffffff826dce8a)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff8123027d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
```
```
In mm/mempolicy.c (ffffffff826ddc9d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff81246de5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
```
In mm/memcontrol.c (ffffffff8125b853)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff8128f2c1)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff812ea8ff)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812fb02e)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8154fbfb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff826f9965)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In drivers/char/random.c (ffffffff8160edb2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/iommu/intel-iommu.c (ffffffff827013ec)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816608ca)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81976331)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff826dc6ab)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff826ed5c7)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff826eec07)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff826ef153)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff826f3cd8)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810d223b)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810dc236)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810eccf8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff811007d6)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f37a5)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/page_alloc.c (ffffffff827022fa)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff827035d5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81214e05)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff82703888)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff827060ff)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81224b56)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8124096b)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/swapfile.c (ffffffff827073fc)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff812536eb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff82708289)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff81268201)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff8270a09a)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff812b6865)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81317df6)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8132861b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815864b9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff82723d4c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff8164852f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff8272b171)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff8169c0ab)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff819d2af0)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff82892a87)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff828a4159)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828a58f5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a5e41)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff828aaac0)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810dbbab)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810e5e70)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810f8398)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff8110bf91)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/oom_kill.c (ffffffff8120574d)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/page_alloc.c (ffffffff828b9a1b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmscan.c (ffffffff828bacfe)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81227ce5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff828bafb1)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828bd8a4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81237ac6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8125525b)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/swapfile.c (ffffffff828be7ce)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff8126762b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff828bf65b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff8127dd20)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828c1227)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff812cbbe0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8132ebd6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff8133f870)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff8159e7c9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828dbf31)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff816669fa)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e39ff)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816bca4b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81a0c170)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff828a9fcf)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff828bc5ef)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828bdec3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828be40e)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff828c329c)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810e2b25)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810ecad5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff81100957)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff811156d0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff8121c515)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (ffffffff828d2188)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81237a25)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff828d2413)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828d4e9c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81249042)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8126730a)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/page_alloc.c (ffffffff828d6b07)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff828d798b)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff81283086)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff828d8857)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff81299b6f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828da5a8)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff812e8a98)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81356644)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81367b62)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815cfcc9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828f682a)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff8169c765)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828fdf30)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816f727b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81a7bad0)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff828ad032)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd2b7)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/mm/init_64.c (ffffffff828c2a96)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828c431d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c4872)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c93d8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/workqueue.c (ffffffff810bfab5)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810ed1d5)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810f8575)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff8110cdb7)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff811218d0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff81229ee5)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (ffffffff828da606)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81245cd5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff828da885)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828dd32b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81257492)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff81275b79)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828def98)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff828dfdfc)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff81292ba6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff828e0ceb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff812a9a2f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828e2a4f)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff812fa638)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8136e873)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff8137fde2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815f0f39)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828ff881)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff816bf4d5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82906f98)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff8171b69b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81ab2e30)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff82cd23df)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce181d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff82ce5eb3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff82ce6edc)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff82ce7be0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff82cebe7b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/workqueue.c (ffffffff82ced852)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810f70e9)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff811025a8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81117f29)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff8112e3c4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In mm/oom_kill.c (ffffffff8125584d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff82cf8998)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81273acd)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff82cf8cba)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff82cfa7b0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81285a46)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812a6ea9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff82cfc381)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff82cfd24a)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff812c5eed)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff82cfe3e6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff812de602)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
```
```
In mm/memcontrol.c (ffffffff82cffb2f)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff813336d7)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff8138a0c8)
Location: include/linux/nodemask.h:269
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
In fs/proc/task_mmu.c (ffffffff813b64a5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813ca27a)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In lib/nodemask.c (ffffffff815ed6d0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff82d16bb9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff817737cd)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff82d1d94c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff817d775b)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff82fbe226)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce5ca)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff82fd3834)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff82fd5249)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff82fd55d7)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff82fd9eac)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810f5309)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff811011c8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81114369)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff81129fb4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In mm/oom_kill.c (ffffffff812604cd)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff82fe5691)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8127e33d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff82fe5992)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff82fe74ac)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8128fd06)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812b46f9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff82fe8d9c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff82fe9c7b)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff812d3173)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:allowed_mems_nr
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff82feadd9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff812ea1a2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
```
```
In mm/memcontrol.c (ffffffff82fec4f4)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff8133f047)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff8139b050)
Location: include/linux/nodemask.h:269
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
In fs/proc/task_mmu.c (ffffffff813c7a25)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813dbf3a)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In lib/nodemask.c (ffffffff81611e00)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff8300482c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff8178e78d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff8300b668)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff817ec1bc)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int __next_node(int n, const nodemask_t *srcp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/topology.c (ffffffff831c892f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc98db)
Location: include/linux/nodemask.h:269
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff831de45b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff81bcc258)
Location: include/linux/nodemask.h:269
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff831e007d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810c3b70)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/sched/fair.c (ffffffff810f73dc)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff811034f3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81114bab)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff81129f6c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In mm/oom_kill.c (ffffffff812651c5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff831efd61)
Location: include/linux/nodemask.h:269
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
In mm/mmzone.c (ffffffff8128349d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff831eff92)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff81290211)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
Direct callers:
  - mm/compaction.c:kcompactd_init
```
```
In mm/list_lru.c (ffffffff81295461)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812ba890)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff812bf4b9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
Direct callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff812cda82)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
Direct callers:
  - mm/swapfile.c:swapfile_init
```
```
In mm/hugetlb.c (ffffffff812d9eb2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff812deeaf)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffffffff812f2003)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
Direct callers:
  - mm/slub.c:kmem_cache_init
```
```
In mm/memcontrol.c (ffffffff81308193)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_lruvec_page_state
  - mm/memcontrol.c:__invalidate_reclaim_iterators
Direct callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In fs/dcache.c (ffffffff813454af)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813a22d6)
Location: include/linux/nodemask.h:269
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
In fs/proc/task_mmu.c (ffffffff813ced6b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813e2ed4)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In lib/nodemask.c (ffffffff815f54e0)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In drivers/xen/balloon.c (ffffffff8320f2d3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff81770ff3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff83215ffc)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff817d0eaa)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff81bc98db-ffffffff81bc990a: __next_node.constprop.0 (STB_LOCAL)
ffffffff81bcc258-ffffffff81bcc286: __next_node (STB_LOCAL)
ffffffff81bcdf3d-ffffffff81bcdf6c: __next_node.constprop.0 (STB_LOCAL)
ffffffff81290180-ffffffff812901ae: __next_node (STB_LOCAL)
ffffffff812be9d0-ffffffff812be9fe: __next_node (STB_LOCAL)
ffffffff812ccb10-ffffffff812ccb3f: __next_node.constprop.0 (STB_LOCAL)
ffffffff812dea70-ffffffff812dea9e: __next_node (STB_LOCAL)
ffffffff81bdb161-ffffffff81bdb18f: __next_node (STB_LOCAL)
ffffffff81306f90-ffffffff81306fbe: __next_node (STB_LOCAL)
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
In arch/x86/kernel/topology.c (ffffffff832a9b6d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc51e)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff832c16e9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff832c32aa)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c36c6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff832c859b)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff8111194c)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff81120328)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
```
```
In kernel/power/snapshot.c (ffffffff81134d18)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff8114a8cc)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In mm/oom_kill.c (ffffffff812a19f2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff832d54d7)
Location: include/linux/nodemask.h:269
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
In mm/mmzone.c (ffffffff812c169d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff832d5724)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff832d7773)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff812d59a1)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff812fce90)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff832d9832)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff832da8d4)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff81320ab0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff832dbddb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff8133afb9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff8133e301)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff832dd8d1)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff813930bf)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/io-wq.c (ffffffff813f33f7)
Location: include/linux/nodemask.h:269
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
In fs/proc/task_mmu.c (ffffffff81420119)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff814349e4)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In lib/nodemask.c (ffffffff81662950)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff832f822b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff817f6b46)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff832ff805)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff8185b84a)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346de4e)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff83473d7c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff83475b33)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff83475f5b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff8347b69c)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff8112dbcd)
Location: include/linux/nodemask.h:269
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
In kernel/sched/build_utility.c (ffffffff8114a975)
Location: include/linux/nodemask.h:269
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
In kernel/power/snapshot.c (ffffffff81156fb5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff8116ff02)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In mm/oom_kill.c (ffffffff812f98da)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83489d08)
Location: include/linux/nodemask.h:269
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
In mm/mmzone.c (ffffffff8131e73f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff83489f7d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff8348c304)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff81335336)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff81360874)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff8348e7d9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff8348fa22)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff8138d78d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8349158c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff813ad33e)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff813b11c3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
```
```
In mm/memcontrol.c (ffffffff83493102)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb_cgroup.c (ffffffff813d7447)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff814147df)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81498084)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff814aeb3b)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In io_uring/io-wq.c (ffffffff816dbf77)
Location: include/linux/nodemask.h:269
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
In lib/nodemask.c (ffffffff8177c7d0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
```
In drivers/xen/balloon.c (ffffffff834b094a)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff834b8596)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff834baadc)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108344b)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093ba7)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93b71)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff83e9b9ba)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff83e9e8dd)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff83e9ec90)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff83ea6502)
Location: include/linux/nodemask.h:270
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
In kernel/sched/fair.c (ffffffff811579cd)
Location: include/linux/nodemask.h:270
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
In kernel/sched/build_utility.c (ffffffff811792f1)
Location: include/linux/nodemask.h:270
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
In kernel/power/snapshot.c (ffffffff81187ce8)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff811a6362)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ecc7)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In mm/oom_kill.c (ffffffff813634a2)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83eba5d9)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
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
In mm/mmzone.c (ffffffff81392237)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff83eba877)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff83ebd5f8)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
```
```
In mm/list_lru.c (ffffffff813abff3)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff813dbd84)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff83ec0a1c)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff83ec21c7)
Location: include/linux/nodemask.h:270
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
In mm/hugetlb.c (ffffffff83ec3a68)
Location: include/linux/nodemask.h:270
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
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff83ec4985)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff8142db2c)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/memory-tiers.c (ffffffff83ec69af)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff81447e76)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff83ec705d)
Location: include/linux/nodemask.h:270
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
In mm/hugetlb_cgroup.c (ffffffff8145c76e)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff8149fcbf)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8152bdfd)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff815451d1)
Location: include/linux/nodemask.h:270
Inline: True
```
```
In io_uring/io-wq.c (ffffffff817a8087)
Location: include/linux/nodemask.h:270
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
In drivers/xen/balloon.c (ffffffff83eea705)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff83ef52df)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff83ef836f)
Location: include/linux/nodemask.h:270
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810858fb)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096b37)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b77c0)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff836bf45a)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff836c2a3d)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff836c2e04)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff836cacc2)
Location: include/linux/nodemask.h:270
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
In kernel/sched/fair.c (ffffffff81167a1d)
Location: include/linux/nodemask.h:270
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
In kernel/sched/build_utility.c (ffffffff81189ee2)
Location: include/linux/nodemask.h:270
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
In kernel/power/snapshot.c (ffffffff81198e78)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/cgroup/cpuset.c (ffffffff81234dbd)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In mm/oom_kill.c (ffffffff813958f2)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff836dfbe9)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
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
In mm/mmzone.c (ffffffff813c4c37)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff836dfe87)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff836e2ff4)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/compaction.c (ffffffff836e5aa8)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
```
```
In mm/show_mem.c (ffffffff813de7c4)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/show_mem.c:__show_free_areas
```
```
In mm/list_lru.c (ffffffff813e0393)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff81410624)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff81422ab7)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/swapfile.c (ffffffff836e77b7)
Location: include/linux/nodemask.h:270
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
In mm/hugetlb.c (ffffffff836e8b48)
Location: include/linux/nodemask.h:270
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
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff836e9aa5)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff814631bc)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/memory-tiers.c (ffffffff836eb99f)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff8147d826)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff836ec044)
Location: include/linux/nodemask.h:270
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
In mm/hugetlb_cgroup.c (ffffffff814923d9)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff814d4fdf)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8156416e)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff8157cdb1)
Location: include/linux/nodemask.h:270
Inline: True
```
```
In lib/group_cpus.c (ffffffff818e6d95)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/xen/balloon.c (ffffffff837100f6)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff8371af23)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff8371df0f)
Location: include/linux/nodemask.h:270
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c8dd)
Location: include/linux/nodemask.h:270
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e0a7)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e8108)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/mm/init_64.c (ffffffff838efefa)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff838f345d)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff838f39f4)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/sched/fair.c (ffffffff8117481d)
Location: include/linux/nodemask.h:270
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
In kernel/sched/build_utility.c (ffffffff811987e2)
Location: include/linux/nodemask.h:270
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
In kernel/power/snapshot.c (ffffffff811a7e04)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e9dd)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In mm/oom_kill.c (ffffffff813bf6b2)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
```
```
In mm/vmscan.c (ffffffff83912469)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
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
In mm/shrinker.c (ffffffff813e4c6c)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
  - mm/shrinker.c:free_shrinker_info
```
```
In mm/mmzone.c (ffffffff813ef657)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mmzone.c:next_zone
```
```
In mm/vmstat.c (ffffffff83912737)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/mm_init.c (ffffffff83915884)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/compaction.c (ffffffff839182d8)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
```
```
In mm/show_mem.c (ffffffff814085b4)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/show_mem.c:show_free_areas
```
```
In mm/list_lru.c (ffffffff8140a6f3)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
```
```
In mm/vmalloc.c (ffffffff8143cf84)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/vmalloc.c:show_numa_info
```
```
In mm/page_alloc.c (ffffffff8144f8a7)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/slub.c (ffffffff8145f40c)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
```
In mm/swapfile.c (ffffffff8391a847)
Location: include/linux/nodemask.h:270
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
In mm/zswap.c (ffffffff8146f1fc)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/zswap.c:shrink_memcg
```
```
In mm/hugetlb.c (ffffffff8391c0d8)
Location: include/linux/nodemask.h:270
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
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8391ce65)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/memory-tiers.c (ffffffff8391e5d0)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff814abbf6)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In mm/memcontrol.c (ffffffff8391f04e)
Location: include/linux/nodemask.h:270
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
In mm/hugetlb_cgroup.c (ffffffff814c1de9)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
```
```
In fs/dcache.c (ffffffff815073df)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff8159afe2)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff815b56d1)
Location: include/linux/nodemask.h:270
Inline: True
```
```
In lib/group_cpus.c (ffffffff8192ddb5)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
```
```
In drivers/acpi/numa/hmat.c (ffffffff8393f6d4)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_init
```
```
In drivers/xen/balloon.c (ffffffff83943a6b)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/iommu/intel/iommu.c (ffffffff8394ea03)
Location: include/linux/nodemask.h:270
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
```
```
In drivers/base/node.c (ffffffff839518df)
Location: include/linux/nodemask.h:270
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
In arch/arm64/kernel/setup.c (ffff800011433e88)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:topology_init
```
```
In arch/arm64/mm/numa.c (ffff800011438fb8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_init
```
```
In kernel/workqueue.c (ffff800011442fa4)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffff80001014d878)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffff80001015cb98)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/irq/affinity.c (ffff800010187b80)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffff8000102b7f94)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (ffff8000114531d0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffff8000102d9410)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffff8000114534d8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffff800011455e68)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffff8000102eef28)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffff80001030bfa8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffff800011457d80)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffff800011458fe4)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffff800010330444)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffff800011459fb8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (ffff80001034b534)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffff80001145bcfc)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffff8000103a96f0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffff800010438440)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffff80001044da60)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffff80001077bacc)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffff8000114918a8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffff8000108b000c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/base/node.c (ffff80001090f098)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffff800010d8d090)
Location: include/linux/nodemask.h:269
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
In lib/nodemask.c (c0e875e0)
Location: include/linux/nodemask.h:269
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
In arch/powerpc/mm/numa.c (c000000001357b60)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:initmem_init
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:dump_numa_cpu_topology
```
```
In arch/powerpc/platforms/powernv/opal-imc.c (c0000000000dfb04)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-imc.c:disable_nest_pmu_counters
```
```
In arch/powerpc/platforms/powernv/memtrace.c (c0000000000e0ba0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012d610)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
```
```
In kernel/workqueue.c (c000000000164fd0)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (c0000000001a0830)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (c0000000001b1514)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/irq/affinity.c (c0000000001e189c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (c00000000036ffa8)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (c00000000137b508)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (c00000000039903c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (c00000000137b908)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (c00000000137ed84)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (c0000000003b35e4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (c0000000003dbfe0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (c000000001381514)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (c000000001382990)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (c00000000040917c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (c000000001383cb4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/slub.c (c00000000042ab28)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (c0000000013867a4)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (c0000000004a41e8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (c00000000054ab50)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (c0000000005651f0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/char/random.c (c00000000094990c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/base/node.c (c0000000009afcf8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (c000000000ecf298)
Location: include/linux/nodemask.h:269
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
In lib/nodemask.c (ffffffe0008b5de4)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff8289b044)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff828ada6c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828af2f3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828af848)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810b9e25)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810e7335)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810f1975)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff81104fd7)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff81119eb0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff81222535)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (ffffffff828c34ba)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8123e325)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff828c3739)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828c61df)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8124fae2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8126e1c9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828c7e4c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff828c8cb0)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff8128b186)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff828c9b9f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff812a200f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828cb903)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff812f2c18)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81366e53)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff813783c2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815dfbc9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828e70c7)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff81684f25)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828ee775)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816e19cb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvme/host/multipath.c (ffffffff817498db)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
```
```
In lib/nodemask.c (ffffffff81a51c80)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff82893302)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff828a5d0a)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828a74e5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a7a3a)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810a8765)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810d64d5)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810e19e5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff810f6277)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff8110af20)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff812156e5)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (ffffffff828bbbdf)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff81231325)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff828bbe5e)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828be904)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff81242a82)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff81260179)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828c0571)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff828c13d5)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff8127cfb6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff828c22c4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff81293aef)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828c4028)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff812e3848)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81357af3)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81368e92)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815cb209)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/char/random.c (ffffffff81662bc5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff828e5c0c)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff816bc00b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In drivers/nvme/host/multipath.c (ffffffff8172b4cb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_mpath_set_live
  - drivers/nvme/host/multipath.c:nvme_mpath_clear_current_path
```
```
In lib/nodemask.c (ffffffff81a0ed80)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff828ae024)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/mm/init_64.c (ffffffff828c096b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828c21f2)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c2747)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810b9385)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810e3705)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810eeaa5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff81103287)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff81117da0)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff812202d5)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (ffffffff828d623a)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8123c0c5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff828d64b9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828d8f5f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8124d882)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8126bf69)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828dabcc)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff828dba30)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff81288f96)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff828dc91f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff8129fe1f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828de683)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff812f0a28)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81364923)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81375e92)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815e5219)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff828faba4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff816b3315)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff829022bb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff8170eefb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81abe070)
Location: include/linux/nodemask.h:269
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
In arch/x86/kernel/topology.c (ffffffff828ae042)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be2e4)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
```
In arch/x86/mm/init_64.c (ffffffff828c3ab6)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:mem_init
```
```
In arch/x86/mm/numa.c (ffffffff828c533d)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c5892)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca415)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
```
In kernel/workqueue.c (ffffffff810c1e9a)
Location: include/linux/nodemask.h:269
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
In kernel/sched/fair.c (ffffffff810ef2ed)
Location: include/linux/nodemask.h:269
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
In kernel/sched/topology.c (ffffffff810f9ae5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/power/snapshot.c (ffffffff8110e677)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
```
```
In kernel/irq/affinity.c (ffffffff81123430)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/oom_kill.c (ffffffff8122f3f5)
Location: include/linux/nodemask.h:269
Inline: True
```
```
In mm/vmscan.c (ffffffff828db65b)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:drop_slab
```
```
In mm/mmzone.c (ffffffff8124b825)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mmzone.c:next_online_pgdat
```
```
In mm/vmstat.c (ffffffff828db8da)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/compaction.c (ffffffff828de380)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
```
```
In mm/list_lru.c (ffffffff8125d542)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
```
```
In mm/vmalloc.c (ffffffff8127baa9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/vmalloc.c:s_show
```
```
In mm/page_alloc.c (ffffffff828dffed)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:page_alloc_init_late
```
```
In mm/swapfile.c (ffffffff828e0e51)
Location: include/linux/nodemask.h:269
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
In mm/hugetlb.c (ffffffff81298d21)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/mempolicy.c (ffffffff828e1d36)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/slub.c (ffffffff812aff5f)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
```
In mm/memcontrol.c (ffffffff828e3a9a)
Location: include/linux/nodemask.h:269
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
In fs/dcache.c (ffffffff81301be8)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
```
```
In fs/proc/task_mmu.c (ffffffff81378343)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_numa_map
```
```
In fs/proc/kcore.c (ffffffff81389942)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
```
```
In drivers/acpi/numa.c (ffffffff815ff0c9)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/xen/balloon.c (ffffffff829008d5)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
```
```
In drivers/char/random.c (ffffffff816cd895)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
```
```
In drivers/iommu/intel-iommu.c (ffffffff82907ffa)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
```
In drivers/base/node.c (ffffffff81729cbb)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_distance
```
```
In lib/nodemask.c (ffffffff81aca510)
Location: include/linux/nodemask.h:269
Inline: True
Inline callers:
  - lib/nodemask.c:__next_node_in
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
