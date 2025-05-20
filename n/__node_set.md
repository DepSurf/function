# Function: <code>__node_set</code>

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
In arch/x86/mm/numa.c (ffffffff81f782dc)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f79292)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff81f794bd)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_memory_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810baf60)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In mm/page_alloc.c (ffffffff81208ca3)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - mm/page_alloc.c:node_set_state
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/vmstat.c (ffffffff811ad902)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/hugetlb.c (ffffffff811dc0a9)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff811e126f)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff811e9484)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff81819a58)
Location: include/linux/nodemask.h:116
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:try_online_node
```
```
In drivers/acpi/numa.c (ffffffff8148b1a2)
Location: include/linux/nodemask.h:116
Inline: True
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
In arch/x86/mm/numa.c (ffffffff81fa0b66)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa19e8)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff81fa1c01)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810be526)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In mm/page_alloc.c (ffffffff811a6a19)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:node_set_state
```
```
In mm/vmstat.c (ffffffff811c6b4d)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/hugetlb.c (ffffffff811fa349)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8120215c)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff81207d3d)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff818945c0)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In drivers/acpi/numa.c (ffffffff81fcea2f)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff81fdc433)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fdcfce)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff81fdd1e4)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810bdcca)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff810ef9f1)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/page_alloc.c (ffffffff811b6d77)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:node_set_state
```
```
In mm/vmstat.c (ffffffff811d6c11)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/hugetlb.c (ffffffff8120a823)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81213f75)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81219da6)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff818c8cd3)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In drivers/acpi/numa.c (ffffffff8200bdf2)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff820bd455)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff820be08d)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff820be1e4)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810b8c46)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff810ef9b1)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/page_alloc.c (ffffffff811becb2)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:node_set_state
```
```
In mm/vmstat.c (ffffffff811dfa71)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/hugetlb.c (ffffffff81215b9f)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8121f290)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81225b0e)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff8122c717)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In drivers/acpi/numa.c (ffffffff820ed5d9)
Location: include/linux/nodemask.h:118
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff826c4294)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff826c4ec7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff826c5024)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810c0aa6)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff810f8598)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
```
In mm/page_alloc.c (ffffffff811d3979)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:node_set_state
```
```
In mm/vmstat.c (ffffffff811f5881)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/hugetlb.c (ffffffff812307d2)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8123a4b0)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8124119e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff81247ef7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In drivers/acpi/numa.c (ffffffff826f653a)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff826ee52f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff826ef0ab)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff826ef2c5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810c60b7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff811007c6)
Location: include/linux/nodemask.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f4d51)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:node_set_state
```
```
In mm/vmstat.c (ffffffff81216b01)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/hugetlb.c (ffffffff81252f9e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8125da82)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8126412c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff8126b847)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff8272055f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff828a521d)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a5d99)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828a5fb3)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810d0687)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff8110bf84)
Location: include/linux/nodemask.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff81207131)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:node_set_state
```
```
In mm/vmstat.c (ffffffff81229a11)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/hugetlb.c (ffffffff81267a0e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81272312)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8127889c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff812800d7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff828d84f5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff828bd79e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828be366)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828be59e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810d85b5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff81115714)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff828d240b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828d6a1d)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81282183)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8128d94f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81294999)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff8129c20f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff828f23af)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff828c3c28)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c47cf)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828c4a40)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810e2eb5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff81121915)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff828da87d)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828deeae)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81291d7e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8129d60f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff812a4769)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff812ac2bf)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff828fb5a4)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff82ce7216)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff82ce7b3d)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff82ce7dae)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810ec414)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff8112e09b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In mm/vmstat.c (ffffffff82cf8cb2)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff82cfc297)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/hugetlb.c (ffffffff812c5386)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812d120f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff812d8eed)
Location: include/linux/nodemask.h:128
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812e119a)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:node_states_set_node
  - mm/memory_hotplug.c:node_states_set_node
  - mm/memory_hotplug.c:node_states_set_node
```
```
In drivers/acpi/numa/srat.c (ffffffff82d13808)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff82fd4b8b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff82fd5534)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff82fd57a5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810e9f24)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff81129c8b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:get_nodes_in_cpumask
```
```
In mm/vmstat.c (ffffffff82fe598a)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff82fe8cb2)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/hugetlb.c (ffffffff812d0f96)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812dcd2f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff812e44dd)
Location: include/linux/nodemask.h:128
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81c3ad1b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff830011b7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831cec3c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/mm/numa.c (ffffffff831df64b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff831dffe0)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff831e0250)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810eb811)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff81129fb9)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff831eff89)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff831f353f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/memory_hotplug.c (ffffffff81c2d392)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff812d7d76)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff812e4596)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff812f29f7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_init
```
```
In drivers/acpi/numa/srat.c (ffffffff8320c2a7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b0ed9)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/mm/numa.c (ffffffff832c2b9d)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c35ad)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff832c38d0)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff81103391)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff8114a917)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff832d571b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff832d9756)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/memory_hotplug.c (ffffffff81d4bbff)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff8131e786)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8132b5dc)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8133a43f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff8133e2f6)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
```
```
In drivers/acpi/numa/srat.c (ffffffff832f4a21)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8346227e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/mm/numa.c (ffffffff834753e1)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:node_set_online
```
```
In arch/x86/mm/amdtopology.c (ffffffff83475e10)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff8347618a)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff8111ea78)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff8116fef5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff81321709)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff81371215)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:node_set_state
```
```
In mm/memory_hotplug.c (ffffffff81f1b4ee)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff81389d6b)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8139afce)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff813ac18f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_init
```
```
In mm/migrate.c (ffffffff813b113c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
```
```
In drivers/acpi/numa/srat.c (ffffffff834acd72)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e84433)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/mm/numa.c (ffffffff83e9e912)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/mm/amdtopology.c (ffffffff83e9eb37)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff83e9f011)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff81147e35)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff811a6355)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff83eba8cb)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff83ec0842)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/memory_hotplug.c (ffffffff820c345e)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff8140aaeb)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8141b03e)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8142ab2f)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_init
```
```
In mm/memory-tiers.c (ffffffff8143670a)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/memory-tiers.c:set_node_memory_tier
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff81447e71)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In drivers/acpi/numa/srat.c (ffffffff83ee5911)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a7983)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/mm/numa.c (ffffffff836c2a72)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/mm/amdtopology.c (ffffffff836c2cae)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff836c3191)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff81157cd6)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff836dfedb)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/mm_init.c (ffffffff836e25a4)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/page_alloc.c (ffffffff81422655)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/memory_hotplug.c (ffffffff814255fe)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/hugetlb.c (ffffffff8143e19b)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8144e504)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8145ffb7)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_init
```
```
In mm/memory-tiers.c (ffffffff8146c3ca)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/memory-tiers.c:set_node_memory_tier
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff8147d821)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In lib/group_cpus.c (ffffffff818e6d88)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/acpi/numa/srat.c (ffffffff8370b2e1)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d7ec8)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/mm/numa.c (ffffffff838f3492)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In arch/x86/mm/amdtopology.c (ffffffff838f389e)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff838f3d71)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff81163f26)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff8391278b)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/mm_init.c (ffffffff83914ea5)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/page_alloc.c (ffffffff8144f545)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:find_next_best_node
```
```
In mm/memory_hotplug.c (ffffffff81452906)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In mm/slub.c (ffffffff8145d357)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
  - mm/slub.c:kmem_cache_init
```
```
In mm/hugetlb.c (ffffffff81477e2b)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff814880a4)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/memory-tiers.c (ffffffff8149b51a)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/memory-tiers.c:set_node_memory_tier
  - mm/memory-tiers.c:establish_demotion_targets
```
```
In mm/khugepaged.c (ffffffff814abbf1)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - mm/khugepaged.c:alloc_charge_hpage
```
```
In lib/group_cpus.c (ffffffff8192dda8)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
```
In drivers/acpi/numa/srat.c (ffffffff8393e77a)
Location: include/linux/nodemask.h:129
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
  - drivers/acpi/numa/srat.c:acpi_parse_cfmws
  - drivers/acpi/numa/srat.c:acpi_numa_memory_affinity_init
  - drivers/acpi/numa/srat.c:acpi_map_pxm_to_node
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
In arch/arm64/kernel/acpi_numa.c (ffff800011436b98)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi_numa.c:acpi_numa_gicc_affinity_init
```
```
In arch/arm64/mm/numa.c (ffff800011438a64)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_add_memblk
  - arch/arm64/mm/numa.c:node_set_online
