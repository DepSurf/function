# Function: <code>list_splice_init</code>

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
In kernel/cgroup.c (ffffffff81116b52)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In mm/list_lru.c (ffffffff811b9af6)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In fs/fs-writeback.c (ffffffff81236283)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff812551e3)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_scan_ready_list
```
```
In fs/fuse/dev.c (ffffffff8131058d)
Location: include/linux/list.h:319
Inline: True
```
```
In ipc/sem.c (ffffffff81328948)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In block/blk-core.c (ffffffff813bb581)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-softirq.c (ffffffff813c1d97)
Location: include/linux/list.h:319
Inline: True
```
```
In block/blk-iopoll.c (ffffffff813c2527)
Location: include/linux/list.h:319
Inline: True
```
```
In block/blk-mq.c (ffffffff813c406f)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_flush_plug_list
```
```
In drivers/acpi/pci_root.c (ffffffff81485563)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/scsi/scsi_error.c (ffffffff815aac0f)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad40f)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
```
```
In drivers/ata/libata-eh.c (ffffffff815da410)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff816a134f)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff8171aeba)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff817307ca)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/sched/cls_api.c (ffffffff81745eaf)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_change
```
```
In net/ipv4/tcp_output.c (ffffffff81777732)
Location: include/linux/list.h:319
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
In kernel/sched/swait.c (ffffffff810c7676)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup.c (ffffffff8111de4b)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In kernel/events/core.c (ffffffff81189a01)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/list_lru.c (ffffffff811d3e86)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff8122b972)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/fs-writeback.c (ffffffff81261e35)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8127d571)
Location: include/linux/list.h:319
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81344958)
Location: include/linux/list.h:319
Inline: True
```
```
In ipc/sem.c (ffffffff8135d9e7)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In block/blk-core.c (ffffffff813ff39a)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-softirq.c (ffffffff81405d37)
Location: include/linux/list.h:319
Inline: True
```
```
In block/blk-mq.c (ffffffff8140a0ca)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:__blk_mq_run_hw_queue
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In lib/irq_poll.c (ffffffff81462122)
Location: include/linux/list.h:319
Inline: True
```
```
In drivers/acpi/pci_root.c (ffffffff814d4180)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/scsi/scsi_error.c (ffffffff81604d3b)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81609478)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff81633fb0)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8170244f)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff8178371a)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff8179af3a)
Location: include/linux/list.h:319
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817e4752)
Location: include/linux/list.h:319
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
In kernel/sched/swait.c (ffffffff810cd536)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup.c (ffffffff8112617b)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_taskset_migrate
```
```
In kernel/events/core.c (ffffffff81198dd1)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/list_lru.c (ffffffff811e3d4b)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff8123ded2)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/fs-writeback.c (ffffffff81275335)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff81291101)
Location: include/linux/list.h:332
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8135a718)
Location: include/linux/list.h:332
Inline: True
```
```
In ipc/sem.c (ffffffff8137422f)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In block/blk-core.c (ffffffff81418dba)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-softirq.c (ffffffff8141ffcc)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff81424ae6)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_process_rq_list
  - block/blk-mq.c:blk_mq_abort_requeue_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In lib/irq_poll.c (ffffffff81480a77)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8149f0d9)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus_msi
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff814f67cf)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816224a7)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/scsi/scsi_error.c (ffffffff8163441d)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81638d58)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff81665100)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8173433f)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff817b0ccb)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff817c8cda)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818166b2)
Location: include/linux/list.h:332
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
In kernel/sched/swait.c (ffffffff810c9f56)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff811251ae)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/events/core.c (ffffffff811a0eb1)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff811e6117)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff811ee1b8)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff81249877)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/fs-writeback.c (ffffffff8128289f)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8129dff1)
Location: include/linux/list.h:332
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8136f983)
Location: include/linux/list.h:332
Inline: True
```
```
In ipc/sem.c (ffffffff8138753d)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - ipc/sem.c:SYSC_semtimedop
```
```
In block/blk-core.c (ffffffff81426ccb)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff8142acba)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff8142df8c)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff81430439)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81435711)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81489c67)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff814a8f2f)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff81504e11)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636fc1)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/scsi/scsi_error.c (ffffffff81648e76)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164d7a3)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff81679910)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8174d71f)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff817d1045)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff817e789a)
Location: include/linux/list.h:332
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818369a2)
Location: include/linux/list.h:332
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
In kernel/sched/swait.c (ffffffff810d1765)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8113146c)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/events/core.c (ffffffff811b47b1)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff811fc357)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81204628)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff81269ad7)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/fs-writeback.c (ffffffff812a53df)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff812c14e1)
Location: include/linux/list.h:333
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81394693)
Location: include/linux/list.h:333
Inline: True
```
```
In ipc/sem.c (ffffffff813abda6)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff81451cdb)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff81455eaa)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814590fc)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff8145c4e9)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814614cb)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff814c5eb7)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff814e7f5f)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff81547131)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169ec9a)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff816b1f73)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b6a73)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff816e2f70)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff817c0c1f)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff8184b135)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff818627da)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818b6052)
Location: include/linux/list.h:333
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
In kernel/sched/swait.c (ffffffff810d9d2f)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8113fb1f)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/trace/trace_events_hist.c (ffffffff8119e4d8)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:synth_events_open
```
```
In kernel/events/core.c (ffffffff811d3942)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff8121d4b7)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff8122530d)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff8128e471)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/fs-writeback.c (ffffffff812cc298)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff812ea2e1)
Location: include/linux/list.h:333
Inline: True
```
```
In fs/fuse/dev.c (ffffffff813c39a1)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_abort_conn
```
```
In ipc/sem.c (ffffffff813dbe48)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff81484f2e)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814892f8)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff8148c76c)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff8148fdb9)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81494eeb)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff814f6e57)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff815175d8)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff8157d131)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816dad79)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff816ee1f2)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f2d71)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff8171f818)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8180933d)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff81895535)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
```
```
In net/core/link_watch.c (ffffffff818ae4ba)
Location: include/linux/list.h:333
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8190b8ca)
Location: include/linux/list.h:333
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
In kernel/sched/swait.c (ffffffff810e38bf)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8114b53f)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81166b06)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811df535)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811e3d12)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff812304a7)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81238506)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff812a2fdf)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/fs-writeback.c (ffffffff812e11ef)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff812ff4b6)
Location: include/linux/list.h:386
Inline: True
```
```
In fs/locks.c (ffffffff813143f6)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff813dd142)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff813f64b7)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff8149fdc9)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814a312f)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814a620c)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814a96bb)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814aef78)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff8150b1f7)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8152d058)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff81594fb1)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fcd30)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81711dea)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715c11)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff81742108)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8183546d)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff818b71b5)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list
  - net/core/dev.c:netif_receive_skb_list
