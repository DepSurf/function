# Function: <code>_find_next_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/find_bit.c (ffffffff813fdf60)
Location: lib/find_bit.c:31
Inline: True
```
**Symbols:**

```
ffffffff813fdf60-ffffffff813fdfcd: _find_next_bit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/find_bit.c (ffffffff814455c0)
Location: lib/find_bit.c:31
Inline: True
```
**Symbols:**

```
ffffffff814455c0-ffffffff8144562d: _find_next_bit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/find_bit.c (ffffffff81463db0)
Location: lib/find_bit.c:31
Inline: True
```
**Symbols:**

```
ffffffff81463db0-ffffffff81463e1d: _find_next_bit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start, long unsigned int invert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81468e50)
Location: lib/find_bit.c:31
Inline: False
Direct callers:
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
**Symbols:**

```
ffffffff81468e50-ffffffff81468ebd: _find_next_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start, long unsigned int invert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81495110)
Location: lib/find_bit.c:31
Inline: False
Direct callers:
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
**Symbols:**

```
ffffffff81495110-ffffffff81495181: _find_next_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814ca390)
Location: lib/find_bit.c:34
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff814df0b0)
Location: lib/find_bit.c:34
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8150afe0)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81528e00)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/find_bit.c (ffffffff8158c720)
Location: lib/find_bit.c:30
Inline: True
Direct callers:
  - lib/find_bit.c:find_next_clump8
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
```
**Symbols:**

```
ffffffff8158c720-ffffffff8158c793: _find_next_bit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/find_bit.c (ffffffff815a9190)
Location: lib/find_bit.c:32
Inline: True
Direct callers:
  - lib/find_bit.c:find_next_clump8
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
```
**Symbols:**

```
ffffffff815a9190-ffffffff815a9203: _find_next_bit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start, long unsigned int invert, long unsigned int le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815b3d80)
Location: lib/find_bit.c:32
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/numa.c:__next_node
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
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
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/slub.c:kmem_cache_open
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_flush_lruvec_page_state
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/io-wq.c:io_wq_cpu_online
  - fs/io-wq.c:io_wq_put_and_exit
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_exit_workers
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/io-wq.c:io_wq_cancel_cb
  - fs/proc/task_mmu.c:show_numa_map
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_remap
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/find_bit.c:find_next_clump8
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_destroy
  - lib/sbitmap.c:__sbitmap_get_word
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/idr.c:ida_alloc_range
  - lib/xarray.c:xas_store
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/ff-core.c:input_ff_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff815b3d80-ffffffff815b3e0c: _find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start, long unsigned int invert, long unsigned int le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81619f70)
Location: lib/find_bit.c:32
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
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
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/trace/trace.c:trace_pid_write
  - kernel/trace/trace.c:trace_pid_start
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_drain_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/list_lru.c:memcg_update_all_list_lrus
  - mm/vmalloc.c:s_show
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
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
  - fs/proc/task_mmu.c:show_numa_map
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_test_and_clear_bits
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/find_bit.c:find_next_clump8
  - lib/genalloc.c:gen_pool_best_fit
  - lib/genalloc.c:gen_pool_destroy
  - lib/sbitmap.c:__sbitmap_get_word
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/idr.c:ida_alloc_range
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_squash_marks
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:ldma_dev_init
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/char/random.c:do_numa_crng_init
  - drivers/char/random.c:do_numa_crng_init
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/ff-core.c:input_ff_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
```
**Symbols:**

```
ffffffff81619f70-ffffffff8161a005: _find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr1, const long unsigned int *addr2, long unsigned int nbits, long unsigned int start, long unsigned int invert, long unsigned int le);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff816e74c0)
Location: lib/find_bit.c:32
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/apic/apic.c:apic_pending_intr_clear
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
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
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/trace/pid_list.c:trace_pid_list_next
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
  - mm/vmalloc.c:show_numa_info
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/slub.c:init_kmem_cache_nodes
  - mm/slub.c:kmem_cache_init
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__disable_all_migrate_targets
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/file.c:alloc_fd
  - fs/file.c:alloc_fd
  - fs/proc/task_mmu.c:show_numa_map
  - fs/ext4/balloc.c:ext4_valid_block_bitmap
  - fs/ext4/ialloc.c:find_inode_bit
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:mb_free_blocks
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - io_uring/io_uring.c:io_fixed_fd_install
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_cancel_cb
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_ord_to_pos
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/find_bit.c:find_next_clump8
  - lib/genalloc.c:gen_pool_best_fit
  - lib/sbitmap.c:__sbitmap_get_word
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_any_and_distribute
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_local_spread
  - lib/cpumask.c:cpumask_next_wrap
  - lib/cpumask.c:cpumask_any_but
  - lib/idr.c:ida_alloc_range
  - lib/nodemask.c:__next_node_in
  - lib/xarray.c:xas_store
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpiolib.c:gpiod_set_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/balloon.c:balloon_init
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/input/input.c:input_dev_release_keys
  - drivers/input/input.c:input_dev_release_keys
  - drivers/input/ff-core.c:input_ff_create
  - drivers/input/ff-core.c:input_ff_create
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/netlink/genetlink.c:genl_allocate_reserve_groups
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_check_work_pending
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_append_new_local_addr
```
**Symbols:**

```
ffffffff816e74c0-ffffffff816e7583: _find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff817d6ed0)
Location: lib/find_bit.c:131
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/events/intel/uncore_snbep.c:snbep_pci2phy_map_init
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_has_discovery_tables
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_mon
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_die
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:init_x2apic_ldr
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:hw_break_release_slot
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/itmt.c:sched_set_itmt_core_prio
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:softirq_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_assert_empty
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:cpudl_init
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_sched_rt_class
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:__cpuusage_read
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:irq_get_next_irq
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - kernel/irq/affinity.c:irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:alloc_nodes_vectors
  - kernel/irq/affinity.c:irq_spread_init_one
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/module/main.c:post_relocation
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_hld.c:hardlockup_detector_perf_restart
  - kernel/watchdog_hld.c:hardlockup_detector_perf_stop
  - kernel/watchdog_hld.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:ftrace_init_tracefs_toplevel
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:ring_buffer_wake_waiters
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:set_buffer_entries
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/pid_list.c:trace_pid_list_next
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:perf_swevent_init
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:compaction_proactiveness_sysctl_handler
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/rmap.c:try_to_unmap_one
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:mem_init_print_info
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:__show_free_areas
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:page_alloc_init_late
  - mm/page_alloc.c:free_area_init_core_hotplug
  - mm/memory_hotplug.c:try_offline_node
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
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
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:kmem_cache_init
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_page_state_local
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
  - mm/memory-failure.c:memory_failure_init
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_writers
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/apparmor/lsm.c:alloc_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - block/blk-mq-rdma.c:blk_mq_rdma_map_queues
  - io_uring/io-wq.c:io_wq_max_workers
  - io_uring/io-wq.c:io_wq_cpu_affinity
  - io_uring/io-wq.c:__io_wq_cpu_online
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_put_and_exit
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_cancel_cb
  - lib/random32.c:prandom_seed_full_state
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/find_bit.c:find_next_clump8
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/genalloc.c:gen_pool_best_fit
  - lib/percpu_counter.c:__percpu_counter_sum_mask
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_community_irq_handler
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/cppc_acpi.c:cppc_perf_ctrs_in_pcc
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:cppc_allow_fast_switch
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_alloc_device
  - drivers/spi/spi.c:spi_statistics_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_statistics_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_statistics_bytes_tx_show
  - drivers/spi/spi.c:spi_statistics_bytes_rx_show
  - drivers/spi/spi.c:spi_statistics_bytes_show
  - drivers/spi/spi.c:spi_statistics_spi_async_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_statistics_spi_sync_show
  - drivers/spi/spi.c:spi_statistics_timedout_show
  - drivers/spi/spi.c:spi_statistics_errors_show
  - drivers/spi/spi.c:spi_statistics_transfers_show
  - drivers/spi/spi.c:spi_statistics_messages_show
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/input/ff-core.c:input_ff_create
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/amd-pstate.c:cppc_enable
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_no_acpi_pss
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_register
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/devlink.c:devl_trap_groups_register
  - net/core/devlink.c:devlink_trap_stats_read
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_orphan_count_sum
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:trie_show_usage
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/mib.c:mptcp_seq_show
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_next_wrap
  - lib/xarray.c:xas_squash_marks
