# Function: <code>__msecs_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eacd0)
Location: kernel/time/time.c:512
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/core.c:sched_rr_handler
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - fs/fs-writeback.c:wb_writeback
  - fs/fs-writeback.c:wb_workfn
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-core.c:blk_delay_queue
  - block/blk-mq.c:blk_mq_delay_queue
  - block/scsi_ioctl.c:sg_io
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - block/cfq-iosched.c:cfq_target_latency_store
  - block/cfq-iosched.c:cfq_group_idle_store
  - block/cfq-iosched.c:cfq_slice_idle_store
  - block/cfq-iosched.c:cfq_slice_async_store
  - block/cfq-iosched.c:cfq_slice_sync_store
  - block/cfq-iosched.c:cfq_fifo_expire_async_store
  - block/cfq-iosched.c:cfq_fifo_expire_sync_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/misc/bmp085.c:show_pressure
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/cpufreq/intel_pstate.c:intel_pstate_timer_func
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff810eacd0-ffffffff810eacf3: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1970)
Location: kernel/time/time.c:519
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - kernel/sched/core.c:sched_rr_handler
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-core.c:blk_delay_queue
  - block/blk-mq.c:blk_mq_delay_queue
  - block/scsi_ioctl.c:sg_io
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_notify_event
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:charger_manager_probe
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/power/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff810f1970-ffffffff810f1995: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8af0)
Location: kernel/time/time.c:519
Inline: False
Direct callers:
  - arch/x86/events/intel/cqm.c:intel_cqm_rmid_rotate
  - kernel/sched/core.c:sched_rr_handler
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-core.c:blk_delay_queue
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/wakeup.c:__pm_wakeup_event
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_notify_event
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff810f8af0-ffffffff810f8b15: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fab10)
Location: kernel/time/time.c:609
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-core.c:blk_delay_queue
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff810fab10-ffffffff810fab33: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811054a0)
Location: kernel/time/time.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - kernel/sched/core.c:__sched_fork
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/migrate.c:numamigrate_update_ratelimit
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-core.c:blk_delay_queue
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/serio/libps2.c:ps2_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff811054a0-ffffffff811054c3: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110300)
Location: kernel/time/time.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/intel_rdt_monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:numa_migrate_preferred
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-core.c:blk_delay_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_events_poll_jiffies
  - block/genhd.c:disk_events_poll_jiffies
  - block/scsi_ioctl.c:sg_io
  - block/deadline-iosched.c:deadline_write_expire_store
  - block/deadline-iosched.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81110300-ffffffff81110323: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111b8f0)
Location: kernel/time/time.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_events_poll_jiffies
  - block/genhd.c:disk_events_poll_jiffies
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8111b8f0-ffffffff8111b913: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126320)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/soundwire/stream.c:sdw_prep_deprep_ports
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81126320-ffffffff81126343: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811322c0)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff811322c0-ffffffff811322e3: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141730)
Location: kernel/time/time.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:boot_delay_msec
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_check_old_data_flush
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_sq_offload_start
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/scsi_ioctl.c:blk_fill_sghdr_rq
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:ec_poll
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:fullbatt_handler
  - drivers/power/supply/charger-manager.c:fullbatt_handler
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/mcast.c:mld_process_v2
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff81141730-ffffffff81141750: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113d940)
Location: kernel/time/time.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:boot_delay_msec
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_check_old_data_flush
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_sq_offload_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/scsi_ioctl.c:blk_fill_sghdr_rq
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:ec_poll
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/mcast.c:mld_process_v2
  - net/packet/af_packet.c:init_prb_bdqc
