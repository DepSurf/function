# Function: <code>raw_atomic_dec_return</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff812a616e)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812aee0a)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff81397763)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff814a7833)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/mbcache.c (ffffffff8154c646)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff81568c85)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
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
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81608b00)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
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
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
```
```
In block/blk-wbt.c (ffffffff817b9c65)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff817dba0d)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In drivers/pci/pci.c (ffffffff81924f82)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81a916c2)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abe6d3)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd57e4)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81be519c)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81d3f745)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e5d8)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81dec36d)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/netlink/af_netlink.c (ffffffff81ec786a)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff820560f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff8209c5b5)
Location: include/linux/atomic/atomic-arch-fallback.h:1218
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
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_box_unref
  - arch/x86/events/intel/uncore.c:uncore_pci_pmu_unregister
```
```
In kernel/trace/trace_events.c (ffffffff812c1c8e)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:__ftrace_event_enable_disable
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cb32a)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:clear_event_triggers
```
```
In mm/oom_kill.c (ffffffff813c1593)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - mm/oom_kill.c:exit_oom_victim
```
```
In mm/bootmem_info.c (ffffffff814d8863)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - mm/bootmem_info.c:put_page_bootmem
```
```
In fs/open.c (ffffffff814d98ca)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2abf)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/mbcache.c (ffffffff81582476)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
```
In fs/proc/inode.c (ffffffff815a12a5)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
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
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
```
```
In fs/ext4/xattr.c (ffffffff81641840)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
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
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
```
```
In block/blk-wbt.c (ffffffff817fe3d5)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_rqw_done
```
```
In io_uring/sqpoll.c (ffffffff8181fd8d)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_thread_unpark
```
```
In drivers/pci/pci.c (ffffffff8196d652)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_disable_device
```
```
In drivers/reset/core.c (ffffffff81ae4032)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/reset/core.c:reset_control_assert
  - drivers/reset/core.c:reset_control_rearm
  - drivers/reset/core.c:reset_control_rearm
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b11453)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:serial_core_remove_one_port
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a438)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_get_budget
  - drivers/scsi/scsi_lib.c:scsi_target_queue_ready
```
```
In drivers/scsi/sd.c (ffffffff81c3a2fc)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_release
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df60f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:power_supply_unregister
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45ee8)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_remove_sysfs
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea26bd)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_resume_device
```
```
In net/netlink/af_netlink.c (ffffffff81f8abcc)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_skb_destructor
```
```
In net/rfkill/core.c (ffffffff82128975)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_release
```
```
In arch/x86/pci/common.c (ffffffff82173d95)
Location: include/linux/atomic/atomic-arch-fallback.h:1227
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
