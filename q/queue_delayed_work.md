# Function: <code>queue_delayed_work</code>

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
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In arch/x86/kernel/tsc.c (ffffffff81f68fdc)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81065326)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810ccb75)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcu.c (ffffffff810e3ae1)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:call_srcu
```
```
In kernel/time/ntp.c (ffffffff810f72a7)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff8112d77b)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff8117a1e4)
Location: include/linux/workqueue.h:483
Inline: True
```
```
In kernel/jump_label.c (ffffffff8118afa7)
Location: include/linux/workqueue.h:483
Inline: True
```
```
In mm/vmstat.c (ffffffff811ad1b4)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:setup_vmstat
```
```
In mm/backing-dev.c (ffffffff811aea3c)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff8120e3b1)
Location: include/linux/workqueue.h:483
Inline: True
```
```
In fs/namespace.c (ffffffff8122d013)
Location: include/linux/workqueue.h:483
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81f8f04f)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In block/blk-core.c (ffffffff813b5522)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
  - block/blk-core.c:kblockd_schedule_delayed_work
```
```
In block/genhd.c (ffffffff813ca909)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:disk_check_events
```
```
In drivers/pci/pci.c (ffffffff81435673)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144f645)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473502)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/xen/grant-table.c (ffffffff814c5e5a)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff814c6776)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff814d32bd)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:selfballoon_process
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
```
```
In drivers/regulator/core.c (ffffffff814da1a8)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/firmware_class.c (ffffffff8155edf3)
Location: include/linux/workqueue.h:483
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8156ca50)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_error.c (ffffffff815abefb)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff815d44e7)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff815da31b)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff815dc8a9)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/phy/phy.c (ffffffff815ea906)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_machine
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_state_machine
```
```
In drivers/net/virtio_net.c (ffffffff815f1f31)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_restore
```
```
In drivers/usb/core/hub.c (ffffffff81604c21)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:led_work
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8162895f)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8162ce71)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8166f9e5)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/power_supply_core.c (ffffffff8167f66c)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
```
```
In drivers/power/charger-manager.c (ffffffff81680c5f)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:cm_suspend_complete
```
```
In drivers/mmc/core/core.c (ffffffff816be2ed)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:_mmc_detect_change
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/devfreq/devfreq.c (ffffffff816ebf7b)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
```
```
In net/core/dst.c (ffffffff81724099)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff8172781e)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_periodic_work
  - net/core/neighbour.c:neigh_table_init
```
```
In net/core/link_watch.c (ffffffff81730680)
Location: include/linux/workqueue.h:483
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738de3)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - net/core/netpoll.c:queue_process
  - net/core/netpoll.c:netpoll_send_skb_on_dev
```
```
In net/ipv4/inetpeer.c (ffffffff81757ec2)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
```
```
In net/ipv4/devinet.c (ffffffff817912f0)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - net/ipv4/devinet.c:__inet_insert_ifa
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:devinet_init
```
```
In net/rfkill/core.c (ffffffff81810e7e)
Location: include/linux/workqueue.h:483
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_poll
  - net/rfkill/core.c:rfkill_register
```
```
In net/rfkill/input.c (ffffffff81812593)
Location: include/linux/workqueue.h:483
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
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In arch/x86/kernel/tsc.c (ffffffff81036c3a)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810651ed)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810d1634)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcu.c (ffffffff810e9df1)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:call_srcu
```
```
In kernel/time/ntp.c (ffffffff810fe446)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff811367bb)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811926be)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8119d667)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In mm/vmstat.c (ffffffff81fb1fd1)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff811c7e7c)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff81234dd4)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In fs/namespace.c (ffffffff812557b0)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81fb9651)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff81279023)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In block/blk-core.c (ffffffff813fa3d9)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - block/blk-core.c:kblockd_schedule_delayed_work
  - block/blk-core.c:blk_delay_queue
