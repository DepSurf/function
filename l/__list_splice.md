# Function: <code>__list_splice</code>

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
In kernel/exit.c (ffffffff81083e61)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810990e9)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/cgroup.c (ffffffff81115cc1)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In mm/vmscan.c (ffffffff811a32b2)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:putback_inactive_pages
```
```
In mm/slab_common.c (ffffffff811b32d6)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/list_lru.c (ffffffff811b9b01)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff811ee30b)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In fs/namespace.c (ffffffff8122cd8b)
Location: include/linux/list.h:274
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81235102)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/fs-writeback.c:move_expired_inodes
  - fs/fs-writeback.c:queue_io
```
```
In fs/pnode.c (ffffffff8123cf77)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812551ec)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_scan_ready_list
  - fs/eventpoll.c:ep_scan_ready_list
```
```
In fs/proc/kcore.c (ffffffff81286db3)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff8131059c)
Location: include/linux/list.h:274
Inline: True
```
```
In ipc/sem.c (ffffffff81328959)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/smack/smackfs.c (ffffffff813653df)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In block/blk-core.c (ffffffff813bb581)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-softirq.c (ffffffff813c1da2)
Location: include/linux/list.h:274
Inline: True
```
```
In block/blk-iopoll.c (ffffffff813c2532)
Location: include/linux/list.h:274
Inline: True
```
```
In block/blk-mq.c (ffffffff813c4084)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_flush_plug_list
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814719e5)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff8148556b)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff814d04ac)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
```
In drivers/base/bus.c (ffffffff81549747)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff8154b4fb)
Location: include/linux/list.h:274
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8155a8cd)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_error.c (ffffffff815aac12)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad418)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/ata/libata-eh.c (ffffffff815da423)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8163165e)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff816a1362)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff8171aec6)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff817307d9)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow.c (ffffffff817345a5)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/sched/cls_api.c (ffffffff81745ebc)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/ipv4/inetpeer.c (ffffffff81757e9c)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp_output.c (ffffffff8177773f)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/exit.c (ffffffff81086f06)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff8109c6d5)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810c7680)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup.c (ffffffff8111c9e0)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In kernel/events/core.c (ffffffff81189a1a)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811ba321)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811bfe81)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff811ccd3b)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff811cf0b3)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/list_lru.c (ffffffff811d3e91)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff8120d90b)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff81218140)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff8122b97f)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8125551f)
Location: include/linux/list.h:274
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81261e41)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81265042)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8127d57a)
Location: include/linux/list.h:274
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812b3f8a)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff81344967)
Location: include/linux/list.h:274
Inline: True
```
```
In ipc/sem.c (ffffffff8135d9f8)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8139b1aa)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff813ee68e)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff813ff3a7)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-softirq.c (ffffffff81405d42)
Location: include/linux/list.h:274
Inline: True
```
```
In block/blk-mq.c (ffffffff8140a0d3)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In lib/irq_poll.c (ffffffff8146212d)
Location: include/linux/list.h:274
Inline: True
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814bfe81)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff814d4188)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81521632)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/base/bus.c (ffffffff8159b39b)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff8159d1ef)
Location: include/linux/list.h:274
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815ac8df)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_error.c (ffffffff81604d54)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81609489)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff81633fc3)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81644b0d)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169222e)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81702462)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff81783723)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff8179af49)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow.c (ffffffff817a0e58)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/ipv4/inetpeer.c (ffffffff817c4145)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp_output.c (ffffffff817e475f)
Location: include/linux/list.h:274
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/exit.c (ffffffff8108be72)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810a1866)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810cd540)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup.c (ffffffff81124d10)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In kernel/events/core.c (ffffffff81198dea)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811ca9b1)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d06fe)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff811dce2b)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/compaction.c (ffffffff811df1e3)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/list_lru.c (ffffffff811e3d56)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff8121f962)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff8122a6e0)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff8123dedf)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8126776f)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff81275341)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81278483)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8129110a)
Location: include/linux/list.h:287
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812c9822)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff8135a727)
Location: include/linux/list.h:287
Inline: True
```
```
In ipc/sem.c (ffffffff81374241)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/smack/smackfs.c (ffffffff813b1e9a)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff81407ece)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff81418dc7)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-softirq.c (ffffffff8141ffd7)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff81424aef)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_process_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In lib/irq_poll.c (ffffffff81480a82)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8149f10f)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus_msi
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814e1e71)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff814f67d7)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8154db40)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/base/bus.c (ffffffff815c98fb)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff815cb72f)
Location: include/linux/list.h:287
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815db68f)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816224b4)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/label.c (ffffffff816238e8)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff81634436)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81638d69)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff81665113)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81675bdd)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c030e)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81734352)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff817b0cd3)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff817c8ce9)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow.c (ffffffff817cfa85)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/ipv4/inetpeer.c (ffffffff817f3c5d)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp_output.c (ffffffff818166bf)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/exit.c (ffffffff81089031)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff8109eba6)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810c9f60)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81124993)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/events/core.c (ffffffff811a0eca)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811d3504)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811d8bb4)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff811e607a)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff811e8e6d)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/list_lru.c (ffffffff811ee1c3)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff8122b1d8)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff81236308)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff81249886)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff81275f0c)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812828ab)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81285e7f)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8129dffa)
Location: include/linux/list.h:287
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812d6874)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff8136f990)
Location: include/linux/list.h:287
Inline: True
```
```
In ipc/sem.c (ffffffff81387553)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In security/smack/smackfs.c (ffffffff813c848a)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff8141560b)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff81426cd9)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff8142accd)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff8142df97)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff81430442)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8143571a)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81489c72)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff814a8f58)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff814edb61)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff81504e1d)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81562113)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/base/bus.c (ffffffff815de63b)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff815e02ff)
Location: include/linux/list.h:287
Inline: True
```
```
In drivers/base/power/main.c (ffffffff815f021d)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636fce)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/label.c (ffffffff8163862c)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff81648e83)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164d7b0)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff8167991d)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff8168a2f3)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d4cca)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff8174d732)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff817d104d)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff817e78a9)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow.c (ffffffff817eee95)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_gc_task
```
```
In net/ipv4/inetpeer.c (ffffffff81814044)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/tcp_output.c (ffffffff818369af)
Location: include/linux/list.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/exit.c (ffffffff8108fd8b)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810a53f0)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810d1774)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81130ad3)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/events/core.c (ffffffff811b47ca)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff811e8a5a)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff811ef2f5)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff811fc2ba)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff811ff1cd)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/list_lru.c (ffffffff81204633)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff812468d8)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff81255149)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff81269ae6)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812982ac)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812a53eb)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812a88ff)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812c14ea)
Location: include/linux/list.h:288
Inline: True
```
```
In fs/proc/kcore.c (ffffffff812fb0c4)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff813946a0)
Location: include/linux/list.h:288
Inline: True
```
```
In ipc/sem.c (ffffffff813abdbc)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff813ee91a)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff8143fddb)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff81451ce9)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff81455ebd)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff81459107)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff8145c4f2)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814614d4)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff814c5ec2)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff814e7f88)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815226e1)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff8154713d)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c641d)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/base/bus.c (ffffffff81645660)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff816473bf)
Location: include/linux/list.h:288
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8165771a)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169eca7)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816a0d2c)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff816b1f80)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b6a80)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff816e2f7d)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff816f3b1e)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817413ba)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff817c0c32)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff8184b13d)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff818627e9)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818b605f)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/exit.c (ffffffff8109396c)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810ab6c2)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810d9d3e)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8113f1a8)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119e4f2)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:synth_events_open
```
```
In kernel/events/core.c (ffffffff811d3959)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81209f78)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8120f188)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff8121dcb3)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff812205e7)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/list_lru.c (ffffffff8122531f)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff81269cce)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff81278fa8)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff8128e480)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812bdb70)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812cc2b2)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812cf493)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812ea2f2)
Location: include/linux/list.h:288
Inline: True
```
```
In fs/proc/kcore.c (ffffffff8132868c)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff813c39ae)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff813dbe5e)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8141f9c4)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff81472c43)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff81484f3f)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff8148930b)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff8148c77e)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff8148fdca)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81494efc)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff814f6e69)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff815175fc)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8155835c)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff8157d147)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815febc3)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/base/bus.c (ffffffff81680ad0)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff816828b6)
Location: include/linux/list.h:288
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8169331e)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816dad8e)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816dcfd1)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff816ee1ff)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f2d8a)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff8171f825)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff8173046a)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81782655)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81809350)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff8189554b)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff818ae4d7)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8190b8d7)
Location: include/linux/list.h:288
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/exit.c (ffffffff8109bc23)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810b4742)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810e38ce)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8114abc8)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81166b17)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811df551)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811e3d29)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8121cc5d)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/vmscan.c:putback_inactive_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122232a)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff81230c93)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff81233627)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/compaction.c:map_pages
```
```
In mm/list_lru.c (ffffffff81238518)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff8127e58e)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff8128d658)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff812a2fec)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812d31e0)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812e1209)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812e4803)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff812ff4c7)
Location: include/linux/list.h:341
Inline: True
```
```
In fs/locks.c (ffffffff81314409)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff8133f917)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff813dd155)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff813f64cd)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8143a7d9)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff814909c3)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff8149fdda)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814a3142)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814a621e)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814a96d1)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814aef89)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff8150b209)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8152d07c)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8156fcec)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff81594fc7)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81619c93)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/base/bus.c (ffffffff816a0560)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff816a23f6)
Location: include/linux/list.h:341
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b399e)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fcd45)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816ff321)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff81711df7)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715c2a)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff81742115)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81752b92)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817a8e95)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81835480)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183ee50)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff818b71c8)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
```
```
In net/core/link_watch.c (ffffffff818d2757)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/ip_input.c (ffffffff8191542f)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff81939ba7)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffff819995e3)
Location: include/linux/list.h:341
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffff810a01fe)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810ba34b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810ea4ee)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff811563a8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81173697)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811f4f49)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811faefb)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8122d077)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff812318e5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff812410cc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff81244dca)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff81249af2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff8129a38d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812a7fe5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff812be31c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812f147d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812ff971)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81302ff1)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8132067c)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffffffff8132f99e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffffffff8133bd49)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff81367c0a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff81408c90)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff8142288e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8146843f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff814bdb57)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff814cde31)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814d1202)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814d411e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814d7533)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814dd241)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81539919)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8155b81c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a01cd)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff815c6070)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164da44)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/base/bus.c (ffffffff816d948f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff816db132)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816ed71b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736f75)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff817390cc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff8174d273)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff817513cd)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff8177dc8c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81792a24)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ec87d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff818782d3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81881b86)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81902fe8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list
```
```
In net/core/link_watch.c (ffffffff8191f9ed)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff8195f061)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81977961)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8199de8a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffff81a05525)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffff810a686c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810c07cb)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810f5ebe)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81162008)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff8117f507)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81201f59)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81207fcb)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8123b297)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8123f9a5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff8124f571)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff8125328a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff81257f42)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff812aa24d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812b94d3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff812d020c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8130302d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff81314890)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81316071)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8133342c)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffffffff813431bc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffffffff81354289)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff8137fe8a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff8142059c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff8143c617)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8148221f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff814d69a7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff814e7151)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814ea5bf)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814ed43e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814f08b3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814f66b1)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff8155a739)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8157c8cc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815c104d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff815e72a0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166ff44)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff816db35f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff816fd48f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff816ff102)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8171174b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175ad14)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8175ce1c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff817713f5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8177565d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff817a1a9c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff817b6589)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d4267)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181d74d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff818aa113)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3a26)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81935d88)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81951c2d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81996503)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff819ae2f1)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819d494a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c0fe)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffff810aca03)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810c7f3e)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810ff672)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8117346c)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81192b19)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81229650)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81234c97)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff812682eb)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8126d964)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff8127d6ae)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/slab_common.c:shutdown_memcg_caches
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff81281f5b)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff81285ecf)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_list_lru_node
```
```
In mm/slub.c (ffffffff812def5c)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812ee034)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff813067c0)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8133cadf)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8134b9f0)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8134fc43)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/eventpoll.c (ffffffff8136d72b)
Location: include/linux/list.h:415
Inline: True
```
```
In fs/locks.c (ffffffff8139a85f)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff813ca31a)
Location: include/linux/list.h:415
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8146f2fd)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff8148d3dd)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff814da2a0)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff815365d0)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff815460d9)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff81549563)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff8154d017)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff81551564)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81557020)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff815e4082)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff81621e50)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166b0c6)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff81692937)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8172058b)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff8178f627)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff817b4fda)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/base/core.c:fw_devlink_resume
```
```
In drivers/base/bus.c (ffffffff817b6ded)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff817b8d19)
Location: include/linux/list.h:415
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817cd359)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a9e5)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8181c750)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff818339d5)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8183859d)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81865880)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff8187d224)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a1137)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1fb3)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81977c87)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff819845c5)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (ffffffff819dc644)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81a0ac8e)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81a22ab0)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81a6ee70)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81a8dd58)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81ac12ee)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81bacafc)
Location: include/linux/list.h:415
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_shutdown
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068526)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
```
```
In kernel/exit.c (ffffffff810a80c3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810c305e)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810fe182)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8117016c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff8118fc89)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81231144)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8123eca7)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81272d76)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81278058)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff81287908)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff8128c097)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff8129018d)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_list_lru_node
```
```
In mm/hugetlb.c (ffffffff812d0225)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff812ead2c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/migrate.c (ffffffff812f232f)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812f96a4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff81303644)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/zsmalloc.c (ffffffff81312500)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8134899f)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff81358910)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8135c909)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/eventpoll.c (ffffffff8137b6a1)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/locks.c (ffffffff813ac31f)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff813dbfda)
Location: include/linux/list.h:433
Inline: True
```
```
In fs/ext4/fast_commit.c (ffffffff81455cf6)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff81489a5d)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff814aaaf9)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff814f7860)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff81553540)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff81561f09)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff81565383)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff8156d6a4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq-sched.c (ffffffff81573679)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In lib/irq_poll.c (ffffffff816085b2)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff81648a40)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8168ba16)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff816b0377)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173d4eb)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff817ba1b7)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff817cbb1d)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff817cda89)
Location: include/linux/list.h:433
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817e1d1c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81829b05)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8182b7a0)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff81844605)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848f1d)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81874680)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81c18c8e)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818aff17)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818faed3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff8197c917)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81988665)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (ffffffff819dbca4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81a0bede)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81a22e10)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81a77840)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81a97d28)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81accd5e)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81bbe642)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_disconnect
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_check_send_data_fin
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_move_skbs
  - net/mptcp/protocol.c:__mptcp_push_pending
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc8add)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068abb)
Location: include/linux/list.h:433
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8106973c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In kernel/exit.c (ffffffff810a8ed7)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810c4e86)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff811005a2)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81170d9c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81190bb9)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff812352d4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81242ed7)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81278063)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8127cdb8)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff8128cae8)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff8128ec31)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff81295d70)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/hugetlb.c (ffffffff812d6ff5)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff812f27e2)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/migrate.c (ffffffff812f8696)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff812ffc72)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8130a78b)
Location: include/linux/list.h:433
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81318580)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8134ed6f)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8135f310)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff813632cf)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff81381e21)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/io_uring.c (ffffffff8139ae38)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/locks.c (ffffffff813b3aef)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff813e2f7c)
Location: include/linux/list.h:433
Inline: True
```
```
In fs/ext4/fast_commit.c (ffffffff8145b928)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff8148f2cd)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff814b1344)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff814fecaf)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff8155bcc0)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff8156a669)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff8156d9f3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff81575504)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8157b709)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In lib/irq_poll.c (ffffffff815eb212)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8162b600)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8166e6f3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff81692967)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/virt-dma.c (ffffffff81706d28)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff817089f8)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8172106b)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff8179da15)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff817af48d)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff817b1409)
Location: include/linux/list.h:433
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817c612c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180cd15)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8180eac2)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff818277f5)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182c34d)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81856e70)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81c0aa11)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8189326b)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddc93)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff819607a7)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196ce8a)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (ffffffff819c1f54)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff819f3042)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81a0a130)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81a5fe9d)
Location: include/linux/list.h:433
Inline: True
```
```
In net/netfilter/core.c (ffffffff81a83078)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7f1b)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81babd19)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_flush_join_list
```
```
In net/mptcp/pm_netlink.c (ffffffff81bba10f)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073831)
Location: include/linux/list.h:433
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073e8c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In kernel/exit.c (ffffffff810ba9c4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810d7a80)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff8111c602)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8119746c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff811b9a99)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff8126f416)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8127d727)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff812b5cfa)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff812c60c3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slab_common.c (ffffffff812cc8aa)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff812ceae8)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff812d641c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/hugetlb.c (ffffffff8131cec5)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff8133a214)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff81342d53)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff813498bf)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff813553f8)
Location: include/linux/list.h:433
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81364ab3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8139ce0f)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff813adf20)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff813b1acf)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff813cf071)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/io_uring.c (ffffffff813e5449)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/locks.c (ffffffff814037cf)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff81434a8c)
Location: include/linux/list.h:433
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81477a83)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff814af1f8)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff814e6d3d)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff81509843)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff81559cff)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff815bcff0)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff815ceb69)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff815d1fe3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff815d9b01)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff815e0aa6)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In lib/irq_poll.c (ffffffff81657722)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8169aad0)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff816e28c3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff817084b7)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/virt-dma.c (ffffffff817825d8)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff8178481c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179fe8b)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff81826a15)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff818386ed)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff8183a649)
Location: include/linux/list.h:433
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81850492)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81897280)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff818990a2)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff818b31b5)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b7eed)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff818e5710)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81d0f960)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81926dd3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff819797b3)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81a091f7)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a15967)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (ffffffff81a717d4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81aa3ea4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81abc640)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow_offload.c (ffffffff81ad463c)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81b190b4)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81b3cd08)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81b750db)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81c7da69)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81c89a9f)
Location: include/linux/list.h:433
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081c5e)
Location: include/linux/list.h:442
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8108290c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In kernel/exit.c (ffffffff810d158a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff810f22b9)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/sched/build_utility.c (ffffffff8113d702)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff811c8447)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff811ecbe9)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff812be6f9)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff812d1d56)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8130ef7f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/backing-dev.c (ffffffff81323538)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slab_common.c (ffffffff8132b02a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff8132cc1d)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff81335779)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/hugetlb.c (ffffffff81387565)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff813abf8f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff813b52a4)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff813c001c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff813c9bf2)
Location: include/linux/list.h:442
Inline: True
```
```
In mm/zsmalloc.c (ffffffff813e2cd3)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8141fd5f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff814350a0)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff81436b86)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff81457e24)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/locks.c (ffffffff814756af)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff814aebe3)
Location: include/linux/list.h:442
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff814f9ec9)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff815362c2)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff81574aec)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff8159b438)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff815f49e1)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff816669d0)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff81679e06)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-ioc.c (ffffffff8167dec1)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff81687477)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8168f6b2)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In io_uring/io_uring.c (ffffffff816c88e6)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff8176ef9c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff817bc263)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8180ce61)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff818367f3)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/virt-dma.c (ffffffff818b904d)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bb4e4)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d97bb)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff81965f93)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196aec8)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/base/bus.c (ffffffff8197ab30)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff8197ce99)
Location: include/linux/list.h:442
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81995e35)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb3b7)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0476)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff819e300a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff819fe365)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a03545)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81a36a0c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81a47d66)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7d1b4)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6e9f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81b71af7)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7db9a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (ffffffff81be323c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81c1c8a1)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81c3704b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow_offload.c (ffffffff81c52bdb)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81ca0787)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81cc91a5)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81d048c9)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32553)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff81e3519b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094696)
Location: include/linux/list.h:442
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109539c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In kernel/exit.c (ffffffff810effca)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff811130e9)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/sched/build_utility.c (ffffffff81168252)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff811abb3b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/cgroup/cgroup.c (ffffffff8120b437)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81233169)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff813219d2)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8133ab46)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81381374)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff81397d88)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slab_common.c (ffffffff813a047a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff813a31fd)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff813ac531)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/hugetlb.c (ffffffff814057c5)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff8142969f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff814357a1)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/huge_memory.c (ffffffff8144230a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff8144ed77)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/zsmalloc.c (ffffffff8146a23d)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff814ac26f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff814c30e0)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff814c4be6)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff814e7174)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/locks.c (ffffffff81507b7f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff81545271)
Location: include/linux/list.h:442
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815946dd)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff815d47c2)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff8161a8fc)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff81644788)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff816a5461)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff81720e10)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff81736296)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-ioc.c (ffffffff8173ab21)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff817456d7)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8174e1e2)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In io_uring/io_uring.c (ffffffff817886c8)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/kbuf.c (ffffffff8179ecb6)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff8189ea1d)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff818d80d3)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8193b951)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff8196a967)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/virt-dma.c (ffffffff81a066fd)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07999)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a004)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2c28b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff81acf723)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad53a8)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/base/bus.c (ffffffff81ae7a60)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff81aea289)
Location: include/linux/list.h:442
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81b069ec)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/block/xen-blkfront.c (ffffffff81b308e7)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5be5c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff81b5ec6a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7c805)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b82065)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81bbb6ec)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81bcee56)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61c1f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff81d0ed37)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1bb0a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (ffffffff81d8ee9c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81dcd931)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81dea8bb)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow_offload.c (ffffffff81e0819b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81e5c787)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81e88d35)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81ec988c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a8a3)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff8200de2b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097636)
Location: include/linux/list.h:442
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109832b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In kernel/exit.c (ffffffff810fbf8b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff8111f486)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/sched/build_utility.c (ffffffff81178912)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff811bda5b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/cgroup/cgroup.c (ffffffff812209aa)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81249e09)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81351b57)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8136ba26)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff813b2728)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff813cad08)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slab_common.c (ffffffff813d373a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff813d9cd0)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff813e08ce)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/hugetlb.c (ffffffff81438ce5)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/slub.c (ffffffff8145ea26)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/migrate.c (ffffffff8146b223)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_sync
  - mm/migrate.c:migrate_pages_sync
  - mm/migrate.c:migrate_pages_sync
```
```
In mm/huge_memory.c (ffffffff81477bf6)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff814848a7)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/zsmalloc.c (ffffffff8149f440)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff814e103f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff814f84c0)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff814fa066)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8151d9c4)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/locks.c (ffffffff8153f1ef)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff8157ce51)
Location: include/linux/list.h:442
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff815cb6b1)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff8160c3b2)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff81652bfc)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff8167cc77)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff816dde41)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff8175c6c0)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff817728f3)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-mq.c (ffffffff81781657)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8178a6c7)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In io_uring/io_uring.c (ffffffff817c8da8)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/kbuf.c (ffffffff817dfea6)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff818e0fed)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8191b3a3)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff8197f951)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff819b0f27)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/virt-dma.c (ffffffff81a4f58d)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50829)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a52e7c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a75a2b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff81b1ecf3)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23b58)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_free_iova
```
```
In drivers/base/bus.c (ffffffff81b3623a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff81b38619)
Location: include/linux/list.h:442
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81b54a2c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/block/xen-blkfront.c (ffffffff81b83dd7)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81baf42b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff81bb2224)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81bd0585)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd5d76)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81c12f4c)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff81c26ac6)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8fc0)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/md.c (ffffffff81d65ed1)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/dm.c (ffffffff81d78317)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d84c6a)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/list.h:442
Inline: True
```
```
In net/core/dev.c (ffffffff81e3e540)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81e5c09b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow_offload.c (ffffffff81e7aabb)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81eb933e)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81ee6ca5)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81f283dc)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff8207653f)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff82086a03)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff8208aa8b)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/handshake/netlink.c (ffffffff82092299)
Location: include/linux/list.h:442
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_net_exit
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109eba6)
Location: include/linux/list.h:523
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f8cb)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
```
In kernel/exit.c (ffffffff8110549b)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/exit.c:forget_original_parent
```
```
In kernel/workqueue.c (ffffffff81129736)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/workqueue.c:__flush_workqueue
```
```
In kernel/sched/build_utility.c (ffffffff81186632)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff811cdf7b)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/cgroup/cgroup.c (ffffffff812386fa)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81263d19)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81379037)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff813946a6)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff813dbcb9)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:scan_folios
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_folios_to_lru
  - mm/vmscan.c:isolate_lru_folios
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_folio_list
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/backing-dev.c (ffffffff813f5ce8)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/backing-dev.c:cleanup_offline_cgwbs_workfn
```
```
In mm/slab_common.c (ffffffff813fe13a)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff81403a25)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff8140b19e)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/slub.c (ffffffff8145d0fb)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_do_shrink
```
```
In mm/hugetlb.c (ffffffff814726a2)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/hugetlb.c:allocate_file_region_entries
```
```
In mm/migrate.c (ffffffff8149a244)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_sync
  - mm/migrate.c:migrate_pages_sync
  - mm/migrate.c:migrate_pages_sync
