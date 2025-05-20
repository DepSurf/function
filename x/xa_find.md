# Function: <code>xa_find</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a175a0)
Location: lib/xarray.c:1775
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff81a175a0-ffffffff81a17655: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87250)
Location: lib/xarray.c:1802
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff81a87250-ffffffff81a87305: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe4f0)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff81abe4f0-ffffffff81abe5a5: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fad30)
Location: lib/xarray.c:1815
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff815fad30-ffffffff815fade5: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161f530)
Location: lib/xarray.c:2005
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - mm/shmem.c:shmem_alloc_hugepage
  - fs/io_uring.c:tctx_inflight
  - fs/io_uring.c:__io_uring_files_cancel
  - fs/io_uring.c:io_uring_remove_task_files
```
**Symbols:**

```
ffffffff8161f530-ffffffff8161f5f9: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81602b60)
Location: lib/xarray.c:2006
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - mm/shmem.c:shmem_alloc_hugepage
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:__io_uring_cancel
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:partition_overlaps
```
**Symbols:**

```
ffffffff81602b60-ffffffff81602c29: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81671000)
Location: lib/xarray.c:2006
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - mm/shmem.c:shmem_alloc_hugepage
  - fs/io_uring.c:__io_uring_show_fdinfo
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_free
  - block/blk-settings.c:blk_queue_set_zoned
  - block/genhd.c:diskstats_show
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:partition_overlaps
  - drivers/base/memory.c:walk_dynamic_memory_groups
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_get_from_attrs
```
**Symbols:**

```
ffffffff81671000-ffffffff816710c9: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178aa20)
Location: lib/xarray.c:2013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_free_msi_descs_range
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/list_lru.c:list_lru_walk_node
  - block/blk-settings.c:blk_queue_set_zoned
  - block/blk-mq.c:blk_mq_cancel_work_sync
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - block/blk-mq.c:blk_mq_queue_stopped
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_wake_waiters
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:__blk_mq_register_dev
  - block/blk-mq-sysfs.c:blk_mq_unregister_dev
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/genhd.c:diskstats_show
  - block/genhd.c:show_partition
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:partition_overlaps
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - io_uring/io_uring.c:__io_uring_show_fdinfo
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/io_uring.c:io_ring_ctx_free
  - drivers/base/memory.c:walk_dynamic_memory_groups
  - net/core/devlink.c:devlink_pernet_pre_exit
  - net/core/devlink.c:devlink_nl_cmd_trap_policer_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_info_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_param_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_linecard_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_rate_get_dumpit
  - net/core/devlink.c:devlink_get_from_attrs
```
**Symbols:**

```
ffffffff8178aa20-ffffffff8178ab08: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82047f70)
Location: lib/xarray.c:2013
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_depopulate_descs
  - kernel/irq/msi.c:msi_domain_free_descs
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/list_lru.c:list_lru_walk_node
  - block/blk-settings.c:disk_set_zoned
  - block/blk-mq.c:blk_mq_cancel_work_sync
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_wake_waiters
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/genhd.c:diskstats_show
  - block/genhd.c:show_partition
  - block/genhd.c:printk_all_partitions
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:blk_drop_partitions
  - block/partitions/core.c:partition_overlaps
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
  - io_uring/tctx.c:io_uring_clean_tctx
  - io_uring/kbuf.c:io_destroy_buffers
  - drivers/pci/doe.c:pci_doe_supports_prot
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
  - drivers/base/memory.c:walk_dynamic_memory_groups
  - net/core/devlink.c:devlink_notify_unregister
  - net/core/devlink.c:devlink_notify_register
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_region_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_tc_pool_bind_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_sb_port_pool_get_dumpit
  - net/core/devlink.c:devlink_nl_cmd_port_get_dumpit