```
```
In block/genhd.c (ffffffff8140f0e7)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff81480fc1)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149bde5)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1ac7)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff815164ea)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81516f64)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff81524386)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/regulator/core.c (ffffffff8152c918)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/firmware_class.c (ffffffff815b3333)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff815c1ef0)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_error.c (ffffffff81603e14)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff8162df7c)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81633ed4)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81636698)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/phy/phy.c (ffffffff816494cc)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_start_machine
```
```
In drivers/net/virtio_net.c (ffffffff81653e59)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_restore
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/usb/core/hub.c (ffffffff81669c03)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81687f99)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8168d1f2)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816cfd46)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/power_supply_core.c (ffffffff816e04e0)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
```
```
In drivers/power/charger-manager.c (ffffffff816e368c)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:_setup_polling
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ecce3)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/mmc/core/core.c (ffffffff81723d49)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/devfreq/devfreq.c (ffffffff81750f3e)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/dst.c (ffffffff8178db16)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff8179206c)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff8179adf0)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In net/core/netpoll.c (ffffffff817a5520)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/inetpeer.c (ffffffff817c4201)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/devinet.c (ffffffff81feb0af)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81884ed0)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81885473)
Location: include/linux/workqueue.h:484
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
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_event_init
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In arch/x86/kernel/tsc.c (ffffffff8103696a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8106871d)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810d8094)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcu.c (ffffffff810f0cc1)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/rcu/srcu.c:call_srcu
```
```
In kernel/time/ntp.c (ffffffff81101236)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff8114053b)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811a1e98)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811ad087)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In mm/vmstat.c (ffffffff81feea20)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/vmstat.c:setup_vmstat
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff811d7f9c)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff81247984)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In fs/namespace.c (ffffffff81268ba0)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81ff5fc2)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff8128cc48)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
```
In block/blk-core.c (ffffffff81413d59)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/blk-core.c:kblockd_schedule_delayed_work
  - block/blk-core.c:blk_delay_queue
```
```
In block/genhd.c (ffffffff8142a487)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff814a2681)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bd9c6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3ab7)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8154295a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff815433bb)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff81550846)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/regulator/core.c (ffffffff81558f88)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/firmware_class.c (ffffffff815e26d3)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff815f1340)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_error.c (ffffffff816334f4)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff8165f0cc)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81665024)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81667738)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/phy/phy.c (ffffffff8167a77a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/net/phy/phy.c:phy_start_machine
```
```
In drivers/usb/core/hub.c (ffffffff81697933)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b61cc)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816bb2c6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816fdc26)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81710950)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81713afc)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171dd99)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/mmc/core/core.c (ffffffff81756c27)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/devfreq/devfreq.c (ffffffff8177ccbe)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/dst.c (ffffffff817bb3e6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/dst.c:dst_gc_task
```
```
In net/core/neighbour.c (ffffffff817bf1ec)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff817c8b90)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In net/core/netpoll.c (ffffffff817d3f8f)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/inetpeer.c (ffffffff817f3d21)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/devinet.c (ffffffff8202998f)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff818b9740)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff818b9ce3)
Location: include/linux/workqueue.h:498
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
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81067a3d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810d70d0)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff810f20e8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
```
```
In kernel/livepatch/transition.c (ffffffff810f8f51)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff81103396)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff811418cc)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811a964e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811b4529)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In mm/vmstat.c (ffffffff820d0a93)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff811e0e7c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812531b0)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In fs/namespace.c (ffffffff812762e7)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In fs/fs-writeback.c (ffffffff820d875c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff812996e3)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In block/blk-core.c (ffffffff81421849)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/blk-core.c:kblockd_schedule_delayed_work
  - block/blk-core.c:blk_delay_queue
```
```
In block/genhd.c (ffffffff8143873c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff814ac3db)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c8041)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef8a8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8155681c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff8155724b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff81564fc1)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/regulator/core.c (ffffffff8156d8d6)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/base/firmware_class.c (ffffffff815f7513)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8160549f)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_error.c (ffffffff81648223)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff81673ad1)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff816797c1)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8167beae)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/phy/phy.c (ffffffff8168f17b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/net/phy/phy.c:phy_start_machine
```
```
In drivers/usb/core/hub.c (ffffffff816acded)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816ca4ec)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff816cf46c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81713546)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81728c79)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b0a2)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735f03)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/edac/wq.c (ffffffff8175f7a9)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff81774b4b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81780b56)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff8179b88e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff817dc063)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff817e7767)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/core/netpoll.c (ffffffff817f32ff)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/inetpeer.c (ffffffff81814101)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_inval_rcu
  - net/ipv4/inetpeer.c:inetpeer_gc_worker
```
```
In net/ipv4/devinet.c (ffffffff8210cf42)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff818e0110)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff818e06f3)
Location: include/linux/workqueue.h:500
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
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8106bccd)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810df070)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff810fb4f2)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
```
```
In kernel/livepatch/transition.c (ffffffff81103984)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff8110e511)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff8114e67c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811bcea3)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811c8347)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In mm/vmstat.c (ffffffff826d94a3)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff811f6e8c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812752b3)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In fs/namespace.c (ffffffff81298c3a)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In fs/fs-writeback.c (ffffffff826e1456)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff812bca53)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/blk-core.c (ffffffff8144c329)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/blk-core.c:kblockd_schedule_delayed_work
  - block/blk-core.c:blk_delay_queue
```
```
In block/genhd.c (ffffffff814641a2)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff814eb4ab)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815085e7)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8152442b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff815ba329)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff815bb25b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff815c9151)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/firmware_class.c (ffffffff8165f3c3)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8166d8a6)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_error.c (ffffffff816b1308)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff816dd0c1)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff816e2e2f)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff816e554e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/phy/phy.c (ffffffff816f8beb)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/net/phy/phy.c:phy_start_machine
```
```
In drivers/usb/core/hub.c (ffffffff817181b1)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81736a2c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8173babb)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81784786)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8179a3f8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c842)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7d48)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
```
In drivers/edac/wq.c (ffffffff817d1839)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff817ead9d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff817f7116)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff8181247e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff818564e4)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff818626a7)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/core/netpoll.c (ffffffff8186e682)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/devinet.c (ffffffff82717256)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81965e0f)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81966403)
Location: include/linux/workqueue.h:500
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
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff826dc9a7)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8106eb06)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/power/qos.c (ffffffff810e76c0)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff811037cf)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
```
```
In kernel/livepatch/transition.c (ffffffff8110bf0f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff81119ebf)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff8115cf7f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811dd08c)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811e874a)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In mm/vmstat.c (ffffffff8270394d)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8121812a)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff8129bb43)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In fs/namespace.c (ffffffff812bee29)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8270ca83)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff812e5630)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/blk-core.c (ffffffff8147f5fc)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
```
```
In block/genhd.c (ffffffff81497acd)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff8151aab0)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539527)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c499)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8155a178)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff815f2179)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff815f38fb)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff816019d5)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/firmware_loader/main.c (ffffffff81699eed)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816a92b0)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed63f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff81719809)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff8171f66a)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81721dee)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/phy/phy.c (ffffffff81735d87)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_trigger_machine
  - drivers/net/phy/phy.c:phy_start_machine
```
```
In drivers/usb/core/hub.c (ffffffff8175700f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8177647c)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8177c283)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c5856)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcc9e)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e18c0)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e3cdd)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In drivers/edac/wq.c (ffffffff8181a5e5)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff81833e62)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818405e5)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff8185c384)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff818a52a0)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff818ae39b)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In net/core/netpoll.c (ffffffff818bf816)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/devinet.c (ffffffff82741673)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff819bf69f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff819bfd0b)
Location: include/linux/workqueue.h:523
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
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff82892d59)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81074b12)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810ef654)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
```
```
In kernel/power/qos.c (ffffffff810f2cc0)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff8110f34f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_queue_delayed_work_on
```
```
In kernel/livepatch/transition.c (ffffffff811176ff)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff811253bf)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff81169e44)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811ed48c)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff811f9412)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In mm/vmstat.c (ffffffff828bb076)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8122b03a)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812b0e73)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In fs/namespace.c (ffffffff812d40f9)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In fs/fs-writeback.c (ffffffff828c3ca9)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff812fa242)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffff814b19ed)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff81530805)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815509b9)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815537e0)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81571a88)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8160d0d9)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff8160e91b)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/xen/xen-selfballoon.c (ffffffff8161cac8)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/xen/xen-selfballoon.c:xen_selfballoon_init
  - drivers/xen/xen-selfballoon.c:store_frontswap_selfshrinking
  - drivers/xen/xen-selfballoon.c:store_selfballooning
  - drivers/xen/xen-selfballoon.c:selfballoon_process