```
**Symbols:**

```
ffffffff8113d940-ffffffff8113d960: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113eb90)
Location: kernel/time/time.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_sq_offload_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:mld_process_v2
  - net/ipv6/mcast.c:mld_process_v2
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8113eb90-ffffffff8113ebb0: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162020)
Location: kernel/time/time.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/reboot.c:hw_protection_shutdown
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_sq_offload_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81162020-ffffffff81162040: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81194f50)
Location: kernel/time/time.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/reboot.c:hw_protection_shutdown
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - io_uring/io_uring.c:io_sq_offload_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_helpers.c:thermal_set_delay_jiffies
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81194f50-ffffffff81194f76: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2cb0)
Location: kernel/time/time.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/fair.c:init_numa_balancing
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:update_task_scan_period
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/vmscan.c:store_min_ttl
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - io_uring/sqpoll.c:io_sq_offload_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff811d2cb0-ffffffff811d2cd6: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e6fa0)
Location: kernel/time/time.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
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
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/vmscan.c:min_ttl_ms_store
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - io_uring/sqpoll.c:io_sq_offload_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/packet/af_packet.c:packet_set_ring
  - net/devlink/health.c:devlink_health_report
```
**Symbols:**

```
ffffffff811e6fa0-ffffffff811e6fc9: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fccf0)
Location: kernel/time/time.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
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
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/vmscan.c:min_ttl_ms_store
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:stable_node_dup
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_do_writeback
  - fs/fs-writeback.c:wb_writeback
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - fs/pstore/platform.c:pstore_dump
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_prio_aging_expire_store
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - io_uring/sqpoll.c:io_sq_offload_create
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/regulator/irq_helpers.c:regulator_notifier_isr_work
  - drivers/tty/sysrq.c:sysrq_handle_keypress
  - drivers/tty/vt/vt_ioctl.c:vt_k_ioctl
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/iommu/dma-iommu.c:queue_iova
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_alter_state
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_stopped_cmd_ring
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_receive_byte
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_add_device
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/edac/edac_pci.c:edac_pci_add_device
  - drivers/mmc/core/mmc_ops.c:__mmc_poll_for_busy
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_update_interval
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_input.c:tcp_rtt_estimator
  - net/ipv4/tcp_output.c:tcp_delack_max
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_clamp_probe0_to_user_timeout
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/ipv6/mcast.c:__mld_query_work
  - net/packet/af_packet.c:packet_set_ring
  - net/devlink/health.c:devlink_health_report
