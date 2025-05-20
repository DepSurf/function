# Function: <code>__sysfs_match_string</code>

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
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff818f7120)
Location: lib/string.c:668
Inline: False
Direct callers:
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff818f7120-ffffffff818f7173: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8197db20)
Location: lib/string.c:669
Inline: False
Direct callers:
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff8197db20-ffffffff8197db73: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff819da010)
Location: lib/string.c:669
Inline: False
Direct callers:
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff819da010-ffffffff819da063: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a12230)
Location: lib/string.c:670
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81a12230-ffffffff81a12283: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a816a0)
Location: lib/string.c:712
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81a816a0-ffffffff81a816f4: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ab8770)
Location: lib/string.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81ab8770-ffffffff81ab87c4: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f33c0)
Location: lib/string.c:771
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff815f33c0-ffffffff815f3427: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617a70)
Location: lib/string.c:768
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81617a70-ffffffff81617ad7: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb0d0)
Location: lib/string.c:768
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_lpm_latch_mode_write
```
**Symbols:**

```
ffffffff815fb0d0-ffffffff815fb133: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668980)
Location: lib/string.c:769
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - mm/memory_hotplug.c:set_online_policy
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
```
**Symbols:**

```
ffffffff81668980-ffffffff816689e3: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff816ec090)
Location: lib/string_helpers.c:919
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - mm/memory_hotplug.c:set_online_policy
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
```
**Symbols:**

```
ffffffff816ec090-ffffffff816ec139: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff817dc860)
Location: lib/string_helpers.c:963
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - mm/memory_hotplug.c:set_online_policy
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
```
**Symbols:**

```
ffffffff817dc860-ffffffff817dc8ba: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff8181bfb0)
Location: lib/string_helpers.c:963
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - mm/memory_hotplug.c:set_online_policy
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_lpm_latch_mode_write
```
**Symbols:**

```
ffffffff8181bfb0-ffffffff8181c00a: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string_helpers.c (ffffffff81861d60)
Location: lib/string_helpers.c:980
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - mm/memory_hotplug.c:set_online_policy
  - block/blk-ioprio.c:ioprio_set_prio_policy
  - drivers/gpio/gpiolib-sysfs.c:edge_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/acpi/button.c:param_set_lid_init_state
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_charge_behaviour_parse
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81861d60-ffffffff81861dba: __sysfs_match_string (STB_GLOBAL)
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
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffff800010d92bd8)
Location: lib/string.c:714
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffff800010d92bd8-ffff800010d92c60: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c0e8f420)
Location: lib/string.c:714
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/usb/roles/class.c:role_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
c0e8f420-c0e8f478: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (c000000000ed6c60)
Location: lib/string.c:714
Inline: False
Direct callers:
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
c000000000ed6c60-c000000000ed6d24: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffe0008bcd00)
Location: lib/string.c:714
Inline: False
Direct callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffe0008bcd00-ffffffe0008bcd4e: __sysfs_match_string (STB_GLOBAL)
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
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a575c0)
Location: lib/string.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81a575c0-ffffffff81a57614: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81a146a0)
Location: lib/string.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81a146a0-ffffffff81a146f4: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81ac39b0)
Location: lib/string.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81ac39b0-ffffffff81ac3a04: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sysfs_match_string(const const char * *array, size_t n, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81acfe80)
Location: lib/string.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_epb.c:energy_perf_bias_store
  - drivers/pci/pcie/aspm.c:pcie_aspm_set_policy
  - drivers/scsi/sd.c:zeroing_mode_store
  - drivers/scsi/sd.c:provisioning_mode_store
  - drivers/scsi/sd.c:cache_type_store
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
  - drivers/power/supply/power_supply_sysfs.c:power_supply_store_property
```
**Symbols:**

```
ffffffff81acfe80-ffffffff81acfed4: __sysfs_match_string (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