```
```
In net/core/link_watch.c (ffffffff818d273a)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81939b9a)
Location: include/linux/list.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffff810ea4df)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81156e1f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81173686)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811f4f2d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811faee8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff8124229a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81249ae0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff812be30f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812f1467)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff812ff95e)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff81320668)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffffffff8132f98a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffffffff8133bd36)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff81408c7d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff81422878)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff814cde1d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814d11ef)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814d410c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814d751d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814dd22d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81539907)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8155b7fd)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff815c605d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736f60)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff8174d266)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff817513bc)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff8177dc7d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff818782c0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff81902fd5)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list
```
```
In net/core/link_watch.c (ffffffff8191f9d0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8199de7d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffff810f5eaf)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81162a8f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff8117f4f6)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81201f3d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81207fb8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff8125072a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81257f30)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff812d01ff)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff81303017)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8131487d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff81333418)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffffffff813431a8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffffffff81354276)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff81420589)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff8143c601)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff814e713d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814ea5ac)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814ed42c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814f089d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814f669d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff8155a727)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8157c8ad)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff815e728d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175acff)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff817713e8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8177564c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff817a1a8d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff818aa100)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff81935d75)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81951c10)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819d493d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffff810ff65f)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81174075)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81192b10)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81229642)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81234c7e)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff8127ed88)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81285ec4)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_list_lru_node
```
```
In mm/zsmalloc.c (ffffffff813067af)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8133cad7)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8134b9d5)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8136d716)
Location: include/linux/list.h:460
Inline: True
```
```
In fs/locks.c (ffffffff8139a856)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff8146f2ee)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff8148d3d1)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff815460c0)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff8154954c)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff8154d00c)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff8155154f)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81557008)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff815e4077)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff81621e40)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff81692921)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a9bd)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff818339c4)
Location: include/linux/list.h:460
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
In drivers/scsi/scsi_lib.c (ffffffff81838588)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff8186586d)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff81977c70)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (ffffffff819dc62f)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81a0ac7f)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81a22a8f)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ac12dd)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81baafa1)
Location: include/linux/list.h:460
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
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
In kernel/sched/swait.c (ffffffff810fe16f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81170d55)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff8118fc80)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81231137)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8123ec8e)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff812878e7)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81290182)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_list_lru_node
```
```
In mm/zsmalloc.c (ffffffff813124ef)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff81348997)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff813588f5)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8137b68c)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/locks.c (ffffffff813ac316)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/ext4/fast_commit.c (ffffffff81455ce3)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff81489a4e)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff814aaaed)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff81561ef0)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff8156536c)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff8156d68f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq-sched.c (ffffffff81573664)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff816085a7)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff81648a30)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff816b0361)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81829add)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff818445f4)
Location: include/linux/list.h:478
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
In drivers/scsi/scsi_lib.c (ffffffff81848f08)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff8187466d)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8197c900)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (ffffffff819dbc8f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81a0becf)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81a22def)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81accd4d)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81bbefcb)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc8acc)
Location: include/linux/list.h:478
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
In kernel/sched/swait.c (ffffffff8110058f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81171997)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81190bb0)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff812352c7)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff81242ebe)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff8128cac7)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81295d65)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff8131856f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8134ed67)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8135f2f5)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff81381e0c)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/io_uring.c (ffffffff8139ae25)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/locks.c (ffffffff813b3ae6)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/ext4/fast_commit.c (ffffffff8145b915)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff8148f2be)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff814b1338)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff8156a650)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff8156d9dc)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff815754ef)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8157b6f4)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff815eb207)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8162b5ed)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff81692951)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180cced)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff818277e4)
Location: include/linux/list.h:478
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
In drivers/scsi/scsi_lib.c (ffffffff8182c338)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81856e5d)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff81960790)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (ffffffff819c1f3f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff819f3033)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81a0a10f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7f0a)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81babd4b)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81bba0fc)
Location: include/linux/list.h:478
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
In kernel/sched/swait.c (ffffffff8111c5ef)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff811982b5)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff811b9a90)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff8126f409)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8127d70e)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff812b2f6b)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff812cc889)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff812d6411)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff81364aa2)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8139ce07)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff813adf05)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff813cf05c)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/io_uring.c (ffffffff813e5436)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_free
  - fs/io_uring.c:io_submit_sqes
