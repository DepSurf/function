# Function: <code>queue_work</code>

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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044872)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In kernel/kmod.c (ffffffff810962db)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8109869e)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In kernel/pid.c (ffffffff8109df86)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810a28b5)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/async.c (ffffffff810a3383)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule
```
```
In kernel/sched/clock.c (ffffffff810b12d9)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810d650b)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff810dc12a)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/hrtimer.c (ffffffff810ef806)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff810f8441)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
```
In kernel/acct.c (ffffffff8110bdf3)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup.c (ffffffff81112100)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/cgroup.c:css_free_rcu_fn
  - kernel/cgroup.c:css_release
```
```
In kernel/cpuset.c (ffffffff8111b0d6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_track_online_nodes
  - kernel/cpuset.c:cpuset_migrate_mm
  - kernel/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/bpf/core.c (ffffffff811710f4)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff81172e96)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In mm/backing-dev.c (ffffffff811ae206)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff811b00d1)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_need_to_extend
```
```
In mm/vmalloc.c (ffffffff811cee62)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In mm/swapfile.c (ffffffff811d3f54)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
```
```
In mm/memcontrol.c (ffffffff811f9a5b)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:__memcg_kmem_get_cache
```
```
In mm/vmpressure.c (ffffffff81200837)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In fs/super.c (ffffffff8120e800)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/super.c:destroy_super_rcu
  - fs/super.c:emergency_remount
```
```
In fs/fs-writeback.c (ffffffff81235de0)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff8124088d)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/buffer.c (ffffffff8124483d)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/buffer.c:emergency_thaw_all
```
```
In fs/direct-io.c (ffffffff81249b8b)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/aio.c (ffffffff8125b579)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
```
```
In fs/kernfs/file.c (ffffffff8128b12b)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff8129fbd1)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In fs/ext4/readpage.c (ffffffff812e2dc4)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/ext4/readpage.c:mpage_end_io
```
```
In fs/pstore/platform.c (ffffffff81320276)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In security/keys/gc.c (ffffffff8132ef56)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_schedule_gc_links
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/key.c (ffffffff8132fc01)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff813952d4)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In crypto/chainiv.c (ffffffff813a2146)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In block/bio.c (ffffffff813b03fa)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
  - block/bio.c:bio_check_pages_dirty
```
```
In block/blk-core.c (ffffffff813b5c96)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - block/blk-core.c:kblockd_schedule_work
```
```
In block/blk-ioc.c (ffffffff813bee9b)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In block/blk-throttle.c (ffffffff813dbaf4)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff813e742b)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In lib/rhashtable.c (ffffffff814005ba)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff81400e0e)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8144a2e6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_queue
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff8144ad6b)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff8144b7ba)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144f3a2)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff81459a0b)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/console/fbcon.c (ffffffff814600c6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff8147a3ee)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
```
```
In drivers/acpi/device_pm.c (ffffffff8147d032)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In drivers/acpi/ec.c (ffffffff814837dc)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_query
```
```
In drivers/acpi/thermal.c (ffffffff814afd24)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff814cc9b2)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff814d17ec)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff814d2436)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff814d5706)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/tty/tty_io.c (ffffffff814dfa16)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_hangup
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:do_SAK
```
```
In drivers/tty/tty_buffer.c (ffffffff814ea600)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
```
```
In drivers/tty/sysrq.c (ffffffff814ed8bd)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_SAK
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f1f5d)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff814f6fe1)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_unregister_con_driver
  - drivers/tty/vt/vt.c:scrollback
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:set_console
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fd894)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff8150dba6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81510a40)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff815126ed)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff815163ca)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:control_intr
  - drivers/char/virtio_console.c:config_intr
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81524af6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff8154b540)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8155637e)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
```
```
In drivers/base/firmware_class.c (ffffffff8155f2c4)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff81560819)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/virtio_blk.c (ffffffff8157167d)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed
```
```
In drivers/block/xen-blkfront.c (ffffffff815731c6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8157b7b9)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8158b80c)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff8158c122)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff815a8568)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff815aa181)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ae018)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff815c262e)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff815d8dff)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff815dc886)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/phy/phy.c (ffffffff815e9fa3)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
```
```
In drivers/net/virtio_net.c (ffffffff815f154d)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_config_changed
  - drivers/net/virtio_net.c:virtnet_probe
```
```
In drivers/usb/core/hub.c (ffffffff81603ef2)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
  - drivers/usb/core/hub.c:usb_queue_reset_device
```
```
In drivers/usb/core/hcd.c (ffffffff8160c72f)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81611f93)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff816256fe)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81643928)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81663776)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff81674309)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/power_supply_core.c (ffffffff8167ed0c)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_changed
```
```
In drivers/power/charger-manager.c (ffffffff81680cf6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/power/charger-manager.c:cm_monitor_poller
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:cm_notify_event
```
```
In drivers/md/md.c (ffffffff8168dac5)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_reap_sync_thread
```
```
In drivers/md/dm.c (ffffffff816a08c1)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_blk_close
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_queue_flush
```
```
In drivers/md/dm-stripe.c (ffffffff816a7c7f)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff816ab654)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:complete_io
  - drivers/md/dm-kcopyd.c:segment_complete
```
```
In drivers/cpufreq/cpufreq.c (ffffffff816af307)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
  - drivers/cpufreq/cpufreq.c:cpufreq_resume
```
```
In drivers/leds/led-core.c (ffffffff816cdca0)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff816d11c0)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8170fc1a)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/core/net_namespace.c:__put_net
```
```
In net/core/sock_diag.c (ffffffff8173362c)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/flow.c (ffffffff817345ca)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_deferred
```
```
In net/core/netpoll.c (ffffffff81738aa6)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_free_async
```
```
In net/netlink/af_netlink.c (ffffffff8174ce77)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_release
```
```
In net/ipv4/inet_fragment.c (ffffffff817a1eb6)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1156)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/xfrm/xfrm_state.c (ffffffff817b7470)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/ipv6/route.c (ffffffff817d57cd)
Location: include/linux/workqueue.h:469
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff81809ee8)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff8181133c)
Location: include/linux/workqueue.h:469
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_register
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810448c2)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In kernel/fork.c (ffffffff81080057)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async
```
```
In kernel/kmod.c (ffffffff810996b3)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8109bc5d)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In kernel/pid.c (ffffffff810a1601)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810a5fe6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/async.c (ffffffff810a6a9b)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule
```
```
In kernel/sched/clock.c (ffffffff810b3e59)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810db38b)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff810e183a)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/time/hrtimer.c (ffffffff810f68fc)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff810ff6b1)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
```
In kernel/acct.c (ffffffff81113653)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup.c (ffffffff81119870)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release
  - kernel/cgroup.c:css_free_rcu_fn
```
```
In kernel/cpuset.c (ffffffff81122f66)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_track_online_nodes
  - kernel/cpuset.c:cpuset_update_active_cpus
  - kernel/cpuset.c:cpuset_migrate_mm
```
```
In kernel/bpf/core.c (ffffffff8117e7b4)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff81180dd6)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In mm/backing-dev.c (ffffffff811c7586)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff811c9926)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In mm/vmalloc.c (ffffffff811ebff2)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In mm/swapfile.c (ffffffff811f1d70)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
```
```
In mm/zswap.c (ffffffff811f639f)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/memcontrol.c (ffffffff8121ef86)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff81224f64)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff8122a416)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
```
```
In fs/super.c (ffffffff81237148)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff8125f740)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff81268bb8)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/buffer.c (ffffffff8126cd68)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/buffer.c:emergency_thaw_all
```
```
In fs/direct-io.c (ffffffff81272683)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/aio.c (ffffffff81284175)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
```
```
In fs/crypto/crypto.c (ffffffff812886b7)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_bio_pages
```
```
In fs/mbcache.c (ffffffff81298c8f)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/kernfs/file.c (ffffffff812b865b)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff812ce487)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81355966)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In security/keys/gc.c (ffffffff81363dfd)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff81364952)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813bc4c2)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/yama/yama_lsm.c (ffffffff813d0cf4)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In crypto/drbg.c (ffffffff813eb9b6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff813f65df)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff813fab66)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff81402bdd)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-throttle.c (ffffffff81421667)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff8142d6ab)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In lib/rhashtable.c (ffffffff81447ac7)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff81448599)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814965a6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_queue
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff81496ffb)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff81497a3a)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff8149831f)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149bf71)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff814a7963)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/console/fbcon.c (ffffffff814adfb6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff814c89fb)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/device_pm.c (ffffffff814cb7e8)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff814cd27f)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_sb_notify
```
```
In drivers/acpi/scan.c (ffffffff814d0303)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff814d2d2b)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff814ff659)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81513caa)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8151d522)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815224e9)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81523166)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff815264d6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/tty/tty_io.c (ffffffff81530a6b)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8153bd16)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8153edfe)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81542b7d)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81547c28)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_unregister_con_driver
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154e3b4)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff8155fe9f)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81562fc0)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff81566a1c)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff81569050)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81577b06)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff8159d233)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815a895a)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff815af876)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:genpd_poweroff_unused
  - drivers/base/power/domain.c:genpd_poweron
```
```
In drivers/base/firmware_class.c (ffffffff815b366c)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff815b4f79)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/virtio_blk.c (ffffffff815c6e5d)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed
```
```
In drivers/block/xen-blkfront.c (ffffffff815ca1e6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815d0808)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff815e0a8c)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff815e1372)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff81600418)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816020ee)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81605ee8)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff8161adbe)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff81632afe)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff81636606)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/phy/phy.c (ffffffff81648a73)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
```
```
In drivers/net/virtio_net.c (ffffffff816546a2)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed
```
```
In drivers/usb/core/hub.c (ffffffff81664666)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff8166c2df)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81671ef3)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81683d89)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a43fb)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff816c3976)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff816d4af9)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/power_supply_core.c (ffffffff816dfa18)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:power_supply_changed
```
```
In drivers/power/charger-manager.c (ffffffff816e26dd)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/power/charger-manager.c:charger_extcon_notifier
  - drivers/power/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff816f7220)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff81701cd1)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8170813b)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8170bbe3)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81710ce4)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
```
In drivers/leds/led-core.c (ffffffff81730dbc)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness
```
```
In drivers/firmware/efi/vars.c (ffffffff81734460)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8177754a)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/core/net_namespace.c:__put_net
```
```
In net/core/sock_diag.c (ffffffff8179f0ec)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/flow.c (ffffffff817a14c6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_deferred
```
```
In net/core/netpoll.c (ffffffff817a4d76)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_free_async
```
```
In net/netlink/af_netlink.c (ffffffff817ba414)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff8180fb76)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8182163f)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff818244b0)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/ipv6/route.c (ffffffff81843be8)
Location: include/linux/workqueue.h:470
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8187b9e8)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff81884ef6)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
```
```
In net/switchdev/switchdev.c (ffffffff8188a809)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff818902ce)
Location: include/linux/workqueue.h:470
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_start_dev
  - net/ncsi/ncsi-manage.c:ncsi_free_request
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810464d6)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In kernel/fork.c (ffffffff810849b7)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async
  - kernel/fork.c:__put_task_struct
```
```
In kernel/kmod.c (ffffffff8109e663)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810a0c9d)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In kernel/pid.c (ffffffff810a66c1)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810abc46)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/async.c (ffffffff810ac6fb)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule
```
```
In kernel/sched/clock.c (ffffffff810ba499)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810e1e5b)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff810e8186)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/tree.c (ffffffff810f361d)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810fd91c)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff81102521)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:clocksource_mark_unstable
```
```
In kernel/acct.c (ffffffff8111ad63)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup.c (ffffffff81121350)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/cgroup.c:css_release
  - kernel/cgroup.c:css_free_rcu_fn
```
```
In kernel/cpuset.c (ffffffff8112ae16)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_track_online_nodes
  - kernel/cpuset.c:cpuset_update_active_cpus
  - kernel/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff81130852)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff8118a3c4)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff8118ce56)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In mm/backing-dev.c (ffffffff811d76a6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff811d9a16)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In mm/vmalloc.c (ffffffff811fd45f)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff81202760)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/swapfile.c:swap_entry_free
```
```
In mm/zswap.c (ffffffff81206d2f)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/memcontrol.c (ffffffff81231496)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff81237554)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff8123c966)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
```
```
In fs/super.c (ffffffff81249df8)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff81272c60)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff8127bb98)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/buffer.c (ffffffff8127fff8)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/buffer.c:emergency_thaw_all
```
```
In fs/direct-io.c (ffffffff812861a3)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/aio.c (ffffffff81297de5)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
```
```
In fs/crypto/crypto.c (ffffffff8129d3b7)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_decrypt_bio_pages
```
```
In fs/mbcache.c (ffffffff812ad70b)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812b1609)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff812cddfb)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff812e4277)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8136bd96)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In security/keys/gc.c (ffffffff8137a619)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff8137b172)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813d36cb)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
```
In security/yama/yama_lsm.c (ffffffff813e83f4)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In crypto/drbg.c (ffffffff814051f6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff8140ffbf)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814144a6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff8141c90d)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-throttle.c (ffffffff8143ca05)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff8144748b)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In lib/rhashtable.c (ffffffff81466ac4)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff81466f89)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b7f46)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_queue
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814b8953)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff814b93ba)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814b9bcf)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bdb01)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff814c9a73)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/console/fbcon.c (ffffffff814d00b6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff814ea93f)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/device_pm.c (ffffffff814ed716)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In drivers/acpi/bus.c (ffffffff814ef1ad)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_sb_notify
```
```
In drivers/acpi/scan.c (ffffffff814f226d)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff814f51fc)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81522353)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815400ea)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815499f2)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8154e9c9)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff8154f646)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff815529f6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81552e76)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff8155d1bb)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81568376)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8156b44e)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff8156f1bd)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff815744a6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:do_unregister_con_driver
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157ac34)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff8158c5ef)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8158f730)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff8159317c)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff815957b0)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff815a3ff6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff815cb773)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815d7448)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff815de558)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:genpd_poweroff_unused
  - drivers/base/power/domain.c:genpd_poweron
```
```
In drivers/base/firmware_class.c (ffffffff815e29fc)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff815e4229)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff815f6e46)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff815fd418)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8160d72c)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff8160e012)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff8162faf8)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816317de)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff816354a8)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff8164ba3e)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff81663c4e)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff816676a6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/phy/phy.c (ffffffff81679d73)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
```
```
In drivers/usb/core/hub.c (ffffffff81692186)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81699fdf)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff8169fba3)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff816b0319)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816d24fb)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff816f1936)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff817047d9)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8170fe88)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81712b4d)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff81728a99)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff81733b21)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:flush_current_bio_list
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8173a00b)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8173dc13)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81744959)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8174f222)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81763a5c)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff81767d90)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817a45ca)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/core/net_namespace.c:__put_net
```
```
In net/core/dev.c (ffffffff817ac630)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In net/core/sock_diag.c (ffffffff817cdabc)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/flow.c (ffffffff817cfde6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_deferred
```
```
In net/core/netpoll.c (ffffffff817d37e6)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_free_async
```
```
In net/netlink/af_netlink.c (ffffffff817e9a86)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff818410c6)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81852e4f)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff818560d5)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/ipv6/route.c (ffffffff8187595f)
Location: include/linux/workqueue.h:484
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818a51f4)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/wireless/wext-core.c (ffffffff818b02a8)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff818b9766)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
```
```
In net/switchdev/switchdev.c (ffffffff818bebb9)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff818c36fc)
Location: include/linux/workqueue.h:484
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_free_request
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046166)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104c711)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff81081898)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async
  - kernel/fork.c:__put_task_struct
```
```
In kernel/kmod.c (ffffffff8109bcc8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/kmod.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8109e23b)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In kernel/pid.c (ffffffff810a364c)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810a8816)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/async.c (ffffffff810a92cc)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule
```
```
In kernel/sched/clock.c (ffffffff810b4d71)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810e0f88)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff810e75cd)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/tree.c (ffffffff810f4216)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff810ffbac)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff81104778)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff8111c983)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff81121a50)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
  - kernel/cgroup/cgroup.c:css_free_rcu_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a6c3)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8112c6d6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff81131e9e)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff8118ced4)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff81191985)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In mm/backing-dev.c (ffffffff811e0476)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff811e3096)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In mm/slab_common.c (ffffffff811e5d9a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff81208130)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff8120d0ac)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff812121fd)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
