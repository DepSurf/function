# Function: <code>efi_enabled</code>

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
In init/main.c (ffffffff81f59f79)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/setup.c (ffffffff81f65f5f)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8105e0ae)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81f79a6e)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
```
```
In arch/x86/platform/efi/efi.c (ffffffff81f79d80)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_mem_type
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7ac21)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_runtime_mkexec
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
```
```
In fs/efivarfs/super.c (ffffffff81f97c41)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/acpi/osl.c (ffffffff81fa11af)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fb5a35)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fb61a8)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi.c (ffffffff816d04fa)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_mem_attributes
```
```
In drivers/firmware/efi/reboot.c (ffffffff816d2105)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_reboot
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
```
```
In drivers/firmware/efi/efivars.c (ffffffff816d3236)
Location: include/linux/efi.h:996
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff816d36c5)
Location: include/linux/efi.h:996
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/main.c (ffffffff81f81f3b)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/setup.c (ffffffff81f8ddd8)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81f95cac)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8105e6ec)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81fa21ff)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff8107a415)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_mem_type
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107a79b)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In kernel/sysctl.c (ffffffff8108b6ab)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - kernel/sysctl.c:moksbstate_disabled_proc_handler
  - kernel/sysctl.c:secure_boot_proc_handler
```
```
In kernel/modsign_uefi.c (ffffffff81faa14f)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - kernel/modsign_uefi.c:load_uefi_certs
```
```
In fs/efivarfs/super.c (ffffffff81fc2840)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/acpi/osl.c (ffffffff81fcd27d)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff81fe2f38)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff81fe36ad)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi.c (ffffffff81733af5)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff81fe4370)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff81fe4467)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/efivars.c (ffffffff81735ff2)
Location: include/linux/efi.h:1052
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff81fe4838)
Location: include/linux/efi.h:1052
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
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
In init/main.c (ffffffff81fbdf89)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/setup.c (ffffffff81fc916f)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81fd114b)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8106176f)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81fdd840)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff8107e1f5)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_mem_type
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107e5f6)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In kernel/sysctl.c (ffffffff810905fb)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - kernel/sysctl.c:moksbstate_disabled_proc_handler
  - kernel/sysctl.c:secure_boot_proc_handler
```
```
In kernel/modsign_uefi.c (ffffffff81fe615b)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - kernel/modsign_uefi.c:load_uefi_certs
```
```
In fs/efivarfs/super.c (ffffffff81fff25a)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/acpi/osl.c (ffffffff8200a275)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff82020d07)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8202147c)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi.c (ffffffff81766b95)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff820220ac)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff820221a3)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff8202242e)
Location: include/linux/efi.h:1105
Inline: True
```
```
In drivers/firmware/efi/efivars.c (ffffffff81769252)
Location: include/linux/efi.h:1105
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff8202297a)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82022db4)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In init/main.c (ffffffff8209e076)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/setup.c (ffffffff820a98d3)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff820b1ca2)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81060617)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/platform/efi/quirks.c (ffffffff820be69d)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff8107c5a5)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_mem_type
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8107cc06)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff820e251a)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/acpi/osl.c (ffffffff820eb967)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff82103828)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8210402e)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff821041a8)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff817854c5)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff82104dd6)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff82104edd)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff8210515c)
Location: include/linux/efi.h:1124
Inline: True
```
```
In drivers/firmware/efi/efivars.c (ffffffff81787dc2)
Location: include/linux/efi.h:1124
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff82105681)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82105aae)
Location: include/linux/efi.h:1124
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
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
In init/main.c (ffffffff826a4048)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/setup.c (ffffffff826b05e7)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826b850a)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81064667)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/mm/ioremap.c (ffffffff81074185)
Location: include/linux/efi.h:1156
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff826c67c2)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff826c7778)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81083ae6)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff826eb176)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In security/lock_down.c (ffffffff826ee3cd)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - security/lock_down.c:init_lockdown
```
```
In drivers/acpi/osl.c (ffffffff826f4832)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff8270cf09)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8270d70f)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff8270d889)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff817fb8b5)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff817fcfad)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff8270e5a6)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff8270e825)
Location: include/linux/efi.h:1156
Inline: True
```
```
In drivers/firmware/efi/efivars.c (ffffffff817fe262)
Location: include/linux/efi.h:1156
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff8270ed4a)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8270f177)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/secureboot.c (ffffffff8270f649)
Location: include/linux/efi.h:1156
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff826cd13a)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - init/main.c:start_kernel
  - init/main.c:start_kernel