```
```
In mm/huge_memory.c (ffffffff814a7376)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/memcontrol.c (ffffffff814b3d97)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_reparent_objcgs
```
```
In mm/zsmalloc.c (ffffffff814ceb90)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8151510f)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8152cc40)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8152e7ad)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff81551fa4)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_done_scan
```
```
In fs/locks.c (ffffffff815746cf)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff815b5771)
Location: include/linux/list.h:523
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffff81604452)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff81645172)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff8168c20c)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff816b9047)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8171a964)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff8179e5c0)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff817b4c93)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-mq.c (ffffffff817c3637)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_dispatch_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff817cce27)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_do_dispatch_sched
```
```
In io_uring/io_uring.c (ffffffff8180daf8)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/kbuf.c (ffffffff818242eb)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_refill_buffer_cache
  - io_uring/kbuf.c:io_destroy_buffers
```
```
In lib/irq_poll.c (ffffffff81927b5d)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff819637d3)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff819cc0c1)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/mipi-disco-img.c (ffffffff819f3c4f)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:acpi_mipi_scan_crs_csi2
```
```
In drivers/acpi/pci_root.c (ffffffff819fb407)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/virt-dma.c (ffffffff81a9b22d)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c4f9)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_synchronize
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_free_chan_resources
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_terminate_all
  - drivers/dma/hsu/hsu.c:hsu_dma_issue_pending
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9ec2c)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_work
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_terminate_all
  - drivers/dma/lgm/lgm-dma.c:ldma_synchronize
  - drivers/dma/lgm/lgm-dma.c:ldma_issue_pending
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7c1b)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff81b75332)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b795b2)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
```
```
In drivers/base/bus.c (ffffffff81b8dc5a)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff81b900b9)
Location: include/linux/list.h:523
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81bacfec)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7d07)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c03859)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff81c06714)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81c251e5)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_unjam_host
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a9cb)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81c6806c)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c90fc6)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:do_hdmi_vsdb_modes
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9c53c)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lru_scan
```
```
In drivers/gpu/drm/drm_flip_work.c (ffffffff81cc8a92)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_flip_work.c:flip_worker
  - drivers/gpu/drm/drm_flip_work.c:drm_flip_work_commit
