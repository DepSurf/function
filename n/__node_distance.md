# Function: <code>__node_distance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81074a70)
Location: arch/x86/mm/numa.c:429
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - kernel/sched/core.c:sched_domains_numa_masks_update
  - kernel/sched/core.c:find_numa_distance
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_fault
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/huge_memory.c:khugepaged
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff81074a70-ffffffff81074aad: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81fa0e54)
Location: arch/x86/mm/numa.c:428
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_cpu_to_node
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:find_numa_distance
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff81076070-ffffffff810760ac: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81079c60)
Location: arch/x86/mm/numa.c:428
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:find_numa_distance
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff81079c60-ffffffff81079c9c: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81078510)
Location: arch/x86/mm/numa.c:428
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff81078510-ffffffff8107854c: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff8107e850)
Location: arch/x86/mm/numa.c:428
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff8107e850-ffffffff8107e88c: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81081990)
Location: arch/x86/mm/numa.c:428
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff81081990-ffffffff810819cc: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810885a0)
Location: arch/x86/mm/numa.c:427
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810885a0-ffffffff810885dc: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff8108c1e0)
Location: arch/x86/mm/numa.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff8108c1e0-ffffffff8108c220: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff8108ce40)
Location: arch/x86/mm/numa.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff8108ce40-ffffffff8108ce80: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810943e0)
Location: arch/x86/mm/numa.c:439
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810943e0-ffffffff81094420: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810937e0)
Location: arch/x86/mm/numa.c:437
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810937e0-ffffffff81093820: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810941a0)
Location: arch/x86/mm/numa.c:443
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:find_numa_distance
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810941a0-ffffffff810941df: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810a3fd0)
Location: arch/x86/mm/numa.c:442
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:init_numa_topology_type
  - kernel/sched/topology.c:find_numa_distance
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810a3fd0-ffffffff810a400f: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810b86f0)
Location: arch/x86/mm/numa.c:442
Inline: False
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:find_numa_distance
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/migrate.c:__set_migration_target_nodes
  - mm/migrate.c:__set_migration_target_nodes
  - mm/khugepaged.c:khugepaged_scan_abort
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810b86f0-ffffffff810b8743: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810d3f30)
Location: arch/x86/mm/numa.c:442
Inline: False
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:find_numa_distance
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/khugepaged.c:hpage_collapse_scan_abort
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810d3f30-ffffffff810d3f83: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810d7310)
Location: arch/x86/mm/numa.c:442
Inline: False
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:find_numa_distance
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/khugepaged.c:hpage_collapse_scan_abort
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810d7310-ffffffff810d7363: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff810dfb90)
Location: arch/x86/mm/numa.c:444
Inline: False
Direct callers:
  - kernel/sched/fair.c:can_migrate_task
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/build_utility.c:sched_domains_numa_masks_set
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:sched_init_numa
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:init_numa_topology_type
  - kernel/sched/build_utility.c:find_numa_distance
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:find_next_best_node
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - mm/memory-tiers.c:establish_demotion_targets
  - mm/khugepaged.c:hpage_collapse_scan_abort
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff810dfb90-ffffffff810dfbe3: __node_distance (STB_GLOBAL)
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
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/numa.c (ffff800011438880)
Location: arch/arm64/mm/numa.c:339
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:pcpu_cpu_distance
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffff8000100b2078-ffff8000100b20e4: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __node_distance(int a, int b);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/numa.c (c0000000000a1660)
Location: arch/powerpc/mm/numa.c:188
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
c0000000000a1660-c0000000000a170c: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff8108be00)
Location: arch/x86/mm/numa.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
  - drivers/nvme/host/multipath.c:__nvme_find_path
```
**Symbols:**

```
ffffffff8108be00-ffffffff8108be40: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff8107a930)
Location: arch/x86/mm/numa.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
  - drivers/nvme/host/multipath.c:__nvme_find_path
```
**Symbols:**

```
ffffffff8107a930-ffffffff8107a970: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff8108bdb0)
Location: arch/x86/mm/numa.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff8108bdb0-ffffffff8108bdf0: __node_distance (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __node_distance(int from, int to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff8108e110)
Location: arch/x86/mm/numa.c:424
Inline: False
Direct callers:
  - kernel/sched/fair.c:preferred_group_nid
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/fair.c:task_numa_migrate
  - kernel/sched/topology.c:sched_domains_numa_masks_set
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - kernel/sched/topology.c:sched_init_numa
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:build_zonelists
  - mm/page_alloc.c:get_page_from_freelist
  - mm/sparse-vmemmap.c:vmemmap_verify
  - drivers/acpi/numa.c:acpi_map_pxm_to_online_node
  - drivers/base/node.c:node_read_distance
```
**Symbols:**

```
ffffffff8108e110-ffffffff8108e150: __node_distance (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int a</code>
</li>
<li>
<b>Param added. </b>
<code>int b</code>
</li>
<li>
<b>Param removed. </b>
<code>int from</code>
</li>
<li>
<b>Param removed. </b>
<code>int to</code>
</li>
</ul>
</details>
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