```
```
In arch/x86/kernel/setup.c (ffffffff826d9c88)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff826e2214)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810672c2)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/mm/ioremap.c (ffffffff81076b75)
Location: include/linux/efi.h:1196
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff826f08cc)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff826f186e)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810866ca)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_query_variable_info
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff82715661)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In security/lock_down.c (ffffffff82718994)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - security/lock_down.c:init_lockdown
```
```
In drivers/acpi/osl.c (ffffffff8271e835)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff827371b3)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff827379bd)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff82737b24)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81845025)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff82738706)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff8273881b)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff82738ae4)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
```
```
In drivers/firmware/efi/efivars.c (ffffffff818479e2)
Location: include/linux/efi.h:1196
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff82739004)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff827393e3)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81849a84)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
```
```
In drivers/firmware/efi/secureboot.c (ffffffff827398f1)
Location: include/linux/efi.h:1196
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff82883120)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288ea17)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff82890076)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82898b62)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8106d2e9)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/ima_arch.c (ffffffff81078bea)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
```
In arch/x86/mm/ioremap.c (ffffffff8107d205)
Location: include/linux/efi.h:1205
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff8108d14f)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828a8612)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108d98a)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff828ccb09)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In security/lock_down.c (ffffffff828d09f9)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - security/lock_down.c:init_lockdown
```
```
In drivers/acpi/osl.c (ffffffff828d6860)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f10df)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f18e9)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff828f1a53)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81871145)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff828f26b2)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff828f27c7)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff828f2a90)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffffffff81873a72)
Location: include/linux/efi.h:1205
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff828f2fbf)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff828f33b2)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81875869)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff828f38c0)
Location: include/linux/efi.h:1205
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff8289a176)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a5fbc)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff828a7860)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b0765)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e772)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8107133d)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/ima_arch.c (ffffffff8107c75a)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
```
In arch/x86/mm/ioremap.c (ffffffff81080ab5)
Location: include/linux/efi.h:1220
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff8109100d)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c1147)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8109183a)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff828e6493)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In security/lock_down.c (ffffffff828ea795)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - security/lock_down.c:init_lockdown
```
```
In drivers/video/fbdev/efifb.c (ffffffff815b3030)
Location: include/linux/efi.h:1220
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff828f06e8)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff8290c6dc)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_setup
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8290cf3e)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff8290d0b7)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff818b53d5)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff8290dd1f)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff8290de3b)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff8290e37d)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffffffff818b7c73)
Location: include/linux/efi.h:1220
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff8290e8d9)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8290ecc3)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818b9a59)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff8290f1cd)
Location: include/linux/efi.h:1220
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff8289d15b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a8fc4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff828aa89b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b3bad)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fd22)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8107233d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/ima_arch.c (ffffffff8107d84a)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
```
In arch/x86/mm/ioremap.c (ffffffff81081b75)
Location: include/linux/efi.h:1221
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81091d0d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c75ce)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff810925df)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff81097f3f)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In fs/efivarfs/super.c (ffffffff828eef4c)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/video/fbdev/efifb.c (ffffffff815d3fb7)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff828f9852)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff829160af)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_setup
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82916911)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff82916a7e)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff818e7d75)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff8291771b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff82917837)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff82917d96)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffffffff818ea663)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff829182b3)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82918692)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818ec4f9)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff82918b9c)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff82cc36b7)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82cce825)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff82ccfc60)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82cd8c57)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074f0c)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:check_efi_reboot
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810771c7)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81078f58)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/mm/ioremap.c (ffffffff81088b25)
Location: include/linux/efi.h:809
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff810975bd)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff810977be)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
  - arch/x86/platform/efi/efi.c:efi_find_mirror
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82ceb0cb)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff82cec099)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:arch_parse_efi_cmdline
```
```
In drivers/video/fbdev/efifb.c (ffffffff8167de76)
Location: include/linux/efi.h:809
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff82d1096a)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff82d284e6)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82d28dba)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff82d28eba)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff819bb075)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff82d29f19)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff82d2a515)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff819be8a5)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82d2abc9)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819bfe29)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff82d2aff3)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff82faf76e)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82fba69f)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff82fbba91)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82fc5075)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd7971)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:check_efi_reboot
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810777f7)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81078f48)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/mm/ioremap.c (ffffffff81088d65)
Location: include/linux/efi.h:814
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff82fd7252)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff810969ee)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:do_add_efi_memmap
  - arch/x86/platform/efi/efi.c:efi_find_mirror
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd894e)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In drivers/video/fbdev/efifb.c (ffffffff81c00099)
Location: include/linux/efi.h:814
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff82ffe450)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff83016bfe)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff830174d2)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff830175d2)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff819bd2d5)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff8301863e)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff83018c2f)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff819c0255)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff830192fa)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819c14f9)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/firmware/efi/secureboot.c (ffffffff83019727)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff8301a165)
Location: include/linux/efi.h:814
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
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
In init/main.c (ffffffff831b9796)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff831c4d30)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff831c612e)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff831cf975)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc9927)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:check_efi_reboot
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81078287)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81079ee8)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/mm/ioremap.c (ffffffff810899f5)
Location: include/linux/efi.h:809
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff831e1c99)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff8109730e)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_find_mirror
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff831e333e)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In drivers/video/fbdev/efifb.c (ffffffff81bf1b97)
Location: include/linux/efi.h:809
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff83209204)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff83221bf7)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff83222344)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff832224b1)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff819a1a65)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff8322351d)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff83223c27)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff819a4965)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff832242dc)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff819a58e9)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/firmware/efi/secureboot.c (ffffffff8322476f)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff832251ad)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
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
In init/main.c (ffffffff83299b18)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff832a5adc)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff832a7058)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff832b1dd7)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81c9e66f)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:check_efi_reboot
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085ab9)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81088048)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/mm/ioremap.c (ffffffff81098e95)
Location: include/linux/efi.h:809
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff832c55a7)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff810a728e)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_map_regions
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_find_mirror
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6ce1)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In drivers/video/fbdev/efifb.c (ffffffff81cee5c9)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/osl.c (ffffffff832f14cf)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff8330b645)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8330bfb0)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff8330c17d)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81a4ea25)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff8330d323)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff8330da2d)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff81a51c15)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff8330e0d6)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81a52ef9)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
```
```
In drivers/firmware/efi/secureboot.c (ffffffff8330e569)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff8330effd)
Location: include/linux/efi.h:809
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
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
In init/main.c (ffffffff83447d48)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83454a8b)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff83456337)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff834630a5)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346e356)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095eb1)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81097c78)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/kernel/kvm.c (ffffffff8346ff8a)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
```
```
In arch/x86/mm/ioremap.c (ffffffff810ab6ae)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
```
```
In arch/x86/platform/efi/quirks.c (ffffffff83478158)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff810bc618)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_find_mirror
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83479ab4)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In security/integrity/ima/ima_efi.c (ffffffff816489af)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
```
In drivers/video/fbdev/efifb.c (ffffffff81eb5cdf)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/osl.c (ffffffff834a9541)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff834c4afd)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff834c58e2)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff834c5b68)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81bbd665)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff834c6e2a)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff834c77a8)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff81bc0ba5)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff834c7ebf)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81bc1879)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/efi/secureboot.c (ffffffff834c82af)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff834c8d94)
Location: include/linux/efi.h:876
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
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
In init/main.c (ffffffff83e6141b)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83e72605)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff83e7470b)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff83e8572f)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e943be)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abb11)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810ae078)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/kernel/kvm.c (ffffffff83e968e6)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
```
```
In arch/x86/mm/ioremap.c (ffffffff810c501e)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
```
```
In arch/x86/platform/efi/memmap.c (ffffffff83ea1602)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_install
```
```
In arch/x86/platform/efi/quirks.c (ffffffff83ea1f41)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff810d7b58)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3e20)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff83ea3f35)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
```
In security/integrity/ima/ima_efi.c (ffffffff8170177f)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
```
In drivers/video/fbdev/efifb.c (ffffffff81951f93)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/osl.c (ffffffff83ee0fa0)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/acpi/prmt.c (ffffffff83ee3c0f)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/firmware/dmi_scan.c (ffffffff83f04faa)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff83f06531)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff83f06883)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81d63335)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_find_mirror
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff83f08066)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff83f089f5)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff83f08b65)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81d661b9)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/efi/secureboot.c (ffffffff83f09445)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff83f0a3e4)
Location: include/linux/efi.h:878
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
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
In init/main.c (ffffffff836818a2)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff83693525)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff836961d8)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff836a8c5a)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b7f1e)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af6d1)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810b1078)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/kernel/kvm.c (ffffffff836ba47a)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
```
```
In arch/x86/mm/ioremap.c (ffffffff810c87ac)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
```
```
In arch/x86/platform/efi/memmap.c (ffffffff836c5842)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_install
```
```
In arch/x86/platform/efi/quirks.c (ffffffff836c61a1)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff810e30e8)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff836c80d0)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff836c8215)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
```
In security/integrity/ima/ima_efi.c (ffffffff8173b81f)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
```
In drivers/video/fbdev/efifb.c (ffffffff8199841c)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/video/fbdev/efifb.c:efifb_probe
```
```
In drivers/acpi/osl.c (ffffffff83706960)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/acpi/prmt.c (ffffffff837095ef)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/xen/efi.c (ffffffff83711b13)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_config_table_is_usable
  - drivers/xen/efi.c:efi_mem_desc_lookup
  - drivers/xen/efi.c:efi_mem_desc_lookup