```
```
In drivers/gpu/drm/drm_modeset_helper.c (ffffffff81ccc672)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_helper.c:drm_helper_move_panel_connectors_to_head
```
```
In drivers/spi/spi.c (ffffffff81cd91e6)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7dea0)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:sitd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:iso_stream_schedule
  - drivers/usb/host/ehci-hcd.c:itd_urb_transaction
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/md.c (ffffffff81e1d4ef)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/dm.c (ffffffff81e2f547)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3c42a)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In drivers/interconnect/core.c (ffffffff81eb37dc)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81efcdf0)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81f1b47b)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/core/flow_offload.c (ffffffff81f3ac8a)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_register
```
```
In net/sched/cls_api.c (ffffffff81f7c495)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_block_bind
```
```
In net/netfilter/core.c (ffffffff81faaab5)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/netfilter/core.c:nf_hook_slow_list
```
```
In net/ipv4/tcp_output.c (ffffffff81fecccc)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff8214aed1)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff8215bb83)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff8216065b)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/handshake/netlink.c (ffffffff82168b79)
Location: include/linux/list.h:523
Inline: True
Inline callers:
  - net/handshake/netlink.c:handshake_net_exit
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
In kernel/exit.c (ffff8000100fd73c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffff80001011d1a0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffff8000101594f8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffff8000101d33ec)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffff8000101f44dc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffff80001028a368)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffff8000102942ac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffff8000102cc320)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d1b84)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffff8000102e598c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffff8000102ea86c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffff8000102efb0c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffff80001034bfc8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffff800010359c94)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffff800010374e7c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffff8000103b6400)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffff8000103ca6f4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffff8000103cca58)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffff8000103f0754)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffff800010404e30)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffff800010416a74)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffff80001044daf8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffff80001050317c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffff80001052446c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffff8000105740f4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffff8000105d2dc8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffff8000105e4b38)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffff8000105e8bc8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffff8000105ebf64)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffff8000105ef460)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffff8000105f6c54)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffff800010667cac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffff8000106e0004)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071dc44)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f834)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-aardvark.c (ffff80001072061c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffff800010723050)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff8000107239b8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724fa8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
```
```
In drivers/pci/controller/pcie-altera.c (ffff8000107275f8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c804)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
```
```
In drivers/pci/controller/pci-xgene.c (ffff80001073a164)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffff800010749ef8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffff8000107744dc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/virt-dma.c (ffff8000107fe710)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/amba-pl08x.c (ffff800010801e70)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/bcm2835-dma.c (ffff800010805068)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_terminate_all
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_issue_pending
```
```
In drivers/dma/mv_xor.c (ffff80001080681c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080cd60)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083aecc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffff8000108c72cc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffff8000108e93b4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffff8000108ea1e0)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (ffff800010901f9c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095c454)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffff80001095e5d4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffff800010974974)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffff8000109798bc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffff8000109ad3ac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffff8000109c3adc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a578bc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffff800010affdac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b7e0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffff800010bd42d4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffff800010bf3b28)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffff800010c42db8)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffff800010c5e7e8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffff800010c874dc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffff800010cfcf00)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In arch/arm/kernel/bios32.c (c03117ac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
```
```
In kernel/exit.c (c035a91c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (c03731ec)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (c03a6794)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (c041617c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (c043488c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (c04b9a14)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (c04c2680)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (c04f60c8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (c0509c20)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (c050e014)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (c0513360)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (c054fddc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/zsmalloc.c (c05611bc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (c059473c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (c05a6cdc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (c05a8798)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (c05c6244)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (c05d4820)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (c05e1d44)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/fuse/dev.c (c06bf3b0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (c06df234)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (c072714c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (c077fd1c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_generate
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (c0791d5c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (c07953e0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (c0798568)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (c079bc74)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (c07a2438)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (c0810310)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (c087bcc8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6cb0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a84e4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9d94)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (c08afd24)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b04cc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b17d8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b28d4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/video/fbdev/core/fbsysfs.c (c08cc908)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/dma/virt-dma.c (c091fa04)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_complete
```
```
In drivers/dma/amba-pl08x.c (c092255c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_terminate_all
  - drivers/dma/amba-pl08x.c:pl08x_issue_pending
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
  - drivers/dma/amba-pl08x.c:pl08x_free_chan_resources
```
```
In drivers/dma/mv_xor.c (c092451c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/ipu/ipu_idmac.c (c092952c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/dma/tegra20-apb-dma.c (c092af28)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_tx_submit
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_desc_put
```
```
In drivers/dma/ti/edma.c (c092da80)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:edma_issue_pending
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_free_chan_resources
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/edma.c:edma_terminate_all
  - drivers/dma/ti/edma.c:edma_terminate_all
```
```
In drivers/dma/ti/omap-dma.c (c09327a0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_terminate_all
  - drivers/dma/ti/omap-dma.c:omap_dma_issue_pending
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
  - drivers/dma/ti/omap-dma.c:omap_dma_free_chan_resources
```
```
In drivers/iommu/iommu.c (c09be2c8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (c09d64ac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (c09d81bc)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (c09ec2a4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/scsi/scsi_error.c (c0a492fc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (c0a4d610)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (c0a7cd08)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (c0ab1908)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (c0b2a688)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (c0bdf9a8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (c0be9b64)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (c0cefae0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (c0d0c118)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (c0d54394)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (c0d6de9c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (c0d968a0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (c0e04c48)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (c00000000014466c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (c000000000167440)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (c0000000001adb60)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (c00000000023e624)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (c0000000002693f4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (c000000000335770)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (c00000000033fae0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (c0000000003897b0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c000000000391514)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (c0000000003a7a94)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (c0000000003ad47c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (c0000000003b4340)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (c00000000042b838)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (c000000000443474)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (c000000000467514)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (c0000000004b2a5c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (c0000000004cc0b4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (c0000000004ce47c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (c0000000004f7eb8)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (c00000000050d8b8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (c0000000005257dc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (c0000000005652d0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (c00000000064769c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (c00000000066e9c0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (c0000000006df378)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (c00000000075f54c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (c000000000778ad4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (c00000000077d7b4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (c000000000781520)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (c000000000786018)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (c00000000078f060)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (c00000000081d0a8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (c000000000858d44)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088ecc4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c0000000008913a8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-host-common.c (c000000000891738)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c0000000008923c4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/video/fbdev/core/fbsysfs.c (c0000000008ab3cc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/iommu/iommu.c (c00000000096daac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (c00000000097ecc0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (c00000000098117c)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (c00000000099fff4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0d968)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (c000000000a10618)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (c000000000a2e914)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (c000000000a342c4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (c000000000a745a0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (c000000000a89218)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b25554)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (c000000000bef200)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (c000000000bfd5ec)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (c000000000cb3320)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (c000000000cd8e18)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (c000000000d3e938)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (c000000000d61104)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (c000000000d93fd4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (c000000000e25394)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffe0000c5f44)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffe0000d7704)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffe0000ff5a2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffe00014cc06)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffe000167788)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffe0001be43e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffe0001c40e8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffe0001eae30)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffe0001fc38e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffe0001fef02)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffe000203634)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffe00023d36e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/zsmalloc.c (ffffffe00024dd3e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffe0002790c6)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffe0002888da)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffe000289fa2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffe0002a3082)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffffffe0002b01ca)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffffffe0002bd978)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffe0002e235e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffe00036feee)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffe0003891b2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffe0003c72c2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffe00041753e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffe0004261d8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffe000429584)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffe00042bd44)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffe00042ecc2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffe00043447c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffe0004930a0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffe0004b7f32)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e4a64)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e66e2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffffffe0004e68a0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e70bc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffe0004f8220)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/base/bus.c (ffffffe00057c94c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffe00057e000)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca76e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffe0005cc572)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dd43c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0f4a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffe00060a78e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffe000616dd8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000672ce4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffe0006edb2c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f9058)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffe00075e238)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffe000775206)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffe0007b1d82)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffe0007c6ef2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffe0007e890e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffe000847a5e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffff810a018c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810bab3b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810ef2be)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8115a628)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81177b27)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811fa579)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff812005eb)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff812338e7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81237ff5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff81247bc1)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff8124b8da)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff81250592)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff812a282d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812b1ab3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff812c87ec)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812fb60d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8130ce70)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8130e651)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8132ba0c)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffffffff8133b79c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffffffff8134c869)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff8137846a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff81418b7c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff81434bf7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8147a7ff)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff814cef87)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff814df731)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814e2b9f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814e5a1e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814e8e93)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814eec91)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81552d19)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff81570dec)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b519d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff815d8580)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81636004)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff816a0daf)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff816c2c7f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff816c48f2)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816d7acb)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f404)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8171150c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff81725ae5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729d4d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/nvme/host/core.c (ffffffff817462cb)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_remove_namespaces
```
```
In drivers/ata/libata-eh.c (ffffffff81766b5c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff8177b069)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d5b2d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff8184ff93)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff818598a6)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff818d5d58)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff818f1bfd)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81936373)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff8194e161)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819747ba)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffff819db78e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffff8108ebbc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810a947b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810df33e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8114d918)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff8116acc7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811ed2c9)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811f333b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81226961)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff8122b035)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff8123ab6b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff8123e87a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff8124351c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff812942fd)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812a2e83)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff812b982c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812ec22d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff812fda90)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff812ff261)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8131bbac)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffffffff8132c47c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffffffff8133d549)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff81368f3a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff814095fc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff81425677)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8146b21f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff814bf9a7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff814d00d1)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814d352f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814d60c8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814d9403)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814df1d1)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81542fb3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8155f54c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815a3f9d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff815c2170)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/iommu/iommu.c (ffffffff8167e79f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff8169df2f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff8169fb72)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (ffffffff816b212b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2e84)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816e4f8c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff816fef15)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8170316d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/nvme/host/core.c (ffffffff81727f4b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_remove_namespaces
```
```
In drivers/ata/libata-eh.c (ffffffff817469bc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff8175ae19)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177e317)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/md/dm.c (ffffffff818175a3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff81820eb6)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff8188fba2)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff818aba3d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff818efe73)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81907c51)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff8192e27a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffff8199854e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffff810a013c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810ba09b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810ec3ee)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff811583f8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff811758f7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811f8349)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811fe3bb)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81231687)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81235d95)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff81245961)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff8124967a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff8124e332)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff812a063d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812af8c3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff812c65fc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812f93fd)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8130ac60)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8130c441)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff813294dc)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffffffff8133926c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffffffff8134a339)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff81375f3a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff81414d1c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff81430d97)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8147689f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff814cb017)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff814db7c1)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814dec2f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814e1aae)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814e4f23)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814ead21)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff8154ea59)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8157061c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815b572d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff815db580)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81663d84)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff816cf01f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff816f114f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff816f2dc2)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8170540b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174e1d4)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff817502dc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff817648b5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768b1d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff8179691c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff817ab409)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817c90e7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818125cd)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff8189f5c3)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a8ed6)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff81926d88)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81942c2d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81987503)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff819b8931)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819def8a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffff81a4620e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In kernel/exit.c (ffffffff810a80c0)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff810c309b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue
```
```
In kernel/sched/swait.c (ffffffff810f72be)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81165448)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81183437)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff812066c5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8120d41b)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff81240ab9)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:isolate_lru_pages
  - mm/vmscan.c:reclaim_clean_pages_from_list
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffff81246073)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/slab_common.c (ffffffff81254868)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/compaction.c (ffffffff81258efa)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/compaction.c:fast_isolate_freepages
  - mm/compaction.c:move_freelist_tail
  - mm/compaction.c:split_map_pages
