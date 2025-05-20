# Function: <code>add_taint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81080ba0)
Location: kernel/panic.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/memory.c:print_bad_pte
  - mm/slub.c:slab_bug
  - lib/bug.c:report_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffff81080ba0-ffffffff81080bd7: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810829d0)
Location: kernel/panic.c:356
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:__delete_from_page_cache
  - mm/page_alloc.c:bad_page
  - mm/memory.c:print_bad_pte
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
**Symbols:**

```
ffffffff810829d0-ffffffff81082a07: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81087430)
Location: kernel/panic.c:386
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:__delete_from_page_cache
  - mm/page_alloc.c:bad_page
  - mm/memory.c:print_bad_pte
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
**Symbols:**

```
ffffffff81087430-ffffffff81087467: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810842c0)
Location: kernel/panic.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:__delete_from_page_cache
  - mm/page_alloc.c:bad_page
  - mm/memory.c:print_bad_pte
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
**Symbols:**

```
ffffffff810842c0-ffffffff810842f7: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108abc0)
Location: kernel/panic.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page_alloc.c:bad_page
  - mm/memory.c:print_bad_pte
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8108abc0-ffffffff8108abf7: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:382
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page_alloc.c:bad_page
  - mm/memory.c:print_bad_pte
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8108e931-ffffffff8108e942: add_taint.cold.8 (STB_LOCAL)
ffffffff8108e440-ffffffff8108e46f: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/page_alloc.c:bad_page
  - mm/memory.c:print_bad_pte
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81096c71-ffffffff81096c82: add_taint.cold.8 (STB_LOCAL)
ffffffff810966d0-ffffffff810966ff: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8109b107)
Location: kernel/panic.c:422
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8109b274-ffffffff8109b285: add_taint.cold (STB_LOCAL)
ffffffff8109ae00-ffffffff8109ae2f: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810a161f)
Location: kernel/panic.c:431
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810a1794-ffffffff810a17a5: add_taint.cold (STB_LOCAL)
ffffffff810a1320-ffffffff810a134f: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810a88be)
Location: kernel/panic.c:441
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:set_license
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810a88ad-ffffffff810a88d5: add_taint.cold (STB_LOCAL)
ffffffff810a8220-ffffffff810a8266: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff81bdb476)
Location: kernel/panic.c:441
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_module_license_and_versions
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:set_license
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81bdb465-ffffffff81bdb48d: add_taint.cold (STB_LOCAL)
ffffffff810a3f70-ffffffff810a3fb6: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff81bcd568)
Location: kernel/panic.c:441
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81bcd557-ffffffff81bcd57f: add_taint.cold (STB_LOCAL)
ffffffff810a4bc0-ffffffff810a4c06: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff81ca3d2f)
Location: kernel/panic.c:439
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
  - mm/kfence/report.c:kfence_report_error
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81ca3d1e-ffffffff81ca3d46: add_taint.cold (STB_LOCAL)
ffffffff810b63e0-ffffffff810b6426: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_check_unsafe
  - kernel/sched/core.c:__schedule_bug
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
  - mm/kfence/report.c:kfence_report_error
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/vfio/vfio.c:vfio_register_group_dev
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff81e534ce-ffffffff81e534f4: add_taint.cold (STB_LOCAL)
ffffffff810cc960-ffffffff810cc9b0: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ea750)
Location: kernel/panic.c:534
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_check_unsafe
  - kernel/sched/core.c:__schedule_bug
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/module/main.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/kfence/report.c:kfence_report_error
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff810ea750-ffffffff810ea7b9: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f6330)
Location: kernel/panic.c:534
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_check_unsafe
  - kernel/sched/core.c:__schedule_bug
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/kfence/report.c:kfence_report_error
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:device_to_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff810f6330-ffffffff810f6399: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ff6e0)
Location: kernel/panic.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/params.c:param_check_unsafe
  - kernel/sched/core.c:__schedule_bug
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/module/main.c:module_augment_kernel_taints
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:filemap_unaccount_folio
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/kfence/report.c:kfence_report_error
  - drivers/pci/pci-sysfs.c:pci_write_config
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/intel/dmar.c:warn_invalid_dmar
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
  - drivers/iommu/intel/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:device_lookup_iommu
  - drivers/iommu/intel/irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
  - arch/x86/pci/common.c:pcibios_setup
  - arch/x86/pci/common.c:pcibios_setup
```
**Symbols:**

```
ffffffff810ff6e0-ffffffff810ff749: add_taint (STB_GLOBAL)
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
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f6170)
Location: kernel/panic.c:431
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:die
  - arch/arm64/kernel/cpufeature.c:update_cpu_features
  - kernel/panic.c:__warn
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:gic_check_reserved_range
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
**Symbols:**

```
ffff8000100f6170-ffff8000100f6208: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c0354508)
Location: kernel/panic.c:431
Inline: True
Direct callers:
  - arch/arm/kernel/traps.c:die
  - arch/arm/mm/mmu.c:early_mm_init
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_lpis
  - drivers/irqchip/irq-gic-v3-its.c:gic_check_reserved_range
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
```
**Symbols:**

```
c0354508-c035457c: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c6d8)
Location: kernel/panic.c:431
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
  - arch/powerpc/kernel/mce.c:machine_check_process_queued_event
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
c00000000013bdd0-c00000000013be8c: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c24d2)
Location: kernel/panic.c:431
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/riscv/kernel/traps.c:die
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
```
**Symbols:**

```
ffffffe0000c1eb2-ffffffe0000c1f2c: add_taint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8109af3f)
Location: kernel/panic.c:431
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8109b0b4-ffffffff8109b0c5: add_taint.cold (STB_LOCAL)
ffffffff8109ac40-ffffffff8109ac6f: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8108997f)
Location: kernel/panic.c:431
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff81089af4-ffffffff81089b05: add_taint.cold (STB_LOCAL)
ffffffff81089680-ffffffff810896af: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff8109aeef)
Location: kernel/panic.c:431
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8109b064-ffffffff8109b075: add_taint.cold (STB_LOCAL)
ffffffff8109abf0-ffffffff8109ac1f: add_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void add_taint(unsigned int flag, enum lockdep_ok lockdep_ok);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/panic.c (ffffffff810a2b5f)
Location: kernel/panic.c:431
Inline: True
Inline callers:
  - kernel/panic.c:__warn
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_get_mtrr
  - kernel/sysctl.c:proc_taint
  - kernel/sched/core.c:__schedule_bug
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/module.c:check_modinfo
  - kernel/watchdog.c:watchdog_timer_fn
  - mm/filemap.c:unaccount_page_cache_page
  - mm/memory.c:print_bad_pte
  - mm/page_alloc.c:bad_page
  - mm/slub.c:slab_bug
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/iommu/dmar.c:warn_invalid_dmar
  - drivers/iommu/dmar.c:dmar_parse_one_andd
  - drivers/iommu/intel-iommu.c:quirk_ioat_snb_local_iommu
  - drivers/iommu/intel_irq_remapping.c:intel_prepare_irq_remapping
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_bypass_write_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_cache_only_write_file
  - drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810a2cd4-ffffffff810a2ce5: add_taint.cold (STB_LOCAL)
ffffffff810a2860-ffffffff810a288f: add_taint (STB_GLOBAL)
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