```
```
In kernel/sched/fair.c (ffff800010147d64)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/irq/affinity.c (ffff800010187bc0)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffff8000114534ac)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffff800011457c7c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffff80001032fd38)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffff80001033c3e0)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
```
```
In mm/slub.c (ffff800010344ca8)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffff800010d9d160)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffff80001147e65c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
```
```
In drivers/of/of_numa.c (ffff8000114aca08)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/of/of_numa.c:of_numa_init
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
In kernel/irq/affinity.c (c03d6798)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/slub.c (c054a178)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
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
In arch/powerpc/mm/numa.c (c000000001357830)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:node_set_online
```
```
In kernel/sched/fair.c (c000000000193dc4)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/irq/affinity.c (c0000000001e1860)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (c00000000137b8c8)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (c00000000138138c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (c000000000408444)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (c000000000417764)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (c000000000422e04)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (c00000000042da9c)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
In kernel/irq/affinity.c (ffffffe00011d618)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/hugetlb.c (ffffffe00022c954)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/slub.c (ffffffe000238b74)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
  - mm/slub.c:process_slab
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
In arch/x86/mm/numa.c (ffffffff828aebfe)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828af7a5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828af9d8)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810dd065)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff81119ef5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff828c3731)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828c7d62)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8128a35e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81295bef)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129cd49)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff812a489f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff828e4238)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff828a6df0)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a7997)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828a7bca)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810cc075)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff8110af65)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff828bbe56)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828c0487)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8127c18e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812877ff)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8128e8d9)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff8129636f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff828dc2df)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff828c1afd)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c26a4)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828c28d7)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810d93e5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff81117de5)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff828d64b1)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828daae2)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8128816e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812939ff)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129ab59)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff812a26af)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff828f71a0)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
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
In arch/x86/mm/numa.c (ffffffff828c4c48)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:dummy_numa_init
  - arch/x86/mm/numa.c:numa_clear_kernel_node_hotplug
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828c57ef)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In arch/x86/mm/srat.c (ffffffff828c5a60)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - arch/x86/mm/srat.c:acpi_numa_processor_affinity_init
  - arch/x86/mm/srat.c:acpi_numa_x2apic_affinity_init
```
```
In kernel/sched/fair.c (ffffffff810e4e15)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/irq/affinity.c (ffffffff81123475)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In mm/vmstat.c (ffffffff828db8d2)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828dff03)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8129859e)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812a385f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff812aaa39)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In mm/memory_hotplug.c (ffffffff812b2a0f)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa.c (ffffffff828fc5f8)
Location: include/linux/nodemask.h:128
Inline: True
Inline callers:
  - drivers/acpi/numa.c:acpi_numa_memory_affinity_init
```
</details>
</li>
</ul>

## Differences