```
```
In mm/slub.c (ffffffff8122ae62)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff8123ccc6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff81243009)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff81248665)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
```
```
In fs/super.c (ffffffff812556f8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff81280040)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff81288f08)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/buffer.c (ffffffff8128d8d8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/buffer.c:emergency_thaw_all
```
```
In fs/direct-io.c (ffffffff81293803)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff8129975f)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In fs/aio.c (ffffffff812a5c59)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
```
```
In fs/crypto/bio.c (ffffffff812ae1b7)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio_pages
```
```
In fs/mbcache.c (ffffffff812bab91)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812bea2b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff812db3e5)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff8131deb6)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813803aa)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In security/keys/gc.c (ffffffff8138e243)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff8138ed42)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff813e6720)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff813f4a66)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In crypto/drbg.c (ffffffff81412986)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff8141d8fd)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81422026)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff81428600)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff8142ab2f)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In block/blk-throttle.c (ffffffff8144b2ed)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff81456002)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff8146c2d6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff8146c449)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c27c8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_queue
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff814c31b1)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff814c3b7a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814c43c3)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c82e1)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff814d59cb)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/console/fbcon.c (ffffffff814dbb86)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff814f67c6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff814fc113)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff814ffb7b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815037ac)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81533f30)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81553f6a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8155d752)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81562af9)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81563d76)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81567226)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815677f6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff81571e3d)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kref_put
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8157b926)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8157fa1f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff8158373d)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81588456)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f034)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff815a072a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
```
```
In drivers/tty/serial/kgdboc.c (ffffffff815a37e0)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff815a6f3b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff815a984f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff815bb218)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff815e0343)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815ebb9a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff815f30b8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/power/domain.c:pm_genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_class.c (ffffffff815f7738)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff815f8e39)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff8160b0c6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816111ba)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8162182c)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81622102)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff81644528)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81646364)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164a6b8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff816604ce)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff816783f1)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff8167be36)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/phy/phy.c (ffffffff8168de83)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
```
```
In drivers/usb/core/hub.c (ffffffff816a78f6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff816af2bf)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff816b4de3)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff816c5661)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816c7e51)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e6b5b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff817071a6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff8171a277)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81728208)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b10e)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff81741270)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff8174cc61)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81753b1f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81757793)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81762fe9)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8176d64e)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff8178205c)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff81786671)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff817997d1)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/core/net_namespace.c (ffffffff817c276a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/core/net_namespace.c:__put_net
```
```
In net/core/dev.c (ffffffff817cadd0)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/core/sock_diag.c (ffffffff817ececc)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/flow.c (ffffffff817ef1e6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_deferred
```
```
In net/core/netpoll.c (ffffffff817f2b26)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_free_async
```
```
In net/netlink/af_netlink.c (ffffffff81809965)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81862946)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff8186b415)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/xfrm/xfrm_policy.c (ffffffff81876b0d)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81879d35)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/ipv6/route.c (ffffffff81899fee)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff818cbcaa)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/wireless/wext-core.c (ffffffff818d6c6b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff818e013a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_any_led_trigger_activate
```
```
In net/switchdev/switchdev.c (ffffffff818e56d3)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff818ea087)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_free_request
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049996)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff8104ffc1)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff8108817b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810a29bb)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810a4a9e)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In kernel/pid.c (ffffffff810a9e77)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810af056)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/async.c (ffffffff810afb5e)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule
```
```
In kernel/sched/clock.c (ffffffff810bc074)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810e9258)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff810ef947)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/tree.c (ffffffff810fe1ef)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In kernel/time/hrtimer.c (ffffffff8110a9c0)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff8110f78e)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff811280a3)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff8112d100)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
  - kernel/cgroup/cgroup.c:css_free_rcu_fn
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8113744d)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81139506)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8113ecbe)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff8119aa04)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff8119e8cb)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811b00e9)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_replace
```
```
In kernel/bpf/sockmap.c (ffffffff811b0a56)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_destroy_psock
  - kernel/bpf/sockmap.c:smap_write_space
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In mm/backing-dev.c (ffffffff811f6466)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff811f8ff6)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In mm/slab_common.c (ffffffff811fbfda)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff8122120e)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff81226f6f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff8122cbfb)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/slub.c (ffffffff81246562)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff8125c184)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff81262e59)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff81268835)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
```
```
In fs/super.c (ffffffff81277888)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff812a2b30)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff812aba48)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/buffer.c (ffffffff812b0488)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/buffer.c:emergency_thaw_all
```
```
In fs/direct-io.c (ffffffff812b66c8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff812bcad5)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff812c91a0)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_rcufn
```
```
In fs/crypto/bio.c (ffffffff812d1bb7)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio_pages
```
```
In fs/mbcache.c (ffffffff812de471)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff812e23fb)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff812ffcd5)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813424c4)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813a53ba)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff813a737f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff813b36e4)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff813b420b)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8140d906)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff8141c9b6)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In crypto/drbg.c (ffffffff8143d106)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff814487b7)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8144ce96)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814536d0)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff81455d26)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In block/blk-throttle.c (ffffffff81477b23)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff81481c49)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff814985d5)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff81498749)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502a08)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv_core.c:aer_recover_queue
```
```
In drivers/pci/pcie/aer/aerdrv.c (ffffffff815033f1)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/aer/aerdrv.c:aer_irq
```
```
In drivers/pci/pcie/pme.c (ffffffff81503dea)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/pcie/pcie-dpc.c (ffffffff815047ec)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:dpc_irq
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508891)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff81515e91)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81524c56)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff815375d6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff8153de83)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff81541d2b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff81545c0e)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff815956b0)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b79aa)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815c1a62)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815c6df9)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff815c7ec6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff815cb476)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff815cb9b6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff815d63b0)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff815e0336)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff815e459f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff815e823d)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff815ecf86)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f3c14)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff81605e5a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81608f20)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff8160d83d)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff8161016f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81621758)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff81647403)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81652f88)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff8165a894)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_class.c (ffffffff8165f6c8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff81660e19)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff81673996)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81679a5a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8168a062)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff8168a942)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff816ad4b8)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816af3ae)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b38e8)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff816c9ade)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff816e1a31)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff816e54d6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/phy/phy.c (ffffffff816f79e3)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
```
```
In drivers/usb/core/hub.c (ffffffff81712cd6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff8171a8af)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81720253)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff81730413)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81731941)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81734301)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8175338b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81778386)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff8178b510)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81799878)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c8ae)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff817b337f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff817bee3e)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff817c5c6a)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff817c99f3)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff817d8f8c)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff817e3404)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff817f83ff)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff817fcad1)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8180fb71)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/core/net_namespace.c (ffffffff8183c0aa)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/core/net_namespace.c:__put_net
```
```
In net/core/dev.c (ffffffff81844610)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818690bc)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/netpoll.c (ffffffff8186e0e6)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_free_async
```
```
In net/sched/cls_api.c (ffffffff8187f556)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_queue_work
```
```
In net/sched/act_api.c (ffffffff81882c09)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff81888866)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff818e2a76)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff818ebbee)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f68fe)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa795)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/ipv6/route.c (ffffffff8191b51e)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81950a4f)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff8195ab76)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff8195c83b)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff81965e3d)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_any_led_trigger_activate
```
```
In net/switchdev/switchdev.c (ffffffff8196b80e)
Location: include/linux/workqueue.h:486
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff8197020c)
Location: include/linux/workqueue.h:486
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
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
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c1f5)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/dev-mcelog.c (ffffffff81052cef)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff8108bf00)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/fork.c:mmput_async
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810a9301)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810ac28d)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/pid.c (ffffffff810b0a97)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810b5e95)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/async.c (ffffffff810b69cd)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule
```
```
In kernel/sched/clock.c (ffffffff810c3704)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810f158b)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff810f7d48)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/tree.c (ffffffff81107017)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/time/timer.c (ffffffff81114d95)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff811162b0)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff8111b18d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff81135ef3)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff8113b788)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145cff)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81147ce5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8114cf05)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811b0608)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811b4fcf)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811ca3fa)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/bpf/sockmap.c (ffffffff811cc6b5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_destroy_psock
  - kernel/bpf/sockmap.c:smap_write_space
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In mm/backing-dev.c (ffffffff81217745)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8121aa05)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In mm/slab_common.c (ffffffff8121d324)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff812430be)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff81248f6f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff8124fae6)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/slub.c (ffffffff8126998f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff81280455)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff81287238)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff8128d9d5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
```
```
In fs/super.c (ffffffff8129e214)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff812c9786)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff812d2854)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff812df54b)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff812e56dc)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff812f2873)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In fs/crypto/crypto.c (ffffffff812f9f85)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/mbcache.c (ffffffff8130a6b1)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff8130e915)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8132d9f3)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff8137036c)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813d44e7)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff813d685e)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff813e3fa5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff813e48bb)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8143f062)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff8144eab4)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In crypto/drbg.c (ffffffff8146ff45)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff81479006)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81480105)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff81486d48)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814890a4)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In block/blk-throttle.c (ffffffff814ac15a)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff814b6877)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff814cd7b8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff814cd969)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In drivers/pci/pcie/aer.c (ffffffff8153339e)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_irq
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff81534c6a)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/pcie/dpc.c (ffffffff815355d1)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/pci/pcie/dpc.c:dpc_irq
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539806)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_interrupt_event
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153d719)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff8154cc58)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155a985)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff8156d155)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff81573bb7)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff81577c31)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff8157c1e8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff815ccb97)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815efedc)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815fa10f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815ff599)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81600735)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81603bd5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81604205)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff8160f418)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff816195d5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8161d918)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81621485)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff816263b3)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162cc54)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff8163e8a8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81642640)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff816470c0)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff81649c5e)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8165b7d5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff816828f3)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8168f4a9)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff8169647b)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff8169a130)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff8169c5d0)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff816af9a5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816b550d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816c6172)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff816c69f2)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff816e9778)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816eb692)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff816ef9d1)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff81706496)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff8171e3de)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff81721d75)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/phy/phy.c (ffffffff81734c45)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
```
```
In drivers/usb/core/hub.c (ffffffff817519b5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81759607)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff8175f183)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff8176f510)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81770c7f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81773855)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81793c65)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff817b90a8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff817cd814)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e0b78)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e3d6d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff817faf0c)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff818073ce)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8180e9d4)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81812826)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81821b9c)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8182c8f1)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff818419ff)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff8184625f)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81859a3d)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81886c22)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/core/dev.c (ffffffff8188e390)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818b8f6d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff818bae78)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
```
In net/core/netpoll.c (ffffffff818bf0b5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_free_async
```
```
In net/sched/act_api.c (ffffffff818d667f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_setup_cb_egdev_register
```
```
In net/netlink/af_netlink.c (ffffffff818dc312)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81939238)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819423e9)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194dbaf)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81951295)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/ipv6/route.c (ffffffff8197333a)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff8199eae3)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819a9f40)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff819b4225)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff819b6016)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff82743a61)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff819c526e)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff819c9893)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff819ccf89)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff819dac30)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff810498e5)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8105035f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff810934cb)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810b21f1)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810b516d)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/pid.c (ffffffff810b9b67)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810bf125)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/async.c (ffffffff810bfa6d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/async.c:__async_schedule
```
```
In kernel/sched/clock.c (ffffffff810cc9ec)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810fcc1b)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81103498)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff828ae402)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff81111bcc)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/time/timer.c (ffffffff811203d5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff811218f0)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff811267d1)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff81141683)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff81146e98)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811518bf)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81153855)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff81159b25)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811bec88)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811c339f)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811ddd1a)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811df72e)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In mm/backing-dev.c (ffffffff8122a655)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8122d9b5)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In mm/slab_common.c (ffffffff81230314)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_deactivate_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff812577ce)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff8125d9ac)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff81264086)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/slub.c (ffffffff8127e24f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff81295935)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff8129c188)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff812a31d5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
```
```
In fs/super.c (ffffffff812b31d4)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff812de9b6)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff812e7c34)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff812f404b)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff812fa2c5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff81309014)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/crypto/crypto.c (ffffffff8130f265)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/mbcache.c (ffffffff81320021)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap.c (ffffffff81324ef6)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff81344de7)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813887fc)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813eeab7)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff813f0eeb)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - ipc/util.c:ipc_set_key_private
  - ipc/util.c:ipc_rmid
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff813fe795)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff813ff0cb)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8145bf77)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff8146ba84)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In crypto/drbg.c (ffffffff8148d6c5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff81499a81)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8149d185)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814a1368)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814a2fd4)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In block/blk-throttle.c (ffffffff814c6538)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff814c9f77)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff814e1991)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff814e2039)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In drivers/pci/pcie/aer.c (ffffffff8154aabe)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8154c30a)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554ae9)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff81563cc8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81572475)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff81584d15)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff8158b7d7)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8158f871)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815938a8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff815e6177)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a546)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff816151bf)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8161a669)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff8161b805)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff8161ec75)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8161f2a5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff8162c3c8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81636845)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8163ab6e)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163e965)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff816438a3)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164af24)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff8165caa8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816607b0)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff81665560)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff81667f5e)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81675f35)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff816a2433)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816af835)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff816b6b4b)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff816ba993)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff816bcf60)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff816cfaf5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff816d676d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816e7572)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff816e7e12)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff8170d278)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8170f183)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81713171)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff81728886)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff81740cbe)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff81744625)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/usb/core/hub.c (ffffffff81775e15)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff8177db77)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81783903)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff81793b90)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff8179598e)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817993a5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817ba235)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff817e04b8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff817f48b0)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8180c1b8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f69d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff81826fc5)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff818333fe)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8183a994)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8183e7a6)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8184da45)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:__cpufreq_get
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81858501)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff8186d91f)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff8187248f)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8187593d)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81878cdd)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818a7312)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/core/dev.c (ffffffff818af2a0)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818dfbbd)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff818e1f0a)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
```
In net/core/skmsg.c (ffffffff818e5e36)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/sched/cls_api.c (ffffffff81901b38)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff81908ce4)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81968e05)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_kill
```
```
In net/ipv4/ipmr.c (ffffffff819721e6)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980f32)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff81984c4a)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a8f90)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d54d8)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e0a6c)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff819eb255)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff819ed2d6)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff828fdd7f)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff819fc8be)
Location: include/linux/workqueue.h:509
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a01463)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81a061d9)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff81a12ed0)
Location: include/linux/workqueue.h:509
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c895)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8105346f)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff81099ac3)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810b7d7d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810baf79)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In kernel/pid.c (ffffffff810bfa77)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810c5235)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810d4ddc)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff81105324)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff8110be81)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff828c6ddb)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff8111b4fa)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff81120284)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
```
```
In kernel/livepatch/transition.c (ffffffff81121b00)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/timer.c (ffffffff8112acc5)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff8112c200)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff81131201)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/module.c (ffffffff81148713)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff8114cd84)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff81152068)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d286)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8115fe75)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8116627e)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811cebc8)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811d40ed)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f33ea)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811f50a0)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffffffff811f71c6)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In mm/backing-dev.c (ffffffff8123a2c5)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8123d6e5)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In mm/slab_common.c (ffffffff81240485)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
```
```
In mm/vmalloc.c (ffffffff812697b3)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff81278c2c)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff8127efd6)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/slub.c (ffffffff8129a5eb)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff812b195a)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff812b7319)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff812be540)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff812cff34)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff812fd0a6)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff813064f4)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff813159c8)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff8131acc6)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff8132ada8)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff8132e59c)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffffffff813367f5)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/mbcache.c (ffffffff813478c7)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff8134d5ee)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8136d047)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813b28e4)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8141ad87)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8141d090)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff8142addd)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff8142b29a)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff81489ddb)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff81498a74)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In crypto/drbg.c (ffffffff814bb045)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff814c7ba7)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814cb325)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814ce418)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814d108c)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f187d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff814f4d93)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff814f8839)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff8150d937)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff8150dee9)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffffffff81538b8b)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In lib/dim/rdma_dim.c (ffffffff81538d4f)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff8157a9fe)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8157bffc)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8158434d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff8159404d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a2975)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff815b5925)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff815bc617)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815c04e1)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815c47ec)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81617d74)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e336)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8164905f)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8164e419)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff8164f485)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81652275)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81652895)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff81660318)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8166aa95)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8166eefa)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81672eb5)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81677cb3)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8167fa54)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff81691da8)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81696357)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff8169b196)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff8169d9ee)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816abd4d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff816db177)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816e939b)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff816f099b)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff816f4f1e)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff816f7790)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff8170baf5)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81711f3d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81720d32)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff817215f2)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff81748d9c)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8174a925)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174ea41)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff81763fb0)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff8177a0cf)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffffffff817803e5)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/usb/core/hub.c (ffffffff817b3be5)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff817bee56)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff817c1c13)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff817d2490)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817d532d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817de85d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f9bd3)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81820d75)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff818358f8)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184de28)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851d2a)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff8186945d)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff8187532e)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8187d524)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818814e6)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81890088)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8189bdbb)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff818b1b8f)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818b66af)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818b9b2e)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818bdfaf)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In net/core/net_namespace.c (ffffffff818f2a62)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In net/core/dev.c (ffffffff818fb0dc)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8192e20e)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff819308b3)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In net/core/skmsg.c (ffffffff81935576)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/sched/cls_api.c (ffffffff81962b37)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/sched/cls_api.c:__tc_indr_block_cb_register
```
```
In net/netlink/af_netlink.c (ffffffff8196706a)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819cfc74)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff819dbc2a)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ead25)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819eed5b)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a15a79)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a4443f)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a4f748)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff81a5a425)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81a5c4c2)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff8291a966)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81a6bc0d)
Location: include/linux/workqueue.h:487
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a705c1)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81a75ae8)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff81a82330)
Location: include/linux/workqueue.h:487
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d255)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053d5f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff8109ff47)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810be27d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c11d9)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (ffffffff810c5e47)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810ce335)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810df39c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff811116a5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81118281)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff828cf3f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811278a2)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff8112c9a4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
```
```
In kernel/livepatch/transition.c (ffffffff8112e120)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/timer.c (ffffffff81136c65)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff81138220)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff8113d141)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/module.c (ffffffff81154593)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff81158a54)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff8115dcb8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168e86)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8116bb45)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8117213e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811db1e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811e047d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8120018a)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff812020a4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffffffff81204186)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff8121e1fb)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (ffffffff812485c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8124bb35)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (ffffffff8124e895)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff812786f3)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff8128871c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff8128ea22)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff81292f15)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (ffffffff812aa4ab)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff812c334a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff812c91e9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff812d0430)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff812e1b44)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff8130f596)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff81319574)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff81328848)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff8132d836)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff8133bfe5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff81343459)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffffffff8134a3e5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff81351115)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff8135f8d7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff813658ae)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff813851c7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813cb932)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81434bd7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff81436ee0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff81444b2d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff81444fea)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814a3c9b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff814b29a4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffff814d3e15)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff814e0ca7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814e4515)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814e7728)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814ea44c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150ae6d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff8150e3b7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff815166c9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff8152b787)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff8152bd39)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffffffff815599ab)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (ffffffff81559b6f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff8159c43e)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8159da5c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a5d2d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff815b51ad)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c37f5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff815d6b55)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff815dd8d7)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815e17a1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815e5a2c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81639384)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660816)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8166b4ff)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166f055)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff816708f9)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81671a35)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81674815)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81674e35)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff81682968)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8168d185)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81691502)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81695635)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff8169a443)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2104)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff816b4898)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816b8ee7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff816bdebf)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff816c075e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816ceabd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff816ff147)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8170d3fb)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff81714e3b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff8171931e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff8171bbf0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff8172fdf5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff8173623d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81744eb2)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81745892)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff8176ceec)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8176ea95)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81772bf1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff81787fa0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff817a065b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff817a40a5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff817d1ead)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff817d2766)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff817e4315)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff817ef7c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff817f2593)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff81803360)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818061dd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180f7ad)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8182aa0d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff818521e5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff818670c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187f868)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81882f5a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff8189b1fd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff818a70de)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff818af304)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818b3386)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818c2288)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818cdf2b)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff818e433f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818e900f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818ec5ce)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818f0aff)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f551f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_report_crash
```
```
In net/core/net_namespace.c (ffffffff819249c2)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/dev.c (ffffffff8192d22c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8196049e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81962e8f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff8196405a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff8196834f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffff81974817)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff8199dafa)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a06804)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff81a12b5a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21d25)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25c2f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a4c6b9)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a7b02f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a863d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff81a91075)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81a930ef)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff829247d5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81aa25ed)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81aa6df1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81aac968)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff81ab9540)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052264)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81058d6f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106bbc7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
```
```
In kernel/fork.c (ffffffff810a519a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810c557d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c94db)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In kernel/reboot.c (ffffffff810d8105)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810e768c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110bac9)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sched_cpufreq_governor_change
```
```
In kernel/power/wakelock.c (ffffffff8111c775)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81123ad7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff82cf058e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff81137aa7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff8113afb1)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/pool.c (ffffffff8113f899)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In kernel/time/timer.c (ffffffff811458b5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff81147030)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff8114be21)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:__clocksource_unstable
```
```
In kernel/module.c (ffffffff81165dbb)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff811696d3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff8116e6a8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117ac36)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8117db65)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff811846bf)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/trace/trace.c (ffffffff811ba9d0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/bpf/core.c (ffffffff811f8ef0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff81200b6a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
```
```
In kernel/bpf/arraymap.c (ffffffff8121a516)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/cpumap.c (ffffffff8122879a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff8122942e)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff8122c0c6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff8124a706)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff81276785)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8127b356)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff8127ccb5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff812ac4fd)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff812bb169)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff812c273f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff812c67c5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In mm/slub.c (ffffffff812df1ce)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff812f8e0a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff812fe849)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff813069e0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff81318e54)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff81348cc6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff813533c4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff81362018)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff813678e8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff81378c27)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff813855de)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/crypto/crypto.c (ffffffff8138fd15)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff81397b85)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff813a5617)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff813adae7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff813d04c7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff814173cc)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_add_complete_io
```
```
In fs/pstore/platform.c (ffffffff81484e49)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff81486aae)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/namespace.c (ffffffff81495010)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In security/keys/gc.c (ffffffff81495b88)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
  - security/keys/gc.c:key_schedule_gc