```
```
In drivers/firmware/dmi_scan.c (ffffffff8372af5a)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff8372c507)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff8372c8b3)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81dce415)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/efi.c:__efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_find_mirror
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff8372e189)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff8372eb35)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff8372eca5)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81dd12c9)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/efi/secureboot.c (ffffffff8372f565)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff83730504)
Location: include/linux/efi.h:898
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
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
In init/main.c (ffffffff838b08c7)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff838c3095)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff838c5e29)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff838d921a)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e885e)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b6261)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810b8328)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
```
```
In arch/x86/kernel/kvm.c (ffffffff838eadea)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_init_platform
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
  - arch/x86/kernel/kvm.c:setup_efi_kvm_sev_migration
```
```
In arch/x86/mm/ioremap.c (ffffffff810d0c7c)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
```
```
In arch/x86/platform/efi/memmap.c (ffffffff838f6442)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/platform/efi/memmap.c:efi_memmap_install
```
```
In arch/x86/platform/efi/quirks.c (ffffffff838f6da1)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff810eb938)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_attr_is_visible
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:kexec_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_systab_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff838f8cd0)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_set_virtual_address_map
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff838f8e15)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - arch/x86/platform/efi/runtime-map.c:efi_runtime_map_init
```
```
In security/integrity/platform_certs/machine_keyring.c (ffffffff8392d335)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - security/integrity/platform_certs/machine_keyring.c:imputed_trust_enabled
  - security/integrity/platform_certs/machine_keyring.c:add_to_machine_keyring
