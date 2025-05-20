# Function: <code>isdigit</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002616)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - init/do_mounts.c:name_to_dev_t
  - init/do_mounts.c:name_to_dev_t
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81fce446)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff81fd8de3)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff8108fec0)
Location: include/linux/ctype.h:25
Inline: True
```
```
In kernel/sysctl_binary.c (ffffffff81091732)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
```
```
In kernel/sys.c (ffffffff8109b89b)
Location: include/linux/ctype.h:25
Inline: True
```
```
In kernel/reboot.c (ffffffff81fe1587)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff810db0fc)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:25
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81147db9)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff81176671)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_enum_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117c23b)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff81182459)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81186d5d)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In kernel/trace/trace_uprobe.c (ffffffff81189c15)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In mm/shmem.c (ffffffff811cee29)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff81213bbc)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff8133d20a)
Location: include/linux/ctype.h:25
Inline: True
```
```
In security/tomoyo/util.c (ffffffff813c0804)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff813e902a)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff813fb0fd)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff8142cd1a)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff8142e969)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/vsprintf.c (ffffffff81457f2b)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
```
```
In lib/parser.c (ffffffff8145c0eb)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In lib/bitmap.c (ffffffff8145db84)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In lib/swiotlb.c (ffffffff82006a47)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/swiotlb.c:setup_io_tlb_npages
```
```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8151bf0d)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
```
In drivers/md/md.c (ffffffff81729dcc)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - drivers/md/md.c:strict_strtoul_scaled
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
In init/do_mounts.c (ffffffff81002476)
Location: include/linux/ctype.h:25
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff820aedff)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff820b9c4d)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff8108cf67)
Location: include/linux/ctype.h:25
Inline: True
```
```
In kernel/sysctl_binary.c (ffffffff8108e8d8)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
```
```
In kernel/sys.c (ffffffff810986ab)
Location: include/linux/ctype.h:25
Inline: True
```
```
In kernel/reboot.c (ffffffff820c2404)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff810da20c)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:25
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81149b69)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff81179481)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8117eefa)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff81185392)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811899ea)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In kernel/trace/trace_uprobe.c (ffffffff8118c7d4)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In mm/shmem.c (ffffffff811d7b60)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff8121ed41)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff81352237)
Location: include/linux/ctype.h:25
Inline: True
```
```
In security/tomoyo/util.c (ffffffff813d70ad)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff813f5438)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff81407bed)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff8143a02e)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:disk_name
```
```
In block/partitions/check.c (ffffffff8143bc79)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff814615bb)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In lib/bitmap.c (ffffffff81462ad4)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In lib/swiotlb.c (ffffffff820e7a7e)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/swiotlb.c:setup_io_tlb_npages
```
```
In drivers/acpi/acpica/utstrtoul64.c (ffffffff8152c724)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64
```
```
In drivers/tty/tty_io.c (ffffffff81571af5)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff8173f859)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8175ffcc)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff818f9894)
Location: include/linux/ctype.h:25
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff810024a6)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826b5698)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826c05fc)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff81093c37)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sysctl_binary.c (ffffffff8109576e)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
```
```
In kernel/sys.c (ffffffff8109f38b)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff826ca522)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff810e23ce)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811563e9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff81186bd9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8118c7ba)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff81193080)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81197670)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In kernel/trace/trace_uprobe.c (ffffffff8119a294)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In mm/shmem.c (ffffffff811ec9cf)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff81239f61)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff81376aba)
Location: include/linux/ctype.h:26
Inline: True
```
```
In security/tomoyo/util.c (ffffffff813fd5e3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff8141d6f8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff8143054d)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff8146604e)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
  - block/partition-generic.c:disk_name
```
```
In block/partitions/check.c (ffffffff81467c89)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff8148d4ab)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In lib/bitmap.c (ffffffff8148e9ce)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In lib/swiotlb.c (ffffffff826f07ee)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/swiotlb.c:setup_io_tlb_npages
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81586fbf)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff815d6065)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff817b1879)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff817d205c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81980504)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81002bc9)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff826df6f2)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff826ea827)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff81097693)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffff810a589b)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff826f476e)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff810ea7b6)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (ffffffff826f676b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_setup
```
```
In kernel/dma/swiotlb.c (ffffffff826f7e3c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81164f29)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff81195c5a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff81198e57)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_trigger.c (ffffffff8119b67d)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811a83c9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811ad070)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
```
```
In kernel/trace/trace_uprobe.c (ffffffff811af94f)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
```
In mm/shmem.c (ffffffff8120dfbf)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff8125d68b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5271)
Location: include/linux/ctype.h:26
Inline: True
```
```
In security/tomoyo/util.c (ffffffff8142e673)
Location: include/linux/ctype.h:26
Inline: True
```
```
In security/device_cgroup.c (ffffffff8144f9b8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff81462ea2)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff81499a14)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff8149bb07)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff814c2201)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In lib/bitmap.c (ffffffff814c37b3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150c88d)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815be168)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff8160f08b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff817f98bc)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181ae15)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff819dc227)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81002c4d)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828956a5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a14d0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff8109f9b3)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffff810ae59b)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff828ab5ba)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff810f5de6)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (ffffffff828ad6a5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_setup
```
```
In kernel/dma/swiotlb.c (ffffffff828aed83)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81171c39)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811a3dca)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff811a6f95)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811a987d)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b53a1)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811bbb27)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bdddf)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff81220b5f)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff81271f23)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff813be035)
Location: include/linux/ctype.h:26
Inline: True
```
```
In security/tomoyo/util.c (ffffffff8144b188)
Location: include/linux/ctype.h:26
Inline: True
```
```
In security/device_cgroup.c (ffffffff8146c998)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff81480b23)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff814b3c90)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff814b5e1c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff814d6901)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In lib/bitmap.c (ffffffff814d7be3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/bitmap.c:__bitmap_parselist
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81521eed)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815d75b3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff8162c03b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff8182588c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81846605)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81a14697)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81002d6f)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828ad242)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828b9759)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff810a40a0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffff810b2f87)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff828c3d9d)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff810fe379)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (ffffffff828c6063)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_setup
```
```
In kernel/dma/swiotlb.c (ffffffff828c7869)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8117ea19)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811b1c95)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b4def)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b77f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c4159)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811cb48d)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ccd2b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff81230309)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff8128d54e)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff813e8b0a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffff81478ac8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff8149a098)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff814aec43)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff814e2210)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff814e4377)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff81502741)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8155040b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff81608faf)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff8165ffb5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff81867d42)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818893a5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81a83f99)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81002d5f)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b0586)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828bfc47)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff810aa680)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffff810b9577)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff828cc374)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff8110a87a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff828cfe48)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118a899)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811bd315)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c043b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c2e60)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d0079)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811d7394)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d92eb)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff8123e1d8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff8129d1fe)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff81402baa)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffff814927e4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff814b4298)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff814c98d3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff814fb5d0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff814fd737)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff815206e1)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815718bb)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8162a450)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff81682605)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff81899ad2)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb355)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81abb209)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81003fc0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82cd56d3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff82ce40f6)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff810b2004)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffff810c0b49)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff82cee351)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff81115422)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff82cf117f)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119f3b9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811d3530)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:update_event_printk
```
```
In kernel/trace/trace_events_filter.c (ffffffff811da1ba)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811dc720)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_events_inject.c (ffffffff811dd415)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_inject.c:parse_field
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ede49)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811f3cbf)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5fba)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff8126b518)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff812d0dde)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff81450683)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffff814e9dcf)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff81513779)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
  - security/device_cgroup.c:devcgroup_update_access