```
```
In drivers/base/dd.c (ffffffff816a254f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba7cd)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816c9ea9)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff816d04f8)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81704a67)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff8171114f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff8173c109)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81741f5a)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8174469e)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff8177b4af)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179bea2)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817a2786)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ece26)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff8180466c)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180cfec)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f60d)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81845dd5)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff8185fdf5)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8186c595)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff8187b914)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff818c4aa5)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff818d261b)
Location: include/linux/workqueue.h:523
Inline: True
```
```
In net/core/netpoll.c (ffffffff818e863c)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/ipv4/devinet.c (ffffffff828fb8d9)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff819f6a2f)
Location: include/linux/workqueue.h:523
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff819f6eab)
Location: include/linux/workqueue.h:523
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
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828aa388)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810786d8)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810f6a65)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff810fb164)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff811190bf)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/livepatch/transition.c (ffffffff81121a01)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff8112fe3f)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff81176b88)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81204ef2)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121136d)
Location: include/linux/workqueue.h:501
Inline: True
```
```
In mm/vmstat.c (ffffffff828d24eb)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8123ac6a)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812cd899)
Location: include/linux/workqueue.h:501
Inline: True
```
```
In fs/namespace.c (ffffffff812f1138)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828dd09b)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff8131ac45)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffff814dfe02)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff81560166)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81580c88)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815844c3)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a1f70)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81640893)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff816426b6)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/base/dd.c (ffffffff816db25f)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f4d74)
Location: include/linux/workqueue.h:501
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81705442)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff8170bfd1)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff8173e86b)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:nvdimm_security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c56f)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff81777c2b)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff8177db85)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8178047f)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff817bab41)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817daf62)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817e14eb)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182d9e6)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff81845cc5)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184ebaf)
Location: include/linux/workqueue.h:501
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851c9a)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:501
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81888bb5)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff818a399a)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818b0415)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff818c5a6a)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff829111d4)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff819144bb)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff8191f8a9)
Location: include/linux/workqueue.h:501
Inline: True
```
```
In net/core/xdp.c (ffffffff81930d07)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/netpoll.c (ffffffff81937d4c)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff8194d481)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff829182e9)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81a66005)
Location: include/linux/workqueue.h:501
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81a663eb)
Location: include/linux/workqueue.h:501
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828ad3eb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81079728)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff811027f5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff81107194)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff81124f85)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/livepatch/transition.c (ffffffff8112e021)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff8113bd7f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff81182abf)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81211ae2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121ee3d)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In mm/vmstat.c (ffffffff828da95d)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff812490da)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812df2b9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (ffffffff81302cd8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828e580d)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff8132d7b5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffff814f9232)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff81581296)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a28c1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a5ea3)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815c2df0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81663253)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81664c7c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff829009b6)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff816ff22f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff81719174)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff817296d2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff817302d1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81762861)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (ffffffff817706ef)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff8179bb8b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff817a1995)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817a4138)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff817eb3bb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180be82)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818123db)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/input-poller.c (ffffffff8185a4ab)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185f316)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff818775e5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818805df)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81882eca)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (ffffffff818bab65)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff818d5f0b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio.c (ffffffff818e011b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818e28cd)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff818f80fa)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff8291af6b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81946b2b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81951ae9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (ffffffff8196781f)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (ffffffff8196ac0c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81982dd1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff82922158)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81a9cb75)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81a9cf0b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff8102faa6)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f0f2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81080b09)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff8110d400)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff81132c8f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811341d8)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff8113c9f7)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff8114b13f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff81195b8f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81239ea8)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff8124abbd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff82cf8bd6)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8127739a)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/page_reporting.c (ffffffff8130cff0)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff8131611b)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In fs/namespace.c (ffffffff8133c68f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff81349192)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff81367852)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/io_uring.c (ffffffff8137bb7b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_data_ref_zero
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff8151cd65)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/genhd.c (ffffffff8155a620)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff81625cd9)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164b55a)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8164ec06)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8166d400)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8171270b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81714480)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff82d17c9d)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff817b8e5f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d4c80)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff817e5f02)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff817ed841)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff8182249c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff81832fe0)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff8185f97b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81865794)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff818696f8)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff818baa60)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818dcdd2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818e0c37)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818f64a9)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff8192d12b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819326a6)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194eaa8)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff819518e2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In drivers/edac/wq.c (ffffffff8198b3c5)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff819a88fd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/sdio.c (ffffffff819b319b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff819b59fd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce17c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff82d2c9c9)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81a13272)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81a22849)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81a3adf0)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81a3e70c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81a5ae71)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff82d2e706)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81b980d5)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81b9883b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff810306d6)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8103f1b2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81bd829a)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff8110a43d)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff8112e46f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8112fc4f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff81137107)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81192837)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81243520)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff812552fd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff82fe58ae)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/vmstat.c:start_shepherd_timer
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff81281c8a)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/page_reporting.c (ffffffff81318f40)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff813212b1)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In fs/namespace.c (ffffffff8134853c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff813560f7)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff81374bb2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/io_uring.c (ffffffff81389da5)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/io_uring.c:io_file_data_ref_zero
```
```
In fs/fuse/dax.c (ffffffff8149ddc7)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_free_mem_worker
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff81539c05)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/genhd.c (ffffffff81576b4e)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff8164baf9)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bfbeb0)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bfc657)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8168db20)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8172f49b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff817316c0)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff83005916)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff817cdbcf)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e9650)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff817fab92)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81802171)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff818311ac)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff81843bc7)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff8186e95b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81874594)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff818784f8)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff81c1b501)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e6c22)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ea4a7)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hprt0_enable
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818ff059)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff819345eb)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81939906)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8195450b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81956126)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In drivers/edac/wq.c (ffffffff8198efe3)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff819ab47c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff819b5697)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff819b7fbd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff819cdb4b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff8301b434)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81a13652)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81a22ba9)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81a3d210)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81a414ac)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81a66716)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff8301d2bd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81ba7ddb)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81ba850b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff810311c6)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff81040c9f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81bca095)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff8110c01c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff8112ea8f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8113017f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff81137ddb)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81193721)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff812484d4)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff812597fd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/vmstat.c (ffffffff831f0073)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff81286c4a)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/page_reporting.c (ffffffff8131f130)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff8132771b)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In fs/namespace.c (ffffffff8134e907)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff8135cce7)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff8137b572)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/fuse/dax.c (ffffffff814a3537)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_free_mem_worker
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff815420a5)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/genhd.c (ffffffff8157eafc)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff8162e6c9)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81bedd28)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81bee542)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8165b577)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81670810)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81712eeb)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff817150c0)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff832104bd)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff817b15e8)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff817cde50)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff817df8b2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff817e6e6a)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff8181426c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff81826d77)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff81851158)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81856d72)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff8185ab67)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff81c0d3e5)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818c8bb2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff818ce2bc)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (ffffffff818e27bc)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff8191795b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191d026)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81938340)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81939c66)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:518
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81973633)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff8198ffdc)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81999c17)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8199c55d)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff819b2dbb)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff8322655f)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff819f9762)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81a09ed9)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81a24030)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81a2611c)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81a46c66)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff832283a2)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81af7b15)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv6/mcast.c (ffffffff81b5ef27)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/rfkill/core.c (ffffffff81b96f6b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81b9769b)
Location: include/linux/workqueue.h:518
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff81036416)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff81046d8f)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81c9f3a4)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81ca5776)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/sched/psi.c (ffffffff8112ad56)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_group_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff8114ff6f)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81155712)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:schedule_page_work_fn
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff8115ab2b)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff811bc279)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff8128285d)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff8129554a)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/page-writeback.c (ffffffff812a826f)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/page-writeback.c:test_clear_page_writeback
```
```
In mm/vmstat.c (ffffffff832d5887)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff812c61da)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/kfence/core.c (ffffffff832dcff3)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
```
```
In mm/memcontrol.c (ffffffff8135389e)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/memcontrol.c:flush_memcg_stats_dwork
```
```
In mm/page_reporting.c (ffffffff8136c513)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff81374d1b)
Location: include/linux/workqueue.h:512
Inline: True
```
```
In fs/namespace.c (ffffffff8139c94a)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff813ab0c7)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff813c82dc)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/io_uring.c (ffffffff813deed4)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - fs/io_uring.c:io_req_task_work_add
```
```
In fs/fuse/dax.c (ffffffff814fb5b4)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_free_mem_worker
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff815a2015)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/disk-events.c (ffffffff815eec8f)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/disk-events.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff8169db86)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81ce8b03)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81ce9469)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff816cd967)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff816e4ae0)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff8178f9ab)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff832f9542)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff817b2600)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/base/dd.c (ffffffff8183a845)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff818586a0)
Location: include/linux/workqueue.h:512
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8186b33a)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff818731e2)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff8189e909)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff818b26fb)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff818dece8)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff818e55d2)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff818ec6ac)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff81d1448a)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8196165c)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81969168)
Location: include/linux/workqueue.h:512
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (ffffffff8197e8cc)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff819b9bcb)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819bf9f6)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dc79f)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff819de387)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/edac/wq.c (ffffffff81a1c333)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff81a3b7ac)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81a463b7)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81a48f3d)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff81a6275d)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff833108af)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81aac7b2)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81abc3d9)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81ad8600)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81adae8c)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81b01a66)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff8331281d)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81bb77f5)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv6/mcast.c (ffffffff81c266cc)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/rfkill/core.c (ffffffff81c63d97)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
  - net/rfkill/core.c:rfkill_resume
