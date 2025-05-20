# Function: <code>kstrtobool</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814495f0)
Location: lib/kstrtox.c:333
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - fs/debugfs/file.c:debugfs_write_file_bool
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/usb/core/hcd.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff814495f0-ffffffff81449638: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81467fe0)
Location: lib/kstrtox.c:329
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/ksm.c:use_zero_pages_store
  - fs/debugfs/file.c:debugfs_write_file_bool
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/usb/core/hcd.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff81467fe0-ffffffff81468028: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8146d6f0)
Location: lib/kstrtox.c:331
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/ksm.c:use_zero_pages_store
  - fs/debugfs/file.c:debugfs_write_file_bool
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/usb/core/hcd.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff8146d6f0-ffffffff8146d738: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81499a20)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/ksm.c:use_zero_pages_store
  - fs/debugfs/file.c:debugfs_write_file_bool
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/hcd.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff81499a20-ffffffff81499a6e: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814cecd0)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/hcd.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff814cecd0-ffffffff814ced17: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff814e35c0)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/hcd.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff814e35c0-ffffffff814e362e: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8150f970)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pci-sysfs.c:sriov_drivers_autoprobe_store
  - drivers/pci/pcie/aspm.c:clk_ctl_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff8150f970-ffffffff8150fa04: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8152d870)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - arch/x86/platform/uv/tlb_uv.c:setup_bau
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/md/md.c:fail_last_dev_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff8152d870-ffffffff8152d904: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8159167a)
Location: lib/kstrtox.c:332
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtobool_from_user
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - arch/x86/platform/uv/tlb_uv.c:setup_bau
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff81591580-ffffffff81591614: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815ae1ba)
Location: lib/kstrtox.c:328
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtobool_from_user
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/reboot.c:force_store
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/roles/class.c:role_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/input/input.c:inhibited_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/cpufreq/intel_pstate.c:store_energy_efficiency
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff815ae0c0-ffffffff815ae154: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff815b97aa)
Location: lib/kstrtox.c:335
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtobool_from_user
Direct callers:
  - init/main.c:set_debug_rodata
  - init/main.c:early_randomize_kstack_offset
  - init/initramfs.c:initramfs_async_setup
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/reboot.c:force_store
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/roles/class.c:role_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/input/input.c:inhibited_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/cpufreq/intel_pstate.c:store_energy_efficiency
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff815b8d50-ffffffff815b8de4: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816200d4)
Location: lib/kstrtox.c:336
Inline: True
Inline callers:
  - lib/kstrtox.c:kstrtobool_from_user