```
**Symbols:**

```
ffffffff811fccf0-ffffffff811fcd15: __msecs_to_jiffies (STB_GLOBAL)
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
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199ce0)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/mmc/core/block.c:card_busy_detect
  - drivers/leds/led-core.c:led_timer_function
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
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffff800010199ce0-ffff800010199d1c: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4730)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_events_poll_jiffies
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
  - drivers/tty/serial/amba-pl011.c:pl011_int
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/scsi/sg.c:sg_new_write
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/mtd/nand/raw/nand_base.c:nand_soft_waitrdy
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_wait_for_idle
  - drivers/net/ethernet/ti/cpsw_sl.c:cpsw_sl_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/musb/musb_core.c:vbus_store
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/usb/musb/musb_core.c:musb_stage0_irq
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/media/cec/cec-api.c:cec_ioctl
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/mmc/core/block.c:card_busy_detect
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/mmc/host/cqhci.c:cqhci_halt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/tegra-hsp.c:tegra_hsp_mailbox_flush
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - sound/core/pcm_native.c:snd_pcm_drain
  - sound/core/pcm_lib.c:__snd_pcm_lib_xfer
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
  - sound/soc/soc-jack.c:gpio_handler
  - sound/soc/soc-pcm.c:soc_pcm_close
  - sound/soc/soc-compress.c:soc_compr_free
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c03e4730-c03e4758: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001f9f90)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:kopald
  - arch/powerpc/platforms/pseries/vio.c:vio_h_cop_sync
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_events_poll_jiffies
  - block/genhd.c:disk_events_poll_jiffies
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/8250/8250_fsl.c:fsl8250_handle_irq
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
c0000000001f9f90-c0000000001f9fc8: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a1f0)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:update_group_capacity
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/genhd.c:disk_events_poll_jiffies
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/mmc/core/block.c:card_busy_detect
  - drivers/mmc/host/mmc_spi.c:mmc_spi_detect_irq
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffe00012a1f0-ffffffe00012a22c: __msecs_to_jiffies (STB_GLOBAL)
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
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112aa70)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_user_cmd64
  - drivers/nvme/host/core.c:nvme_user_cmd
  - drivers/nvme/host/lightnvm.c:nvme_nvm_user_vcmd
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8112aa70-ffffffff8112aa93: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d2e0)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/core.c:nvme_user_cmd64
  - drivers/nvme/host/core.c:nvme_user_cmd
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff8111d2e0-ffffffff8111d303: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128790)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81128790-ffffffff811287b3: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int __msecs_to_jiffies(const unsigned int m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134e10)
Location: kernel/time/time.c:594
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:mbm_setup_overflow_handler
  - arch/x86/kernel/cpu/resctrl/monitor.c:cqm_setup_limbo_handler
  - kernel/sched/fair.c:newidle_balance
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
  - kernel/sched/rt.c:sched_rr_handler
  - kernel/power/process.c:freeze_processes
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/printk/printk.c:printk_timed_ratelimit
  - kernel/printk/printk.c:vprintk_emit
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep
  - mm/backing-dev.c:wb_wakeup_delayed
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:__stable_node_chain
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_track_foreign_dirty_slowpath
  - fs/fs-writeback.c:wb_workfn
  - fs/fs-writeback.c:wb_writeback
  - fs/io_uring.c:io_uring_create
  - fs/pstore/platform.c:pstore_timefunc
  - fs/pstore/platform.c:pstore_register
  - block/blk-sysfs.c:queue_io_timeout_store
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/mq-deadline.c:deadline_write_expire_store
  - block/mq-deadline.c:deadline_read_expire_store
  - lib/random32.c:__prandom_timer
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
  - drivers/video/fbdev/core/fbcon.c:fbcon_init
  - drivers/acpi/osl.c:acpi_os_wait_semaphore
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/battery.c:acpi_battery_get_state
  - drivers/acpi/apei/ghes.c:ghes_add_timer
  - drivers/xen/grant-table.c:__gnttab_unmap_refs_async
  - drivers/regulator/core.c:regulator_disable_deferred
  - drivers/tty/sysrq.c:sysrq_filter
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/scsi/scsi_sysfs.c:sdev_store_queue_ramp_up_period
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-scsi.c:ata_scsi_park_store
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-sff.c:ata_sff_queue_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-zpodd.c:zpodd_on_suspend
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/urb.c:usb_wait_anchor_empty_timeout
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/input/serio/libps2.c:__ps2_command
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_drain
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/serio/libps2.c:ps2_do_sendbyte
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input-poller.c:input_dev_poller_queue_work
  - drivers/input/mousedev.c:mousedev_event
  - drivers/input/keyboard/atkbd.c:atkbd_interrupt
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
  - drivers/media/cec/cec-adap.c:cec_transmit_done_ts
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/media/cec/cec-api.c:cec_receive_msg
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:charger_manager_probe
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/power/supply/charger-manager.c:_setup_polling
  - drivers/edac/edac_mc.c:edac_mc_add_mc_with_groups
  - drivers/edac/edac_device.c:edac_device_reset_delay_period
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc_ops.c:mmc_interrupt_hpi
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_enable_func
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_cd_irqt
  - drivers/leds/led-core.c:led_timer_function
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hwspinlock/hwspinlock_core.c:__hwspin_lock_timeout
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_interval_update
  - drivers/devfreq/devfreq.c:devfreq_monitor_resume
  - drivers/devfreq/devfreq.c:devfreq_monitor_start
  - drivers/devfreq/devfreq.c:devfreq_monitor
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/neighbour.c:neightbl_set
  - net/core/net-sysfs.c:bql_set_hold_time
  - net/core/devlink.c:devlink_health_report
  - net/sched/act_api.c:tc_dump_action
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_init_metrics
  - net/ipv4/igmp.c:unsolicited_report_interval
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/ipv6/mcast.c:igmp6_event_query
  - net/packet/af_packet.c:packet_set_ring
```
**Symbols:**

```
ffffffff81134e10-ffffffff81134e2d: __msecs_to_jiffies (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