```
```
In net/rfkill/input.c (ffffffff81c6418b)
Location: include/linux/workqueue.h:512
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
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
In arch/x86/hyperv/hv_init.c (ffffffff8103c256)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8104f952)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81e4eb46)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81e55015)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/sched/build_utility.c (ffffffff8113f90e)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff81176a8d)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8117f2c4)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:schedule_page_work_fn
  - kernel/rcu/tree.c:kfree_rcu_monitor
```
```
In kernel/livepatch/transition.c (ffffffff811843de)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff811efae7)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff812ce1ae)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff812eb33d)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/page-writeback.c (ffffffff81300976)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmstat.c (ffffffff8348a0e0)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff81323f88)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/kfence/core.c (ffffffff813ae57f)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memcontrol.c (ffffffff813cb72b)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:flush_memcg_stats_dwork
```
```
In mm/page_reporting.c (ffffffff813eadbf)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff813f36c3)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In fs/namespace.c (ffffffff8141f844)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff81431eec)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff8144f403)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/fuse/dax.c (ffffffff8158ba90)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_free_mem_worker
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff81648465)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/disk-events.c (ffffffff8169f5df)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/disk-events.c:__disk_unblock_events
```
```
In io_uring/io_uring.c (ffffffff816ca4ce)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_req_task_work_add
```
```
In drivers/pci/pci.c (ffffffff817bf756)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81eafb9f)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81eb047a)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff817f62f9)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8180f582)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81810c93)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
```
In drivers/xen/grant-table.c (ffffffff818c7f18)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff834b1d15)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff818ede52)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/base/dd.c (ffffffff8197d0a5)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f0cc)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff819b409b)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff819bb458)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff819e83bb)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff819fd7f7)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff81a302c3)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81a368e0)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81a3d82f)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff81edf03c)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81abbabe)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81ac3366)
Location: include/linux/workqueue.h:513
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ada029)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff81b19805)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b20562)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b4085d)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b42ef7)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81b52880)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/edac/wq.c (ffffffff81b853d3)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9f196)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff81ba872c)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb416b)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81bb71cd)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd38af)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff834ca558)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81c2568e)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81c36ea7)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81c594c9)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81c5c34e)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81c810a6)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devl_port_register
```
```
In net/ipv4/devinet.c (ffffffff834cc9f8)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81d4b53b)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv6/mcast.c (ffffffff81dc4347)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/rfkill/core.c (ffffffff81e067d9)
Location: include/linux/workqueue.h:513
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
  - net/rfkill/core.c:rfkill_resume
```
```
In net/rfkill/input.c (ffffffff81e06df7)
Location: include/linux/workqueue.h:513
Inline: True
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
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff83e78f11)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810b9253)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81127a99)
Location: include/linux/workqueue.h:514
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8116a471)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff811ace6d)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811b8a01)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:schedule_page_work_fn
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
```
```
In kernel/livepatch/transition.c (ffffffff811bf688)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81236537)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81335b53)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff813553ed)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/page-writeback.c (ffffffff8136b250)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmstat.c (ffffffff83eba9dc)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff81398838)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/kfence/core.c (ffffffff8142e92f)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memcontrol.c (ffffffff814503fb)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:flush_memcg_stats_dwork
```
```
In mm/page_reporting.c (ffffffff81472f8c)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff8147c483)
Location: include/linux/workqueue.h:514
Inline: True
```
```
In fs/namespace.c (ffffffff814abd77)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff83ec9495)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff814ddc73)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/fuse/dax.c (ffffffff816322b0)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_free_mem_worker
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff81701155)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/disk-events.c (ffffffff8175df2f)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/disk-events.c:__disk_unblock_events
```
```
In io_uring/io_uring.c (ffffffff81789b0b)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fallback_tw
```
```
In drivers/pci/pci.c (ffffffff818dbd36)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190f187)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8191273f)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81921d09)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193e32f)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8193fb93)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
```
In drivers/xen/grant-table.c (ffffffff81a194d8)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff83eec0f5)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a459ec)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/char/random.c (ffffffff81a94055)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/dd.c (ffffffff81aea435)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b10aec)
Location: include/linux/workqueue.h:514
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81b28f2c)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81b30988)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81b63f1b)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7bc1d)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb3894)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81bbb5c4)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81bc30eb)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff81c1a620)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c4503e)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81c4d286)
Location: include/linux/workqueue.h:514
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81c651c9)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff81cab2d5)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb2892)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccffcd)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_acquire_i2c_bus
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd6e9e)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cd98e7)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81ceaaad)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/edac/wq.c (ffffffff81d243d3)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d40b76)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff81d4af8c)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7f7ff)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff83f0c212)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81dd8a22)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81dea4c7)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81e0f455)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81e12a2b)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81e3e151)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/core/devlink.c:__devlink_port_type_set
  - net/core/devlink.c:devl_port_register
