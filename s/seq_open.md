# Function: <code>seq_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812317b0)
Location: fs/seq_file.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/resource.c:iomem_open
  - kernel/resource.c:ioports_open
  - kernel/sched/stats.c:schedstat_open
  - kernel/sched/debug.c:sched_debug_open
  - kernel/module.c:modules_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - mm/vmstat.c:zoneinfo_open
  - mm/vmstat.c:vmstat_open
  - mm/vmstat.c:pagetypeinfo_open
  - mm/vmstat.c:fragmentation_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:single_open
  - fs/seq_file.c:__seq_open_private
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/proc_tty.c:tty_drivers_open
  - fs/proc/consoles.c:consoles_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/proc/devices.c:devinfo_open
  - fs/proc/interrupts.c:interrupts_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/keys/proc.c:proc_key_users_open
  - security/keys/proc.c:proc_keys_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - crypto/proc.c:crypto_info_open
  - block/genhd.c:partitions_open
  - block/genhd.c:diskstats_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/pci/proc.c:proc_bus_pci_dev_open
  - drivers/video/fbdev/core/fbmem.c:proc_fb_open
  - drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open
  - drivers/char/misc.c:misc_seq_open
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_open
  - drivers/char/tpm/tpm_eventlog.c:tpm_ascii_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/scsi/sg.c:sg_proc_open_devstrs
  - drivers/scsi/sg.c:sg_proc_open_dev
  - drivers/scsi/sg.c:sg_proc_open_debug
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/core/net-procfs.c:softnet_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff812317b0-ffffffff81231854: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259ca0)
Location: fs/seq_file.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/resource.c:iomem_open
  - kernel/resource.c:ioports_open
  - kernel/sched/stats.c:schedstat_open
  - kernel/sched/debug.c:sched_debug_open
  - kernel/module.c:modules_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/vmstat.c:vmstat_open
  - mm/vmstat.c:zoneinfo_open
  - mm/vmstat.c:pagetypeinfo_open
  - mm/vmstat.c:fragmentation_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/proc_tty.c:tty_drivers_open
  - fs/proc/consoles.c:consoles_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/proc/devices.c:devinfo_open
  - fs/proc/interrupts.c:interrupts_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/keys/proc.c:proc_key_users_open
  - security/keys/proc.c:proc_keys_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - crypto/proc.c:crypto_info_open
  - block/genhd.c:diskstats_open
  - block/genhd.c:partitions_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/pci/proc.c:proc_bus_pci_dev_open
  - drivers/video/fbdev/core/fbmem.c:proc_fb_open
  - drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open
  - drivers/char/misc.c:misc_seq_open
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_open
  - drivers/char/tpm/tpm_eventlog.c:tpm_ascii_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/scsi/sg.c:sg_proc_open_debug
  - drivers/scsi/sg.c:sg_proc_open_devstrs
  - drivers/scsi/sg.c:sg_proc_open_dev
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/core/net-procfs.c:softnet_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff81259ca0-ffffffff81259d36: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126cca0)
Location: fs/seq_file.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/resource.c:iomem_open
  - kernel/resource.c:ioports_open
  - kernel/sched/stats.c:schedstat_open
  - kernel/sched/debug.c:sched_debug_open
  - kernel/module.c:modules_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/vmstat.c:vmstat_open
  - mm/vmstat.c:zoneinfo_open
  - mm/vmstat.c:pagetypeinfo_open
  - mm/vmstat.c:fragmentation_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/proc_tty.c:tty_drivers_open
  - fs/proc/consoles.c:consoles_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/proc/devices.c:devinfo_open
  - fs/proc/interrupts.c:interrupts_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/keys/proc.c:proc_key_users_open
  - security/keys/proc.c:proc_keys_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - crypto/proc.c:crypto_info_open
  - block/genhd.c:diskstats_open
  - block/genhd.c:partitions_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/pci/proc.c:proc_bus_pci_dev_open
  - drivers/video/fbdev/core/fbmem.c:proc_fb_open
  - drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open
  - drivers/char/misc.c:misc_seq_open
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/scsi/sg.c:sg_proc_open_debug
  - drivers/scsi/sg.c:sg_proc_open_devstrs
  - drivers/scsi/sg.c:sg_proc_open_dev
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/core/net-procfs.c:softnet_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff8126cca0-ffffffff8126cd36: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a860)
Location: fs/seq_file.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/resource.c:iomem_open
  - kernel/resource.c:ioports_open
  - kernel/sched/stats.c:schedstat_open
  - kernel/sched/debug.c:sched_debug_open
  - kernel/module.c:modules_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:tracing_saved_tgids_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/vmstat.c:vmstat_open
  - mm/vmstat.c:zoneinfo_open
  - mm/vmstat.c:pagetypeinfo_open
  - mm/vmstat.c:fragmentation_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/proc_tty.c:tty_drivers_open
  - fs/proc/consoles.c:consoles_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/proc/devices.c:devinfo_open
  - fs/proc/interrupts.c:interrupts_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/keys/proc.c:proc_key_users_open
  - security/keys/proc.c:proc_keys_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - crypto/proc.c:crypto_info_open
  - block/genhd.c:diskstats_open
  - block/genhd.c:partitions_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/pci/proc.c:proc_bus_pci_dev_open
  - drivers/video/fbdev/core/fbmem.c:proc_fb_open
  - drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open
  - drivers/char/misc.c:misc_seq_open
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/scsi/sg.c:sg_proc_open_debug
  - drivers/scsi/sg.c:sg_proc_open_devstrs
  - drivers/scsi/sg.c:sg_proc_open_dev
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/core/net-procfs.c:softnet_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff8127a860-ffffffff8127a8e7: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129d2d0)
Location: fs/seq_file.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/resource.c:iomem_open
  - kernel/resource.c:ioports_open
  - kernel/sched/stats.c:schedstat_open
  - kernel/sched/debug.c:sched_debug_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:tracing_saved_tgids_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/vmstat.c:vmstat_open
  - mm/vmstat.c:zoneinfo_open
  - mm/vmstat.c:pagetypeinfo_open
  - mm/vmstat.c:fragmentation_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/proc_tty.c:tty_drivers_open
  - fs/proc/consoles.c:consoles_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/proc/devices.c:devinfo_open
  - fs/proc/interrupts.c:interrupts_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/ext4/mballoc.c:ext4_mb_seq_groups_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/keys/proc.c:proc_key_users_open
  - security/keys/proc.c:proc_keys_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - crypto/proc.c:crypto_info_open
  - block/genhd.c:diskstats_open
  - block/genhd.c:partitions_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/pci/proc.c:proc_bus_pci_dev_open
  - drivers/video/fbdev/core/fbmem.c:proc_fb_open
  - drivers/tty/tty_ldisc.c:proc_tty_ldiscs_open
  - drivers/char/misc.c:misc_seq_open
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/scsi/sg.c:sg_proc_open_debug
  - drivers/scsi/sg.c:sg_proc_open_devstrs
  - drivers/scsi/sg.c:sg_proc_open_dev
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/core/net-procfs.c:softnet_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff8129d2d0-ffffffff8129d357: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c29e0)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce-severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:tracing_saved_tgids_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_hist.c:synth_events_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff812c29e0-ffffffff812c2a62: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d7c80)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:tracing_saved_tgids_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_hist.c:synth_events_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_dynevent.c:dyn_event_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff812d7c80-ffffffff812d7d02: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (0)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_saved_cmdlines_open
  - kernel/trace/trace.c:tracing_saved_tgids_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_printk.c:ftrace_formats_open
  - kernel/trace/trace_stack.c:stack_trace_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_hist.c:synth_events_open
  - kernel/trace/trace_kprobe.c:profile_open
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_dynevent.c:dyn_event_open
  - kernel/trace/trace_uprobe.c:profile_open
  - kernel/trace/trace_uprobe.c:probes_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff812f7802-ffffffff812f7815: seq_open.cold (STB_LOCAL)
