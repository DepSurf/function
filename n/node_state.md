# Function: <code>node_state</code>

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
In arch/x86/kernel/quirks.c (ffffffff81035765)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81042345)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042ede)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f6fced)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff81f78669)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/workqueue.c (ffffffff81f7c36f)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In mm/page_alloc.c (ffffffff811923aa)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:is_pageblock_removable_nolock
```
```
In mm/vmscan.c (ffffffff811a54da)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaim
```
```
In mm/vmstat.c (ffffffff811ac755)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show
```
```
In mm/compaction.c (ffffffff811b7f93)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/sparse.c (ffffffff81819525)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff8181f0ce)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block
```
```
In mm/memory_hotplug.c (ffffffff81819a28)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:try_online_node
```
```
In mm/migrate.c (ffffffff811f2ca1)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
```
```
In mm/memcontrol.c (ffffffff81f8d83d)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-sysfs.c (ffffffff8143b965)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff8148b1d8)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff81533275)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff8156085f)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:register_one_node
```
```
In arch/x86/pci/acpi.c (ffffffff816f8e06)
Location: include/linux/nodemask.h:398
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81034965)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104223a)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042e37)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81f98410)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff81fa1608)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff81fa5119)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In mm/page_alloc.c (ffffffff811ac51f)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/vmscan.c (ffffffff811bbfb3)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff811c55e5)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show
```
```
In mm/compaction.c (ffffffff811d1ab3)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/sparse.c (ffffffff81893075)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff818995d2)
Location: include/linux/nodemask.h:407
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81894587)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff8121292c)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
```
```
In mm/memcontrol.c (ffffffff81fb7d36)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-sysfs.c (ffffffff814877f5)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff814da010)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff81587816)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff815b54f4)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
```
```
In arch/x86/pci/acpi.c (ffffffff8175db16)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff810345a5)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81041cce)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81042919)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff81fd38da)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff81fdcbdf)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff81fe0a8f)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In mm/page_alloc.c (ffffffff811bcaff)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/vmscan.c (ffffffff811cc683)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff811d56f5)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/vmstat.c:unusable_show
```
```
In mm/compaction.c (ffffffff811e19f3)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/sparse.c (ffffffff818c78c5)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff818cdc8a)
Location: include/linux/nodemask.h:407
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff818c8c9e)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff81224bf8)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/memcontrol.c (ffffffff818c9075)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-sysfs.c (ffffffff814a8fd8)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff814fc8d3)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff815b4ed6)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff815e47e0)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
```
```
In arch/x86/pci/acpi.c (ffffffff8178a046)
Location: include/linux/nodemask.h:407
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81032631)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff820ac686)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8103fdde)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81040a08)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff820b4596)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff820bdbca)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff820c18de)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In mm/page_alloc.c (ffffffff811c4ccf)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/vmscan.c (ffffffff811d52aa)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff811df405)
Location: include/linux/nodemask.h:403
Inline: True
```
```
In mm/compaction.c (ffffffff811eb7b3)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/sparse.c (ffffffff818ff025)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/sparse-vmemmap.c (ffffffff81905131)
Location: include/linux/nodemask.h:403
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81900207)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812302d2)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/memcontrol.c (ffffffff81900620)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff814b1f14)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff814b3872)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff8150cc53)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff815cad20)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff815f93c3)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
```
```
In arch/x86/pci/acpi.c (ffffffff817a9176)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81034961)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff826b2ea8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81043153)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81043e0a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff826bacc9)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff826c4a01)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff826c9ace)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/bpf/syscall.c (ffffffff8119fe72)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
```
In mm/page_alloc.c (ffffffff811d9ab3)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:is_pageblock_removable_nolock
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/vmscan.c (ffffffff811ea7da)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff811f5082)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff81201b33)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/memory_hotplug.c (ffffffff8198a1a7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff8124df61)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
```
```
In mm/memcontrol.c (ffffffff8198a616)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff814f15f4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff814f3052)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff8154fbb5)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff81631b2b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff816614a4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
```
```
In arch/x86/pci/acpi.c (ffffffff81820626)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81035971)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff826dc671)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81044f7b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81045fcb)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff826e4a95)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff826eeca4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff8109115f)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
```
```
In kernel/workqueue.c (ffffffff826f3cb3)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/bpf/syscall.c (ffffffff811b51d8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/page_alloc.c (ffffffff811f4fe6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/vmscan.c (ffffffff8120c107)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff81216345)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff81222f13)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/memory_hotplug.c (ffffffff8126c56f)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff81271a42)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memcontrol.c (ffffffff8270a03e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff815217f0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff815232ee)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff81586451)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff8166cf3b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff8169cbc5)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
```
```
In arch/x86/pci/acpi.c (ffffffff8186a87a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81036b51)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff82892a4b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104698d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff810479c2)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810485c5)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff8289b56a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff828a5992)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810994f3)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
```
```
In kernel/workqueue.c (ffffffff828aaa9b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/bpf/syscall.c (ffffffff811c413e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
```
In mm/page_alloc.c (ffffffff81207356)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/vmscan.c (ffffffff8121ec4a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff81229245)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff81235f63)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/memory_hotplug.c (ffffffff81280dd4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff81286062)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
```
In mm/memcontrol.c (ffffffff828c11cb)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff81537620)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8153914e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff8159e761)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff8168b2cb)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff816bd3c1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_mem_sect_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
```
```
In arch/x86/pci/acpi.c (ffffffff8188a94b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81038b91)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff828a9f93)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104939f)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104a759)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104b344)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b3348)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff828bdf67)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff8109ddf8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff828c3277)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/bpf/syscall.c (ffffffff811d4357)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff8122e320)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff81238f05)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff81247447)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff8126d564)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/memory_hotplug.c (ffffffff8129d230)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812a05b5)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff828da54c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff81566f6c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81568aae)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff815cfc61)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff816c2ccc)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff816f8132)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_memory_block_under_nodes
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff818d518a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81039361)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff828acff6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c6f)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b0d0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bd3e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b679f)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff828c43c1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810a4348)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff810c1656)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/bpf/syscall.c (ffffffff811e0a57)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff8123c4b0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff81247215)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff812558e7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff8127c374)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/slub.c (ffffffff812a65aa)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff812aca00)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812b1964)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff828e29f3)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff815882cc)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81589cee)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff815f0ed1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/acpi/hmat/hmat.c (ffffffff8163b030)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816e60b3)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/base/node.c (ffffffff8171c532)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff8190750a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff8103c161)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff82cd23a1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104e421)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ecfb)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
  - arch/x86/kernel/cpu/amd.c:nearby_node
  - arch/x86/kernel/cpu/amd.c:nearby_node
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105003b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
  - arch/x86/kernel/cpu/hygon.c:nearby_node
  - arch/x86/kernel/cpu/hygon.c:nearby_node
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff82cdb83d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff82ce7765)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810ab5f8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff82ced824)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/bpf/syscall.c (ffffffff811fec97)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff8126ad1d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff812756a5)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff8128407d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff812ae704)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/mempolicy.c (ffffffff812cc93a)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/slub.c (ffffffff812db54b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff81bc1bc5)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812e7205)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff82cffaca)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
```
```
In fs/io-wq.c (ffffffff8138b591)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
```
```
In drivers/pci/pci-driver.c (ffffffff8162e03d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163118e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e8016)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/iommu/intel/dmar.c (ffffffff8179cc73)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/base/node.c (ffffffff817d86ac)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff81bb7c19)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff8103c8c1)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff82fbe1e8)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104d961)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104dfbb)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
  - arch/x86/kernel/cpu/amd.c:srat_detect_node
  - arch/x86/kernel/cpu/amd.c:nearby_node
  - arch/x86/kernel/cpu/amd.c:nearby_node
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104f24b)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
  - arch/x86/kernel/cpu/hygon.c:srat_detect_node
  - arch/x86/kernel/cpu/hygon.c:nearby_node
  - arch/x86/kernel/cpu/hygon.c:nearby_node
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff82fc7c93)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff82fd5228)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810a6e78)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff82fd9e7e)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/bpf/syscall.c (ffffffff811fdfb7)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff8127575d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff8127fed5)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In mm/compaction.c (ffffffff8128e0dd)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff812ba324)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/mempolicy.c (ffffffff812d82da)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In mm/slub.c (ffffffff812e7a8d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff81c3ac72)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812f2772)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff82fec48f)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:alloc_mem_cgroup_per_node_info
```
```
In fs/io-wq.c (ffffffff8139c77e)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
  - fs/io-wq.c:io_wq_manager
  - fs/io-wq.c:io_wq_manager
```
```
In drivers/pci/pci-driver.c (ffffffff8165373d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8165682e)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff817058c0)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
  - drivers/acpi/numa/hmat.c:alloc_memory_initiator
```
```
In drivers/iommu/intel/dmar.c (ffffffff817aa943)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In drivers/base/node.c (ffffffff817ed0ec)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff81bcc969)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff8103e0f1)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff831c88f0)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104f516)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81050778)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105112c)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff831d25f4)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff831dfced)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810a7f38)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff831e4836)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/bpf/syscall.c (ffffffff811fea47)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff8127aa7d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff81284e95)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In mm/compaction.c (ffffffff8129374d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff812bf484)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/memory_hotplug.c (ffffffff81c2d296)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/mempolicy.c (ffffffff812df348)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In mm/migrate.c (ffffffff812f8b12)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff831f6cbf)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In fs/io-wq.c (ffffffff813a3845)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In drivers/pci/pci-driver.c (ffffffff816370bd)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8163944e)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff816e6f6e)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/iommu/intel/dmar.c (ffffffff8178d593)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In drivers/base/node.c (ffffffff817d18bc)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff81bc0399)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81043da1)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff832a9b2e)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810575ed)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff81058aa5)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8105958c)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff832b4e66)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
```
```
In arch/x86/mm/numa.c (ffffffff832c3289)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810b99d6)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff832c856d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/topology.c (ffffffff811206da)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
```
```
In kernel/bpf/syscall.c (ffffffff81230687)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff812b8add)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff812c34b5)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In mm/compaction.c (ffffffff812d3bbd)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/compaction.c:compact_store
```
```
In mm/page_alloc.c (ffffffff813090a4)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/memory_hotplug.c (ffffffff81d4bb3d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/mempolicy.c (ffffffff81326ca8)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In mm/migrate.c (ffffffff813431b7)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff832dd85e)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In fs/io-wq.c (ffffffff813f2d7f)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_create
```
```
In drivers/pci/pci-driver.c (ffffffff816a730d)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff816a98de)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff8176055c)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/iommu/intel/dmar.c (ffffffff81814e13)
Location: include/linux/nodemask.h:414
Inline: True
```
```
In drivers/base/node.c (ffffffff8185c507)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In drivers/base/memory.c (ffffffff8185cd60)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In arch/x86/pci/acpi.c (ffffffff81c90359)
Location: include/linux/nodemask.h:414
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int node_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8104bf18)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810639d3)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8106534d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81065c4c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/numa.c (ffffffff81e518c2)
Location: include/linux/nodemask.h:413
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810d0460)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff8347b675)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/fair.c (ffffffff8111f0c3)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/build_utility.c (ffffffff8114aa64)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
```
```
In kernel/bpf/syscall.c (ffffffff81273600)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff8131457d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff813216d9)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff8348a977)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
```
```
In mm/compaction.c (ffffffff81332a83)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:compact_store
```
```
In mm/mprotect.c (ffffffff813540a1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/page_alloc.c (ffffffff8348e675)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/memory_hotplug.c (ffffffff81f1b441)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff834904b1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In mm/mempolicy.c (ffffffff81399ac6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
```
```
In mm/migrate.c (ffffffff813b60b0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:migrate_misplaced_page
  - mm/migrate.c:do_pages_move
```
```
In mm/huge_memory.c (ffffffff813bdc1d)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/huge_memory.c:change_huge_pmd
```
```
In mm/memcontrol.c (ffffffff8349309e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In mm/hugetlb_cgroup.c (ffffffff813d7095)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In io_uring/io-wq.c (ffffffff816db8e0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/pci/pci-driver.c (ffffffff817c8d11)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff817cc345)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff81893f84)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/iommu/intel/dmar.c (ffffffff81955dbf)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/base/node.c (ffffffff819a3680)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
Direct callers:
  - drivers/base/node.c:node_dev_init
```
```
In drivers/base/memory.c (ffffffff819a3fe6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In arch/x86/pci/acpi.c (ffffffff81e3f47b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
**Symbols:**

```
ffffffff81e518c2-ffffffff81e518d9: node_state.constprop.0 (STB_LOCAL)
ffffffff81e56cc1-ffffffff81e56cd8: node_state.constprop.0 (STB_LOCAL)
ffffffff81eb9c0c-ffffffff81eb9c4c: node_state (STB_LOCAL)
ffffffff81eccd6f-ffffffff81eccdaf: node_state (STB_LOCAL)
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
In arch/x86/events/intel/ds.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In arch/x86/kernel/quirks.c (ffffffff810581f8)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81072ad3)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107463d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff81074f8c)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/numa.c (ffffffff83e9e905)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810eecbd)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff83ea652a)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/fair.c (ffffffff8114845b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/build_utility.c (ffffffff811793e4)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
```
```
In kernel/dma/direct.c (ffffffff811c1f28)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811c392e)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/bpf/syscall.c (ffffffff812c9d60)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In mm/filemap.c (ffffffff8135a13d)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In mm/vmscan.c (ffffffff813886bd)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:run_cmd
```
```
In mm/vmstat.c (ffffffff813956d9)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/percpu.c (ffffffff83ebb959)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
```
```
In mm/slab_common.c (ffffffff813a138b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/compaction.c (ffffffff813a9793)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/compaction.c:compact_store
```
```
In mm/vmalloc.c (ffffffff813e2b5b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff83ec07f1)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/memory_hotplug.c (ffffffff820c33b1)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff83ec3635)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In mm/hugetlb_vmemmap.c (ffffffff81413c68)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8141887f)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In mm/slub.c (ffffffff81427a27)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff81432932)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_page
  - mm/migrate.c:do_pages_move