```
```
In fs/locks.c (ffffffff814037c6)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/ext4/mballoc.c (ffffffff814745ef)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff814af1e5)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff814e6d2e)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff81509837)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In block/blk-core.c (ffffffff815ceb50)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff815d1fcc)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff815d9aec)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff815e0a8e)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81657717)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8169aabd)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff817084a1)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81897258)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff818b31a4)
Location: include/linux/list.h:478
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
In drivers/scsi/scsi_lib.c (ffffffff818b7ed8)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff818e56fd)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff81a091e0)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (ffffffff81a717bf)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81aa3e93)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81abc61f)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81b750ca)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff81c7da9b)
Location: include/linux/list.h:478
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_destroy_sock
```
```
In net/mptcp/pm_netlink.c (ffffffff81c89a8c)
Location: include/linux/list.h:478
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
In kernel/sched/build_utility.c (ffffffff8113d6ef)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff811c842e)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff811ecbe0)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff812be6ec)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff812d1d3f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8130e26b)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/slab_common.c (ffffffff8132b009)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff8133576e)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/migrate.c (ffffffff813b527c)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/zsmalloc.c (ffffffff813e2cc2)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8141fd57)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff81435089)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff81457e0f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/locks.c (ffffffff814756a6)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/ext4/mballoc.c (ffffffff814f663b)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff815362af)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff81574add)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff8159b42c)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In block/blk-core.c (ffffffff81679ded)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-ioc.c (ffffffff8167deaa)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff81687462)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8168f69d)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In io_uring/io_uring.c (ffffffff816c88cc)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff8176ef91)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff817bc251)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff818367dd)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0449)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff819fe354)
Location: include/linux/list.h:487
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
In drivers/scsi/scsi_lib.c (ffffffff81a03530)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81a369fb)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff81b71ae0)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (ffffffff81be3227)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81c1c892)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81c3702a)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81d048b8)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/pm_netlink.c (ffffffff81e32542)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff81e35184)
Location: include/linux/list.h:487
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
In kernel/sched/build_utility.c (ffffffff8116823f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff811abb20)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/cgroup/cgroup.c (ffffffff8120b41e)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81233160)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff813219ba)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8133ab2f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff8138135c)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/slab_common.c (ffffffff813a0459)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff813ac526)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/migrate.c (ffffffff8143578a)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/zsmalloc.c (ffffffff8146a22e)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff814ac267)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff814c30c9)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff814e715f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/locks.c (ffffffff81507b76)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/ext4/mballoc.c (ffffffff8159099b)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff815d47af)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff8161a8ed)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff8164477c)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In block/blk-core.c (ffffffff8173627d)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-ioc.c (ffffffff8173ab0a)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-mq.c (ffffffff817456c2)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8174e1cd)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In io_uring/io_uring.c (ffffffff817886af)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/kbuf.c (ffffffff8179ec9c)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff8189ea12)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff818d80c1)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff8196a94d)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5be34)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7c7f4)
Location: include/linux/list.h:487
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
In drivers/scsi/scsi_lib.c (ffffffff81b82050)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81bbb6db)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff81d0ed20)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (ffffffff81d8ee87)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81dcd922)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81dea89a)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec987b)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/pm_netlink.c (ffffffff8200a892)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff8200de14)
Location: include/linux/list.h:487
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
In kernel/sched/build_utility.c (ffffffff811788ff)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff811bda40)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/cgroup/cgroup.c (ffffffff81220991)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81249e00)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81351b48)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8136ba0f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff813b2710)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/slab_common.c (ffffffff813d3719)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff813e08c3)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/migrate.c (ffffffff8146b20a)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/zsmalloc.c (ffffffff8149f431)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff814e1037)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff814f84a9)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8151d9af)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/locks.c (ffffffff8153f1e6)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/ext4/mballoc.c (ffffffff815c7bab)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff8160c39f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff81652bed)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff8167cc5a)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In block/blk-core.c (ffffffff817728da)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-mq.c (ffffffff81781642)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff8178a6b2)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In io_uring/io_uring.c (ffffffff817c8d8f)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/kbuf.c (ffffffff817dfe8c)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff818e0fe2)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8191b391)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff819b0f0d)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81baf403)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81bd0574)
Location: include/linux/list.h:487
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
In drivers/scsi/scsi_lib.c (ffffffff81bd5d61)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81c12f3b)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/md.c (ffffffff81d65ec5)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/dm.c (ffffffff81d78300)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (0)
Location: include/linux/list.h:487
Inline: True
```
```
In net/core/dev.c (ffffffff81e3e531)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81e5c07a)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f283cb)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff82076521)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff820869f2)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_flush_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff8208aa74)
Location: include/linux/list.h:487
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/handshake/netlink.c (ffffffff8209228b)
Location: include/linux/list.h:487
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
In kernel/sched/build_utility.c (ffffffff8118661f)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:swake_up_all
```
```
In kernel/rcu/update.c (ffffffff811cdf60)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_trace_pregp_step
```
```
In kernel/cgroup/cgroup.c (ffffffff812386e1)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81263d10)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff81379028)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8139468f)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/vmscan.c (ffffffff813dbca1)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - mm/vmscan.c:evict_folios
  - mm/vmscan.c:shrink_folio_list
