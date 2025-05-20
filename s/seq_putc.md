# Function: <code>seq_putc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230630)
Location: fs/seq_file.c:654
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup.c:cgroup_release_agent_show
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace.c:t_show
  - kernel/trace/trace.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/slab_common.c:print_slabinfo_header
  - mm/slab_common.c:cache_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/namespace.c:generic_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - drivers/pci/proc.c:show_device
  - drivers/pci/proc.c:show_device
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/core/net-procfs.c:dev_mc_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff81230630-ffffffff81230654: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259c08)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_release_agent_show
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace.c:t_show
  - kernel/trace/trace.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/namespace.c:generic_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - drivers/pci/proc.c:show_device
  - drivers/pci/proc.c:show_device
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - net/core/net-procfs.c:dev_mc_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff81258cc0-ffffffff81258ce4: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126d3d8)
Location: fs/seq_file.c:664
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:proc_cgroup_show
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup.c:cgroup_release_agent_show
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup.c:cgroup_show_options
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace.c:t_show
  - kernel/trace/trace.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/namespace.c:generic_show_options
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - drivers/pci/proc.c:show_device
  - drivers/pci/proc.c:show_device
  - drivers/tty/serial/serial_core.c:uart_proc_show
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/char/tpm/tpm_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - net/core/net-procfs.c:dev_mc_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff8126c170-ffffffff8126c194: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127ab2f)
Location: fs/seq_file.c:650
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/tpm1_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/char/tpm/tpm1_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff81279950-ffffffff81279974: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129d59f)
Location: fs/seq_file.c:654
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/tpm1_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/char/tpm/tpm1_eventlog.c:tpm_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/proc.c:snmp_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff8129c380-ffffffff8129c3a4: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c378b)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:synth_events_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_kprobe.c:probes_seq_show
  - kernel/trace/trace_uprobe.c:probes_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff812c28c0-ffffffff812c28e4: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d89db)
Location: fs/seq_file.c:645
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff812d7b60-ffffffff812d7b84: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6df9)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff812f6070-ffffffff812f6094: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81308e39)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff81307c40-ffffffff81307c64: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81342179)
Location: fs/seq_file.c:633
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:track_data_snapshot_print
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:cache_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/io_uring.c:io_uring_show_cred
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff81341100-ffffffff81341124: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e839)
Location: fs/seq_file.c:649
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:track_data_snapshot_print
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:cache_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/io_uring.c:io_uring_show_cred
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff8134d190-ffffffff8134d1b4: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81354b99)
Location: fs/seq_file.c:670
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:slab_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff81353d70-ffffffff81353d94: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2f9e)
Location: fs/seq_file.c:679
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:slab_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff813a21c0-ffffffff813a21e4: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81426d0a)
Location: fs/seq_file.c:663
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:slab_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff81425ca0-ffffffff81425cd2: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b37aa)
Location: fs/seq_file.c:663
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:slab_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff814b24f0-ffffffff814b2522: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e881e)
Location: fs/seq_file.c:663
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:slab_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff814e7540-ffffffff814e7572: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151c6ae)
Location: fs/seq_file.c:663
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_pad
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/proc.c:arch_proc_pid_thread_features
  - arch/x86/kernel/cpu/proc.c:arch_proc_pid_thread_features
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:proc_resctrl_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_show
  - kernel/trace/trace_events_synth.c:__synth_event_show
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - kernel/trace/trace_fprobe.c:trace_fprobe_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmscan.c:lru_gen_seq_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show
  - mm/slab_common.c:slab_show
  - mm/slab_common.c:slab_show
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:lstats_show_proc
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:task_seccomp
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_key_describe
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/scsi/scsi_proc.c:proc_print_scsidevice
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:trie_show_stats
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
  - net/mptcp/mib.c:mptcp_seq_show
