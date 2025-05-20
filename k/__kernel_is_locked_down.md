# Function: <code>__kernel_is_locked_down</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __kernel_is_locked_down(const char *what, bool first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lock_down.c (ffffffff81425080)
Location: security/lock_down.c:60
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:SyS_iopl
  - arch/x86/kernel/ioport.c:sys_ioperm
  - kernel/power/hibernate.c:hibernation_available
  - kernel/power/user.c:snapshot_open
  - kernel/module.c:load_module
  - kernel/kexec.c:compat_SyS_kexec_load
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:open_proxy_open
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:open_port
```
**Symbols:**

```
ffffffff81425080-ffffffff814250b8: __kernel_is_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool __kernel_is_locked_down(const char *what, bool first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lock_down.c (0)
Location: security/lock_down.c:69
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:hibernation_available
  - kernel/power/user.c:snapshot_open
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/bpf/syscall.c:__ia32_sys_bpf
  - kernel/bpf/syscall.c:__x64_sys_bpf
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_ioctl
  - drivers/char/mem.c:open_port
```
**Symbols:**

```
ffffffff81457ec8-ffffffff81457ef3: __kernel_is_locked_down.cold.0 (STB_LOCAL)
ffffffff81457e80-ffffffff81457ea5: __kernel_is_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool __kernel_is_locked_down(const char *what, bool first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lock_down.c (0)
Location: security/lock_down.c:69
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:hibernation_available
  - kernel/power/user.c:snapshot_open
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/debugfs/inode.c:debugfs_setattr
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info_user
  - drivers/char/mem.c:open_port
```
**Symbols:**

```
ffffffff814753b8-ffffffff814753e3: __kernel_is_locked_down.cold.0 (STB_LOCAL)
ffffffff81475370-ffffffff81475395: __kernel_is_locked_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool __kernel_is_locked_down(const char *what, bool first);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/lock_down.c (0)
Location: security/lock_down.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:__ia32_sys_iopl
  - arch/x86/kernel/ioport.c:__x64_sys_iopl
  - arch/x86/kernel/ioport.c:ksys_ioperm
  - kernel/power/hibernate.c:hibernation_available
  - kernel/power/user.c:snapshot_open
  - kernel/module.c:load_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
  - kernel/kprobes.c:register_kprobe
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/events/core.c:__do_sys_perf_event_open
  - fs/proc/kcore.c:open_kcore
  - fs/debugfs/inode.c:debugfs_setattr
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/tables.c:acpi_table_upgrade
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/tty/serial/serial_core.c:uart_set_info
  - drivers/char/mem.c:open_port
```
**Symbols:**

```
ffffffff814a30c8-ffffffff814a30f3: __kernel_is_locked_down.cold (STB_LOCAL)
ffffffff814a3080-ffffffff814a30a5: __kernel_is_locked_down (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