```
```
In mm/slab_common.c (ffffffff813fe119)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff8140b193)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_reparent_list_lrus
```
```
In mm/migrate.c (ffffffff8149a3ba)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
```
In mm/zsmalloc.c (ffffffff814ceb81)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff81515107)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8152cc29)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff81551f8f)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - fs/eventpoll.c:ep_send_events
```
```
In fs/locks.c (ffffffff815746c6)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/ext4/mballoc.c (ffffffff815ff80b)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_discard_work
```
```
In fs/ext4/fast_commit.c (ffffffff8164515f)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
  - fs/ext4/fast_commit.c:ext4_fc_cleanup
```
```
In fs/fuse/dev.c (ffffffff8168c1fd)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff816b902a)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - ipc/sem.c:__do_semtimedop
```
```
In block/blk-core.c (ffffffff817b4c7a)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - block/blk-core.c:__blk_flush_plug
```
```
In block/blk-mq.c (ffffffff817c3622)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_requeue_work
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff817cce12)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
```
In io_uring/io_uring.c (ffffffff8180dadf)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_overflow_kill
```
```
In io_uring/kbuf.c (ffffffff818242d1)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_refill_buffer_cache
  - io_uring/kbuf.c:io_destroy_buffers
```
```
In lib/irq_poll.c (ffffffff81927b52)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff819637c1)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff819fb3ed)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c03831)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81c251d4)
Location: include/linux/list.h:568
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
In drivers/scsi/scsi_lib.c (ffffffff81c2a9b6)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/ata/libata-eh.c (ffffffff81c6805b)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/md.c (ffffffff81e1d4e3)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_unlock
```
```
In drivers/md/dm.c (ffffffff81e2f530)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In drivers/interconnect/core.c (ffffffff81eb37c7)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
  - drivers/interconnect/core.c:path_find