ffffffff812f6190-ffffffff812f6212: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81307d60)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff81307d60-ffffffff81307de2: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341200)
Location: fs/seq_file.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff81341200-ffffffff81341277: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134d290)
Location: fs/seq_file.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff8134d290-ffffffff8134d307: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81353e90)
Location: fs/seq_file.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - kernel/sched/debug.c:sched_debug_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
```
**Symbols:**

```
ffffffff81353e90-ffffffff81353f07: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a22e0)
Location: fs/seq_file.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - kernel/sched/debug.c:sched_debug_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_hwlat.c:hwlat_mode_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - mm/kfence/core.c:open_objects
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
```
**Symbols:**

```
ffffffff813a22e0-ffffffff813a2357: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81425e70)
Location: fs/seq_file.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - kernel/sched/build_utility.c:sched_debug_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_hwlat.c:hwlat_mode_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - mm/kfence/core.c:open_objects
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
```
**Symbols:**

```
ffffffff81425e70-ffffffff81425ef1: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b2740)
Location: fs/seq_file.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - kernel/sched/build_utility.c:sched_debug_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_hwlat.c:hwlat_mode_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv.c:available_monitors_open
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_open
  - kernel/trace/rv/rv_reactors.c:available_reactors_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmscan.c:lru_gen_seq_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
