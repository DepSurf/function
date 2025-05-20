# Function: <code>kernel_is_locked_down</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kernel_is_locked_down();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff813fcb60)
Location: security/lock_down.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:SyS_iopl
  - arch/x86/kernel/ioport.c:sys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_open
  - kernel/module.c:load_module
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/trace/bpf_trace.c:bpf_trace_printk
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - kernel/trace/bpf_trace.c:bpf_probe_read
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:open_port
  - drivers/char/mem.c:write_mem
```
**Symbols:**

```
ffffffff813fcb60-ffffffff813fcb72: kernel_is_locked_down (STB_GLOBAL)
```
</details>
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
<b>Regular</b>
<ul>
</ul>
