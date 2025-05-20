# Function: <code>list_move_tail</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100e7de)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In kernel/workqueue.c (ffffffff81097de1)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/workqueue.c:pwq_activate_delayed_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
```
```
In kernel/sched/fair.c (ffffffff810bd522)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810c019e)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
  - kernel/sched/rt.c:task_tick_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810f3966)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup.c (ffffffff811131fd)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/cgroup.c:rebind_subsystems
```
```
In kernel/events/core.c (ffffffff81179a86)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/events/core.c:perf_group_detach
```
```
In mm/swap.c (ffffffff8119cb24)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/shmem.c (ffffffff811ab6d7)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/percpu.c (ffffffff811afff7)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffff811b921d)
Location: include/linux/list.h:165
Inline: True
```
```
In mm/hugetlb.c (ffffffff811dfacf)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/hugetlb.c:isolate_huge_page
  - mm/hugetlb.c:putback_active_hugepage
```
```
In fs/namespace.c (ffffffff8122d4a9)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
```
```
In fs/pnode.c (ffffffff8123d5e9)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff81242b68)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff8126cb51)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
```
```
In fs/ext4/extents_status.c (ffffffff812db47b)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff81310c0e)
Location: include/linux/list.h:165
Inline: True
```
```
In block/blk-flush.c (ffffffff813bd574)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-iopoll.c (ffffffff813c2448)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/blk-iopoll.c:blk_iopoll_softirq
```
```
In block/blk-mq.c (ffffffff813c6185)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_hctx_notify
```
```
In block/bsg.c (ffffffff813d58e4)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/bsg.c:bsg_rq_end_io
```
```
In block/blk-throttle.c (ffffffff813d9687)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In drivers/pci/probe.c (ffffffff81432148)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8143ee82)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff81547e32)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/core.c:devices_kset_move_last
  - drivers/base/core.c:device_move