```
```
In mm/memory-tiers.c (ffffffff81436689)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In mm/memcontrol.c (ffffffff83ec6ff8)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
```
```
In mm/hugetlb_cgroup.c (ffffffff8145cef5)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In block/blk-mq.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In io_uring/io-wq.c (ffffffff817a79b9)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
```
```
In drivers/pci/pci-driver.c (ffffffff818e6611)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff818ea548)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff819dba3d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/iommu/intel/dmar.c (ffffffff81abc8f8)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/iommu/intel/iommu.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad48c4)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In drivers/base/node.c (ffffffff83ef8397)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In drivers/base/memory.c (ffffffff81b15fc6)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In net/core/skbuff.c (ffffffff81da45eb)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In net/core/page_pool.c (ffffffff81e102af)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In arch/x86/pci/acpi.c (ffffffff8201930b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/events/intel/ds.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In arch/x86/kernel/quirks.c (ffffffff81059398)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff810746ee)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107655a)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff810770fc)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/numa.c (ffffffff836c2a65)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810fac6d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff836cacea)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/fair.c (ffffffff811582fa)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/sched/build_utility.c (ffffffff81189fce)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
```
```
In kernel/dma/direct.c (ffffffff811d4a52)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811d647b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/bpf/syscall.c (ffffffff812f1564)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In mm/filemap.c (ffffffff8138bb93)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In mm/vmscan.c (ffffffff813ba84d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:run_cmd
```
```
In mm/vmstat.c (ffffffff813c82f9)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/mm_init.c (ffffffff836e255c)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
```
```
In mm/percpu.c (ffffffff836e3fa7)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
```
```
In mm/slab_common.c (ffffffff813d4607)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
```
In mm/compaction.c (ffffffff813dca63)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/compaction.c:compact_store
```
```
In mm/vmalloc.c (ffffffff81417704)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff81422a7f)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:__page_frag_cache_refill
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/memory_hotplug.c (ffffffff82147191)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff836e8715)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In mm/hugetlb_vmemmap.c (ffffffff81447368)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb_vmemmap.c:vmemmap_remap_free
```
```
In mm/mempolicy.c (ffffffff8144bdd2)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In mm/slub.c (ffffffff8145cf91)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/migrate.c (ffffffff81466fe3)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_folio
  - mm/migrate.c:do_pages_move
```
```
In mm/memory-tiers.c (ffffffff8146c349)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In mm/hugetlb_cgroup.c (ffffffff81492f45)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In block/blk-mq.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/pci/pci-driver.c (ffffffff81929c51)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8192db58)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a236eb)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target_initiators
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b06c90)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b07e5f)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b091e8)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b0f124)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b23091)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In drivers/base/node.c (ffffffff8371df37)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In drivers/base/memory.c (ffffffff81b64d36)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In net/core/skbuff.c (ffffffff81e1323d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In net/core/page_pool.c (ffffffff81e83b53)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In arch/x86/pci/acpi.c (ffffffff8209998b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/events/intel/ds.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In arch/x86/events/intel/pt.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In arch/x86/hyperv/hv_proc.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In arch/x86/kernel/espfix_64.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In arch/x86/kernel/quirks.c (ffffffff810605b8)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8107bbc1)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8107d962)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8107e669)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/mm/numa.c (ffffffff838f3485)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff8110408d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff8112b912)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/sched/build_utility.c (ffffffff811988ce)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
```
```
In kernel/dma/direct.c (ffffffff811e9942)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In kernel/dma/ops_helpers.c (ffffffff811eb4ab)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/dma/ops_helpers.c:dma_common_alloc_pages
```
```
In kernel/profile.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/bpf/syscall.c (ffffffff81310394)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/ringbuf.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In mm/filemap.c (ffffffff813b5703)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In mm/vmscan.c (ffffffff813e396d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:run_cmd
```
```
In mm/vmstat.c (ffffffff813f2ce9)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/mm_init.c (ffffffff83914e5d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
```
```
In mm/percpu.c (ffffffff83916837)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
```
```
In mm/compaction.c (ffffffff814069b3)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/compaction.c:compact_store
```
```
In mm/vmalloc.c (ffffffff81444214)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
```
In mm/page_alloc.c (ffffffff8144f873)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:page_frag_alloc_align
  - mm/page_alloc.c:alloc_pages_exact_nid
```
```
In mm/memory_hotplug.c (ffffffff822298eb)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/slub.c (ffffffff81454f9b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/slub.c:__kmalloc_large_node
  - mm/slub.c:allocate_slab
  - mm/slub.c:allocate_slab
```
```
In mm/hugetlb.c (ffffffff8391bca5)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb.c:hugepages_setup
```
```
In mm/hugetlb_vmemmap.c (0)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In mm/mempolicy.c (ffffffff81485a3b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_mpol
  - mm/mempolicy.c:__do_sys_set_mempolicy_home_node
```
```
In mm/sparse-vmemmap.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In mm/migrate.c (ffffffff81496220)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/migrate.c:alloc_misplaced_dst_folio
  - mm/migrate.c:do_pages_move
```
```
In mm/memory-tiers.c (ffffffff8149b499)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/memory-tiers.c:set_node_memory_tier
```
```
In mm/hugetlb_cgroup.c (ffffffff814c294d)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In block/blk-mq.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/pci/pci-driver.c (ffffffff81972451)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_call_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff819764d8)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a6e5ff)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:hmat_register_target
  - drivers/acpi/numa/hmat.c:hmat_update_target_attrs
```
```
In drivers/iommu/amd/iommu.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff81b5ac66)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In drivers/iommu/amd/io_pgtable_v2.c (ffffffff81b5be8f)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable_v2.c:v2_alloc_pte
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5d208)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_rhsa
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b63a14)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:alloc_pgtable_page
```
```
In drivers/iommu/intel/pasid.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/intel/irq_remapping.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b79a01)
Location: include/linux/nodemask.h:421
Inline: True
```
```
In drivers/base/node.c (ffffffff83951907)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_cpu_under_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In drivers/base/memory.c (ffffffff81bb8a66)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
```
```
In net/core/skbuff.c (ffffffff81ed03fd)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - net/core/skbuff.c:__napi_alloc_skb
```
```
In net/core/xdp.c (0)
Location: include/linux/nodemask.h:421
Inline: False
```
```
In net/core/page_pool.c (ffffffff81f43f94)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - net/core/page_pool.c:__page_pool_alloc_page_order
```
```
In arch/x86/pci/acpi.c (ffffffff8217108b)
Location: include/linux/nodemask.h:421
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/arm64/kernel/setup.c (ffff800011433e44)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:topology_init
```
```
In kernel/workqueue.c (ffff800011442f8c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
  - kernel/workqueue.c:queue_work_node
```
```
In kernel/bpf/syscall.c (ffff800010263068)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffff8000102cd650)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffff8000102da810)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffff8000102ecdc4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffff800010313af8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/slub.c (ffff800010347950)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffff800010d9cf10)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffff80001035210c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffff80001145bcac)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In drivers/pci/pci-driver.c (ffff8000106ec6d4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ee728)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffff80001077ba20)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/acpi/hmat/hmat.c (ffff8000107a62f8)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/acpi/arm64/iort.c (ffff80001148175c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:arm_smmu_v3_set_proximity
```
```
In drivers/base/node.c (ffff8000109101b8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In drivers/of/of_numa.c (ffff800010b78b68)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/of/of_numa.c:of_node_to_nid
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
In kernel/workqueue.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/nodemask.h:464
Inline: True
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
In arch/powerpc/kernel/sysfs.c (c000000001348844)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/powerpc/kernel/sysfs.c:topology_init
```
```
In arch/powerpc/kernel/pci-common.c (c00000000006d0b0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
```
```
In arch/powerpc/mm/numa.c (c0000000000a32a4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:find_and_online_cpu_nid
  - arch/powerpc/mm/numa.c:hot_add_scn_to_nid
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:numa_setup_cpu
```
```
In kernel/workqueue.c (c000000000165878)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/bpf/syscall.c (c00000000030823c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (c00000000038b0d0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (c00000000039b05c)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (c0000000003b0908)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (c0000000003ec944)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/slub.c (c000000000425a0c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (c00000000042ee7c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (c00000000043891c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (c000000001386734)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_css_alloc
```
```
In drivers/pci/pci-driver.c (c0000000008683d0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (c00000000086ae68)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/base/node.c (c0000000009b0e0c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
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
In kernel/workqueue.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/nodemask.h:464
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/linux/nodemask.h:464
Inline: True
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
In arch/x86/kernel/quirks.c (ffffffff810394c1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff8289b008)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049ddf)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b240)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104beae)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828a47a6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff828af397)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff8109dc68)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff810bb9c6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/bpf/syscall.c (ffffffff811d9077)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff81234b00)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff8123f865)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff8124df37)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff812749c4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/slub.c (ffffffff8129eb8a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff812a4fe0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812a9f44)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff828cb8a7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff8157c15c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157db7e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff815dfb61)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/acpi/hmat/hmat.c (ffffffff81608390)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816abb93)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/base/node.c (ffffffff816e2862)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff818a68ca)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81028dd1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff828932c6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81039137)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8103a6f1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8103b0a3)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff8289c8e8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff828a7589)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff8108c688)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff810aa44c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/bpf/syscall.c (ffffffff811cbe37)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff81227b70)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff81232865)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff81240ed7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff81266934)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/slub.c (ffffffff812906ca)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff81296ab0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff8129b8a4)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff828c3fcc)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff8156af2c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8156c94e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff815cb1a1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/acpi/hmat/hmat.c (ffffffff815fa4e0)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816894f3)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/base/node.c (ffffffff816bcea2)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff818613fa)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff81039321)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff828adfe8)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff81049c1f)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104b080)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104bcee)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b76b6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff828c2296)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff8109dc18)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff810baf26)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/bpf/syscall.c (ffffffff811d6e47)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff812328a0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff8123d605)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff8124bcd7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff81272764)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/slub.c (ffffffff8129c99a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff812a2df0)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812a7d54)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff828de627)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff8157c01c)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff8157da3e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff815e51b1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/iommu/dmar.c (ffffffff816d9d73)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/base/node.c (ffffffff8170fa62)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
```
```
In arch/x86/pci/acpi.c (ffffffff818f7f2a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
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
In arch/x86/kernel/quirks.c (ffffffff8103a321)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/quirks.c:quirk_amd_nb_node
```
```
In arch/x86/kernel/topology.c (ffffffff828ae006)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8104b02f)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
```
In arch/x86/kernel/cpu/amd.c (ffffffff8104c490)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
  - arch/x86/kernel/cpu/amd.c:init_amd
```
```
In arch/x86/kernel/cpu/hygon.c (ffffffff8104d0fe)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
  - arch/x86/kernel/cpu/hygon.c:init_hygon
```
```
In arch/x86/kernel/setup_percpu.c (ffffffff828b77b7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
```
In arch/x86/mm/numa.c (ffffffff828c53e1)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/cpu.c (ffffffff810a5b08)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_smt_enable
```
```
In kernel/workqueue.c (ffffffff810c27d6)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/workqueue.c:queue_work_node
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/bpf/syscall.c (ffffffff811e51b7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In mm/vmscan.c (ffffffff81241d60)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
```
```
In mm/vmstat.c (ffffffff8124cd35)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In mm/compaction.c (ffffffff8125b5e7)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/compaction.c:sysfs_compact_node
```
```
In mm/page_alloc.c (ffffffff81282094)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/page_alloc.c:__build_all_zonelists
```
```
In mm/slub.c (ffffffff812ac9cd)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
```
In mm/memory_hotplug.c (ffffffff812b307b)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:is_mem_section_removable
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/migrate.c (ffffffff812b8054)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
```
In mm/memcontrol.c (ffffffff828e3a3e)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:mem_cgroup_alloc
```
```
In drivers/pci/pci-driver.c (ffffffff815964cc)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:pci_device_probe
```
```
In drivers/pci/pci-sysfs.c (ffffffff81597eee)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
```
```
In drivers/acpi/numa.c (ffffffff815ff061)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
```
```
In drivers/acpi/hmat/hmat.c (ffffffff816491b0)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/iommu/dmar.c (ffffffff816f4323)
Location: include/linux/nodemask.h:413
Inline: True
```
```
In drivers/base/node.c (ffffffff8172ab52)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_hugetlb_work
  - drivers/base/node.c:unregister_cpu_under_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:register_memory_node_under_compute_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_set_perf_attrs
```
```
In arch/x86/pci/acpi.c (ffffffff8191902a)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