```
```
In security/keys/key.c (ffffffff81495edd)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814feafb)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff81511c94)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In crypto/drbg.c (ffffffff815346f5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff8153faf8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81543065)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff815473d8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff815493ca)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-cgroup.c (ffffffff8156beed)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff8156ee77)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff81576e59)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff81581e4d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In lib/rhashtable.c (ffffffff8158ecfb)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff8158f749)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/crc-t10dif.c (ffffffff8159a789)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/dim/net_dim.c (ffffffff815e322d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff815e345f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In lib/vsprintf.c (ffffffff815f41b0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
```
```
In drivers/pci/pcie/aer.c (ffffffff8163c02e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff8163dadc)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8164ea0d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/rapidio/rio.c (ffffffff8165e18d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166dca5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff81680885)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff81687f87)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_sb_notify
```
```
In drivers/acpi/scan.c (ffffffff8168c491)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff81690cdd)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/acpi/thermal.c (ffffffff816e6114)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff817104b7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171b83f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171f9aa)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817211e9)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff81722135)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81725235)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81725b05)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff817344fa)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f255)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81743b44)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81749165)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff8174dc23)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817550c4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff817684f8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8176d570)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff81770a90)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff81774bee)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff817839bc)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff817b8d57)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817c8941)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff817d036b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff817d4dce)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff817d7d60)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff817ec995)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817f3eed)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff818024d2)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff818037e2)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff8182f04c)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81830fe1)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81835c31)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81849376)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff8184d5e0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff81862c0f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffffffff81869665)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff8189d374)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff8189d816)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff818b2dc5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff818bc0b7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff818c1d53)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff818d3e16)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818d6756)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_conn_id_status_change_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff818e04dc)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_change_bus_speed
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818fc86c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81924095)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff8193a748)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ecf8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff8195195c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff8196a77b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff81977a71)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8197fc24)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8198416d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81994998)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8199e8ec)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_acpi_perf_limits
```
```
In drivers/leds/led-core.c (ffffffff819b7540)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness_nosleep
```
```
In drivers/firmware/efi/vars.c (ffffffff819bc08f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_run_worker
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819bfefe)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c3658)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb931)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f8d5d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a0088d)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81a339fe)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81a3617e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/skmsg.c (ffffffff81a3c580)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffff81a499a4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff81a793a0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81af5088)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b01e4a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13672)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1b62d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/espintcp.c (ffffffff81b2355d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff81b426ce)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81b753da)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b815de)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/strparser/strparser.c (ffffffff81b8c485)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81b8e400)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff81b979d7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81b9dfcd)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba2c79)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81ba8c65)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/mptcp/protocol.c (ffffffff81bac1c8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_acked
```
```
In net/mptcp/pm.c (ffffffff81bb22c3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_schedule_work
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051454)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81057b7f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81bd6b34)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
```
```
In kernel/fork.c (ffffffff810a08bd)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810c08ad)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c461b)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In kernel/reboot.c (ffffffff810d33c5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810e52cc)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff81108a79)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sched_cpufreq_governor_change
```
```
In kernel/power/wakelock.c (ffffffff811170d5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff8111f927)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff82fdcf29)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811330e7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:schedule_page_work_fn
```
```
In kernel/livepatch/core.c (ffffffff81135aa1)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/pool.c (ffffffff8113ae89)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In kernel/time/timer.c (ffffffff81141e95)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff811434d0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/ntp.c (ffffffff811475ea)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_timer_callback
```
```
In kernel/time/clocksource.c (ffffffff81148281)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:__clocksource_unstable
```
```
In kernel/module.c (ffffffff811624e3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff81165e03)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff8116b0a6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81177a36)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8117a9b5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8118171d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/trace/trace.c (ffffffff82fe2961)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/bpf/core.c (ffffffff811f7f30)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff8120002a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
```
```
In kernel/bpf/arraymap.c (ffffffff8121d236)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/trampoline.c (ffffffff81222504)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu
```
```
In kernel/bpf/cpumap.c (ffffffff8122f66a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff81230fbe)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812344b6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff81254ab6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff81281095)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff81285e08)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff81287faa)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/vmalloc.c (ffffffff812b7566)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff812c6c09)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff812ce555)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff812d23c5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/hugetlb.c:free_huge_page
```
```
In mm/memcontrol.c (ffffffff81304d0a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff8130ab89)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff81312720)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff81324394)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff81355c26)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff8135fca4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff8136f308)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff81374c48)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff81386957)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff813966d2)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/crypto/crypto.c (ffffffff813a1380)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff813a9410)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff813b6377)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff813bf157)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff813e2097)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff8142adcc)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_add_complete_io
```
```
In fs/ext4/super.c (ffffffff814494a8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/pstore/platform.c (ffffffff814a2589)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff814a415e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/namespace.c (ffffffff814b2a30)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In security/keys/gc.c (ffffffff814b35e8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
  - security/keys/gc.c:key_schedule_gc
```
```
In security/keys/key.c (ffffffff814b393d)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8151bd5b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff8152eb1d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In crypto/drbg.c (ffffffff81551645)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff8155c318)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8155f8b5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff815651ea)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-cgroup.c (ffffffff81586bfd)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff81589c31)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff81593b66)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff8159ee1d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In lib/rhashtable.c (ffffffff815ab85b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff815ac279)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/crc-t10dif.c (ffffffff815b61e5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/dim/net_dim.c (ffffffff816076a5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff81607904)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In lib/vsprintf.c (ffffffff81618820)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
```
```
In drivers/pci/pcie/aer.c (ffffffff81662fce)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff8166416c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8167297d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/rapidio/rio.c (ffffffff8167e7ad)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8168e255)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff8169f380)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff816a5cf7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_sb_notify
```
```
In drivers/acpi/scan.c (ffffffff816aa511)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff816aea0d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:acpi_ec_submit_query
```
```
In drivers/acpi/thermal.c (ffffffff81705049)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e6d6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172dd02)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173c90a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8173e149)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff8173ede5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff817421f5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817428f5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff8175064a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8175b185)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8175fad3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81764ea5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff817691f3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817703c4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81783258)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81787fd0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff8178bb00)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff8178f93e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8179af4c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff817cdac7)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817dd735)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff817e49db)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff817e986e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff817ec770)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff818012c5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81807b4d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81813362)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81814532)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff8184006c)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81841c21)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81846741)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81859631)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff8185d9d0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff81871a1f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffffffff81878470)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff818abfa4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff818ac3f6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff818c1735)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff818c9127)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff818cdf63)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff818de1b6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818e0936)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_conn_id_status_change_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c1f553)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_change_bus_speed
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c20632)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff8192be45)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff81940b1e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81954758)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81956eed)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff819712fb)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff8197c701)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81984014)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8198827d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff819978e8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff819a132a)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff819b9a40)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness_nosleep
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c15ce)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819c3a28)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2e4a7)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f8833)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a00c9d)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81a35dae)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81a3854e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/skmsg.c (ffffffff81a3ec45)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffff81a4f178)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff81a821b0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81b01e88)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81b0ff2a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21a2c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b29dfd)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/espintcp.c (ffffffff81b31f4d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff81b5108e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81b8414a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b90e1e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/strparser/strparser.c (ffffffff81b9c0d5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81b9e0a0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff81ba769a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81bad8ed)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81bb24f9)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81bb84f3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81bb9c6a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81bbe73f)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bc21c9)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81bc5330)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052bc4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810584cf)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81bc8d0e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
```
```
In kernel/fork.c (ffffffff810a1745)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810c22ad)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c5eab)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In kernel/reboot.c (ffffffff810d50b5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810e727c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff8110a959)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sched_cpufreq_governor_change
```
```
In kernel/power/wakelock.c (ffffffff81117805)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff8111fbe3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff831e7c87)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff81133157)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:schedule_page_work_fn
```
```
In kernel/livepatch/core.c (ffffffff811368e1)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/pool.c (ffffffff8113c31b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In kernel/time/timer.c (ffffffff81143055)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff81144680)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/ntp.c (ffffffff8114871a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_timer_callback
```
```
In kernel/time/clocksource.c (ffffffff8114916a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:__clocksource_unstable
```
```
In kernel/module.c (ffffffff81162fa3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff81166b33)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff8116bce6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178596)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b535)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff81182858)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/trace/trace.c (ffffffff831ece61)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/bpf/core.c (ffffffff811f8d10)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff812009da)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
```
```
In kernel/bpf/arraymap.c (ffffffff81220d46)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/trampoline.c (ffffffff81226e24)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu
```
```
In kernel/bpf/cpumap.c (ffffffff8123449a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff8123514d)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812382f6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff81259062)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff812861c5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8128a9e0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff8128d356)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/vmalloc.c (ffffffff812bce36)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff812cd7ae)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff812d4c69)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/memcontrol.c (ffffffff8130bd0a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff813111e9)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff8131844e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
```
```
In fs/super.c (ffffffff8132a464)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff8135c8b6)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff81366734)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff81375bb8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff8137b608)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff8138c65f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff81399b56)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/crypto/crypto.c (ffffffff813a8510)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff813b0950)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff813bd357)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff813c6297)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff813e8cc7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff814321b0)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In fs/ext4/super.c (ffffffff8144ee27)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/pstore/platform.c (ffffffff814a862a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff814aa082)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/namespace.c (ffffffff814b88b0)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In security/keys/gc.c (ffffffff814b9421)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
  - security/keys/gc.c:key_schedule_gc