```
```
In security/integrity/ima/ima_efi.c (ffffffff8177c3df)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
```
In drivers/acpi/osl.c (ffffffff83939ee0)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/acpi/prmt.c (ffffffff8393ca7f)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:init_prmt
  - drivers/acpi/prmt.c:acpi_platformrt_space_handler
```
```
In drivers/xen/efi.c (ffffffff839454a3)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/xen/efi.c:xen_efi_config_table_is_usable
  - drivers/xen/efi.c:efi_mem_desc_lookup
  - drivers/xen/efi.c:efi_mem_desc_lookup
```
```
In drivers/firmware/dmi_scan.c (ffffffff8395ef1a)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff83960527)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:reserve_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff83960c93)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff81e87115)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/efi.c:__efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efi_find_mirror
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:fw_platform_size_show
  - drivers/firmware/efi/efi.c:__efi_soft_reserve_enabled
```
```
In drivers/firmware/efi/memattr.c (ffffffff83962589)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff83962f35)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/esrt.c (ffffffff839630a4)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81e8a053)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:__efi_queue_work
```
```
In drivers/firmware/efi/secureboot.c (ffffffff83963a65)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff83964a64)
Location: include/linux/efi.h:892
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_table_init
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
In arch/arm64/kernel/process.c (ffff800010089094)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:machine_restart
```
```
In arch/arm64/kernel/efi.c (ffff8000100a77f8)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/arm64/kernel/efi.c:efi_poweroff_required
```
```
In arch/arm/xen/enlighten.c (ffff80001143a7b4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/arm/xen/enlighten.c:xen_guest_init
```
```
In fs/efivarfs/super.c (ffff800011468b70)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800011474900)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
```
```
In drivers/video/fbdev/efifb.c (ffff80001075e644)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/acpi/osl.c (ffff80001147ca74)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/rtc/rtc-efi-platform.c (ffff80001149dc80)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/rtc/rtc-efi-platform.c:rtc_init
```
```
In drivers/firmware/dmi_scan.c (ffff8000114a3f64)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/efi/efi-bgrt.c (ffff8000114a4fb0)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffff800010b5aea8)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffff8000114a5f78)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffff8000114a60f8)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffff8000114a6684)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffff800010b5db14)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffff8000114a6d28)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffff800010b5f6d4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/efi/secureboot.c (ffff8000114a7130)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/arm-init.c (ffff8000114a76bc)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/firmware/efi/arm-init.c:reserve_regions
```
```
In drivers/firmware/efi/arm-runtime.c (ffff8000114a7814)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
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
In fs/efivarfs/super.c (c1541678)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (c154cda4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
```
```
In drivers/video/fbdev/efifb.c (c08e1414)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/rtc/rtc-efi-platform.c (c15a02b8)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/rtc/rtc-efi-platform.c:rtc_init
```
```
In drivers/firmware/dmi_scan.c (c15a6670)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_scan_machine
```
```
In drivers/firmware/efi/efi.c (c0c3baac)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:fdt_find_uefi_params
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (c15a8238)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (c15a8390)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (c15a8a1c)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (c0c3e850)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/firmware/efi/esrt.c (c15a9340)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (c0c3ed74)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
```
```
In drivers/firmware/efi/secureboot.c (c15a97bc)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/firmware/efi/arm-init.c (c15a9dfc)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-init.c:efi_init
  - drivers/firmware/efi/arm-init.c:reserve_regions
  - drivers/firmware/efi/arm-init.c:reserve_regions
```
```
In drivers/firmware/efi/arm-runtime.c (c15a9f80)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
  - drivers/firmware/efi/arm-runtime.c:arm_enable_runtime_services
```
</details>
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
In init/main.c (ffffffff8288b15b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff82896fd4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff828988ab)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828a1bcc)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ecc2)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8107133d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/ima_arch.c (ffffffff8107c84a)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
```
In arch/x86/mm/ioremap.c (ffffffff81080b75)
Location: include/linux/efi.h:1221
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81090ccd)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828b2566)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8109159f)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff828d7e00)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c7fc3)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff828e2590)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff828fb603)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_setup
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828fbe65)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi.c (ffffffff8188aaf5)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff828fcb21)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff828fcc3d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff828fd19c)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffffffff8188d3e3)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff828fd6b9)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff828fda98)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff8188e0d9)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff828fdfa2)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff828890ec)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff8288f2f0)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff82890bbb)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff82899cba)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ed6b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8106134d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/ima_arch.c (ffffffff8106bfba)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
```
In arch/x86/mm/ioremap.c (ffffffff8106fac5)
Location: include/linux/efi.h:1221
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff8107f7dd)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828aa6d8)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8108005f)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff828d051c)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/acpi/osl.c (ffffffff828da5a9)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff828f2e9f)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_setup
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff828f3701)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi.c (ffffffff81842475)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff828f43bd)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff828f44d9)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff828f4a38)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffffffff81844d63)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff828f4f55)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff828f5334)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff81846bf9)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff828f583e)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184e4d0)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_acpi_add
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
In init/main.c (ffffffff8289e15b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a9fc4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff828ab89b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4b8f)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f172)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810712ed)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/ima_arch.c (ffffffff8107c7fa)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
```
In arch/x86/mm/ioremap.c (ffffffff81080b25)
Location: include/linux/efi.h:1221
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff81090c7d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c5465)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff8109154f)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In fs/efivarfs/super.c (ffffffff828eab80)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/video/fbdev/efifb.c (ffffffff815c8553)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff828f544e)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff829106e4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_setup
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82910f46)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff829110b3)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff818dcbd5)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff82911d50)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff82911e6c)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff829123cb)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffffffff818df4c3)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff829128e8)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff82912cc7)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818e1359)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff829131d1)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
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
In init/main.c (ffffffff8289e162)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - init/main.c:start_kernel
```
```
In arch/x86/hyperv/hv_init.c (ffffffff828a9fd4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_pci_init
```
```
In arch/x86/kernel/setup.c (ffffffff828ab8ab)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/kernel/setup.c:setup_arch
```
```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff828b4bb0)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810713f2)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8107334d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_probe
```
```
In arch/x86/kernel/ima_arch.c (ffffffff8107e8fa)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
```
In arch/x86/mm/ioremap.c (ffffffff81082c45)
Location: include/linux/efi.h:1221
Inline: True
```
```
In arch/x86/platform/efi/quirks.c (ffffffff8109305d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/quirks.c:efi_recover_from_page_fault
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_free_boot_services
  - arch/x86/platform/efi/quirks.c:efi_reuse_config
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
  - arch/x86/platform/efi/quirks.c:efi_apply_memmap_quirks
```
```
In arch/x86/platform/efi/efi.c (ffffffff828c860b)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:__efi_enter_virtual_mode
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_init
  - arch/x86/platform/efi/efi.c:efi_memblock_x86_reserve_range
```
```
In arch/x86/platform/efi/efi_64.c (ffffffff81093986)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_reset_system
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_high_mono_count
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_next_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable_nonblocking
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_variable
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_wakeup_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_set_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_thunk_get_time
  - arch/x86/platform/efi/efi_64.c:efi_sync_low_kernel_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_runtime_update_mappings
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_setup_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_alloc_page_tables
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_epilog
  - arch/x86/platform/efi/efi_64.c:efi_call_phys_prolog
```
```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099406)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
  - arch/x86/platform/uv/bios_uv.c:__uv_bios_call
