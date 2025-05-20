# Function: <code>single_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81231860)
Location: fs/seq_file.c:563
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_sleep_tmr_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_pss_state_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_dev_state_open
  - kernel/exec_domain.c:execdomains_proc_open
  - kernel/sched/core.c:sched_feat_open
  - kernel/power/qos.c:pm_qos_dbg_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:irq_spurious_proc_open
  - kernel/irq/proc.c:irq_node_proc_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_hint_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timer_stats.c:tstats_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/dma.c:proc_dma_open
  - kernel/cgroup.c:cgroupstats_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/filesystems.c:filesystems_proc_open
  - fs/seq_file.c:single_open_size
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/cmdline.c:cmdline_proc_open
  - fs/proc/loadavg.c:loadavg_proc_open
  - fs/proc/meminfo.c:meminfo_proc_open
  - fs/proc/uptime.c:uptime_proc_open
  - fs/proc/version.c:version_proc_open
  - fs/proc/softirqs.c:softirqs_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/ext4/sysfs.c:es_shrinker_info_open
  - fs/ext4/sysfs.c:options_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/acpi/button.c:acpi_button_state_open_fs
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/tty/serial/serial_core.c:uart_proc_open
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/connector/connector.c:cn_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/scsi/sg.c:sg_proc_single_open_version
  - drivers/scsi/sg.c:sg_proc_single_open_devhdr
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/ras/debugfs.c:trace_open
  - net/sched/sch_api.c:psched_open
  - net/ipv4/route.c:rt_acct_proc_open
  - net/ipv6/proc.c:snmp6_dev_seq_open
```
**Symbols:**

```
ffffffff81231860-ffffffff81231903: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259d40)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_sleep_tmr_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_pss_state_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_dev_state_open
  - kernel/exec_domain.c:execdomains_proc_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/power/qos.c:pm_qos_dbg_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:irq_spurious_proc_open
  - kernel/irq/proc.c:irq_node_proc_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_hint_proc_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timer_stats.c:tstats_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/dma.c:proc_dma_open
  - kernel/cgroup.c:cgroupstats_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace_events_hist.c:event_hist_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/filesystems.c:filesystems_proc_open
  - fs/seq_file.c:single_open_size
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/cmdline.c:cmdline_proc_open
  - fs/proc/loadavg.c:loadavg_proc_open
  - fs/proc/meminfo.c:meminfo_proc_open
  - fs/proc/uptime.c:uptime_proc_open
  - fs/proc/version.c:version_proc_open
  - fs/proc/softirqs.c:softirqs_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/ext4/sysfs.c:options_open
  - fs/ext4/sysfs.c:es_shrinker_info_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/acpi/button.c:acpi_button_state_open_fs
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/tty/serial/serial_core.c:uart_proc_open
  - drivers/connector/connector.c:cn_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
  - drivers/base/power/domain.c:pm_genpd_summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/scsi/sg.c:sg_proc_single_open_devhdr
  - drivers/scsi/sg.c:sg_proc_single_open_version
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/ras/debugfs.c:trace_open
  - net/sched/sch_api.c:psched_open
  - net/ipv4/route.c:rt_acct_proc_open
  - net/ipv6/proc.c:snmp6_dev_seq_open
```
**Symbols:**

```
ffffffff81259d40-ffffffff81259de3: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126cd40)
Location: fs/seq_file.c:573
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_sleep_tmr_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_pss_state_open
  - arch/x86/platform/atom/pmc_atom.c:pmc_dev_state_open
  - kernel/exec_domain.c:execdomains_proc_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/power/qos.c:pm_qos_dbg_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:irq_spurious_proc_open
  - kernel/irq/proc.c:irq_node_proc_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_hint_proc_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timer_stats.c:tstats_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/dma.c:proc_dma_open
  - kernel/cgroup.c:cgroupstats_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace_events_hist.c:event_hist_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/filesystems.c:filesystems_proc_open
  - fs/seq_file.c:single_open_size
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/cmdline.c:cmdline_proc_open
  - fs/proc/loadavg.c:loadavg_proc_open
  - fs/proc/meminfo.c:meminfo_proc_open
  - fs/proc/uptime.c:uptime_proc_open
  - fs/proc/version.c:version_proc_open
  - fs/proc/softirqs.c:softirqs_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/ext4/sysfs.c:options_open
  - fs/ext4/sysfs.c:es_shrinker_info_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_ns_name
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_ns_level
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_ns_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_open_stacked
  - security/apparmor/apparmorfs.c:aa_fs_seq_hash_open
  - security/apparmor/apparmorfs.c:aa_fs_seq_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/acpi/button.c:acpi_button_state_open_fs
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/tty/serial/serial_core.c:uart_proc_open
  - drivers/connector/connector.c:cn_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
  - drivers/base/power/domain.c:pm_genpd_summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_devhdr
  - drivers/scsi/sg.c:sg_proc_single_open_version
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_open
  - drivers/ras/debugfs.c:trace_open
  - net/sched/sch_api.c:psched_open
  - net/ipv4/route.c:rt_acct_proc_open
  - net/ipv6/proc.c:snmp6_dev_seq_open
