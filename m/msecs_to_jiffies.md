# Function: <code>msecs_to_jiffies</code>

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
In arch/x86/events/intel/cqm.c (ffffffff8100e974)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In kernel/sysctl.c (ffffffff81087fbd)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a5ada)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/core.c:sched_rr_handler
```
```
In kernel/sched/fair.c (ffffffff810b2577)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
```
```
In kernel/power/process.c (ffffffff810cd8e4)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810d6aa0)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff810ec69a)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff811aea05)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff811e5bc6)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/migrate.c (ffffffff811f0b53)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
```
```
In mm/huge_memory.c (ffffffff811f471e)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff8123bf97)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_workfn
```
```
In fs/pstore/platform.c (ffffffff81320259)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-core.c (ffffffff813b551b)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
```
```
In block/blk-mq.c (ffffffff813c3878)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
```
```
In block/genhd.c (ffffffff813ca864)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff813cbdb7)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff813d5a59)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In block/deadline-iosched.c (ffffffff813dc74e)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
```
```
In block/cfq-iosched.c (ffffffff813dd0d7)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
```
```
In lib/random32.c (ffffffff813f8a41)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814501ad)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/video/console/fbcon.c (ffffffff8146248a)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff8147a532)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff81483d87)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff814b1e9a)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff814b5cf7)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff814c5e4b)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/regulator/core.c (ffffffff814da1a1)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff814ee364)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff814eedc9)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f3343)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff814fbc63)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fe6b0)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8150304e)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff81555fcd)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/base/power/wakeup.c (ffffffff8155c2d7)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:__pm_wakeup_event
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/misc/bmp085.c (ffffffff815791e8)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/misc/bmp085.c:show_pressure
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b524a)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff815c5bbb)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff815c872c)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff815d1b47)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff815d7c5c)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff815dc913)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff815e23bb)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff815e74a1)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff816078a8)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff81610051)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81610e40)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff81666191)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:__ps2_command
```
```
In drivers/input/input.c (ffffffff8166826f)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff8166c25d)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81670900)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/i2c/i2c-dev.c (ffffffff8167e67b)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/power_supply_core.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/power/charger-manager.c (ffffffff81680c08)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
```
```
In drivers/thermal/thermal_core.c (ffffffff81685085)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff816bb0d1)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
```
```
In drivers/mmc/core/core.c (ffffffff816bde90)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff816c6359)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff816cb850)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff816cdb37)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff816eb500)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/devfreq/devfreq.c (ffffffff816ebf76)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
```
```
In net/core/neighbour.c (ffffffff817281b3)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81735eca)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/ipv4/tcp.c (ffffffff81768675)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8176d07f)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177d35e)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817822a0)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff8179549f)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff817ac715)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff817ecf24)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81805639)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:354
Inline: True
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
In arch/x86/events/intel/cqm.c (ffffffff8100e82b)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In kernel/sysctl.c (ffffffff8108ae4d)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b36cf)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_handler
  - kernel/sched/core.c:__sched_fork
```
```
In kernel/sched/fair.c (ffffffff810c1930)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
```
```
In kernel/power/process.c (ffffffff810d23a6)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810dba70)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff810f3d2a)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff811c7e63)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff812048d8)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/migrate.c (ffffffff8120fd85)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
```
```
In mm/khugepaged.c (ffffffff8121c1e2)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff81264784)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/pstore/platform.c (ffffffff81355943)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-core.c (ffffffff813fa39b)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
```
```
In block/blk-mq.c (ffffffff81407371)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
```
```
In block/genhd.c (ffffffff8140eb1f)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814105ff)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff8141b772)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In block/deadline-iosched.c (ffffffff81422358)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff8143fa34)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149c97d)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/video/console/fbcon.c (ffffffff814b048d)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff814c8af0)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff814d270d)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff815017b4)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff815056a7)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815164e5)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/regulator/core.c (ffffffff8152c911)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8153eed8)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8153fa21)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81543f55)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8154c7f6)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154f1e6)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8155465f)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815a928b)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/base/power/wakeup.c (ffffffff815ae4d7)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:__pm_wakeup_event
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160d7aa)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff8161e3a2)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff816219d2)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8162afe7)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8163186a)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff81636690)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff8163c0a9)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff81645dc0)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff816675bc)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff8166fc65)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81670a50)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff816c67e8)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/input.c (ffffffff816c9c1f)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff816cc2bf)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816d0c43)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/i2c/i2c-dev.c (ffffffff816df48e)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/power_supply_core.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/power/charger-manager.c (ffffffff816e2644)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff816e6485)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec0c5)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81722103)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8172920b)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8172e889)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81730b63)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff8174ffe9)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/devfreq/devfreq.c (ffffffff81750f36)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81791a4d)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff817a207a)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/ipv4/tcp.c (ffffffff817d4fa6)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817dadce)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817ea9fb)
Location: include/linux/jiffies.h:354
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff817ef759)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81802e7f)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff81819c75)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff8185b740)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81876216)
Location: include/linux/jiffies.h:354
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:354
Inline: True
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
In arch/x86/events/intel/cqm.c (ffffffff8100e8eb)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In kernel/sysctl.c (ffffffff8108fd9d)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b9d0f)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_rr_handler
  - kernel/sched/core.c:__sched_fork