```
```
In net/core/dev.c (ffffffff81efcde1)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81f1b45a)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81feccbb)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
```
In net/mptcp/protocol.c (ffffffff8214aeb3)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
```
In net/mptcp/pm_netlink.c (ffffffff8215bb72)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_flush_addrs_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_free_anno_list
```
```
In net/mptcp/pm_userspace.c (ffffffff82160644)
Location: include/linux/list.h:568
Inline: True
Inline callers:
  - net/mptcp/pm_userspace.c:mptcp_free_local_addr_list
```
```
In net/handshake/netlink.c (ffffffff82168b6b)
Location: include/linux/list.h:568
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
In kernel/sched/swait.c (ffff8000101594ec)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffff8000101d4068)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffff8000101f44c0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffff80001028a358)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffff80001029429c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffff8000102e77a8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffff8000102efafc)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffff800010374e70)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffff8000103b63f0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffff8000103ca6e4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffff8000103f0748)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffff800010404e20)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffff800010416a64)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffff800010503168)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffff800010524454)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffff8000105e4b28)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffff8000105e8bb8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffff8000105ebf4c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffff8000105ef448)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffff8000105f6c44)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffff800010667c94)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffff8000106dfff4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffff80001071dc34)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f824)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-aardvark.c (ffff800010720604)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-aardvark.c:advk_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffff800010723040)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffff8000107239ac)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (ffff800010724f98)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx-nwl.c:nwl_pcie_probe
```
```
In drivers/pci/controller/pcie-altera.c (ffff8000107275e0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/pci/controller/pcie-mobiveil.c (ffff80001072c7ec)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mobiveil.c:mobiveil_pcie_probe
```
```
In drivers/pci/controller/pci-xgene.c (ffff80001073a154)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_probe
```
```
In drivers/acpi/pci_root.c (ffff8000107744b0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080cd54)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095c440)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffff800010974968)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffff8000109798a8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffff8000109ad3a0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffff800010affda0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffff800010bd42c0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffff800010bf3b0c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffff800010c874d0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In arch/arm/kernel/bios32.c (c0311794)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - arch/arm/kernel/bios32.c:pci_common_init_dev
```
```
In kernel/sched/swait.c (c03a6784)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (c0416c94)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (c0434880)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (c04b99fc)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (c04c2670)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (c050b8d4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (c0513350)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (c05611ac)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (c059472c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (c05a6cc4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (c05c622c)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (c05d4808)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (c05e1d38)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/fuse/dev.c (c06bf398)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (c06df224)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (c0791d44)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (c07953cc)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (c0798558)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (c079bc60)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (c07a2424)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (c0810300)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (c087bcb0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (c08a6c98)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c08a84cc)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-mvebu.c (c08a9d80)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-mvebu.c:mvebu_pcie_probe
```
```
In drivers/pci/controller/pci-host-common.c (c08afd0c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c08b04c0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/pci/controller/pci-v3-semi.c (c08b17c0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-v3-semi.c:v3_pci_probe
```
```
In drivers/pci/controller/pcie-altera.c (c08b28bc)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-altera.c:altera_pcie_probe
```
```
In drivers/dma/ipu/ipu_idmac.c (c0929520)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/dma/tegra20-apb-dma.c (c092af18)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_free_chan_resources
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_desc_put
```
```
In drivers/scsi/scsi_error.c (c0a492ec)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (c0a4d604)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (c0a7ccf8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (c0bdf998)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (c0cefac8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (c0d0c100)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (c0d9688c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (c0000000001adb50)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (c00000000023f4b8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (c0000000002693e0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (c000000000335758)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (c00000000033fad0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (c0000000003a9584)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (c0000000003b4328)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (c000000000467504)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (c0000000004b2a48)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (c0000000004cc0a0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (c0000000004f7ea4)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (c00000000050d8a4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (c0000000005257c8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (c00000000064768c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (c00000000066e9b4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (c000000000778ac0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (c00000000077d7a4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (c000000000781504)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (c000000000786004)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (c00000000078f04c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (c00000000081d08c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (c000000000858d2c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (c00000000088ecb8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (c000000000891394)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-host-common.c (c000000000891724)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (c0000000008923b0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0d950)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (c000000000a2e904)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (c000000000a342b4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (c000000000a74590)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (c000000000bef1f0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (c000000000cb330c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (c000000000cd8df4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (c000000000d93fc4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffe0000ff58e)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffe00014d5fc)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffe000167774)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffe0001be430)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffe0001c40d2)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffe0001fd330)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffe000203628)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffe00024dd30)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffe0002790a4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffe0002888c6)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffe0002a3074)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffffffe0002b01c0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffffffe0002bd962)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffe00036feda)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffe000389192)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffe0004261ce)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffe000429570)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffe00042bd2e)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffe00042ecb4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffe000434472)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffe00049308a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffe0004b7f1e)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/controller/pcie-cadence-host.c (ffffffe0004e4a50)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-host.c:cdns_pcie_host_probe
```
```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e66ce)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-ftpci100.c:faraday_pci_probe
```
```
In drivers/pci/controller/pci-host-common.c (ffffffe0004e688c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pci-host-common.c:pci_host_common_probe
```
```
In drivers/pci/controller/pcie-xilinx.c (ffffffe0004e70a4)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-xilinx.c:xilinx_pcie_probe
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca756)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dd426)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0f38)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffe00060a77e)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffe0006edb16)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffe00075e224)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffe0007751de)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8900)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffff810ef2af)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b0af)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81177b16)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811fa55d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff812005d8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff81248d7a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff81250580)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff812c87df)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812fb5f7)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8130ce5d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8132b9f8)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffffffff8133b788)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffffffff8134c856)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff81418b69)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff81434be1)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff814df71d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814e2b8c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814e5a0c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814e8e7d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814eec7d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81552d07)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff81570dcd)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff815d856d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f3ef)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81725ad8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729d3c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/nvme/host/core.c (ffffffff817462be)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_remove_namespaces
```
```
In drivers/ata/libata-eh.c (ffffffff81766b4d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8184ff80)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff818d5d45)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff818f1be0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819747ad)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffff810df32f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff8114e399)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff8116acb6)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811ed2ad)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811f3328)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff8123bd24)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff8124350a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff812b981f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812ec217)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff812fda7d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8131bb98)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffffffff8132c468)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffffffff8133d536)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff814095e9)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff81425661)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff814d00bd)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814d351c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814d60b6)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814d93ed)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814df1bd)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81542fa1)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8155f52d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff815c215d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2e6f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff816fef08)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8170315c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/nvme/host/core.c (ffffffff81727f3e)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_remove_namespaces
```
```
In drivers/ata/libata-eh.c (ffffffff817469ad)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff81817590)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff8188fb8f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff818aba20)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8192e26d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffff810ec3df)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81158e7f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff811758e6)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff811f832d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff811fe3a8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff81246b1a)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff8124e320)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff812c65ef)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff812f93e7)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8130ac4d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff813294c8)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffffffff81339258)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffffffff8134a326)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff81414d09)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff81430d81)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff814db7ad)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814dec1c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814e1a9c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814e4f0d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff814ead0d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff8154ea47)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff815705fd)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff815db56d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174e1bf)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff817648a8)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768b0c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff8179690d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff8189f5b0)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff81926d75)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81942c10)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819def7d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
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
In kernel/sched/swait.c (ffffffff810f72af)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/sched/swait.c:swake_up_all
```
```
In kernel/cgroup/cgroup.c (ffffffff81165eef)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
```
In kernel/audit_tree.c (ffffffff81183426)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/audit_tree.c:replace_chunk
```
```
In kernel/bpf/offload.c (ffffffff812066a9)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
```
```
In kernel/events/core.c (ffffffff8120d408)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - kernel/events/core.c:perf_addr_filters_splice
```
```
In mm/slab_common.c (ffffffff8125633b)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_deactivate_kmem_caches
  - mm/slab_common.c:slab_caches_to_rcu_destroy_workfn
```
```
In mm/list_lru.c (ffffffff8125dc93)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_drain_all_list_lrus
```
```
In mm/zsmalloc.c (ffffffff812d7e5f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - mm/zsmalloc.c:async_free_zspage
```
```
In fs/namespace.c (ffffffff8130a707)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/namespace.c:namespace_unlock
```
```
In fs/fs-writeback.c (ffffffff8131c37f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/fs-writeback.c:queue_io
```
```
In fs/eventpoll.c (ffffffff8133a856)
Location: include/linux/list.h:446
Inline: True
```
```
In fs/io_uring.c (ffffffff8134ba9b)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/locks.c (ffffffff8135b106)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/locks.c:locks_move_blocks
```
```
In fs/fuse/dev.c (ffffffff8142b569)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
```
```
In ipc/sem.c (ffffffff8144743e)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - ipc/sem.c:do_semtimedop
```
```
In block/blk-core.c (ffffffff814f461d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-core.c:blk_flush_plug_list
```
```
In block/blk-ioc.c (ffffffff814f7a8c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-ioc.c:ioc_clear_queue
```
```
In block/blk-softirq.c (ffffffff814fa95c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-softirq.c:blk_softirq_cpu_dead
```
```
In block/blk-mq.c (ffffffff814fdd3d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify_dead
  - block/blk-mq.c:blk_mq_flush_plug_list
  - block/blk-mq.c:blk_mq_requeue_work
```
```
In block/blk-mq-sched.c (ffffffff81503ced)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
```
In lib/irq_poll.c (ffffffff81568897)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_cpu_dead
```
```
In drivers/pci/probe.c (ffffffff8158aadd)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/acpi/pci_root.c (ffffffff815f542d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_validate_resources
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8176963f)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff8177ff28)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178428c)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_evt_thread
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/ata/libata-eh.c (ffffffff817b077d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_error
```
```
In drivers/md/dm.c (ffffffff818bb810)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - drivers/md/dm.c:event_callback
```
```
In net/core/dev.c (ffffffff819483c5)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:netif_receive_skb_list_internal
```
```
In net/core/link_watch.c (ffffffff81964470)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/core/link_watch.c:__linkwatch_run_queue
  - net/core/link_watch.c:__linkwatch_run_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819e8c1d)
Location: include/linux/list.h:446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_tasklet_func
```
</details>
</li>
</ul>

## Differences