```
**Symbols:**

```
ffffffff817d6ed0-ffffffff817d6f40: _find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81815f00)
Location: lib/find_bit.c:131
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
  - arch/x86/kernel/topology.c:topology_init
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_update_die_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:hw_break_release_slot
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:mm_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_bringup_mask
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpu_down_maps_locked
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:softirq_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:wq_pool_ids_show
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_assert_empty
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:cpudl_init
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_sched_rt_class
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:membarrier_global_expedited
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sched_debug_start
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:__cpuusage_read
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/module/main.c:post_relocation
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/timer.c:__next_timer_interrupt
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/kexec_file.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:ring_buffer_wake_waiters
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:set_buffer_entries
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/pid_list.c:trace_pid_list_next
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_osnoise.c:timerlat_tracer_stop
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:reparent_shrinker_deferred
  - mm/vmscan.c:alloc_shrinker_info
  - mm/vmscan.c:free_shrinker_info
  - mm/vmscan.c:expand_one_shrinker_info
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:free_area_init_core_hotplug
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/show_mem.c:__show_free_areas
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/workingset.c:count_shadow_nodes
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/memory_hotplug.c:try_offline_node
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
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
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:kmem_cache_init
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/memcontrol.c:memcg_page_state_local
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
  - mm/memory-failure.c:memory_failure_init
  - fs/exec.c:mm_init_cid
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_writers
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/apparmor/lsm.c:alloc_buffers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_parse
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/find_bit.c:find_next_clump8
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/genalloc.c:gen_pool_best_fit
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - lib/group_cpus.c:grp_spread_init_one
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/cppc_acpi.c:cppc_perf_ctrs_in_pcc
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:cppc_allow_fast_switch
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/power/domain.c:genpd_add_device
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/spi/spi.c:spi_emit_pcpu_stats
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/input/ff-core.c:input_ff_create
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/amd-pstate.c:cppc_enable
  - drivers/cpufreq/amd-pstate.c:pstate_enable
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/page_pool.c:page_pool_get_stats
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:__tcp_alloc_md5sig_pool
  - net/ipv4/tcp.c:tcp_orphan_count_sum
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:trie_show_usage
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/devlink/leftover.c:devl_trap_groups_register
  - net/devlink/leftover.c:devlink_trap_stats_read
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/mib.c:mptcp_seq_show
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_next_wrap
  - lib/xarray.c:xas_squash_marks