```
```
In net/ipv4/devinet.c (ffffffff83f0f4dd)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81f14e41)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv6/mcast.c (ffffffff81f944a7)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/rfkill/core.c (ffffffff81fdbb39)
Location: include/linux/workqueue.h:514
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
  - net/rfkill/core.c:rfkill_resume
```
```
In net/rfkill/input.c (ffffffff81fdc1e7)
Location: include/linux/workqueue.h:514
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
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff8369b60d)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810bc423)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff81134f39)
Location: include/linux/workqueue.h:517
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff8117ab90)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff811bedad)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811ca914)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:schedule_page_work_fn
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
```
```
In kernel/livepatch/transition.c (ffffffff811d2168)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff8124d357)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff813668a3)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff813868dd)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/page-writeback.c (ffffffff8139d3cd)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmstat.c (ffffffff836dffec)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff813cb798)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/kfence/core.c (ffffffff8146406f)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memcontrol.c (ffffffff81485ef3)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:flush_memcg_stats_dwork
```
```
In mm/page_reporting.c (ffffffff814a76fa)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff814b1003)
Location: include/linux/workqueue.h:517
Inline: True
```
```
In fs/namespace.c (ffffffff814e0b37)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff836ee505)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff8151448c)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/quota/dquot.c (ffffffff8155badf)
Location: include/linux/workqueue.h:517
Inline: True
```
```
In fs/fuse/dax.c (ffffffff8166ae60)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_free_mem_worker
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff8173b1f5)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/disk-events.c (ffffffff8179ce3f)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/disk-events.c:__disk_unblock_events
```
```
In io_uring/io_uring.c (ffffffff817cbb75)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fallback_tw
```
```
In drivers/pci/pci.c (ffffffff8191ee06)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952817)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81955dcf)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81965759)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8198281e)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819840a3)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
```
In drivers/xen/grant-table.c (ffffffff81a623f8)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff83711de5)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a8fb9a)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/char/random.c (ffffffff81adf875)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
```
In drivers/base/dd.c (ffffffff81b387c5)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5ed78)
Location: include/linux/workqueue.h:517
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81b790dc)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81b83e78)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81bb751b)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcf940)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0b1ac)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81c0f66e)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81c1bdb6)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
```
In drivers/net/virtio_net.c (ffffffff81c52eb6)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/usb/core/hub.c (ffffffff81c81647)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81cac62e)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81cb48f6)
Location: include/linux/workqueue.h:517
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81ccc609)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff81d128b5)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d19eb2)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f075)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d41b57)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81d536bd)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/edac/wq.c (ffffffff81d8d5e3)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81dab6f6)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff81db583c)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/devfreq/devfreq.c (ffffffff81dedb8f)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff83732592)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81e49782)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81e5bcc6)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81e82c25)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81e8636b)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/skmsg.c (ffffffff81ea15b8)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/devinet.c (ffffffff83735aed)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff81f74b03)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv6/mcast.c (ffffffff81ff4e22)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/devlink/leftover.c (ffffffff8203dd35)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/devlink/leftover.c:__devlink_port_type_set
  - net/devlink/leftover.c:devl_port_register_with_ops
```
```
In net/rfkill/core.c (ffffffff82057819)
Location: include/linux/workqueue.h:517
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
  - net/rfkill/core.c:rfkill_resume
```
```
In net/rfkill/input.c (ffffffff82057ec7)
Location: include/linux/workqueue.h:517
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
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:__sysvec_hyperv_reenlightenment
```
```
In arch/x86/kernel/tsc.c (ffffffff838cb2dd)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810c35a3)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/reboot.c (ffffffff8114042d)
Location: include/linux/workqueue.h:559
Inline: True
```
```
In kernel/sched/core.c (ffffffff8115926f)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/build_utility.c (ffffffff811885c0)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/sched/build_utility.c:psi_avgs_work
```
```
In kernel/rcu/srcutree.c (ffffffff811cf21d)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811db1b4)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:schedule_page_work_fn
  - kernel/rcu/tree.c:schedule_delayed_monitor_work
```
```
In kernel/livepatch/transition.c (ffffffff811e6de8)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/kprobes.c (ffffffff81267257)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff813949a2)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/events/core.c:unaccount_event
```
```
In kernel/jump_label.c (ffffffff813afd9d)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - kernel/jump_label.c:__static_key_slow_dec_deferred
```
```
In mm/page-writeback.c (ffffffff813c7160)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - mm/page-writeback.c:__folio_end_writeback
```
```
In mm/vmstat.c (ffffffff8391289c)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff813f60e8)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/kfence/core.c (ffffffff814933ef)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_enable
  - mm/kfence/core.c:param_set_sample_interval
```
```
In mm/memcontrol.c (ffffffff814b4e91)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:flush_memcg_stats_dwork
```
```
In mm/page_reporting.c (ffffffff814d872a)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_register
  - mm/page_reporting.c:page_reporting_process
  - mm/page_reporting.c:__page_reporting_notify
```
```
In fs/file_table.c (ffffffff814e281f)
Location: include/linux/workqueue.h:559
Inline: True
```
```
In fs/namespace.c (ffffffff81514c07)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff83921555)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff8154895c)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/quota/dquot.c (ffffffff8159225b)
Location: include/linux/workqueue.h:559
Inline: True
```
```
In fs/fuse/dax.c (ffffffff816a51a0)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_free_mem_worker
  - fs/fuse/dax.c:alloc_dax_mapping
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff8177bd85)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_init_key_queue
```
```
In block/disk-events.c (ffffffff817e088f)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/disk-events.c:__disk_unblock_events
```
```
In io_uring/io_uring.c (ffffffff81810065)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_fallback_tw
```
```
In drivers/pci/pci.c (ffffffff81966f45)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199bca7)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8199f2ef)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:handle_button_press_event
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff819aee6f)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c9f8e)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cdfe3)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:store_cursor_blink
  - drivers/video/fbdev/core/fbcon.c:fbcon_blank
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_startup
  - drivers/video/fbdev/core/fbcon.c:set_con2fb_map
```
```
In drivers/xen/grant-table.c (ffffffff81ab4c24)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff839457a5)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae240a)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
```
```
In drivers/char/random.c (ffffffff81b32c95)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
```
In drivers/iommu/iova.c (ffffffff81b7e241)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_depot_work_func
  - drivers/iommu/iova.c:free_iova_fast