```
**Symbols:**

```
ffffffff82047f70-ffffffff82048058: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c6700)
Location: lib/xarray.c:2011
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_depopulate_descs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_domain_free_descs
  - mm/shmem.c:shmem_alloc_hugefolio
  - mm/list_lru.c:list_lru_walk_node
  - mm/vmalloc.c:_vm_unmap_aliases
  - block/blk-settings.c:disk_set_zoned
  - block/blk-mq.c:blk_mq_cancel_work_sync
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_wake_waiters
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/genhd.c:diskstats_show
  - block/genhd.c:show_partition
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:blk_mark_disk_dead
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:partition_overlaps
  - block/early-lookup.c:printk_all_partitions
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
  - io_uring/tctx.c:io_uring_clean_tctx
  - io_uring/kbuf.c:io_destroy_buffers
  - drivers/pci/doe.c:pci_doe_disconnected
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_find_doe_mailbox
  - drivers/pci/doe.c:pci_doe_supports_prot
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
  - drivers/base/memory.c:walk_dynamic_memory_groups
  - net/devlink/leftover.c:devlink_params_driverinit_load_new
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_unregister
  - net/devlink/leftover.c:devlink_notify_register
  - net/devlink/leftover.c:devlink_notify_register
  - net/devlink/leftover.c:devlink_nl_cmd_region_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_param_get_dump_one
  - net/devlink/leftover.c:devlink_param_find_by_name
  - net/devlink/leftover.c:devlink_nl_cmd_sb_tc_pool_bind_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_sb_port_pool_get_dump_one
  - net/devlink/leftover.c:devlink_nl_cmd_port_get_dump_one
  - net/devlink/core.c:devlinks_xa_find_get
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_get_dump_one
```
**Symbols:**

```
ffffffff820c6700-ffffffff820c67f6: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a1080)
Location: lib/xarray.c:2017
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_ioctl
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_depopulate_descs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_domain_free_descs
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/list_lru.c:list_lru_walk_node
  - mm/vmalloc.c:_vm_unmap_aliases
  - block/blk-mq.c:blk_mq_cancel_work_sync
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_release
  - block/blk-mq.c:queue_set_hctx_shared
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_map_swqueue
  - block/blk-mq.c:blk_mq_start_stopped_hw_queues
  - block/blk-mq.c:blk_mq_start_hw_queues
  - block/blk-mq.c:blk_mq_stop_hw_queues
  - block/blk-mq.c:blk_mq_delay_run_hw_queues
  - block/blk-mq.c:blk_mq_run_hw_queues
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_wake_waiters
  - block/blk-mq-tag.c:blk_mq_queue_tag_busy_iter
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister_hctxs
  - block/blk-mq-sysfs.c:blk_mq_sysfs_unregister
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sysfs.c:blk_mq_sysfs_register
  - block/blk-mq-sched.c:blk_mq_exit_sched
  - block/blk-mq-sched.c:blk_mq_sched_free_rqs
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
  - block/genhd.c:diskstats_show
  - block/genhd.c:show_partition
  - block/genhd.c:del_gendisk
  - block/genhd.c:del_gendisk
  - block/genhd.c:blk_report_disk_dead
  - block/genhd.c:disk_uevent
  - block/partitions/core.c:bdev_disk_changed
  - block/partitions/core.c:partition_overlaps
  - block/early-lookup.c:printk_all_partitions
  - block/blk-mq-debugfs.c:blk_mq_debugfs_unregister_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_hctxs
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
  - io_uring/fdinfo.c:io_uring_show_fdinfo
  - io_uring/tctx.c:io_uring_clean_tctx
  - io_uring/kbuf.c:io_destroy_buffers
  - drivers/pci/doe.c:pci_doe_disconnected
  - drivers/pci/doe.c:pci_doe_destroy
  - drivers/pci/doe.c:pci_find_doe_mailbox
  - drivers/pci/doe.c:pci_doe_supports_prot
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_tlb_sync
  - drivers/iommu/intel/iommu.c:switch_to_super_page
  - drivers/iommu/intel/iommu.c:intel_flush_iotlb_all
  - drivers/iommu/intel/iommu.c:parent_domain_flush
  - drivers/iommu/intel/iommu.c:domain_update_iommu_cap
  - drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user
  - drivers/base/memory.c:walk_dynamic_memory_groups
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_unregister
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_register
  - drivers/dpll/dpll_core.c:dpll_pin_on_pin_register
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_first
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
  - drivers/dpll/dpll_netlink.c:dpll_nl_device_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_device_find_from_nlattr
  - drivers/dpll/dpll_netlink.c:dpll_nl_pin_get_dumpit
  - drivers/dpll/dpll_netlink.c:dpll_pin_find
  - drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_phase_adj_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_phase_adj_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_phase_adj_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_freq_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_freq_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_freq_set
  - drivers/dpll/dpll_netlink.c:dpll_pin_available
  - drivers/dpll/dpll_netlink.c:dpll_pin_available
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_dplls
  - drivers/dpll/dpll_netlink.c:dpll_msg_add_pin_parents
  - net/core/netdev-genl.c:netdev_nl_queue_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_napi_get_dumpit
  - net/core/netdev-genl.c:netdev_nl_dev_get_dumpit
  - net/core/page_pool_user.c:netdev_nl_page_pool_get_dump
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/tunnels.c:ethnl_tunnel_info_dumpit
  - net/devlink/core.c:devlinks_xa_find_get
  - net/devlink/core.c:devlink_rel_devlink_handle_put
  - net/devlink/core.c:devlink_rel_devlink_handle_put
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
  - net/devlink/dev.c:devlink_nl_fill
  - net/devlink/port.c:devlink_nl_port_get_dump_one
  - net/devlink/port.c:devlink_ports_notify
  - net/devlink/sb.c:devlink_nl_sb_tc_pool_bind_get_dump_one
  - net/devlink/sb.c:devlink_nl_sb_port_pool_get_dump_one
  - net/devlink/param.c:devlink_params_driverinit_load_new
  - net/devlink/param.c:devlink_nl_param_get_dump_one
  - net/devlink/param.c:devlink_params_notify
  - net/devlink/param.c:devlink_param_find_by_name
  - net/devlink/region.c:devlink_nl_region_get_dump_one
  - net/devlink/health.c:devlink_nl_health_reporter_get_dump_one
```
**Symbols:**

```
ffffffff821a1080-ffffffff821a1176: xa_find (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d997a8)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffff800010d997a8-ffff800010d9985c: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96524)
Location: lib/xarray.c:1813
Inline: False
```
**Symbols:**

```
c0e96524-c0e965f4: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edf5c0)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
c000000000edf5c0-c000000000edf6c0: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c26b6)
Location: lib/xarray.c:1813
Inline: False
```
**Symbols:**

```
ffffffe0008c26b6-ffffffe0008c274a: xa_find (STB_GLOBAL)
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
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5d340)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff81a5d340-ffffffff81a5d3f5: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1a410)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff81a1a410-ffffffff81a1a4c5: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9730)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff81ac9730-ffffffff81ac97e5: xa_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xa_find(struct xarray *xa, long unsigned int *indexp, long unsigned int max, xa_mark_t filter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad5c40)
Location: lib/xarray.c:1813
Inline: False
Direct callers:
  - mm/shmem.c:shmem_alloc_hugepage
```
**Symbols:**

```
ffffffff81ad5c40-ffffffff81ad5d0e: xa_find (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
