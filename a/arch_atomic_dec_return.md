# Function: <code>arch_atomic_dec_return</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81018698)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811d5988)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dccad)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81257533)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8125e53e)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812e1613)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In fs/proc/inode.c (ffffffff813b9625)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff813ceeba)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
```
```
In block/blk-core.c (ffffffff81542e75)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
```
```
In block/blk-wbt.c (ffffffff81579bd5)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815e594c)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff816298d5)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff817330f3)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757983)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817e74b2)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818380d0)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81844870)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ee15)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198c109)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfb3e)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
```
```
In net/core/dst.c (ffffffff81a10c28)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81a7a1c3)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81b97079)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bb9965)
Location: include/linux/atomic-arch-fallback.h:455
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff81018d6b)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff811d2c58)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9ddd)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81262113)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812685fb)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812ec563)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In fs/proc/inode.c (ffffffff813cb145)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff813e0aea)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
```
```
In block/blk-core.c (ffffffff8155f6f5)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
```
```
In block/blk-wbt.c (ffffffff81596ae5)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81609d0c)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff8164fca5)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8174e5a6)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81772a43)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817fc0ef)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818489a1)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81854b8d)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81954875)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fc39)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf85e)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
```
```
In net/core/dst.c (ffffffff81a10fd8)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81a83023)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81ba6d19)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bce275)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff8101a08b)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff811d390a)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db33d)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81266ba3)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8126df8b)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e03)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In fs/io_uring.c (ffffffff81391d1d)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/proc/inode.c (ffffffff813d2075)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff813e761a)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
```
```
In block/blk-core.c (ffffffff81567e95)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
```
```
In block/blk-wbt.c (ffffffff8159d919)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815eceec)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81632865)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8173242a)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817564be)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817e11a1)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bdb0)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff8183857d)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819386e5)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974219)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819b498e)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
```
```
In net/core/dst.c (ffffffff819f7e48)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81a6c0f3)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81b95ea9)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bc1c35)
Location: include/linux/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff8101c91b)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff8120078a)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8120894d)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff812a33a3)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812aaed8)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/bootmem_info.c (ffffffff8136cb33)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/io_uring.c (ffffffff813df57d)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/proc/inode.c (ffffffff814235a5)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8143932a)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
```
```
In block/blk-core.c (ffffffff815cc4e5)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
```
```
In block/blk-wbt.c (ffffffff81605fd9)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81659e0c)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff816a29c5)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff817b2c75)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817d9bee)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff81870b71)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b79a4)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818c2e8d)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dcc45)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cf19)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81a634ce)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
```
```
In net/core/dst.c (ffffffff81aa9a58)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81b25714)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81c628f5)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81c92245)
Location: include/linux/atomic/atomic-arch-fallback.h:525
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff8101f2bb)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff8123a857)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243f6a)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff812fb2b3)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff813eaec3)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff81481bc9)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/proc/inode.c (ffffffff8149c1d5)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff814b436a)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81532a80)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
```
In block/blk-core.c (ffffffff816782c5)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8168c84e)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-wbt.c (ffffffff816ba419)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff81e8e4a9)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread_unpark
  - io_uring/io_uring.c:__io_arm_poll_handler
```
```
In lib/sbitmap.c (ffffffff817724cd)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff817c4b62)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff818ef7e2)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81918619)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a03213)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81a0f09c)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b40ee5)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b86008)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd233d)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/dst.c (ffffffff81c21ea9)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81cae387)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81e051c5)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81e418b5)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff8102399b)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff8128940a)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291baa)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff813652a3)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff814730c3)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff81514c46)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff81530b05)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_compat_ioctl
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_read_iter
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/kernfs/dir.c (ffffffff8154b20a)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff815d0f50)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_xattr_release_block
  - fs/ext4/xattr.c:ext4_evict_ea_inode
```
```
In block/blk-core.c (ffffffff817345b5)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8174b01e)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-wbt.c (ffffffff8177a9a9)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff8179a95d)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In drivers/pci/pci.c (ffffffff818e1b42)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81a47512)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a7404f)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81aab)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81b8f04c)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd7575)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d25398)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7dfed)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/dst.c (ffffffff81dd4429)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81e6b81e)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81fda435)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8201bf15)
Location: include/linux/atomic/atomic-arch-fallback.h:609
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
