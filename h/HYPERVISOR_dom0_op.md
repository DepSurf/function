# Function: <code>HYPERVISOR_dom0_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f6045a)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten.c:xen_check_mwait
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
```
In arch/x86/xen/time.c (ffffffff810235c8)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff81025901)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In drivers/xen/acpi.c (ffffffff814d1ee7)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff814d1f60)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
```
```
In drivers/xen/pcpu.c (ffffffff814d2264)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_down
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff814d5dc5)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff814d66f3)
Location: arch/x86/include/asm/xen/hypercall.h:313
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_get_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_probe
  - drivers/xen/efi.c:xen_efi_probe
  - drivers/xen/efi.c:xen_efi_probe
  - drivers/xen/efi.c:xen_efi_probe
```
</details>
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