```
```
In drivers/base/dd.c (ffffffff81b90285)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
  - drivers/base/dd.c:deferred_probe_extend_timeout
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb26e5)
Location: include/linux/workqueue.h:559
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81bccfdc)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd7da8)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81c0bb6b)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
  - drivers/nvdimm/security.c:security_overwrite
```
```
In drivers/scsi/scsi_error.c (ffffffff81c245a0)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_timeout
```
```
In drivers/ata/libata-scsi.c (ffffffff81c6026b)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_rescan
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81c648ae)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81c70e96)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
```
In drivers/gpu/drm/drm_probe_helper.c (ffffffff81cce08f)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_probe_helper.c:output_poll_execute
  - drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_reschedule
  - drivers/gpu/drm/drm_probe_helper.c:drm_kms_helper_poll_enable
```
```
In drivers/net/virtio_net.c (ffffffff81d092de)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
```
```
In drivers/usb/core/hub.c (ffffffff81d35e92)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d612de)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81d69626)
Location: include/linux/workqueue.h:559
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (ffffffff81d81509)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/usb/host/ehci-platform.c:quirk_poll_timer
```
```
In drivers/input/input-poller.c (ffffffff81dc84b5)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcfbd2)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df5a22)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df8507)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_work
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff81e0a56d)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_process_event
```
```
In drivers/edac/wq.c (ffffffff81e44e93)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e63796)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:notify_hwp_interrupt
```
```
In drivers/mmc/core/core.c (ffffffff81e6dc8c)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea3f2f)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff83966a22)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81f084a1)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_managed_work
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81f1b086)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/core/link_watch.c:linkwatch_schedule_work
```
```
In net/core/page_pool.c (ffffffff81f44e2e)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release_retry
```
```
In net/core/netpoll.c (ffffffff81f4837f)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_send_skb
  - net/core/netpoll.c:queue_process
```
```
In net/core/skmsg.c (ffffffff81f63db8)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_backlog
```
```
In net/ipv4/devinet.c (ffffffff8396a15d)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/ipv4/nexthop.c (ffffffff8203b2a5)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_res_table_upkeep
```
```
In net/ipv6/mcast.c (ffffffff820c29f2)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_report_work
  - net/ipv6/mcast.c:mld_query_work
```
```
In net/devlink/core.c (ffffffff82100726)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_rel_nested_in_notify_work_schedule
  - net/devlink/core.c:devlink_rel_nested_in_notify_work
```
```
In net/devlink/port.c (ffffffff821075b9)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/devlink/port.c:__devlink_port_type_set
  - net/devlink/port.c:devl_port_register_with_ops
```
```
In net/rfkill/core.c (ffffffff8212a319)
Location: include/linux/workqueue.h:559
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
  - net/rfkill/core.c:rfkill_resume
```
```
In net/rfkill/input.c (ffffffff8212a9cd)
Location: include/linux/workqueue.h:559
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffff80001016e04c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffff80001018a3bc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/time/ntp.c (ffff8000101a60f0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/events/core.c (ffff80001029bf3c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffff8000102ab1e8)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In mm/vmstat.c (ffff8000114535b4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffff8000102de610)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffff800010385b7c)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (ffff8000103b60dc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffff80001145ef18)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffff8000103e9c38)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffff8000105faa38)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffff8000106e4204)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070ace0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070ddbc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074be88)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/amba/bus.c (ffff8000107b9ee4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_deferred_retry_func
```
```
In drivers/xen/grant-table.c (ffff80001082c6e8)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/xen/balloon.c (ffff80001082e9b8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffff800011492638)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/tty/serial/8250/8250_fsl.c (ffff800010890a1c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/base/dd.c (ffff8000108ea34c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffff80001090c5c4)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/base/devcoredump.c (ffff80001091f464)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffff800010929914)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffff800010962380)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (ffff800010973b3c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffff8000109a6658)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffff8000109ad138)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffff8000109af86c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (ffff8000109ed3d4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
```
```
In drivers/usb/core/hub.c (ffff800010a18db0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a4449c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffff800010a4b778)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/input-poller.c (ffff800010a9a514)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa3160)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffff800010abefac)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc24c)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffff800010acf9fc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (ffff800010b130e4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffff800010b2f1b4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffff800010b3a2e8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffff800010b3d1a4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffff800010b843e4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffff800010be2594)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffff800010bf36f8)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (ffff800010c0cdf4)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (ffff800010c11210)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffff800010c2afb0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffff8000114b2e14)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffff800010d6ca40)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffff800010d6d8a4)
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (c03b8ef0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (c03d8f9c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_reschedule
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/time/ntp.c (c03f10e0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/kprobes.c (c0438188)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (c04cb4ec)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/vmstat.c (c152e230)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (c05037b4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (c056ea08)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (c05943fc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (c153778c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (c05c0d44)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (c07a4afc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/bus/ti-sysc.c (c0829278)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_probe
```
```
In drivers/pci/pci.c (c0880044)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/video/fbdev/core/fb_defio.c (c08ceb64)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/amba/bus.c (c08e5e58)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_deferred_retry_func
```
```
In drivers/regulator/core.c (c159339c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/tty/serial/8250/8250_fsl.c (c098d01c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/base/dd.c (c09d8328)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (c09f5730)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/base/devcoredump.c (c0a046a0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/scsi/scsi_error.c (c0a4858c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (c0a76a8c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (c0a7cc30)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (c0a7f280)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/net/ethernet/freescale/fec_ptp.c (c0acf094)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_time_keep
```
```
In drivers/auxdisplay/arm-charlcd.c (c159d27c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/auxdisplay/arm-charlcd.c:charlcd_probe
```
```
In drivers/usb/core/hub.c (c0af0f80)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (c0b16ccc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1da00)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/usb/musb/musb_core.c (c0b657c0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
```
```
In drivers/usb/musb/musb_virthub.c (c0b69600)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_reset
  - drivers/usb/musb/musb_virthub.c:musb_port_suspend
```
```
In drivers/usb/musb/musb_gadget.c (c0b6fac0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_stop
  - drivers/usb/musb/musb_gadget.c:musb_gadget_pullup
  - drivers/usb/musb/musb_gadget.c:musb_gadget_disable
  - drivers/usb/musb/musb_gadget.c:musb_gadget_enable
```
```
In drivers/input/input-poller.c (c0b7c15c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (c0b81478)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (c0ba0ca4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (c0bad1f8)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c0bb0308)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (c0bf109c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (c0c0a5f4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
```
```
In drivers/mmc/core/sdio.c (c0c14ce0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (c0c1779c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (c0c67884)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In sound/core/compress_offload.c (c0c9cf0c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - sound/core/compress_offload.c:snd_compr_stop_error
```
```
In sound/soc/soc-jack.c (c0cadaf4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
  - sound/soc/soc-jack.c:gpio_handler
```
```
In sound/soc/soc-pcm.c (c0cb2590)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:soc_pcm_close
```
```
In sound/soc/soc-compress.c (c0cbcce0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - sound/soc/soc-compress.c:soc_compr_free
```
```
In net/core/neighbour.c (c0d01038)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (c0d0c064)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (c0d254d0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (c0d290c4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (c0d4239c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (c15b80bc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (c0e6afa0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (c0e6b518)
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (c0000000001c5910)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (c0000000001e500c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/livepatch/transition.c (c0000000001f30ac)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (c0000000002082dc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (c00000000026ec7c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (c00000000034c160)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (c00000000035ed98)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In mm/vmstat.c (c00000000137ba08)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (c00000000039dee0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (c00000000047bd60)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (c0000000004b2554)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (c000000001389eb8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (c0000000004f03e0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (c000000000793980)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (c00000000085e680)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/video/fbdev/core/fb_defio.c (c0000000008adbe4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/regulator/core.c (c0000000013a4de8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/tty/hvc/hvsi.c (c00000000091f140)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_write
  - drivers/tty/hvc/hvsi.c:hvsi_write_worker
  - drivers/tty/hvc/hvsi.c:hvsi_write_worker
```
```
In drivers/tty/serial/8250/8250_fsl.c (c00000000093aa1c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/base/dd.c (c000000000981360)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (c0000000009ac8a0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/base/devcoredump.c (c0000000009c47e0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/nvdimm/security.c (c000000000a18050)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (c000000000a2d6f0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_transport_srp.c (c000000000a41c18)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers
  - drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers
  - drivers/scsi/scsi_transport_srp.c:__srp_start_tl_fail_timers
  - drivers/scsi/scsi_transport_srp.c:srp_reconnect_work
  - drivers/scsi/scsi_transport_srp.c:store_reconnect_delay
```
```
In drivers/ata/libata-scsi.c (c000000000a6cb64)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (c000000000a74464)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (c000000000a77d70)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (c000000000ad20ac)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (c000000000b0734c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b12508)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/input-poller.c (c000000000b7a638)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (c000000000b81e74)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (c000000000ba0958)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (c000000000baed14)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c000000000bb3498)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (c000000000c079bc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (c000000000c28c50)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_pm_notify
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (c000000000c36ba0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (c000000000c3a4bc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (c000000000c6206c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (c000000000cca178)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (c000000000cd8b98)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (c000000000cf88c8)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (c000000000cfda20)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (c000000000d20540)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (c0000000013c40d4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (c000000000eaabb4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (c000000000eab524)
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffe00010d534)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffe00011f8a2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/time/ntp.c (ffffffe00013221c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_hw_clock
```
```
In kernel/events/core.c (ffffffe0001c9a1e)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In mm/vmstat.c (ffffffe000012838)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffe0001f66a2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffe0002587e0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (ffffffe000278db6)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffe00001bb7e)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffe00029e618)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffe000436db0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffe0004bb4fa)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7a02)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da3ec)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9b56)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/regulator/core.c (ffffffe00002d9e4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffe00057e176)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/devcoredump.c (ffffffe00059e40e)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/nvdimm/security.c (ffffffe0005cf89c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc8b2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffe0006051ca)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffe00060a6b4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffe00060ce72)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffe00063d9aa)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffe000660b76)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe00066870a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/input-poller.c (ffffffe0006aae18)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006af6e8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffe0006c0a1c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c9a7a)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cc3e8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (ffffffe0006ffb0e)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffe000708dcc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_start_host
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:mmc_detect_card_removed
```
```
In drivers/mmc/core/sdio.c (ffffffe000711e92)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffe0007143bc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffe00072db50)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffe000769cae)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffe00077508a)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (ffffffe000789eda)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (ffffffe00078d47e)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffe0007a250a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffe000041b16)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffe00089f2a8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffe00089f6a0)
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff8289b3fd)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81078728)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810fbb05)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff811004a4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff8111d565)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/livepatch/transition.c (ffffffff81126601)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff8113452f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff8117b0df)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff8120a132)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121748d)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In mm/vmstat.c (ffffffff828c3811)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8124172a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812d7899)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (ffffffff812fb2b8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828ce6c1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff81325d95)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffff814f1812)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff815757b6)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815960d1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815996b3)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b6f40)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff816290c3)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff8162ae5c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff828e81d3)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff816c4a1f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff816df4a4)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff816ef4b2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff816f6e11)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81716f51)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (ffffffff81724ddf)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/nvme/host/core.c (ffffffff81742223)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_keep_alive_end_io
```
```
In drivers/ata/libata-scsi.c (ffffffff81760c7b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81766a52)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817691f8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff817a379b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c4262)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff817ca7bb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/input-poller.c (ffffffff8180f4bb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81814326)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff8181fb55)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81828b4f)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (ffffffff818609e5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff818798cb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio.c (ffffffff81883adb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff8188628d)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff8189942a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff828ffc7a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff818e6afb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff818f1ab9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (ffffffff819077ef)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (ffffffff8190abdc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81922c41)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff82906e5c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81a3bf05)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81a3c29b)
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828936bb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff81067f18)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/core.c (ffffffff810c67bc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:sched_tick_remote
```
```
In kernel/sched/psi.c (ffffffff810ebd25)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff810f0694)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff8110e61b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/livepatch/transition.c (ffffffff81119061)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff81126f8f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff8116e27f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff811fcf23)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8120a1ed)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In mm/vmstat.c (ffffffff828bbf36)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8123471a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812c8519)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (ffffffff812ebed8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828c6ddd)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff81316935)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffff814e1d4c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff81563f16)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81585261)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81588843)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815a5d20)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/acpi/nfit/core.c (ffffffff815f449b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/acpi/nfit/core.c:__sched_ars
```
```
In drivers/regulator/core.c (ffffffff828df936)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff8169fc9f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff816b9ae4)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/nvdimm/security.c (ffffffff816ea9d1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (ffffffff816fe20f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff81710499)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_delete
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_delete
```
```
In drivers/nvme/host/core.c (ffffffff81723eb3)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_keep_alive_end_io
```
```
In drivers/ata/libata-scsi.c (ffffffff81740adb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff817468b2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81749058)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff8179530c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/input/input-poller.c (ffffffff817d6c0b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dba56)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff817e71f5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817f01df)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (ffffffff81827fb5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/devfreq/devfreq.c (ffffffff818568fa)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff828f8292)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff818a093b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff818ab8f9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (ffffffff818c15ff)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (ffffffff818c497c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff818dc9f1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff828ff1aa)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff819f8b25)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff819f8ebb)
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae3dd)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff810786d8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff810f8cc5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff810fd664)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff8111b455)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/livepatch/transition.c (ffffffff811244f1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff8113224f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff81178eaf)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81207ed2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8121522d)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In mm/vmstat.c (ffffffff828d6591)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8123f4ca)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812d56a9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (ffffffff812f90a8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828e1441)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff81323865)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffff814ed8a2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff81574fe6)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81596611)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81599bf3)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815b74d0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81657093)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff81658abc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff828fbcd9)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff816f2eef)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170cbc4)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff8171cb92)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff81723791)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81755d21)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (ffffffff81763baf)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff81790a0b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff81796815)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff81798fb8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff817e023b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81800d02)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff8180725b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/input-poller.c (ffffffff8184e63b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff818534a6)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff8186ca95)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81875a8f)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8187837a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (ffffffff818b0015)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff818cad6b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio.c (ffffffff818d4f7b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818d772d)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff818e8b1a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff82915276)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff81937b2b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff81942ae9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (ffffffff8195881f)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (ffffffff8195bc0c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff81973dd1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a0ab0)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
  - net/netfilter/nf_conntrack_core.c:gc_worker
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a9341)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:ecache_work
```
```
In net/ipv4/devinet.c (ffffffff8291c73f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81aa7db5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81aa814b)
Location: include/linux/workqueue.h:505
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
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hyperv_reenlightenment_intr
```
```
In arch/x86/kernel/tsc.c (ffffffff828ae3fb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/tsc.c:init_tsc_clocksource
  - arch/x86/kernel/tsc.c:tsc_refine_calibration_work
```
```
In arch/x86/kernel/check.c (ffffffff8107a7d8)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - arch/x86/kernel/check.c:start_periodic_check_for_corruption
  - arch/x86/kernel/check.c:check_corruption
```
```
In kernel/sched/psi.c (ffffffff81103e15)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_avgs_work
```
```
In kernel/power/qos.c (ffffffff81108904)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/power/qos.c:pm_qos_update_request_timeout
```
```
In kernel/rcu/srcutree.c (ffffffff81127425)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/livepatch/transition.c (ffffffff81130b50)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/ntp.c (ffffffff8113ec6f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
```
```
In kernel/kprobes.c (ffffffff8118677f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_optimizer
```
```
In kernel/events/core.c (ffffffff81216c79)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
```
In kernel/jump_label.c (ffffffff8122421d)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In mm/vmstat.c (ffffffff828db9b2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_shepherd
```
```
In mm/backing-dev.c (ffffffff8124ec4a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In fs/file_table.c (ffffffff812e64f9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In fs/namespace.c (ffffffff8130a3d4)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/fs-writeback.c (ffffffff828e6857)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/fs-writeback.c:start_dirtytime_writeback
  - fs/fs-writeback.c:wakeup_dirtytime_writeback
```
```
In fs/notify/mark.c (ffffffff81335548)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In block/genhd.c (ffffffff81506319)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:__disk_unblock_events
```
```
In drivers/pci/pci.c (ffffffff8158f5b6)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
  - drivers/pci/pci.c:pci_pme_list_scan
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0a8c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b4033)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:interrupt_event_handler
```
```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815d0f38)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_mkwrite
  - drivers/video/fbdev/core/fb_defio.c:fb_deferred_io_fsync
```
```
In drivers/xen/grant-table.c (ffffffff81671693)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/balloon.c (ffffffff816730cc)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:balloon_set_new_target
  - drivers/xen/balloon.c:balloon_process
```
```
In drivers/regulator/core.c (ffffffff82901a0a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_init_complete
```
```
In drivers/base/dd.c (ffffffff8170d71f)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_initcall
```
```
In drivers/base/firmware_loader/main.c (ffffffff817279f4)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81737ef2)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/block/xen-blkfront.c (ffffffff8173ec01)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
```
In drivers/nvdimm/security.c (ffffffff81771191)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/nvdimm/security.c:nvdimm_security_store
  - drivers/nvdimm/security.c:__nvdimm_security_overwrite_query
```
```
In drivers/scsi/scsi_error.c (ffffffff8177f22c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/ata/libata-scsi.c (ffffffff817aa84b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_scan_host
```
```
In drivers/ata/libata-eh.c (ffffffff817b0685)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
```
```
In drivers/ata/libata-sff.c (ffffffff817b2e38)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
```
```
In drivers/usb/core/hub.c (ffffffff817fa571)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:led_work
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181ae12)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffff81821367)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_handle_hcd_intr
```
```
In drivers/input/input-poller.c (ffffffff8186980b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186e6f6)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_schedule_event_work
  - drivers/input/keyboard/atkbd.c:atkbd_event_work
```
```
In drivers/media/cec/cec-adap.c (ffffffff81886a25)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8189142f)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81893d1a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In drivers/edac/wq.c (ffffffff818cc2a5)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/edac/wq.c:edac_queue_work
```
```
In drivers/mmc/core/core.c (ffffffff818e788b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
  - drivers/mmc/core/core.c:_mmc_detect_change
```
```
In drivers/mmc/core/sdio.c (ffffffff818f1a9b)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff818f424d)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/devfreq/devfreq.c (ffffffff81909b9a)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In drivers/ras/cec.c (ffffffff8291bfcd)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_init
```
```
In net/core/neighbour.c (ffffffff819592fb)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_periodic_work
```
```
In net/core/link_watch.c (ffffffff819643e9)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/page_pool.c (ffffffff8197a95f)
Location: include/linux/workqueue.h:505
Inline: True
```
```
In net/core/netpoll.c (ffffffff8197e00c)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_skb_on_dev
  - net/core/netpoll.c:queue_process
```
```
In net/core/devlink.c (ffffffff819962c1)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_register
```
```
In net/ipv4/devinet.c (ffffffff829231ba)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_init
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:check_lifetime
  - net/ipv4/devinet.c:__inet_insert_ifa
```
```
In net/rfkill/core.c (ffffffff81ab4155)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_poll
```
```
In net/rfkill/input.c (ffffffff81ab4631)
Location: include/linux/workqueue.h:505
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_schedule_ratelimited
```
</details>
</li>
</ul>

## Differences