```
```
In security/keys/key.c (ffffffff814b976d)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8152242b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff81534d3d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In security/landlock/ruleset.c (ffffffff81538205)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
```
```
In crypto/drbg.c (ffffffff81559e35)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff81564b94)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81568135)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff8156d85a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-ioc.c:put_io_context
```
```
In block/blk-cgroup.c (ffffffff8158d90d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff81590631)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff8159a94b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff815a5c2d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In lib/rhashtable.c (ffffffff815b66c0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff815b6f37)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/crc-t10dif.c (ffffffff815c101c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/dim/net_dim.c (ffffffff815ea3b5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff815ea628)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In lib/vsprintf.c (ffffffff815fbeb0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
```
```
In drivers/pci/pcie/aer.c (ffffffff8164548e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff816465dc)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81654e88)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/rapidio/rio.c (ffffffff8166162c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81670f55)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff81682030)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff816889f7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_sb_notify
```
```
In drivers/acpi/scan.c (ffffffff8168cd91)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff81691028)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff816e670b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f01d2)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81708ca4)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81711872)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8172046a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81721c99)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff81722835)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81725be5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817262e5)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff817344ca)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8173f025)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81743935)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748125)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff8174cde3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753e74)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81766b58)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8176b920)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff8176ed10)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffff817724ae)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8177da63)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/core.c (ffffffff817a9918)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/core.c:devlink_dev_release
```
```
In drivers/base/dd.c (ffffffff817b1447)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817c1aca)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff817c8ddb)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff817ce06a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff817d0fe0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff817e5e85)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817ec71d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff817f7a82)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff817f8c12)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff818232cc)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81824e21)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff818299b1)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff8183c325)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81840650)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff8185411f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffffffff8185aae0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff8188f070)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff8188f516)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff818a4935)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff818ac5b7)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff818b1963)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff818c1504)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff818c41c2)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c113dd)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_change_bus_speed
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c1269a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff8190f355)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff8192425e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819385c8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193ae1d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff819553eb)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff819602d1)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8196840b)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff8196c79d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8197c5a8)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81985e5a)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff8199e231)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness_nosleep
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a59be)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff819a7f68)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c20581)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819df063)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff819e746d)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81a1cf0e)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81a1f382)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/drop_monitor.c (ffffffff81a3419f)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/core/skmsg.c (ffffffff81a4d055)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/netlink/af_netlink.c (ffffffff81a6b295)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81aed798)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81afdb13)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f64c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17a1c)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/espintcp.c (ffffffff81b1fc6d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff81b3ef5d)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6mr.c (ffffffff81b72dc3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80022)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/strparser/strparser.c (ffffffff81b8b195)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81b8d1a0)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff81b9682a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81b9ca33)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ba1519)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81ba76b3)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ba8e0a)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81bae4ef)
Location: include/linux/workqueue.h:504
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81bb2b24)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81bb5b62)
Location: include/linux/workqueue.h:504
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105b0c4)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106139f)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In arch/x86/kernel/smpboot.c (ffffffff81c9d6c8)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:arch_scale_freq_tick
```
```
In kernel/fork.c (ffffffff810b2b73)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810d4ded)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810d9719)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/reboot.c (ffffffff810e82a5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/core.c (ffffffff810f25de)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
```
```
In kernel/sched/clock.c (ffffffff810fe8a9)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/sched/cpufreq_schedutil.c (ffffffff811290e9)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/sched/cpufreq_schedutil.c:sched_cpufreq_governor_change
```
```
In kernel/power/wakelock.c (ffffffff81137b65)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81140083)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff832cbd77)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811553f7)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff81159521)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/pool.c (ffffffff8115f43e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In kernel/time/timer.c (ffffffff811665e5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff81167f15)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_delayed
```
```
In kernel/time/ntp.c (ffffffff8116c2ca)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_timer_callback
```
```
In kernel/time/clocksource.c (ffffffff8116d289)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
  - kernel/time/clocksource.c:__clocksource_unstable
```
```
In kernel/module.c (ffffffff811884b6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff8118c2f3)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff811918c6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119fef6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811a3085)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/user_namespace.c (ffffffff811aa828)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/trace/trace.c (ffffffff832d19fa)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/bpf/core.c (ffffffff8122a3a0)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff8123274a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
```
```
In kernel/bpf/arraymap.c (ffffffff81258706)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/trampoline.c (ffffffff8125ef24)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu
```
```
In kernel/bpf/cpumap.c (ffffffff8126db7a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff8126f290)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812728f6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff81294d1c)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff812c62b3)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff812cadef)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff812cd180)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/vmalloc.c (ffffffff812ff5a6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff81312b4e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff8131afd7)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff8131d975)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In mm/memcontrol.c (ffffffff81356fea)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/vmpressure.c (ffffffff8135c4de)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81364956)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:zs_free
```
```
In fs/super.c (ffffffff81377a94)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/sync.c (ffffffff813b5284)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff813c1fe8)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff813c8372)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/timerfd.c (ffffffff813d3135)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_resume
```
```
In fs/aio.c (ffffffff813d9c4b)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/io_uring.c (ffffffff813e8c10)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In fs/io-wq.c (ffffffff813f179f)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/io-wq.c:create_io_worker
  - fs/io-wq.c:create_worker_cont
```
```
In fs/crypto/crypto.c (ffffffff813f7c50)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff81400530)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff8140d11e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff81416105)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8143a9f7)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/mballoc.c (ffffffff81477ab1)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/page-io.c (ffffffff81485a20)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In fs/ext4/super.c (ffffffff814a2964)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/pstore/platform.c (ffffffff8150095a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff81502541)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - ipc/util.c:__rhashtable_remove_fast_one
```
```
In ipc/namespace.c (ffffffff815110e0)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In security/keys/gc.c (ffffffff81511c51)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
  - security/keys/gc.c:key_schedule_gc
```
```
In security/keys/key.c (ffffffff81511f9d)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8158067b)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff815932dd)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In security/landlock/ruleset.c (ffffffff815968c5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
```
```
In crypto/drbg.c (ffffffff815bb0b5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff815c8f14)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff815cc725)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff815d1e4a)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815f337d)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff815f75d3)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff81602b2b)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff8160e73d)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In lib/rhashtable.c (ffffffff8161cc0e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff8161d4e7)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/crc-t10dif.c (ffffffff81628e8c)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/dim/net_dim.c (ffffffff81656815)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff81656ac8)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In lib/vsprintf.c (ffffffff816699e0)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
```
```
In drivers/pci/pcie/aer.c (ffffffff816b644e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff816b7e4c)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff816c6da8)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/rapidio/rio.c (ffffffff816d43bc)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816e50a5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff816f7160)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff816fde37)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/acpi/bus.c:acpi_sb_notify
```
```
In drivers/acpi/scan.c (ffffffff817025c0)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_notify
  - drivers/acpi/scan.c:acpi_scan_clear_dep
```
```
In drivers/acpi/ec.c (ffffffff81706abe)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff8175faba)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
```
```
In drivers/acpi/apei/ghes.c (ffffffff8176a2c2)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81784bf1)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178e2d2)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f28a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817a0ab9)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff817a1685)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff817a4bc5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff817a52b5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff817b4e2a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff817bf7b5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff817c45db)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c9337)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff817cec93)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d73b4)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff817eb528)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff817f1020)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff832fb6b0)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
```
In drivers/char/virtio_console.c (ffffffff817f857e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81803c7a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/iommu/io-pgfault.c (ffffffff81830326)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81832a78)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/base/core.c:devlink_dev_release
```
```
In drivers/base/dd.c (ffffffff8183a687)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8184b64a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff818532f8)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff818588c4)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff8185b990)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/loop.c (ffffffff8186fd0e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81872225)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81879305)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81880dc2)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81882082)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff818adbec)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818b06a1)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b53f1)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff818c8c45)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff818cd1a0)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff818e2479)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffffffff818e95d0)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff81922640)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff81922e16)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff819395e5)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81941607)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81946bb3)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff81957d14)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff8195bb54)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d1a6fb)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_change_bus_speed
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d1f1b0)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff819b0195)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff819c728b)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dca35)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff819df607)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff819faa1b)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff81a08591)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_io_dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81a1081b)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81a14cad)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81a25848)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81a2fc4e)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81a4aeb1)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness_nosleep
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a52fe1)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81a57508)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5c501)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81a8f443)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81a97e5d)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81ad078e)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81ad3621)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/xdp.c:__rhashtable_remove_fast_one
```
```
In net/core/drop_monitor.c (ffffffff81ae9ca4)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/core/skmsg.c (ffffffff81b05b15)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/netlink/af_netlink.c (ffffffff81b223d2)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/inet_fragment.c (ffffffff81badb58)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
  - net/ipv4/inet_fragment.c:__rhashtable_remove_fast_one
```
```
In net/ipv4/ipmr.c (ffffffff81bbfc26)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:__rhashtable_remove_fast_one
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2a93)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdbdcf)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/espintcp.c (ffffffff81be490d)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff81c06a34)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ioam6.c (ffffffff81c3a362)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
  - net/ipv6/ioam6.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/ip6mr.c (ffffffff81c3d316)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:__rhashtable_remove_fast_one
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4b8d1)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:__rhashtable_remove_fast_one
```
```
In net/strparser/strparser.c (ffffffff81c57435)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81c59562)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff81c6315a)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81c69c28)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff81c6ef81)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81c75333)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81c76bca)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81c7b7ef)
Location: include/linux/workqueue.h:498
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81c810b6)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81c849be)
Location: include/linux/workqueue.h:498
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81e4a232)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8345e6d9)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8106dcab)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff810c8d75)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810edda9)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810f2b79)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/reboot.c (ffffffff81102705)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/core.c (ffffffff8110e44a)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
```
```
In kernel/sched/build_utility.c (ffffffff81145f45)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_cpufreq_governor_change
  - kernel/sched/build_utility.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff8115a1b8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81163987)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff8347f6fa)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff8117ee9c)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff81182ab1)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/pool.c (ffffffff81189691)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In kernel/module/main.c (ffffffff8118e57d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/time/timer.c (ffffffff81199d65)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff8119b905)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_delayed
```
```
In kernel/time/ntp.c (ffffffff811a02c6)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_timer_callback
```
```
In kernel/time/clocksource.c (ffffffff811a0e49)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff811bb733)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff811c1236)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d05ce)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811d3db5)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/user_namespace.c (ffffffff811dbe75)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/trace/ftrace.c (ffffffff83484864)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
```
```
In kernel/trace/trace.c (ffffffff83485d86)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/bpf/core.c (ffffffff8126be60)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff81275b04)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
```
```
In kernel/bpf/arraymap.c (ffffffff812a1506)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/trampoline.c (ffffffff812a94f4)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu
```
```
In kernel/bpf/cpumap.c (ffffffff812bd445)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff812bdbc0)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812c1d46)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff812e9779)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff813240fa)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8132873b)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff8132baa3)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/vmalloc.c (ffffffff813666e2)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/swapfile.c (ffffffff8137dcce)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff81386362)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff81388f3d)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d00c8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/vmpressure.c (ffffffff813d611c)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In mm/zsmalloc.c (ffffffff813e098a)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In fs/super.c (ffffffff813f6d54)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/sync.c (ffffffff8143a484)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff81448f13)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff8144f4a3)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/timerfd.c (ffffffff8145c665)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_resume
```
```
In fs/aio.c (ffffffff8146416d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/crypto/crypto.c (ffffffff8146a900)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff814743d0)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff814822fb)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff8148d970)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff814b61e4)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/mballoc.c (ffffffff814f9ef7)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/page-io.c (ffffffff81508f57)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In fs/ext4/super.c (ffffffff81529d7e)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/pstore/platform.c (ffffffff81591b34)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8159382b)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In ipc/namespace.c (ffffffff815a3304)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In security/keys/gc.c (ffffffff815a3fbd)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
```
```
In security/keys/key.c (ffffffff815a444b)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8161f85b)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff816353b2)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In security/landlock/ruleset.c (ffffffff81638dbd)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
```
```
In block/bio.c (ffffffff81673fdf)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81678475)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff8167dcee)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In block/blk-cgroup.c (ffffffff816a491d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff816aa374)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff816b569b)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff816c2e78)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In io_uring/io_uring.c (ffffffff81e92497)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In io_uring/io-wq.c (ffffffff816da877)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In lib/rhashtable.c (ffffffff816ea409)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff816eafc0)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/crc-t10dif.c (ffffffff816f9cc3)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/crc64-rocksoft.c (ffffffff816fa293)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_notify
```
```
In lib/dim/net_dim.c (ffffffff8176dfc8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff8176e2a5)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In lib/vsprintf.c (ffffffff81783b35)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - lib/vsprintf.c:__ptr_to_hashval
```
```
In drivers/pci/pcie/aer.c (ffffffff817d9f9e)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff817dc43d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff817ecd34)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/rapidio/rio.c (ffffffff817fe4ac)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81eb3b50)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff81824050)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff8182b7c3)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff8183034c)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_notify
  - drivers/acpi/scan.c:acpi_scan_clear_dep
```
```
In drivers/acpi/ec.c (ffffffff81834c62)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81893414)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189ef8f)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818bbaa8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c6532)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8ea4)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff818da623)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff818db655)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff818de965)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff818df015)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff818f0d0a)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff818fbd75)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff819013f4)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81906897)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff8190c9b3)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81915544)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8192ba51)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81931570)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/virtio_console.c (ffffffff819366ee)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81943540)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/iommu/io-pgfault.c (ffffffff819715ba)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81974258)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/base/core.c:devlink_dev_release
```
```
In drivers/base/dd.c (ffffffff8197ced7)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff819910bc)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff819994d6)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff8199f232)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff819a29aa)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/loop.c (ffffffff819b66bf)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff819ba3e5)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff819c18c4)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff819c9542)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff819ca922)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff819f8a9c)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff819fb756)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a004f1)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81a161a5)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81a1b870)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff81a3363f)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffffffff81a3ae30)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/virqfd.c (ffffffff81a78906)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff81a91375)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81a99823)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81a9f021)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff81ab1b14)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81ab590e)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ee5820)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_change_bus_speed
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81eeacdb)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81b0eecf)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff81b28353)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b40b05)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b43e35)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff81b61f04)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff81b71a5c)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:dm_io_complete
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81b78c2b)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81b7d75d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81b8ead7)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81b9ba2f)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81bb9359)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness_nosleep
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc196d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81bc6fb8)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81bcc511)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In drivers/hte/hte.c (ffffffff81be4a38)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_push_ts_ns
```
```
In net/core/net_namespace.c (ffffffff81c052ad)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81c0f83b)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81c4e06d)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81c50e6e)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81c6c504)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/core/skmsg.c (ffffffff81c8adb4)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
```
```
In net/netlink/af_netlink.c (ffffffff81caaf82)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
```
```
In net/ipv4/inet_fragment.c (ffffffff81d40bc8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff81d52d0b)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6973a)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81d72b38)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/espintcp.c (ffffffff81d7be0a)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff81da1249)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ioam6.c (ffffffff81dd80fb)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81dda24b)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81deaa1b)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In net/strparser/strparser.c (ffffffff81df8a05)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81dfacf8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff81e05afa)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81e0cd5c)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff81e12b37)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81e194c3)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81e1b575)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81e20b9b)
Location: include/linux/workqueue.h:499
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81e26ac8)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff81e2aae9)
Location: include/linux/workqueue.h:499
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106fa31)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff83e7f63f)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8107df6b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff810e6215)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff8110f23b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff81114e49)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/reboot.c (ffffffff81127af5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/core.c (ffffffff8113517a)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
```
```
In kernel/sched/build_utility.c (ffffffff81173115)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_cpufreq_governor_change
  - kernel/sched/build_utility.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff8118c498)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81197657)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff83eaba93)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811b048e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff811bd931)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/pool.c (ffffffff811c5ab1)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/dma/pool.c:dma_alloc_from_pool
```
```
In kernel/module/main.c (ffffffff811caf25)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/time/timer.c (ffffffff811d8425)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff811da1d5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_delayed
```
```
In kernel/time/ntp.c (ffffffff811df0e6)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_timer_callback
```
```
In kernel/time/clocksource.c (ffffffff811e0793)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff811fd563)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff81203816)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8121407e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81217b65)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/user_namespace.c (ffffffff812216c5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/trace/ftrace.c (ffffffff83eb2dbf)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
```
```
In kernel/trace/trace.c (ffffffff83eb4bc8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/bpf/core.c (ffffffff812c1030)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff812c7454)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_release
  - kernel/bpf/syscall.c:__bpf_prog_put
```
```
In kernel/bpf/arraymap.c (ffffffff812fe746)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/trampoline.c (ffffffff81308544)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu
```
```
In kernel/bpf/memalloc.c (ffffffff8131bac7)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff813208c5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff813210f0)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81326436)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8134ce20)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In kernel/padata.c (ffffffff81353549)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff813989da)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff8139da96)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff813a0e08)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/vmalloc.c (ffffffff813e2312)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/swapfile.c (ffffffff813fb88e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff81404192)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff8140774d)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In mm/memcontrol.c (ffffffff81455118)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/vmpressure.c (ffffffff8145bb4c)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In mm/zsmalloc.c (ffffffff81467ef4)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In fs/super.c (ffffffff8147ff94)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/sync.c (ffffffff814c88c4)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff814d779a)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff814ddd13)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/timerfd.c (ffffffff814ebdb5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_resume
```
```
In fs/aio.c (ffffffff814f447d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/crypto/crypto.c (ffffffff814fb880)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff81506680)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff81514e80)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff81521130)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8154cfa1)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/mballoc.c (ffffffff8159470b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/page-io.c (ffffffff815a3ad7)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In fs/ext4/super.c (ffffffff815c8688)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/pstore/platform.c (ffffffff81639274)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8163c28b)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In ipc/namespace.c (ffffffff8164ced4)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In security/keys/gc.c (ffffffff8164dc7d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
  - security/keys/gc.c:key_schedule_gc
```
```
In security/keys/key.c (ffffffff8164e1bb)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff816d2c5b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff816ec022)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In security/landlock/ruleset.c (ffffffff816f02cd)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
```
```
In block/bio.c (ffffffff8172fc4f)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81734955)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff8173a92e)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8176369d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81768302)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff8177528b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff817842a8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In io_uring/io_uring.c (ffffffff8178a6ed)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In io_uring/io-wq.c (ffffffff817a6967)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In lib/rhashtable.c (ffffffff817da633)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff817db56e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - lib/once.c:once_disable_jump
```
```
In lib/crc-t10dif.c (ffffffff817ec623)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/crc64-rocksoft.c (ffffffff817eccd3)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_notify
```
```
In lib/dim/net_dim.c (ffffffff8189d868)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff8189db75)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff818fb97a)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff818fe35d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81913d81)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/pci/doe.c (ffffffff8191fa97)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_submit_task
```
```
In drivers/rapidio/rio.c (ffffffff8192b70c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8193f38b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
```
```
In drivers/acpi/osl.c (ffffffff819553f0)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff8195e0eb)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff819636fc)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_notify
  - drivers/acpi/scan.c:acpi_scan_clear_dep
```
```
In drivers/acpi/ec.c (ffffffff81968822)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff819daeb4)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7bf4)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0a2d3)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a16e72)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b924)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2d143)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff81a2e745)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81a32065)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a327c5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff81a48e2a)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81a551c5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81a5b2f4)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a618b7)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81a67633)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a70814)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81a8a5ee)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81a8fdb0)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/virtio_console.c (ffffffff81a9653e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81aa5f90)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/iommu/io-pgfault.c (ffffffff81adc6fa)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81adf978)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/base/core.c:devlink_dev_release
```
```
In drivers/base/dd.c (ffffffff81aea2c7)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81b01405)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff81b0a7d6)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b10c5e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/block/loop.c (ffffffff81b2b8cf)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/xen-blkfront.c (ffffffff81b2f8f5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b40932)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81b41e62)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff81b76588)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81b79886)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7eb21)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/scsi/sd_zbc.c (ffffffff81b96f0b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81b9c9f0)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff81bb7e01)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffffffff81bc0090)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/usb/core/hub.c (ffffffff81c131e5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81c1ddfd)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81c24481)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff81c3a094)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81c3e1e8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81c426cc)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c6ba36)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81c9f1cb)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff81cbbdd3)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd7145)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cda9f5)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff81cfc0f8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_kick_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff81d0ec8c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm.c:dm_handle_requeue
  - drivers/md/dm.c:dm_handle_requeue
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81d162bb)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d1b69d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d2ee47)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81d3d3cf)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81d587c9)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81d5c61b)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/leds/led-core.c (ffffffff81d5e629)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness_nosleep
  - drivers/leds/led-core.c:led_set_brightness
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d662b7)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81d6f7e8)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76793)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In drivers/hte/hte.c (ffffffff81d90ae8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_push_ts_ns
```
```
In net/core/net_namespace.c (ffffffff81db4b3d)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81dbf445)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81e030dd)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81e06554)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e23f04)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/core/skmsg.c (ffffffff81e46544)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_skb_redirect
  - net/core/skmsg.c:sk_msg_recvmsg
```
```
In net/netlink/af_netlink.c (ffffffff81e680f2)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
```
```
In net/ipv4/inet_fragment.c (ffffffff81f09908)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff81f1d68b)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34a3a)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3e928)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81f417d8)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff81f48efa)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff81f70559)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ioam6.c (ffffffff81fa9aea)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff81fabf0b)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe28b)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/strparser/strparser.c (ffffffff81fccf75)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81fcf52e)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff83f12b38)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81fe2f4c)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff81fe9657)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81ff07a3)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff81ff2b35)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff81ff7fdb)
Location: include/linux/workqueue.h:500
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81ffe237)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
```
```
In net/mptcp/options.c (ffffffff82002c79)
Location: include/linux/workqueue.h:500
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81071631)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff836a238f)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8108034b)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff810f1a8c)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff8111b6db)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff81121d02)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:idle_worker_timeout
  - kernel/workqueue.c:pwq_dec_nr_in_flight
```
```
In kernel/reboot.c (ffffffff81134f95)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/core.c (ffffffff8114438a)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
```
```
In kernel/sched/build_utility.c (ffffffff81184005)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_cpufreq_governor_change
  - kernel/sched/build_utility.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff8119dbb8)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff811a920e)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff836d0a53)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811c24b0)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff811d0311)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/pool.c (ffffffff811d84ff)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In kernel/module/main.c (ffffffff811de289)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/time/timer.c (ffffffff811ec855)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff811ee705)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_delayed
```
```
In kernel/time/ntp.c (ffffffff811f35c6)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_timer_callback
```
```
In kernel/time/clocksource.c (ffffffff811f4c95)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff812126f3)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff81218d26)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812299ae)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8122d385)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/user_namespace.c (ffffffff81237b75)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/watchdog.c (ffffffff836d777b)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_retry_init
```
```
In kernel/trace/ftrace.c (ffffffff836d7f1f)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
```
```
In kernel/trace/trace.c (ffffffff836d9ee8)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/trace/trace_events_user.c (ffffffff812c58bd)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/bpf/core.c (ffffffff812e7da0)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff812edb10)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put
```
```
In kernel/bpf/arraymap.c (ffffffff8132d336)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/trampoline.c (ffffffff81337324)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu
```
```
In kernel/bpf/memalloc.c (ffffffff8134b507)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81350775)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
```
In kernel/bpf/offload.c (ffffffff81350da0)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81356786)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff8137dc70)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In kernel/padata.c (ffffffff81384749)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff813cb93a)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff813d0bfe)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff813d4088)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/vmalloc.c (ffffffff81416efd)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/swapfile.c (ffffffff8142e80e)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff81436f50)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff8143a87d)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In mm/memcontrol.c (ffffffff8148b018)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/vmpressure.c (ffffffff814917eb)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In mm/zsmalloc.c (ffffffff8149cef5)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In fs/super.c (ffffffff814b4c84)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/sync.c (ffffffff814feb04)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff8151075a)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff81514535)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/timerfd.c (ffffffff81522b55)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_resume
```
```
In fs/aio.c (ffffffff8152b24f)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/crypto/crypto.c (ffffffff81532ba0)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff8153dae0)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff8154c880)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff81559163)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff81584c71)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/mballoc.c (ffffffff815cb6df)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/page-io.c (ffffffff815da567)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In fs/ext4/super.c (ffffffff81600495)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
```
```
In fs/pstore/platform.c (ffffffff816716b4)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8167459b)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In ipc/namespace.c (ffffffff81685414)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In security/keys/gc.c (ffffffff81686432)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
  - security/keys/gc.c:key_schedule_gc