```
**Symbols:**

```
ffffffff8126cd40-ffffffff8126cde0: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a8f0)
Location: fs/seq_file.c:559
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/exec_domain.c:execdomains_proc_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/power/qos.c:pm_qos_dbg_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:irq_spurious_proc_open
  - kernel/irq/proc.c:irq_node_proc_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_effective_aff_list_proc_open
  - kernel/irq/proc.c:irq_effective_aff_proc_open
  - kernel/irq/proc.c:irq_affinity_hint_proc_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/dma.c:proc_dma_open
  - kernel/cgroup/cgroup-v1.c:cgroupstats_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace_events_hist.c:event_hist_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/filesystems.c:filesystems_proc_open
  - fs/seq_file.c:single_open_size
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/cmdline.c:cmdline_proc_open
  - fs/proc/loadavg.c:loadavg_proc_open
  - fs/proc/meminfo.c:meminfo_proc_open
  - fs/proc/uptime.c:uptime_proc_open
  - fs/proc/version.c:version_proc_open
  - fs/proc/softirqs.c:softirqs_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/ext4/sysfs.c:options_open
  - fs/ext4/sysfs.c:es_shrinker_info_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/acpi/button.c:acpi_button_state_open_fs
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/tty/serial/serial_core.c:uart_proc_open
  - drivers/connector/connector.c:cn_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
  - drivers/base/power/domain.c:pm_genpd_summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_devhdr
  - drivers/scsi/sg.c:sg_proc_single_open_version
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/ras/cec.c:array_open
  - net/sched/sch_api.c:psched_open
  - net/ipv4/route.c:rt_acct_proc_open
  - net/ipv6/proc.c:snmp6_dev_seq_open
```
**Symbols:**

```
ffffffff8127a8f0-ffffffff8127a990: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129d360)
Location: fs/seq_file.c:563
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/exec_domain.c:execdomains_proc_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/power/qos.c:pm_qos_dbg_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:irq_spurious_proc_open
  - kernel/irq/proc.c:irq_node_proc_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_effective_aff_list_proc_open
  - kernel/irq/proc.c:irq_effective_aff_proc_open
  - kernel/irq/proc.c:irq_affinity_hint_proc_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/dma.c:proc_dma_open
  - kernel/cgroup/cgroup-v1.c:cgroupstats_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace_events_hist.c:event_hist_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/filesystems.c:filesystems_proc_open
  - fs/seq_file.c:single_open_size
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/cmdline.c:cmdline_proc_open
  - fs/proc/loadavg.c:loadavg_proc_open
  - fs/proc/meminfo.c:meminfo_proc_open
  - fs/proc/uptime.c:uptime_proc_open
  - fs/proc/version.c:version_proc_open
  - fs/proc/softirqs.c:softirqs_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/ext4/sysfs.c:options_open
  - fs/ext4/sysfs.c:es_shrinker_info_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/acpi/button.c:acpi_button_state_open_fs
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/tty/serial/serial_core.c:uart_proc_open
  - drivers/connector/connector.c:cn_proc_open
  - drivers/base/power/wakeup.c:wakeup_sources_stats_open
  - drivers/base/power/domain.c:genpd_devices_open
  - drivers/base/power/domain.c:genpd_total_idle_time_open
  - drivers/base/power/domain.c:genpd_active_time_open
  - drivers/base/power/domain.c:genpd_idle_states_open
  - drivers/base/power/domain.c:genpd_sub_domains_open
  - drivers/base/power/domain.c:genpd_status_open
  - drivers/base/power/domain.c:genpd_summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_devhdr
  - drivers/scsi/sg.c:sg_proc_single_open_version
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/rtc/rtc-proc.c:rtc_proc_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/ras/cec.c:array_open
  - net/sched/sch_api.c:psched_open
  - net/ipv4/route.c:rt_acct_proc_open
  - net/ipv6/proc.c:snmp6_dev_seq_open
