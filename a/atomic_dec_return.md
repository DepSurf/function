# Function: <code>atomic_dec_return</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014d6d)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_event_cpu_offline
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff8119318b)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119b86f)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
```
```
In kernel/memremap.c (ffffffff811e93a5)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f3257)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff8126bc98)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In fs/proc/inode.c (ffffffff8131a5d5)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8132cc79)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In block/blk-mq.c (ffffffff8148e325)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
```
```
In block/blk-wbt.c (ffffffff814b8df9)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
```
```
In lib/sbitmap.c (ffffffff814f86a6)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff8151ce42)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8160e847)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8162ffb1)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff816ab542)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816c501a)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f2514)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/sd.c (ffffffff816fdcf0)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817e1005)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/dm.c (ffffffff8180760a)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b095)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff8186c305)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/dst.c (ffffffff8189fafa)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff818dc25e)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff819be66e)
Location: include/asm-generic/atomic-instrumented.h:196
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016838)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811af212)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b79ef)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121cd43)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff8129c8d3)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812c23d5)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/io_uring.c (ffffffff8132f888)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff813595a5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8136c239)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_put_active
```
```
In block/blk-core.c (ffffffff814cb385)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-wbt.c (ffffffff814fb6c5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8153b037)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81561c12)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8165f583)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81682cc3)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817072b2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8171fb9c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8175084a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8175bf72)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8184e315)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81889625)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff818c6e9a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff818d6d25)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/dst.c (ffffffff8190e9ea)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81969fdb)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81a64c79)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/intel/uncore.c (ffffffff810171e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811ba6e2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c305f)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122a723)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff812ac573)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812d4305)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/io_uring.c (ffffffff81343056)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff813717f5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff813843da)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-core.c (ffffffff814e4575)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-wbt.c (ffffffff81519615)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff8155be57)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81582db2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81681cc3)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a5353)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff8172b502)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff81743e6a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774a6d)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8177fe12)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8187fd55)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb5d5)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff818f8f0a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff819090a5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/dst.c (ffffffff8194105a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff819a0a4b)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81a9b8e9)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/intel/uncore.c (ffffffff81018698)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811d5988)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dccad)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81257533)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8125e53e)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812e1613)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In fs/proc/inode.c (ffffffff813b9625)
Location: include/asm-generic/atomic-instrumented.h:338
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
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In block/blk-core.c (ffffffff81542e75)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In block/blk-wbt.c (ffffffff81579bd5)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815e594c)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff816298d5)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff817330f3)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81757983)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817e74b2)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818380d0)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81844870)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff8194ee15)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198c109)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819cfb3e)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In net/core/dst.c (ffffffff81a10c28)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81a7a1c3)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81b97079)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bb9965)
Location: include/asm-generic/atomic-instrumented.h:338
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
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff811d2c58)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811d9ddd)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81262113)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812685fb)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812ec563)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In fs/proc/inode.c (ffffffff813cb145)
Location: include/asm-generic/atomic-instrumented.h:338
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
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In block/blk-core.c (ffffffff8155f6f5)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In block/blk-wbt.c (ffffffff81596ae5)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81609d0c)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff8164fca5)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8174e5a6)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_array_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81772a43)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817fc0ef)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818489a1)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81854b8d)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81954875)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fc39)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819cf85e)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In net/core/dst.c (ffffffff81a10fd8)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81a83023)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81ba6d19)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bce275)
Location: include/asm-generic/atomic-instrumented.h:338
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
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff811d390a)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811db33d)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81266ba3)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff8126df8b)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/memory_hotplug.c (ffffffff812c6e03)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In fs/io_uring.c (ffffffff81391d1d)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/proc/inode.c (ffffffff813d2075)
Location: include/asm-generic/atomic-instrumented.h:338
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
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In block/blk-core.c (ffffffff81567e95)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In block/blk-wbt.c (ffffffff8159d919)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815eceec)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81632865)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff8173242a)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817564be)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff817e11a1)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bdb0)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff8183857d)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819386e5)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81974219)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff819b498e)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
```
```
In net/core/dst.c (ffffffff819f7e48)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81a6c0f3)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81b95ea9)
Location: include/asm-generic/atomic-instrumented.h:338
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81bc1c35)
Location: include/asm-generic/atomic-instrumented.h:338
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
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff8120078a)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8120894d)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff812a33a3)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/swap.c (ffffffff812aaed8)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - mm/swap.c:put_devmap_managed_page
```
```
In mm/bootmem_info.c (ffffffff8136cb33)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/io_uring.c (ffffffff813df57d)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_thread_unpark
```
```
In fs/proc/inode.c (ffffffff814235a5)
Location: include/linux/atomic/atomic-instrumented.h:249
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
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
```
```
In block/blk-core.c (ffffffff815cc4e5)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
```
```
In block/blk-wbt.c (ffffffff81605fd9)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81659e0c)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff816a29c5)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff817b2c75)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff817d9bee)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff81870b71)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b79a4)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff818c2e8d)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff819dcc45)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cf19)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81a634ce)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
```
```
In net/core/dst.c (ffffffff81aa9a58)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81b25714)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81c628f5)
Location: include/linux/atomic/atomic-instrumented.h:249
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81c92245)
Location: include/linux/atomic/atomic-instrumented.h:249
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
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff8123a857)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81243f6a)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff812fb2b3)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff813eaec3)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff81481bc9)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
```
```
In fs/proc/inode.c (ffffffff8149c1d5)
Location: include/linux/atomic/atomic-instrumented.h:262
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
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81532a80)
Location: include/linux/atomic/atomic-instrumented.h:262
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
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8168c84e)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-wbt.c (ffffffff816ba419)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/io_uring.c (ffffffff81e8e4a9)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_sq_thread_unpark
  - io_uring/io_uring.c:__io_arm_poll_handler
