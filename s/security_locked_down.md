# Function: <code>security_locked_down</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455690)
Location: security/security.c:2608
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff81455690-ffffffff814556ca: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7ec0)
Location: security/security.c:2979
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff814a7ec0-ffffffff814a7efa: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5440)
Location: security/security.c:2997
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_compat
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel_str
  - kernel/trace/bpf_trace.c:bpf_probe_read_kernel
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff814c5440-ffffffff814c547a: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cb930)
Location: security/security.c:3060
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff814cb930-ffffffff814cb96a: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524630)
Location: security/security.c:3068
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff81524630-ffffffff8152466a: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8710)
Location: security/security.c:3146
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_check_unsafe
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/module/signing.c:module_sig_check
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_init_dentry
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - security/integrity/ima/ima_policy.c:ima_appraise_signature
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff815b8710-ffffffff815b875d: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81663d20)
Location: security/security.c:3126
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_check_unsafe
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/module/signing.c:module_sig_check
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_init_dentry
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - security/integrity/ima/ima_policy.c:ima_appraise_signature
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff81663d20-ffffffff81663d6d: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c220)
Location: security/security.c:5589
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_check_unsafe
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
  - kernel/module/signing.c:module_sig_check
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_init_dentry
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - security/integrity/ima/ima_policy.c:ima_appraise_signature
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff8169c220-ffffffff8169c26d: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d8ec0)
Location: security/security.c:5730
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/params.c:param_check_unsafe
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
  - kernel/module/signing.c:module_sig_check
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_prepare_segments
  - kernel/debug/debug_core.c:kgdb_cpu_enter
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:late_trace_init
  - kernel/trace/trace.c:tracing_init_dentry
  - kernel/trace/trace.c:tracing_open_options
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_mark_open
  - kernel/trace/trace.c:tracing_open_file_tr
  - kernel/trace/trace.c:tracing_open_generic
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/bpf/helpers.c:bpf_base_func_proto
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - security/integrity/ima/ima_policy.c:ima_appraise_signature
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff816d8ec0-ffffffff816d8f0d: security_locked_down (STB_GLOBAL)
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
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540b70)
Location: security/security.c:2608
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:__arm64_sys_kexec_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/syscall.c:__arm64_sys_pciconfig_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffff800010540b70-ffff800010540bc0: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6bd4)
Location: security/security.c:2608
Inline: False
Direct callers:
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__se_sys_kexec_load
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/debugfs/file.c:debugfs_locked_down
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_mmap_resource
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
```
**Symbols:**

```
c06f6bd4-c06f6c28: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000692bb0)
Location: security/security.c:2608
Inline: False
Direct callers:
  - arch/powerpc/xmon/xmon.c:xmon_is_locked_down
  - arch/powerpc/xmon/xmon.c:xmon_is_locked_down
  - kernel/module.c:load_module
  - kernel/kexec.c:__se_compat_sys_kexec_load
  - kernel/kexec.c:__se_sys_kexec_load
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/debugfs/file.c:debugfs_locked_down
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/pci/syscall.c:__se_sys_pciconfig_write
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
```
**Symbols:**

```
c000000000692bb0-c000000000692c58: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039daec)
Location: security/security.c:2608
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/debugfs/file.c:debugfs_locked_down
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
```
**Symbols:**

```
ffffffe00039daec-ffffffe00039db28: security_locked_down (STB_GLOBAL)
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
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dc70)
Location: security/security.c:2608
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff8144dc70-ffffffff8144dcaa: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e6c0)
Location: security/security.c:2608
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff8143e6c0-ffffffff8143e6fa: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449d10)
Location: security/security.c:2608
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff81449d10-ffffffff81449d4a: security_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_locked_down(enum lockdown_reason what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814610e0)
Location: security/security.c:2608
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/trace.c:tracing_set_default_clock
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_stat.c:tracing_stat_open
  - kernel/trace/trace_events_trigger.c:event_trigger_open
  - kernel/trace/bpf_trace.c:bpf_probe_read_str
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - fs/tracefs/inode.c:tracefs_create_file
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
  - drivers/firmware/efi/efi.c:efivar_ssdt_setup
```
**Symbols:**

```
ffffffff814610e0-ffffffff8146111a: security_locked_down (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