```
**Symbols:**

```
ffffffff814b2740-ffffffff814b27c1: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e7790)
Location: fs/seq_file.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - kernel/sched/build_utility.c:sched_debug_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_hwlat.c:hwlat_mode_open
  - kernel/trace/trace_osnoise.c:osnoise_options_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_user.c:user_status_open
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv.c:available_monitors_open
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_open
  - kernel/trace/rv/rv_reactors.c:available_reactors_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmscan.c:lru_gen_seq_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
```
**Symbols:**

```
ffffffff814e7790-ffffffff814e7811: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151b620)
Location: fs/seq_file.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat/memtype.c:memtype_seq_open
  - kernel/sched/build_utility.c:sched_debug_open
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_hwlat.c:hwlat_mode_open
  - kernel/trace/trace_osnoise.c:osnoise_options_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/trace_events_user.c:user_status_open
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv.c:available_monitors_open
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_open
  - kernel/trace/rv/rv_reactors.c:available_reactors_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmscan.c:lru_gen_seq_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
```
**Symbols:**

```
ffffffff8151b620-ffffffff8151b6a1: seq_open (STB_GLOBAL)
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
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bb818)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - virt/kvm/arm/vgic/vgic-debug.c:debug_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffff8000103bb818-ffff8000103bb8b0: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c059902c)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_ports_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
c059902c-c05990d4: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b8c30)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
c0000000004b8c30-c0000000004b8cf0: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d360)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffe00027d360-ffffffe00027d3e2: seq_open (STB_GLOBAL)
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
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300340)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff81300340-ffffffff813003c2: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f0f60)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff812f0f60-ffffffff812f0fe2: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe130)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff812fe130-ffffffff812fe1b2: seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_open(struct file *file, const struct seq_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f470)
Location: fs/seq_file.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:severities_coverage_open
  - arch/x86/mm/pat.c:memtype_seq_open
  - arch/x86/platform/uv/tlb_uv.c:ptc_proc_open
  - kernel/kprobes.c:kprobe_blacklist_open
  - kernel/kprobes.c:kprobes_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:trace_format_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/bpf/inode.c:bpffs_map_open
  - mm/vmstat.c:extfrag_open
  - mm/vmstat.c:unusable_open
  - mm/slab_common.c:slabinfo_open
  - mm/swapfile.c:swaps_open
  - fs/seq_file.c:__seq_open_private
  - fs/seq_file.c:single_open
  - fs/proc/base.c:proc_id_map_open
  - fs/proc/generic.c:proc_seq_open
  - fs/proc/array.c:children_seq_open
  - fs/proc/cpuinfo.c:cpuinfo_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/pstore/inode.c:pstore_file_open
  - security/selinux/selinuxfs.c:sel_open_avc_cache_stats
  - security/smack/smackfs.c:smk_open_relabel_self
  - security/smack/smackfs.c:smk_open_load_self2
  - security/smack/smackfs.c:smk_open_load2
  - security/smack/smackfs.c:smk_open_load_self
  - security/smack/smackfs.c:smk_open_onlycap
  - security/smack/smackfs.c:smk_open_net6addr
  - security/smack/smackfs.c:smk_open_net4addr
  - security/smack/smackfs.c:smk_open_cipso2
  - security/smack/smackfs.c:smk_open_cipso
  - security/smack/smackfs.c:smk_open_load
  - security/apparmor/apparmorfs.c:profiles_open
  - security/integrity/ima/ima_fs.c:ima_ascii_measurements_open
  - security/integrity/ima/ima_fs.c:ima_measurements_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/error-inject.c:ei_open
  - drivers/gpio/gpiolib.c:gpiolib_open
  - drivers/pwm/core.c:pwm_seq_open
  - drivers/char/tpm/eventlog/common.c:tpm_bios_measurements_open
  - drivers/scsi/scsi_devinfo.c:proc_scsi_devinfo_open
  - drivers/scsi/scsi_proc.c:proc_scsi_open
  - drivers/input/input.c:input_proc_handlers_open
  - drivers/input/input.c:input_proc_devices_open
  - drivers/md/md.c:md_seq_open
  - net/ipv4/route.c:rt_cpu_seq_open
  - net/ipv4/route.c:rt_cache_seq_open
```
**Symbols:**

```
ffffffff8130f470-ffffffff8130f4f2: seq_open (STB_GLOBAL)
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