```
```
In kernel/sched/fair.c (ffffffff810c7920)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
```
```
In kernel/power/process.c (ffffffff810d9574)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810e2a30)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff810faeda)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff811d7f83)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff812169cc)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/migrate.c (ffffffff81221eb5)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
```
```
In mm/khugepaged.c (ffffffff8122d98a)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff81277bc4)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/pstore/platform.c (ffffffff8136bd73)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-core.c (ffffffff81413d1b)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
```
```
In block/blk-mq.c (ffffffff81421b35)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff81429ebf)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff8142b98f)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81436cb2)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In block/deadline-iosched.c (ffffffff8143d4b8)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff8145cb34)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814be4fd)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/video/console/fbcon.c (ffffffff814d259d)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff814eaa34)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff814f4bdc)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff81524272)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff81529897)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81542955)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81558f81)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8156b528)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8156c061)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81570595)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81579031)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157ba66)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8158122f)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815d7e4b)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/base/power/wakeup.c (ffffffff815dd2d7)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:__pm_wakeup_event
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163d04a)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff8164ef82)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81652552)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8165c277)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff816629ba)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff81667730)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff8166d129)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff81676bc0)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff816952d9)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff8169d935)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff8169e700)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff816f47f0)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/input.c (ffffffff816f7bff)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff816fa26f)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff816feb23)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff8170f86e)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81712ab4)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81715a45)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d0b8)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff817550c3)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8175c2a5)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81761a8d)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81763b54)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff8177bba9)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/devfreq/devfreq.c (ffffffff8177ccb6)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff817bf59d)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff817d099a)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/ipv4/tcp.c (ffffffff81804f66)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8180a90e)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181af9b)
Location: include/linux/jiffies.h:358
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8181ffa9)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81833e1f)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff8184b535)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff8188d640)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff818aa717)
Location: include/linux/jiffies.h:358
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:358
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104474f)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In kernel/sysctl.c (ffffffff8108ce75)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ac6a3)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
```
```
In kernel/sched/fair.c (ffffffff810c15ce)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
```
```
In kernel/sched/rt.c (ffffffff810c518f)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff810d8549)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810e1a90)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff810fdf8a)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff811e0e63)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff81222156)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/migrate.c (ffffffff8122daa6)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
```
```
In mm/khugepaged.c (ffffffff81239990)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff81284ea9)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/pstore/platform.c (ffffffff8138038d)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-core.c (ffffffff81421805)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
```
```
In block/blk-mq.c (ffffffff8142fc5e)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff814381cf)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff81443774)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81444864)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In block/deadline-iosched.c (ffffffff8144c8e4)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff81461d44)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c8cfd)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/video/console/fbcon.c (ffffffff814dfb8d)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff814f68bc)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff81502f44)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff815368f8)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff8153c3a7)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81556817)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8156d8cf)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8157fc58)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815806ef)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff815846d2)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8158cde3)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f9a7)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81595137)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/iommu/amd_iommu.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/iommu/intel-iommu.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff815eccbb)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/base/power/wakeup.c (ffffffff815f1e43)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81651b4a)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81663842)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81666b72)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81671830)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff816771f3)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff8167bea7)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81681776)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff8168b350)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff816aa777)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff816b2cf5)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff816b3900)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff8170a3ab)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/input.c (ffffffff8170d6a4)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff8170fdba)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81714051)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81725aaa)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8172b09d)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8172d589)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735278)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8175befb)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8175e1e2)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff8175fa3d)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81772b9f)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8177ab67)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81780111)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff81782154)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff8179a86a)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/devfreq/devfreq.c (ffffffff8179b886)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff817dde07)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff817efd9a)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/ipv4/tcp.c (ffffffff81825904)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8182a9a3)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183b763)
Location: include/linux/jiffies.h:359
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff8184071d)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff818553cf)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff8186efa8)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff818b3d01)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff818d1254)
Location: include/linux/jiffies.h:359
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:359
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff81047f1f)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In kernel/sysctl.c (ffffffff81093b45)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3493)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
```
```
In kernel/sched/fair.c (ffffffff810c8d6e)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
```
```
In kernel/sched/rt.c (ffffffff810cc8af)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff810e0639)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810e9bf0)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff8110883a)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff811f6e73)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff8123d485)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/migrate.c (ffffffff81249626)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - mm/migrate.c:numamigrate_update_ratelimit
```
```
In mm/khugepaged.c (ffffffff81258163)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff812a7938)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/pstore/platform.c (ffffffff813a539d)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-core.c (ffffffff8144c2f5)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
```
```
In block/blk-mq.c (ffffffff8145b59e)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff81463d0f)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff81470201)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81470fb4)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In block/deadline-iosched.c (ffffffff81478fe4)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff8148dc24)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/access.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815092bd)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81527ecd)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff815377ab)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815453a4)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff81598088)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff8159eef7)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815ba324)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff815d1b47)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff815e47d8)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff815e526f)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff815e91d2)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff815f18b4)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f44a7)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff815f9c87)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8165407b)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/base/power/wakeup.c (ffffffff816593f3)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/base/firmware_class.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816baf5a)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff816cce92)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff816d01d2)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff816dae10)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff816e082a)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff816e5547)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff816eafb6)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff816f4cd5)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff81715bca)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff8171e3b5)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff8171f0b0)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff8177b55b)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
```
```
In drivers/input/input.c (ffffffff8177e8e2)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff81781040)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81785294)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81796f9a)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8179c83d)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8179ebd9)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817a6f68)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff817ce138)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff817d0242)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff817d1ad3)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff817e883f)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff817f1159)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff817f66d1)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (0)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff817f84ef)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81810c2a)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81811cd3)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81812476)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81856bfd)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff8186b3ba)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/sched/act_api.c (ffffffff81882506)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp.c (ffffffff818a281c)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818aa547)
Location: include/linux/jiffies.h:360
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff818bfe91)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff818d526f)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff818ef938)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff81936a71)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81956187)
Location: include/linux/jiffies.h:360
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:360
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt_monitor.c (ffffffff8104a785)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff810975a5)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d0795)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/sched/rt.c (ffffffff810d47fb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff810e8cbe)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810f21a0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff81113b15)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff812180e5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff81260ae5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/migrate.c (ffffffff8126d795)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/khugepaged.c (ffffffff8127d94a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff812ce552)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/pstore/platform.c (ffffffff813d44ad)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-core.c (ffffffff8147f5f5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-core.c:blk_delay_queue
```
```
In block/blk-mq.c (ffffffff8148e574)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff81496e25)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/genhd.c:disk_events_poll_jiffies
```
```
In block/scsi_ioctl.c (ffffffff814a4454)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814a5095)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In block/deadline-iosched.c (ffffffff814ad734)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff814c2991)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153a19b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155e83d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff8156d31a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff8157b9f4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff815cf4a8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff815d6c2b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff815f216a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff81609c13)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8161d873)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8161e5eb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff816225e0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8162b461)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d757)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81633568)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm-interface.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/runtime.c (ffffffff8168fdf6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_schedule_suspend
```
```
In drivers/base/power/wakeup.c (ffffffff816950ab)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f736a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81709824)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8170cc20)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff817172f3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8171d0ce)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff81721de7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81727936)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff81732d23)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff81754a06)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff8175d5f1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff8175de40)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff817bc476)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff817bf902)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff817c23d8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817c6356)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff817d9a86)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/i2c/busses/i2c-designware-baytrail.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff817e3d13)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff817e6189)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81816f2a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81818e55)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff8181a847)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81831b1c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8183a3dd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8183fc76)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81840f9b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff81841abe)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff8185aaca)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185bab5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff8185c375)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff818a1c27)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff818bbb2a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/sched/act_api.c (ffffffff818d615a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp.c (ffffffff818f9124)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818ff947)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffff81915a56)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff8192bbcf)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff8194637b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff8198f82d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff819b15d0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
Inline: True
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105ab05)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff8109f8c5)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d9fd5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/sched/rt.c (ffffffff810de22b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff810f42bd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810fd8f0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff81120375)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff8122aff5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff81275da6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffffffff81291417)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff812e3852)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/pstore/platform.c (ffffffff813eea7d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffff814a00d1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff814a7f04)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff814b0d45)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/genhd.c:disk_events_poll_jiffies
```
```
In block/scsi_ioctl.c (ffffffff814bee9c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814bfb1e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
```
In block/mq-deadline.c (ffffffff814c7b74)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff814d7041)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815514cb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8157533d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff81584eda)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815930b4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff815e8a88)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff815f04bb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8160d0ca)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff81626cfa)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8163aaa3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8163b84b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163f890)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8164945b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164bb5d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81650fcb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/serial_core.c:uart_set_info_user
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b574b)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81719c6a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff8172bd14)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8172f0a0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff817399a3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8173f9ae)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff81744697)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff8174a116)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff817557fe)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff81778e9b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff81781c31)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81782410)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff817e38d6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff817e6db2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff817e9986)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817ed926)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81800d94)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/media/cec/cec-adap.c (ffffffff81804664)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffff818079b1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8180f643)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81812609)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818427e9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818446f5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81846037)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff8185dafc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818663b0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8186bc26)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8186ceeb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff8186d9e1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81879eca)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187b1d5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff8187b905)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff818c4de2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff818e2bfa)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/sched/act_api.c (ffffffff8190294f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff8192d6e4)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8193aa1a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81944206)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff8195b05f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff8197651b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff819c60e1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff819e89b9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
Inline: True
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
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105de05)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffffffff810a3fb5)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e12f8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/sched/rt.c (ffffffff810e5239)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff810fc822)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff81105c32)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff8112ac65)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff8123ac25)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff81292386)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812ac55d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/fs-writeback.c (ffffffff81301fb3)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff81331410)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffffffff8141ad4d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffff814ce651)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff814d5dc2)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff814df69e)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814ed441)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814ee21f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff814f63ee)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff81502ea1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8158145b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a57dc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff815b5afb)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815c402b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff8161a7a8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff8162226b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81640870)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8165a35c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8166ee21)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81670532)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81673eac)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8167da96)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816803b4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81685a85)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816ef2e9)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8174ad3d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8175536a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81767474)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8176a86e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8177599a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8177b7e6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff81780462)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81785f86)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff81791a08)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff817b6d3b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff817c017e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff817c08d4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff8182425d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff818277e1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/mousedev.c (ffffffff8182abf9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8182e3ad)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff8184205f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/media/cec/cec-adap.c (ffffffff81845ca7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffff818492f0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81851cd0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8185459f)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81885638)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818874b5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81888e2b)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818a176c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818aa1b7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818afc66)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818b0d5c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff818b1c75)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff818bf44e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818c0795)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/soundwire/stream.c (ffffffff818c482b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/soundwire/stream.c:sdw_prep_deprep_ports
```
```
In drivers/devfreq/devfreq.c (ffffffff818c5a45)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81910e35)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/xdp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/net-sysfs.c (ffffffff8193220a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/devlink.c (ffffffff819483b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff81963bba)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff819910b6)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8199edc7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819a87c9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff819bfd5f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff819e01b9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff81a34f48)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81a58ced)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e6c5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffffffff810aa595)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ec125)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810f06c9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81108c17)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff81111fb2)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff81136c05)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff81249095)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff812a2106)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812bea9a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812c7a86)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff813150b3)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff813450bb)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffffffff81434b9d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffff814e79c1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff814ef0f2)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff814f8ace)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff81506881)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff8150767f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff8151427e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff81520e41)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a2f5b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c66ac)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff815d6d2b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815e526b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff8163c1d8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff81643d4b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81663230)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8167d09c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff81691431)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81692c17)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff8169660c)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816a0293)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a2a64)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a8145)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81713449)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8176eead)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff817795ea)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff8178b464)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8178e8de)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8179990a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff8179f356)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff817a411d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff817a9bc6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff817b5608)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff817e7456)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff817f0afe)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff817f1254)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff81855733)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff81858d40)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff8185a485)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff8185c589)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8185fcdd)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff818739df)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/media/cec/cec-adap.c (ffffffff818775c7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffff8187aaf0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81882f00)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81885fff)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818b75d8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818b9475)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff818baddb)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818d3a65)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818dc607)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818e2116)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818e31ec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff818e4425)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff818f1f9e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818f3295)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff818f80d5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81943c05)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81964d4a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (ffffffff8197d85b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff8199a736)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff819c7b05)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5867)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819df49d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff819f68ff)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a17049)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff81a6ba98)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81a8ee52)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810641d5)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In kernel/sysctl.c (ffffffff810b21c5)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810f5dca)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810f9bd9)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81113811)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff8111d6a2)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:boot_delay_msec
```
```
In kernel/time/timer.c (ffffffff81144a65)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff81277355)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff812d6824)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/khugepaged.c (ffffffff812efed6)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In mm/memcontrol.c (ffffffff812fd516)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff8134db1e)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_check_old_data_flush
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff8137f000)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_start
```
```
In fs/pstore/platform.c (ffffffff81484e0f)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In block/blk-sysfs.c (ffffffff81546881)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff81550062)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff8155a560)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
```
In block/scsi_ioctl.c (ffffffff815674ae)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_fill_sghdr_rq
```
```
In block/bsg.c (ffffffff8156879d)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff81575ac7)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff81583eb1)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164badd)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166f9ac)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff81680a57)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff81690392)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_poll
```
```
In drivers/acpi/battery.c (ffffffff816e96d8)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff816f103b)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff817126e8)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8172e67f)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff81743d4e)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81745548)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81748aec)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81751a6d)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:setterm_command
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754efd)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175a245)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817cf2a8)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8183178d)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183c35a)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff8184f9b9)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8185275e)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8185e9d5)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81863ddc)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81868371)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff818696dd)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff8186f59d)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff8187c5a8)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff818b4e7d)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff818c000e)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff818c0b94)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff81927c53)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff8192ab64)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff8192d105)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff8192f1af)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81933b98)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81947bbe)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff819518ca)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:fullbatt_handler
  - drivers/power/supply/charger-manager.c:fullbatt_handler
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff819545ff)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198819f)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81989d55)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff8198b64c)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff819ae24c)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b50f6)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b62cc)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff819b77a7)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffffffff819c764e)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c8c85)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff819ce15b)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81a1495d)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81a378fa)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:362
Inline: True
```
```
In net/core/devlink.c (ffffffff81a59519)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff81a73694)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4908)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2a3d)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81acca55)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81ae4c5f)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff81b64a9e)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/mcast.c:mld_process_v2
```
```
In net/packet/af_packet.c (ffffffff81b86019)
Location: include/linux/jiffies.h:362
Inline: True
Inline callers:
  - net/packet/af_packet.c:init_prb_bdqc
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:362
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810625e2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff810ad9f5)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810f3f1a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810f7fb9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81bdeb44)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff81118112)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:boot_delay_msec
```
```
In kernel/time/timer.c (ffffffff81141e25)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff81281c45)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/ksm.c (ffffffff812e2361)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/khugepaged.c (ffffffff812fb696)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In mm/memcontrol.c (ffffffff81309980)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff8135a9be)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_check_old_data_flush
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff81394058)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In fs/pstore/platform.c (ffffffff814a254f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In block/blk-sysfs.c (ffffffff815624e1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff8156c532)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff81576a8d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
```
In block/scsi_ioctl.c (ffffffff8158224e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/scsi_ioctl.c:blk_fill_sghdr_rq
```
```
In block/bsg.c (ffffffff815830db)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff815928c7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8166fe2d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff8168febc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff8169f547)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff816ae092)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_poll
```
```
In drivers/acpi/battery.c (ffffffff81706ebb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff8170e31b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8172f478)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8174b24f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8175fc3d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817604ee)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81764810)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8176d4b3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:setterm_command
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817701fd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81775325)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817e38a8)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8184239d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184cb5a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff818602f9)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81862abe)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8186d9f5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81872bdc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81877181)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff818784dd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff8187e26d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff8188a8c6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff818c37dd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff818cbace)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff818ccc84)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff8192f163)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff819320d4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff819345c5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff81936553)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8193ade8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff8194d9df)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8195739d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8195956f)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8198c0cf)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8198dac5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff8198f23c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff819b08ac)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b76b6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff819b880c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff819b9ca7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffffffff819c759e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819c89d5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff819cdb2a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81a14c6d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81a39d0a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/devlink.c (ffffffff81a61cd1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff81a7c294)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff81abf986)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace46d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ad89c2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81af1b2f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff81b7323e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/mcast.c:mld_process_v2
```
```
In net/packet/af_packet.c (ffffffff81b95929)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:init_prb_bdqc
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff81062d45)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff810aec05)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810f57de)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810fa119)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81bd0cbd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff811187e2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff81142c25)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff81286c05)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/ksm.c (ffffffff812e9af0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/khugepaged.c (ffffffff81306409)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In mm/memcontrol.c (ffffffff8130ffd0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff81361662)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff813942c1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In fs/pstore/platform.c (ffffffff814a85ef)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In block/blk-sysfs.c (ffffffff8156b331)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff81573f3a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff8157ea43)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
```
In block/scsi_ioctl.c (ffffffff81589364)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81589f0b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff81598d5e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8165232d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81672bcc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff816821f7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff81690a9e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
```
In drivers/acpi/battery.c (ffffffff816e84bb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff816efa2b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81712ec8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8172e95f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff81743a9f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff8174410f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff817480e0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8175102d)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753caa)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81758855)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817c7a6c)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818255b3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8182ffaa)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81842405)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff818458b6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8184d3ce)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff818551f9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff818599fc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff8185ab4a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81860986)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff8186d257)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff818a68a8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff818af0ee)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff818b0294)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff819124f4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff819150d4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff81917935)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff819192db)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8191dee6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff8193116f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff8193b2df)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81942145)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81970748)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81972164)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81973848)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8199507c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8199be56)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff8199cf3c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff8199e2b8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffffffff819ac4de)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff819ad925)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff819b2d9a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff819fb76d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81a210ca)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/devlink.c (ffffffff81a444b1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff81a64ec4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff81aa9c96)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab95fc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ac38e1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81add31f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff81b606f0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/mcast.c:mld_process_v2
```
```
In net/packet/af_packet.c (ffffffff81b88d74)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8106cbd5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff810c0764)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/reboot.c (ffffffff81ca5758)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/sched/fair.c (ffffffff8110f59f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff81114f19)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81ca99ef)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff81138ad2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff8115582b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/timer.c (ffffffff81166125)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff812c6195)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/ksm.c (ffffffff81331a20)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/kfence/core.c (ffffffff8133bd39)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/khugepaged.c (ffffffff81350372)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In mm/memcontrol.c (ffffffff8135b300)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff813afcc2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff813e3451)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8150091f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In block/blk-sysfs.c (ffffffff815cf5b1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff815d844a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/disk-events.c (ffffffff815eec1d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
```
```
In block/bsg.c (ffffffff815ef55c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff81600f52)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c407c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff816e7de4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff816f733d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff817064fe)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
```
In drivers/acpi/battery.c (ffffffff81761afb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff81769aab)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff8178f988)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff817ae546)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff817b24c3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/tty/sysrq.c (ffffffff817c471b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff817c4f4e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff817c92d4)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff817d3b2e)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d71e7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dca25)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81851e09)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff818aee11)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_error.c (ffffffff818b0e33)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bbeca)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff818cf075)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff818d2346)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff818da9fe)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff818e3779)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff818e85ac)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff818eac42)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff818ef769)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff818fd1f3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff8193b72d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff8194423e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff819454f4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff8194f107)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff819b44b8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff819b7264)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff819b9ba5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff819bb69b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff819c1488)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff819d443f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff819dfac4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_helpers.c (ffffffff819e6a65)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81a19068)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81a1ae14)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81a1c548)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81a40a4e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81a48887)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81a4993c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff81a4af38)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81a5aa5b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81a5be85)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81a6273c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81aadabf)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81ad554a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/devlink.c (ffffffff81afbb75)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff81b1e194)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b6608d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76a38)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81b81e62)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81b9c78f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff81c27f56)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/packet/af_packet.c (ffffffff81c54e5d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8107a095)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff810d7ca4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
```
```
In kernel/reboot.c (ffffffff81e54ff8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/reboot.c:hw_protection_shutdown
```
```
In kernel/sched/fair.c (ffffffff8112b4eb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_task_scan_period
```
```
In kernel/sched/build_policy.c (ffffffff8112e12b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81e5990d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff8115b500)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff8117893a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/timer.c (ffffffff81199ca5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff81323f35)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/ksm.c (ffffffff813a2c38)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/kfence/core.c (ffffffff813ae6e9)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/khugepaged.c (ffffffff813c846d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In mm/memcontrol.c (ffffffff813d4a02)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff814347d1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In fs/pstore/platform.c (ffffffff81591aed)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In block/blk-sysfs.c (ffffffff8167abd8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff81684b6b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/disk-events.c (ffffffff8169f55a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
```
```
In block/bsg.c (ffffffff816a0528)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff816b3539)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In io_uring/io_uring.c (ffffffff81e905e8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_offload_create
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817e9c7c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81812a34)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff81824258)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff81834678)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
```
In drivers/acpi/battery.c (ffffffff81895829)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff8189e42b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff818c7ef7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff818e9555)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff818ede3b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/tty/sysrq.c (ffffffff819013a9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81901dce)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81906835)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81911bb7)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81915337)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191b826)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81997dfb)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff819f995d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a08111)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81a1cd23)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81a22a5f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2eec2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81a3477b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81a39ed3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff81a3bb53)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81a418fc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff81a4e881)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff81a933bd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff81a9c7d5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81a9dba4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81aa8113)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff81b13357)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff81b170d0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff81b197e5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff81b1b6e4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81b1ffc1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81b370c4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81b442f8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_helpers.c (ffffffff81b4bf75)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81b81e26)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81b83c04)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81b85608)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81bae0b2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81bb6955)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81bb7cab)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff81bb93ed)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81bca227)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81bcb595)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd388e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81c26753)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81c55971)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/devlink.c (ffffffff81c7dbde)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff81ca5b88)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cf431a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06268)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81d122d3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81d2e7b3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff81dc52f5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/packet/af_packet.c (ffffffff81df505d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108b195)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff810f834c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
```
```
In kernel/reboot.c (ffffffff81127a7c)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81154ebb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_task_scan_period
```
```
In kernel/sched/build_policy.c (ffffffff8115802b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81181468)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff8118d7a0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff811b02ea)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/timer.c (ffffffff811d8345)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/vmscan.c (ffffffff81377009)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/vmscan.c:store_min_ttl
```
```
In mm/backing-dev.c (ffffffff813987e5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/ksm.c (ffffffff814228a0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/kfence/core.c (ffffffff8142eb79)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/khugepaged.c (ffffffff8144c70a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In mm/memcontrol.c (ffffffff8145a442)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff814c27b1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8163922d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/apparmor/notify.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In block/blk-sysfs.c (ffffffff817372b8)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff81742608)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/disk-events.c (ffffffff8175deaa)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
```
```
In block/bsg.c (ffffffff8175f028)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff81772ce9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In io_uring/sqpoll.c (ffffffff8179adc1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8190fcac)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff81941ae4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff81955628)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff819682a0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
```
In drivers/acpi/battery.c (ffffffff819dd5c6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff819e7467)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a194b7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff81a3f8b5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a459d5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/tty/sysrq.c (ffffffff81a5b2a9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81a5bd5e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a612d4)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81a6cb17)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a705ce)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a77708)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/hw_random/core.c (ffffffff81a9b6df)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b08efb)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81b77921)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b87331)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81b9dfe3)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81ba423f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb23e2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81bb8fdf)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81bbf1f3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff81bc012d)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81bc7c4c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff81bd0a57)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_wait
```
```
In drivers/usb/core/hub.c (ffffffff81c1554c)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff81c21775)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81c22c64)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81c2f153)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff81ca4287)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff81caa22e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff81cab2b5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff81cad29a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81cb22f6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81ccc4e4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81cdac1d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81ce0a76)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81d2057f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d221bd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81d2466d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81d514e2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81d5b3e5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81d5c92b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff81d5e6cd)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81d73845)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d74e15)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7f7de)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81dd90a9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81e0b3c1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/devlink.c (ffffffff81e364c5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff81e63ad1)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81eb8cda)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb5d6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ed80c3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81ef6783)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff81f95e85)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/packet/af_packet.c (ffffffff81fc79fc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8108e235)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sysctl.c (ffffffff81104740)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
```
```
In kernel/reboot.c (ffffffff81134f1c)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In kernel/sched/fair.c (ffffffff8116506b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_task_scan_period
```
```
In kernel/sched/build_policy.c (ffffffff8116812b)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81192368)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff8119ef40)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/tree.c (ffffffff811c1f1a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/timer.c (ffffffff811ec775)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/vmscan.c (ffffffff813a8d39)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/vmscan.c:min_ttl_ms_store
```
```
In mm/backing-dev.c (ffffffff813cb745)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/ksm.c (ffffffff81457610)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/kfence/core.c (ffffffff81464329)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In mm/khugepaged.c (ffffffff81481fba)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In mm/memcontrol.c (ffffffff814900a2)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff814f7b71)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In fs/pstore/platform.c (ffffffff8167166d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/apparmor/notify.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In block/blk-sysfs.c (ffffffff81773a18)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff8177ddeb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/disk-events.c (ffffffff8179cdba)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
```
```
In block/bsg.c (ffffffff8179df25)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff817b1dd9)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In io_uring/sqpoll.c (ffffffff817dbe70)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819533cc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819860c4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff8199ba28)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff819ae880)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
```
In drivers/acpi/battery.c (ffffffff81a252d6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a2fb77)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81a623d7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff81a89485)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff81a8fb81)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/tty/sysrq.c (ffffffff81aa58ee)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81aa637e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aab994)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81ab71a2)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abad8e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2038)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/hw_random/core.c (ffffffff81ae703f)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/iommu/dma-iommu.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b56f1b)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcb6b6)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bdb161)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81bf4603)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81bfa93f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c09912)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81c10884)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81c16d43)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff81c17c1d)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c1f7dc)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff81c2d0db)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff81c7c365)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff81c886f5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81c89be4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81c963c3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff81d0b998)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff81d117fe)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff81d12895)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff81d1487a)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81d19912)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81d342b4)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81d42edb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81d48c30)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81d8975f)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81d8b3b7)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81d8d87d)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbbf02)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81dc5e63)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81dc73fb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff81dc9433)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81de1615)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de2d55)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81dedb6e)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81e49dcb)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81e7e771)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/sched/act_api.c (ffffffff81ebfb67)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:363
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f171c0)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a121)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81f37185)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81f561f3)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff81ff6854)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/packet/af_packet.c (ffffffff82028996)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/devlink/health.c (ffffffff82047ce5)
Location: include/linux/jiffies.h:363
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:363
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff810955c5)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In kernel/sysctl.c (ffffffff8110e090)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
```
```
In kernel/reboot.c (ffffffff81140410)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81171dbb)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_task_scan_period
```
```
In kernel/sched/build_policy.c (ffffffff81174ed6)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff811a0d58)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff811ae030)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/rcu/update.c (ffffffff83901b70)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
```
In kernel/rcu/tree.c (ffffffff811d25da)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
```
```
In kernel/time/timer.c (ffffffff81202795)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/vmscan.c (ffffffff813d2839)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - mm/vmscan.c:min_ttl_ms_store
```
```
In mm/backing-dev.c (ffffffff813f6095)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/compaction.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In mm/ksm.c (ffffffff814920e1)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
```
```
In mm/kfence/core.c (ffffffff814936a9)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In mm/khugepaged.c (ffffffff814b1371)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In mm/memcontrol.c (ffffffff814bf8b2)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff8152c2c1)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/fuse/dax.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In fs/pstore/platform.c (ffffffff816ad71d)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
```
```
In security/apparmor/notify.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In block/blk-sysfs.c (ffffffff817b5ce8)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff817c045b)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/disk-events.c (ffffffff817e080a)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
```
```
In block/bsg.c (ffffffff817e19a5)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff817f5be9)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In io_uring/sqpoll.c (ffffffff818201f2)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/pci/pcie/dpc.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199c85c)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cffe4)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff819e3f78)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff819f8d00)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
```
In drivers/acpi/battery.c (ffffffff81a70116)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7aef7)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81ab4c03)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff81adbb65)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/regulator/irq_helpers.c (ffffffff81ae23f1)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
```
```
In drivers/tty/sysrq.c (ffffffff81af833e)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_handle_keypress
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81af8e0e)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff81afe534)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81b09ea2)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0dafe)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b157f8)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/hw_random/core.c (ffffffff81b3a40f)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b795f6)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:queue_iova
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81baf50b)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (ffffffff81c202e6)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c2fe81)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff81c49f43)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff81c503df)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5e9cb)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81c65ac2)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sata.c (ffffffff81c6be55)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
```
In drivers/ata/libata-sff.c (ffffffff81c6cccd)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c7493c)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/gpu/drm/drm_vblank.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_helper.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (ffffffff81ccf813)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_alter_state
```
```
In drivers/spi/spi.c (ffffffff81cdafe8)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_wait
```
```
In drivers/usb/core/hub.c (ffffffff81d30fb5)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff81d3d145)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81d3e5d4)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/core/devio.c (ffffffff81d4aea3)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/host/ehci-platform.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da31a0)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff81dc1628)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff81dc73fe)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff81dc8495)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff81dca49a)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dcf632)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81dea364)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81df9887)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81dff12f)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81e40e9f)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff81e42c37)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81e4512d)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_add_device
```
```
In drivers/cpufreq/intel_pstate.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mmc/core/core.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81e744d2)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81e7e7a3)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81e7fd5b)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff81e81ee3)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81e975d5)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e98e45)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea3f0e)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81f08aee)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81f3f681)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In net/core/selftests.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In net/sched/act_api.c (ffffffff81f82d17)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/jiffies.h:515
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fdc671)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
```
```
In net/ipv4/tcp_output.c (ffffffff81fed9bc)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_delack_max
```
```
In net/ipv4/tcp_timer.c (ffffffff81feee78)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffd25d)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff8201c663)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv6/mcast.c (ffffffff820c4494)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/packet/af_packet.c (ffffffff820f83ce)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/devlink/health.c (ffffffff82113d42)
Location: include/linux/jiffies.h:515
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_report
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:515
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
In arch/arm64/kernel/psci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/arm64/kernel/smp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffff800010102804)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffff80001014c5fc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffff800010151e04)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffff8000101700d4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffff8000101722c4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffff80001019f158)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffff8000102de568)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffff80001034191c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffff80001035fd6c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffff80001036a8fc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffff8000103cb2e8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffff8000104033a8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffff80001051aaa0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffff8000105e5500)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffff8000105eed24)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffff8000105f9fac)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In block/scsi_ioctl.c (ffff800010607fa4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffff800010609d98)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffff800010618d2c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffff80001062a37c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/bus/fsl-mc/mc-sys.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070b818)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/controller/pci-aardvark.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffff80001074fda0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffff8000107641e4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffff800010771d70)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffff8000107a6f9c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffff8000107af074)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/amba/bus.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/clk/imx/clk-busy.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/soc/qcom/rpmh.c (ffff80001081cda4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
```
```
In drivers/xen/grant-table.c (ffff80001082c6d8)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/regulator/core.c (ffff800010846c74)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffff8000108649f4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffff80001086687c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffff80001086b688)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffff800010878124)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087b08c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffff800010881168)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_fsl.c (ffff800010890a14)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/tty/serial/amba-pl011.c (ffff800010896e8c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (ffff8000109045d0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffff8000109721a8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097e298)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffff800010991d64)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-core.c (ffff80001099854c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffff8000109a41a4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffff8000109aadbc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffff8000109af864)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffff8000109b687c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/ata/libahci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/spi/spi.c (ffff8000109c8d2c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb3a0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
```
```
In drivers/usb/core/hub.c (ffff800010a16410)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffff800010a206b4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffff800010a216b0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffff800010a94528)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffff800010a98d84)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffff800010a9a4f8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffff800010a9cdf8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffff800010aa20a0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/rtc/rtc-sun6i.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffff800010ab8570)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/i2c/busses/i2c-omap.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/media/cec/cec-adap.c (ffff800010abefa4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffff800010ac242c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffff800010acf9f8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffff800010ad3094)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffff800010b0f6cc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffff800010b11664)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffff800010b133ec)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (ffff800010b2cfc4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffff800010b367d4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffff800010b3c7d4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffff800010b3daa8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/mmc/core/block.c (ffff800010b3ecf4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:card_busy_detect
```
```
In drivers/leds/led-core.c (ffff800010b49200)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/ti_sci.c (ffff800010b51404)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_get_status
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_control
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_handover
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_release
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_request
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_unpair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_pair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config
  - drivers/firmware/ti_sci.c:ti_sci_get_resource_range
  - drivers/firmware/ti_sci.c:ti_sci_cmd_core_reboot
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_match_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_num_parents
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_get_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_set_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_cmd_set_device_resets
  - drivers/firmware/ti_sci.c:ti_sci_get_device_state
  - drivers/firmware/ti_sci.c:ti_sci_set_device_state
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56bcc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
```
```
In drivers/firmware/imx/imx-scu.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffff800010b7a694)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/mailbox/pl320-ipc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7f07c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffff800010b843dc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffff800010be6ac8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffff800010c097e8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (ffff800010c26f7c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffff800010c47948)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffff800010c79174)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffff800010c88a04)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffff800010c92d9c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffff800010cad3b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2ab8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffff800010d333b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffff800010d5c034)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/arm/kernel/smp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/arm/mach-hisi/hotplug.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/arm/mach-imx/src.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/arm/mach-imx/hotplug.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/arm/mach-omap2/omap_phy_internal.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/arm/mach-tegra/platsmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (c035eab8)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (c039a214)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/rt.c (c039f094)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (c03bad88)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (c03c4ea4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (c03e9024)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (c0503770)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (c05478b0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/memcontrol.c (c055be90)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (c05a7644)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (c05d6914)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (c06d4ed0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (c0792534)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (c079a6c4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (c07a4994)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/genhd.c:disk_events_poll_jiffies
```
```
In block/scsi_ioctl.c (c07b3dd4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c07b4e2c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (c07c3940)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (c07d16b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pinctrl/tegra/pinctrl-tegra-xusb.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/controller/pci-tegra.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (c08d23d4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/amba/bus.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/clk/imx/clk-busy.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/clk/samsung/clk-cpu.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/clk/tegra/clk-pll.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/soc/tegra/fuse/fuse-tegra20.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/soc/tegra/pmc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/regulator/core.c (c095041c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (c096a36c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (c096c040)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (c0970128)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (c097aae8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (c097cdcc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (c0981ca4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_fsl.c (c098d014)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/tty/serial/amba-pl011.c (c0991420)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (c09ee46c)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (c0a46a08)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (c0a519e4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (c0a642f4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_new_write
```
```
In drivers/ata/libata-core.c (c0a680b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (c0a74304)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (c0a7a6b4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (c0a7f27c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libahci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mtd/nand/raw/nand_base.c (c0aa057c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_soft_waitrdy
```
```
In drivers/mtd/nand/raw/nand_legacy.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/spi/spi.c (c0aaf6d4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_wait
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/net/ethernet/ti/cpts.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/net/ethernet/ti/cpsw_sl.c (c0ada498)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_wait_for_idle
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_reset
```
```
In drivers/auxdisplay/arm-charlcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/core/hub.c (c0aee73c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (c0af7880)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (c0af8094)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/musb/musb_core.c (c0b64e6c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/musb/musb_core.c:vbus_store
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
```
```
In drivers/usb/musb/musb_virthub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/musb/musb_gadget.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (c0b77018)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (c0b7ab04)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (c0b7c13c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (c0b7e0c8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (c0b81fdc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/i2c/i2c-dev.c (c0b97ea0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/i2c/busses/i2c-imx.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/i2c/busses/i2c-omap.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/media/cec/cec-adap.c (c0ba0c9c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (c0ba4848)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c0bb0304)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (c0bb3790)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (c0bed9b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c0befad0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (c0bf138c)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (c0c08318)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (c0c11264)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (c0c16eec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (c0c1809c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/mmc/core/block.c (c0c1924c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:card_busy_detect
```
```
In drivers/mmc/host/sdhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/host/omap_hsmmc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/host/cqhci.c (c0c2fd04)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_halt
```
```
In drivers/leds/led-core.c (c0c325e4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37ff4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
```
```
In drivers/firmware/imx/imx-scu.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mailbox/mailbox.c (c0c5fab4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/mailbox/pl320-ipc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mailbox/tegra-hsp.c (c0c61204)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_flush
```
```
In drivers/hwspinlock/hwspinlock_core.c (c0c61c68)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (c0c67880)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In sound/core/pcm_native.c (c0c92b00)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - sound/core/pcm_native.c:snd_pcm_drain
```
```
In sound/core/pcm_lib.c (c0c9a67c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
```
```
In sound/soc/soc-dapm.c (c0ca7ea4)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In sound/soc/soc-jack.c (c0cadaec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
  - sound/soc/soc-jack.c:gpio_handler
```
```
In sound/soc/soc-pcm.c (c0cb2588)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - sound/soc/soc-pcm.c:soc_pcm_close
```
```
In sound/soc/soc-compress.c (c0cbccd8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - sound/soc/soc-compress.c:soc_compr_free
```
```
In net/core/neighbour.c (c0d00aec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (c0d22760)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (c0d3c53c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (c0d58734)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (c0d893d8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (c0d977f4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (c0da1778)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (c0db9cc0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (c0ddcdb0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (c0e360d0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (c0e5c09c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/powerpc/platforms/powernv/opal.c (c0000000000c5110)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:kopald
```
```
In arch/powerpc/platforms/powernv/vas-window.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/powerpc/platforms/pseries/vio.c (c0000000000ff44c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/vio.c:vio_h_cop_sync
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (c00000000014a028)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (c00000000019efd0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (c0000000001a5768)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (c0000000001c8284)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (c0000000001cb9d0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
```
```
In kernel/time/timer.c (c0000000001ffeac)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (c00000000039de78)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (c00000000041f0a0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (c00000000044b52c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (c000000000459c0c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (c0000000004cce64)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (c00000000050fe24)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (c000000000664660)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (c000000000779594)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (c000000000784308)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (c00000000079225c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/genhd.c:disk_events_poll_jiffies
```
```
In block/scsi_ioctl.c (c0000000007a4a04)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c0000000007a6168)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (c0000000007b8244)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (c0000000007cc40c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (c0000000008b199c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/regulator/core.c (c0000000008e2d88)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (c000000000903c44)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (c000000000905d34)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (c00000000090b83c)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (c00000000091a60c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (c0000000009220ec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (c0000000009289b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/tty/serial/8250/8250_fsl.c (c00000000093aa10)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_i2c_atmel.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_i2c_infineon.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_i2c_nuvoton.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (c0000000009a2d80)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (c000000000a2b698)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a3a0b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (c000000000a55288)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-core.c (c000000000a5ad14)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (c000000000a68f8c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (c000000000a71be8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (c000000000a77d68)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/spi/spi.c (c000000000a8a7e8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (c000000000acecd4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (c000000000adab64)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (c000000000adb800)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (c000000000b73328)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (c000000000b77df0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (c000000000b7a610)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (c000000000b7cb58)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (c000000000b82d4c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/i2c/i2c-dev.c (c000000000b9b4f0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/media/cec/cec-adap.c (c000000000ba094c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (c000000000ba4cd0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (c000000000bb3498)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (c000000000bb7a10)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (c000000000c02cec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (c000000000c056dc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (c000000000c07e40)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1c678)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
```
```
In drivers/mmc/core/core.c (c000000000c25ee4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (c000000000c31af0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (c000000000c39814)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (c000000000c3b14c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (c000000000c3d368)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (c000000000c5923c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a030)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (c000000000c62064)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (c000000000cc6384)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (c000000000cf48d8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (c000000000d1ac14)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (c000000000d448b0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (c000000000d83fe0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (c000000000d954ec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (c000000000da3030)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (c000000000dc38e4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (c000000000df1498)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (c000000000e65a2c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (c000000000e97a58)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/riscv/kernel/smpboot.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffffffe0000c9608)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffffffe0000f5b44)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
```
```
In kernel/sched/rt.c (ffffffe0000f9f48)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffe00010da80)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffe00010e622)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffe00012db0c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffe0001f665a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffe000235e56)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/memcontrol.c (ffffffe000248118)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffe0002891d0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffe0002b0b60)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffffffe000383a8c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffe0004268c6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffe00042d726)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffe000435fe4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/genhd.c:disk_events_poll_jiffies
```
```
In block/scsi_ioctl.c (ffffffe0004426b6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffe00044333c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffe00044ebe2)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffe00045aec4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8404)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fc26c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/regulator/core.c (ffffffe000527118)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffe00053b0fc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffe00053c1a6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053fc88)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffe000548d5a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054acaa)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054e3b0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/stmpe.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffe0005db2a8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e4e70)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffe0005f5ada)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffe0005f8e5c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffe000602620)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffe00060868c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffe00060ce66)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/spi/spi.c (ffffffe000619032)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffe00063b5b4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffe000643952)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffe000644218)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffe0006a65b8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffe0006a9b0a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffe0006aadfa)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffe0006ac320)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffe0006aff6e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bd840)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/media/cec/cec-adap.c (ffffffe0006c0a12)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffe0006c3538)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffe0006cc3e6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffe0006cf562)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffe0006fc7ea)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffe0006fe4ee)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffe0006ffe50)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffe000706fd0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e8c6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffe000713bda)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffe000714afc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/mmc/core/block.c (ffffffe000715bee)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:card_busy_detect
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe00071a012)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_detect_irq
```
```
In drivers/leds/led-core.c (ffffffe00071c808)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffe00072beaa)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072d3f6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffe00072db46)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffe000769f54)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffe000787b26)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (ffffffe00079d86e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffe0007b562c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffe0007dd6d2)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9740)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f254e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffe000807404)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823ffe)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffe000871756)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffe00089228a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e245)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffffffff810a3eb5)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e6285)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810e9b29)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff81101d57)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff8110a592)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff8112f3b5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff812416e5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff8129a6e6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812b707a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812c0066)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff8130d693)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff8133d69b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffffffff8142d17d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffff814dffa1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff814e76d2)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff814f10ae)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814fee61)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814ffc5f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff8150c85e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff81519421)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8159676b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ba7ac)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff815ca3da)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815d715b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff816290a0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8164297c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff81656eb1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81658697)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165c06c)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81665cf3)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816684c4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166dba5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816d97b9)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff816f4831)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_freeze
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8172359d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172dcda)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff8173fb54)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff817484bb)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_user_cmd64
  - drivers/nvme/host/core.c:nvme_user_cmd
```
```
In drivers/nvme/host/lightnvm.c (ffffffff8174c284)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/nvme/host/lightnvm.c:nvme_nvm_user_vcmd
```
```
In drivers/ata/libata-core.c (ffffffff81753a4e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e9fa)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff81764446)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff817691dd)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/spi/spi.c (ffffffff8177a0e8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff8179f836)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff817a8ede)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff817a9634)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff8180a743)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff8180dd50)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff8180f495)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff81811599)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81814ced)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/media/cec/cec-adap.c (ffffffff8181fb37)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffff81823060)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff8182be7f)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff8185d458)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff8185f2f5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff81860c5b)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff81877425)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff8187ffc7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81885ad6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff81886bac)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff81887de5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff818932ce)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818945c5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81899405)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff818e3bd5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81904d1a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (ffffffff8191d6cb)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff8193a5a6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff81967975)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819756d7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff8197f30d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff8199669f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff819b66d9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff81a0b128)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81a2e4e2)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8104e575)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffffffff81092895)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810d5425)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810d9a89)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff810f2117)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff810fb472)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff81121e35)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff812346d5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff8128c2a6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812a824a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812b1136)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff812fe2a3)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff8132e35b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffffffff8141dbfd)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffff814d0941)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff814d7c42)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff814e15ee)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814ef371)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814f016f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff814fcc8e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff81509711)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815858fb)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a958c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff815b345a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815c0d1b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/regulator/core.c (ffffffff81622f7c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff81637241)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81638a21)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163c3ec)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81646073)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81648844)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164cff5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b3e09)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816fc9cd)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff817070fa)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff817217f4)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff8172a0db)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_user_cmd64
  - drivers/nvme/host/core.c:nvme_user_cmd
