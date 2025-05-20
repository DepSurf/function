# Function: <code>bitmap_print_to_pagebuf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f95c0)
Location: lib/bitmap.c:471
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/rapl.c:rapl_get_attr_cpumask
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff813f95c0-ffffffff813f9610: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814405f0)
Location: lib/bitmap.c:473
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff814405f0-ffffffff81440640: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d6f0)
Location: lib/bitmap.c:473
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff8145d6f0-ffffffff8145d740: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462cc0)
Location: lib/bitmap.c:473
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
**Symbols:**

```
ffffffff81462cc0-ffffffff81462d12: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148ebd0)
Location: lib/bitmap.c:475
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
```
**Symbols:**

```
ffffffff8148ebd0-ffffffff8148ec22: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c33f0)
Location: lib/bitmap.c:472
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
```
**Symbols:**

```
ffffffff814c33f0-ffffffff814c3441: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d7e80)
Location: lib/bitmap.c:470
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff814d7e80-ffffffff814d7ec2: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81503a40)
Location: lib/bitmap.c:470
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:package_cpus_list_show
  - drivers/base/topology.c:package_cpus_show
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:core_cpus_list_show
  - drivers/base/topology.c:core_cpus_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81503a40-ffffffff81503a7e: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815219e0)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:package_cpus_list_show
  - drivers/base/topology.c:package_cpus_show
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:core_cpus_list_show
  - drivers/base/topology.c:core_cpus_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff815219e0-ffffffff81521a1e: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81584b20)
Location: lib/bitmap.c:478
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81584b20-ffffffff81584b5e: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a1c20)
Location: lib/bitmap.c:478
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff815a1c20-ffffffff815a1c5e: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815a8a30)
Location: lib/bitmap.c:480
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff815a8a30-ffffffff815a8a6e: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81611be0)
Location: lib/bitmap.c:480
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff81611be0-ffffffff81611c1e: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff816dde50)
Location: lib/bitmap.c:480
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff816dde50-ffffffff816ddeab: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff817cddf0)
Location: lib/bitmap.c:491
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff817cddf0-ffffffff817cde4b: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8180c2a0)
Location: lib/bitmap.c:491
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/iommu/intel/perfmon.c:cpumask_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff8180c2a0-ffffffff8180c2fb: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap-str.c (ffffffff81861440)
Location: lib/bitmap-str.c:58
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/iommu/intel/perfmon.c:cpumask_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
  - net/core/net-sysfs.c:xps_queue_show
```
**Symbols:**

```
ffffffff81861440-ffffffff8186149b: bitmap_print_to_pagebuf (STB_GLOBAL)
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
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062b0f0)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
  - drivers/perf/arm-cci.c:pmu_cpumask_attr_show
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show
  - drivers/perf/arm_pmu.c:armpmu_cpumask_show
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_cpumask_show
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_cpumask_show
  - drivers/perf/xgene_pmu.c:xgene_pmu_cpumask_show
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffff80001062b0f0-ffff80001062b140: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d2434)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_cpumask_show
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_cpumask_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/perf/arm-cci.c:pmu_cpumask_attr_show
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show
  - drivers/perf/arm_pmu.c:armpmu_cpumask_show
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
c07d2434-c07d2474: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007cd6d0)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - arch/powerpc/perf/imc-pmu.c:imc_pmu_cpumask_get_attr
  - arch/powerpc/perf/imc-pmu.c:imc_pmu_cpumask_get_attr
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:package_cpus_list_show
  - drivers/base/topology.c:package_cpus_show
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:core_cpus_list_show
  - drivers/base/topology.c:core_cpus_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
c0000000007cd6d0-c0000000007cd750: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045bc88)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffe00045bc88-ffffffe00045bcd6: bitmap_print_to_pagebuf (STB_GLOBAL)
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
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519fc0)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:package_cpus_list_show
  - drivers/base/topology.c:package_cpus_show
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:core_cpus_list_show
  - drivers/base/topology.c:core_cpus_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81519fc0-ffffffff81519ffe: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150a2b0)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:package_cpus_list_show
  - drivers/base/topology.c:package_cpus_show
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:core_cpus_list_show
  - drivers/base/topology.c:core_cpus_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff8150a2b0-ffffffff8150a2ee: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81516050)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:package_cpus_list_show
  - drivers/base/topology.c:package_cpus_show
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:core_cpus_list_show
  - drivers/base/topology.c:core_cpus_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff81516050-ffffffff8151608e: bitmap_print_to_pagebuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bitmap_print_to_pagebuf(bool list, char *buf, const long unsigned int *maskp, int nmaskbits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f7e0)
Location: lib/bitmap.c:490
Inline: False
Direct callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/base/cpu.c:show_cpus_attr
  - drivers/base/topology.c:package_cpus_list_show
  - drivers/base/topology.c:package_cpus_show
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:core_cpus_list_show
  - drivers/base/topology.c:core_cpus_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
  - drivers/base/node.c:node_read_cpumap
  - net/core/net-sysfs.c:xps_rxqs_show
```
**Symbols:**

```
ffffffff8152f7e0-ffffffff8152f81e: bitmap_print_to_pagebuf (STB_GLOBAL)
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