Direct callers:
  - init/main.c:set_debug_rodata
  - init/main.c:early_randomize_kstack_offset
  - init/initramfs.c:initramfs_async_setup
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/reboot.c:force_store
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/roles/class.c:role_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/input/input.c:inhibited_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/cpufreq/intel_pstate.c:store_energy_efficiency
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff8161f5a0-ffffffff8161f634: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff816ed920)
Location: lib/kstrtox.c:348
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - init/initramfs.c:initramfs_async_setup
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/signal.c:strict_sas_size
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/reboot.c:force_store
  - kernel/sched/build_utility.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/swap_state.c:vma_ra_enabled_store
  - mm/hugetlb_vmemmap.c:hugetlb_vmemmap_early_param
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/migrate.c:numa_demotion_enabled_store
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - lib/stackdepot.c:is_stack_depot_disabled
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_bootloader
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/roles/class.c:role_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/input/input.c:inhibited_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/cpufreq/intel_pstate.c:store_energy_efficiency
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff816ed920-ffffffff816ed9d9: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff817de330)
Location: lib/kstrtox.c:348
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - init/initramfs.c:initramfs_async_setup
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:parse_xen_msr_safe
  - arch/x86/kernel/signal.c:strict_sas_size
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/reboot.c:force_store
  - kernel/sched/build_utility.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/swap_state.c:vma_ra_enabled_store
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/memory-tiers.c:numa_demotion_enabled_store
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - lib/stackdepot.c:is_stack_depot_disabled
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_bootloader
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:early_stop_store
  - drivers/usb/roles/class.c:role_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/input/input.c:inhibited_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/cpufreq/intel_pstate.c:store_energy_efficiency
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff817de330-ffffffff817de3e9: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8181db20)
Location: lib/kstrtox.c:348
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - init/initramfs.c:initramfs_async_setup
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:parse_xen_msr_safe
  - arch/x86/kernel/signal.c:strict_sas_size
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/cpu.c:parallel_bringup_parse_param
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/reboot.c:force_store
  - kernel/sched/build_utility.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/mm_init.c:early_init_on_free
  - mm/mm_init.c:early_init_on_alloc
  - mm/swap_state.c:vma_ra_enabled_store
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/memory-tiers.c:numa_demotion_enabled_store
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - lib/stackdepot.c:disable_stack_depot
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_bootloader
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
  - drivers/base/firmware_loader/sysfs_upload.c:cancel_store
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_cdl_enable
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:early_stop_store
  - drivers/usb/roles/class.c:role_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/input/input.c:inhibited_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/cpufreq/intel_pstate.c:store_energy_efficiency
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff8181db20-ffffffff8181dbc2: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81863990)
Location: lib/kstrtox.c:348
Inline: False
Direct callers:
  - init/main.c:early_randomize_kstack_offset
  - init/initramfs.c:initramfs_async_setup
  - arch/x86/entry/common.c:ia32_emulation_override_cmdline
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/xen/enlighten_pv.c:parse_xen_msr_safe
  - arch/x86/kernel/signal.c:strict_sas_size
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/cpu.c:parallel_bringup_parse_param
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/reboot.c:force_store
  - kernel/sched/build_utility.c:setup_psi
  - kernel/rcu/tree.c:param_set_do_rcu_barrier
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - kernel/cgroup/cgroup.c:cgroup_favordynmods_setup
  - mm/mm_init.c:early_init_on_free
  - mm/mm_init.c:early_init_on_alloc
  - mm/memory_hotplug.c:set_memmap_mode
  - mm/swap_state.c:vma_ra_enabled_store
  - mm/ksm.c:smart_scan_store
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/memory-tiers.c:demotion_enabled_store
  - mm/memcontrol.c:setup_swap_account
  - mm/usercopy.c:parse_hardened_usercopy
  - block/bdev.c:setup_bdev_allow_write_mounted
  - lib/kstrtox.c:kstrtobool_from_user
  - lib/stackdepot.c:disable_stack_depot
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/p2pdma.c:pci_p2pdma_enable_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/tty/serial/serial_core.c:console_store
  - drivers/char/random.c:parse_trust_bootloader
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/iommu/dma-iommu.c:iommu_dma_forcedac_setup
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/base/core.c:fw_devlink_strict_setup
  - drivers/base/firmware_loader/sysfs_upload.c:cancel_store
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/scsi/scsi_sysfs.c:sdev_store_cdl_enable
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_shutdown_store
  - drivers/scsi/sd.c:manage_runtime_start_stop_store
  - drivers/scsi/sd.c:manage_system_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/core/port.c:disable_store
  - drivers/usb/core/port.c:early_stop_store
  - drivers/usb/roles/class.c:role_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/input/input.c:inhibited_store
  - drivers/md/md.c:serialize_policy_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/cpufreq/intel_pstate.c:store_energy_efficiency
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff81863990-ffffffff81863a32: kstrtobool (STB_GLOBAL)
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
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffff800010639a68)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/arm64/kernel/cpufeature.c:early_enable_pseudo_nmi
  - arch/arm64/kernel/cpufeature.c:parse_kpti
  - arch/arm64/mm/mmu.c:parse_rodata
  - virt/kvm/arm/vgic/vgic-v3.c:early_gicv4_enable
  - virt/kvm/arm/vgic/vgic-v3.c:early_common_trap_cfg
  - virt/kvm/arm/vgic/vgic-v3.c:early_group1_trap_cfg
  - virt/kvm/arm/vgic/vgic-v3.c:early_group0_trap_cfg
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg
  - drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/roles/class.c:role_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffff800010639a68-ffff800010639b10: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c07df45c)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/irqchip/irq-gic.c:gicv2_force_probe_cfg
  - drivers/irqchip/irq-gic-v3.c:gicv3_nolpi_cfg
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/usb/roles/class.c:role_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/clocksource/arm_arch_timer.c:early_evtstrm_cfg
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
c07df45c-c07df5a4: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (c0000000007e0710)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - arch/powerpc/kernel/prom.c:parse_ppc_tm
  - arch/powerpc/kernel/rtasd.c:rtasmsgs_setup
  - arch/powerpc/mm/init_64.c:parse_disable_radix
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:setup_cede_offline
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/region_devs.c:deep_flush_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/md/md.c:fail_last_dev_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
c0000000007e0710-c0000000007e0888: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffe00046655e)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/md/md.c:fail_last_dev_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffe00046655e-ffffffe0004665f8: kstrtobool (STB_GLOBAL)
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
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81525e50)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/md/md.c:fail_last_dev_store
```
**Symbols:**

```
ffffffff81525e50-ffffffff81525ee4: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81516130)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/md/md.c:fail_last_dev_store
```
**Symbols:**

```
ffffffff81516130-ffffffff815161c4: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff81521ee0)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/md/md.c:fail_last_dev_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff81521ee0-ffffffff81521f74: kstrtobool (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kstrtobool(const char *s, bool *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kstrtox.c (ffffffff8153b860)
Location: lib/kstrtox.c:332
Inline: True
Direct callers:
  - init/main.c:set_debug_rodata
  - arch/x86/events/intel/core.c:set_sysctl_tfa
  - arch/x86/events/intel/core.c:intel_perf_counter_freezing_setup
  - arch/x86/xen/setup.c:xen_memory_setup
  - arch/x86/kernel/cpu/umwait.c:enable_c02_store
  - arch/x86/kernel/aperture_64.c:parse_gart_mem
  - arch/x86/platform/uv/tlb_uv.c:setup_bau
  - kernel/params.c:param_set_bint
  - kernel/params.c:param_set_invbool
  - kernel/params.c:param_set_bool_enable_only
  - kernel/params.c:param_set_bool_enable_only
  - kernel/sched/psi.c:setup_psi
  - kernel/livepatch/core.c:enabled_store
  - kernel/time/hrtimer.c:setup_hrtimer_hres
  - kernel/time/tick-sched.c:setup_tick_nohz
  - mm/page_alloc.c:early_init_on_free
  - mm/page_alloc.c:early_init_on_alloc
  - mm/ksm.c:use_zero_pages_store
  - mm/page_poison.c:early_page_poison_param
  - mm/usercopy.c:parse_hardened_usercopy
  - lib/kstrtox.c:kstrtobool_from_user
  - drivers/pci/pcie/aspm.c:clkpm_store
  - drivers/pci/iov.c:sriov_drivers_autoprobe_store
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epc_start_store
  - drivers/acpi/sysfs.c:force_remove_store
  - drivers/char/random.c:parse_trust_cpu
  - drivers/iommu/iommu.c:iommu_dma_setup
  - drivers/iommu/iommu.c:iommu_set_def_domain_type
  - drivers/base/core.c:online_store
  - drivers/base/core.c:device_store_bool
  - drivers/nvdimm/region_devs.c:read_only_store
  - drivers/nvdimm/namespace_devs.c:force_raw_store
  - drivers/dax/super.c:write_cache_store
  - drivers/scsi/sd.c:allow_restart_store
  - drivers/scsi/sd.c:manage_start_stop_store
  - drivers/usb/core/sysfs.c:interface_authorized_store
  - drivers/usb/core/sysfs.c:interface_authorized_default_store
  - drivers/usb/core/sysfs.c:usb2_hardware_lpm_store
  - drivers/input/serio/i8042.c:i8042_set_reset
  - drivers/md/md.c:fail_last_dev_store
  - drivers/powercap/powercap_sys.c:enabled_store
```
**Symbols:**

```
ffffffff8153b860-ffffffff8153b8f4: kstrtobool (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
