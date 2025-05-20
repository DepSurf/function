# Function: <code>bus_get_dev_root</code>

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
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *bus_get_dev_root(const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36690)
Location: drivers/base/bus.c:1360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/workqueue.c:wq_sysfs_init
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/base/core.c:get_device_parent
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
```
**Symbols:**

```
ffffffff81b36690-ffffffff81b366e0: bus_get_dev_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *bus_get_dev_root(const struct bus_type *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8e0b0)
Location: drivers/base/bus.c:1360
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/umwait.c:umwait_init
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/cpu.c:cpuhp_sysfs_init
  - kernel/workqueue.c:wq_sysfs_init
  - drivers/acpi/acpi_lpit.c:lpit_update_residency
  - drivers/base/core.c:get_device_parent
  - drivers/base/cpu.c:cpu_dev_init
  - drivers/edac/edac_device_sysfs.c:edac_device_register_sysfs_main_kobj
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
  - drivers/cpufreq/cpufreq.c:cpufreq_core_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_sysfs_expose_params
  - drivers/cpuidle/sysfs.c:cpuidle_add_interface
```
**Symbols:**

```
ffffffff81b8e0b0-ffffffff81b8e100: bus_get_dev_root (STB_GLOBAL)
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