```
```
In crypto/algboss.c (ffffffff81528c7e)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In block/genhd.c (ffffffff815596b5)
Location: include/linux/ctype.h:26
Inline: True
```
```
In block/partitions/core.c (ffffffff8155d544)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/core.c:add_partition
  - block/partitions/core.c:check_partition
```
```
In lib/parser.c (ffffffff81583886)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_one
```
```
In lib/vsprintf.c (ffffffff815f6ce7)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81615ccb)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816d6c29)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff81733ad5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff819690af)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198bbe5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In init/do_mounts.c (ffff800010085434)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sysctl.c (ffff800010102930)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffff80001011695c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_newuname
```
```
In kernel/reboot.c (ffff800011443c90)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffff800011447a44)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010201cd8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffff80001023c628)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffff80001023fb30)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffff800010242750)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffff80001025093c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffff800010257670)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffff800010258d14)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffff8000102cfdb8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffff80001033c108)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffff8000104e13b4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffff800010587700)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffff8000105ac21c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffff8000105c56e8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffff8000105fd584)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffff8000105ff288)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffff800010629be4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c8fa8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffff80001079eb60)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffff80001084e720)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffff800010aeb9d8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffff800010b13ab4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In drivers/of/base.c (ffff800010b6c0e4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
```
```
In drivers/perf/arm-ccn.c (ffff800010b92394)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_get_cmp_mask
```
```
In lib/vsprintf.c (ffff800010d98050)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (c0303bd8)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sysctl.c (c035ebbc)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (c036b0f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_newuname
```
```
In kernel/reboot.c (c151db84)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (c03bd018)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (c15204f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_setup
```
```
In kernel/debug/kdb/kdb_main.c (c0440cf0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (c0477f5c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (c047b440)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (c047e090)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (c048403c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (c048a824)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (c048c7ac)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (c04fa09c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In security/tomoyo/util.c (c0738ce8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (c075bcb8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (c0772524)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (c07a845c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (c07aa554)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (c07d0eb8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (c086672c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/tty/tty_io.c (c095a788)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/mtd/mtdsuper.c (c0a913f4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/mtd/mtdsuper.c:get_tree_mtd
```
```
In drivers/md/md.c (c0bcbf40)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (c0bf1914)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In drivers/of/base.c (c0c4f2f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
```
```
In drivers/perf/arm-ccn.c (c0c7c4f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_get_cmp_mask
```
```
In sound/core/init.c (c0c845c4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - sound/core/init.c:snd_card_set_id_no_lock
```
```
In lib/vsprintf.c (c0e93134)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (c000000000011080)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sysctl.c (c00000000014a1ac)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (c00000000015d600)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (c000000001367f4c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (c00000000136ca78)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (c00000000027b13c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (c0000000002cb460)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (c0000000002d0268)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (c0000000002d4d8c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (c0000000002ef1bc)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (c0000000002f90d0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc5d8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (c00000000038dc38)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (c0000000004171e0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (c00000000061dff4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (c0000000006f77a8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (c00000000072a580)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (c00000000074ef7c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (c000000000796e58)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (c000000000799344)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (c0000000007cb6f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (c000000000846c10)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/tty/tty_io.c (c0000000008ed40c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (c000000000bd8ec8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (c000000000c086c8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In drivers/of/base.c (c000000000c464f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
```
```
In lib/vsprintf.c (c000000000edb774)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffe0000b47e4)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sysctl.c (ffffffe0000c96ea)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffe0000d2700)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_newuname
```
```
In kernel/reboot.c (ffffffe000005cfe)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffe000009312)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/trace/trace_events.c (ffffffe0001927fc)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffe000194fc4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffe0001973a4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In mm/shmem.c (ffffffe0001ed4dc)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In fs/hugetlbfs/inode.c (ffffffe00035542a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffe0003d6ac2)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffe0003f49ae)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffe0004098f6)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffe000439160)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffe00043a876)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffe00045a786)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004ac702)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/tty/tty_io.c (ffffffe00052cd5e)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffe0006e2470)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffe0007003cc)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In drivers/of/base.c (ffffffe00072133a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/of/base.c:of_alias_scan
```
```
In lib/vsprintf.c (ffffffe0008bfbda)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81002d5f)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8289e5a5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828aac1d)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff810a3fa0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sysctl_binary.c (ffffffff810a5e21)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
```
```
In kernel/sys.c (ffffffff810b38e7)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff828b5167)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff81102ada)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff828b8cf9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81182eb9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811b5935)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b8a5b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811bb480)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c8699)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811cf9b4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d190b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff81236828)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff812957de)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff813fb18a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffff8148adc4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff814ac878)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff814c1eb3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff814f3bb0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff814f5d17)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff81518cc1)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8156707b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8160153a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff81648085)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff8183f952)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818611d5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81a5a059)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff8100123f)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82896776)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828a2ee9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff81092980)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sysctl_binary.c (ffffffff81094801)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/sysctl_binary.c:bin_ulongvec
  - kernel/sysctl_binary.c:bin_intvec
```
```
In kernel/sys.c (ffffffff810a2217)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff828ad2e8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff810f3d4a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff828b124a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81175ff9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811a8735)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff811ab83b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811ae260)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bb479)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811c2784)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c46db)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff81229888)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff812873ee)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff813ebc0a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffff8147b7e4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff8149d298)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff814b28d3)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff814e40c0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff814e6227)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff81508fc1)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81557ecb)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff815ec9f5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff816284e5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff81806fb2)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818287a5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81a17139)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81002d5f)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b1568)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828bdb1c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff810a3f50)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffff810b2e47)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff828c8066)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff81100d4a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff828cba7c)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81180c89)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811b3705)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff811b682b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811b9250)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c6469)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811cd784)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf6db)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff812345c8)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff812935ee)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff813f850a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffff81486e64)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff814a8918)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff814bdf43)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff814efc40)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff814f1da7)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff81514d51)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81565beb)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff8161e730)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff81676445)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff8188ef82)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0805)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81ac6449)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
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
In init/do_mounts.c (ffffffff81002daf)
Location: include/linux/ctype.h:26
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff828b1596)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mcheck_enable
```
```
In arch/x86/kernel/amd_gart_64.c (ffffffff828c0c69)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - arch/x86/kernel/amd_gart_64.c:gart_parse_options
```
```
In kernel/sysctl.c (ffffffff810ac010)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/sys.c (ffffffff810bb867)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/reboot.c (ffffffff828cd3bd)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_setup
  - kernel/reboot.c:reboot_setup