```
**Symbols:**

```
ffffffff8151b3d0-ffffffff8151b402: seq_putc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bc8b0)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_group_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffff8000103bb5d8-ffff8000103bb620: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c059a42c)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinconf_group_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/tty/serial/serial_core.c:uart_line_info
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
c0598e5c-c0598e90: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004ba084)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/powerpc/kernel/rtas-proc.c:ppc_rtas_sensors_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
c0000000004b8a80-c0000000004b8aac: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027df8e)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/vmalloc.c:s_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/gpio/gpio-stmpe.c:stmpe_dbg_show
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffe00027d18a-ffffffe00027d1c6: seq_putc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81301419)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff81300220-ffffffff81300244: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f2039)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff812f0e40-ffffffff812f0e64: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812ff209)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/netfilter/nf_conntrack_expect.c:exp_seq_show
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff812fe010-ffffffff812fe034: seq_putc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void seq_putc(struct seq_file *m, char c);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81310549)
Location: fs/seq_file.c:657
Inline: True
Inline callers:
  - fs/seq_file.c:seq_hex_dump
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_hex_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:proc_pid_arch_status
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
  - kernel/fork.c:pidfd_show_fdinfo
  - kernel/irq/proc.c:show_interrupts
  - kernel/irq/proc.c:show_interrupts
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup.c:cgroup_print_ss_mask
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_show_options
  - kernel/cgroup/cgroup-v1.c:cgroup_release_agent_show
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/rdma.c:rdmacg_resource_read
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:t_show
  - kernel/trace/ftrace.c:function_stat_show
  - kernel/trace/trace.c:tracing_clock_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_printk.c:t_show
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_functions_graph.c:print_graph_headers_flags
  - kernel/trace/trace_events.c:f_show
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_print
  - kernel/trace/trace_events_trigger.c:event_trigger_print
  - kernel/trace/trace_events_hist.c:event_hist_trigger_print
  - kernel/trace/trace_events_hist.c:hist_field_print
  - kernel/trace/trace_events_hist.c:hist_show
  - kernel/trace/trace_events_hist.c:__synth_event_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_kprobe.c:trace_kprobe_show
  - kernel/trace/trace_uprobe.c:trace_uprobe_show
  - mm/vmstat.c:extfrag_show_print
  - mm/vmstat.c:unusable_show_print
  - mm/vmstat.c:vmstat_show
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:pagetypeinfo_showblockcount_print
  - mm/vmstat.c:pagetypeinfo_showfree_print
  - mm/vmstat.c:frag_show_print
  - mm/slab_common.c:cache_show
  - mm/slab_common.c:print_slabinfo_header
  - mm/vmalloc.c:s_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_vfsstat
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_mountinfo
  - fs/proc_namespace.c:show_vfsmnt
  - fs/proc_namespace.c:show_vfsmnt
  - fs/notify/fdinfo.c:fanotify_fdinfo
  - fs/notify/fdinfo.c:inotify_fdinfo
  - fs/proc/task_mmu.c:show_numa_map
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_smap
  - fs/proc/task_mmu.c:show_map_vma
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/task_mmu.c:show_vma_header_prefix
  - fs/proc/base.c:comm_show
  - fs/proc/base.c:proc_pid_limits
  - fs/proc/base.c:lstats_show_proc
  - fs/proc/base.c:proc_pid_wchan
  - fs/proc/array.c:proc_pid_statm
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:render_cap_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:render_sigset_t
  - fs/proc/array.c:task_state
  - fs/proc/array.c:task_state
  - fs/proc/proc_tty.c:show_tty_range
  - fs/proc/cmdline.c:cmdline_proc_show
  - fs/proc/consoles.c:show_console_dev
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/stat.c:show_stat
  - fs/proc/softirqs.c:show_softirqs
  - fs/proc/softirqs.c:show_softirqs
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - fs/ext4/super.c:_ext4_show_options
  - security/keys/proc.c:proc_keys_show
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/selinux/hooks.c:show_sid
  - security/smack/smackfs.c:relabel_self_seq_show
  - security/smack/smackfs.c:onlycap_seq_show
  - security/smack/smackfs.c:cipso2_seq_show
  - security/smack/smackfs.c:cipso_seq_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/smack/smackfs.c:smk_rule_show
  - security/apparmor/apparmorfs.c:seq_show_profile
  - security/apparmor/apparmorfs.c:seq_rawdata_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/apparmor/apparmorfs.c:seq_profile_hash_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - security/integrity/ima/ima_fs.c:ima_measurements_show
  - crypto/proc.c:c_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - lib/sbitmap.c:sbitmap_bitmap_show
  - drivers/pinctrl/core.c:pinctrl_maps_show
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_groups_show
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_config
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_show
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/clk/clk.c:clk_dump_subtree
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_binary_bios_measurements_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_show
  - drivers/dma-buf/sync_debug.c:sync_print_fence
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/scsi/scsi_proc.c:scsi_seq_show
  - drivers/input/input.c:input_handlers_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_devices_seq_show
  - drivers/input/input.c:input_seq_print_bitmap
  - drivers/input/input.c:input_seq_print_bitmap
  - net/ipv4/fib_trie.c:fib_trie_seq_show
  - net/ipv4/fib_trie.c:fib_triestat_seq_show
  - net/ipv4/proc.c:netstat_seq_show
  - net/ipv4/ipmr.c:ipmr_mfc_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/unix/af_unix.c:unix_seq_show
  - net/ipv6/ip6mr.c:ipmr_mfc_seq_show
```
**Symbols:**

```
ffffffff8130f350-ffffffff8130f374: seq_putc (STB_GLOBAL)
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
