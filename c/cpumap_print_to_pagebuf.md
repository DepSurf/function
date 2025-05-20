# Function: <code>cpumap_print_to_pagebuf</code>

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
In arch/x86/events/amd/uncore.c (ffffffff810083be)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a4b6)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/cstate.c (ffffffff8100f089)
Location: include/linux/cpumask.h:791
Inline: True
```
```
In arch/x86/events/intel/rapl.c (ffffffff810148e6)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/events/intel/rapl.c:rapl_get_attr_cpumask
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015576)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143b9fa)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
```
```
In drivers/base/cpu.c (ffffffff8154ebed)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff81550c76)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffff815522b9)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff8156071b)
Location: include/linux/cpumask.h:791
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In arch/x86/events/amd/uncore.c (ffffffff810088eb)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a646)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014ad6)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff8148790b)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff815a09d9)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff815a2a76)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffff815a4259)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff815b4e7b)
Location: include/linux/cpumask.h:826
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In arch/x86/events/amd/uncore.c (ffffffff8100892b)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a686)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014cb6)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a90e8)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff815cef09)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff815d1226)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffff815d2919)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff815e412b)
Location: include/linux/cpumask.h:831
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In arch/x86/events/amd/uncore.c (ffffffff810085e4)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff81009bf6)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013296)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b2848)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff815e3979)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff815e5c06)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffff815e74a9)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff815f8d3b)
Location: include/linux/cpumask.h:874
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
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
In arch/x86/events/amd/uncore.c (ffffffff81008a74)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a0d6)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81013ac6)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f1f38)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff8164ab29)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff8164cf06)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffff8164e879)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff81660ea5)
Location: include/linux/cpumask.h:878
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff8100919b)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a7e5)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff810144b5)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff815221d8)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff81686065)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff816884f9)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffff81689fd5)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff8169c665)
Location: include/linux/cpumask.h:880
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff810091fb)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100a715)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81014915)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff81538008)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff816a5d05)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff816a81e9)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffff816a94d5)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff816bcff5)
Location: include/linux/cpumask.h:892
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff81009688)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b055)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015db5)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff815679f8)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff816dede5)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff816e13d9)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
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
```
```
In drivers/base/cacheinfo.c (ffffffff816e2ab5)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff816f7825)
Location: include/linux/cpumask.h:891
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff81009a88)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b465)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016765)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff81588cc8)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff81703035)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff81705589)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
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
```
```
In drivers/base/cacheinfo.c (ffffffff81706c65)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff8171bc85)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff8100a9e8)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100c745)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81017ff5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff8162fc38)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff817bd155)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff817bfdf9)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
```
```
In drivers/base/cacheinfo.c (ffffffff817c1955)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff817d7cd5)
Location: include/linux/cpumask.h:919
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff81009998)
Location: include/linux/cpumask.h:925
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b6af)
Location: include/linux/cpumask.h:925
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101852f)
Location: include/linux/cpumask.h:925
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff816552c8)
Location: include/linux/cpumask.h:925
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff817d1f72)
Location: include/linux/cpumask.h:925
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff817d4cf9)
Location: include/linux/cpumask.h:925
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
```
```
In drivers/base/node.c (ffffffff817ec6e5)
Location: include/linux/cpumask.h:925
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff8100a378)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100c00f)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/core.c (ffffffff8100cd99)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
```
```
In arch/x86/events/intel/uncore.c (ffffffff810197df)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff81637ef8)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff817b59a2)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff817b8709)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
```
```
In drivers/base/node.c (ffffffff817d0f55)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/iommu.c (ffffffff8100c50f)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/core.c (ffffffff8100d2d9)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101c07f)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a8176)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff8183eea2)
Location: include/linux/cpumask.h:980
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
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
In arch/x86/events/amd/iommu.c (ffffffff8100d23f)
Location: include/linux/cpumask.h:1006
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/core.c (ffffffff8100e419)
Location: include/linux/cpumask.h:1006
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
```
```
In arch/x86/events/intel/uncore.c (ffffffff8101e81f)
Location: include/linux/cpumask.h:1006
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cad15)
Location: include/linux/cpumask.h:1006
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff81981ec2)
Location: include/linux/cpumask.h:1006
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/nvdimm/nd_perf.c (ffffffff819d8f8c)
Location: include/linux/cpumask.h:1006
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
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
In arch/x86/events/amd/iommu.c (ffffffff8101038f)
Location: include/linux/cpumask.h:1115
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/core.c (ffffffff81011969)
Location: include/linux/cpumask.h:1115
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
```
```
In arch/x86/events/intel/uncore.c (ffffffff81022dcf)
Location: include/linux/cpumask.h:1115
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff818e88b5)
Location: include/linux/cpumask.h:1115
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff81aefc22)
Location: include/linux/cpumask.h:1115
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81b53f9c)
Location: include/linux/cpumask.h:1115
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
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
In arch/x86/events/amd/iommu.c (ffffffff8100fa4f)
Location: include/linux/cpumask.h:1167
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/core.c (ffffffff81010ff9)
Location: include/linux/cpumask.h:1167
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
```
```
In arch/x86/events/intel/uncore.c (ffffffff81022aaf)
Location: include/linux/cpumask.h:1167
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192bec5)
Location: include/linux/cpumask.h:1167
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b1acff)
Location: include/linux/cpumask.h:1167
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:cpumask_show
```
```
In drivers/base/cpu.c (ffffffff81b3e002)
Location: include/linux/cpumask.h:1167
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81ba74dc)
Location: include/linux/cpumask.h:1167
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
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
In arch/x86/events/amd/iommu.c (ffffffff8101518f)
Location: include/linux/cpumask.h:1189
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/core.c (ffffffff81016749)
Location: include/linux/cpumask.h:1189
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_hybrid_get_attr_cpus
```
```
In arch/x86/events/intel/uncore.c (ffffffff81028bdf)
Location: include/linux/cpumask.h:1189
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff819747b5)
Location: include/linux/cpumask.h:1189
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b7082f)
Location: include/linux/cpumask.h:1189
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:cpumask_show
```
```
In drivers/base/cpu.c (ffffffff81b95c32)
Location: include/linux/cpumask.h:1189
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfb78c)
Location: include/linux/cpumask.h:1189
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:nvdimm_pmu_cpumask_show
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
In drivers/pci/pci-sysfs.c (ffff8000106ed3e0)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffff8000108eedc4)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffff8000108f1de0)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffff8000108f40ec)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffff80001090f5b4)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpulist
  - drivers/base/node.c:node_read_cpumask