```
```
In drivers/base/bus.c (ffffffff815496ba)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff8154fd6e)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff81559c2b)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_pm_move_before
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_prepare
```
```
In drivers/scsi/scsi_error.c (ffffffff815a95d4)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad4b5)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/usb/core/devio.c (ffffffff81619a05)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81633377)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81645c1c)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff817178f0)
Location: include/linux/list.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b0d31)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff817b8505)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff817c210c)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/events/intel/cqm.c (ffffffff8100e67d)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In kernel/workqueue.c (ffffffff8109df66)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810c0c96)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810c3d01)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff810faaad)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup.c (ffffffff8111ee9d)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/cgroup.c:rebind_subsystems
```
```
In kernel/events/core.c (ffffffff8118a4a2)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - kernel/events/core.c:perf_group_detach
```
```
In mm/swap.c (ffffffff811b3f47)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/shmem.c (ffffffff811c3f9c)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/percpu.c (ffffffff811c9217)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffff811d351d)
Location: include/linux/list.h:165
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fe25f)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff81255c5a)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
```
```
In fs/fs-writeback.c (ffffffff81261e8e)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff812656e9)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8126ae86)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff812989f3)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff8130ae05)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff81344fef)
Location: include/linux/list.h:165
Inline: True
```
```
In block/blk-flush.c (ffffffff81401499)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/bsg.c (ffffffff8141b5e4)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/bsg.c:bsg_rq_end_io
```
```
In block/blk-throttle.c (ffffffff8141f4ac)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff81461fed)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8147d983)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_create_root_bus
```
```
In drivers/pci/setup-bus.c (ffffffff8148acf9)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff81599d9e)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff8159b310)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff815a1b4e)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff815ad4ac)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/scsi/scsi_error.c (ffffffff81604c38)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81607bc8)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff81644917)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff81679c25)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81688b67)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168d0da)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168e92f)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816901d9)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169ce83)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816a674f)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff8177f8d7)
Location: include/linux/list.h:165
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181dc79)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81825924)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff8182f520)
Location: include/linux/list.h:165
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/events/intel/cqm.c (ffffffff8100e73d)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In kernel/workqueue.c (ffffffff810a2ad2)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810c6c7f)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810c9d6d)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110842d)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup.c (ffffffff8112722d)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/cgroup.c:rebind_subsystems
```
```
In kernel/events/core.c (ffffffff81199892)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:perf_group_detach
```
```
In mm/swap.c (ffffffff811c45d5)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/shmem.c (ffffffff811d409c)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/percpu.c (ffffffff811d92f7)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffff811e33cd)
Location: include/linux/list.h:178
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120ed2f)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff8126904a)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
```
```
In fs/fs-writeback.c (ffffffff8127538e)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff81278bc4)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8127dfb6)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff812ad470)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff81320e05)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff8135adb1)
Location: include/linux/list.h:178
Inline: True
```
```
In ipc/msg.c (ffffffff81370aa2)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff8141b0d5)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/bsg.c (ffffffff81436b24)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - block/bsg.c:bsg_rq_end_io
```
```
In block/blk-throttle.c (ffffffff8143aa6c)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff81480b9d)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8149ef6b)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff814ac4e9)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff815c8401)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff815c9870)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff815d026e)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff815dc26c)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8162247d)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/label.c (ffffffff816247e9)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff8163431a)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff816374ce)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff816759e7)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff816a7905)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b6d87)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816bb1ba)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bc9ef)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816be289)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816cafa3)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816d486f)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff817acb07)
Location: include/linux/list.h:178
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8184f4f9)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81857284)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81860fb2)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff8109fe4c)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/fair.c (ffffffff810c0876)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
```
In kernel/sched/rt.c (ffffffff810c4a90)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8110a6d3)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup/cgroup.c (ffffffff81126742)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/events/core.c (ffffffff811a1749)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - kernel/events/core.c:perf_group_detach
```
```
In mm/swap.c (ffffffff811cca26)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/shmem.c (ffffffff811dc85a)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/percpu.c (ffffffff811e2106)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffff811ed80e)
Location: include/linux/list.h:178
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121a5ce)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff812767f4)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
```
```
In fs/fs-writeback.c (ffffffff812828f8)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff81285f29)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8128bb5b)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff812ba923)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff812efdc7)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff8136ed51)
Location: include/linux/list.h:178
Inline: True
```
```
In ipc/msg.c (ffffffff81383e47)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff81429239)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/bsg.c (ffffffff81444364)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - block/bsg.c:bsg_rq_end_io
```
```
In block/blk-throttle.c (ffffffff8144870e)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff81489d8e)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff814a8dc5)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff814b6559)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff815dd0ce)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff815de5bb)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff815e4faa)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff815f0de5)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81636f93)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
```
In drivers/nvdimm/label.c (ffffffff81639535)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81646d3c)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164d135)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff8168a0fb)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff816bcaba)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cb0f7)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cf34f)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816d09cd)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d223e)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816df679)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff816e8d09)
Location: include/linux/list.h:178
Inline: True
```
```
In net/core/dev.c (ffffffff817cb28b)
Location: include/linux/list.h:178
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81873043)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff8187ae1e)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81885702)
Location: include/linux/list.h:178
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810a667a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810cc140)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8111587c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup/cgroup.c (ffffffff81132aa7)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In kernel/events/core.c (ffffffff811b52c9)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/events/core.c:perf_group_detach
```
```
In mm/swap.c (ffffffff811e1a46)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/shmem.c (ffffffff811f270b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/percpu.c (ffffffff811f80a7)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffff81203c67)
Location: include/linux/list.h:179
Inline: True
```
```
In mm/hugetlb.c (ffffffff8123573e)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff81299147)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
```
```
In fs/fs-writeback.c (ffffffff812a5438)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff812a89a9)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff812ae70b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff812de203)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff813148c7)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff8139394c)
Location: include/linux/list.h:179
Inline: True
```
```
In ipc/msg.c (ffffffff813a83e7)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814542f5)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/bsg.c (ffffffff81470c14)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/bsg.c:bsg_rq_end_io
```
```
In block/blk-throttle.c (ffffffff814752c6)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff814c6034)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff814e7df5)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff814f6219)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff816440ce)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff816455dd)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff8164c28a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff816583d6)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8169ec6c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816a1c05)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff816afd9c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b62b2)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff816f393d)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff8172848a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81737657)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173b99b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173d01d)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173e8c3)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174be0e)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817554f9)
Location: include/linux/list.h:179
Inline: True
```
```
In net/core/dev.c (ffffffff81844b1b)
Location: include/linux/list.h:179
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b586a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f3a55)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff818fb901)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819068b2)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810adb95)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810d37e2)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112202f)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup/cgroup.c (ffffffff8114117a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/swap.c (ffffffff81203162)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/shmem.c (ffffffff81213bb8)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/percpu.c (ffffffff81219387)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffff812247fb)
Location: include/linux/list.h:179
Inline: True
```
```
In mm/hugetlb.c (ffffffff8125868c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff812bfdd5)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/fs-writeback.c (ffffffff812cc30d)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff812cf59b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff812d769a)
Location: include/linux/list.h:179
Inline: True
```
```
In fs/mbcache.c (ffffffff8130a443)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff8134277b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff813c210b)
Location: include/linux/list.h:179
Inline: True
```
```
In ipc/msg.c (ffffffff813d7610)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff8148776a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/bsg.c (ffffffff814a4ec8)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/bsg.c:bsg_rq_end_io
```
```
In block/blk-throttle.c (ffffffff814a973f)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff814f6e02)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff815174ac)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff815271e7)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff8167f54c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff81680a5a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff81687871)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff81693e08)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816dad4b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816dcf7b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff816ec15d)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f27f8)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff81730271)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff817672da)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8177762f)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177bf7c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177d9bd)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177f225)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178cb78)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81795ad6)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff818981eb)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8190b0b2)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a35a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81952770)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff8195d8b4)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810b6295)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810dcb82)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112d74d)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup/cgroup.c (ffffffff8114cc2a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/swap.c (ffffffff81215b02)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/shmem.c (ffffffff81226b3a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/shmem.c:shmem_unuse
```
```
In mm/percpu.c (ffffffff8122c2e7)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffff8123778c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff8126cd5e)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff812d4ff3)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/fs-writeback.c (ffffffff812e125e)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff812e490b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff812eb9fd)
Location: include/linux/list.h:179
Inline: True
```
```
In fs/mbcache.c (ffffffff8131fc23)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff8135a24b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff813db90b)
Location: include/linux/list.h:179
Inline: True
```
```
In ipc/msg.c (ffffffff813f1c20)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814a18fe)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff814c456f)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff8150b372)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8152cf2c)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8153d087)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff8169f987)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff816a04ea)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff816a7291)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff816b4488)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816fcd02)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816ff2cb)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
```
In drivers/scsi/scsi_error.c (ffffffff8170fc9d)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff8171536a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff8175298e)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff8178b86a)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179d3ef)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a24e3)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a3f8f)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a5a0b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817b3378)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817bc1f6)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff818ba64b)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81937695)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c2da)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81985645)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819923f4)
Location: include/linux/list.h:179
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810bc109)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810e3b2a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff810f7c12)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81138149)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/cgroup/cgroup.c (ffffffff81158832)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/swap.c (ffffffff812254fc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/swap.c:lru_add_page_tail
```
```
In mm/percpu.c (ffffffff8123cdf8)
Location: include/linux/list.h:210
Inline: True
```
```
In mm/list_lru.c (ffffffff81248d37)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff81288182)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff812f24a8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/fs-writeback.c (ffffffff812ff9d4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff813030f9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8130d0ed)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffffffff8132e839)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffffffff81347494)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff8138329f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff81407c24)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffffffff8141df0e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814cf8c2)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff814f2d3f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff81539a80)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8155d4e8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8156c6ce)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffff816d80eb)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff816d941a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff816e0384)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff816ee1f7)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81736f33)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8173906f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff8174b4f4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750aff)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff81790873)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff817c9e8f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817dbfd1)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e1048)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e30d2)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e4dc9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ec83e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817fb400)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff818fcb0b)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8199cadc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e5609)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff819ef465)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819fda0c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810c23a5)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810ed2f9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/locking/rwsem.c (ffffffff81103a42)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81164490)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffff8124b248)
Location: include/linux/list.h:210
Inline: True
```
```
In mm/list_lru.c (ffffffff81257187)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff81297d82)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff81304065)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (ffffffff8130cd3a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff813148f3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff81316179)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff813200bd)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffffffff81341d5d)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffffffff8135f604)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff8139b77f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff814215f7)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffffffff81437d5e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814e8c22)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff8150c2df)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff8155a8a0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8157e55c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8158d6ae)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/iommu/iommu.c (ffffffff816db279)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff816fc1eb)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff816fd41a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff817045b3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff817121d7)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8175accd)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8175cdbf)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff8176f674)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774d42)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff817b4453)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff817fa9af)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180cef1)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81811f38)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81813fd2)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81815c89)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181d70e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8182c218)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff8192f11b)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d358e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c639)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81a26335)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81a345fc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810c9eb8)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810f788f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8110e599)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811754db)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:link_css_set
```
```
In mm/percpu.c (ffffffff81279475)
Location: include/linux/list.h:224
Inline: True
```
```
In mm/list_lru.c (ffffffff81285867)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff812cb443)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/page_reporting.c (ffffffff8130d138)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff8133b68d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:m_stop
```
```
In fs/libfs.c (ffffffff813466d6)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff8134ba3b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
```
```
In fs/pnode.c (ffffffff8134faca)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:umount_list
  - fs/pnode.c:umount_list
```
```
In fs/buffer.c (ffffffff8135a0ff)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/io_uring.c (ffffffff81384e29)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/io_uring.c:io_do_iopoll
  - fs/io_uring.c:io_iopoll_complete
```
```
In fs/mbcache.c (ffffffff813a51e0)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff813a9c92)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff813e6b46)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff81470893)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In ipc/msg.c (ffffffff81487d2e)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff81547cba)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff8156d73f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff815e414f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff81623a6e)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff816357b9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/iommu/iommu.c (ffffffff8178f54c)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff817b5afe)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff817b6d68)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff817be1ac)
Location: include/linux/list.h:224
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817cdb85)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a988)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8181c6e9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81832867)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81836cdd)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff818799ab)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff818cac3f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818ddec3)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e34d9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e5073)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6f59)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1eed)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ffddc)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81a0e23b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81abfe43)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0d9f9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17d57)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81b293fc)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106815c)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
```
```
In kernel/workqueue.c (ffffffff810c4ffb)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810f5a5f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8110b81a)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8117218b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:link_css_set
```
```
In mm/percpu.c (ffffffff81282e6d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_chunk_move
```
```
In mm/list_lru.c (ffffffff8128fb47)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/page_alloc.c (ffffffff812bb9a8)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff812d7063)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/migrate.c (ffffffff812f126d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_reporting.c (ffffffff81319088)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff8134752d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:m_stop
```
```
In fs/libfs.c (ffffffff81352bc6)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff8135895b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
```
```
In fs/pnode.c (ffffffff8135c794)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:umount_list
  - fs/pnode.c:umount_list
```
```
In fs/buffer.c (ffffffff8136821f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/io_uring.c (ffffffff8139a1df)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_do_iopoll
  - fs/io_uring.c:io_do_iopoll
  - fs/io_uring.c:io_iopoll_complete
```
```
In fs/mbcache.c (ffffffff813b5f40)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff813bb2e2)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff813f8e75)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff8148b17f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dax.c (ffffffff8149db8c)
Location: include/linux/list.h:224
Inline: True
```
```
In ipc/msg.c (ffffffff814a534e)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff815639da)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff81587d8f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff8160867f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff81bf778d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8165a879)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/iommu/iommu.c (ffffffff817ba0dc)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff817caf6e)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff817cba98)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff817d2efc)
Location: include/linux/list.h:224
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817e24e1)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81829aa8)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8182b739)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81843477)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff8184774d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff8188834b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff818d5d2f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e7d33)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ecd39)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ee543)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818f0019)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818fae12)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff819086ac)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81a05dab)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81acb8ae)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1bc09)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81b25e27)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81b37d2c)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810686ca)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/workqueue.c (ffffffff810c6938)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810f7b2f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8110d63a)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81173099)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffff81287f8e)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_chunk_move
```
```
In mm/list_lru.c (ffffffff812951a7)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/page_alloc.c (ffffffff812c0a05)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff812de653)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/migrate.c (ffffffff812f756d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_reporting.c (ffffffff8131f275)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff8134f83a)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
  - fs/namespace.c:m_stop
```
```
In fs/libfs.c (ffffffff81359c16)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff8135f35b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
```
```
In fs/pnode.c (ffffffff81363329)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8136ecdc)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/io_uring.c (ffffffff8139b102)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_do_iopoll
  - fs/io_uring.c:io_do_iopoll
```
```
In fs/mbcache.c (ffffffff813bd090)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff813c2415)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff813ff5a2)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff814911f3)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dax.c (ffffffff814a32fc)
Location: include/linux/list.h:224
Inline: True
```
```
In ipc/msg.c (ffffffff814ab2ee)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff8156c040)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff8158ebdf)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff815eb28f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff81be96a3)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8163cdc6)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (ffffffff81706ae6)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/iommu/iommu.c (ffffffff8179d939)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff817ae8de)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff817af408)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff817b690c)
Location: include/linux/list.h:224
Inline: True
```
```
In drivers/base/power/main.c (ffffffff817c68c1)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8180ccb8)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8180ea5b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81826540)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182acdd)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff8186afa4)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff818b927f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818c9c03)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818d0520)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1d43)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d37c9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddbd2)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff818ebe8c)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff819ec727)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6a63)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b098f9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81b134e9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81b259cc)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81072c03)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/workqueue.c (ffffffff810d95de)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/rt.c (ffffffff81112283)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8112ce8a)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811986b3)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_setup_root
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffff812ca436)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
```
```
In mm/list_lru.c (ffffffff812d5807)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/page_alloc.c (ffffffff81303966)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81325981)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In mm/migrate.c (ffffffff81341bda)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_reporting.c (ffffffff8136c690)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff8139db2c)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
  - fs/namespace.c:m_stop
```
```
In fs/libfs.c (ffffffff813a80b6)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff813adf6b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fs-writeback.c:wait_sb_inodes
```
```
In fs/pnode.c (ffffffff813b1b29)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff813c03af)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/io_uring.c (ffffffff813e9dce)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_do_iopoll
```
```
In fs/mbcache.c (ffffffff8140ce1b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff81411f55)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff81451bb2)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff814e8c92)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dax.c (ffffffff814fb368)
Location: include/linux/list.h:224
Inline: True
```
```
In ipc/msg.c (ffffffff815037ae)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff815d0574)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff815f4c3f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff816577bf)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff81ce4049)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff816ad826)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (ffffffff817823a6)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/iommu/iommu.c (ffffffff81826939)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff81837afb)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff81838668)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff8183fec5)
Location: include/linux/list.h:224
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81850c65)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81897223)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8189903b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff818b1e60)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b675d)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff818fa144)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff8194ed5f)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81962a49)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8196ac44)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196c763)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196e2c9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff819796f2)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8198859c)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81a9d649)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81b73b51)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bcc879)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd73e9)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81beb10b)
Location: include/linux/list.h:224
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810810a3)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/workqueue.c (ffffffff810f2a0c)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/build_policy.c (ffffffff8112f473)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8114e16d)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811c8798)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:link_css_set
```
```
In mm/percpu.c (ffffffff81326d55)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
```
```
In mm/list_lru.c (ffffffff81334f55)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/page_alloc.c (ffffffff8136b9ac)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff813945e4)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/migrate.c (ffffffff813b38b4)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_reporting.c (ffffffff813ea88c)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff81420b19)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
  - fs/namespace.c:m_stop
```
```
In fs/libfs.c (ffffffff8142bf18)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff814350ea)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff814369fd)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff81446581)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff81481dba)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff81487e7e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff814cee34)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff81576ad0)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dax.c (ffffffff8158b84f)
Location: include/linux/list.h:226
Inline: True
```
```
In ipc/msg.c (ffffffff815950b1)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff8167bd64)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff816a668e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff81e922be)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff8176f13a)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff81eaaa90)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff817d0c9b)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (ffffffff818b8dc6)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/iommu/iommu.c (ffffffff81965ebe)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff81979c95)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff8197aaaa)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff81983095)
Location: include/linux/list.h:226
Inline: True
```
```
In drivers/base/power/main.c (ffffffff819966d5)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff819e0410)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff819e2fb2)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff819fcee4)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff3a9)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81a4abea)
Location: include/linux/list.h:226
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81aa7dff)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81abced9)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac4fc2)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac6bd4)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac883c)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6de2)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5100)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81c16e89)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81d031ec)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d62586)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6de10)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81d8340f)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff81e230e8)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093773)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/workqueue.c (ffffffff81114cdc)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/build_policy.c (ffffffff81159223)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8117d0ed)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8120b793)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:link_css_set
```
```
In mm/vmscan.c (ffffffff8137b993)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
```
```
In mm/percpu.c (ffffffff8139ba10)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
```
```
In mm/list_lru.c (ffffffff813abcb5)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/page_alloc.c (ffffffff813e7cec)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff8141305e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/migrate.c (ffffffff814352b9)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_reporting.c (ffffffff81472a2c)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff814ad20b)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
  - fs/namespace.c:m_stop
```
```
In fs/libfs.c (ffffffff814b95f8)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff814c312a)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff814c4a5d)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff814d5671)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff81514a77)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff8151ba9e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff815676d4)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff8161c2a0)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dax.c (ffffffff816320bf)
Location: include/linux/list.h:226
Inline: True
```
```
In ipc/msg.c (ffffffff8163ddd1)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In security/device_cgroup.c (ffffffff816eea80)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-flush.c (ffffffff817385e4)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff8176569e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff8178f7a9)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
```
```
In io_uring/kbuf.c (ffffffff8179ebe8)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff8189eb1a)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff818d7f7b)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff818f1037)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (ffffffff81a06446)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/iommu/iommu.c (ffffffff81acf64e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff81ae6af2)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff81ae79da)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff81af1035)
Location: include/linux/list.h:226
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81b073dc)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5be00)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff81b5ec12)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7b174)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d9a9)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81bd1d2a)
Location: include/linux/list.h:226
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81c2eddf)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c46579)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4ef9a)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50d94)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c52bec)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61b62)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70d10)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81dd1229)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec81b5)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2d066)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81f396a0)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81f50aaf)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff81ff9e6b)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089cca)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810966f3)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/workqueue.c (ffffffff81121b9e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/build_policy.c (ffffffff811694e3)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8118dd9d)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81220d93)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:link_css_set
```
```
In mm/vmscan.c (ffffffff813adc48)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
```
```
In mm/percpu.c (ffffffff813ce9f0)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
```
```
In mm/list_lru.c (ffffffff813e005f)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/page_alloc.c (ffffffff8141cdcf)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81446665)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/migrate.c (ffffffff8146b1d2)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
```
```
In mm/page_reporting.c (ffffffff814a719b)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff814e1fec)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
  - fs/namespace.c:m_stop
```
```
In fs/libfs.c (ffffffff814ee5bb)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff814f850a)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff814f9edd)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff81508461)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff8154c486)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff81553d66)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff8159f8c0)
Location: include/linux/list.h:226
Inline: True
```
```
In fs/fuse/dev.c (ffffffff81654411)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dax.c (ffffffff8166abff)
Location: include/linux/list.h:226
Inline: True
```
```
In ipc/msg.c (ffffffff816762c1)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In security/device_cgroup.c (ffffffff81728f73)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-flush.c (ffffffff81775457)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - block/blk-flush.c:blk_insert_flush
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff817a475e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff817d0ae5)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
```
```
In io_uring/kbuf.c (ffffffff817dfdd8)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_add_buffers
```
```
In lib/irq_poll.c (ffffffff818e10ea)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8191b20f)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff81934454)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (ffffffff81a4f2d6)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/iommu/iommu.c (ffffffff81b1ec1e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff81b34f4e)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff81b361b4)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff81b3f195)
Location: include/linux/list.h:226
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81b5542c)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81baf3cf)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff81bb21bb)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81bc579a)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcee84)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd1749)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/spi/spi.c (ffffffff81c295a3)
Location: include/linux/list.h:226
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81c9603f)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cadb39)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb6546)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb82f6)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cba1ab)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8f00)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd82f0)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81e41e21)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f26c49)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8cb66)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81f99180)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81fb041f)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff820765de)
Location: include/linux/list.h:226
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81090de3)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_rename
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109dc63)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
```
In kernel/workqueue.c (ffffffff8112aa2b)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:pwq_activate_inactive_work
```
```
In kernel/sched/build_policy.c (ffffffff811766a3)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff8119c74d)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff81239f47)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:link_css_set
```
```
In mm/vmscan.c (ffffffff813d7060)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/vmscan.c:sort_folio
  - mm/vmscan.c:sort_folio
