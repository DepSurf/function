# Function: <code>secure_modules</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool secure_modules();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81104910)
Location: kernel/module.c:4119
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:sys_ioperm
  - arch/x86/kernel/ioport.c:SyS_iopl
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
  - kernel/kexec.c:compat_SyS_kexec_load
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_mem
```
**Symbols:**

```
ffffffff81104910-ffffffff81104931: secure_modules (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool secure_modules();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110bdd0)
Location: kernel/module.c:4290
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:SyS_iopl
  - arch/x86/kernel/ioport.c:sys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/kexec.c:compat_SyS_kexec_load
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_mem
```
**Symbols:**

```
ffffffff8110bdd0-ffffffff8110bdf1: secure_modules (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool secure_modules();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811137c0)
Location: kernel/module.c:4311
Inline: False
Direct callers:
  - arch/x86/kernel/ioport.c:SyS_iopl
  - arch/x86/kernel/ioport.c:sys_ioperm
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/kexec.c:compat_SyS_kexec_load
  - kernel/bpf/syscall.c:SyS_bpf
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/proc.c:proc_bus_pci_mmap
  - drivers/pci/proc.c:proc_bus_pci_ioctl
  - drivers/pci/proc.c:proc_bus_pci_write
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
  - drivers/char/mem.c:write_port
  - drivers/char/mem.c:write_mem
```
**Symbols:**

```
ffffffff811137c0-ffffffff811137e1: secure_modules (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