```
```
In drivers/perf/arm-cci.c (ffff800010b90ba8)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_cpumask_attr_show
```
```
In drivers/perf/arm-ccn.c (ffff800010b92c50)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show
```
```
In drivers/perf/arm_pmu.c (ffff800010b94404)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_cpumask_show
```
```
In drivers/perf/qcom_l2_pmu.c (ffff800010b98b34)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/qcom_l2_pmu.c:l2_cache_pmu_cpumask_show
```
```
In drivers/perf/qcom_l3_pmu.c (ffff800010b9a294)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache_pmu_cpumask_show
```
```
In drivers/perf/xgene_pmu.c (ffff800010b9b1fc)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/xgene_pmu.c:xgene_pmu_cpumask_show
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
In arch/arm/mm/cache-l2x0-pmu.c (c0324e00)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/arm/mm/cache-l2x0-pmu.c:l2x0_pmu_cpumask_show
```
```
In arch/arm/mach-imx/mmdc.c (c03330d8)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/arm/mach-imx/mmdc.c:mmdc_pmu_cpumask_show
```
```
In drivers/pci/pci-sysfs.c (c08885f8)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (c09dc7d4)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (c09debc4)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (c09e05b0)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/perf/arm-cci.c (c0c7b2a8)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/arm-cci.c:pmu_cpumask_attr_show
```
```
In drivers/perf/arm-ccn.c (c0c7c7e4)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/arm-ccn.c:arm_ccn_pmu_cpumask_show
```
```
In drivers/perf/arm_pmu.c (c0c7db74)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/perf/arm_pmu.c:armpmu_cpumask_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/imc-pmu.c (c00000000012b3d4)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:imc_pmu_cpumask_get_attr
```
```
In drivers/pci/pci-sysfs.c (c000000000869470)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (c000000000987bcc)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (c00000000098b5a4)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
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
```
```
In drivers/base/cacheinfo.c (c00000000098dffc)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (c0000000009b03cc)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffe0004c209a)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffe000581836)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffe000583aac)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_show
  - drivers/base/topology.c:die_cpus_show
  - drivers/base/topology.c:core_siblings_list_show
  - drivers/base/topology.c:core_siblings_show
  - drivers/base/topology.c:thread_siblings_list_show
  - drivers/base/topology.c:thread_siblings_show
```
```
In drivers/base/cacheinfo.c (ffffffe0005856ae)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
</details>
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
In arch/x86/events/amd/uncore.c (ffffffff81009a88)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b465)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016765)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157cb58)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff816c8785)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff816cacd9)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
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
```
```
In drivers/base/cacheinfo.c (ffffffff816cc3b5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff816e1fb5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff81008228)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff81009df5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81015b95)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156b928)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff816a3ab5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff816a6009)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
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
```
```
In drivers/base/cacheinfo.c (ffffffff816a76e5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff816bc5f5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff81009a48)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b425)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016725)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157ca18)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff816f6cf5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff816f9249)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
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
```
```
In drivers/base/cacheinfo.c (ffffffff816fa925)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff8170f4e5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
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
In arch/x86/events/amd/uncore.c (ffffffff81009ba8)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/uncore.c:amd_uncore_attr_show_cpumask
```
```
In arch/x86/events/amd/iommu.c (ffffffff8100b605)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:_iommu_cpumask_show
```
```
In arch/x86/events/intel/uncore.c (ffffffff81016965)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_get_attr_cpumask
```
```
In drivers/pci/pci-sysfs.c (ffffffff81596ec8)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:cpulistaffinity_show
  - drivers/pci/pci-sysfs.c:cpuaffinity_show
  - drivers/pci/pci-sysfs.c:local_cpulist_show
  - drivers/pci/pci-sysfs.c:local_cpus_show
```
```
In drivers/base/cpu.c (ffffffff81711595)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cpu.c:show_cpus_attr
```
```
In drivers/base/topology.c (ffffffff81713ae9)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
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
```
```
In drivers/base/cacheinfo.c (ffffffff817151c5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:shared_cpu_list_show
  - drivers/base/cacheinfo.c:shared_cpu_map_show
```
```
In drivers/base/node.c (ffffffff8172a2a5)
Location: include/linux/cpumask.h:914
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_cpumap
```
</details>
</li>
</ul>

## Differences