```
```
In kernel/power/hibernate.c (ffffffff8110c11a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/power/hibernate.c:software_resume
```
```
In kernel/printk/printk.c (0)
Location: include/linux/ctype.h:26
Inline: True
```
```
In kernel/dma/swiotlb.c (ffffffff828d0e76)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:setup_io_tlb_npages
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118e5a9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_mm
  - kernel/debug/kdb/kdb_main.c:kdb_md
```
```
In kernel/trace/trace_events.c (ffffffff811c17a5)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_eval_update
```
```
In kernel/trace/trace_events_filter.c (ffffffff811c48cb)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:filter_parse_regex
```
```
In kernel/trace/trace_events_trigger.c (ffffffff811c72f0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_trigger_callback
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d46c9)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_probe.c (ffffffff811db9e4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
  - kernel/trace/trace_probe.c:traceprobe_parse_event_name
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd97b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
```
In mm/shmem.c (ffffffff81244728)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/shmem.c:shmem_parse_options
```
```
In mm/mempolicy.c (ffffffff812a344e)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
```
```
In fs/hugetlbfs/inode.c (ffffffff8140e25a)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
  - fs/hugetlbfs/inode.c:hugetlbfs_parse_param
```
```
In security/tomoyo/util.c (ffffffff8149e9a4)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
  - security/tomoyo/util.c:tomoyo_file_matches_pattern2
```
```
In security/device_cgroup.c (ffffffff814c12db)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
  - security/device_cgroup.c:devcgroup_access_write
```
```
In crypto/algboss.c (ffffffff814d6a13)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_notify
```
```
In block/partition-generic.c (ffffffff81508cd0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partition-generic.c:add_partition
```
```
In block/partitions/check.c (ffffffff8150ae07)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - block/partitions/check.c:check_partition
```
```
In lib/parser.c (ffffffff8152e4c1)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/parser.c:match_token
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157fb0b)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:value_store
```
```
In drivers/acpi/acpica/utstrsuppt.c (ffffffff816385e0)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstrsuppt.c:acpi_ut_convert_decimal_string
```
```
In drivers/tty/tty_io.c (ffffffff81690b65)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_dev_name_to_number
```
```
In drivers/md/md.c (ffffffff818a9cd2)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/md/md.c:add_named_array
  - drivers/md/md.c:strict_strtoul_scaled
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff818cca95)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_int_store
```
```
In lib/vsprintf.c (ffffffff81ad2929)
Location: include/linux/ctype.h:26
Inline: True
Inline callers:
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:vsscanf
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:format_decode
  - lib/vsprintf.c:skip_atoi
```
</details>
</li>
</ul>

## Differences