```
**Symbols:**

```
ffffffff8129d360-ffffffff8129d400: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c2fe0)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/power/qos.c:pm_qos_dbg_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace_events_hist.c:event_hist_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/power/domain.c:genpd_perf_state_open
  - drivers/base/power/domain.c:genpd_devices_open
  - drivers/base/power/domain.c:genpd_total_idle_time_open
  - drivers/base/power/domain.c:genpd_active_time_open
  - drivers/base/power/domain.c:genpd_idle_states_open
  - drivers/base/power/domain.c:genpd_sub_domains_open
  - drivers/base/power/domain.c:genpd_status_open
  - drivers/base/power/domain.c:genpd_summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_sts_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_sts_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/ras/cec.c:array_open
```
**Symbols:**

```
ffffffff812c2fe0-ffffffff812c3080: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d7f50)
Location: fs/seq_file.c:554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace_events_hist.c:event_hist_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_dbg_config_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/ras/cec.c:array_open
```
**Symbols:**

```
ffffffff812d7f50-ffffffff812d7ff0: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6460)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace_events_hist.c:event_hist_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffffffff812f6460-ffffffff812f64f7: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81308030)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffffffff81308030-ffffffff813080c7: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341410)
Location: fs/seq_file.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_res_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff81341410-ffffffff813414a7: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134d480)
Location: fs/seq_file.c:558
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_units_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_context_array_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_id_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_res_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff8134d480-ffffffff8134d517: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813540e0)
Location: fs/seq_file.c:579
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sd_flags_open
  - kernel/sched/debug.c:sched_scaling_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_units_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_select_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_context_array_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_id_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_lpm_latch_mode_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_req_regs_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_l_sts_regs_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_sts_regs_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_substate_res_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff813540e0-ffffffff81354177: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2510)
Location: fs/seq_file.c:588
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sd_flags_open
  - kernel/sched/debug.c:sched_scaling_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_units_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/kfence/core.c:stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_select_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_context_array_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_id_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_req_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_res_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff813a2510-ffffffff813a25a7: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814260f0)
