# Function: <code>HYPERVISOR_platform_op</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81f8894a)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten.c:xen_check_mwait
```
```
In arch/x86/xen/time.c (ffffffff810229f6)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff81024d0d)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/efi.c (ffffffff81f8d078)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff81522c07)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff81522d03)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff81523082)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff81fd1a67)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff81527bba)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81fc3d38)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten.c:xen_check_mwait
```
```
In arch/x86/xen/time.c (ffffffff81023146)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8102542d)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/efi.c (ffffffff81fc848c)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff8154f0e7)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8154f1e3)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8154f562)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8200f402)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff8155413a)
Location: arch/x86/include/asm/xen/hypercall.h:314
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff8101adac)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101be35)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff820a5fe2)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff820a8c05)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff81563639)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff81563739)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff81563caa)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff820f0eb7)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff81568602)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff8101b6ac)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101cb05)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826ac6af)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff826af1f4)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff815c7929)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff815c7a29)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff815c7dfa)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff826fa6c1)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff815cc7b2)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff8101c0b2)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101d51c)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff826d57ef)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff826d8476)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff816001a9)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8160029f)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8160065a)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff827249ca)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff81604f99)
Location: arch/x86/include/asm/xen/hypercall.h:319
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff8101bbf2)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101cdae)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff8288b873)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff8288e4b5)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff8161b279)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8161b36f)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8161b72a)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828dcba3)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff81620079)
Location: arch/x86/include/asm/xen/hypercall.h:286
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff8101d732)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101e8de)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a2ca4)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff828a5a4c)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff8164ef39)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8164f02f)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8164f3aa)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828f7495)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff816535f6)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff8101e032)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101f26e)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a5d57)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff828a8ad3)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff816714e9)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff816715df)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8167195a)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff82900434)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff81675b96)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff81020612)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8102186e)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82ccc04f)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff82cce421)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff81721bae)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff81721c35)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff81722022)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff82d17829)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff81726656)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81021052)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff81021f4c)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7e83)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff82fba27d)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff8173e86e)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8173e8f5)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8173ecd2)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83005417)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff81742bb6)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810233f2)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff810242dc)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff831c25b9)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
```
```
In arch/x86/xen/efi.c (ffffffff831c492a)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff8172238e)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff81722415)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff817228b0)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff8320ffbd)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff817265a6)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810275da)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff810286bc)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff832a2ffa)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
```
```
In arch/x86/xen/efi.c (ffffffff832a5570)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff817a11de)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff817a1265)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff817a1700)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff832f8f92)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff817a5576)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8102b8e8)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8102cd7e)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83452231)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff8345458f)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff818db0b6)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff818db208)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff818db6e1)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff834b1795)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff818df379)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff81032638)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff81033fde)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff83e6f1b6)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff83e71fb7)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff81a2e0c6)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff81a2e258)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff81a2e7e3)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83eeba67)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff81a33709)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff810325d8)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff81033f6e)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff836900fa)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff83692402)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/efi.c (ffffffff83692ec7)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff81a77876)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff81a77a08)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff81a77f93)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff837116a7)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff81a7d7bf)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/efi.c:efi_mem_desc_lookup
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff810388c8)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8103a26e)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff838bfc4a)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
  - arch/x86/xen/enlighten_pv.c:xen_set_mtrr_data
```
```
In arch/x86/xen/enlighten_pvh.c (ffffffff838c1f12)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pvh.c:xen_pvh_init
```
```
In arch/x86/xen/efi.c (ffffffff838c2a37)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff81ac9a86)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff81ac9c18)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff81aca54a)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_sanitize_proc_cap_bits
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff83945037)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
```
```
In drivers/xen/efi.c (ffffffff81acfc5f)
Location: arch/x86/include/asm/xen/hypercall.h:407
Inline: True
Inline callers:
  - drivers/xen/efi.c:efi_mem_desc_lookup
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
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
In arch/arm/xen/enlighten.c (ffff8000100f01a4)
Location: include/xen/arm/hypercall.h:61
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_pvclock_gtod_notify
```
```
In drivers/xen/efi.c (ffff80001083e668)
Location: include/xen/arm/hypercall.h:61
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101e032)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101f3ce)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff82893d60)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff82896ae3)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff816375a9)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8163769f)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff81637a1a)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828e7c51)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff8163b886)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/time.c (ffffffff8101dff2)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101f22e)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6d57)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff828a9ad3)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff81665329)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8166541f)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8166579a)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff828fb757)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff816699d6)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
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
In arch/x86/xen/time.c (ffffffff8101e266)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/time.c:xen_pvclock_gtod_notify
```
```
In arch/x86/xen/apic.c (ffffffff8101f47e)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/apic.c:xen_apic_read
```
```
In arch/x86/xen/enlighten_pv.c (ffffffff828a6d2b)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_boot_params_init_edd
  - arch/x86/xen/enlighten_pv.c:xen_check_mwait
```
```
In arch/x86/xen/efi.c (ffffffff828a9ae3)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
  - arch/x86/xen/efi.c:xen_efi_probe
```
```
In drivers/xen/acpi.c (ffffffff8167f8d9)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/acpi.c:xen_acpi_notify_hypervisor_state
```
```
In drivers/xen/xen-acpi-pad.c (ffffffff8167f9cf)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus_num
  - drivers/xen/xen-acpi-pad.c:xen_acpi_pad_idle_cpus
```
```
In drivers/xen/pcpu.c (ffffffff8167fd4a)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:xen_pcpu_id
  - drivers/xen/pcpu.c:sync_pcpu
  - drivers/xen/pcpu.c:xen_pcpu_up
  - drivers/xen/pcpu.c:xen_pcpu_down
```
```
In drivers/xen/xen-acpi-processor.c (ffffffff82901488)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:get_max_acpi_id
  - drivers/xen/xen-acpi-processor.c:push_pxx_to_hypervisor
  - drivers/xen/xen-acpi-processor.c:push_cxx_to_hypervisor
```
```
In drivers/xen/efi.c (ffffffff81683f96)
Location: arch/x86/include/asm/xen/hypercall.h:305
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_query_capsule_caps
  - drivers/xen/efi.c:xen_efi_update_capsule
  - drivers/xen/efi.c:xen_efi_get_next_high_mono_count
  - drivers/xen/efi.c:xen_efi_query_variable_info
  - drivers/xen/efi.c:xen_efi_set_variable
  - drivers/xen/efi.c:xen_efi_get_next_variable
  - drivers/xen/efi.c:xen_efi_get_variable
  - drivers/xen/efi.c:xen_efi_set_wakeup_time
  - drivers/xen/efi.c:xen_efi_get_wakeup_time
  - drivers/xen/efi.c:xen_efi_set_time
  - drivers/xen/efi.c:xen_efi_get_time
```
</details>
</li>
</ul>

## Differences