```
```
In mm/percpu.c (ffffffff813f9550)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_reclaim_populated
```
```
In mm/list_lru.c (ffffffff8140a90f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/page_alloc.c (ffffffff81449880)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/page_alloc.c:steal_suitable_fallback
  - mm/page_alloc.c:move_freepages_block
```
```
In mm/hugetlb.c (ffffffff81480103)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:isolate_hugetlb
```
```
In mm/migrate.c (ffffffff8149a169)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_pages_batch
  - mm/migrate.c:migrate_hugetlbs
  - mm/migrate.c:unmap_and_move_huge_page
  - mm/migrate.c:migrate_folio_undo_src
```
```
In mm/page_reporting.c (ffffffff814d819b)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_cycle
  - mm/page_reporting.c:page_reporting_cycle
```
```
In fs/namespace.c (ffffffff815160c6)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
```
```
In fs/fs-writeback.c (ffffffff8152cc8a)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff8152e822)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8153d211)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/mbcache.c (ffffffff815822b6)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/iomap/buffered-io.c (ffffffff81589d26)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_ioend_try_merge
```
```
In fs/ext4/extents_status.c (ffffffff815d8500)
Location: include/linux/list.h:307
Inline: True
```
```
In fs/fuse/dev.c (ffffffff8168eaa1)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dax.c (ffffffff816a4f3f)
Location: include/linux/list.h:307
Inline: True
```
```
In ipc/msg.c (ffffffff816b2681)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In security/device_cgroup.c (ffffffff8176a2d3)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
```
```
In block/blk-flush.c (ffffffff817b711f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff817e832e)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In io_uring/io_uring.c (ffffffff818143d5)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
```
```
In io_uring/kbuf.c (ffffffff81825072)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_provide_buffers
```
```
In lib/irq_poll.c (ffffffff81927c5a)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8196363f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8197d150)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (ffffffff81a9af76)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/iommu/iommu.c (ffffffff81b7525d)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff81b8c97e)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff81b8dbd4)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff81b97015)
Location: include/linux/list.h:307
Inline: True
```
```
In drivers/base/power/main.c (ffffffff81bad9ec)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c037fd)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff81c066ab)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a17a)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_timeline_signal
```
```
In drivers/scsi/scsi_error.c (ffffffff81c23aa4)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c263b9)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9b044)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_fb_release
```
```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca5d4f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modes.c:drm_connector_list_update
```
```
In drivers/gpu/drm/drm_modeset_helper.c (ffffffff81ccc62b)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_helper.c:drm_helper_move_panel_connectors_to_head
```
```
In drivers/spi/spi.c (ffffffff81cdbde3)
Location: include/linux/list.h:307
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81d4ab1f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d627e9)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_process_periodic_channels
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d6b299)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6d066)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6ef1b)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7dde0)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:sitd_link_urb
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:itd_link_urb
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8d300)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81f0086e)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81feb631)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205a4f6)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff820664e0)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff8207da7f)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
```
In net/mptcp/protocol.c (ffffffff8214af5e)
Location: include/linux/list.h:307
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
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
In kernel/workqueue.c (ffff800010120980)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffff80001014de94)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/locking/rwsem.c (ffff800010169344)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffff8000101d5d90)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffff8000102e1474)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffff8000102eebb8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffff800010336190)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffff8000103b785c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (ffff8000103c1fa4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffff8000103ca73c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffff8000103ccb2c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffff8000103d8c6c)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffff800010402840)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffff80001042525c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffff80001046e3ec)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffff800010504438)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffff80001051ec84)
Location: include/linux/list.h:210
Inline: True
```
```
In block/blk-flush.c (ffff8000105e6bc4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffff800010610334)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffff800010667d5c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffff8000106dfe68)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffff8000106f29b0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (ffff8000107fe44c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_dma_desc_free_list
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/mv_xor.c (ffff800010806e78)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/iommu/iommu.c (ffff8000108c7220)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffff8000108e6aec)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffff8000108e9364)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffff8000108f0020)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffff800010902d58)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffff80001095c40c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffff80001095e690)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffff800010972938)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffff800010978be8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffff8000109c38f8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffff800010a2cc3c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a457f0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b320)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4d1fc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4ebe0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a57880)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffff800010a67b08)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffff800010bcbf68)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/core/dev.c:unregister_netdevice_queue
```
```
In net/ipv4/tcp_output.c (ffff800010c8615c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdc2e4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5dbc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffff800010cf4c40)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (c03748c4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (c039c9e8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/locking/rwsem.c (c03b5440)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (c0418884)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (c05063a4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (c0512a3c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In fs/namespace.c (c0594e88)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:do_umount
```
```
In fs/libfs.c (c059ddc4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (c05a6d10)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (c05a868c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (c05b1ae8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/io_uring.c (c05d58bc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (c05eddc8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (c062f9a0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (c06c0a9c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In ipc/msg.c (c06daea0)
Location: include/linux/list.h:210
Inline: True
```
```
In block/blk-flush.c (c0793910)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (c07ba5b0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (c081040c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (c087bb04)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (c088d4c8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/dma/virt-dma.c (c091f8a0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/dma/virt-dma.c:vchan_dma_desc_free_list
  - drivers/dma/virt-dma.c:vchan_tx_submit
```
```
In drivers/dma/mv_xor.c (c0924a68)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_free_chan_resources
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_xor_tx_submit
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/tegra20-apb-dma.c (c092b68c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:handle_cont_sngl_cycle_dma_done
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_abort_all
```
```
In drivers/iommu/iommu.c (c09be1e0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (c09d5070)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (c09d644c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (c09dde0c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (c09ed010)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/scsi/scsi_error.c (c0a4718c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (c0a4caa4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (c0ab17b0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (c0b01a5c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (c0b18014)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1d670)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (c0b1f3b8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (c0b20ce8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (c0b2a3a0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (c0b3b4e0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In drivers/usb/musb/musb_host.c (c0b6bfc4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_bulk_nak_timeout
  - drivers/usb/musb/musb_host.c:musb_bulk_nak_timeout
```
```
In sound/core/timer.c (c0c8c140)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - sound/core/timer.c:snd_timer_start1
  - sound/core/timer.c:snd_timer_close_locked
  - sound/core/timer.c:snd_timer_open
  - sound/core/timer.c:snd_timer_open
```
```
In net/core/dev.c (c0ce9fe4)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d95410)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (c0de2488)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (c0dece5c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (c0dfb8a0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (c00000000016905c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (c0000000001a09d4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/locking/rwsem.c (c0000000001c0cdc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (c00000000024174c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
  - kernel/cgroup/cgroup.c:link_css_set
```
```
In mm/percpu.c (c0000000003a1e90)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (c0000000003b2d40)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (c00000000041097c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (c0000000004b4448)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (c0000000004c006c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (c0000000004cc0fc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (c0000000004ce584)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (c0000000004dc548)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_dirty_inode
```
```
In fs/io_uring.c (c00000000050bf54)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (c0000000005344ac)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (c00000000058e5b8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (c000000000648fdc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In ipc/msg.c (c0000000006683e8)
Location: include/linux/list.h:210
Inline: True
```
```
In block/blk-flush.c (c00000000077b418)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (c0000000007ad518)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (c00000000081d234)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (c000000000858aec)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (c0000000008707d4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/iommu/iommu.c (c00000000096d9a0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (c00000000097ca9c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (c00000000097ec5c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (c000000000989f48)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (c0000000009a1308)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (c000000000a0d914)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (c000000000a105bc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (c000000000a2c01c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (c000000000a33580)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (c000000000a89034)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (c000000000ae9320)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (c000000000b09348)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b11e30)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (c000000000b14760)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (c000000000b16cc8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b25514)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (c000000000b3a5d4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (c000000000ca89a4)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d9248c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (c000000000df90c0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (c000000000e06fc0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (c000000000e1aca0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffe0000d9730)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffe0000f6b50)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/locking/rwsem.c (ffffffe00010a96e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffe00014efaa)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffe0001f8de0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_relocate
```
```
In mm/list_lru.c (ffffffe000202ae6)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffe0002321fa)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffe00027a34c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (ffffffe000281d08)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffe00028891c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffe00028a044)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffe000291792)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffffffe0002ae2ce)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffffffe0002c43f0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffe0002fb35c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffe00037106e)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffffffe000385d9a)
Location: include/linux/list.h:210
Inline: True
```
```
In block/blk-flush.c (ffffffe000427cde)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffe000447d1e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffe00049317a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffe0004b7d96)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffe0004c5d10)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/base/core.c (ffffffe00057b414)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffe00057c8d4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffe0005829b0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca726)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffe0005cc52e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffe0005db942)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0688)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffe000616c7e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffe00064d410)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000662246)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe00066805c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000669cb8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066b720)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000672ca6)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000682536)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffe000759826)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7826)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffe000828de4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffe000832270)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffe000840906)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810bc715)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810e8eea)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff810fcd52)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8115cab0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffff81243898)
Location: include/linux/list.h:210
Inline: True
```
```
In mm/list_lru.c (ffffffff8124f7d7)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff81290362)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff812fc645)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (ffffffff8130531a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff8130ced3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff8130e759)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8131869d)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffffffff8133a33d)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffffffff81357be4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff81393d5f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff81419bd7)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffffffff8143033e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814e1202)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff815048bf)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff81552e80)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff81572a7c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8158152e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/iommu/iommu.c (ffffffff816a0cc9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff816c19db)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff816c2c0a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff816c9d03)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff816d8557)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8170f3bd)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff817114af)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81723d64)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729432)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/nvme/host/core.c (ffffffff817461e2)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_remove_invalid_namespaces
```
```
In drivers/spi/spi.c (ffffffff81778f33)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff817b2d8f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c52d1)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817ca318)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cc3b2)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817ce069)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d5aee)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff817e45f8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff818cf11b)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819733fe)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbcc9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff819c59c5)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff819d3c8c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810aaf8f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810d65f9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/locking/rwsem.c (ffffffff810ecf62)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8114fda0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffff81236868)
Location: include/linux/list.h:210
Inline: True
```
```
In mm/list_lru.c (ffffffff81242777)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff81281ff2)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff812ed265)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (ffffffff812f5f3a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff812fdaf3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff812ff369)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8130928d)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffffffff8132b04d)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffffffff81348894)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff813847ef)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff8140a657)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffffffff81420dbe)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814d1b92)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff814f4d7f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff8154309f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff815611dc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8157030e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/acpi/nfit/core.c (ffffffff815f8ce3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_init
  - drivers/acpi/nfit/core.c:acpi_nfit_scrub
```
```
In drivers/iommu/iommu.c (ffffffff8167e6b9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff8169cc8b)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff8169deba)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff816a5033)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff816b2bb7)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2e3d)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff816e4f2f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff816fd194)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff8170285c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff817123f6)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_timeout_deleted_rport
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_add
```
```
In drivers/nvme/host/core.c (ffffffff81727e62)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_remove_invalid_namespaces
```
```
In drivers/spi/spi.c (ffffffff81758ce3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff817a47bf)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In net/core/dev.c (ffffffff8188923b)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192cece)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978ab9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff819827b5)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81990a4c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810bbc75)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810e3829)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:requeue_rt_entity
```
```
In kernel/locking/rwsem.c (ffffffff810f9f12)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff8115a880)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffff81241638)
Location: include/linux/list.h:210
Inline: True
```
```
In mm/list_lru.c (ffffffff8124d577)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff8128e172)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff812fa435)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (ffffffff8130310a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff8130acc3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff8130c549)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff8131616d)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffffffff81337e0d)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffffffff813556b4)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff813916bf)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff81415d77)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffffffff8142c4de)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814dd292)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff8150094f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff8154ebc0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff815722ac)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff815813fe)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/iommu/iommu.c (ffffffff816cef39)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff816efeab)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff816f10da)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff816f8273)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff81705e97)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8174e18d)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8175027f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff81762b34)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81768202)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff817a92d3)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff817ef82f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81801d71)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81806db8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81808e52)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8180ab09)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181258e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81821098)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff8192011b)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819ddbce)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a26749)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81a30445)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81a3e70c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
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
In kernel/workqueue.c (ffffffff810c44ad)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:pwq_activate_delayed_work
```
```
In kernel/sched/rt.c (ffffffff810f0a7e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/sched/rt.c:task_tick_rt
  - kernel/sched/rt.c:yield_task_rt
```
```
In kernel/locking/rwsem.c (ffffffff81105082)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_mark_wake
```
```
In kernel/cgroup/cgroup.c (ffffffff811678e0)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:rebind_subsystems
```
```
In mm/percpu.c (ffffffff81250db8)
Location: include/linux/list.h:210
Inline: True
```
```
In mm/list_lru.c (ffffffff8125d0f7)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/list_lru.c:__list_lru_walk_one
```
```
In mm/hugetlb.c (ffffffff8129df12)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:isolate_huge_page
```
```
In fs/namespace.c (ffffffff8130b771)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/namespace.c:ksys_umount
```
```
In fs/libfs.c (ffffffff813141cd)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/libfs.c:dcache_readdir
```
```
In fs/fs-writeback.c (ffffffff8131c3fd)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
```
In fs/pnode.c (ffffffff8131dd79)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
  - fs/pnode.c:propagate_umount
