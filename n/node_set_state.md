# Function: <code>node_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81f78e51)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In mm/page_alloc.c (ffffffff81208ca2)
Location: include/linux/nodemask.h:403
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/vmstat.c (ffffffff811ad902)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/memory_hotplug.c (ffffffff81819a58)
Location: include/linux/nodemask.h:403
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff81208ca2-ffffffff81208cb7: node_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81fa157c)
Location: include/linux/nodemask.h:412
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In mm/page_alloc.c (ffffffff8122e991)
Location: include/linux/nodemask.h:412
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/vmstat.c (ffffffff811c6b4d)
Location: include/linux/nodemask.h:412
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/memory_hotplug.c (ffffffff818945c0)
Location: include/linux/nodemask.h:412
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8122e991-ffffffff8122e9a6: node_set_state (STB_LOCAL)
ffffffff8120e580-ffffffff8120e595: node_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81fdc34b)
Location: include/linux/nodemask.h:412
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/page_alloc.c (ffffffff81240edd)
Location: include/linux/nodemask.h:412
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/vmstat.c (ffffffff811d6c11)
Location: include/linux/nodemask.h:412
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
Direct callers:
  - mm/vmstat.c:setup_vmstat
```
```
In mm/memory_hotplug.c (ffffffff818c8cd3)
Location: include/linux/nodemask.h:412
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81240edd-ffffffff81240ef5: node_set_state (STB_LOCAL)
ffffffff811d6740-ffffffff811d6752: node_set_state.constprop.13 (STB_LOCAL)
ffffffff812205c0-ffffffff812205d8: node_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff820bd362)
Location: include/linux/nodemask.h:408
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/page_alloc.c (ffffffff811c5571)
Location: include/linux/nodemask.h:408
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/vmstat.c (ffffffff811dfa71)
Location: include/linux/nodemask.h:408
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/memory_hotplug.c (ffffffff819002bd)
Location: include/linux/nodemask.h:408
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811c5571-ffffffff811c5589: node_set_state (STB_LOCAL)
ffffffff811df350-ffffffff811df362: node_set_state.constprop.14 (STB_LOCAL)
ffffffff8122c260-ffffffff8122c278: node_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff826c41a1)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/page_alloc.c (ffffffff811da321)
Location: include/linux/nodemask.h:418
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/vmstat.c (ffffffff811f5881)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/memory_hotplug.c (ffffffff8198a25d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811da321-ffffffff811da339: node_set_state (STB_LOCAL)
ffffffff811f4fc0-ffffffff811f4fd2: node_set_state.constprop.14 (STB_LOCAL)
ffffffff81247a30-ffffffff81247a48: node_set_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff826ee43c)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/page_alloc.c (ffffffff811fac1a)
Location: include/linux/nodemask.h:418
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/vmstat.c (ffffffff81216b01)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/memory_hotplug.c (ffffffff819e6b16)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811fac1a-ffffffff811fac32: node_set_state (STB_LOCAL)
ffffffff81216290-ffffffff812162a2: node_set_state.constprop.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828a512a)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/page_alloc.c (ffffffff8120d45e)
Location: include/linux/nodemask.h:418
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/vmstat.c (ffffffff81229a11)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/memory_hotplug.c (ffffffff81a2203e)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8120d45e-ffffffff8120d476: node_set_state (STB_LOCAL)
ffffffff81229190-ffffffff812291a2: node_set_state.constprop.16 (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff828bd6b0)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff828d240b)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828d6a1d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81a91dcd)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
In arch/x86/mm/numa.c (ffffffff828c3b3a)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff828da87d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828deeae)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81ac955d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
In arch/x86/mm/numa.c (ffffffff82ce6c3f)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff82cf8cb2)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff82cfc297)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81bc1c81)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:node_states_set_node
  - mm/memory_hotplug.c:node_states_set_node
  - mm/memory_hotplug.c:node_states_set_node
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
In arch/x86/mm/numa.c (ffffffff82fd45be)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff82fe598a)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff82fe8cb2)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81c3ad1b)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff830011c9)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
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
In arch/x86/mm/numa.c (ffffffff831df13d)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff831eff89)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff831f353f)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81c2d392)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff8320c2b9)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
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
In arch/x86/mm/numa.c (ffffffff832c2699)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff832d571b)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff832d9756)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81d4bbff)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff832f4a33)
Location: include/linux/nodemask.h:419
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void node_set_state(int node, enum node_states state);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81e5188f)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:node_set_online
```
```
In mm/vmstat.c (ffffffff81321709)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_online
Direct callers:
  - mm/vmstat.c:init_mm_internals
```
```
In mm/page_alloc.c (ffffffff81e6ee1e)
Location: include/linux/nodemask.h:418
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81f1b4ee)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff834acd7d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
```
**Symbols:**

```
ffffffff81e6c424-ffffffff81e6c437: node_set_state.constprop.0 (STB_LOCAL)
ffffffff81e6ee1e-ffffffff81e6ee58: node_set_state (STB_LOCAL)
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
In arch/x86/mm/numa.c (ffffffff83e9e912)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In mm/vmstat.c (ffffffff83eba8cb)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff83ec0842)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff820c345e)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff83ee591c)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
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
In arch/x86/mm/numa.c (ffffffff836c2a72)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:alloc_node_data
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In mm/vmstat.c (ffffffff836dfedb)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/mm_init.c (ffffffff836e25a4)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff8214723e)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff8370b2ec)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
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
In arch/x86/mm/numa.c (ffffffff838f3492)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In mm/vmstat.c (ffffffff8391278b)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/mm_init.c (ffffffff83914ea5)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff822299f9)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In drivers/acpi/numa/srat.c (ffffffff8393e785)
Location: include/linux/nodemask.h:426
Inline: True
Inline callers:
  - drivers/acpi/numa/srat.c:acpi_parse_gi_affinity
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
In arch/arm64/mm/numa.c (ffff8000100b2320)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:node_set_online
```
```
In mm/vmstat.c (ffff8000114534ac)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffff800011457c7c)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffff800010d9d160)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/nodemask.h:469
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
In arch/powerpc/mm/numa.c (c0000000000a3a00)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:node_set_online
```
```
In mm/vmstat.c (c00000000137b8c8)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (c00000000138138c)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (c0000000004302b8)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
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
In mm/vmstat.c (0)
Location: include/linux/nodemask.h:469
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:469
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
In arch/x86/mm/numa.c (ffffffff828aeb10)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff828c3731)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828c7d62)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81a683cd)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
In arch/x86/mm/numa.c (ffffffff828a6d02)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff828bbe56)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828c0487)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81a24e8d)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
In arch/x86/mm/numa.c (ffffffff828c1a0f)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff828d64b1)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828daae2)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81ad47dd)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
In arch/x86/mm/numa.c (ffffffff828c4b5a)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/vmstat.c (ffffffff828db8d2)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/vmstat.c:init_mm_internals
  - mm/vmstat.c:vmstat_cpu_online
```
```
In mm/page_alloc.c (ffffffff828dff03)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:free_area_init_nodes
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81ae0cbd)
Location: include/linux/nodemask.h:418
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
</ul>
