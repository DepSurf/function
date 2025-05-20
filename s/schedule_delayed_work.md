# Function: <code>schedule_delayed_work</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100deb4)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In arch/x86/kernel/tsc.c (ffffffff81f68fdc)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81065326)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810ccb75)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/kprobes.c (ffffffff8112d77b)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/jump_label.c (ffffffff8118afa7)
Location: include/linux/workqueue.h:585
Inline: True
```
```
In mm/vmstat.c (ffffffff811ad1b4)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:setup_vmstat
```
```
In fs/file_table.c (ffffffff8120e3b1)
Location: include/linux/workqueue.h:585
Inline: True
```
```
In fs/namespace.c (ffffffff8122d013)
Location: include/linux/workqueue.h:585
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81f8f04f)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/pci.c (ffffffff81435673)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473502)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/xen/grant-table.c (ffffffff814c5e5a)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff814c6776)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff814d32bd)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:selfballoon_process
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
```
```
In drivers/base/devcoredump.c (ffffffff8156ca50)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (ffffffff815da31b)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/net/virtio_net.c (ffffffff815f1f31)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_restore
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8166f9e5)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In net/core/dst.c (ffffffff81724099)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - net/core/dst.c:dst_gc_task
```
```
In net/core/link_watch.c (ffffffff81730680)
Location: include/linux/workqueue.h:585
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738de3)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/inetpeer.c (ffffffff81757ec2)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
```
```
In net/rfkill/input.c (ffffffff81812593)
Location: include/linux/workqueue.h:585
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/events/intel/cqm.c (ffffffff8100ed4d)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In arch/x86/kernel/tsc.c (ffffffff81036c3a)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810651ed)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810d1634)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/kprobes.c (ffffffff811367bb)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811926be)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8119d667)
Location: include/linux/workqueue.h:586
Inline: True
```
```
In mm/vmstat.c (ffffffff81fb1fd1)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff81234dd4)
Location: include/linux/workqueue.h:586
Inline: True
```
```
In fs/namespace.c (ffffffff812557b0)
Location: include/linux/workqueue.h:586
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81fb9651)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/pci.c (ffffffff81480fc1)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1ac7)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff815164ea)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81516f64)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff81524386)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/devcoredump.c (ffffffff815c1ef0)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (ffffffff81633ed4)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/net/virtio_net.c (ffffffff81653e59)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816cfd46)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In net/core/dst.c (ffffffff8178db16)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - net/core/dst.c:dst_gc_task
```
```
In net/core/link_watch.c (ffffffff8179adf0)
Location: include/linux/workqueue.h:586
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a5520)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/inetpeer.c (ffffffff817c4201)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/rfkill/input.c (ffffffff81885473)
Location: include/linux/workqueue.h:586
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/events/intel/cqm.c (ffffffff8100ee0d)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In arch/x86/kernel/tsc.c (ffffffff8103696a)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8106871d)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810d8094)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/kprobes.c (ffffffff8114053b)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811a1e98)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811ad087)
Location: include/linux/workqueue.h:600
Inline: True
```
```
In mm/vmstat.c (ffffffff81feea20)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff81247984)
Location: include/linux/workqueue.h:600
Inline: True
```
```
In fs/namespace.c (ffffffff81268ba0)
Location: include/linux/workqueue.h:600
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81ff5fc2)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/pci.c (ffffffff814a2681)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3ab7)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8154295a)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff815433bb)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff81550846)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/devcoredump.c (ffffffff815f1340)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (ffffffff81665024)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816fdc26)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In net/core/dst.c (ffffffff817bb3e6)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - net/core/dst.c:dst_gc_task
```
```
In net/core/link_watch.c (ffffffff817c8b90)
Location: include/linux/workqueue.h:600
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d3f8f)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d21)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/rfkill/input.c (ffffffff818b9ce3)
Location: include/linux/workqueue.h:600
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/kernel/tsc.c (ffffffff81034c44)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81067a3d)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810d70d0)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff810f8f51)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff811418cc)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811a964e)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811b4529)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In mm/vmstat.c (ffffffff820d0a93)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812531b0)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In fs/namespace.c (ffffffff812762e7)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In fs/fs-writeback.c (ffffffff820d875c)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef8a8)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8155681c)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff8155724b)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff81564fc1)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/devcoredump.c (ffffffff8160549f)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (ffffffff816797c1)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81713546)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In net/core/link_watch.c (ffffffff817e7767)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f32ff)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/inetpeer.c (ffffffff81814101)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/rfkill/input.c (ffffffff818e06f3)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/kernel/tsc.c (ffffffff81036f9a)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8106bccd)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810df070)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff81103984)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff8114e67c)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811bcea3)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811c8347)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In mm/vmstat.c (ffffffff826d94a3)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812752b3)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In fs/namespace.c (ffffffff81298c3a)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In fs/fs-writeback.c (ffffffff826e1456)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8152442b)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff815ba329)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff815bb25b)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff815c9151)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/devcoredump.c (ffffffff8166d8a6)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (ffffffff816e2e2f)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81784786)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In net/core/link_watch.c (ffffffff818626a7)
Location: include/linux/workqueue.h:602
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186e682)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/rfkill/input.c (ffffffff81966403)
Location: include/linux/workqueue.h:602
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81a01bfb)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff826dc9a7)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8106eb06)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810e76c0)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff8110bf0f)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff8115cf7f)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811dd08c)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811e874a)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In mm/vmstat.c (ffffffff8270394d)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff8129bb43)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In fs/namespace.c (ffffffff812bee29)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8270ca83)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a178)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff815f2179)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff815f38fb)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff816019d5)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/devcoredump.c (ffffffff816a92b0)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (ffffffff8171f66a)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c5856)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcc9e)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In net/core/link_watch.c (ffffffff818ae39b)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In net/core/netpoll.c (ffffffff818bf816)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/rfkill/input.c (ffffffff819bfd0b)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01c0b)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff82892d59)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81074b12)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810ef654)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/power/qos.c (ffffffff810f2cc0)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff811176ff)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81169e44)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811ed48c)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811f9412)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In mm/vmstat.c (ffffffff828bb076)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812b0e73)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In fs/namespace.c (ffffffff812d40f9)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In fs/fs-writeback.c (ffffffff828c3ca9)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815509b9)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571a88)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8160d0d9)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff8160e91b)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff8161cac8)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/dd.c (ffffffff816a254f)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff816c9ea9)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff816d04f8)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81741f5a)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ece26)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff8180466c)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In net/core/link_watch.c (ffffffff818d261b)
Location: include/linux/workqueue.h:625
Inline: True
```
```
In net/core/netpoll.c (ffffffff818e863c)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/rfkill/input.c (ffffffff819f6eab)
Location: include/linux/workqueue.h:625
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dd3)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828aa388)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810786d8)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810f6a65)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff810fb164)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff81121a01)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81176b88)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81204ef2)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121136d)
Location: include/linux/workqueue.h:603
Inline: True
```
```
In mm/vmstat.c (ffffffff828d24eb)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812cd899)
Location: include/linux/workqueue.h:603
Inline: True
```
```
In fs/namespace.c (ffffffff812f1138)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828dd09b)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81580c88)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a1f70)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81640893)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff816426b6)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/base/dd.c (ffffffff816db25f)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff81705442)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff8170bfd1)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff8177db85)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182d9e6)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff81845cc5)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:603
Inline: True
```
```
In drivers/ras/cec.c (ffffffff829111d4)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff8191f8a9)
Location: include/linux/workqueue.h:603
Inline: True
```
```
In net/core/xdp.c (ffffffff81930d07)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/netpoll.c (ffffffff81937d4c)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff8194d481)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffff81a663eb)
Location: include/linux/workqueue.h:603
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01df3)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828ad3eb)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81079728)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff811027f5)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff81107194)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff8112e021)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81182abf)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81211ae2)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121ee3d)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In mm/vmstat.c (ffffffff828da95d)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812df2b9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (ffffffff81302cd8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828e580d)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a28c1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c2df0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81663253)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81664c7c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff829009b6)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff816ff22f)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff817296d2)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff817302d1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff817a1995)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185f316)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff818775e5)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In drivers/ras/cec.c (ffffffff8291af6b)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81951ae9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (ffffffff8196781f)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (ffffffff8196ac0c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81982dd1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffff81a9cf0b)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102faa6)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f0f2)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
```
```
In arch/x86/kernel/check.c (ffffffff81080b09)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff8110d400)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/tree.c (ffffffff811341d8)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff8113c9f7)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81195b8f)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81239ea8)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff8124abbd)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff82cf8bd6)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff8130cff0)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff8131611b)
Location: include/linux/workqueue.h:623
Inline: True
```
```
In fs/namespace.c (ffffffff8133c68f)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff81349192)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
Direct callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff8151cd65)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164b55a)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d400)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8171270b)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81714480)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff82d17c9d)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff817b8e5f)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff817e5f02)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff817ed841)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81865794)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f64a9)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819326a6)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:623
Inline: False
```
```
In drivers/ras/cec.c (ffffffff82d2c9c9)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81a22849)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81a3adf0)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81a3e70c)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81a5ae71)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffff81b9883b)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
```
**Symbols:**

```
ffffffff8103eb80-ffffffff8103eba1: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
ffffffff8134edd2-ffffffff8134edf3: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff810306d6)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f1b2)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
```
```
In arch/x86/kernel/check.c (ffffffff81bd829a)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff8110a43d)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/tree.c (ffffffff8112fc4f)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff81137107)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81192837)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81243520)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff812552fd)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff82fe58ae)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff81318f40)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff813212b1)
Location: include/linux/workqueue.h:623
Inline: True
```
```
In fs/namespace.c (ffffffff8134853c)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff813560f7)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
Direct callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff81539c05)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bfbeb0)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168db20)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8172f49b)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff817316c0)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff83005916)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff817cdbcf)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff817fab92)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81802171)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81874594)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818ff059)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81939906)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:623
Inline: False
```
```
In drivers/ras/cec.c (ffffffff8301b434)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81a22ba9)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81a3d210)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81a414ac)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81a66716)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffff81ba850b)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
```
**Symbols:**

```
ffffffff8103ec30-ffffffff8103ec51: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
ffffffff81bea894-ffffffff81bea8b5: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff810311c6)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff81040c9f)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
```
```
In arch/x86/kernel/check.c (ffffffff81bca095)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff8110c01c)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/tree.c (ffffffff8113017f)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff81137ddb)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81193721)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff812484d4)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff812597fd)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff831f0073)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff8131f130)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff8132771b)
Location: include/linux/workqueue.h:623
Inline: True
```
```
In fs/namespace.c (ffffffff8134e907)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff8135cce7)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
Direct callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff815420a5)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bedd28)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81670810)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81712eeb)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff817150c0)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff832104bd)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff817b15e8)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff817df8b2)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff817e6e6a)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81856d72)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e27bc)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191d026)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:623
Inline: False
```
```
In drivers/ras/cec.c (ffffffff8322655f)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81a09ed9)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81a24030)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81a2611c)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81a46c66)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv6/mcast.c (ffffffff81b5ef27)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/rfkill/input.c (ffffffff81b9769b)
Location: include/linux/workqueue.h:623
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
```
**Symbols:**

```
ffffffff810404e0-ffffffff81040501: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
ffffffff81bdc8a9-ffffffff81bdc8ca: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81036416)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff81046d8f)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
```
```
In arch/x86/kernel/check.c (ffffffff81c9f3a4)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81ca5776)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/sched/psi.c (ffffffff8112ad56)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/tree.c (ffffffff81155712)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff8115ab2b)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff811bc279)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff8128285d)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff8129554a)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff832d5887)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff8136c513)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff81374d1b)
Location: include/linux/workqueue.h:617
Inline: True
```
```
In fs/namespace.c (ffffffff8139c94a)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff813ab0c7)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
Direct callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
```
```
In fs/io_uring.c (ffffffff813deed4)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_task_work_add
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff815a2015)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81ce8b03)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e4ae0)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8178f9ab)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff832f9542)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff817b2600)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/base/dd.c (ffffffff8183a845)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff8186b33a)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff818731e2)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff818e55d2)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e8cc)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bf9f6)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/ras/cec.c (ffffffff833108af)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81abc3d9)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81ad8600)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81adae8c)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81b01a66)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv6/mcast.c (ffffffff81c266cc)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/rfkill/input.c (ffffffff81c6418b)
Location: include/linux/workqueue.h:617
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
```
**Symbols:**

```
ffffffff81046350-ffffffff81046371: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
ffffffff81cc411f-ffffffff81cc4140: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8103c256)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8104f952)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
Direct callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
```
```
In arch/x86/kernel/check.c (ffffffff81e4eb46)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81e55015)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/sched/build_utility.c (ffffffff8113f90e)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/rcu/tree.c (ffffffff8117f2c4)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff811843de)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff811efae7)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff812ce1ae)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff812eb33d)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff8348a0e0)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff813eadbf)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff813f36c3)
Location: include/linux/workqueue.h:666
Inline: True
```
```
In fs/namespace.c (ffffffff8141f844)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff81431eec)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
Direct callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff81648465)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In io_uring/io_uring.c (ffffffff816ca4ce)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81eafb9f)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f582)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff818c7f18)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff834b1d15)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff818ede52)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/base/dd.c (ffffffff8197d0a5)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/devcoredump.c (ffffffff819b409b)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb458)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81a368e0)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ada029)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b20562)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9f196)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/ras/cec.c (ffffffff834ca558)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81c36ea7)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81c594c9)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81c5c34e)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81c810a6)
Location: include/linux/workqueue.h:666
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devl_port_register
```
```
In net/rfkill/input.c (ffffffff81e06df7)
Location: include/linux/workqueue.h:666
Inline: True
```
**Symbols:**

```
ffffffff8104efc0-ffffffff8104efef: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
ffffffff81e76a21-ffffffff81e76a50: schedule_delayed_work.constprop.0.isra.0 (STB_LOCAL)
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
In arch/x86/hyperv/hv_init.c (ffffffff81044da6)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff83e78f11)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810b9253)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81127a99)
Location: include/linux/workqueue.h:667
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8116a471)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/livepatch/transition.c (ffffffff811bf688)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81236537)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81335b53)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff813553ed)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff83eba9dc)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff81472f8c)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff8147c483)
Location: include/linux/workqueue.h:667
Inline: True
```
```
In fs/namespace.c (ffffffff814abd77)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff83ec9495)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff81701155)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In io_uring/io_uring.c (ffffffff81789b0b)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fallback_tw
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f187)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e32f)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81a194d8)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff83eec0f5)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a459ec)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/base/dd.c (ffffffff81aea435)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/devcoredump.c (ffffffff81b28f2c)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30988)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81bbb5c4)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c651c9)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb2892)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccffcd)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_acquire_i2c_bus
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d40b76)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/ras/cec.c (ffffffff83f0c212)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81dea4c7)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81e0f455)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81e12a2b)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81e3e151)
Location: include/linux/workqueue.h:667
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devl_port_register
```
```
In net/rfkill/input.c (ffffffff81fdc1e7)
Location: include/linux/workqueue.h:667
Inline: True
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
In arch/x86/hyperv/hv_init.c (ffffffff81044ee6)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8369b60d)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810bc423)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81134f39)
Location: include/linux/workqueue.h:670
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8117ab90)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/livepatch/transition.c (ffffffff811d2168)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff8124d357)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff813668a3)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff813868dd)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff836dffec)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff814a76fa)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff814b1003)
Location: include/linux/workqueue.h:670
Inline: True
```
```
In fs/namespace.c (ffffffff814e0b37)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff836ee505)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff8173b1f5)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In io_uring/io_uring.c (ffffffff817cbb75)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fallback_tw
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952817)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8198281e)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81a623f8)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff83711de5)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a8fb9a)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/base/dd.c (ffffffff81b387c5)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/devcoredump.c (ffffffff81b790dc)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81b83e78)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0b1ac)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
```
```
In drivers/ata/libata-eh.c (ffffffff81c0f66e)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/net/virtio_net.c (ffffffff81c52eb6)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccc609)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d19eb2)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81dab6f6)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/ras/cec.c (ffffffff83732592)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81e5bcc6)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81e82c25)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81e8636b)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/skmsg.c (ffffffff81ea15b8)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/devlink/leftover.c (ffffffff8203dd35)
Location: include/linux/workqueue.h:670
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/devlink/leftover.c:devl_port_register_with_ops
```
```
In net/rfkill/input.c (ffffffff82057ec7)
Location: include/linux/workqueue.h:670
Inline: True
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
In arch/x86/hyperv/hv_init.c (ffffffff8104b535)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff838cb2dd)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810c35a3)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff8114042d)
Location: include/linux/workqueue.h:674
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff811885c0)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/livepatch/transition.c (ffffffff811e6de8)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81267257)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff813949a2)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff813afd9d)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff8391289c)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/page_reporting.c (ffffffff814d872a)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff814e281f)
Location: include/linux/workqueue.h:674
Inline: True
```
```
In fs/namespace.c (ffffffff81514c07)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff83921555)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff8177bd85)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In io_uring/io_uring.c (ffffffff81810065)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fallback_tw
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199bca7)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9f8e)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/xen/grant-table.c (ffffffff81ab4c24)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff839457a5)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae240a)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/iommu/iova.c (ffffffff81b7e241)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_depot_work_func
  - drivers/iommu/iova.c:free_iova_fast