```
```
In mm/list_lru.c (ffffffff8125dca5)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/slub.c (ffffffff812b077d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shrink
```
```
In mm/huge_memory.c (ffffffff812bfc03)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
```
```
In mm/zsmalloc.c (ffffffff812d7e6c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8130a71d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
  - fs/namespace.c:commit_tree
```
```
In fs/fs-writeback.c (ffffffff8131c392)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
  - fs/fs-writeback.c:move_expired_inodes
```
```
In fs/pnode.c (ffffffff8131dc71)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:change_mnt_propagation
```
```
In fs/eventpoll.c (ffffffff8133a867)
Location: include/linux/list.h:401
Inline: True
```
```
In fs/io_uring.c (ffffffff8134baac)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_free_req
```
```
In fs/locks.c (ffffffff8135b119)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/proc/kcore.c (ffffffff813899ea)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/proc/kcore.c:kcore_update_ram
  - fs/proc/kcore.c:kcore_update_ram
```
```
In fs/fuse/dev.c (ffffffff8142b57c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff81447454)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In security/smack/smackfs.c (ffffffff8148e34f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_relabel_self
```
```
In crypto/drbg.c (ffffffff814e3ae7)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_hash_process_addtl
  - crypto/drbg.c:drbg_hash_update
  - crypto/drbg.c:drbg_hmac_update
  - crypto/drbg.c:drbg_ctr_df
```
```
In block/blk-core.c (ffffffff814f4631)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814f7a9f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814fa96e)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814fdd53)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:flush_busy_ctx
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81503d01)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff815688a9)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8158aafc)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffff815cf19d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
  - drivers/video/fbdev/core/fbsysfs.c:store_modes
```
```
In drivers/acpi/pci_root.c (ffffffff815f5440)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167e344)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:watch_fired
```
```
In drivers/iommu/iommu.c (ffffffff816e958f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/bus.c (ffffffff8170b98f)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/dd.c (ffffffff8170d5f2)
Location: include/linux/list.h:401
Inline: True
```
```
In drivers/base/power/main.c (ffffffff8171fd38)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_complete
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81769654)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8176b75c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff8177ff35)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178429d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff817b078c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/spi/spi.c (ffffffff817c5399)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
  - drivers/spi/spi.c:__spi_replace_transfers_release
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e3387)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182d09d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:iso_sched_free
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/md/dm.c (ffffffff818bb823)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c52e6)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:do_work
```
```
In net/core/dev.c (ffffffff819483d8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff8196448d)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff819a99c3)
Location: include/linux/list.h:401
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff819c21a8)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/tcp_output.c (ffffffff819e8c2a)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/ipv6/ip6_input.c (ffffffff81a51f0c)
Location: include/linux/list.h:401
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
</details>
</li>
</ul>

## Differences