```
```
In security/keys/key.c (ffffffff81686a1b)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8170bc5b)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff81726452)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In security/landlock/ruleset.c (ffffffff8172a66d)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
```
```
In crypto/algapi.c (ffffffff81740598)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_destroy_instance
```
```
In block/bio.c (ffffffff8176be7d)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81770f25)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff8177702e)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817a1168)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkcg_punt_bio_submit
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff817a748e)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff817b4f98)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff817c4598)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In io_uring/io_uring.c (ffffffff817cb18c)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In io_uring/io-wq.c (ffffffff817e78e5)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In lib/rhashtable.c (ffffffff81819886)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff8181a7de)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - lib/once.c:once_disable_jump
```
```
In lib/crc-t10dif.c (ffffffff8182c773)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/crc64-rocksoft.c (ffffffff8182ce83)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_notify
```
```
In lib/dim/net_dim.c (ffffffff818dfdb4)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff818e00eb)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff8193ee6a)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff8194180d)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819573f1)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/pci/doe.c (ffffffff81963322)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe
```
```
In drivers/rapidio/rio.c (ffffffff8196f97c)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8198389b)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
```
```
In drivers/acpi/osl.c (ffffffff8199b7f0)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff819a431b)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff819a9bac)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_notify
  - drivers/acpi/scan.c:acpi_scan_clear_dep
```
```
In drivers/acpi/ec.c (ffffffff819aee02)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81a22b43)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
  - drivers/acpi/thermal.c:acpi_thermal_notify
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a30304)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a53153)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ff02)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a750c4)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a768f3)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff81a77ef5)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81a7b945)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81a7c125)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff81a9306a)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81a9f7a5)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81aa5936)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aabfe7)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81ab1d13)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abafc4)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad5dbe)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81adb560)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/virtio_console.c (ffffffff81ae1d4e)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81af1790)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afb17b)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
```
```
In drivers/iommu/io-pgfault.c (ffffffff81b2a966)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81b2dba8)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/base/core.c:devlink_dev_release
```
```
In drivers/base/dd.c (ffffffff81b38657)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81b4f558)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff81b587f6)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5eeee)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/firmware_loader/sysfs_upload.c (ffffffff81b62421)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
```
```
In drivers/block/loop.c (ffffffff81b7bbdf)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/virtio_blk.c (ffffffff81b7e3f5)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed
```
```
In drivers/block/xen-blkfront.c (ffffffff81b82d45)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81b93ca2)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81b951d2)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff81bca208)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81bcd516)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd28a1)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be37d2)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_event_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81bed474)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81bf2fd0)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-sff.c (ffffffff81c17b80)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/virtio_net.c (ffffffff81c521d0)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed
```
```
In drivers/usb/core/hub.c (ffffffff81c7a1a5)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81c84cfd)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81c8b461)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:usb_set_wireless_status
```
```
In drivers/usb/phy/phy.c (ffffffff81ca1444)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81ca561f)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81ca9c9c)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cd2ef6)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81d0650b)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff81d23683)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f315)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d42cb5)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff81d63d18)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81d6c537)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_unplug_async
```
```
In drivers/md/dm.c (ffffffff81d7826c)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81d7ee4a)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81d8480d)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81d97f77)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81da7f9a)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc3159)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81dc707b)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/leds/led-core.c (ffffffff81dc9350)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness
  - drivers/leds/led-core.c:led_blink_set_nosleep
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd13c7)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81dd7331)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_link_release
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81ddd49c)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de46d3)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In drivers/hte/hte.c (ffffffff81dfed78)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_push_ts_ns
```
```
In net/core/net_namespace.c (ffffffff81e251dd)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81e2f0f5)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81e7567d)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81e78dff)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81e99444)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff81ec3f62)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
```
```
In net/ipv4/inet_fragment.c (ffffffff81f69418)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff81f7d18b)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f9465a)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9e25e)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1078)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff81fa8aba)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff81fd07c8)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ioam6.c (ffffffff8200a471)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff8200c6ab)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f0eb)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In net/strparser/strparser.c (ffffffff820488a5)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff8204b1aa)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff837391e1)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff8205f26c)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff820658b6)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff8206c953)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff8206ed55)
Location: include/linux/workqueue.h:503
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff8207450b)
Location: include/linux/workqueue.h:503
Inline: True
```
```
In net/handshake/request.c (ffffffff82092b20)
Location: include/linux/workqueue.h:503
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078df1)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_scale_freq_tick
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff838d248f)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_late_init
  - arch/x86/kernel/cpu/mce/core.c:set_bank
  - arch/x86/kernel/cpu/mce/core.c:mce_irq_work_cb
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81087e5b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In arch/x86/kernel/tsc_sync.c (ffffffff810a66c3)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/tsc_sync.c:check_tsc_sync_source
```
```
In kernel/fork.c (ffffffff810fadec)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff811251cb)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff8112b63a)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/workqueue.c:idle_worker_timeout
```
```
In kernel/reboot.c (ffffffff81140e73)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/core.c (ffffffff8114f8aa)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_put
```
```
In kernel/sched/build_utility.c (ffffffff8118a3d1)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff811acd28)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff811b8d6e)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff83901ef3)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff811d2a20)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff811e4f61)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
```
In kernel/dma/swiotlb.c (ffffffff811ec6bc)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_find_slots
```
```
In kernel/dma/pool.c (ffffffff811ee00f)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/dma/pool.c:__dma_alloc_from_pool
```
```
In kernel/module/main.c (ffffffff811f3fb8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/module/main.c:do_init_module
```
```
In kernel/time/timer.c (ffffffff81202875)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff81204885)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:clock_was_set_delayed
```
```
In kernel/time/ntp.c (ffffffff81209706)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/time/ntp.c:ntp_notify_cmos_timer
  - kernel/time/ntp.c:sync_timer_callback
```
```
In kernel/time/clocksource.c (ffffffff8120adec)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/acct.c (ffffffff81229d73)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff812308e6)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812417fe)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81245655)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/user_namespace.c (ffffffff812513b9)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/watchdog.c (ffffffff83909c3b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/watchdog.c:lockup_detector_retry_init
```
```
In kernel/trace/ftrace.c (ffffffff8390a49f)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_check_for_weak_functions
```
```
In kernel/trace/trace.c (ffffffff8390c448)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_init_tracefs
  - kernel/trace/trace.c:trace_eval_init
  - kernel/trace/trace.c:latency_fsnotify_workfn_irq
```
```
In kernel/trace/trace_events_user.c (ffffffff812e20ff)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_enabler_write
```
```
In kernel/bpf/core.c (ffffffff81306090)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff8130c6c0)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put
```
```
In kernel/bpf/arraymap.c (ffffffff813516a6)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:prog_array_map_clear
```
```
In kernel/bpf/trampoline.c (ffffffff8135d1a4)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_rcu
```
```
In kernel/bpf/memalloc.c (ffffffff81372163)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:destroy_mem_alloc
```
```
In kernel/bpf/offload.c (ffffffff813781d0)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff8137f2b6)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/events/hw_breakpoint.c (ffffffff813a6ed0)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In kernel/padata.c (ffffffff813adb59)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_do_multithreaded
```
```
In mm/backing-dev.c (ffffffff813f627a)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff813fb59f)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
```
In mm/slab_common.c (ffffffff813fedf8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
```
In mm/vmalloc.c (ffffffff81443c5d)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - mm/vmalloc.c:vfree_atomic
  - mm/vmalloc.c:free_vmap_area_noflush
```
```
In mm/swapfile.c (ffffffff814682ce)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - mm/swapfile.c:swap_cluster_schedule_discard
```
```
In mm/zswap.c (ffffffff8147095d)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff81473a3d)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In mm/memcontrol.c (ffffffff814ba918)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:try_charge_memcg
```
```
In mm/vmpressure.c (ffffffff814c11cb)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In mm/zsmalloc.c (ffffffff814cc6ba)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In fs/super.c (ffffffff814e6fb3)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/sync.c (ffffffff81533733)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff81544bfa)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff81548a05)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/timerfd.c (ffffffff81557175)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_resume
```
```
In fs/aio.c (ffffffff8156011f)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
```
```
In fs/crypto/crypto.c (ffffffff81567a90)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff81573080)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/backing-file.c (ffffffff81581567)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/backing-file.c:backing_aio_queue_completion
```
```
In fs/mbcache.c (ffffffff815826b0)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff8158f948)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff815bd6c1)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/mballoc.c (ffffffff8160447c)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
```
In fs/ext4/page-io.c (ffffffff81612d27)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In fs/ext4/super.c (ffffffff816391e5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_handle_error
  - fs/ext4/super.c:ext4_journal_commit_callback
```
```
In fs/pstore/platform.c (ffffffff816ad764)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff816b095b)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In ipc/namespace.c (ffffffff816c1834)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In security/keys/gc.c (ffffffff816c2831)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
  - security/keys/gc.c:key_schedule_gc
```
```
In security/keys/key.c (ffffffff816c2f2b)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8174990b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff81767672)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_del
```
```
In security/landlock/ruleset.c (ffffffff8176bd1d)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - security/landlock/ruleset.c:landlock_put_ruleset_deferred
```
```
In crypto/algapi.c (ffffffff81781438)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_destroy_instance
```
```
In block/bio.c (ffffffff817aae60)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff817b32e5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-ioc.c (ffffffff817b925e)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In block/blk-cgroup.c (ffffffff817e4cb5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkcg_punt_bio_submit
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff817eb20b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff817f99a8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In block/blk-crypto-fallback.c (ffffffff81809258)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_decrypt_endio
```
```
In io_uring/io_uring.c (ffffffff8180de5b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_ctx_wait_and_kill
```
```
In io_uring/io-wq.c (ffffffff8182d6f3)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - io_uring/io-wq.c:create_io_worker
  - io_uring/io-wq.c:create_worker_cont
```
```
In lib/rhashtable.c (ffffffff8185ebd6)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff8185fb5d)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - lib/once.c:once_disable_jump
```
```
In lib/crc-t10dif.c (ffffffff8187e303)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - lib/crc-t10dif.c:crc_t10dif_notify
```
```
In lib/crc64-rocksoft.c (ffffffff8187ea13)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - lib/crc64-rocksoft.c:crc64_rocksoft_notify
```
```
In lib/closure.c (ffffffff8223bfa2)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - lib/closure.c:__closure_sync
  - lib/closure.c:__closure_wake_up
  - lib/closure.c:closure_put
```
```
In lib/dim/net_dim.c (ffffffff819268f4)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - lib/dim/net_dim.c:net_dim
```
```
In lib/dim/rdma_dim.c (ffffffff81926c2b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff81987f3a)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:aer_recover_queue
```
```
In drivers/pci/pcie/pme.c (ffffffff8198aa6d)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819a096d)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/pci/doe.c (ffffffff819ac9a2)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe
```
```
In drivers/rapidio/rio.c (ffffffff819b986c)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cd91b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_output_notifier
```
```
In drivers/acpi/osl.c (ffffffff819e3d10)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/osl.c:acpi_os_execute
```
```
In drivers/acpi/bus.c (ffffffff819eca4b)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff819f267b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_notify
  - drivers/acpi/scan.c:acpi_scan_clear_dep
