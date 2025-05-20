# Function: <code>jiffies_to_msecs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eaba0)
Location: kernel/time/time.c:253
Inline: False
Direct callers:
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/bsg.c:bsg_rq_end_io
  - block/deadline-iosched.c:deadline_write_expire_show
  - block/deadline-iosched.c:deadline_read_expire_show
  - block/cfq-iosched.c:cfq_target_latency_show
  - block/cfq-iosched.c:cfq_group_idle_show
  - block/cfq-iosched.c:cfq_slice_idle_show
  - block/cfq-iosched.c:cfq_slice_async_show
  - block/cfq-iosched.c:cfq_slice_sync_show
  - block/cfq-iosched.c:cfq_fifo_expire_async_show
  - block/cfq-iosched.c:cfq_fifo_expire_sync_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_close
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/base/power/sysfs.c:rtpm_active_time_show
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/md/bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff810eaba0-ffffffff810eabb2: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1840)
Location: kernel/time/time.c:253
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/bsg.c:bsg_rq_end_io
  - block/deadline-iosched.c:deadline_write_expire_show
  - block/deadline-iosched.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_close
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/charger-manager.c:cm_suspend_complete
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/power/charger-manager.c:cm_suspend_prepare
  - drivers/md/bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff810f1840-ffffffff810f1852: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f89c0)
Location: kernel/time/time.c:253
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:__alloc_pages_slowpath
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/bsg.c:bsg_rq_end_io
  - block/deadline-iosched.c:deadline_write_expire_show
  - block/deadline-iosched.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff810f89c0-ffffffff810f89d2: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fa9e0)
Location: kernel/time/time.c:343
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:__alloc_pages_slowpath
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_rq_end_io
  - block/deadline-iosched.c:deadline_write_expire_show
  - block/deadline-iosched.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff810fa9e0-ffffffff810fa9f2: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105370)
Location: kernel/time/time.c:309
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_rq_end_io
  - block/deadline-iosched.c:deadline_write_expire_show
  - block/deadline-iosched.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
  - drivers/base/power/sysfs.c:rtpm_suspended_time_show
  - drivers/base/power/sysfs.c:rtpm_active_time_show
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff81105370-ffffffff81105382: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110180)
Location: kernel/time/time.c:310
Inline: False
Direct callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_rq_end_io
  - block/deadline-iosched.c:deadline_write_expire_show
  - block/deadline-iosched.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/base/power/sysfs.c:runtime_suspended_time_show
  - drivers/base/power/sysfs.c:runtime_active_time_show
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff81110180-ffffffff81110192: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111b7c0)
Location: kernel/time/time.c:308
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/base/power/sysfs.c:runtime_suspended_time_show
  - drivers/base/power/sysfs.c:runtime_active_time_show
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff8111b7c0-ffffffff8111b7d2: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811261f0)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff811261f0-ffffffff81126202: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132190)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff81132190-ffffffff811321a2: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141600)
Location: kernel/time/time.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_fill_request_table
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
```
**Symbols:**

```
ffffffff81141600-ffffffff81141612: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113d810)
Location: kernel/time/time.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_fill_request_table
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
  - net/ipv6/addrconf.c:ipv6_store_devconf
```
**Symbols:**

```
ffffffff8113d810-ffffffff8113d822: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ea60)
Location: kernel/time/time.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/thermal/gov_power_allocator.c:pid_controller
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff8113ea60-ffffffff8113ea72: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81161ef0)
Location: kernel/time/time.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/thermal/gov_power_allocator.c:pid_controller
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff81161ef0-ffffffff81161f02: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81194e10)
Location: kernel/time/time.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_all_workqueues
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/mq-deadline.c:deadline_prio_aging_expire_show
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_release_i2c_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/thermal/gov_power_allocator.c:pid_controller
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff81194e10-ffffffff81194e28: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2b30)
Location: kernel/time/time.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_all_workqueues
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:show_min_ttl
  - mm/mprotect.c:change_pte_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/huge_memory.c:change_huge_pmd
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/mq-deadline.c:deadline_prio_aging_expire_show
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/thermal/gov_power_allocator.c:pid_controller
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/core/devlink.c:devlink_nl_health_reporter_fill
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff811d2b30-ffffffff811d2b48: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e6e20)
Location: kernel/time/time.c:374
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_all_workqueues
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:min_ttl_ms_show
  - mm/mm_init.c:memmap_init_zone_device
  - mm/mprotect.c:change_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/mq-deadline.c:deadline_prio_aging_expire_show
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/thermal/gov_power_allocator.c:pid_controller
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
**Symbols:**