Location: fs/seq_file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/build_utility.c:psi_cpu_open
  - kernel/sched/build_utility.c:psi_memory_open
  - kernel/sched/build_utility.c:psi_io_open
  - kernel/sched/build_utility.c:sd_flags_open
  - kernel/sched/build_utility.c:sched_dynamic_open
  - kernel/sched/build_utility.c:sched_scaling_open
  - kernel/sched/build_utility.c:sched_feat_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_flags_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/kfence/core.c:stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_compress_max_open
  - security/apparmor/apparmorfs.c:seq_ns_compress_min_open
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_hash_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_attach_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_mode_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:seq_profile_name_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_select_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_context_array_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_id_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_req_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_res_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff814260f0-ffffffff8142619b: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b2a10)
Location: fs/seq_file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/build_utility.c:psi_cpu_open
  - kernel/sched/build_utility.c:psi_memory_open
  - kernel/sched/build_utility.c:psi_io_open
  - kernel/sched/build_utility.c:sd_flags_open
  - kernel/sched/build_utility.c:sched_dynamic_open
  - kernel/sched/build_utility.c:sched_scaling_open
  - kernel/sched/build_utility.c:sched_feat_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_flags_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/kfence/core.c:stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_regset32_open
  - security/apparmor/apparmorfs.c:seq_ns_compress_max_open
  - security/apparmor/apparmorfs.c:seq_ns_compress_min_open
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_select_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_raw_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_context_array_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_id_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_err_stats_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_req_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_res_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff814b2a10-ffffffff814b2abb: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e7a60)
Location: fs/seq_file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/build_utility.c:psi_cpu_open
  - kernel/sched/build_utility.c:psi_memory_open
  - kernel/sched/build_utility.c:psi_io_open
  - kernel/sched/build_utility.c:sd_flags_open
  - kernel/sched/build_utility.c:sched_dynamic_open
  - kernel/sched/build_utility.c:sched_scaling_open
  - kernel/sched/build_utility.c:sched_feat_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_flags_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/kfence/core.c:stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_regset32_open
  - security/apparmor/apparmorfs.c:seq_ns_compress_max_open
  - security/apparmor/apparmorfs.c:seq_ns_compress_min_open
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_select_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_raw_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_context_array_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_id_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_err_stats_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_req_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_l_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_sts_regs_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_substate_res_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_pll_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff814e7a60-ffffffff814e7b0b: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151b8f0)
Location: fs/seq_file.c:572
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - arch/x86/kernel/cpu/debugfs.c:cpu_debug_open
  - kernel/sched/build_utility.c:psi_cpu_open
  - kernel/sched/build_utility.c:psi_memory_open
  - kernel/sched/build_utility.c:psi_io_open
  - kernel/sched/build_utility.c:sd_flags_open
  - kernel/sched/build_utility.c:sched_dynamic_open
  - kernel/sched/build_utility.c:sched_scaling_open
  - kernel/sched/build_utility.c:sched_feat_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/power/energy_model.c:em_debug_flags_open
  - kernel/power/energy_model.c:em_debug_cpus_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/latencytop.c:lstats_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/kfence/core.c:stats_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:timens_offsets_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/base.c:lstats_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_regset32_open
  - security/apparmor/apparmorfs.c:seq_ns_compress_max_open
  - security/apparmor/apparmorfs.c:seq_ns_compress_min_open
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - lib/stackdepot.c:stats_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_select_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/dmaengine.c:dmaengine_summary_open
  - drivers/pmdomain/core.c:perf_state_open
  - drivers/pmdomain/core.c:devices_open
  - drivers/pmdomain/core.c:total_idle_time_open
  - drivers/pmdomain/core.c:active_time_open
  - drivers/pmdomain/core.c:idle_states_open
  - drivers/pmdomain/core.c:sub_domains_open
  - drivers/pmdomain/core.c:status_open
  - drivers/pmdomain/core.c:summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/drm/drm_debugfs.c:bridges_open
  - drivers/gpu/drm/drm_debugfs.c:output_bpc_open
  - drivers/gpu/drm/drm_debugfs.c:vrr_range_open
  - drivers/gpu/drm/drm_debugfs.c:edid_open
  - drivers/gpu/drm/drm_debugfs.c:connector_open
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_entry_open
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_open
  - drivers/gpu/drm/drm_debugfs_crc.c:crc_control_open
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_raw_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_open
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_port_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_context_array_open
  - drivers/usb/host/xhci-debugfs.c:xhci_stream_id_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/mmc/core/debugfs.c:mmc_err_stats_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/devfreq/devfreq.c:devfreq_summary_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/interconnect/core.c:icc_graph_open
  - drivers/interconnect/core.c:icc_summary_open