```
```
In drivers/acpi/ec.c (ffffffff819f92b1)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81a6d809)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b814)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_defer_non_standard_event
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9ef03)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:dma_interrupt
```
```
In drivers/pmdomain/core.c (ffffffff81aa01b6)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:genpd_complete
  - drivers/pmdomain/core.c:genpd_power_off_unused
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1cd6)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7254)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8ae3)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
```
```
In drivers/xen/pcpu.c (ffffffff81aca105)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81acddf5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81ace5d5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff81ae5aba)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:do_SAK
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81af21e5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_insert_flip_string_and_push_buffer
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81af8386)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afeb87)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81b049f3)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:tioclinux
  - drivers/tty/vt/vt.c:set_console
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0dd34)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81b2906e)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff81b2e8c0)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/virtio_console.c (ffffffff81b3513e)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81b44cf0)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4e80b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
```
```
In drivers/iommu/io-pgfault.c (ffffffff81b81bc2)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/base/core.c (ffffffff81b853a8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/base/core.c:devlink_dev_release
```
```
In drivers/base/dd.c (ffffffff81b900f7)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81ba7ad8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb286a)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/firmware_loader/sysfs_upload.c (ffffffff81bb5f31)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs_upload.c:fw_upload_start
```
```
In drivers/block/loop.c (ffffffff81bcfbdf)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/virtio_blk.c (ffffffff81bd2355)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_config_changed
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6c35)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be7c42)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81be91a2)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff81c1ee38)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81c22146)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_report_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27511)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c38262)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_event_done
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c42b73)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
```
In drivers/scsi/sg.c (ffffffff81c488c0)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-sff.c (ffffffff81c6cc30)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c875b8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:__drm_connector_put_safe
```
```
In drivers/gpu/drm/drm_framebuffer.c (ffffffff81c9b0e8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_framebuffer.c:drm_fb_release
  - drivers/gpu/drm/drm_framebuffer.c:drm_mode_rmfb
```
```
In drivers/gpu/drm/drm_writeback.c (ffffffff81cb89d0)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_signal_completion
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc4494)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_commit
```
```
In drivers/gpu/drm/drm_flip_work.c (ffffffff81cc89ee)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_flip_work.c:drm_flip_work_commit
```
```
In drivers/gpu/drm/drm_fb_helper.c (ffffffff81cd41e5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_deferred_io
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_damage_area
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_damage_range
  - drivers/gpu/drm/drm_fb_helper.c:drm_fb_helper_sysrq
```
```
In drivers/net/virtio_net.c (ffffffff81d08646)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_config_changed
```
```
In drivers/usb/core/hub.c (ffffffff81d2eba5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81d396fd)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81d3ff10)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:usb_set_wireless_status
```
```
In drivers/usb/phy/phy.c (ffffffff81d56094)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:usb_phy_set_charger_state
  - drivers/usb/phy/phy.c:usb_phy_set_charger_current
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81d5a26f)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d5e94c)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d87eb8)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81dbc13e)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff81dd93e3)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
  - drivers/rtc/interface.c:rtc_update_irq
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df5cc5)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df9665)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff81e1ac63)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/md-bitmap.c (ffffffff81e23697)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_unplug_async
```
```
In drivers/md/dm.c (ffffffff81e2f49c)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:dm_submit_bio
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm.c:__dm_io_complete
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81e3646a)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3bfcd)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e4fbf7)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e5fcca)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7ba33)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_irq.c (ffffffff81e7f9bb)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_irq.c:sdio_signal_irq
```
```
In drivers/leds/led-core.c (ffffffff81e81e00)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness
  - drivers/leds/led-core.c:led_blink_set_nosleep
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a10b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:__efi_queue_work
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8f5d1)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_destroy_device
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_link_release
```
```
In drivers/platform/x86/intel/turbo_max_3.c (ffffffff81e931ac)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a7c3)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In drivers/hte/hte.c (ffffffff81eb6068)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - drivers/hte/hte.c:hte_push_ts_ns
```
```
In net/core/net_namespace.c (ffffffff81ee313d)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/dev.c (ffffffff81eedd75)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81f34f5c)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81f38ccf)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81f5bb33)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff81f87322)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
```
```
In net/ipv4/inet_fragment.c (ffffffff8202fa98)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff8204388b)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (ffffffff8204d195)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/ipv4/tcp_sigpool.c:tcp_sigpool_release
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061a4a)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
```
```
In net/xfrm/xfrm_state.c (ffffffff8206b5be)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff8206e398)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue_net
```
```
In net/xfrm/espintcp.c (ffffffff82075daa)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_write_space
```
```
In net/ipv6/route.c (ffffffff8209e08b)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ioam6.c (ffffffff820d9412)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_genl_addsc
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/ip6mr.c (ffffffff820db67b)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee21b)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In net/strparser/strparser.c (ffffffff8211ac25)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff8211d62a)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff8396d9b1)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_hw_state_reason
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff821321bc)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (ffffffff82138a56)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff82140773)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82142e35)
Location: include/linux/workqueue.h:545
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_put_pool
```
```
In net/mptcp/protocol.c (ffffffff821488ab)
Location: include/linux/workqueue.h:545
Inline: True
```
```
In net/handshake/request.c (ffffffff821693d0)
Location: include/linux/workqueue.h:545
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
In virt/kvm/eventfd.c (ffff8000100c1534)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - virt/kvm/eventfd.c:kvm_irqfd_assign
  - virt/kvm/eventfd.c:irqfd_wakeup
```
```
In kernel/fork.c (ffff8000100f47f4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffff80001011ad6c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffff80001011f118)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (ffff800010124464)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffff80001012dd50)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/power/wakelock.c (ffff800010171b38)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffff80001017aab8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffff800011446b08)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffff80001018fdd8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/time/timer.c (ffff80001019fde8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffff8000101a1cc8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/module.c (ffff8000101c3744)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffff8000101c7fc4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffff8000101ce364)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dbf9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffff8000101dff30)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/user_namespace.c (ffff8000101e6804)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffff80001025bbfc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffff800010262b9c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (ffff800010287aec)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (ffff80001028a4c4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffff80001028c95c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffff8000102a9e34)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (ffff8000102dd640)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffff8000102e1040)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (ffff8000102e5780)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffff80001030f054)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffff80001032472c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
```
In mm/zswap.c (ffff80001032b474)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
```
```
In mm/hugetlb.c (ffff800010330aa0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (ffff80001034c2c0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffff800010366780)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffff80001036c694)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffff8000103752b8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffff800010388f8c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffff8000103c3294)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffff8000103d0544)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffff8000103e3d00)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffff8000103e9ce0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffff8000103fe9a0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffff800010405184)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffff80001040a9f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffff8000104131a0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffff800010425718)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffff80001042d5a4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffff8000104553c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffff8000104a3650)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (ffff80001051aad4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffff80001051d604)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffff80001052d7a8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffff80001052de00)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffff800010599a18)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffff8000105aa3ec)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (ffff8000105d08d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffff8000105dd7f4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffff8000105e08f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffff8000105e5254)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffff8000105e8918)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060e764)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffff800010611ff8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffff80001061d970)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffff800010636e20)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffff80001063774c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffff80001066614c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (ffff800010666354)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffff800010704884)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffff800010705e08)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070f100)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffff80001073d3cc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffff80001074ca50)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffff800010764090)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffff800010769b34)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/acpi/scan.c (ffff80001076e13c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffff800010772690)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffff8000107a496c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082aaa8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffff8000108359b4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff800010839e38)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffff80001083bb1c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/tty/tty_io.c (ffff80001084ea78)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffff80001085dab8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffff800010864a18)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffff800010869af0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffff800010871768)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffff800010879bec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffff800010898460)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffff8000108a8ef8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffff8000108ae928)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffff8000108b2824)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffff8000108b8e88)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffff8000108ea208)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (ffff8000108fc2cc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffff800010905f14)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffff80001090c774)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffff80001090f6d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/base/arch_topology.c (ffff80001092044c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffff800010926a68)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffff80001092e3bc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffff800010940b94)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffff8000109420cc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffff80001096f21c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffff8000109717a0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffff80001097714c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffff80001098f840)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffff8000109a9580)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (ffff8000109af7c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109ec224)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_timeout
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb0a0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
```
```
In drivers/usb/core/hub.c (ffff800010a12800)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffff800010a1fe0c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffff800010a22b84)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffff800010a37b0c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffff800010a3d7c0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffff800010a3ffbc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a662c4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffff800010a926fc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffff800010aa8b5c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc74c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffff800010acfaa4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffff800010aef5ec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffff800010afcc80)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffff800010b06718)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0b3d4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffff800010b1eb84)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/mmc/core/block.c (ffff800010b4256c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
```
```
In drivers/mmc/core/queue.c (ffff800010b43e94)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
  - drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier
```
```
In drivers/leds/led-core.c (ffff800010b48a6c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffff800010b5c3a8)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b5f76c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/imx/imx-scu-irq.c (ffff800010b62850)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_callback
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b817b4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_report_crash
```
```
In net/core/net_namespace.c (ffff800010bc0484)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/dev.c (ffff800010bcb3f0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (ffff800010c03db0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffff800010c069c0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffff800010c0878c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffff800010c0e254)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffff800010c1b9bc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffff800010c4efa4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffff800010cbf674)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffff800010ccc2cc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde054)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:__xfrm_policy_inexact_prune_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffff800010ce3068)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (ffff800010d13014)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (ffff800010d44efc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffff800010d5202c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffff800010d5ec40)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffff800010d60f14)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffff8000114b5958)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffff800010d73d94)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffff800010d79ea8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffff800010d8124c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffff800010d93c10)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In kernel/fork.c (c0350430)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:mmdrop_async
```
```
In kernel/umh.c (c036f298)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c037244c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (c0377630)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (c037dba4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/power/wakelock.c (c03c44d0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (c03cbd4c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (c15211ac)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (c03dbd40)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/time/timer.c (c03e9a2c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (c03ebacc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/module.c (c040a950)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (c040ecf4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (c0411968)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (c041e2c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (c042537c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (c0426848)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (c048f188)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (c0495620)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (c04b7c44)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_replace
```
```
In kernel/bpf/offload.c (c04b9b9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (c04bc060)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/events/ring_buffer.c (c04d2b58)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free
```
```
In kernel/padata.c (c04d7b88)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (c0502ae0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (c0505bac)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (c050988c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (c052a89c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (c053c3d4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
```
In mm/zswap.c (c05419a4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
```
```
In mm/slub.c (c054feb4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (c05578b8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (c055d75c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (c0561414)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (c0571580)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (c05a10d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (c05ab7e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (c05bbad4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (c05c0dd0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (c05d02f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (c05d4ad8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (c05d7d14)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (c05df47c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (c05ee25c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (c05f606c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (c0616d7c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (c0665880)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (c06d4f14)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (c06d9a1c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (c06e5f14)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (c06e65dc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (c074ab90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (c075a288)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (c077eabc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (c078ac08)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c078eb94)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (c0792274)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (c0795224)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (c07b8f98)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (c07bc800)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (c07c550c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (c07dcc10)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (c07dd344)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (c080eda4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (c080efd0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/pme.c (c089cd78)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/rapidio/rio.c (c08c1b7c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (c08cf704)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/virtio/virtio_balloon.c (c0947450)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/tty/tty_io.c (c095aa80)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (c0965760)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (c096a46c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (c096ed70)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (c09746d4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (c097c328)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (c09931bc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/omap-serial.c (c099eaac)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_runtime_resume
  - drivers/tty/serial/omap-serial.c:serial_omap_runtime_suspend
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
```
```
In drivers/tty/serial/kgdboc.c (c09a54b0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (c09aac48)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (c09ad3b4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (c09b2490)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (c09d81e4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (c09e6dc4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (c09efc80)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (c09f5d44)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/arch_topology.c (c0a053a0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/mfd/htc-i2cpld.c (c0a0f620)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (c0a2a73c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (c0a2b0d4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (c0a4456c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (c0a4657c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (c0a4aa88)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (c0a61400)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (c0a7b920)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (c0a7f1dc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0ace3ac)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_timeout
```
```
In drivers/usb/core/hub.c (c0aeb2d0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (c0af6c94)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (c0af95e4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (c0b0ac78)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (c0b10568)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (c0b12ba0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (c0b371dc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/usb/gadget/udc/core.c (c0b734e4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/gadget/udc/core.c:usb_gadget_unregister_driver
  - drivers/usb/gadget/udc/core.c:usb_add_gadget_udc_release
  - drivers/usb/gadget/udc/core.c:usb_gadget_udc_reset
```
```
In drivers/input/serio/serio.c (c0b75b78)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (c0b876d4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (c0babb90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (c0bb038c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/thermal/samsung/exynos_tmu.c (c0bbdf9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/thermal/samsung/exynos_tmu.c:exynos_tmu_irq
```
```
In drivers/md/md.c (c0bd0b38)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (c0bdc9dc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (c0be49b4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (c0be8ed0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (c0bf911c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/mmc/core/block.c (c0c1aa70)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
```
```
In drivers/mmc/core/queue.c (c0c1db28)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
  - drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier
```
```
In drivers/mmc/host/sdhci.c (c0c28248)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_timeout_data_timer
  - drivers/mmc/host/sdhci.c:sdhci_finish_mrq
```
```
In drivers/leds/led-core.c (c0c324d0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/vars.c (c0c3ced8)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (c0c3ee18)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/imx/imx-scu-irq.c (c0c40f9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/imx/imx-scu-irq.c:imx_scu_irq_callback
```
```
In drivers/remoteproc/remoteproc_core.c (c0c64ce0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_report_crash
```
```
In sound/soc/soc-core.c (c0ca00d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - sound/soc/soc-core.c:snd_soc_resume
```
```
In net/core/net_namespace.c (c0cdbef8)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (c0d1d104)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (c0d1fbb4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (c0d2198c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (c0d2659c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (c0d327fc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (c0d5f130)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c0dcafe0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (c0dd80b0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
  - net/ipv4/ipmr.c:ipmr_mfc_delete
```
```
In net/xfrm/xfrm_policy.c (c0de82c0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (c0dec8d8)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (c0e16c28)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (c0e4712c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c0e53120)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (c0e5e820)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (c0e605e0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (c15bac48)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (c0e702ac)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_deferred_enqueue
```
```
In net/ncsi/ncsi-manage.c (c0e757a8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (c0e7b780)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (c0e8fec0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/powerpc/kernel/mce.c (c00000000003919c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/powerpc/kernel/mce.c:machine_check_ue_irq_work
```
```
In arch/powerpc/mm/numa.c (c0000000000a2520)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:topology_update_init
```
```
In arch/powerpc/platforms/powernv/opal-hmi.c (c0000000000cc6f4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In arch/powerpc/platforms/powernv/opal-memory-errors.c (c0000000000df9fc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In arch/powerpc/platforms/pseries/dlpar.c (c0000000000f4048)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/dlpar.c:queue_hotplug_event
```
```
In kernel/fork.c (c000000000139f58)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (c000000000162568)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c000000000165bd4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (c00000000016e0e4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (c000000000176c3c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/power/wakelock.c (c0000000001ca340)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (c0000000001d4fd0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (c00000000136ba54)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (c0000000001e8efc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (c0000000001f115c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
```
```
In kernel/livepatch/transition.c (c0000000001f329c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/timer.c (c000000000200c6c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (c000000000203104)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/module.c (c000000000229e20)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (c000000000230240)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (c00000000023815c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002496f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (c00000000024ea0c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (c0000000002566f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (c0000000002ffa14)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (c00000000030788c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (c000000000332e6c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (c0000000003358f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (c000000000338e20)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (c00000000035c908)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (c00000000039ce3c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (c0000000003a14bc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (c0000000003a6530)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (c0000000003e0070)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (c0000000003fa6ec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
```
In mm/zswap.c (c00000000040233c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
```
```
In mm/hugetlb.c (c0000000004098d0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (c00000000042bc9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (c000000000452b8c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (c00000000045c514)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (c0000000004678b0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (c00000000047ff7c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (c0000000004c47ec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (c0000000004d2cec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (c0000000004e9c54)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (c0000000004f04f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (c0000000005044f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (c00000000050dadc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (c00000000051738c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (c000000000520f0c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (c000000000534c40)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (c00000000053dcfc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (c00000000056db34)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (c0000000005d09e0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (c0000000006646d0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (c000000000666778)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (c0000000006799d0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (c00000000067a528)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (c000000000710cb4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (c000000000727be4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (c00000000075db4c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (c00000000076f0e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c000000000774d8c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (c0000000007791f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (c00000000077d550)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (c0000000007abc9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (c0000000007b024c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (c0000000007bc938)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (c0000000007dcdbc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (c0000000007dd770)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (c00000000081ba94)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (c00000000081bd90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/rapidio/rio.c (c000000000895280)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (c0000000008aedf0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d6320)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/tty/tty_io.c (c0000000008eda3c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_kref_put
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (c0000000008fce7c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (c000000000903cb0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (c000000000909bcc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (c0000000009119bc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvsi.c (c00000000091f82c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvsi.c:hvsi_interrupt
```
```
In drivers/tty/hvc/hvc_console.c (c000000000921118)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/tty/serial/kgdboc.c (c00000000093fbc4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (c000000000946d84)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (c00000000094b828)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (c000000000959bfc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (c0000000009811a4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (c0000000009991bc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (c0000000009a4c00)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (c0000000009acf78)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (c0000000009b0588)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/mfd/htc-i2cpld.c (c0000000009cd354)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (c0000000009ea010)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (c0000000009ead70)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (c000000000a28bdc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (c000000000a2b17c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (c000000000a30734)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (c000000000a5125c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (c000000000a6ff90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
```
In drivers/ata/libata-sff.c (c000000000a77c9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (c000000000ab0a7c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (c000000000ab1a90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (c000000000acad90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (c000000000ad9b18)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (c000000000add4e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (c000000000af61fc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (c000000000afd008)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (c000000000b009d0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b360e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (c000000000b6e0c4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (c000000000b8a3b4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (c000000000bac9f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (c000000000bb35a0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (c000000000bdaf4c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (c000000000bea9e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (c000000000bf6960)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (c000000000bfc8ec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (c000000000c11730)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1bbe8)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/leds/led-core.c (c000000000c3d230)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5e428)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_report_crash
```
```
In net/core/net_namespace.c (c000000000c99cb0)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/dev.c (c000000000ca6cec)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (c000000000ced7f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (c000000000cf0f70)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (c000000000cf2eac)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (c000000000cf9ae0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (c000000000d0ac4c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (c000000000d4d6e0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (c000000000dda318)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (c000000000deb70c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (c000000000dff470)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (c000000000e06668)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (c000000000e3cc64)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (c000000000e7993c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (c000000000e8ac40)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (c000000000e9951c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (c000000000e9c314)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (c0000000013c7c84)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (c000000000eb3424)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (c000000000eb96ec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (c000000000ec110c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (c000000000ed81e4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In kernel/fork.c (ffffffe0000c0bd4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffe0000d5216)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffe0000d8784)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (ffffffe0000dc516)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffe0000e1de8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/irq/manage.c (ffffffe0001148a0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffe00000859a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffe00012240e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/time/timer.c (ffffffe00012db62)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffe00012effe)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/module.c (ffffffe0001445f4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffe000147ce4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffe000148d26)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154066)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a76e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
```
```
In kernel/user_namespace.c (ffffffe00015bafc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffe00019a872)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffe00019f3ec)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffe0001bc5c8)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (ffffffe0001be52c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffffffe0001c035a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffe0001d335e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (ffffffe0001f5ba8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffe0001f8afc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (ffffffe0001fb76c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffe000217822)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffe000224e90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
```
In mm/zswap.c (ffffffe00022a22e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffe00022dcba)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (ffffffe00023d45c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffe000244458)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffe0002496ba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffe00024dfd0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffe00025b484)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffe000283c90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffe00028c6e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffe000299b5a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffe00029e6ba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffe0002aa0ba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffe0002af398)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffffffe0002b487e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffe0002bad4a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffe0002c475a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffe0002c9b6a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffe0002e66ca)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffe000324e02)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (ffffffe000383ab6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffe000384ea8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffe00038f486)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_gc_timer_func
```
```
In security/keys/key.c (ffffffe00038f8fe)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e6108)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffe0003f35ae)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffe000415c0a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffe00042088c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffe000423c2e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffe000426640)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffe0004293fe)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000446c3c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffe00044979c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffe000450706)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffe000464412)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffe000464936)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffffffe000492326)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (ffffffe0004924ba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/pme.c (ffffffe0004d395a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004db444)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffe0004ed272)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fa5e2)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fb82)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/tty/tty_io.c (ffffffe00052cf04)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffe0005367f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffe00053b1a2)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053e908)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffe0005436da)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a24c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffe00055a958)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/char/random.c (ffffffe000562898)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffe000564cb8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffe00056942c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffe00057e024)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffe00058b818)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffe00058d5a4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_dev_pm_sync
  - drivers/base/power/domain.c:genpd_dev_pm_detach
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffe000591912)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/mfd/htc-i2cpld.c (ffffffe0005a4a3c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0005b4816)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffe0005b51dc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffe0005d933c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffe0005daedc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005de818)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffe0005f32e4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffe0006099e0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffe00060cddc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/usb/core/hub.c (ffffffe0006389de)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffe000642e5c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffe000645590)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffe000654834)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffe0006596f6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065bdd6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00068058c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffe0006a49ba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffe0006b4316)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c866e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cc47c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffe0006e3ae4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffe0006ed6aa)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_internal_resume_fast
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffe0006f4e30)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f8a4e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/mmc/core/block.c (ffffffe0007170f6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
  - drivers/mmc/core/block.c:mmc_blk_mq_req_done
```
```
In drivers/mmc/core/queue.c (ffffffe000719876)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_mq_timed_out
  - drivers/mmc/core/queue.c:mmc_cqe_recovery_notifier
```
```
In drivers/leds/led-core.c (ffffffe00071c716)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074dfb2)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (ffffffe000782d0e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffe000784e32)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_allocator_disconnect
```
```
In net/core/flow_offload.c (ffffffe0007865a4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffe00078acc2)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffe000794d32)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffe0007bacb6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffe000815394)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffe000820aec)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082daac)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffe0008319ae)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (ffffffe000857220)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffe00087f774)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffe00088a668)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffe000894422)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffe000895f90)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffe000044764)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffe0008a3fee)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffe0008a8b34)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad71c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffe0008bdc32)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d3c5)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810538df)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff81099867)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810b85ed)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810bb549)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (ffffffff810c01c7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810c86b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810d958c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff81109c85)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81110861)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff828b80e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff8111fe82)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff81124f84)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
```
```
In kernel/livepatch/transition.c (ffffffff81126700)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/timer.c (ffffffff8112f415)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff811309d0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff811358f1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/module.c (ffffffff8114cbb3)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff81151074)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff811562d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811614a6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81164165)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8116a75e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811d3808)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811d8a9d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f87aa)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811fa6c4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffffffff811fc7a6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff8121684b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (ffffffff81240c15)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff81244185)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (ffffffff81246ee5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff81270d43)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff81280cfc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff81287002)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff8128b4f5)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (ffffffff812a2a8b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff812bb92a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff812c17c9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff812c8a10)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff812da124)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff81307b76)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff81311b54)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff81320e28)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff81325e16)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff813345c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff8133ba39)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffffffff813429c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff813496f5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff81357eb7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff8135de8e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8137d7a7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813c3f12)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8142d1b7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8142f4c0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff8143d10d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff8143d5ca)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149c27b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff814aaf84)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffff814cc3f5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff814d9287)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814dcaf5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814dfd08)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814e2a2c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150344d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff81506997)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff8150eca9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff81523d67)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff81524319)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffffffff81551f8b)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (ffffffff8155214f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/pme.c (ffffffff8159125c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8159953d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff815a941d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b7945)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff815ca2e5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff815cfdb7)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815d3a71)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815d791c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626686)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8163136f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635115)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff816369b9)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81637af5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff8163a505)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8163ab25)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff816483e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81652c05)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81656f82)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165b095)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff8165fea3)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81667b64)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff8167a2f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8167e947)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff8168392f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff816861ae)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff8169450d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff816c4937)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816d2b4b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff816db16b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff816df64e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff816e1f20)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff816f5d65)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81702f52)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/scsi/hosts.c (ffffffff817215dc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81723185)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff817272e1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff8173c690)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/nvme/host/core.c (ffffffff817418fb)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_delete_ctrl
  - drivers/nvme/host/core.c:nvme_reset_ctrl
  - drivers/nvme/host/core.c:nvme_try_sched_reset