```
```
In fs/efivarfs/super.c (ffffffff828eff96)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init
```
```
In drivers/video/fbdev/efifb.c (ffffffff815e20f7)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/acpi/osl.c (ffffffff828fa8a6)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_get_root_pointer
```
```
In drivers/firmware/dmi_scan.c (ffffffff82917111)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/dmi_scan.c:dmi_setup
```
```
In drivers/firmware/iscsi_ibft_find.c (ffffffff82917973)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/iscsi_ibft_find.c:find_ibft_region
```
```
In drivers/firmware/efi/efi-bgrt.c (ffffffff82917ae0)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
```
In drivers/firmware/efi/efi.c (ffffffff818f96e5)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_type
  - drivers/firmware/efi/efi.c:efi_mem_attributes
  - drivers/firmware/efi/efi.c:efi_config_init
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - drivers/firmware/efi/efi.c:efi_mem_desc_lookup
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efi_attr_is_visible
  - drivers/firmware/efi/efi.c:fw_platform_size_show
```
```
In drivers/firmware/efi/reboot.c (ffffffff8291877d)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/reboot.c:efi_shutdown_init
  - drivers/firmware/efi/reboot.c:efi_reboot
```
```
In drivers/firmware/efi/memattr.c (ffffffff82918899)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
  - drivers/firmware/efi/memattr.c:efi_memattr_apply_permissions
```
```
In drivers/firmware/efi/memmap.c (ffffffff82918df8)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/memmap.c:__efi_memmap_init
  - drivers/firmware/efi/memmap.c:efi_memmap_unmap
```
```
In drivers/firmware/efi/efivars.c (ffffffff818fbf63)
Location: include/linux/efi.h:1221
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff82919315)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/esrt.c:esrt_attr_is_visible
  - drivers/firmware/efi/esrt.c:efi_esrt_init
```
```
In drivers/firmware/efi/runtime-map.c (ffffffff829196f4)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
```
```
In drivers/firmware/efi/runtime-wrappers.c (ffffffff818fddf9)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_capsule_caps
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_update_capsule
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_query_variable_info
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time
  - drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_rts
```
```
In drivers/firmware/efi/secureboot.c (ffffffff82919bfe)
Location: include/linux/efi.h:1221
Inline: True
Inline callers:
  - drivers/firmware/efi/secureboot.c:efi_set_secure_boot
```
</details>
</li>
</ul>

## Differences