```
```
In lib/sbitmap.c (ffffffff817724cd)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff817c4b62)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff818ef7e2)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81918619)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a03213)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81a0f09c)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81b40ee5)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b86008)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81bd233d)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/dst.c (ffffffff81c21ea9)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81cae387)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81e051c5)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff81e418b5)
Location: include/linux/atomic/atomic-instrumented.h:262
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
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff8128940a)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff81291baa)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff813652a3)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff814730c3)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff81514c46)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff81530b05)
Location: include/linux/atomic/atomic-instrumented.h:262
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
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff815d0f50)
Location: include/linux/atomic/atomic-instrumented.h:262
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
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
```
```
In block/blk-mq-tag.c (ffffffff8174b01e)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_tag_idle
```
```
In block/blk-wbt.c (ffffffff8177a9a9)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff8179a95d)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In drivers/pci/pci.c (ffffffff818e1b42)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81a47512)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a7404f)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81aab)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81b8f04c)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81cd7575)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d25398)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81d7dfed)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/core/dst.c (ffffffff81dd4429)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81e6b81e)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81fda435)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8201bf15)
Location: include/linux/atomic/atomic-instrumented.h:262
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff810236bb)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff812a616e)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aee0a)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81397763)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff814a7833)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff8154c646)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff81568c85)
Location: include/linux/atomic/atomic-instrumented.h:607
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
In fs/kernfs/dir.c (ffffffff81582e5a)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81608b00)
Location: include/linux/atomic/atomic-instrumented.h:607
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
In block/blk-core.c (ffffffff817709b5)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
```
```
In block/blk-wbt.c (ffffffff817b9c65)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff817dba0d)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In drivers/pci/pci.c (ffffffff81924f82)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81a916c2)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe6d3)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd57e4)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81be519c)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f745)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e5d8)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81dec36d)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/netlink/af_netlink.c (ffffffff81ec786a)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff820560f5)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8209c5b5)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In arch/x86/events/intel/uncore.c (ffffffff810297eb)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff812c1c8e)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb32a)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff813c1593)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff814d8863)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/open.c (ffffffff814d98ca)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2abf)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/mbcache.c (ffffffff81582476)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff815a12a5)
Location: include/linux/atomic/atomic-instrumented.h:607
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
In fs/kernfs/dir.c (ffffffff815bba8a)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81641840)
Location: include/linux/atomic/atomic-instrumented.h:607
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
In block/blk-core.c (ffffffff817b2c25)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
```
```
In block/blk-wbt.c (ffffffff817fe3d5)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff8181fd8d)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In drivers/pci/pci.c (ffffffff8196d652)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81ae4032)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11453)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a438)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81c3a2fc)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df60f5)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45ee8)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea26bd)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/netlink/af_netlink.c (ffffffff81f8abcc)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff82128975)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff82173d95)
Location: include/linux/atomic/atomic-instrumented.h:607
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
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
In init/do_mounts.c (ffff800011431878)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In virt/kvm/kvm_main.c (ffff8000100bbf7c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:__gfn_to_pfn_memslot
  - virt/kvm/kvm_main.c:kvm_put_kvm
  - virt/kvm/kvm_main.c:kvm_create_vm
```
```
In virt/kvm/arm/mmu.c (ffff8000100ca934)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:stage2_set_pte
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:__unmap_hyp_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
  - virt/kvm/arm/mmu.c:unmap_stage2_range
```
```
In kernel/fork.c (ffff8000100f5804)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffff8000100fd32c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (ffff800010108550)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffff80001010b51c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (ffff80001011acdc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffff80001011cdb4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (ffff80001012b6c0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (ffff80001012d0dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (ffff80001013133c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/groups.c:__arm64_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (ffff80001013d100)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (ffff80001015ad88)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (ffff8000101688b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/irq/manage.c (ffff80001017935c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/rcu/srcutree.c (ffff80001018a640)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffff80001018c1f0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/futex.c (ffff8000101b7bd8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (ffff8000101be210)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
  - kernel/uid16.c:__arm64_sys_setgroups16
```
```
In kernel/cgroup/cgroup.c (ffff8000101d07bc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101da07c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101db518)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/utsname.c (ffff8000101e51f0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (ffff8000101e6770)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffff8000101e7524)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffff8000101e8608)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/trace/trace_events.c (ffff80001023b3a4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242958)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/bpf/syscall.c (ffff80001025fe5c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (ffff800010287e14)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/bpf/stackmap.c (ffff80001028bc14)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffff80001029a98c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (ffff8000102a59d0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/events/uprobes.c:is_trap_at_addr
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (ffff8000102a92e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (ffff8000102ab390)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/filemap.c (ffff8000102b16b8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:wait_on_page_bit_common
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (ffff8000102b7a14)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (ffff8000102bd260)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffff8000102bf1c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffff8000102c1788)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffff8000102c408c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffff8000102cb51c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffff8000102d59a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/mmu_context.c (ffff8000102e001c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffff8000102f1288)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffff8000102fba0c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffff8000102fccf8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffff8000102fe1c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffff80001030a6cc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffff8000103123f0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/page_alloc.c (ffff80001031726c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (ffff80001031e6ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:__arm64_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (ffff8000103223a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffff800010327a44)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/zswap.c (ffff80001032c5e4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/hugetlb.c (ffff8000103361d0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffff800010339b40)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/mmu_notifier.c (ffff80001033cd24)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffff80001033fbac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (ffff80001034e0ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (ffff8000103530f8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (ffff800010359c28)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035f818)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (ffff800010368bcc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (ffff800010370644)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
```
```
In mm/zsmalloc.c (ffff800010375d04)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffff800010378424)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In mm/page_idle.c (ffff80001037934c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffff800010379d68)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/open.c (ffff80001037e450)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffff800010380460)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/file_table.c (ffff8000103851b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffff800010386a60)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffff80001038ce58)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (ffff80001038fcc0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffff800010393354)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffff8000103a8390)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (ffff8000103b1dc8)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/namespace.c (ffff8000103b4af8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffff8000103c0a5c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffff8000103c3e1c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/splice.c (ffff8000103ce474)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffff8000103d58e0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffff8000103dd00c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffff8000103e0acc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffff8000103e4f60)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffff8000103e6ef4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (ffff8000103e9d98)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/userfaultfd.c (ffff8000103f6e04)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/userfaultfd.c:__arm64_sys_userfaultfd
```
```
In fs/aio.c (ffff8000103fa710)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffff800010403444)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/verity/enable.c (ffff800010411120)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffff8000104133a4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffff800010420f54)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (ffff800010424804)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffff800010424f0c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (ffff800010428444)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffff80001042bbfc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffff80001042d36c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffff8000104397dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/inode.c (ffff80001043b378)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (ffff80001043c94c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffff80001043e754)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (ffff800010444fd0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (ffff800010452014)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/kernfs/file.c (ffff800010454d0c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/sysfs/mount.c (ffff800010457a64)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffff800010458ce4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffff80001045af30)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffff80001045d7ac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (ffff80001047b310)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffff800010488fc4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffff8000104923c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffff80001049a7b8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffff8000104a3bbc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffff8000104a4df4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffff8000104c0f58)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/ext4/xattr.c (ffff8000104c4b68)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (ffff8000104c833c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/jbd2/transaction.c (ffff8000104ca5f0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffff8000104cf414)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffff8000104dbcb0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffff8000104de140)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffff8000104e24e0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffff8000104f626c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffff8000104f66e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffff8000105031bc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (ffff80001050e63c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
```
```
In fs/fuse/inode.c (ffff800010512150)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/fuse/readdir.c (ffff8000105154c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (ffff800010529dbc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffff80001052cd44)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (ffff800010533b54)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffff8000105352b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffff800010535948)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffff800010536358)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In security/tomoyo/common.c (ffff80001057d8ac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffff8000105802b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (ffff800010594e68)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffff80001059d970)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (ffff8000105dbc58)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (ffff8000105e0d74)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-ioc.c (ffff8000105e8964)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/partition-generic.c (ffff8000105fd100)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffff8000105ff524)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffff800010600080)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffff800010600504)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffff8000106010c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffff800010603100)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
```
```
In block/partitions/msdos.c (ffff800010604984)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffff8000106051f8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffff8000106054bc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffff800010605824)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffff800010605ac4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffff800010606020)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffff800010606c54)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffff800010606ef8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/blk-wbt.c (ffff800010621068)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffff80001066a2f0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffff8000106e6b18)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffff8000107434c0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/dma/dmaengine.c (ffff8000107fd0b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082b23c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/xen/grant-table.c (ffff80001082e240)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_handle_deferred
```
```
In drivers/reset/core.c (ffff80001084d0c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffff80001087dc5c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffff8000108b3840)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/base/power/runtime.c (ffff8000108fd74c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffff80001090887c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (ffff800010923968)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (ffff8000109408d0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/nvdimm/bus.c (ffff800010952e50)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (ffff800010968000)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (ffff80001096cbfc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffff800010970d20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffff800010978dbc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffff800010987c80)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/net/tun.c (ffff8000109e18e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e2b64)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_cleanup
```
```
In drivers/usb/core/devio.c (ffff800010a2d304)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/power/supply/power_supply_core.c (ffff800010acc5e4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (ffff800010ae9b20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffff800010af7f44)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffff800010afe544)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (ffff800010b0a034)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (ffff800010b0babc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b13cb0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81200)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/devfreq/devfreq.c (ffff800010b864e0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In net/core/sock.c (ffff800010baca18)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (ffff800010bb3da0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (ffff800010bc111c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (ffff800010bced24)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (ffff800010be0e78)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (ffff800010bfdc08)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (ffff800010c06d54)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffff800010c0ca68)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffff800010c0e784)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (ffff800010c4dd44)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_input.c (ffff800010c5eb50)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (ffff800010c623dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (ffff800010c76190)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (ffff800010c81f8c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8f148)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (ffff800010c987ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In net/ipv4/udp.c (ffff800010c9f454)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (ffff800010cb68c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (ffff800010cc0e20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (ffff800010ccfc00)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3620)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0c58)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (ffff800010ce35ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffff800010cead48)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec41c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffff800010cf4050)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/ipv6/ip6_output.c (ffff800010cf8484)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffff800010cfd924)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (ffff800010d1583c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (ffff800010d2af68)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (ffff800010d3f094)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (ffff800010d5b710)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (ffff800010d6bb20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (ffff800010d72ed4)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In lib/dec_and_lock.c (ffff800010d847a8)
Location: include/linux/atomic-fallback.h:453
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
In init/do_mounts.c (c150189c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/arm/mm/fault-armv.c (c1507e90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/arm/mm/fault-armv.c:check_writebuffer_bugs
```
```
In kernel/fork.c (c0353fac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:mmdrop_async
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (c035a430)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
```
```
In kernel/ptrace.c (c0361f10)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c0363ddc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/umh.c (c036f29c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c03708dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/nsproxy.c (c037bc48)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
```
```
In kernel/cred.c (c037d5c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:prepare_creds
  - kernel/cred.c:cred_alloc_blank
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/groups.c (c038078c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (c038d2c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:finish_task_switch
```
```
In kernel/sched/topology.c (c03a77dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/locking/mutex.c (c03b4fa0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/power/swap.c (c03c0a70)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
  - kernel/power/swap.c:hib_end_io
```
```
In kernel/irq/manage.c (c03cb288)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/rcu/srcutree.c (c03d8d00)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (c03dc644)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/futex.c (c040198c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/uid16.c (c04064e4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_setgroups16
  - kernel/uid16.c:__se_sys_setgroups16
```
```
In kernel/acct.c (c040e514)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/cgroup/cgroup.c (c0414324)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (c041c9d0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c041d74c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/utsname.c (c0425aa0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/utsname.c:free_uts_ns
```
```
In kernel/user_namespace.c (c04267e4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (c04276c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (c0428704)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/audit_tree.c (c0435698)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/trace/trace_events.c (c0475ad4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c047e298)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/bpf/syscall.c (c0492d1c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_uref
```
```
In kernel/bpf/cpumap.c (c04b8008)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/bpf/stackmap.c (c04bb26c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c04c1f8c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:put_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/uprobes.c (c04d74cc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c04d8664)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In mm/filemap.c (c04de184)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/oom_kill.c (c04e469c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/page-writeback.c (c04e97a0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (c04eaee4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c04ecad8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c04eeb1c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c04f5530)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c04fdb44)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/mmu_context.c (c0504908)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (c0515670)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (c051c098)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (c051c410)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c051ce04)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0526bd4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (c052d27c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/page_alloc.c (c0531968)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (c05385dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/swap_state.c (c053aa54)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c053ef78)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:unuse_mm
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c05428f8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
```
```
In mm/mmu_notifier.c (c054388c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (c0545ec4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (c0552a38)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (c055a228)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (c0561fa4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (c0563988)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c0564a14)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c0564f94)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/open.c (c0568de0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (c056b6a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/file_table.c (c056e09c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (c056f384)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (c05759f4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:would_dump
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
```
```
In fs/pipe.c (c0576ac4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c057a270)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (c0589108)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/file.c (c05912bc)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/namespace.c (c059303c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (c059df78)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (c05a1994)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/splice.c (c05a9bcc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (c05af00c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (c05b64ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_slow
```
```
In fs/block_dev.c (c05b85cc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (c05bcf1c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (c05bebc4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/notify/mark.c (c05c0ab8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_drop_object
```
```
In fs/userfaultfd.c (c05cdd40)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/aio.c (c05ce17c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c05d69c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/verity/enable.c (c05dd74c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c05df6f0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c05e91f4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/binfmt_elf_fdpic.c (c05ea324)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/binfmt_elf_fdpic.c:elf_fdpic_core_dump
```
```
In fs/mbcache.c (c05edcbc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/coredump.c (c05f10d8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c05f5014)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (c05f64bc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (c0600e48)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:smaps_pte_entry
  - fs/proc/task_mmu.c:proc_map_release
```
```
In fs/proc/inode.c (c0601958)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (c0602970)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c0603e2c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:mem_release
```
```
In fs/proc/array.c (c0609c14)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/kernfs/dir.c (c0614e04)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/kernfs/file.c (c0616c50)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_put_open_node
```
```
In fs/sysfs/mount.c (c06197ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (c061aa34)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c061c398)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/dir.c:detach_attrs
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c061e534)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/ext4/inline.c (c063cbac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c064b540)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (c0653710)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_unload_buddy
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (c065c12c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (c0665aac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (c0666670)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0684bd0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/ext4/xattr.c (c0688bc0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/verity.c (c068bd90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c068df8c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (c06920fc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c069d3b8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c069fd70)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/ecryptfs/mmap.c (c06b3be4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c06b4098)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c06bf3fc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (c06c9de8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_release_user_pages
```
```
In fs/fuse/inode.c (c06cd264)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/fuse/readdir.c (c06d041c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In ipc/mqueue.c (c06e3b74)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c06e5674)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/keyctl.c (c06eb394)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (c06ec9a4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c06ed1cc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c06eda10)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In security/tomoyo/common.c (c072fe34)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (c0732798)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/domain.c (c0745ebc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (c074e3e0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_getprocattr
```
```
In block/bio.c (c0789158)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (c078ec28)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-ioc.c (c07951bc)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/partition-generic.c (c07a7908)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c07aa7e4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c07ab3c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c07ab7ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c07ac4b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c07ae6b8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (c07afc24)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c07b03fc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c07b05dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c07b08e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c07b0b40)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c07b0e28)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c07b1f90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c07b2358)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/blk-wbt.c (c07c884c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (c0811bd4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0852144)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_retention_disable
```
```
In drivers/pci/pci.c (c0881dfc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (c08c7b9c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/dma/dmaengine.c (c091db14)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (c09476c0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/reset/core.c (c0959558)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (c097f250)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (c09ad68c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/base/power/runtime.c (c09e7ef0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (c09efab4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/block/loop.c (c0a068c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (c0a29674)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_disable
```
```
In drivers/dma-buf/dma-fence-array.c (c0a3e3fc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
```
```
In drivers/dma-buf/udmabuf.c (c0a4211c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c0a457e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (c0a4c9dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (c0a59668)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/net/tun.c (c0ac6b2c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
```
```
In drivers/usb/core/devio.c (c0b02b2c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/power/supply/power_supply_core.c (c0bac6c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (c0bccdf4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (c0bd77ec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (c0bdcc7c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-io.c (c0be84f4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dec_count
```
```
In drivers/md/dm-kcopyd.c (c0be9084)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1d58)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/cpufreq/omap-cpufreq.c (c0c0047c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/cpufreq/omap-cpufreq.c:omap_cpu_exit
```
```
In drivers/remoteproc/remoteproc_core.c (c0c647e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
```
```
In drivers/devfreq/devfreq.c (c0c68858)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In net/core/sock.c (c0ccaa14)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
```
```
In net/core/skbuff.c (c0cd67d0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/net_namespace.c (c0cdc290)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/dev.c (c0ce4a90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
```
```
In net/core/dst.c (c0cfadd4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/dst.c:dst_destroy
```
```
In net/core/filter.c (c0d1a048)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
```
```
In net/core/xdp.c (c0d2007c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c0d251b8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c0d2747c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/netlink/af_netlink.c (c0d5cdbc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/ipv4/ip_input.c (c0d6e1c0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_output.c (c0d71bd8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp.c (c0d848c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/tcp_output.c (c0d90b50)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
```
```
In net/ipv4/tcp_ipv4.c (c0d9e0c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
```
```
In net/ipv4/raw.c (c0da6654)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In net/ipv4/udp.c (c0dac6a4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
```
```
In net/ipv4/fib_semantics.c (c0dc2078)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/ping.c (c0dcbd60)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_init_sock
```
```
In net/ipv4/ipmr.c (c0dda170)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
```
```
In net/ipv4/tcp_bpf.c (c0ddd3cc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/xfrm/xfrm_policy.c (c0de9f6c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_state.c (c0debb7c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c0df3070)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4304)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (c0dfb334)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:init_peercred
```
```
In net/unix/scm.c (c0dfbf70)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/unix/scm.c:unix_notinflight
```
```
In net/ipv6/ip6_output.c (c0dffbdc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (c0e050bc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/route.c (c0e1b3b8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_init
```
```
In net/ipv6/raw.c (c0e2eea8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/ip6_flowlabel.c (c0e419e0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/packet/af_packet.c (c0e5b840)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (c0e69c04)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (c0e6fddc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In lib/dec_and_lock.c (c0e7fc30)
Location: include/linux/atomic-fallback.h:453
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
In init/do_mounts.c (c000000001344c84)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/powerpc/kernel/rtas.c (c00000000003d864)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_cpu
  - arch/powerpc/kernel/rtas.c:__rtas_suspend_last_cpu
```
```
In arch/powerpc/kernel/iommu.c (c000000000051d74)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - arch/powerpc/kernel/iommu.c:iommu_tce_table_put
```
```
In arch/powerpc/mm/pgtable-frag.c (c000000000089374)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - arch/powerpc/mm/pgtable-frag.c:pte_fragment_free
```
```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000091144)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pmd_fragment_free
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000096540)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:do_exit_flush_lazy_tlb
```
```
In arch/powerpc/mm/book3s64/iommu_api.c (c0000000000a0ec8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_free
  - arch/powerpc/mm/book3s64/iommu_api.c:mm_iommu_do_alloc
```
```
In arch/powerpc/perf/core-book3s.c (c00000000012898c)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/fork.c (c00000000013b98c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:mmput
  - kernel/fork.c:mmput
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
  - kernel/fork.c:put_task_stack
```
```
In kernel/exit.c (c000000000142cd4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:put_task_struct_rcu_user
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (c00000000014f964)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_compat_sys_ptrace
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (c000000000152030)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (c000000000160e98)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/umh.c (c000000000162574)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (c000000000166f30)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (c00000000016dce4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/pid.c:put_pid
```
```
In kernel/kthread.c (c000000000173204)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (c000000000174258)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (c0000000001763dc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:abort_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (c000000000178810)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/groups.c (c00000000017a8e4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_groups
```
```
In kernel/sched/core.c (c00000000018be98)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sched/core.c:idle_task_exit
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/fair.c (c00000000019ae6c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_free
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_find_cpu
```
```
In kernel/sched/rt.c (c0000000001a2484)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (c0000000001a7ae8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:task_contending
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/topology.c (c0000000001af044)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/autogroup.c (c0000000001b4c08)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (c0000000001bff78)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
```
In kernel/locking/mutex.c (c0000000001c0684)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/locking/mutex.c:atomic_dec_and_mutex_lock
```
```
In kernel/locking/rtmutex.c (c0000000001c2f54)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (c0000000001d48a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (c0000000001e3178)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (c0000000001e5568)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (c0000000001e9ae0)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/kcmp.c (c0000000001f79d4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (c000000000211308)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (c00000000021dc14)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:put_pi_state
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (c00000000023aeb0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
```
```
In kernel/cgroup/namespace.c (c000000000247478)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (c0000000002490b4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (c0000000002558c0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c00000000025664c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (c0000000002579e4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/pid_namespace.c:put_pid_ns
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (c000000000258fb0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_signal_done
```
```
In kernel/audit.c (c00000000025d250)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/audit_watch.c (c000000000267be0)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/audit_tree.c (c00000000026bbbc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:audit_put_chunk
```
```
In kernel/hung_task.c (c00000000028342c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (c000000000285e68)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/seccomp.c:__put_seccomp_filter
```
```
In kernel/relay.c (c0000000002892b8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (c00000000028b924)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace.c (c0000000002a478c)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/trace/trace_sched_wakeup.c (c0000000002bab6c)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/trace/trace_events.c (c0000000002c5820)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d5070)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/bpf/syscall.c (c00000000030a284)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/bpf/btf.c (c00000000032e144)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/bpf/cpumap.c (c000000000333284)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In kernel/bpf/stackmap.c (c000000000337c54)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (c000000000353214)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/ring_buffer.c (c000000000355004)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_free_aux
```
```
In kernel/events/uprobes.c (c00000000035bcb4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:prepare_uprobe
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:uprobe_write_opcode
  - kernel/events/uprobes.c:__update_ref_ctr
  - kernel/events/uprobes.c:__replace_page
```
```
In kernel/padata.c (c00000000035d6f8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - kernel/padata.c:padata_replace
```
```
In kernel/jump_label.c (c00000000035eff8)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In mm/filemap.c (c000000000367524)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
```
```
In mm/oom_kill.c (c00000000036fa5c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (c000000000375dd4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (c000000000378080)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (c00000000037b54c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (c00000000037e860)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/truncate.c:pagecache_isize_extended
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:invalidate_mapping_pages
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (c000000000388510)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (c0000000003958c8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
  - mm/shmem.c:shmem_unused_huge_shrink
```
```
In mm/backing-dev.c (c00000000039e834)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_put
  - mm/backing-dev.c:cgwb_release_workfn
```
```
In mm/mmu_context.c (c00000000039f818)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (c0000000003b76b8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:undo_dev_pagemap
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:follow_pmd_mask
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (c0000000003c6db0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_numa_page
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:__do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:zap_pte_range
```
```
In mm/mincore.c (c0000000003c7c68)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (c0000000003c9908)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:munlock_vma_pages_range
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (c0000000003da2e8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (c0000000003e3178)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In mm/page_alloc.c (c0000000003e95e8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/page_alloc.c:page_frag_free
```
```
In mm/madvise.c (c0000000003f28e4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (c0000000003f4fa4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (c0000000003f7eac)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (c0000000003fe918)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (c000000000404054)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_pool_put
```
```
In mm/hugetlb.c (c0000000004109e0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_surplus_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (c0000000004142fc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
```
```
In mm/mmu_notifier.c (c0000000004186a4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (c00000000041c470)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:stable_tree_search
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:replace_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/memory_hotplug.c (c00000000042e2a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/migrate.c (c0000000004368c0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_finalize
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_setup
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_vma_collect_pmd
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_move
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/huge_memory.c (c00000000044425c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:deferred_split_scan
  - mm/huge_memory.c:split_huge_page_to_list
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:mm_put_huge_zero_page
```
```
In mm/khugepaged.c (c00000000044b18c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collect_mm_slot
  - mm/khugepaged.c:__khugepaged_exit
```
```
In mm/memcontrol.c (c000000000457024)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/memory-failure.c (c000000000461dd8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:me_huge_page
  - mm/memory-failure.c:delete_from_lru_cache
  - mm/memory-failure.c:kill_procs
```
```
In mm/zsmalloc.c (c0000000004686f4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (c00000000046aed0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (c00000000046c93c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (c00000000046d11c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In mm/memremap.c (c00000000046dc50)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - mm/memremap.c:memunmap_pages
  - mm/memremap.c:devmap_managed_enable_put
```
```
In fs/open.c (c000000000473f20)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (c0000000004772d4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/file_table.c (c00000000047b12c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (c00000000047cab0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (c000000000483b40)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/exec.c:would_dump
```
```
In fs/pipe.c (c00000000048796c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (c00000000048c838)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (c0000000004a1bd0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:dentry_free
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/inode.c (c0000000004a8690)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (c0000000004adad0)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/namespace.c (c0000000004b0080)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (c0000000004bf1b0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (c0000000004c5294)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/splice.c (c0000000004d17b4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (c0000000004d80f0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (c0000000004de974)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/buffer.c:drop_buffers
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (c0000000004e4fc4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (c0000000004eb31c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (c0000000004ed3f8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/proc_namespace.c (c0000000004ee268)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (c0000000004efa04)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_put_group
```
```
In fs/notify/mark.c (c0000000004f0450)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (c0000000004fdd20)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_ctx_put
```
```
In fs/userfaultfd.c (c0000000004fea78)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/aio.c (c000000000507530)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (c00000000050fd64)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_iopoll_getevents
  - fs/io_uring.c:io_put_req
```
```
In fs/crypto/keyring.c (c00000000051b2c4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (c00000000051bc6c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/verity/enable.c (c00000000051ec6c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (c0000000005211e8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (c00000000052fcd4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/compat_binfmt_elf.c (c0000000005338f4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (c000000000534368)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (c0000000005371b0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_all_cached_acls
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/coredump.c (c000000000538638)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (c00000000053ce68)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (c00000000053d9e0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (c00000000054bac0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/inode.c (c00000000054eee0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/proc/root.c (c0000000005506ac)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (c0000000005541a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:mem_release
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_pid_cmdline_read
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (c000000000559654)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/proc/array.c (c00000000055a4c8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (c00000000055cc34)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (c00000000055f620)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (c0000000005649fc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (c00000000056aa98)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/kernfs/file.c (c00000000056e630)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/sysfs/mount.c (c000000000571fb4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (c000000000573960)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (c000000000576114)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:put_fragment
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (c0000000005794a4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:create_link
  - fs/configfs/symlink.c:create_link
```
```
In fs/configfs/item.c (c000000000579c94)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
```
```
In fs/ext4/ialloc.c (c000000000596968)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (c00000000059e5fc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (c0000000005afda0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (c0000000005ba818)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (c0000000005c4f84)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (c0000000005d0c5c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (c0000000005d1ef8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (c0000000005f7880)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/ext4/xattr.c (c0000000005fc4c8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/acl.c (c0000000006004cc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
```
```
In fs/ext4/verity.c (c000000000600924)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (c00000000060337c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (c0000000006081a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (c000000000616e68)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (c000000000619e24)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (c00000000061d638)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (c00000000063713c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (c00000000063766c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (c0000000006476f8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
```
```
In fs/fuse/file.c (c000000000655294)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete
```
```
In fs/fuse/inode.c (c000000000659924)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/fuse/readdir.c (c00000000065ded0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_readdir_cached
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/inode.c (c00000000065edd4)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In fs/debugfs/file.c (c0000000006600a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - fs/debugfs/file.c:debugfs_file_put
```
```
In ipc/util.c (c000000000666aa4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (c00000000066fc6c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (c000000000677834)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (c000000000678db0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (c00000000067a4f8)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In security/keys/keyring.c (c00000000067ddec)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In security/keys/keyctl.c (c000000000681a00)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (c000000000683888)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (c0000000006843b4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (c000000000684e98)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In security/selinux/netlabel.c (c0000000006d1164)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (c0000000006d8868)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/tomoyo/common.c (c0000000006e9630)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (c0000000006edbe4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/apparmorfs.c (c0000000006fc580)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:put_multi_transaction
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/capability.c (c000000000701078)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (c0000000007019d0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lib.c (c000000000703900)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (c000000000703a00)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (c00000000070b194)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (c00000000070e418)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (c000000000711468)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (c0000000007116d4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (c000000000715650)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
```
```
In security/apparmor/resource.c (c000000000718790)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (c00000000071a7dc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (c00000000071b7a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (c00000000071de74)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_free_or_put_new
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
```
```
In security/apparmor/mount.c (c000000000723448)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (c000000000724184)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (c000000000726f64)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In security/yama/yama_lsm.c (c0000000007281d8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/yama/yama_lsm.c:__report_access
```
```
In crypto/api.c (c00000000073c76c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - crypto/api.c:crypto_has_alg
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_alloc_tfm
  - crypto/api.c:crypto_alloc_base
  - crypto/api.c:crypto_alg_mod_lookup
  - crypto/api.c:crypto_alg_lookup
  - crypto/api.c:crypto_larval_wait
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_larval_destroy
  - crypto/api.c:__crypto_alg_lookup
```
```
In crypto/algapi.c (c0000000007413b0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_skcipher_decrypt
  - crypto/algapi.c:crypto_stats_skcipher_encrypt
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (c00000000074f014)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/bio.c (c00000000076c6b8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (c000000000774e74)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In block/blk-flush.c (c00000000077b804)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (c00000000077d5a4)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In block/blk-mq.c (c000000000783368)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partition-generic.c (c0000000007967a4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (c0000000007996c8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (c00000000079a640)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (c00000000079acc4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (c00000000079bc8c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (c00000000079e910)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (c0000000007a072c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (c0000000007a0ed8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (c0000000007a12f0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (c0000000007a1740)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (c0000000007a1ab8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (c0000000007a1e70)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (c0000000007a334c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (c0000000007a3708)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/bsg.c (c0000000007a5f6c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/bsg-lib.c (c0000000007a6f94)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_put
```
```
In block/blk-cgroup.c (c0000000007ab960)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-wbt.c (c0000000007c0ed4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/refcount.c (c0000000007ddd8c)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In lib/cpu_rmap.c (c000000000816828)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - lib/cpu_rmap.c:cpu_rmap_put
```
```
In lib/sbitmap.c (c00000000081eb08)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (c000000000824914)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_put
```
```
In drivers/pci/pci.c (c000000000860f9c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (c0000000008a4b50)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In drivers/dma/dmaengine.c (c0000000008c9184)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d67f4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/reset/core.c (c0000000008ea9f4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_put_internal
```
```
In drivers/tty/tty_io.c (c0000000008efa9c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_driver_kref_put
  - drivers/tty/tty_io.c:tty_kref_put
```
```
In drivers/tty/tty_port.c (c0000000008fd944)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/tty/tty_ldsem.c (c000000000ee9568)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/serial/serial_core.c (c000000000924534)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_poll_put_char
  - drivers/tty/serial/serial_core.c:uart_poll_get_char
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (c00000000094e000)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (c000000000950cec)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
  - drivers/char/hw_random/core.c:drop_current_rng
```
```
In drivers/char/agp/generic.c (c000000000955cf0)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In drivers/connector/cn_queue.c (c000000000970a94)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In drivers/lightnvm/core.c (c000000000975d14)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
```
```
In drivers/base/core.c (c000000000977a38)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_drop_managed
```
```
In drivers/base/power/runtime.c (c00000000099ab9c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (c0000000009a4988)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/base/firmware_loader/main.c (c0000000009ac4c8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:free_fw_priv
```
```
In drivers/block/loop.c (c0000000009c6554)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (c0000000009e88d0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:mfd_cell_disable
```
```
In drivers/nvdimm/core.c (c0000000009fc45c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/bus.c (c0000000009fffbc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a0267c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (c000000000a1a4d4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_put
```
```
In drivers/dma-buf/dma-buf.c (c000000000a1d4c0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (c000000000a1f7e0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (c000000000a1fe70)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (c000000000a21274)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (c000000000a224e0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (c000000000a24204)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sync_timeline_put
```
```
In drivers/dma-buf/udmabuf.c (c000000000a253e4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (c000000000a29f40)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (c000000000a33238)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/scsi_scan.c (c000000000a36e88)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_target_reap
```
```
In drivers/scsi/sd.c (c000000000a46d5c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sr.c (c000000000a4d468)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (c000000000a510cc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io_usercontext
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (c000000000a5a2cc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_host_put
```
```
In drivers/net/tun.c (c000000000aa369c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (c000000000aa654c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/vfio/vfio.c (c000000000aae270)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_container_put
```
```
In drivers/vfio/vfio_iommu_spapr_tce.c (c000000000ab2ccc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_clear
  - drivers/vfio/vfio_iommu_spapr_tce.c:tce_iommu_release
```
```
In drivers/vfio/pci/vfio_pci_nvlink2.c (c000000000abe1b8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_nvlink2.c:vfio_pci_nvgpu_release
```
```
In drivers/usb/core/hub.c (c000000000ad3128)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (c000000000ad5148)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (c000000000ada190)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_free_urb
```
```
In drivers/usb/core/message.c (c000000000add214)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (c000000000ae477c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (c000000000ae564c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/usb/core/devio.c (c000000000aeb5c4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/media/cec/cec-notifier.c (c000000000ba5f30)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
```
In drivers/power/supply/power_supply_core.c (c000000000badbcc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (c000000000bd7360)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (c000000000be6ea4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (c000000000beac24)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-table.c (c000000000bf0f5c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/md/dm-io.c (c000000000bfbe34)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
```
In drivers/md/dm-kcopyd.c (c000000000bfcb74)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c08c30)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In drivers/opp/core.c (c000000000c0a724)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
```
In drivers/remoteproc/remoteproc_core.c (c000000000c5dd28)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_shutdown
  - drivers/remoteproc/remoteproc_core.c:rproc_resource_cleanup
```
```
In drivers/remoteproc/remoteproc_virtio.c (c000000000c6022c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_dev_release
```
```
In drivers/devfreq/devfreq.c (c000000000c63ae4)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In drivers/nvmem/core.c (c000000000c723c0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:nvmem_unregister
```
```
In net/core/sock.c (c000000000c833e0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sk_free
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (c000000000c85e7c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (c000000000c8a0b8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/datagram.c (c000000000c948f0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/datagram.c:__skb_free_datagram_locked
```
```
In net/core/net_namespace.c (c000000000c9a094)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:net_drop_ns
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (c000000000c9d384)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/dev.c (c000000000ca50c4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (c000000000cc15f4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (c000000000cc9884)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (c000000000cd5f54)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (c000000000ce2d90)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:sk_filter_release
```
```
In net/core/xdp.c (c000000000cf1480)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (c000000000cf83b0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (c000000000cf9d04)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/core/netpoll.c (c000000000cfd1a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (c000000000d01160)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/sock_map.c (c000000000d13154)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (c000000000d229c4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_item_put
```
```
In net/core/bpf_sk_storage.c (c000000000d2aa04)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (c000000000d31158)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (c000000000d3dfd4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_proto_put
```
```
In net/sched/act_api.c (c000000000d46248)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (c000000000d4be5c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/netfilter/nf_queue.c (c000000000d561fc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (c000000000d59598)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (c000000000d60248)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_putpeer
```
```
In net/ipv4/ip_input.c (c000000000d615a0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (c000000000d62bbc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (c000000000d65698)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (c000000000d6a3cc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (c000000000d6e714)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d71244)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_put
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72f14)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:reqsk_timer_handler
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (c000000000d7dc38)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (c000000000d85348)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (c000000000d8cd7c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_pace_kick
```
```
In net/ipv4/tcp_timer.c (c000000000d95b40)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9da24)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ea1c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (c000000000da4180)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/raw.c (c000000000da9f48)
Location: include/linux/atomic-fallback.h:512
Inline: True
```
```
In net/ipv4/udp.c (c000000000db158c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/arp.c (c000000000db6b5c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (c000000000dbc4e8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (c000000000dc59c8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
```
```
In net/ipv4/fib_semantics.c (c000000000dce3b4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/inet_fragment.c (c000000000dd8d54)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (c000000000ddd330)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (c000000000de2860)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv4/fib_rules.c (c000000000de5894)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (c000000000dedca8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/syncookies.c (c000000000df0a70)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (c000000000df3300)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (c000000000df52a8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (c000000000df6ec0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (c000000000e03a40)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (c000000000e07974)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (c000000000e0ef24)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10550)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (c000000000e16ba0)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (c000000000e1bdd8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (c000000000e1dc3c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_put
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (c000000000e20458)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (c000000000e259cc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (c000000000e32804)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/ipv6/route.c (c000000000e3c764)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (c000000000e4a57c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ipv6_sockglue.c (c000000000e4bf24)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (c000000000e4f6dc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (c000000000e54f0c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (c000000000e5b328)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (c000000000e63458)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (c000000000e67acc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6cabc)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
```
```
In net/ipv6/ip6_flowlabel.c (c000000000e73050)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (c000000000e797e4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7d868)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e440)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (c000000000e83204)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (c000000000e85de8)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_cache_entry_free
```
```
In net/packet/af_packet.c (c000000000e97e4c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (c000000000ea90e4)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (c000000000eb2108)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:put_cred
```
```
In net/xdp/xsk.c (c000000000ebf468)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (c000000000ec109c)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/dec_and_lock.c (c000000000ec3a94)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - lib/dec_and_lock.c:_atomic_dec_and_lock_irqsave
  - lib/dec_and_lock.c:_atomic_dec_and_lock
```
```
In lib/klist.c (c000000000ecadac)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (c000000000ecb860)
Location: include/linux/atomic-fallback.h:512
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In init/do_mounts.c (ffffffe000001528)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
```
In arch/riscv/kernel/perf_event.c (ffffffe0000b96f2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/riscv/kernel/perf_event.c:riscv_event_destroy
```
```
In kernel/fork.c (ffffffe0000c1b94)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:_do_fork
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:dup_mm
  - kernel/fork.c:dup_mm
  - kernel/fork.c:mm_access
  - kernel/fork.c:mm_access
  - kernel/fork.c:mmput_async_fn
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__put_task_struct
  - kernel/fork.c:__mmdrop
```
```
In kernel/exit.c (ffffffe0000c5320)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_consider_task
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:do_exit
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:mm_update_next_owner
  - kernel/exit.c:release_task
  - kernel/exit.c:delayed_put_task_struct
```
```
In kernel/ptrace.c (ffffffe0000cc320)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/ptrace.c:__ptrace_unlink
```
```
In kernel/signal.c (ffffffe0000cd54a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/signal.c:__sigqueue_alloc
```
```
In kernel/sys.c (ffffffe0000d44fe)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_prlimit64
```
```
In kernel/umh.c (ffffffe0000d5224)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec
```
```
In kernel/workqueue.c (ffffffe0000d7438)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/workqueue.c:flush_workqueue_prep_pwqs
  - kernel/workqueue.c:pwq_dec_nr_in_flight
  - kernel/workqueue.c:wq_worker_sleeping
```
```
In kernel/pid.c (ffffffe0000dc302)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/pid.c:put_pid
```
```
In kernel/kthread.c (ffffffe0000df3ae)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_stop
```
```
In kernel/nsproxy.c (ffffffe0000e04ba)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/nsproxy.c:switch_task_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:create_new_namespaces
```
```
In kernel/cred.c (ffffffe0000e1844)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:prepare_kernel_cred
  - kernel/cred.c:revert_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:commit_creds
  - kernel/cred.c:copy_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:exit_creds
  - kernel/cred.c:put_cred_rcu
  - kernel/cred.c:put_cred_rcu
```
```
In kernel/smpboot.c (ffffffe0000e3030)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/groups.c (ffffffe0000e4300)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:__se_sys_setgroups
  - kernel/groups.c:set_current_groups
```
```
In kernel/sched/core.c (ffffffe0000ebe8c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__se_sys_sched_setattr
  - kernel/sched/core.c:do_sched_setscheduler
  - kernel/sched/core.c:finish_task_switch
  - kernel/sched/core.c:wake_up_q
  - kernel/sched/core.c:wake_q_add_safe
```
```
In kernel/sched/rt.c (ffffffe0000f9278)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/rt.c:push_rt_task
  - kernel/sched/rt.c:push_rt_task
```
```
In kernel/sched/deadline.c (ffffffe0000fb4ae)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:dl_task_timer
  - kernel/sched/deadline.c:dl_change_utilization
```
```
In kernel/sched/topology.c (ffffffe000100460)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/topology.c:destroy_sched_domain
  - kernel/sched/topology.c:sched_put_rd
  - kernel/sched/topology.c:rq_attach_root
```
```
In kernel/sched/autogroup.c (ffffffe00010389a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/autogroup.c:proc_sched_autogroup_show_task
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
  - kernel/sched/autogroup.c:sched_autogroup_exit
  - kernel/sched/autogroup.c:sched_autogroup_create_attach
  - kernel/sched/autogroup.c:autogroup_move_group
```
```
In kernel/sched/psi.c (ffffffe00010a172)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_trigger_replace
```
```
In kernel/locking/mutex.c (ffffffe00010a57c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/locking/rtmutex.c (ffffffe00010ba90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/irq/manage.c (ffffffe000113e90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_set_affinity_notifier
  - kernel/irq/manage.c:irq_affinity_notify
  - kernel/irq/manage.c:irq_set_affinity_locked
```
```
In kernel/rcu/update.c (ffffffe00011e178)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
```
In kernel/rcu/srcutree.c (ffffffe00011f386)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier_cb
```
```
In kernel/rcu/tree.c (ffffffe000121336)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/kcmp.c (ffffffe000128aca)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
```
```
In kernel/time/posix-cpu-timers.c (ffffffe0001371e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timer_del
  - kernel/time/posix-cpu-timers.c:posix_cpu_clock_get
```
```
In kernel/futex.c (ffffffe00013e4d6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
  - kernel/futex.c:get_futex_key
```
```
In kernel/cgroup/cgroup.c (ffffffe0001518a4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_free
  - kernel/cgroup/cgroup.c:css_killed_work_fn
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_end
  - kernel/cgroup/cgroup.c:css_task_iter_next
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:css_task_iter_advance_css_set
  - kernel/cgroup/cgroup.c:cgroup_procs_write_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_prepare_dst
  - kernel/cgroup/cgroup.c:cgroup_migrate_finish
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/cgroup/namespace.c (ffffffe000152858)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_put
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:free_cgroup_ns
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000153c26)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
```
```
In kernel/utsname.c (ffffffe00015aef8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/utsname.c:utsns_install
  - kernel/utsname.c:utsns_put
  - kernel/utsname.c:free_uts_ns
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffe00015ba9c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/user_namespace.c:userns_install
  - kernel/user_namespace.c:userns_put
  - kernel/user_namespace.c:free_user_ns
  - kernel/user_namespace.c:unshare_userns
```
```
In kernel/pid_namespace.c (ffffffe00015ca24)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/pid_namespace.c:pidns_install
  - kernel/pid_namespace.c:pidns_put
  - kernel/pid_namespace.c:pidns_for_children_get
  - kernel/pid_namespace.c:delayed_free_pidns
```
```
In kernel/stop_machine.c (ffffffe00015d38c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:cpu_stop_queue_work
```
```
In kernel/audit.c (ffffffe000160354)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_send_reply_thread
  - kernel/audit.c:audit_send_list
  - kernel/audit.c:kauditd_thread
  - kernel/audit.c:auditd_conn_free
```
```
In kernel/audit_watch.c (ffffffe0001666f6)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/audit_tree.c (ffffffe0001691e6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_tag_tree
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_add_tree_rule
  - kernel/audit_tree.c:audit_put_tree
  - kernel/audit_tree.c:audit_trim_trees
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:prune_tree_chunks
  - kernel/audit_tree.c:free_chunk
```
```
In kernel/hung_task.c (ffffffe0001696dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
```
```
In kernel/seccomp.c (ffffffe00016c250)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_get_metadata
  - kernel/seccomp.c:seccomp_get_filter
  - kernel/seccomp.c:seccomp_notify_release
  - kernel/seccomp.c:seccomp_attach_filter
```
```
In kernel/relay.c (ffffffe00016d5dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/relay.c:relay_file_release
  - kernel/relay.c:relay_close_buf
  - kernel/relay.c:relay_destroy_buf
```
```
In kernel/taskstats.c (ffffffe00016e8b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/trace.c (ffffffe00017d070)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace.c:buffer_spd_release
  - kernel/trace/trace.c:buffer_pipe_buf_release
```
```
In kernel/trace/trace_sched_wakeup.c (ffffffe0001887b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/trace/trace_events.c (ffffffe00018fd90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffe00019752e)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe0001a0cd6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_release
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/syscall.c:bpf_prog_release
  - kernel/bpf/syscall.c:__bpf_prog_put_rcu
  - kernel/bpf/syscall.c:__bpf_map_inc_not_zero
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
```
In kernel/bpf/btf.c (ffffffe0001bb0ae)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_get_fd_by_id
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_release
```
```
In kernel/bpf/cpumap.c (ffffffe0001bcc66)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf6f8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_get_build_id_offset
```
```
In kernel/events/core.c (ffffffe0001d03cc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_free_task
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - kernel/events/core.c:__perf_event_overflow
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_mmap_close
  - kernel/events/core.c:ring_buffer_attach
  - kernel/events/core.c:perf_event_release_kernel
  - kernel/events/core.c:_free_event
  - kernel/events/core.c:perf_sched_delayed
```
```
In kernel/events/ring_buffer.c (ffffffe0001d0e5a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
```
In kernel/padata.c (ffffffe0001d28f2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
```
```
In mm/filemap.c (ffffffe0001d71ca)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_map_pages
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:find_get_pages_range_tag
  - mm/filemap.c:find_get_pages_contig
  - mm/filemap.c:find_get_pages_range
  - mm/filemap.c:find_get_entries
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:find_get_entry
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/filemap.c:replace_page_cache_page
  - mm/filemap.c:delete_from_page_cache_batch
```
```
In mm/oom_kill.c (ffffffe0001dbe9a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:exit_oom_victim
  - mm/oom_kill.c:oom_reaper
```
```
In mm/page-writeback.c (ffffffe0001dffec)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page-writeback.c:write_one_page
```
```
In mm/readahead.c (ffffffe0001e1622)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/readahead.c:read_pages
  - mm/readahead.c:read_cache_pages
```
```
In mm/swap.c (ffffffe0001e2ca2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
```
```
In mm/truncate.c (ffffffe0001e4bd0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:truncate_inode_pages_range
  - mm/truncate.c:truncate_inode_pages_range
```
```
In mm/vmscan.c (ffffffe0001ea318)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_pages
  - mm/vmscan.c:shrink_active_list
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:move_pages_to_lru
  - mm/vmscan.c:shrink_page_list
```
```
In mm/shmem.c (ffffffe0001f1404)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
  - mm/shmem.c:shmem_put_link
  - mm/shmem.c:shmem_symlink
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_file_read_iter
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_unuse
  - mm/shmem.c:shmem_unuse_inode
  - mm/shmem.c:shmem_undo_range
  - mm/shmem.c:shmem_undo_range
```
```
In mm/backing-dev.c (ffffffe0001f765e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - mm/backing-dev.c:wb_exit
  - mm/backing-dev.c:wb_init
```
```
In mm/mmu_context.c (ffffffe0001f77dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mmu_context.c:use_mm
```
```
In mm/gup.c (ffffffe00020539c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
```
```
In mm/memory.c (ffffffe00020b040)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory.c:__access_remote_vm
  - mm/memory.c:do_fault
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
```
```
In mm/mincore.c (ffffffe00020b93e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mincore.c:mincore_page
```
```
In mm/mlock.c (ffffffe00020c260)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
```
```
In mm/rmap.c (ffffffe000214330)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/rmap.c:__put_anon_vma
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_lock_anon_vma_read
  - mm/rmap.c:page_get_anon_vma
  - mm/rmap.c:unlink_anon_vmas
  - mm/rmap.c:anon_vma_fork
  - mm/rmap.c:__anon_vma_prepare
```
```
In mm/process_vm_access.c (ffffffe00021999c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021fd52)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page_alloc.c:free_contig_range
  - mm/page_alloc.c:free_reserved_area
  - mm/page_alloc.c:page_frag_free
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/madvise.c (ffffffe0002215b6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:swapin_walk_pmd_entry
```
```
In mm/page_io.c (ffffffe0002217f2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
```
```
In mm/swap_state.c (ffffffe00022336e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swap_state.c:swapin_readahead
  - mm/swap_state.c:swap_cluster_readahead
  - mm/swap_state.c:__read_swap_cache_async
  - mm/swap_state.c:free_page_and_swap_cache
```
```
In mm/swapfile.c (ffffffe000227a34)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:try_to_unuse
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:unuse_pte_range
  - mm/swapfile.c:__try_to_reclaim_swap
```
```
In mm/zswap.c (ffffffe00022ace8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:zswap_writeback_entry
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
```
In mm/hugetlb.c (ffffffe000232252)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_unshare
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_reserve_pages
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_vm_op_close
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mmu_notifier.c (ffffffe00023258c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/mmu_notifier.c:mmu_notifier_free_rcu
  - mm/mmu_notifier.c:mmu_notifier_unregister
```
```
In mm/ksm.c (ffffffe000234454)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/ksm.c:run_store
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:__stable_node_chain
  - mm/ksm.c:try_to_merge_one_page
  - mm/ksm.c:remove_stable_node
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:remove_rmap_item_from_tree
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:get_ksm_page
  - mm/ksm.c:remove_node_from_stable_tree
  - mm/ksm.c:break_cow
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffe00023fd4a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:isolate_movable_page
```
```
In mm/memcontrol.c (ffffffe00024686c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
```
In mm/zsmalloc.c (ffffffe00024e478)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
```
In mm/userfaultfd.c (ffffffe00024fd08)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/page_idle.c (ffffffe000250bbc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/page_idle.c:page_idle_bitmap_write
  - mm/page_idle.c:page_idle_bitmap_read
  - mm/page_idle.c:page_idle_get_page
```
```
In mm/frame_vector.c (ffffffe000251046)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/frame_vector.c:put_vaddr_frames
```
```
In fs/open.c (ffffffe000254112)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/open.c:do_faccessat
```
```
In fs/read_write.c (ffffffe000255d22)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:generic_remap_file_range_prep
  - fs/read_write.c:vfs_dedupe_get_page
```
```
In fs/file_table.c (ffffffe000257fd6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/file_table.c:file_free_rcu
```
```
In fs/super.c (ffffffe0002592dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/super.c:deactivate_locked_super
```
```
In fs/exec.c (ffffffe00025ed58)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
  - fs/exec.c:would_dump
  - fs/exec.c:copy_strings
  - fs/exec.c:copy_strings
```
```
In fs/pipe.c (ffffffe00025fa00)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/pipe.c:generic_pipe_buf_release
  - fs/pipe.c:anon_pipe_buf_release
```
```
In fs/namei.c (ffffffe00026216e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/namei.c:page_put_link
  - fs/namei.c:page_get_link
```
```
In fs/dcache.c (ffffffe00026daee)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:release_dentry_name_snapshot
```
```
In fs/inode.c (ffffffe000271c58)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/inode.c:__destroy_inode
  - fs/inode.c:__destroy_inode
```
```
In fs/file.c (ffffffe00027609e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/file.c:exit_files
  - fs/file.c:reset_files_struct
```
```
In fs/namespace.c (ffffffe00027ac92)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:free_mnt_ns
```
```
In fs/libfs.c (ffffffe00028104e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/fs-writeback.c (ffffffe000284236)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/splice.c (ffffffe00028b428)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/splice.c:iter_to_pipe
  - fs/splice.c:default_file_splice_read
  - fs/splice.c:page_cache_pipe_buf_release
```
```
In fs/fs_context.c (ffffffe00028f3b0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
  - fs/fs_context.c:put_fs_context
```
```
In fs/buffer.c (ffffffe000295188)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_truncate_page
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:block_write_begin
  - fs/buffer.c:__getblk_gfp
```
```
In fs/block_dev.c (ffffffe000296a42)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_write_end
  - fs/block_dev.c:blkdev_bio_end_io
```
```
In fs/direct-io.c (ffffffe00029ab22)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_blockdev_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:do_direct_IO
  - fs/direct-io.c:dio_complete
```
```
In fs/mpage.c (ffffffe00029c004)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/mpage.c:mpage_readpages
```
```
In fs/proc_namespace.c (ffffffe00029c8fc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/notify/group.c (ffffffe00029db7a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
```
In fs/notify/mark.c (ffffffe00029e644)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
```
In fs/eventfd.c (ffffffe0002a67f2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/eventfd.c:eventfd_release
```
```
In fs/userfaultfd.c (ffffffe0002a8fb6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/userfaultfd.c:__se_sys_userfaultfd
```
```
In fs/aio.c (ffffffe0002aa02c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
  - fs/aio.c:free_ioctx_reqs
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_migratepage
  - fs/aio.c:aio_free_ring
```
```
In fs/io_uring.c (ffffffe0002b0af6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_ring_ctx_wait_and_kill
  - fs/io_uring.c:io_mem_free
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:__io_submit_sqe
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_wake
  - fs/io_uring.c:io_poll_complete_work
  - fs/io_uring.c:io_send_recvmsg
  - fs/io_uring.c:io_complete_rw
  - fs/io_uring.c:io_iopoll_getevents
```
```
In fs/crypto/keyring.c (ffffffe0002b711e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/crypto/keyring.c:do_remove_key
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup.c (ffffffe0002b7776)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/crypto/keysetup.c:put_crypt_info
```
```
In fs/verity/enable.c (ffffffe0002b956a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/verity/enable.c:build_merkle_tree
```
```
In fs/verity/verify.c (ffffffe0002bb060)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
  - fs/verity/verify.c:verify_page
```
```
In fs/binfmt_elf.c (ffffffe0002c1970)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
```
```
In fs/mbcache.c (ffffffe0002c41de)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:__entry_find
```
```
In fs/posix_acl.c (ffffffe0002c5b00)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:simple_acl_create
  - fs/posix_acl.c:posix_acl_xattr_set
  - fs/posix_acl.c:posix_acl_xattr_get
  - fs/posix_acl.c:posix_acl_from_xattr
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_chmod
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__posix_acl_create
  - fs/posix_acl.c:__forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
```
In fs/coredump.c (ffffffe0002c66a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/iomap/buffered-io.c (ffffffe0002c934c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_dirty_actor
  - fs/iomap/buffered-io.c:iomap_write_end
  - fs/iomap/buffered-io.c:iomap_readpages
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_readpages_actor
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_page_release
```
```
In fs/iomap/direct-io.c (ffffffe0002c999a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_bio_end_io
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/proc/task_mmu.c (ffffffe0002d1c64)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_release
  - fs/proc/task_mmu.c:clear_refs_write
  - fs/proc/task_mmu.c:smaps_rollup_release
  - fs/proc/task_mmu.c:show_smaps_rollup
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:m_stop
```
```
In fs/proc/inode.c (ffffffe0002d3c22)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_put_link
  - fs/proc/inode.c:proc_reg_open
  - fs/proc/inode.c:proc_reg_get_unmapped_area
  - fs/proc/inode.c:proc_reg_mmap
  - fs/proc/inode.c:proc_reg_unlocked_ioctl
  - fs/proc/inode.c:proc_reg_poll
  - fs/proc/inode.c:proc_reg_write
  - fs/proc/inode.c:proc_reg_read
  - fs/proc/inode.c:proc_reg_llseek
```
```
In fs/proc/root.c (ffffffe0002d4ab8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/root.c:pid_ns_prepare_proc
  - fs/proc/root.c:proc_init_fs_context
```
```
In fs/proc/base.c (ffffffe0002d4e96)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_task_lookup
  - fs/proc/base.c:proc_tid_comm_permission
  - fs/proc/base.c:proc_pid_readdir
  - fs/proc/base.c:next_tgid
  - fs/proc/base.c:proc_pid_lookup
  - fs/proc/base.c:proc_setgroups_release
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:proc_id_map_release
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/base.c:proc_coredump_filter_write
  - fs/proc/base.c:proc_coredump_filter_read
  - fs/proc/base.c:proc_pid_attr_read
  - fs/proc/base.c:proc_pident_readdir
  - fs/proc/base.c:proc_pident_lookup
  - fs/proc/base.c:timerslack_ns_show
  - fs/proc/base.c:timerslack_ns_write
  - fs/proc/base.c:timers_stop
  - fs/proc/base.c:proc_map_files_readdir
  - fs/proc/base.c:proc_map_files_lookup
  - fs/proc/base.c:map_files_get_link
  - fs/proc/base.c:map_files_d_revalidate
  - fs/proc/base.c:pid_revalidate
  - fs/proc/base.c:proc_exe_link
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:comm_write
  - fs/proc/base.c:sched_autogroup_write
  - fs/proc/base.c:sched_autogroup_show
  - fs/proc/base.c:sched_write
  - fs/proc/base.c:sched_show
  - fs/proc/base.c:proc_sessionid_read
  - fs/proc/base.c:proc_loginuid_read
  - fs/proc/base.c:oom_score_adj_read
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:oom_adj_read
  - fs/proc/base.c:mem_release
  - fs/proc/base.c:proc_mem_open
  - fs/proc/base.c:proc_single_show
  - fs/proc/base.c:proc_pid_permission
  - fs/proc/base.c:proc_fd_access_allowed
  - fs/proc/base.c:proc_root_link
  - fs/proc/base.c:proc_cwd_link
```
```
In fs/proc/generic.c (ffffffe0002d9efc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_subtree
  - fs/proc/generic.c:remove_proc_entry
```
```
In fs/proc/array.c (ffffffe0002daff0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/array.c:task_state
```
```
In fs/proc/fd.c (ffffffe0002dcaa8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_readfd_common
  - fs/proc/fd.c:proc_lookupfd_common
  - fs/proc/fd.c:proc_fd_link
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:tid_fd_revalidate
  - fs/proc/fd.c:seq_show
```
```
In fs/proc/namespaces.c (ffffffe0002deb9e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/namespaces.c:proc_ns_dir_lookup
  - fs/proc/namespaces.c:proc_ns_dir_readdir
  - fs/proc/namespaces.c:proc_ns_readlink
  - fs/proc/namespaces.c:proc_ns_get_link
```
```
In fs/proc/proc_net.c (ffffffe0002e1efa)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_tgid_net_readdir
  - fs/proc/proc_net.c:proc_tgid_net_getattr
  - fs/proc/proc_net.c:proc_tgid_net_lookup
  - fs/proc/proc_net.c:single_release_net
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_open_net
```
```
In fs/kernfs/dir.c (ffffffe0002e4ec6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_dir_pos
  - fs/kernfs/dir.c:kernfs_dir_fop_release
  - fs/kernfs/dir.c:kernfs_rename_ns
  - fs/kernfs/dir.c:kernfs_remove_self
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rename
  - fs/kernfs/dir.c:kernfs_iop_rmdir
  - fs/kernfs/dir.c:kernfs_iop_mkdir
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_find_and_get_node_by_ino
```
```
In fs/kernfs/file.c (ffffffe0002e6baa)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/sysfs/mount.c (ffffffe0002e8d9c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffe0002e9cea)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_hash_and_remove
```
```
In fs/configfs/dir.c (ffffffe0002ec800)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_dir_close
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_remove_dirent
  - fs/configfs/dir.c:configfs_d_iput
  - fs/configfs/dir.c:configfs_d_iput
```
```
In fs/configfs/symlink.c (ffffffe0002ed7e0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
```
In fs/configfs/item.c (ffffffe0002ede5e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
```
In fs/ext4/ialloc.c (ffffffe0003007f2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inline.c (ffffffe000305850)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
  - fs/ext4/inline.c:ext4_convert_inline_data_to_extent
```
```
In fs/ext4/inode.c (ffffffe0003108c4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:__ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_end_io_dio
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:ext4_da_write_begin
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:__ext4_journalled_writepage
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
  - fs/ext4/inode.c:ext4_write_begin
```
```
In fs/ext4/mballoc.c (ffffffe0003170e2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_mb_release_context
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_process_freed_data
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
  - fs/ext4/mballoc.c:ext4_mb_init_group
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
```
In fs/ext4/move_extent.c (ffffffe00031df36)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
  - fs/ext4/move_extent.c:move_extent_per_page
```
```
In fs/ext4/page-io.c (ffffffe000324e52)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_end_bio
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
```
In fs/ext4/readpage.c (ffffffe000325e2e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
```
In fs/ext4/symlink.c (ffffffe00033c610)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/ext4/xattr.c (ffffffe00033f44e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_block_set
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_release_block
```
```
In fs/ext4/acl.c (ffffffe000341b58)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_init_acl
  - fs/ext4/acl.c:ext4_get_acl
```
```
In fs/ext4/verity.c (ffffffe000341e20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ext4/verity.c:pagecache_read
```
```
In fs/jbd2/transaction.c (ffffffe000343808)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/transaction.c:jbd2__journal_restart
```
```
In fs/jbd2/commit.c (ffffffe000346cdc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/squashfs/file.c (ffffffe00035094c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/squashfs/file.c:squashfs_copy_cache
```
```
In fs/squashfs/file_direct.c (ffffffe000352b32)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
```
In fs/hugetlbfs/inode.c (ffffffe000354d0e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:remove_inode_hugepages
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In fs/ecryptfs/mmap.c (ffffffe000365074)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
```
In fs/ecryptfs/read_write.c (ffffffe000365424)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/fuse/dev.c (ffffffe00036ff44)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_release
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_dev_splice_read
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_finish
  - fs/fuse/dev.c:fuse_get_req
```
```
In fs/fuse/file.c (ffffffe000378fa6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_begin
  - fs/fuse/file.c:fuse_writepages
  - fs/fuse/file.c:fuse_write_inode
  - fs/fuse/file.c:fuse_writepage_free
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_readpages_end
  - fs/fuse/file.c:fuse_aio_complete
  - fs/fuse/file.c:fuse_release_common
```
```
In fs/fuse/inode.c (ffffffe00037c0be)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/fuse/readdir.c (ffffffe00037ee88)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_readdir
  - fs/fuse/readdir.c:fuse_emit
```
```
In fs/debugfs/inode.c (ffffffe00037f998)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/debugfs/file.c (ffffffe0003817b6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/debugfs/file.c:read_file_blob
  - fs/debugfs/file.c:debugfs_write_file_bool
  - fs/debugfs/file.c:debugfs_read_file_bool
  - fs/debugfs/file.c:debugfs_attr_write
  - fs/debugfs/file.c:debugfs_attr_read
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:full_proxy_poll
  - fs/debugfs/file.c:full_proxy_unlocked_ioctl
  - fs/debugfs/file.c:full_proxy_write
  - fs/debugfs/file.c:full_proxy_read
  - fs/debugfs/file.c:full_proxy_llseek
  - fs/debugfs/file.c:open_proxy_open
```
```
In ipc/util.c (ffffffe0003850a2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/util.c:ipc_rcu_putref
```
```
In ipc/sem.c (ffffffe00038a154)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
```
```
In ipc/mqueue.c (ffffffe00038c526)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/mqueue.c:remove_notification
  - ipc/mqueue.c:__do_notify
  - ipc/mqueue.c:mq_create_mount
  - ipc/mqueue.c:mqueue_init_fs_context
```
```
In ipc/namespace.c (ffffffe00038ec3a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In security/keys/key.c (ffffffe000390afa)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
  - security/keys/key.c:key_create_or_update
```
```
In security/keys/keyring.c (ffffffe000391dae)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/keyring.c:key_remove_domain
```
```
In security/keys/keyctl.c (ffffffe000393f60)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/keys/process_keys.c (ffffffe00039521a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/process_keys.c:key_change_session_keyring
  - security/keys/process_keys.c:lookup_user_key
  - security/keys/process_keys.c:lookup_user_key
```
```
In security/keys/request_key.c (ffffffe0003958b6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/keys/request_key.c:call_sbin_request_key
```
```
In security/keys/request_key_auth.c (ffffffe000396018)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In security/selinux/netlabel.c (ffffffe0003c15c8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_setsockopt
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sk_security_free
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/smack/smack_lsm.c (ffffffe0003c5b56)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_inet_conn_request
  - security/smack/smack_lsm.c:smack_socket_getpeersec_dgram
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
```
In security/tomoyo/common.c (ffffffe0003cec3e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_close_control
```
```
In security/tomoyo/domain.c (ffffffe0003d0f20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d98a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:p_stop
  - security/apparmor/apparmorfs.c:p_start
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
  - security/apparmor/apparmorfs.c:create_profile_file
  - security/apparmor/apparmorfs.c:rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_release
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_name_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_level_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_ns_stacked_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_attach_show
  - security/apparmor/apparmorfs.c:seq_profile_mode_show
  - security/apparmor/apparmorfs.c:seq_profile_name_show
  - security/apparmor/apparmorfs.c:seq_profile_release
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:aa_write_access
  - security/apparmor/apparmorfs.c:multi_transaction_release
  - security/apparmor/apparmorfs.c:multi_transaction_read
  - security/apparmor/apparmorfs.c:ns_revision_open
  - security/apparmor/apparmorfs.c:ns_revision_release
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_remove
  - security/apparmor/apparmorfs.c:profile_replace
  - security/apparmor/apparmorfs.c:profile_load
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
  - security/apparmor/apparmorfs.c:policy_update
```
```
In security/apparmor/capability.c (ffffffe0003dc4d2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/capability.c:aa_capable
```
```
In security/apparmor/task.c (ffffffe0003dc9ce)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_hat
  - security/apparmor/task.c:aa_set_current_onexec
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lib.c (ffffffe0003dde56)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/lib.c:aa_policy_destroy
```
```
In security/apparmor/match.c (ffffffe0003ddeee)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/domain.c (ffffffe0003e2744)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:build_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:handle_onexec
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:profile_transition
  - security/apparmor/domain.c:find_attach
  - security/apparmor/domain.c:may_change_ptraced_domain
```
```
In security/apparmor/policy.c (ffffffe0003e477a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_remove_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:aa_replace_profiles
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:__replace_profile
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:policy_view_capable
  - security/apparmor/policy.c:aa_fqlookupn_profile
  - security/apparmor/policy.c:__list_remove_profile
  - security/apparmor/policy.c:__add_profile
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e64d0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
```
In security/apparmor/procattr.c (ffffffe0003e6780)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
  - security/apparmor/procattr.c:aa_getprocattr
```
```
In security/apparmor/lsm.c (ffffffe0003e9a6a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_getpeersec_stream
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_post_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_socket_create
  - security/apparmor/lsm.c:apparmor_unix_may_send
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_unix_stream_connect
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_sk_free_security
  - security/apparmor/lsm.c:apparmor_task_setrlimit
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_setprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_getprocattr
  - security/apparmor/lsm.c:apparmor_sb_pivotroot
  - security/apparmor/lsm.c:apparmor_sb_umount
  - security/apparmor/lsm.c:apparmor_sb_mount
  - security/apparmor/lsm.c:common_file_perm
  - security/apparmor/lsm.c:apparmor_file_free_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_alloc_security
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:common_perm
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_traceme
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_ptrace_access_check
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_task_free
  - security/apparmor/lsm.c:apparmor_cred_free
```
```
In security/apparmor/resource.c (ffffffe0003ea098)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffe0003eb482)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
  - security/apparmor/file.c:update_file_ctx
  - security/apparmor/file.c:update_file_ctx
```
```
In security/apparmor/policy_ns.c (ffffffe0003ebd4e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:__aa_remove_ns
```
```
In security/apparmor/label.c (ffffffe0003ed356)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:__labelset_update
  - security/apparmor/label.c:aa_label_strn_parse
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_printk
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_seq_print
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_label_audit
  - security/apparmor/label.c:aa_update_label_name
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_find_merge
  - security/apparmor/label.c:aa_label_replace
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:label_destroy
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:aa_vec_unique
  - security/apparmor/label.c:__proxy_share
  - security/apparmor/label.c:__aa_proxy_redirect
  - security/apparmor/label.c:free_proxy
```
```
In security/apparmor/mount.c (ffffffe0003f068e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
  - security/apparmor/mount.c:aa_pivotroot
```
```
In security/apparmor/net.c (ffffffe0003f0ecc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/net.c:aa_sk_perm
  - security/apparmor/net.c:aa_sk_perm
```
```
In security/apparmor/af_unix.c (ffffffe0003f2a50)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/apparmor/af_unix.c:aa_unix_file_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_opt_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_accept_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_listen_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_bind_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
  - security/apparmor/af_unix.c:aa_unix_sock_perm
```
```
In security/yama/yama_lsm.c (ffffffe0003f36a6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:yama_task_prctl
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:report_access
  - security/yama/yama_lsm.c:__report_access
  - security/yama/yama_lsm.c:__report_access
```
```
In crypto/api.c (ffffffe0003fd8be)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_kill
  - crypto/api.c:crypto_mod_put
```
```
In crypto/algapi.c (ffffffe0004006a4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - crypto/algapi.c:crypto_stats_rng_generate
  - crypto/algapi.c:crypto_stats_rng_seed
  - crypto/algapi.c:crypto_stats_kpp_compute_shared_secret
  - crypto/algapi.c:crypto_stats_kpp_generate_public_key
  - crypto/algapi.c:crypto_stats_kpp_set_secret
  - crypto/algapi.c:crypto_stats_ahash_final
  - crypto/algapi.c:crypto_stats_ahash_update
  - crypto/algapi.c:crypto_stats_decompress
  - crypto/algapi.c:crypto_stats_compress
  - crypto/algapi.c:crypto_stats_akcipher_verify
  - crypto/algapi.c:crypto_stats_akcipher_sign
  - crypto/algapi.c:crypto_stats_akcipher_decrypt
  - crypto/algapi.c:crypto_stats_akcipher_encrypt
  - crypto/algapi.c:crypto_stats_aead_decrypt
  - crypto/algapi.c:crypto_stats_aead_encrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_decrypt
  - crypto/algapi.c:crypto_stats_ablkcipher_encrypt
  - crypto/algapi.c:crypto_remove_final
```
```
In crypto/algboss.c (ffffffe000409a72)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/algboss.c:cryptomgr_probe
```
```
In block/bio.c (ffffffe00041f17c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_map_user_iov
  - block/bio.c:bio_iov_iter_get_pages
```
```
In block/blk-core.c (ffffffe000423d00)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-flush.c (ffffffe000427ed2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-ioc.c (ffffffe00042943e)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-mq.c (ffffffe00042ce52)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/partition-generic.c (ffffffe000438cf0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partition-generic.c:read_dev_sector
```
```
In block/partitions/amiga.c (ffffffe00043aa6e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
  - block/partitions/amiga.c:amiga_partition
```
```
In block/partitions/atari.c (ffffffe00043b8a6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
  - block/partitions/atari.c:atari_partition
```
```
In block/partitions/aix.c (ffffffe00043bcac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
  - block/partitions/aix.c:aix_partition
```
```
In block/partitions/mac.c (ffffffe00043c5d2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
  - block/partitions/mac.c:mac_partition
```
```
In block/partitions/ldm.c (ffffffe00043e6e4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_get_vblks
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/msdos.c (ffffffe00043f916)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:msdos_partition
  - block/partitions/msdos.c:parse_minix
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_unixware
  - block/partitions/msdos.c:parse_solaris_x86
  - block/partitions/msdos.c:parse_solaris_x86
```
```
In block/partitions/osf.c (ffffffe00043fdd6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/osf.c:osf_partition
  - block/partitions/osf.c:osf_partition
```
```
In block/partitions/sgi.c (ffffffe00043ffe6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sgi.c:sgi_partition
  - block/partitions/sgi.c:sgi_partition
```
```
In block/partitions/sun.c (ffffffe0004402ca)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sun.c:sun_partition
  - block/partitions/sun.c:sun_partition
```
```
In block/partitions/ultrix.c (ffffffe0004404d2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/ultrix.c:ultrix_partition
  - block/partitions/ultrix.c:ultrix_partition
```
```
In block/partitions/efi.c (ffffffe000440642)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/efi.c:read_lba
```
```
In block/partitions/karma.c (ffffffe000441b2c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/karma.c:karma_partition
  - block/partitions/karma.c:karma_partition
```
```
In block/partitions/sysv68.c (ffffffe000441ce4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
  - block/partitions/sysv68.c:sysv68_partition
```
```
In block/bsg.c (ffffffe00044320a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/bsg.c:bsg_release
```
```
In block/bsg-lib.c (ffffffe000443ca0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
```
```
In block/blk-cgroup.c (ffffffe0004469fe)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_offline
```
```
In block/blk-wbt.c (ffffffe0004534ea)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/refcount.c (ffffffe000464d2a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In lib/cpu_rmap.c (ffffffe00048f07a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_release
```
```
In lib/sbitmap.c (ffffffe00049427a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pinctrl/core.c (ffffffe000499450)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_release
```
```
In drivers/pci/pci.c (ffffffe0004bd466)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f4532)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_unregister_framebuffer
  - drivers/video/fbdev/core/fbmem.c:fb_release
  - drivers/video/fbdev/core/fbmem.c:fb_open
```
```
In drivers/clk/clk.c (ffffffe000510e5a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_put
  - drivers/clk/clk.c:clk_unregister
```
```
In drivers/dma/dmaengine.c (ffffffe000517398)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:dmaengine_unmap_put
  - drivers/dma/dmaengine.c:chan_dev_release
```
```
In drivers/virtio/virtio_balloon.c (ffffffe00051fdb6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/reset/core.c (ffffffe00052c57e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/reset/core.c:of_reset_control_array_get
```
```
In drivers/tty/tty_io.c (ffffffe00052deb6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_tty
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_vhangup_self
```
```
In drivers/tty/tty_port.c (ffffffe000536ebe)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/tty_port.c:tty_port_put
```
```
In drivers/tty/tty_ldsem.c (ffffffe0008c8efe)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/tty_ldsem.c:ldsem_down_read
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054c11e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_carrier_raised
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_get_icount
  - drivers/tty/serial/serial_core.c:uart_wait_modem_status
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_send_xchar
  - drivers/tty/serial/serial_core.c:uart_flush_buffer
  - drivers/tty/serial/serial_core.c:uart_chars_in_buffer
  - drivers/tty/serial/serial_core.c:uart_write_room
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_write
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_put_char
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_port_startup
  - drivers/tty/serial/serial_core.c:uart_start
  - drivers/tty/serial/serial_core.c:uart_stop
```
```
In drivers/char/virtio_console.c (ffffffe000566710)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
```
In drivers/char/hw_random/core.c (ffffffe000567a26)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:put_rng
```
```
In drivers/connector/cn_queue.c (ffffffe000573e00)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_del_callback
  - drivers/connector/cn_queue.c:cn_queue_add_callback
```
```
In drivers/lightnvm/core.c (ffffffe000577028)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_ctl_ioctl
  - drivers/lightnvm/core.c:nvm_unregister
  - drivers/lightnvm/core.c:nvm_unregister
```
```
In drivers/base/core.c (ffffffe00057aa28)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
```
In drivers/base/power/runtime.c (ffffffe00058c3b6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:__pm_runtime_idle
```
```
In drivers/base/power/domain.c (ffffffe00058d396)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/base/power/domain.c:genpd_sd_counter_dec
```
```
In drivers/base/firmware_loader/main.c (ffffffe0005919e2)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/block/loop.c (ffffffe00059ff60)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
  - drivers/block/loop.c:lo_rw_aio_do_completion
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3b56)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffe0005c0168)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nvdimm_map_put
```
```
In drivers/nvdimm/bus.c (ffffffe0005c29ac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nd_ioctl
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c42fa)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:put_ndd
```
```
In drivers/dax/bus.c (ffffffe0005d111a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
```
In drivers/dma-buf/dma-buf.c (ffffffe0005d2a56)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
  - drivers/dma-buf/dma-buf.c:dma_buf_poll
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d3d70)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_release
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_enable_signaling
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:dma_fence_array_cb_func
  - drivers/dma-buf/dma-fence-array.c:irq_dma_fence_array_work
```
```
In drivers/dma-buf/dma-fence-chain.c (ffffffe0005d4180)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_release
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_signaled
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_enable_signaling
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_cb
  - drivers/dma-buf/dma-fence-chain.c:dma_fence_chain_irq_work
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d551c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_test_signaled_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_wait_timeout_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences_rcu
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_copy_fences
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_excl_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_add_shared_fence
  - drivers/dma-buf/dma-resv.c:dma_resv_reserve_shared
  - drivers/dma-buf/dma-resv.c:dma_resv_fini
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5766)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_release
```
```
In drivers/dma-buf/sw_sync.c (ffffffe0005d6a50)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_ioctl
  - drivers/dma-buf/sw_sync.c:sw_sync_debugfs_release
  - drivers/dma-buf/sw_sync.c:timeline_fence_release
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d7414)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
  - drivers/dma-buf/udmabuf.c:release_udmabuf
```
```
In drivers/scsi/scsicam.c (ffffffe0005da24e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsi_bios_ptable
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e0442)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e2d48)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/scsi/sd.c (ffffffe0005eb86a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/scsi/sr.c (ffffffe0005f0e1a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_remove
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/scsi/sr.c:sr_block_check_events
  - drivers/scsi/sr.c:sr_block_open
  - drivers/scsi/sr.c:scsi_cd_put
```
```
In drivers/scsi/sg.c (ffffffe0005f31e6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_remove_sfp_usercontext
  - drivers/scsi/sg.c:sg_remove_device
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/scsi/sg.c:sg_rq_end_io_usercontext
  - drivers/scsi/sg.c:sg_release
  - drivers/scsi/sg.c:sg_open
```
```
In drivers/ata/libata-core.c (ffffffe0005f8898)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_devres_release
```
```
In drivers/net/tun.c (ffffffe00062b362)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
```
```
In drivers/net/ppp/ppp_generic.c (ffffffe00062bee0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_destroy_channel
  - drivers/net/ppp/ppp_generic.c:ppp_disconnect_channel
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_dev_priv_destructor
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
```
In drivers/usb/core/hub.c (ffffffe00063e6a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_activate
```
```
In drivers/usb/core/hcd.c (ffffffe00063fd8c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_put_hcd
```
```
In drivers/usb/core/urb.c (ffffffe000643bd2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_unlink_anchored_urbs
  - drivers/usb/core/urb.c:usb_poison_anchored_urbs
  - drivers/usb/core/urb.c:usb_kill_anchored_urbs
```
```
In drivers/usb/core/message.c (ffffffe000645318)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_release_interface
```
```
In drivers/usb/core/config.c (ffffffe00064a2b6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_destroy_configuration
```
```
In drivers/usb/core/file.c (ffffffe00064ac7a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/file.c:usb_deregister_dev
```
```
In drivers/usb/core/devio.c (ffffffe00064d81e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_release
  - drivers/usb/core/devio.c:async_completed
  - drivers/usb/core/devio.c:free_async
```
```
In drivers/media/cec/cec-notifier.c (ffffffe0006c41a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_put
```
```
In drivers/power/supply/power_supply_core.c (ffffffe0006c90cc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/md/md.c (ffffffe0006de208)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_wait_for_blocked_rdev
  - drivers/md/md.c:super_written
  - drivers/md/md.c:super_written
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:md_rdev_clear
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:submit_flushes
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_end_flush
  - drivers/md/md.c:md_handle_request
```
```
In drivers/md/md-bitmap.c (ffffffe0006eae18)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_endwrite
  - drivers/md/md-bitmap.c:end_bitmap_write
  - drivers/md/md-bitmap.c:write_page
```
```
In drivers/md/dm.c (ffffffe0006ed7d6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm.c:dec_pending
  - drivers/md/dm.c:dm_put_table_device
  - drivers/md/dm.c:dm_blk_close
```
```
In drivers/md/dm-table.c (ffffffe0006f1a7a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_put_device
```
```
In drivers/md/dm-io.c (ffffffe0006f8460)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:dispatch_io
  - drivers/md/dm-io.c:endio
```
```
In drivers/md/dm-kcopyd.c (ffffffe0006f8bea)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:segment_complete
  - drivers/md/dm-kcopyd.c:run_complete_job
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe000700a26)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/opp/core.c (ffffffe00070187e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_remove_all_dynamic
```
```
In drivers/devfreq/devfreq.c (ffffffe00072ee0c)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/nvmem/core.c (ffffffe000737290)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/nvmem/core.c:__nvmem_device_put
  - drivers/nvmem/core.c:devm_nvmem_release
```
```
In net/core/sock.c (ffffffe00073fcb2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sk_common_release
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sock_efree
  - net/core/sock.c:sk_free_unlock_clone
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:__sk_receive_skb
  - net/core/sock.c:__sk_receive_skb
```
```
In net/core/request_sock.c (ffffffe0007412b2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/request_sock.c:reqsk_fastopen_remove
  - net/core/request_sock.c:reqsk_fastopen_remove
```
```
In net/core/skbuff.c (ffffffe00074473e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/core/skbuff.c:skb_ext_put_sp
  - net/core/skbuff.c:skb_ext_add
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_scrub_packet
  - net/core/skbuff.c:skb_complete_wifi_ack
  - net/core/skbuff.c:skb_complete_tx_timestamp
  - net/core/skbuff.c:skb_clone_sk
  - net/core/skbuff.c:skb_shift
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:sock_spd_release
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:sock_zerocopy_callback
  - net/core/skbuff.c:consume_skb
  - net/core/skbuff.c:kfree_skb
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/datagram.c (ffffffe00074b1de)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074e182)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/net_namespace.c:netns_install
  - net/core/net_namespace.c:netns_put
  - net/core/net_namespace.c:rtnl_net_dumpid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_getid
  - net/core/net_namespace.c:rtnl_net_newid
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:cleanup_net
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:peernet2id_alloc
```
```
In net/core/flow_dissector.c (ffffffe00074fe7e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/flow_dissector.c:skb_flow_dissector_prog_query
```
```
In net/core/dev.c (ffffffe0007551ae)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dev.c:gro_pull_from_frag0
  - net/core/dev.c:__dev_kfree_skb_irq
```
```
In net/core/dst.c (ffffffe000766ebc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
  - net/core/dst.c:dst_destroy
```
```
In net/core/neighbour.c (ffffffe00076c1a0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_get
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_add
  - net/core/neighbour.c:neigh_delete
  - net/core/neighbour.c:neigh_rcu_free_parms
  - net/core/neighbour.c:__neigh_update
  - net/core/neighbour.c:neigh_timer_handler
  - net/core/neighbour.c:neigh_destroy
  - net/core/neighbour.c:___neigh_create
  - net/core/neighbour.c:neigh_cleanup_and_release
```
```
In net/core/rtnetlink.c (ffffffe0007732fa)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_getlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:__rtnl_newlink
  - net/core/rtnetlink.c:rtnl_dellink
  - net/core/rtnetlink.c:do_setlink
  - net/core/rtnetlink.c:rtnl_dump_ifinfo
  - net/core/rtnetlink.c:rtnl_get_net_ns_capable
```
```
In net/core/filter.c (ffffffe00077c63e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skc_lookup
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
  - net/core/filter.c:bpf_msg_pull_data
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
```
In net/core/xdp.c (ffffffe000785192)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_return
```
```
In net/core/page_pool.c (ffffffe000789bf6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:page_pool_release
  - net/core/page_pool.c:__page_pool_alloc_pages_slow
```
```
In net/core/skmsg.c (ffffffe00078adbc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_msg_verdict
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/core/skmsg.c:sk_msg_free_elem
```
```
In net/core/netpoll.c (ffffffe00078cea4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_cleanup
```
```
In net/core/fib_rules.c (ffffffe00078f340)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_nl_delrule
  - net/core/fib_rules.c:fib_rules_unregister
```
```
In net/core/sock_map.c (ffffffe000799d20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_unref
```
```
In net/core/devlink.c (ffffffe0007a3c9e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7b4a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
```
```
In net/sched/sch_generic.c (ffffffe0007a9608)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/sched/sch_generic.c:qdisc_put
```
```
In net/sched/cls_api.c (ffffffe0007b3f88)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tcf_chain_dump
  - net/sched/cls_api.c:tc_get_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_del_tfilter
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_chain_tp_delete_empty
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_block_playback_offloads
  - net/sched/cls_api.c:tcf_chain_flush
```
```
In net/sched/act_api.c (ffffffe0007b642c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/sched/act_api.c:tca_action_gd
```
```
In net/netlink/af_netlink.c (ffffffe0007b9e92)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:__netlink_dump_start
  - net/netlink/af_netlink.c:netlink_getsockopt
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_broadcast_filtered
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_unicast
  - net/netlink/af_netlink.c:netlink_detachskb
  - net/netlink/af_netlink.c:netlink_sendskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_attachskb
  - net/netlink/af_netlink.c:netlink_getname
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_bind
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/netfilter/nf_queue.c (ffffffe0007bfed6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/route.c (ffffffe0007c1f20)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_dst_destroy
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/inetpeer.c (ffffffe0007c6572)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inetpeer_invalidate_tree
```
```
In net/ipv4/ip_input.c (ffffffe0007c7108)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_protocol_deliver_rcu
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c7f5a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv4/ip_fragment.c:ip_expire
```
```
In net/ipv4/ip_output.c (ffffffe0007c9f90)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd308)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_destroy_rcu
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf704)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d190e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_purge
  - net/ipv4/inet_timewait_sock.c:inet_twsk_deschedule_put
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2d5c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_stop
  - net/ipv4/inet_connection_sock.c:inet_csk_complete_hashdance
  - net/ipv4/inet_connection_sock.c:inet_csk_prepare_forced_close
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop_and_put
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
  - net/ipv4/inet_connection_sock.c:inet_csk_accept
```
```
In net/ipv4/tcp.c (ffffffe0007d9392)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp.c:tcp_close
```
```
In net/ipv4/tcp_input.c (ffffffe0007de402)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3a1c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__pskb_trim_head
  - net/ipv4/tcp_output.c:tcp_pace_kick
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9bae)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_compressed_ack_kick
  - net/ipv4/tcp_timer.c:tcp_keepalive_timer
  - net/ipv4/tcp_timer.c:tcp_write_timer
  - net/ipv4/tcp_timer.c:tcp_delack_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ef028)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
  - net/ipv4/tcp_ipv4.c:tcp_req_err
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efc7a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_child_process
```
```
In net/ipv4/tcp_fastopen.c (ffffffe0007f323c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
  - net/ipv4/tcp_fastopen.c:tcp_try_fastopen
```
```
In net/ipv4/raw.c (ffffffe0007f699c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_rcv
```
```
In net/ipv4/udp.c (ffffffe0007fb866)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:__udp4_lib_rcv
  - net/ipv4/udp.c:udp_queue_rcv_one_skb
  - net/ipv4/udp.c:skb_consume_udp
```
```
In net/ipv4/arp.c (ffffffe0007ff270)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_ioctl
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffe000802eac)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_dump_ifaddr
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffe000807038)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
```
```
In net/ipv4/fib_semantics.c (ffffffe00080dafc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_detect_death
  - net/ipv4/fib_semantics.c:fib_release_info
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:free_fib_info_rcu
  - net/ipv4/fib_semantics.c:fib_nh_common_release
```
```
In net/ipv4/inet_fragment.c (ffffffe0008146d8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_work_fn
  - net/ipv4/inet_fragment.c:inet_frags_fini
```
```
In net/ipv4/ping.c (ffffffe000817386)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_rcv
  - net/ipv4/ping.c:ping_err
  - net/ipv4/ping.c:ping_init_sock
  - net/ipv4/ping.c:ping_unhash
```
```
In net/ipv4/nexthop.c (ffffffe00081a99c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/nexthop.c:remove_nexthop
```
```
In net/ipv4/fib_rules.c (ffffffe00081c834)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_suppress
```
```
In net/ipv4/ipmr.c (ffffffe000821c8c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ip_mr_input
  - net/ipv4/ipmr.c:ipmr_queue_xmit
  - net/ipv4/ipmr.c:mroute_clean_tables
```
```
In net/ipv4/syncookies.c (ffffffe0008238b8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_v4_check
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
  - net/ipv4/syncookies.c:tcp_get_cookie_sock
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824d42)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
  - net/ipv4/tcp_bpf.c:__tcp_bpf_recvmsg
```
```
In net/ipv4/cipso_ipv4.c (ffffffe0008266dc)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_putdef
  - net/ipv4/cipso_ipv4.c:cipso_v4_doi_remove
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_entry_free
```
```
In net/ipv4/xfrm4_policy.c (ffffffe0008279a2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffe000830092)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xdst_queue_output
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:__xfrm_sk_clone_policy
  - net/xfrm/xfrm_policy.c:xfrm_policy_requeue
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_kill
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
  - net/xfrm/xfrm_policy.c:xfrm_policy_timer
```
```
In net/xfrm/xfrm_state.c (ffffffe000831fc4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_user_policy
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:___xfrm_state_destroy
```
```
In net/xfrm/xfrm_input.c (ffffffe000838a92)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839b76)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/unix/af_unix.c (ffffffe00083cfd0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_shutdown
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_getname
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_find_other
  - net/unix/af_unix.c:init_peercred
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/af_inet6.c (ffffffe00084144e)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_destroy_sock
```
```
In net/ipv6/anycast.c (ffffffe000842d54)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
  - net/ipv6/anycast.c:aca_free_rcu
```
```
In net/ipv6/ip6_output.c (ffffffe00084427c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
```
In net/ipv6/ip6_input.c (ffffffe000847df0)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/addrconf.c (ffffffe0008504a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_rtm_getaddr
  - net/ipv6/addrconf.c:inet6_dump_addr
  - net/ipv6/addrconf.c:inet6_rtm_newaddr
  - net/ipv6/addrconf.c:modify_prefix_route
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_add_linklocal
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_failure
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_create_tempaddr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
  - net/ipv6/addrconf.c:cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:ipv6_add_addr
  - net/ipv6/addrconf.c:inet6_ifa_finish_destroy
  - net/ipv6/addrconf.c:inet6_netconf_get_devconf
  - net/ipv6/addrconf.c:addrconf_mod_dad_work
```
```
In net/ipv6/route.c (ffffffe00085462c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_dev_notify
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:rt6_disable_ip
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:ip6_route_del
  - net/ipv6/route.c:__ip6_del_rt
  - net/ipv6/route.c:ip6_route_add
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:fib6_nh_init
  - net/ipv6/route.c:icmp6_dst_alloc
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_pol_route
  - net/ipv6/route.c:ip6_rt_cache_alloc
  - net/ipv6/route.c:ip6_create_rt_rcu
  - net/ipv6/route.c:rt6_route_rcv
  - net/ipv6/route.c:ip6_dst_ifdown
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
  - net/ipv6/route.c:ip6_dst_destroy
```
```
In net/ipv6/ip6_fib.c (ffffffe00085fc02)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
  - net/ipv6/ip6_fib.c:fib6_info_destroy_rcu
```
```
In net/ipv6/ipv6_sockglue.c (ffffffe0008608e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/ndisc.c (ffffffe0008627b6)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_ifinfo_sysctl_change
  - net/ipv6/ndisc.c:ndisc_netdev_event
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_router_discovery
  - net/ipv6/ndisc.c:ndisc_recv_rs
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_na
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_recv_ns
  - net/ipv6/ndisc.c:ndisc_send_unsol_na
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_constructor
```
```
In net/ipv6/udp.c (ffffffe000865f6a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/udp.c:udpv6_sendmsg
  - net/ipv6/udp.c:__udp6_lib_rcv
  - net/ipv6/udp.c:__udp6_lib_rcv
```
```
In net/ipv6/raw.c (ffffffe00086aa94)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/mcast.c (ffffffe00087207c)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ipv6_mc_destroy_dev
  - net/ipv6/mcast.c:igmp6_timer_handler
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_gq_timer_expire
  - net/ipv6/mcast.c:mld_dad_timer_expire
  - net/ipv6/mcast.c:__ipv6_dev_mc_dec
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:mld_clear_delrec
  - net/ipv6/mcast.c:mld_del_delrec
```
```
In net/ipv6/reassembly.c (ffffffe000872ea4)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_expire
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000876660)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_err
  - net/ipv6/tcp_ipv6.c:reqsk_free
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087acb8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:fl_release
```
```
In net/ipv6/ip6mr.c (ffffffe00087f692)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:mroute_clean_tables
  - net/ipv6/ip6mr.c:ip6mr_mfc_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881d68)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffe000882528)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
```
In net/ipv6/syncookies.c (ffffffe000885794)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/syncookies.c:cookie_v6_check
```
```
In net/ipv6/calipso.c (ffffffe00088638a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_req_delattr
  - net/ipv6/calipso.c:calipso_req_setattr
  - net/ipv6/calipso.c:calipso_sock_delattr
  - net/ipv6/calipso.c:calipso_sock_setattr
  - net/ipv6/calipso.c:calipso_sock_getattr
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_opt_update
  - net/ipv6/calipso.c:calipso_doi_remove
  - net/ipv6/calipso.c:calipso_cache_entry_free
```
```
In net/packet/af_packet.c (ffffffe000892558)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_spkt
```
```
In net/rfkill/core.c (ffffffe00089e128)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In net/dns_resolver/dns_key.c (ffffffe0000a2d08)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:exit_dns_resolver
  - net/dns_resolver/dns_key.c:init_dns_resolver
```
```
In net/xdp/xsk.c (ffffffe0008ac334)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad6e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_put_umem
```
```
In lib/dec_and_lock.c (ffffffe0008aebfe)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In lib/klist.c (ffffffe0008b35ba)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/klist.c:klist_next
  - lib/klist.c:klist_prev
  - lib/klist.c:klist_put
```
```
In lib/kobject.c (ffffffe0008b40ce)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/kobject.c:kobject_put
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
In arch/x86/events/intel/uncore.c (ffffffff810171e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811b2d02)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bb67f)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/oom_kill.c (ffffffff81222d73)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff812a4b53)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812cc8e5)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/io_uring.c (ffffffff8133b636)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff81369dd5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8137c9ba)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-core.c (ffffffff814dcb55)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-wbt.c (ffffffff81511bf5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81554447)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff815772d2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81647743)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166adb3)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff816f12e2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff81701f0a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8172915d)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81734502)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/nvme/host/pci.c (ffffffff81750486)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_timeout
```
```
In drivers/power/supply/power_supply_core.c (ffffffff818282c5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81861455)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff8189a23a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff818a8465)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/dst.c (ffffffff818e102a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff819408bb)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81a3ac79)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/intel/uncore.c (ffffffff81016618)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811a5b02)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ae45f)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/oom_kill.c (ffffffff81215f23)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff81296623)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812bd755)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/io_uring.c (ffffffff8132c316)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff8135a865)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8136d48a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-core.c (ffffffff814cd505)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-wbt.c (ffffffff81501f15)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff815446c7)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81565a32)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81627ba3)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81649f23)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff816cb3e2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff816d5d1a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8170258d)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff817161a2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/nvme/host/pci.c (ffffffff81730326)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_timeout
```
```
In drivers/power/supply/power_supply_core.c (ffffffff817ef955)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828a05)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff8185770a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff81862e75)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/dst.c (ffffffff8189ae6a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff818fa3ab)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff819f7899)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/intel/uncore.c (ffffffff810171a8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811b0ad2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b944f)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/oom_kill.c (ffffffff81220b13)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff812a2963)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812ca6f5)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/io_uring.c (ffffffff81339106)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff813678a5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8137a48a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-core.c (ffffffff814d8be5)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-wbt.c (ffffffff8150dc85)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81550187)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81576b02)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81675b03)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff81699193)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff8171e9c2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8173732a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767f2d)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff81774c92)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81875205)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0a85)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff818e992a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff818f9ac5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/dst.c (ffffffff8193205a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff81991a4b)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81aa6b29)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
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
In arch/x86/events/intel/uncore.c (ffffffff810173e8)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
```
```
In kernel/trace/trace_events.c (ffffffff811beb62)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c74ef)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122fcb3)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/memory_hotplug.c (ffffffff812b2bf3)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - mm/memory_hotplug.c:put_page_bootmem
```
```
In mm/memremap.c (ffffffff812db3f5)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In fs/io_uring.c (ffffffff8134b95d)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_sq_wq_submit_work
```
```
In fs/proc/inode.c (ffffffff8137aef5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - fs/proc/inode.c:unuse_pde
```
```
In fs/kernfs/dir.c (ffffffff8138df7a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-core.c (ffffffff814f17f5)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In block/blk-wbt.c (ffffffff815272a5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In lib/sbitmap.c (ffffffff81569fc7)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - lib/sbitmap.c:__sbq_wake_up
```
```
In drivers/pci/pci.c (ffffffff81590fe2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81690163)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b3853)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
```
In drivers/block/loop.c (ffffffff81739df2)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_release
```
```
In drivers/mfd/mfd-core.c (ffffffff8175276a)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178366a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
```
```
In drivers/scsi/sd.c (ffffffff8178ea72)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81890ba5)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818ccd15)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff8190a9aa)
Location: include/linux/atomic-fallback.h:453
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff8191ac25)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_release_device
```
```
In net/core/dst.c (ffffffff8195372a)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/core/dst.c:dst_release_immediate
  - net/core/dst.c:dst_release
```
```
In net/netlink/af_netlink.c (ffffffff819b453b)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff81ab2ec9)
Location: include/linux/atomic-fallback.h:453
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
</details>
</li>
</ul>

## Differences