```
```
In fs/buffer.c (ffffffff81327e9f)
Location: include/linux/list.h:210
Inline: True
```
```
In fs/io_uring.c (ffffffff8134ccae)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/mbcache.c (ffffffff81368c9f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
```
```
In fs/ext4/extents_status.c (ffffffff813a554c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_shrink
```
```
In fs/fuse/dev.c (ffffffff8142caf2)
Location: include/linux/list.h:210
Inline: True
```
```
In ipc/msg.c (ffffffff8144382e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - ipc/msg.c:ss_wakeup
```
```
In block/blk-flush.c (ffffffff814f60f2)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In block/blk-throttle.c (ffffffff8151978f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
```
In lib/irq_poll.c (ffffffff81568a10)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - lib/irq_poll.c:irq_poll_softirq
```
```
In drivers/pci/probe.c (ffffffff8158c78c)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_register_host_bridge
```
```
In drivers/pci/setup-bus.c (ffffffff8159b8ae)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
```
In drivers/iommu/iommu.c (ffffffff816e94a9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
```
In drivers/base/core.c (ffffffff8170a6e9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:devices_kset_move_last
```
```
In drivers/base/bus.c (ffffffff8170b91a)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_sort_breadthfirst
  - drivers/base/bus.c:bus_sort_breadthfirst
```
```
In drivers/base/devres.c (ffffffff81712b13)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/devres.c:release_nodes
  - drivers/base/devres.c:release_nodes
```
```
In drivers/base/power/main.c (ffffffff81720862)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_prepare
  - drivers/base/power/main.c:dpm_resume
  - drivers/base/power/main.c:dpm_resume_early
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:device_pm_move_last
  - drivers/base/power/main.c:device_pm_move_before
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff8176960d)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
```
```
In drivers/nvdimm/label.c (ffffffff8176b6ff)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
```
```
In drivers/scsi/scsi_error.c (ffffffff8177e194)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81783943)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
```
In drivers/spi/spi.c (ffffffff817c3163)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_replace_transfers
```
```
In drivers/usb/core/devio.c (ffffffff81809a6f)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:destroy_async_on_interface
  - drivers/usb/core/devio.c:async_completed
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181be81)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_queue_transaction
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_select_transactions
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81820ec6)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81822f62)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_deactivate
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81824c19)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_complete_xfer_ddma
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182d05e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:sitd_submit
  - drivers/usb/host/ehci-hcd.c:itd_submit
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff8183b4f8)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_unlink_qh
```
```
In net/core/dev.c (ffffffff81941e7b)
Location: include/linux/list.h:210
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e784e)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_update_skb_after_send
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31bf9)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_walk
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3bd45)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_walk
```
```
In net/unix/garbage.c (ffffffff81a4a1cc)
Location: include/linux/list.h:210
Inline: True
Inline callers:
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
  - net/unix/garbage.c:unix_gc
```
</details>
</li>
</ul>

## Differences