```
```
In drivers/base/dd.c (ffffffff81b90285)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/devcoredump.c (ffffffff81bccfdc)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7da8)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-scsi.c (ffffffff81c6026b)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
```
```
In drivers/ata/libata-eh.c (ffffffff81c648ae)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/gpu/drm/drm_probe_helper.c (ffffffff81cce08f)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_probe_helper.c:output_poll_execute
  - drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_reschedule
  - drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_enable
```
```
In drivers/net/virtio_net.c (ffffffff81d092de)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d81509)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcfbd2)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e63796)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/ras/cec.c (ffffffff83966a22)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81f1b086)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81f44e2e)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81f4837f)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/skmsg.c (ffffffff81f63db8)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/devlink/core.c (ffffffff82100726)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_rel_nested_in_notify_work_schedule
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
```
```
In net/devlink/port.c (ffffffff821075b9)
Location: include/linux/workqueue.h:674
Inline: True
Inline callers:
  - net/devlink/port.c:__devlink_port_type_set
  - net/devlink/port.c:devl_port_register_with_ops
```
```
In net/rfkill/input.c (ffffffff8212a9cd)
Location: include/linux/workqueue.h:674
Inline: True
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
In kernel/sched/psi.c (ffff80001016750c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffff80001016e04c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/events/core.c (ffff80001029bf3c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffff8000102ab1e8)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In mm/vmstat.c (ffff8000114535b4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffff800010385b7c)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (ffff8000103b60dc)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffff80001145ef18)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070ace0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074be88)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/amba/bus.c (ffff8000107b9ee4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_deferred_retry_func
```
```
In drivers/xen/grant-table.c (ffff80001082c6e8)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In drivers/xen/balloon.c (ffff80001082e9b8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffff800011492638)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/tty/serial/8250/8250_fsl.c (ffff800010890a1c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/base/dd.c (ffff8000108ea34c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffff80001091f464)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffff800010929914)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffff8000109ad138)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ed3d4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa3160)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffff800010abefac)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/link_watch.c (ffff800010bf36f8)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (ffff800010c0cdf4)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (ffff800010c11210)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffff800010c2afb0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffff800010d6d8a4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In kernel/sched/psi.c (c03b4324)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (c03b8ef0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/kprobes.c (c0438188)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (c04cb4ec)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/vmstat.c (c152e230)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (c056ea08)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (c05943fc)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (c153778c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/bus/ti-sysc.c (c0829278)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ceb64)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/amba/bus.c (c08e5e58)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_deferred_retry_func
```
```
In drivers/regulator/core.c (c159339c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/tty/serial/8250/8250_fsl.c (c098d01c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/base/dd.c (c09d8328)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (c0a046a0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (c0a7cc30)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0acf094)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
```
```
In drivers/auxdisplay/arm-charlcd.c (c159d27c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
```
```
In drivers/usb/musb/musb_core.c (c0b657c0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
```
```
In drivers/usb/musb/musb_virthub.c (c0b69600)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_suspend
```
```
In drivers/usb/musb/musb_gadget.c (c0b6fac0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_pullup
  - drivers/usb/musb/musb_gadget.c:musb_gadget_disable
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
```
```
In drivers/input/keyboard/atkbd.c (c0b81478)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (c0ba0ca4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In sound/soc/soc-jack.c (c0cadaf4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
```
```
In net/core/link_watch.c (c0d0c064)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (c0d254d0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (c0d290c4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (c0d4239c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (c0e6b518)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/powerpc/platforms/pseries/vio.c (c000000000102548)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_sg
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_page
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_page
  - arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_free_coherent
  - arch/powerpc/platforms/pseries/vio.c:vio_cmo_entitlement_update
```
```
In kernel/sched/psi.c (c0000000001bf0e8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (c0000000001c5910)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (c0000000001f30ac)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (c00000000026ec7c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (c00000000034c160)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (c00000000035ed98)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In mm/vmstat.c (c00000000137ba08)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (c00000000047bd60)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (c0000000004b2554)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (c000000001389eb8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008adbe4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/regulator/core.c (c0000000013a4de8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/tty/hvc/hvsi.c (c00000000091f140)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_write
  - drivers/tty/hvc/hvsi.c:hvsi_write_worker
  - drivers/tty/hvc/hvsi.c:hvsi_write_worker
```
```
In drivers/tty/serial/8250/8250_fsl.c (c00000000093aa1c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/base/dd.c (c000000000981360)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (c0000000009c47e0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (c000000000a74464)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (c000000000b81e74)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (c000000000ba0958)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/link_watch.c (c000000000cd8b98)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (c000000000cf88c8)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (c000000000cfda20)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (c000000000d20540)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (c000000000eab524)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In kernel/sched/psi.c (ffffffe000109a9e)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffe00010d534)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/events/core.c (ffffffe0001c9a1e)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/vmstat.c (ffffffe000012838)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffe0002587e0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (ffffffe000278db6)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffe00001bb7e)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7a02)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9b56)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/regulator/core.c (ffffffe00002d9e4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffe00057e176)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffe00059e40e)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/ata/libata-eh.c (ffffffe00060a6b4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006af6e8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffe0006c0a1c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/link_watch.c (ffffffe00077508a)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (ffffffe000789eda)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (ffffffe00078d47e)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffe0007a250a)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffe00089f6a0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01dd3)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff8289b3fd)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81078728)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810fbb05)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff811004a4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff81126601)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff8117b0df)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff8120a132)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121748d)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In mm/vmstat.c (ffffffff828c3811)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812d7899)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (ffffffff812fb2b8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828ce6c1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815960d1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b6f40)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff816290c3)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff8162ae5c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff828e81d3)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff816c4a1f)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff816ef4b2)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff816f6e11)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81766a52)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81814326)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff8181fb55)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In drivers/ras/cec.c (ffffffff828ffc7a)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff818f1ab9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (ffffffff819077ef)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (ffffffff8190abdc)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81922c41)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffff81a3c29b)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01c83)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828936bb)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81067f18)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810ebd25)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff810f0694)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff81119061)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff8116e27f)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811fcf23)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8120a1ed)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In mm/vmstat.c (ffffffff828bbf36)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812c8519)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (ffffffff812ebed8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828c6ddd)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81585261)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5d20)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/regulator/core.c (ffffffff828df936)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff8169fc9f)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/ata/libata-eh.c (ffffffff817468b2)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dba56)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff817e71f5)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In drivers/ras/cec.c (ffffffff828f8292)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff818ab8f9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (ffffffff818c15ff)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (ffffffff818c497c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff818dc9f1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffff819f8ebb)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01db3)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae3dd)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810786d8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810f8cc5)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff810fd664)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff811244f1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81178eaf)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81207ed2)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121522d)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In mm/vmstat.c (ffffffff828d6591)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812d56a9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (ffffffff812f90a8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828e1441)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81596611)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b74d0)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81657093)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81658abc)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff828fbcd9)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff816f2eef)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff8171cb92)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81723791)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff81796815)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818534a6)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff8186ca95)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In drivers/ras/cec.c (ffffffff82915276)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff81942ae9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (ffffffff8195881f)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (ffffffff8195bc0c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81973dd1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199dd5a)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a9341)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:ecache_work
```
```
In net/rfkill/input.c (ffffffff81aa814b)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81c01e13)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae3fb)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8107a7d8)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff81103e15)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff81108904)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/livepatch/transition.c (ffffffff81130b50)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff8118677f)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81216c79)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8122421d)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In mm/vmstat.c (ffffffff828db9b2)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In fs/file_table.c (ffffffff812e64f9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In fs/namespace.c (ffffffff8130a3d4)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828e6857)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0a8c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d0f38)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81671693)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff816730cc)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff82901a0a)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff8170d71f)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffff81737ef2)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff8173ec01)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/ata/libata-eh.c (ffffffff817b0685)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186e6f6)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff81886a25)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In drivers/ras/cec.c (ffffffff8291bfcd)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/link_watch.c (ffffffff819643e9)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/page_pool.c (ffffffff8197a95f)
Location: include/linux/workqueue.h:607
Inline: True
```
```
In net/core/netpoll.c (ffffffff8197e00c)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff819962c1)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/rfkill/input.c (ffffffff81ab4631)
Location: include/linux/workqueue.h:607
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
```
</details>
</li>
</ul>

## Differences