```
```
In drivers/ata/libata-core.c (ffffffff817338ee)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e89a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff817442a6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff8174903d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/spi/spi.c (ffffffff81759e98)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff817914b6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff8179a8ee)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff8179b034)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff817d1ec7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff817d54a0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff817d6be5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff817d8cd9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff817dc41d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/media/cec/cec-adap.c (ffffffff817e71d7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffff817ea700)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/thermal/thermal_core.c (ffffffff817f350f)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff81824a28)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818268c5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff8182822b)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/leds/led-core.c (ffffffff8183f765)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff8184b7ce)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8184c3b5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff818568d5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff8189da15)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff818beb4a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (ffffffff818d747b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff818f40a6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff81921465)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f197)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff81938dcd)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff8195015f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff819734c9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff819c7ee8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff819eb6d2)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105e675)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffffffff810a3e65)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810e2655)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810e6bf9)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff810ff0e7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff81108482)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff8112d0d5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff8123f485)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff812984f6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812b4e8a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812bde76)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff8130b483)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff8133b16b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffffffff8142931d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffff814dc031)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff814e3762)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff814ed13e)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff814faef1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814fbcef)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff815088ee)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff815154b1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81596cab)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815bad3c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff815cb00b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815d954b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff81630018)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff81637b8b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81657070)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff81670edc)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff81685271)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff81686a57)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff8168a44c)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816940d3)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816968a4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169bf85)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81707109)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8176236d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176caaa)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff817802e4)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8178375e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e78a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff817941d6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff81798f9d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff8179ea46)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff817aa488)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff817dc2d6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff817e597e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff817e60d4)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff818498c3)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff8184ced0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff8184e615)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff81850719)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81853e6d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81867b6f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/i2c/busses/i2c-amd-mp2-plat.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/media/cec/cec-adap.c (ffffffff8186ca77)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffff8186ffa0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff818783b0)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff8187b4af)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818aca88)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818ae925)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff818b028b)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818c88c5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818d1467)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818d6f76)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818d804c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff818d9285)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff818e6dce)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818e80c5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff818e8af5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81934c05)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81955d4a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (ffffffff8196e85b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff8198b736)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff819d2145)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819dfea7)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819e9add)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81a00f3f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a21159)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff81a75ba8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81a9a092)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
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
In arch/x86/events/amd/core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (ffffffff8105fbb5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
```
```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/softirq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sysctl.c (ffffffff810abf25)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In kernel/sched/fair.c (ffffffff810ee358)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/rt.c (ffffffff810f1b99)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/sched/rt.c:sched_rr_handler
```
```
In kernel/power/process.c (ffffffff8110a3ec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/printk/printk.c (ffffffff81113822)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
```
```
In kernel/time/timer.c (ffffffff81138e65)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
```
```
In mm/backing-dev.c (ffffffff8124ec05)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_wakeup_delayed
```
```
In mm/ksm.c (ffffffff812a827a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
```
```
In mm/khugepaged.c (ffffffff812c4cbb)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In mm/memcontrol.c (ffffffff812ce7f6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
```
```
In fs/fs-writeback.c (ffffffff8131cc43)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
```
```
In fs/io_uring.c (ffffffff8134e31b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
```
```
In fs/pstore/platform.c (ffffffff814401dd)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
```
```
In block/blk-sysfs.c (ffffffff814f4ea1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_io_timeout_store
```
```
In block/blk-mq.c (ffffffff814fc862)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
```
In block/genhd.c (ffffffff815061ae)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In block/scsi_ioctl.c (ffffffff81513fa1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81514d9f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/mq-deadline.c (ffffffff81521fee)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
```
```
In lib/random32.c (ffffffff8152ec42)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - lib/random32.c:__prandom_timer
```
```
In drivers/pci/pci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b112b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
```
```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d47ec)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
```
```
In drivers/acpi/osl.c (ffffffff815e4eab)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
```
```
In drivers/acpi/ec.c (ffffffff815f340b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
```
In drivers/acpi/battery.c (ffffffff8164a358)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_get_state
```
```
In drivers/acpi/apei/ghes.c (ffffffff81651ebb)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_add_timer
```
```
In drivers/dma/dmaengine.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/xen/grant-table.c (ffffffff81671670)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
```
```
In drivers/regulator/core.c (ffffffff8168b53c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_disable_deferred
```
```
In drivers/tty/sysrq.c (ffffffff8169f871)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_filter
```
```
In drivers/tty/vt/vt_ioctl.c (ffffffff816a104e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a4a4c)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816ae6b3)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0e4a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b6ac5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
```
```
In drivers/char/agp/intel-gtt.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/iommu/iova.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81721b59)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/wm8350-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/twl6040.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mfd/da9052-core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8177d9cd)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8178824a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
```
```
In drivers/scsi/sg.c (ffffffff8179a0d4)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffff8179d61e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
```
```
In drivers/ata/libata-scsi.c (ffffffff817a866a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
```
```
In drivers/ata/libata-eh.c (ffffffff817ae046)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_eh_reset
```
```
In drivers/ata/libata-sff.c (ffffffff817b2e1d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/ata/libata-zpodd.c (ffffffff817b88c6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
```
```
In drivers/spi/spi.c (ffffffff817c435a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_transfer_one_message
```
```
In drivers/usb/core/hub.c (ffffffff817f6566)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/urb.c (ffffffff817ffbd6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
```
```
In drivers/usb/core/message.c (ffffffff81800334)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_start_wait_urb
```
```
In drivers/usb/dwc2/core_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-ring.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/i8042.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/input/serio/libps2.c (ffffffff818647e1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
```
```
In drivers/input/input.c (ffffffff81868090)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
```
```
In drivers/input/input-poller.c (ffffffff818697e5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_dev_poller_queue_work
```
```
In drivers/input/mousedev.c (ffffffff8186b899)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_event
```
```
In drivers/input/keyboard/atkbd.c (ffffffff8186f23d)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
```
```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81882e1f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
```
In drivers/media/cec/cec-adap.c (ffffffff81886a07)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
```
```
In drivers/media/cec/cec-api.c (ffffffff81889f10)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/power/supply/charger-manager.c (ffffffff81893d50)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
```
```
In drivers/thermal/thermal_core.c (ffffffff81896eaf)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/edac/edac_mc.c (ffffffff818c8cd8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
```
```
In drivers/edac/edac_device.c (ffffffff818cabb5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
```
```
In drivers/edac/edac_pci.c (ffffffff818cc51b)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/core.c (ffffffff818e53e5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_do_erase
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff818edf87)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818f3a96)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
```
```
In drivers/mmc/core/sdio_irq.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In drivers/mmc/core/slot-gpio.c (ffffffff818f4b6c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
```
```
In drivers/leds/led-core.c (ffffffff818f5da5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_timer_function
```
```
In drivers/mailbox/mailbox.c (ffffffff81903a4e)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/mailbox/mailbox.c:mbox_send_message
```
```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81904dd5)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
```
```
In drivers/devfreq/devfreq.c (ffffffff81909b75)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
```
```
In net/core/neighbour.c (ffffffff81955f75)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
```
```
In net/core/net-sysfs.c (ffffffff81977f3a)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/net-sysfs.c:bql_set_hold_time
```
```
In net/core/page_pool.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/core/devlink.c (ffffffff81990d0b)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_report
```
```
In net/sched/act_api.c (ffffffff819adfa6)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/sched/act_api.c:tc_dump_action
```
```
In net/ipv4/tcp_input.c (ffffffff819dbce5)
Location: include/linux/jiffies.h:364
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819e9b67)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_metrics.c (ffffffff819f388c)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
```
```
In net/ipv4/igmp.c (ffffffff81a0b42f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/igmp.c:unsolicited_report_interval
```
```
In net/ipv4/tcp_cubic.c (ffffffff81a2c48f)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv6/mcast.c (ffffffff81a822d8)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/packet/af_packet.c (ffffffff81aa6dc1)
Location: include/linux/jiffies.h:364
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_set_ring
```
```
In net/rfkill/input.c (0)
Location: include/linux/jiffies.h:364
Inline: True
```
</details>
</li>
</ul>

## Differences
