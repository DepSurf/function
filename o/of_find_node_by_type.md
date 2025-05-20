# Function: <code>of_find_node_by_type</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of.h:615
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of.h:483
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of.h:481
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of.h:493
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/sysfb_efi.c (0)
Location: include/linux/of.h:492
Inline: True
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
struct device_node *of_find_node_by_type(struct device_node *from, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b69848)
Location: drivers/of/base.c:1025
Inline: False
Direct callers:
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
  - drivers/of/of_numa.c:of_numa_init
  - drivers/of/of_numa.c:of_numa_init
```
**Symbols:**

```
ffff800010b69848-ffff800010b6999c: of_find_node_by_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device_node *of_find_node_by_type(struct device_node *from, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4d63c)
Location: drivers/of/base.c:1025
Inline: False
```
**Symbols:**

```
c0c4d63c-c0c4d718: of_find_node_by_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device_node *of_find_node_by_type(struct device_node *from, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c43100)
Location: drivers/of/base.c:1025
Inline: False
Direct callers:
  - arch/powerpc/kernel/time.c:get_freq
  - arch/powerpc/kernel/time.c:time_init
  - arch/powerpc/kernel/setup-common.c:check_legacy_ioport
  - arch/powerpc/kernel/setup-common.c:check_legacy_ioport
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup-common.c:smp_setup_cpu_maps
  - arch/powerpc/kernel/setup_64.c:initialize_cache_info
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/legacy_serial.c:find_legacy_serial_ports
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_find_early
  - arch/powerpc/kernel/isa-bridge.c:isa_bridge_find_early
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec_prepare
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec_prepare
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_init
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_init
  - arch/powerpc/platforms/pseries/nvram.c:pSeries_nvram_init
  - arch/powerpc/platforms/pseries/setup.c:pseries_init_irq
  - arch/powerpc/platforms/pseries/setup.c:pseries_init_irq
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/iommu.c:enable_ddw
  - arch/powerpc/platforms/pseries/iommu.c:pci_dma_bus_setup_pSeries
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove_by_index
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:dlpar_cpu_remove_by_index
  - arch/powerpc/platforms/pseries/pmem.c:__machine_initcall_pseries_pseries_pmem_init
  - arch/powerpc/platforms/pseries/pmem.c:dlpar_hp_pmem
  - drivers/video/fbdev/offb.c:offb_init
  - drivers/video/fbdev/offb.c:offb_init
  - drivers/video/fbdev/offb.c:offb_init
  - drivers/video/fbdev/offb.c:offb_init
```
**Symbols:**

```
c000000000c43100-c000000000c43254: of_find_node_by_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device_node *of_find_node_by_type(struct device_node *from, const char *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071f81e)
Location: drivers/of/base.c:1025
Inline: False
Direct callers:
  - arch/riscv/kernel/perf_event.c:init_hw_perf_events
```
**Symbols:**

```
ffffffe00071f81e-ffffffe00071f8e2: of_find_node_by_type (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