```
ffffffff811e6e20-ffffffff811e6e38: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fcb70)
Location: kernel/time/time.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_minmax_conv
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_all_workqueues
  - kernel/sched/core.c:sysctl_numa_balancing
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/fair.c:should_numa_migrate_memory
  - kernel/sched/build_policy.c:sched_rr_handler
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/rcu/tree.c:print_cpu_stat_info
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:min_ttl_ms_show
  - mm/mm_init.c:memmap_init_zone_device
  - mm/mprotect.c:change_pte_range
  - mm/huge_memory.c:change_huge_pmd
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
  - block/mq-deadline.c:deadline_prio_aging_expire_show
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/xen/events/events_base.c:handle_irq_for_port
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_proc_debug_helper
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/power/supply/charger-manager.c:cm_setup_timer
  - drivers/thermal/gov_power_allocator.c:pid_controller
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stat_for_entry
  - drivers/mmc/core/sdio_cis.c:cistpl_funce_func
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/sched/sch_generic.c:dev_watchdog
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp.c:tcp_get_info
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/devlink/health.c:devlink_nl_health_reporter_fill
```
**Symbols:**

```
ffffffff811fcb70-ffffffff811fcb83: jiffies_to_msecs (STB_GLOBAL)
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
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199b30)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - arch/arm64/kernel/psci.c:cpu_psci_cpu_kill
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffff800010199b30-ffff800010199b58: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e4538)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/amba-pl011.c:pl011_dma_rx_poll
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_jiffies_to_msec64
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
c03e4538-c03e4554: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001f9e50)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_target_index
  - drivers/cpufreq/powernv-cpufreq.c:gpstate_timer_handler
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
c0000000001f9e50-c0000000001f9e60: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a074)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffe00012a074-ffffffe00012a098: jiffies_to_msecs (STB_GLOBAL)
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
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112a940)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff8112a940-ffffffff8112a952: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d1b0)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff8111d1b0-ffffffff8111d1c2: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128660)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff81128660-ffffffff81128672: jiffies_to_msecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int jiffies_to_msecs(const long unsigned int j);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134cf0)
Location: kernel/time/time.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unblock_punit_i2c_access
  - kernel/sysctl.c:do_proc_dointvec_ms_jiffies_conv
  - kernel/workqueue.c:show_workqueue_state
  - kernel/irq/proc.c:irq_spurious_proc_show
  - kernel/time/timer.c:msleep_interruptible
  - kernel/time/timer.c:msleep_interruptible
  - mm/page_alloc.c:memmap_init_zone_device
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:jbd2_seq_info_show
  - fs/jbd2/journal.c:trace_raw_output_jbd2_checkpoint_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - fs/jbd2/journal.c:trace_raw_output_jbd2_run_stats
  - block/blk-sysfs.c:queue_io_timeout_show
  - block/genhd.c:diskstats_show
  - block/genhd.c:diskstats_show
  - block/partition-generic.c:part_stat_show
  - block/partition-generic.c:part_stat_show
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/mq-deadline.c:deadline_write_expire_show
  - block/mq-deadline.c:deadline_read_expire_show
  - drivers/pwm/sysfs.c:capture_show
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/tty/serial/serial_core.c:uart_get_info
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/scsi_sysfs.c:sdev_show_queue_ramp_up_period
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/scsi_debugfs.c:scsi_show_rq
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_proc_seq_show_debug
  - drivers/scsi/sg.c:sg_add_request
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/ata/libata-scsi.c:ata_scsi_park_show
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:active_duration_show
  - drivers/usb/core/sysfs.c:connected_duration_show
  - drivers/power/supply/charger-manager.c:cm_suspend_complete
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/power/supply/charger-manager.c:cm_suspend_prepare
  - drivers/md/md-bitmap.c:timeout_show
  - drivers/md/dm-stats.c:dm_stats_account_io
  - drivers/devfreq/devfreq.c:trans_stat_show
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/neighbour.c:neightbl_fill_parms
  - net/core/net-sysfs.c:bql_show_hold_time
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_metrics.c:tcp_metrics_fill_info
  - net/ipv4/tcp_cubic.c:bictcp_acked
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
  - net/ipv6/addrconf.c:inet6_fill_ifla6_attrs
```
**Symbols:**

```
ffffffff81134cf0-ffffffff81134cfe: jiffies_to_msecs (STB_GLOBAL)
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