```
```
In drivers/nvme/host/multipath.c (ffffffff8174a308)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_failover_req
```
```
In drivers/nvme/host/pci.c (ffffffff817509e6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/ata/libata-eh.c (ffffffff81765742)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff81769165)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/usb/core/hub.c (ffffffff8179c6f5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff817a7ba5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff817aa973)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff817bb740)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817be5bd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff817c7b8d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817e2ded)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff818072c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff81819d78)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81827dd8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/md/md.c (ffffffff8184107d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff8184cf5e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff81855184)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81859206)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818669a8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81871b2b)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81887cff)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff8188bd8f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8188e1ae)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff81891e2f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff8189684f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_report_crash
```
```
In net/core/net_namespace.c (ffffffff818c49c2)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/dev.c (ffffffff818cd22c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8190046e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81902e5f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff8190402a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff8190831f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffff819147e7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff8193d96a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff819a65a4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff819b241a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c13b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819c52bf)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (ffffffff819ebd49)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a6bf)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a25a68)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff81a30705)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81a3277f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff829094d9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81a4197d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a46181)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81a4bcf8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff81a58390)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c845)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff810439af)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff810882ad)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810a6f2d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810aa019)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (ffffffff810ae9d7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810b6ed5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810c7f71)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff810fab65)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81101591)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff828b0368)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff81111882)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff811179e4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
```
```
In kernel/livepatch/transition.c (ffffffff81119156)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/timer.c (ffffffff81121e95)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff81123440)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff81128300)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/module.c (ffffffff8113fe63)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff81144324)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff811495f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154706)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff811573b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8115d95e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811c65c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811cb85d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811eb4fa)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811ed414)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffffffff811ef4f6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff812095ab)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (ffffffff81233c15)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff81237155)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (ffffffff81239e95)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff81262cb3)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff81272b6c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff81278e62)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff8127d325)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (ffffffff8129455b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff812aca9a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff812b2819)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff812b9a50)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff812cada4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff812f8796)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff81302764)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff813119c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff813169b6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff81327eb6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff8132c719)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffffffff813336a5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff8133a3d5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff81348b67)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff8134eb2e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8136e257)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813b4992)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8141dc37)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8141ff40)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff8142db7d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff8142e03a)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8148cc9b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff8149b9a4)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffff814bce15)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff814c9c37)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814cd4a5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814d06a8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814d33bc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f390d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff814f6e57)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff814ff0d9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff81514047)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff815145f9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffffffff8154226b)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (ffffffff8154242f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff8157ee0e)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff8158042c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815886cd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff815985bd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a6725)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff815b3365)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff815b9977)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815bd631)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815c14dc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161ad06)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/tty/tty_io.c (ffffffff81628848)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81633045)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81637312)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163b415)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff81640223)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81647ee4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff816593e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff8165da37)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff816615af)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff81663e4e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff81671efd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff8169fbb7)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff816ade3f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff816b57eb)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff816b9c8e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff816bc560)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/mfd/ezx-pcap.c (ffffffff816d6d62)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/scsi/hosts.c (ffffffff816faa0c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816fc5b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81700711)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/scsi_transport_fc.c (ffffffff8170ec89)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81713704)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
```
```
In drivers/scsi/sg.c (ffffffff8171e330)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/nvme/host/core.c (ffffffff8172358b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_delete_ctrl
  - drivers/nvme/host/core.c:nvme_reset_ctrl
  - drivers/nvme/host/core.c:nvme_try_sched_reset
```
```
In drivers/nvme/host/multipath.c (ffffffff8172bee8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/nvme/host/multipath.c:nvme_failover_req
```
```
In drivers/nvme/host/pci.c (ffffffff81730886)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/ata/libata-eh.c (ffffffff817455a2)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff81748fc5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff8177bf5d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff8177c816)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff8178e385)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff817995cf)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff8179c373)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/input/serio/serio.c (ffffffff817ce9d5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff817e1468)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817ef468)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/md/md.c (ffffffff818086dd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff8181457e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff8181c794)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff81820816)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff8182f658)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff8183b321)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff8183f67f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff8184370f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81846cce)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8184b1a7)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184f1c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_on_msg_dpc
```
```
In drivers/hv/channel_mgmt.c (ffffffff81852825)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/hv/channel_mgmt.c:vmbus_onoffer
```
```
In net/core/net_namespace.c (ffffffff8187e902)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/dev.c (ffffffff818872bc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (ffffffff818ba29e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff818bcc8f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff818bde5a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff818c212f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffff818ce5a7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff818f746a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81960064)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff8196ea4a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e1a5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff819820af)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (ffffffff819a8b09)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff819d747f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff819e2828)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff819ed8f5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff819ef96f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff82901827)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff819fe56d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81a02d71)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81a088e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff81a15470)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d205)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff81053d0f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff81099817)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810b7b4d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810baaa9)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (ffffffff810bf717)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810c7be5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810d58cc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff81107b75)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff8110e751)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff828cb024)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff8111dd72)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff81122e74)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
```
```
In kernel/livepatch/transition.c (ffffffff811245f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/timer.c (ffffffff8112d135)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff8112e6f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff81133611)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/module.c (ffffffff8114aa63)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff8114ef24)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff811540a8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f276)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff81161f35)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff8116852e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811d15d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811d686d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff811f657a)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff811f8494)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffffffff811fa576)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff812145eb)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (ffffffff8123e9b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff81241f25)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (ffffffff81244c85)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff8126eae3)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff8127eb0c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff81284e12)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff81289305)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (ffffffff812a089b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff812b973a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff812bf5d9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff812c6820)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff812d7f34)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff81305966)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff8130f944)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff8131e8f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff813238e6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff81332095)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff81339509)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffffffff81340495)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff813471c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff81355987)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff8135b95e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8137b277)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813c13a2)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81429357)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8142b660)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff814392ad)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff8143976a)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff8149831b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff814a7024)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffff814c8485)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff814d5317)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814d8b85)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814dbd98)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814deabc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814ff4dd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff81502a27)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff8150ad39)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff8151fdf7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff815203a9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffffffff8154dccb)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (ffffffff8154de8f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff8159018e)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff815917ac)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81599a7d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff815a99ad)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b7ed5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff815cae35)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff815d1bb7)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815d5a81)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815d9d0c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff8162d664)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654656)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8165f33f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81662e95)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81664739)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff81665875)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81668655)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81668c75)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff816767a8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff81680fc5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff81685342)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff81689475)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff8168e283)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81695f44)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff816a86d8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816acd27)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff816b1cff)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff816b459e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816c277d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff816f2e07)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff817010bb)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff81708afb)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff8170cd6e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff8170f450)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff817232b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff817296fd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81738372)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81738d52)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff817603ac)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81761f55)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff817660b1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81771f0f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/sg.c (ffffffff8177ce20)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff817954db)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff81798f25)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff817c6d2d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff817c75e6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff817d9195)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff817e4645)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff817e7413)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff817f81e0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff817fb05d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8180462d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181f88d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81846375)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff8185b258)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81874d18)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff8187840a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff818906ad)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff8189c58e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff818a47b4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818a8836)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818b7738)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818c33db)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff818d919f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818dde6f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818e142e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff818e592f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819159c2)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/dev.c (ffffffff8191e22c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (ffffffff8195149e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff81953e8f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_id_disconnect
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff8195505a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff8195934f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffff81965817)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff8198eafa)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a10e44)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff81a1ccba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2be35)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2fd3f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a567c9)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a8513f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a904e8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff81a9c2b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81a9e32f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff8291ee23)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81aad82d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81ab2031)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81ab7ba8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff81ac4780)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e615)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (ffffffff8105518f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/dev-mcelog.c:mce_work_trigger
```
```
In kernel/fork.c (ffffffff810a1480)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:__put_task_struct
```
```
In kernel/umh.c (ffffffff810bfebd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffff810c3559)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/pid.c (ffffffff810c7b27)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/pid.c:free_pid
```
```
In kernel/reboot.c (ffffffff810d00d5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/reboot.c:orderly_reboot
  - kernel/reboot.c:orderly_poweroff
  - kernel/reboot.c:ctrl_alt_del
```
```
In kernel/sched/clock.c (ffffffff810e11bc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/sched/clock.c:clear_sched_clock_stable
```
```
In kernel/power/wakelock.c (ffffffff81112f25)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/power/wakelock.c:pm_wake_unlock
```
```
In kernel/irq/manage.c (ffffffff81119c81)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/srcutree.c (ffffffff828d041d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_init
```
```
In kernel/rcu/tree.c (ffffffff81128cd6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
```
In kernel/livepatch/core.c (ffffffff8112f484)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
```
```
In kernel/livepatch/transition.c (ffffffff81130c42)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
```
In kernel/time/timer.c (ffffffff81139a45)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/timer.c:timers_update_nohz
```
```
In kernel/time/hrtimer.c (ffffffff8113b0f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_resume
```
```
In kernel/time/clocksource.c (ffffffff81140031)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
```
In kernel/module.c (ffffffff81157753)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/module.c:do_init_module
```
```
In kernel/acct.c (ffffffff8115bd24)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/acct.c:acct_pin_kill
```
```
In kernel/cgroup/cgroup.c (ffffffff81160fa8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_release
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116c516)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f3c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_track_online_nodes
  - kernel/cgroup/cpuset.c:cpuset_update_active_cpus
  - kernel/cgroup/cpuset.c:cpuset_migrate_mm
```
```
In kernel/user_namespace.c (ffffffff81175c1e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
```
```
In kernel/bpf/core.c (ffffffff811df8c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free
```
```
In kernel/bpf/syscall.c (ffffffff811e4bdd)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81204afa)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff812068d5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_unregister
  - kernel/bpf/offload.c:bpf_offload_dev_netdev_register
```
```
In kernel/bpf/cgroup.c (ffffffff81209036)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release_fn
```
```
In kernel/padata.c (ffffffff81222627)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
```
In mm/backing-dev.c (ffffffff8124e0e5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release
```
```
In mm/percpu.c (ffffffff812516c5)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slab_common.c (ffffffff81254445)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slab_common.c:kmemcg_cache_shutdown
  - mm/slab_common.c:kmemcg_rcufn
  - mm/slab_common.c:shutdown_cache
```
```
In mm/vmalloc.c (ffffffff8127e4e3)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:vfree_atomic
```
```
In mm/swapfile.c (ffffffff8128e6cc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/swapfile.c:free_cluster
```
```
In mm/zswap.c (ffffffff81294a02)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zswap.c:__zswap_pool_empty
```
```
In mm/hugetlb.c (ffffffff812990e5)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In mm/slub.c (ffffffff812b09db)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/slub.c:__kmemcg_cache_deactivate_after_rcu
  - mm/slub.c:__kmem_cache_shutdown
```
```
In mm/memcontrol.c (ffffffff812c9dba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:memcg_event_wake
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:try_charge
```
```
In mm/vmpressure.c (ffffffff812d003b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure
```
```
In mm/zsmalloc.c (ffffffff812d752e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
```
In fs/super.c (ffffffff812e8d74)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:destroy_super_rcu
```
```
In fs/fs-writeback.c (ffffffff81316cd6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/fs-writeback.c:inode_switch_wbs_rcu_fn
```
```
In fs/sync.c (ffffffff81321144)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/direct-io.c (ffffffff813305f8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/direct-io.c:dio_bio_end_aio
```
```
In fs/notify/mark.c (ffffffff813354f3)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/aio.c (ffffffff81347eda)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_cancel
```
```
In fs/io_uring.c (ffffffff8134bd39)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/crypto/crypto.c (ffffffff81353795)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/crypto/crypto.c:fscrypt_enqueue_decrypt_work
```
```
In fs/verity/verify.c (ffffffff8135a4c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_enqueue_verify_work
```
```
In fs/mbcache.c (ffffffff81368fc6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/iomap/direct-io.c (ffffffff8136f0ae)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
```
```
In fs/kernfs/file.c (ffffffff8138ed67)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_notify
```
```
In fs/ext4/page-io.c (ffffffff813d6502)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81440217)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
```
```
In ipc/util.c (ffffffff8144261d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - ipc/util.c:ipc_addid
```
```
In security/keys/gc.c (ffffffff814503f0)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/keys/gc.c:key_garbage_collector
  - security/keys/gc.c:key_gc_keytype
  - security/keys/gc.c:key_schedule_gc_links
```
```
In security/keys/key.c (ffffffff814509da)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffff814b046b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_loaddata_kref
```
```
In security/yama/yama_lsm.c (ffffffff814bfb0f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In crypto/drbg.c (ffffffff814e0f55)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_schedule_async_seed
```
```
In block/bio.c (ffffffff814edec7)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio.c:bio_check_pages_dirty
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814f1795)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_timed_out_timer
```
```
In block/blk-sysfs.c (ffffffff814f4c08)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
```
In block/blk-ioc.c (ffffffff814f792c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8151865d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkcg_punt_bio_submit
```
```
In block/blk-throttle.c (ffffffff8151be4d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_pending_timer_fn
```
```
In block/bio-integrity.c (ffffffff815243d9)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - block/bio-integrity.c:__bio_integrity_endio
```
```
In lib/rhashtable.c (ffffffff81539710)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (ffffffff81539d29)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/once.c:__do_once_done
```
```
In lib/dim/net_dim.c (ffffffff81567b1b)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In lib/dim/rdma_dim.c (ffffffff81567cdf)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/dim/rdma_dim.c:rdma_dim
```
```
In drivers/pci/pcie/aer.c (ffffffff815aa63e)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/pci/pcie/pme.c (ffffffff815abd9c)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_irq
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b3ebd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
  - drivers/pci/hotplug/shpchp_ctrl.c:queue_interrupt_event
```
```
In drivers/rapidio/rio.c (ffffffff815c29ed)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_init_mports
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d1935)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:cursor_timer_handler
```
```
In drivers/acpi/osl.c (ffffffff815e4cd5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_queue_hotplug_work
  - drivers/acpi/osl.c:acpi_hotplug_schedule
```
```
In drivers/acpi/bus.c (ffffffff815eba77)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/acpi/scan.c (ffffffff815ef941)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_handler
```
```
In drivers/acpi/ec.c (ffffffff815f3bcc)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:advance_transaction
```
```
In drivers/acpi/thermal.c (ffffffff81647504)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_resume
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166edb6)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:stats_request
```
```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8167993f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:wake_waiting
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167d465)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8167ecf9)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/xen/pcpu.c (ffffffff8167fe25)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_hotplug_sync
  - drivers/xen/pcpu.c:xen_pcpu_interrupt
```
```
In drivers/xen/mcelog.c (ffffffff81682ce5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/mcelog.c:xen_mce_interrupt
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81683235)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_resume
```
```
In drivers/tty/tty_io.c (ffffffff81690ec8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:queue_release_one_tty
  - drivers/tty/tty_io.c:tty_hangup
```
```
In drivers/tty/tty_buffer.c (ffffffff8169b615)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:tty_buffer_restart_work
  - drivers/tty/tty_buffer.c:tty_flip_buffer_push
```
```
In drivers/tty/sysrq.c (ffffffff8169f942)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/sysrq.c:sysrq_handle_moom
  - drivers/tty/sysrq.c:sysrq_handle_SAK
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a3ad5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:fn_SAK
```
```
In drivers/tty/vt/vt.c (ffffffff816a8883)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:blank_screen_t
  - drivers/tty/vt/vt.c:scrollfront
  - drivers/tty/vt/vt.c:scrollback
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0504)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:__hvc_resize
```
```
In drivers/tty/serial/max310x.c (ffffffff816c2b38)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_rs485_config
  - drivers/tty/serial/max310x.c:max310x_set_mctrl
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/kgdboc.c (ffffffff816c7187)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/tty/serial/kgdboc.c:kgdboc_post_exp_handler
```
```
In drivers/char/random.c (ffffffff816cc19f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
  - drivers/char/random.c:credit_entropy_bits
```
```
In drivers/char/virtio_console.c (ffffffff816ceafe)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:control_intr
```
```
In drivers/char/tpm/tpm-dev-common.c (ffffffff816dcd4d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev-common.c:tpm_common_write
  - drivers/char/tpm/tpm-dev-common.c:user_reader_timeout
```
```
In drivers/base/dd.c (ffffffff8170d637)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8171af80)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/base/power/domain.c (ffffffff8172366b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_complete
  - drivers/base/power/domain.c:genpd_power_off_unused
```
```
In drivers/base/firmware_loader/main.c (ffffffff81727b9e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
```
```
In drivers/base/node.c (ffffffff8172a210)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/base/node.c:node_memory_callback
```
```
In drivers/block/xen-blkfront.c (ffffffff8173e725)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_restart_queue_callback
```
```
In drivers/mfd/htc-i2cpld.c (ffffffff81744b3d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/htc-i2cpld.c:htcpld_chip_set
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81753902)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_irq_handler
  - drivers/mfd/ezx-pcap.c:pcap_unmask_irq
  - drivers/mfd/ezx-pcap.c:pcap_mask_irq
```
```
In drivers/mfd/da903x.c (ffffffff81754192)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/mfd/da903x.c:da903x_irq_handler
```
```
In drivers/scsi/hosts.c (ffffffff8177ba0c)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8177d5b5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
```
```
In drivers/scsi/scsi_lib.c (ffffffff81781761)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:sdev_evt_send
```
```
In drivers/scsi/sg.c (ffffffff81796c50)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp
  - drivers/scsi/sg.c:sg_rq_end_io
```
```
In drivers/ata/libata-eh.c (ffffffff817af34b)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
```
```
In drivers/ata/libata-sff.c (ffffffff817b2da5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_work
```
```
In drivers/vfio/vfio.c (ffffffff817e0fcd)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_iommu_group_notifier
```
```
In drivers/vfio/virqfd.c (ffffffff817e1a96)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/vfio/virqfd.c:vfio_virqfd_disable
  - drivers/vfio/virqfd.c:vfio_virqfd_enable
  - drivers/vfio/virqfd.c:virqfd_wakeup
  - drivers/vfio/virqfd.c:virqfd_wakeup
```
```
In drivers/usb/core/hub.c (ffffffff817f3505)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_queue_reset_device
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff817fe8b1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hc_died
  - drivers/usb/core/hcd.c:usb_hcd_resume_root_hub
```
```
In drivers/usb/core/message.c (ffffffff81801611)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
```
```
In drivers/usb/phy/phy.c (ffffffff81812420)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/phy/phy.c:__usb_phy_get_charger_type
```
```
In drivers/usb/dwc2/core_intr.c (ffffffff81815258)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_wakeup_detected_intr
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8181e73d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81839822)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_irq
```
```
In drivers/input/serio/serio.c (ffffffff81861985)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/rtc/interface.c (ffffffff818763c5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818906c8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_changed
```
```
In drivers/power/supply/charger-manager.c (ffffffff81893daa)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:charger_extcon_notifier
  - drivers/power/supply/charger-manager.c:cm_monitor_poller
```
```
In drivers/md/md.c (ffffffff818ac29d)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:unbind_rdev_from_array
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
```
```
In drivers/md/dm.c (ffffffff818b87ce)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_queue_flush
  - drivers/md/dm.c:queue_io
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-stripe.c (ffffffff818c09f4)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_end_io
```
```
In drivers/md/dm-kcopyd.c (ffffffff818c4a76)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_do_callback
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:dispatch_job
  - drivers/md/dm-kcopyd.c:process_jobs
  - drivers/md/dm-kcopyd.c:complete_io
```
```
In drivers/cpufreq/cpufreq.c (ffffffff818d2d78)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_verify_current_freq
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_max
  - drivers/cpufreq/cpufreq.c:cpufreq_notifier_min
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff818df73b)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff818f5cbf)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/vars.c (ffffffff818fa97f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818fdece)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/platform/x86/intel_turbo_max_3.c (ffffffff8190258f)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906faf)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_report_crash
```
```
In net/core/net_namespace.c (ffffffff81936bb2)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/dev.c (ffffffff8193f8bc)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/core/sock_diag.c (ffffffff81972e8e)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/xdp.c (ffffffff819755d5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/xdp.c:mem_xa_remove
```
```
In net/core/flow_offload.c (ffffffff81977062)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/flow_offload.c:__flow_indr_block_cb_register
```
```
In net/core/skmsg.c (ffffffff8197b69a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_write_space
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_destroy
```
```
In net/core/drop_monitor.c (ffffffff81987a57)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_probe
  - net/core/drop_monitor.c:net_dm_packet_trace_kfree_skb_hit
  - net/core/drop_monitor.c:sched_send_work
```
```
In net/netlink/af_netlink.c (ffffffff819b13ba)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:deferred_put_nlk_sk
  - net/netlink/af_netlink.c:netlink_remove
  - net/netlink/af_netlink.c:__netlink_insert
```
```
In net/ipv4/inet_fragment.c (ffffffff81a1b722)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_create
  - net/ipv4/inet_fragment.c:inet_frag_kill
  - net/ipv4/inet_fragment.c:fqdir_exit
```
```
In net/ipv4/ipmr.c (ffffffff81a27c15)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:mroute_clean_tables
  - net/ipv4/ipmr.c:ipmr_mfc_add
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a37505)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
  - net/xfrm/xfrm_policy.c:xfrm_policy_hash_rebuild
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b6df)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/route.c (ffffffff81a62844)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81a91a5a)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_add
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/seg6_hmac.c (ffffffff81a9d0f5)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
```
```
In net/strparser/strparser.c (ffffffff81aa8495)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/strparser/strparser.c:strp_check_rcv
  - net/strparser/strparser.c:strp_unpause
  - net/strparser/strparser.c:strp_work
```
```
In net/wireless/wext-core.c (ffffffff81aaa52f)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/wireless/wext-core.c:wireless_send_event
```
```
In net/rfkill/core.c (ffffffff82925845)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_register
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_states
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_sw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_hw_state
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/switchdev/switchdev.c (ffffffff81ab9b9d)
Location: include/linux/workqueue.h:491
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff81abe3e1)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_free_request
```
```
In net/xdp/xdp_umem.c (ffffffff81ac3fc8)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/vsprintf.c (ffffffff81ad0c50)
Location: include/linux/workqueue.h:491
Inline: True
Inline callers:
  - lib/vsprintf.c:fill_random_ptr_key
```
</details>
</li>
</ul>

## Differences