```
**Symbols:**

```
ffffffff8151b8f0-ffffffff8151b99b: single_open (STB_GLOBAL)
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
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bbba0)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - mm/memblock.c:memblock_debug_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/dma/amba-pl08x.c:pl08x_debugfs_open
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_summary_open
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_open
  - drivers/soc/sunxi/sunxi_sram.c:sunxi_sram_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/firmware/ti_sci.c:ti_sci_debug_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/ras/debugfs.c:trace_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffff8000103bbba0-ffff8000103bbc58: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0599318)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/arm/mm/alignment.c:alignment_proc_open
  - arch/arm/mach-omap2/pm-debug.c:pm_dbg_timers_open
  - arch/arm/mach-omap2/pm-debug.c:pm_dbg_counters_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - mm/memblock.c:memblock_debug_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - drivers/bus/mvebu-mbus.c:mvebu_devs_debug_open
  - drivers/bus/mvebu-mbus.c:mvebu_sdram_debug_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/gpio/gpio-tegra.c:tegra_dbg_gpio_open
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/clk/tegra/clk-dfll.c:attr_registers_open
  - drivers/dma/amba-pl08x.c:pl08x_debugfs_open
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_summary_open
  - drivers/soc/amlogic/meson-clk-measure.c:clk_msr_open
  - drivers/soc/tegra/pmc.c:powergate_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/iommu/tegra-smmu.c:tegra_smmu_clients_open
  - drivers/iommu/tegra-smmu.c:tegra_smmu_swgroups_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/mtd/mtdcore.c:mtd_partname_debugfs_open
  - drivers/mtd/mtdcore.c:mtd_partid_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/usb/musb/musb_debugfs.c:musb_softconnect_open
  - drivers/usb/musb/musb_debugfs.c:musb_test_mode_open
  - drivers/usb/musb/musb_debugfs.c:musb_regdump_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/mmc/host/omap_hsmmc.c:mmc_regs_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/memory/tegra/tegra124-emc.c:emc_debug_supported_rates_open
  - drivers/ras/debugfs.c:trace_open
  - sound/core/info.c:snd_info_text_entry_open
  - sound/soc/soc-core.c:component_list_open
  - sound/soc/soc-core.c:dai_list_open
  - sound/soc/fsl/fsl_ssi_dbg.c:fsl_ssi_stats_open
```
**Symbols:**

```
c0599318-c05993c0: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b9090)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/powerpc/kernel/rtas-proc.c:tone_volume_open
  - arch/powerpc/kernel/rtas-proc.c:tone_freq_open
  - arch/powerpc/kernel/rtas-proc.c:clock_open
  - arch/powerpc/kernel/rtas-proc.c:progress_open
  - arch/powerpc/kernel/rtas-proc.c:poweron_open
  - arch/powerpc/kernel/eeh_cache.c:eeh_addr_cache_open
  - arch/powerpc/kernel/fadump.c:fadump_region_open
  - arch/powerpc/mm/numa.c:topology_open
  - arch/powerpc/platforms/powernv/vas-debug.c:hvwc_open
  - arch/powerpc/platforms/powernv/vas-debug.c:info_open
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_freq_open
  - arch/powerpc/platforms/pseries/lpar.c:vcpudispatch_stats_open
  - arch/powerpc/platforms/pseries/lparcfg.c:lparcfg_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - mm/memblock.c:memblock_debug_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