```
**Symbols:**

```
ffffffff81815f00-ffffffff81815f6d: _find_next_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int _find_next_bit(const long unsigned int *addr, long unsigned int nbits, long unsigned int start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8185b040)
Location: lib/find_bit.c:131
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_starting
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:fixup_ht_bug
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:intel_pmu_cpu_starting
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_update_topdown_event
  - arch/x86/events/intel/core.c:update_saved_topdown_regs
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_event_update_no_drain
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_device_to_die
  - arch/x86/events/intel/uncore_snbep.c:skx_pmu_get_topology
  - arch/x86/xen/enlighten.c:xen_reboot
  - arch/x86/xen/enlighten.c:xen_vcpu_restore
  - arch/x86/xen/time.c:xen_timer_resume
  - arch/x86/xen/suspend.c:xen_arch_suspend
  - arch/x86/xen/suspend.c:xen_arch_resume
  - arch/x86/xen/suspend_hvm.c:xen_hvm_post_suspend
  - arch/x86/xen/enlighten_pv.c:xen_setup_vcpu_info_placement
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/mmu_pv.c:xen_drop_mm_ref
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
  - arch/x86/xen/smp_hvm.c:xen_hvm_smp_prepare_cpus
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/hyperv/irqdomain.c:hv_map_interrupt
  - arch/x86/hyperv/hv_apic.c:__send_ipi_mask
  - arch/x86/hyperv/hv_apic.c:__cpumask_to_vpset
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/irq.c:arch_show_interrupts
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_check
  - arch/x86/kernel/nmi.c:nmi_backtrace_stall_snap
  - arch/x86/kernel/hw_breakpoint.c:within_cpu_entry
  - arch/x86/kernel/tsc.c:calibrate_delay_is_known
  - arch/x86/kernel/tsc.c:tsc_init
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
  - arch/x86/kernel/tsc.c:tsc_restore_sched_clock_state
  - arch/x86/kernel/process.c:speculative_store_bypass_ht_init
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/cacheinfo.c:__cache_amd_cpumap_setup
  - arch/x86/kernel/cpu/aperfmperf.c:disable_freq_invariance_workfn
  - arch/x86/kernel/cpu/proc.c:c_start
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_delete_all
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/core.c:mce_reign
  - arch/x86/kernel/cpu/mce/apei.c:apei_smca_report_x86_error
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rmdir_ctrl
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_cache_qos_cfg
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:cbm_validate
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/mshyperv.c:hv_smp_prepare_cpus
  - arch/x86/kernel/cpu/debugfs.c:cpu_init_debugfs
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:remove_siblinginfo
  - arch/x86/kernel/smpboot.c:native_smp_cpus_done
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:smp_prepare_cpus_common
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:set_cpu_sibling_map
  - arch/x86/kernel/smpboot.c:topology_update_die_map
  - arch/x86/kernel/smpboot.c:topology_phys_to_logical_pkg
  - arch/x86/kernel/tsc_sync.c:tsc_store_and_check_tsc_adjust
  - arch/x86/kernel/tsc_sync.c:tsc_sync_check_timer_fn
  - arch/x86/kernel/setup_percpu.c:setup_per_cpu_areas
  - arch/x86/kernel/apic/apic.c:setup_local_APIC
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/vector.c:print_ICs
  - arch/x86/kernel/apic/vector.c:lapic_assign_system_vectors
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/kgdb.c:kgdb_arch_late
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_set_hw_break
  - arch/x86/kernel/kgdb.c:hw_break_release_slot
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - arch/x86/kernel/kvm.c:__send_ipi_mask
  - arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/init_64.c:mem_init
  - arch/x86/mm/tlb.c:arch_tlbbatch_flush
  - arch/x86/mm/tlb.c:flush_tlb_mm_range
  - arch/x86/mm/cpu_entry_area.c:setup_cpu_entry_areas
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/cpu_entry_area.c:init_cea_offsets
  - arch/x86/mm/mmio-mod.c:leave_uniprocessor
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_alloc_distance
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/amdtopology.c:amd_numa_init
  - arch/x86/mm/pti.c:pti_clone_user_shared
  - arch/x86/platform/uv/uv_time.c:uv_rtc_allocate_timers
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_dump_state
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_wait_cpus
  - kernel/fork.c:mm_init
  - kernel/fork.c:nr_processes
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:cpuhp_smt_disable
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
  - kernel/cpu.c:thaw_secondary_cpus
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/cpu.c:cpuhp_bringup_mask
  - kernel/cpu.c:smp_shutdown_nonboot_cpus
  - kernel/cpu.c:cpuhp_threads_init
  - kernel/softirq.c:softirq_init
  - kernel/sysctl.c:proc_do_large_bitmap
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:init_pod_type
  - kernel/workqueue.c:wq_affn_dfl_set
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:apply_wqattrs_commit
  - kernel/workqueue.c:apply_wqattrs_prepare
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:schedule_on_each_cpu
  - kernel/workqueue.c:workqueue_init_topology
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init_early
  - kernel/smpboot.c:smpboot_register_percpu_thread
  - kernel/smpboot.c:smpboot_destroy_threads
  - kernel/smpboot.c:idle_threads_init
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:task_mm_cid_work
  - kernel/sched/core.c:cpu_local_stat_show
  - kernel/sched/core.c:cpu_cfs_local_stat_show
  - kernel/sched/core.c:cpu_cfs_stat_show
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:sched_core_balance
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:nr_iowait
  - kernel/sched/core.c:nr_context_switches
  - kernel/sched/core.c:nr_running
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:sched_core_assert_empty
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
  - kernel/sched/fair.c:init_sched_fair_class
  - kernel/sched/fair.c:show_numa_stats
  - kernel/sched/fair.c:sched_group_set_idle
  - kernel/sched/fair.c:__sched_group_set_shares
  - kernel/sched/fair.c:unregister_fair_sched_group
  - kernel/sched/fair.c:online_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:free_fair_sched_group
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:update_sg_wakeup_stats
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:find_energy_efficient_cpu
  - kernel/sched/fair.c:compute_energy
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:destroy_cfs_bandwidth
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_find_cpu
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_max
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/fair.c:task_scan_start
  - kernel/sched/build_policy.c:sched_dl_do_global
  - kernel/sched/build_policy.c:sched_dl_global_validate
  - kernel/sched/build_policy.c:init_sched_dl_class
  - kernel/sched/build_policy.c:pull_dl_task
  - kernel/sched/build_policy.c:cpudl_init
  - kernel/sched/build_policy.c:cpudl_find
  - kernel/sched/build_policy.c:sched_rt_handler
  - kernel/sched/build_policy.c:init_sched_rt_class
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
  - kernel/sched/build_policy.c:do_sched_rt_period_timer
  - kernel/sched/build_policy.c:__disable_runtime
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
  - kernel/sched/build_utility.c:psi_cgroup_restart
  - kernel/sched/build_utility.c:collect_percpu_times
  - kernel/sched/build_utility.c:group_init
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_free
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:sched_update_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_overlap_sched_groups
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:sched_is_eas_possible
  - kernel/sched/build_utility.c:sched_is_eas_possible
  - kernel/sched/build_utility.c:cpupri_init
  - kernel/sched/build_utility.c:cpupri_find_fitness
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sugov_stop
  - kernel/sched/build_utility.c:sugov_start
  - kernel/sched/build_utility.c:sugov_update_shared
  - kernel/sched/build_utility.c:cpuacct_stats_show
  - kernel/sched/build_utility.c:cpuacct_all_seq_show
  - kernel/sched/build_utility.c:__cpuacct_percpu_seq_show
  - kernel/sched/build_utility.c:__cpuusage_read
  - kernel/sched/build_utility.c:__sched_clock_work
  - kernel/locking/percpu-rwsem.c:percpu_down_write
  - kernel/locking/percpu-rwsem.c:percpu_is_read_locked
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_read_next
  - kernel/power/snapshot.c:memory_bm_next_pfn
  - kernel/power/energy_model.c:em_dev_register_perf_domain
  - kernel/power/energy_model.c:em_create_pd
  - kernel/irq/irqdesc.c:kstat_irqs_usr
  - kernel/irq/irqdesc.c:alloc_desc
  - kernel/irq/irqdesc.c:per_cpu_count_show
  - kernel/irq/irq_sim.c:irq_sim_handle_irq
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/cpuhotplug.c:irq_needs_fixup
  - kernel/irq/matrix.c:irq_matrix_alloc
  - kernel/irq/matrix.c:irq_matrix_alloc_managed
  - kernel/irq/matrix.c:irq_matrix_remove_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/irq/matrix.c:irq_matrix_reserve_managed
  - kernel/rcu/update.c:rcu_tasks_trace_postgp
  - kernel/rcu/update.c:check_all_holdout_tasks_trace
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:try_check_zero
  - kernel/rcu/srcutree.c:srcu_gp_end
  - kernel/rcu/srcutree.c:cleanup_srcu_struct
  - kernel/rcu/srcutree.c:srcu_readers_active
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_fwd_progress_check
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:rcu_check_boost_fail
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - kernel/rcu/tree.c:rcu_init_one
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/rcu/tree.c:kfree_rcu_scheduler_running
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_rcu_shrink_count
  - kernel/rcu/tree.c:rcu_organize_nocb_kthreads
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_init_transition
  - kernel/livepatch/transition.c:klp_start_transition
  - kernel/livepatch/transition.c:klp_try_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/module/main.c:post_relocation
  - kernel/module/main.c:__is_module_percpu_address
  - kernel/profile.c:profile_discard_flip_buffers
  - kernel/profile.c:profile_flip_buffers
  - kernel/time/timer.c:init_timers
  - kernel/time/timer.c:next_expiry_recalc
  - kernel/time/timer.c:next_expiry_recalc
  - kernel/time/hrtimer.c:clock_was_set
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/clocksource.c:clocksource_verify_choose_cpus
  - kernel/time/timer_list.c:move_iter
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/clockevents.c:clockevents_init_sysfs
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:tick_handle_oneshot_broadcast
  - kernel/time/tick-sched.c:tick_clock_notify
  - kernel/time/tick-sched.c:tick_nohz_init
  - kernel/smp.c:wake_up_all_idle_cpus
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:call_function_init
  - kernel/crash_core.c:crash_prepare_elf64_headers
  - kernel/cgroup/rstat.c:root_cgroup_cputime
  - kernel/cgroup/rstat.c:cgroup_rstat_boot
  - kernel/cgroup/rstat.c:cgroup_rstat_exit
  - kernel/cgroup/rstat.c:cgroup_rstat_init
  - kernel/cgroup/rstat.c:cgroup_rstat_flush_locked
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/stop_machine.c:cpu_stop_init
  - kernel/debug/debug_core.c:kgdb_roundup_cpus
  - kernel/debug/gdbstub.c:gdb_cmd_query
  - kernel/debug/gdbstub.c:gdb_get_regs_helper
  - kernel/debug/kdb/kdb_main.c:kdb_per_cpu
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
  - kernel/debug/kdb/kdb_debugger.c:kdb_stub
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:touch_all_softlockup_watchdogs
  - kernel/watchdog_perf.c:hardlockup_detector_perf_restart
  - kernel/watchdog_perf.c:hardlockup_detector_perf_stop
  - kernel/watchdog_perf.c:hardlockup_detector_perf_cleanup
  - kernel/relay.c:relay_late_setup_files
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_open
  - kernel/taskstats.c:taskstats_init_early
  - kernel/taskstats.c:add_del_listener
  - kernel/taskstats.c:add_del_listener
  - kernel/trace/ftrace.c:clear_ftrace_pids
  - kernel/trace/ftrace.c:ftrace_profile_tracefs
  - kernel/trace/ftrace.c:ftrace_profile_init
  - kernel/trace/ring_buffer.c:trace_rb_cpu_prepare
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_subbuf_order_set
  - kernel/trace/ring_buffer.c:ring_buffer_empty
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset
  - kernel/trace/ring_buffer.c:ring_buffer_reset_online_cpus
  - kernel/trace/ring_buffer.c:ring_buffer_overruns
  - kernel/trace/ring_buffer.c:ring_buffer_entries
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_resize
  - kernel/trace/ring_buffer.c:ring_buffer_free
  - kernel/trace/ring_buffer.c:__ring_buffer_alloc
  - kernel/trace/ring_buffer.c:ring_buffer_wake_waiters
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace.c:tracing_total_entries_read
  - kernel/trace/trace.c:tracing_entries_read
  - kernel/trace/trace.c:resize_buffer_duplicate_size
  - kernel/trace/trace.c:set_buffer_entries
  - kernel/trace/trace.c:tracing_set_cpumask
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:get_total_entries
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:__find_next_entry
  - kernel/trace/trace.c:trace_buffered_event_disable
  - kernel/trace/trace.c:trace_buffered_event_enable
  - kernel/trace/pid_list.c:trace_pid_list_next
  - kernel/trace/trace_hwlat.c:stop_per_cpu_kthreads
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - kernel/trace/trace_osnoise.c:timerlat_tracer_stop
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:osnoise_workload_start
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:start_per_cpu_kthreads
  - kernel/trace/trace_osnoise.c:stop_per_cpu_kthreads
  - kernel/trace/trace_functions_graph.c:graph_trace_open
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/trace_events.c:__ftrace_clear_event_pids
  - kernel/trace/trace_event_perf.c:perf_trace_event_reg
  - kernel/trace/bpf_trace.c:send_signal_irq_work_init
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:kdb_ftdump
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/trace/trace_uprobe.c:uprobe_buffer_init
  - kernel/bpf/core.c:bpf_prog_alloc
  - kernel/bpf/syscall.c:bpf_prog_get_stats
  - kernel/bpf/map_iter.c:bpf_map_sum_elem_count
  - kernel/bpf/task_iter.c:task_iter_init
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:__bpf_hash_map_seq_show
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:__bpf_array_map_seq_show
  - kernel/bpf/arraymap.c:percpu_array_map_seq_show_elem
  - kernel/bpf/arraymap.c:array_map_free
  - kernel/bpf/arraymap.c:bpf_percpu_array_update
  - kernel/bpf/arraymap.c:bpf_percpu_array_copy
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop_nmi
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:___pcpu_freelist_pop
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_init
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:bpf_mem_alloc_destroy
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:check_leaked_objs
  - kernel/bpf/memalloc.c:bpf_mem_alloc_percpu_unit_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/devmap.c:dev_map_init
  - kernel/bpf/devmap.c:dev_map_notification
  - kernel/bpf/cpumap.c:cpu_map_init
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
  - kernel/events/core.c:perf_event_init
  - kernel/events/core.c:perf_reboot
  - kernel/events/core.c:perf_pmu_register
  - kernel/events/core.c:perf_event_mux_interval_ms_store
  - kernel/events/core.c:sw_perf_event_destroy
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:alloc_callchain_buffers
  - kernel/events/callchain.c:release_callchain_buffers_rcu
  - kernel/events/hw_breakpoint.c:hw_breakpoint_is_used
  - kernel/events/hw_breakpoint.c:unregister_wide_hw_breakpoint
  - kernel/events/hw_breakpoint.c:register_wide_hw_breakpoint
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_alloc_pd
  - kernel/padata.c:padata_do_serial
  - kernel/padata.c:padata_do_parallel
  - mm/oom_kill.c:constrained_alloc
  - mm/oom_kill.c:constrained_alloc
  - mm/swap.c:__lru_add_drain_all
  - mm/swap.c:__lru_add_drain_all
  - mm/vmscan.c:kswapd_init
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:lru_gen_exit_memcg
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_release_memcg
  - mm/vmscan.c:lru_gen_offline_memcg
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_del_mm
  - mm/vmscan.c:lru_gen_add_mm
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/shrinker.c:reparent_shrinker_deferred
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
  - mm/shrinker.c:free_shrinker_info
  - mm/mmzone.c:next_zone
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:set_pgdat_percpu_threshold
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:refresh_zone_stat_thresholds
  - mm/vmstat.c:fold_vm_numa_events
  - mm/vmstat.c:all_vm_events
  - mm/vmstat.c:sysctl_vm_numa_stat_handler
  - mm/mm_init.c:mm_core_init
  - mm/mm_init.c:page_alloc_init_late
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
  - mm/mm_init.c:free_area_init_core_hotplug
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:pcpu_build_alloc_info
  - mm/percpu.c:per_cpu_ptr_to_phys
  - mm/percpu.c:__is_kernel_percpu_address
  - mm/percpu.c:pcpu_alloc_size
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_balance_free
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_unmap_pages
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/compaction.c:kcompactd_init
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:compaction_zonelist_suitable
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/show_mem.c:show_free_areas
  - mm/list_lru.c:__list_lru_init
  - mm/list_lru.c:memcg_reparent_list_lrus
  - mm/list_lru.c:memcg_init_list_lru_one
  - mm/mmap_lock.c:trace_mmap_lock_reg
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/mmap_lock.c:free_memcg_path_bufs
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
  - mm/vmalloc.c:show_numa_info
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:_vm_unmap_aliases
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
  - mm/vmalloc.c:vmalloc_init
  - mm/page_alloc.c:zone_pcp_reset
  - mm/page_alloc.c:setup_per_cpu_pageset
  - mm/page_alloc.c:setup_pcp_cacheinfo
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__zone_set_pageset_high_and_batch
  - mm/page_alloc.c:build_all_zonelists_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:zone_watermark_ok_safe
  - mm/page_alloc.c:__drain_all_pages
  - mm/page_alloc.c:__drain_all_pages
  - mm/memory_hotplug.c:try_offline_node
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:slabs_cpu_partial_show
  - mm/slub.c:show_slab_objects
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:flush_all_cpus_locked
  - mm/slub.c:kmem_cache_init
  - mm/swapfile.c:swapfile_init
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:alloc_swap_info
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:setup_swap_info
  - mm/swapfile.c:add_to_avail_list
  - mm/swapfile.c:__del_from_avail_list
  - mm/zswap.c:shrink_memcg
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
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/khugepaged.c:alloc_charge_hpage
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:__mem_cgroup_free
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:__invalidate_reclaim_iterators
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_free
  - mm/memory-failure.c:memory_failure_init
  - fs/exec.c:mm_init_cid
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:shrink_dcache_sb
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/inode.c:get_nr_dirty_inodes
  - fs/inode.c:get_nr_inodes
  - fs/namespace.c:mnt_get_writers
  - fs/namespace.c:mnt_get_count
  - fs/seq_file.c:seq_hlist_start_percpu
  - fs/locks.c:filelock_init
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/uptime.c:uptime_proc_show
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_discard_preallocations_should_retry
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_init
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_journal_commit_callback
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/ext4/sysfs.c:ext4_attr_show
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_destroy
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi_percpu.c:squashfs_decompressor_create
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_write
  - security/selinux/ss/ebitmap.c:ebitmap_and
  - security/selinux/ss/policydb.c:filename_write_helper_compat
  - security/selinux/ss/policydb.c:role_bounds_sanity_check
  - security/selinux/ss/policydb.c:user_bounds_sanity_check
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:selinux_policy_commit
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:security_compute_xperms_decision
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/services.c:context_struct_compute_av
  - security/selinux/ss/mls.c:mls_convert_context
  - security/selinux/ss/mls.c:mls_sid_to_context
  - security/selinux/ss/mls.c:mls_compute_context_len
  - security/apparmor/lsm.c:alloc_buffers
  - security/landlock/ruleset.c:landlock_init_layer_masks
  - security/landlock/ruleset.c:landlock_unmask_layers
  - crypto/scompress.c:crypto_scomp_init_tfm
  - crypto/scompress.c:crypto_scomp_free_scratches
  - block/bio.c:bioset_exit
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-stat.c:blk_stat_add_callback
  - block/blk-stat.c:blk_stat_timer_fn
  - block/blk-mq-sysfs.c:blk_mq_sysfs_init
  - block/blk-mq-sysfs.c:blk_mq_sysfs_deinit
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_cpus_show
  - block/blk-mq-cpumap.c:blk_mq_hw_queue_to_node
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/genhd.c:part_inflight_show
  - block/genhd.c:del_gendisk
  - block/genhd.c:part_in_flight
  - block/genhd.c:part_stat_read_all
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:ioc_lat_stat
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-pci.c:blk_mq_pci_map_queues
  - block/blk-mq-virtio.c:blk_mq_virtio_map_queues
  - lib/random32.c:prandom_seed_full_state
  - lib/bitmap.c:bitmap_fold
  - lib/bitmap.c:bitmap_onto
  - lib/bitmap.c:bitmap_find_next_zero_area_off
  - lib/find_bit.c:find_next_clump8
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic_rcu
  - lib/bitmap-str.c:bitmap_parse
  - lib/genalloc.c:gen_pool_best_fit
  - lib/percpu_counter.c:percpu_counter_set
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_update
  - lib/cpu_rmap.c:cpu_rmap_copy_neigh
  - lib/cpu_rmap.c:alloc_cpu_rmap
  - lib/irq_poll.c:irq_poll_setup
  - lib/sbitmap.c:sbitmap_queue_show
  - lib/sbitmap.c:sbitmap_init_node
  - lib/group_cpus.c:group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:__group_cpus_evenly
  - lib/group_cpus.c:alloc_nodes_groups
  - lib/group_cpus.c:grp_spread_init_one
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_thread_fn
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq
  - drivers/gpio/gpio-mmio.c:bgpio_multiple_get_masks
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/gpio/gpio-mmio.c:bgpio_get_multiple_be
  - drivers/pci/search.c:pci_for_each_dma_alias
  - drivers/pci/pcie/aer.c:__aer_print_error
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_irq_domain_alloc
  - drivers/idle/intel_idle.c:intel_idle_init
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/x86/apple.c:acpi_extract_apple_properties
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_exit
  - drivers/acpi/processor_thermal.c:acpi_thermal_cpufreq_init
  - drivers/acpi/processor_thermal.c:phys_package_first_cpu
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_throttling.c:acpi_processor_update_tsd_coord
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_exit
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_init
  - drivers/acpi/numa/hmat.c:hmat_init
  - drivers/acpi/numa/hmat.c:__hmat_register_target_initiators
  - drivers/acpi/cppc_acpi.c:cppc_perf_ctrs_in_pcc
  - drivers/acpi/cppc_acpi.c:acpi_get_psd_map
  - drivers/acpi/cppc_acpi.c:cppc_allow_fast_switch
  - drivers/acpi/cppc_acpi.c:acpi_cpc_valid
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/pnp/manager.c:pnp_assign_irq
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:dma_channel_rebalance
  - drivers/dma/dmaengine.c:bytes_transferred_show
  - drivers/dma/dmaengine.c:memcpy_count_show
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
  - drivers/pmdomain/core.c:genpd_add_device
  - drivers/xen/cpu_hotplug.c:setup_cpu_watcher
  - drivers/xen/grant-table.c:get_free_seq
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_2l.c:evtchn_2l_resume
  - drivers/xen/events/events_2l.c:xen_debug_interrupt
  - drivers/xen/events/events_fifo.c:evtchn_fifo_resume
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_exit
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
  - drivers/xen/xen-acpi-processor.c:xen_upload_processor_pm_data
  - drivers/xen/xen-acpi-processor.c:free_acpi_perf_data
  - drivers/xen/xen-acpi-processor.c:check_acpi_ids
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/tty/n_tty.c:canon_copy_from_read_buf
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:kbd_match
  - drivers/tty/vt/keyboard.c:do_compute_shiftstate
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/irq_remapping.c:alloc_irte
  - drivers/iommu/intel/perfmon.c:iommu_pmu_cpu_offline
  - drivers/iommu/dma-iommu.c:iommu_put_dma_cookie
  - drivers/iommu/dma-iommu.c:iommu_dma_init_fq
  - drivers/iommu/dma-iommu.c:fq_flush_timeout
  - drivers/iommu/iova.c:free_iova_rcaches
  - drivers/iommu/iova.c:alloc_iova_fast
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/base/cacheinfo.c:update_per_cpu_data_slice_size
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_remove
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_read_distance
  - drivers/base/regmap/regmap-irq.c:regmap_irq_thread
  - drivers/block/xen-blkfront.c:xlbd_reserve_minors
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpu_offline
  - drivers/nvdimm/label.c:nd_label_alloc_slot
  - drivers/gpu/drm/drm_print.c:drm_print_bits
  - drivers/spi/spi.c:spi_emit_pcpu_stats
  - drivers/net/loopback.c:loopback_dev_init
  - drivers/net/loopback.c:dev_lstats_read
  - drivers/net/tun.c:tun_net_init
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_get_stats64
  - drivers/input/ff-core.c:input_ff_create
  - drivers/thermal/intel/intel_hfi.c:hfi_update_work_fn
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/md.c:is_mddev_idle
  - drivers/md/dm.c:dm_wait_for_bios_completion
  - drivers/md/dm-stats.c:message_stats_delete
  - drivers/md/dm-stats.c:__dm_stat_init_temporary_percpu_totals
  - drivers/md/dm-stats.c:dm_stats_init
  - drivers/md/dm-stats.c:dm_stat_free
  - drivers/opp/cpu.c:dev_pm_opp_set_sharing_cpus
  - drivers/opp/cpu.c:_dev_pm_opp_cpumask_remove_table
  - drivers/cpufreq/cpufreq.c:cpufreq_driver_fast_switch
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_free
  - drivers/cpufreq/cpufreq.c:cpufreq_show_cpus
  - drivers/cpufreq/cpufreq.c:cpufreq_notify_transition
  - drivers/cpufreq/cpufreq_ondemand.c:od_set_powersave_bias
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_stop
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_start
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
  - drivers/cpufreq/cpufreq_governor.c:free_policy_dbs_info
  - drivers/cpufreq/cpufreq_governor.c:dbs_update
  - drivers/cpufreq/cpufreq_governor.c:gov_update_cpu_data
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_early_init
  - drivers/cpufreq/acpi-cpufreq.c:free_acpi_perf_data
  - drivers/cpufreq/amd-pstate.c:cppc_enable
  - drivers/cpufreq/amd-pstate.c:pstate_enable
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/speedstep-centrino.c:centrino_target
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_driver_cleanup
  - drivers/cpufreq/intel_pstate.c:update_qos_request
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_limits
  - drivers/cpufreq/intel_pstate.c:intel_pstate_update_policies
  - drivers/cpuidle/cpuidle.c:cpuidle_unregister
  - drivers/cpuidle/driver.c:cpuidle_driver_state_disabled
  - drivers/leds/trigger/ledtrig-cpu.c:ledtrig_cpu_init
  - drivers/firmware/efi/unaccepted_memory.c:accept_memory
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
  - drivers/devfreq/governor_passive.c:get_target_freq_with_cpufreq
  - drivers/powercap/idle_inject.c:idle_inject_unregister
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_register_full
  - drivers/powercap/idle_inject.c:idle_inject_stop
  - net/core/sock.c:sock_inuse_get
  - net/core/sock.c:sock_prot_inuse_get
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/dev.c:net_dev_init
  - net/core/dev.c:dev_fetch_sw_netstats
  - net/core/dev.c:dev_get_stats
  - net/core/dev.c:netdev_refcnt_read
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:flush_all_backlogs
  - net/core/dev.c:netif_get_num_default_rss_queues
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dev.c:__netif_set_xps_queue
  - net/core/dst.c:metadata_dst_free_percpu
  - net/core/dst.c:metadata_dst_alloc_percpu
  - net/core/filter.c:bpf_clear_redirect_map
  - net/core/page_pool.c:page_pool_get_stats
  - net/core/drop_monitor.c:init_net_drop_monitor
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_cmd_stats_get
  - net/core/drop_monitor.c:net_dm_trace_off_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_trace_on_set
  - net/core/drop_monitor.c:net_dm_hw_monitor_stop
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/core/drop_monitor.c:net_dm_hw_monitor_start
  - net/sched/sch_generic.c:qdisc_alloc
  - net/sched/sch_mq.c:mq_dump_class_stats
  - net/sched/sch_api.c:tc_fill_qdisc
  - net/sched/act_api.c:tcf_idr_create
  - net/sched/act_api.c:tcf_idr_create
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_set_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_per_queue_coalesce
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ethtool/ioctl.c:ethtool_get_settings
  - net/ipv4/route.c:ip_rt_init
  - net/ipv4/route.c:rt_flush_dev
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:rt_acct_proc_show
  - net/ipv4/tcp.c:tcp_orphan_count_sum
  - net/ipv4/tcp_output.c:tcp_tasklet_init
  - net/ipv4/tcp_ipv4.c:tcp_v4_init
  - net/ipv4/icmp.c:icmp_init
  - net/ipv4/af_inet.c:ipv4_mib_init_net
  - net/ipv4/af_inet.c:snmp_fold_field
  - net/ipv4/fib_trie.c:trie_show_usage
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/tcp_sigpool.c:cpool_cleanup_work_cb
  - net/ipv4/tcp_sigpool.c:sigpool_reserve_scratch
  - net/xfrm/xfrm_input.c:xfrm_input_init
  - net/xfrm/xfrm_proc.c:xfrm_statistics_seq_show
  - net/ipv6/addrconf.c:addrconf_disable_policy_idev
  - net/ipv6/addrconf.c:snmp6_alloc_dev
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/icmp.c:icmpv6_init
  - net/ipv6/proc.c:snmp6_seq_show_item
  - net/ipv6/seg6_local.c:put_nla_counters
  - net/ipv6/seg6_local.c:parse_nla_counters
  - net/ipv6/seg6_hmac.c:seg6_hmac_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
  - net/devlink/trap.c:devl_trap_groups_register
  - net/devlink/trap.c:devlink_trap_stats_read
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mptcp/mib.c:mptcp_seq_show
  - lib/cpumask.c:cpumask_any_distribute
  - lib/cpumask.c:cpumask_next_wrap
  - lib/xarray.c:xas_squash_marks
```
**Symbols:**

```
ffffffff8185b040-ffffffff8185b0ad: _find_next_bit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffff800010633700)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
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
In lib/find_bit.c (c07d9ba0)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (c0000000007d8a40)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
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
In lib/find_bit.c (ffffffe0004616d2)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815213e0)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff815116d0)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff8151d470)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/find_bit.c (ffffffff81536ce0)
Location: lib/find_bit.c:30
Inline: True
Inline callers:
  - lib/find_bit.c:find_next_and_bit
  - lib/find_bit.c:find_next_zero_bit
  - lib/find_bit.c:find_next_bit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const long unsigned int *addr</code>
</li>
<li>
<b>Param removed. </b>
<code>const long unsigned int *addr1</code>
</li>
<li>
<b>Param removed. </b>
<code>const long unsigned int *addr2</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int invert</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int le</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr1, addr2, nbits, start, invert, le</code> ➡️ <code>addr, nbits, start</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