c0000000004b9090-c0000000004b9198: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d61c)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_rawdata_open
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:seq_profile_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffffffe00027d61c-ffffffe00027d6b8: single_open (STB_GLOBAL)
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
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81300610)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffffffff81300610-ffffffff813006a7: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f1230)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffffffff812f1230-ffffffff812f12c7: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe400)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffffffff812fe400-ffffffff812fe497: single_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int single_open(struct file *file, int (*show)(struct seq_file *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f740)
Location: fs/seq_file.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_open
  - kernel/sched/debug.c:sched_feat_open
  - kernel/sched/psi.c:psi_cpu_open
  - kernel/sched/psi.c:psi_memory_open
  - kernel/sched/psi.c:psi_io_open
  - kernel/power/qos.c:pm_qos_debug_open
  - kernel/power/main.c:suspend_stats_open
  - kernel/irq/proc.c:default_affinity_open
  - kernel/irq/proc.c:irq_affinity_list_proc_open
  - kernel/irq/proc.c:irq_affinity_proc_open
  - kernel/profile.c:prof_cpu_mask_proc_open
  - kernel/time/timekeeping_debug.c:tk_debug_sleep_time_open
  - kernel/latencytop.c:lstats_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_trace_options_open
  - mm/backing-dev.c:bdi_debug_stats_open
  - mm/slab_common.c:memcg_slabinfo_open
  - fs/seq_file.c:single_open_size
  - fs/proc/task_mmu.c:smaps_rollup_open
  - fs/proc/base.c:proc_setgroups_open
  - fs/proc/base.c:timerslack_ns_open
  - fs/proc/base.c:comm_open
  - fs/proc/base.c:sched_autogroup_open
  - fs/proc/base.c:sched_open
  - fs/proc/base.c:proc_single_open
  - fs/proc/base.c:lstats_open
  - fs/proc/generic.c:proc_single_open
  - fs/proc/fd.c:seq_fdinfo_open
  - fs/proc/proc_net.c:single_open_net
  - fs/proc/version_signature.c:version_signature_proc_open
  - fs/debugfs/file.c:debugfs_devm_entry_open
  - fs/debugfs/file.c:debugfs_open_regset32
  - security/apparmor/apparmorfs.c:seq_ns_name_open
  - security/apparmor/apparmorfs.c:seq_ns_level_open
  - security/apparmor/apparmorfs.c:seq_ns_nsstacked_open
  - security/apparmor/apparmorfs.c:seq_ns_stacked_open
  - security/apparmor/apparmorfs.c:aa_sfs_seq_open
  - block/blk-mq-debugfs.c:blk_mq_debugfs_open
  - drivers/pinctrl/core.c:pinctrl_open
  - drivers/pinctrl/core.c:pinctrl_maps_open
  - drivers/pinctrl/core.c:pinctrl_devices_open
  - drivers/pinctrl/core.c:pinctrl_gpioranges_open
  - drivers/pinctrl/core.c:pinctrl_groups_open
  - drivers/pinctrl/core.c:pinctrl_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_pins_open
  - drivers/pinctrl/pinmux.c:pinmux_functions_open
  - drivers/pinctrl/pinconf.c:pinconf_groups_open
  - drivers/pinctrl/pinconf.c:pinconf_pins_open
  - drivers/acpi/proc.c:acpi_system_wakeup_device_open_fs
  - drivers/clk/clk.c:clk_max_rate_open
  - drivers/clk/clk.c:clk_min_rate_open
  - drivers/clk/clk.c:clk_duty_cycle_open
  - drivers/clk/clk.c:current_parent_open
  - drivers/clk/clk.c:possible_parents_open
  - drivers/clk/clk.c:clk_flags_open
  - drivers/clk/clk.c:clk_dump_open
  - drivers/clk/clk.c:clk_summary_open
  - drivers/regulator/core.c:regulator_summary_open
  - drivers/regulator/core.c:supply_map_open
  - drivers/char/virtio_console.c:port_debugfs_open
  - drivers/base/component.c:component_devices_open
  - drivers/base/dd.c:deferred_devs_open
  - drivers/base/power/domain.c:perf_state_open
  - drivers/base/power/domain.c:devices_open
  - drivers/base/power/domain.c:total_idle_time_open
  - drivers/base/power/domain.c:active_time_open
  - drivers/base/power/domain.c:idle_states_open
  - drivers/base/power/domain.c:sub_domains_open
  - drivers/base/power/domain.c:status_open
  - drivers/base/power/domain.c:summary_open
  - drivers/base/regmap/regcache-rbtree.c:rbtree_open
  - drivers/base/regmap/regmap-debugfs.c:regmap_access_open
  - drivers/mfd/ab3100-core.c:ab3100_registers_open
  - drivers/dma-buf/dma-buf.c:dma_buf_debug_open
  - drivers/dma-buf/sync_debug.c:sync_info_debugfs_open
  - drivers/scsi/sg.c:sg_proc_single_open_dressz
  - drivers/scsi/sg.c:sg_proc_single_open_adio
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_debugfs_open
  - drivers/usb/dwc2/debugfs.c:dr_mode_open
  - drivers/usb/dwc2/debugfs.c:hw_params_open
  - drivers/usb/dwc2/debugfs.c:params_open
  - drivers/usb/host/xhci-debugfs.c:xhci_port_open
  - drivers/usb/host/xhci-debugfs.c:xhci_context_open
  - drivers/usb/host/xhci-debugfs.c:xhci_ring_open
  - drivers/media/cec/cec-core.c:cec_error_inj_open
  - drivers/mmc/core/debugfs.c:mmc_ios_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pkgc_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ltr_ignore_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_pll_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_mphy_pg_open
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_ppfear_open
  - drivers/platform/x86/pmc_atom.c:pmc_sleep_tmr_open
  - drivers/platform/x86/pmc_atom.c:pmc_pss_state_open
  - drivers/platform/x86/pmc_atom.c:pmc_dev_state_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_carveouts_open
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_rsc_table_open
  - drivers/ras/debugfs.c:trace_open
```
**Symbols:**

```
ffffffff8130f740-ffffffff8130f7d7: single_open (STB_GLOBAL)
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
