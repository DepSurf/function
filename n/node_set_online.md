# Function: <code>node_set_online</code>

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
In arch/x86/mm/numa.c (ffffffff81f78e51)
Location: include/linux/nodemask.h:435
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In mm/memory_hotplug.c (ffffffff81819a58)
Location: include/linux/nodemask.h:435
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/mm/numa.c (ffffffff81fa157c)
Location: include/linux/nodemask.h:444
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In mm/memory_hotplug.c (ffffffff818945c0)
Location: include/linux/nodemask.h:444
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/mm/numa.c (ffffffff81fdc34b)
Location: include/linux/nodemask.h:444
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff818c8cd3)
Location: include/linux/nodemask.h:444
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/mm/numa.c (ffffffff820bd362)
Location: include/linux/nodemask.h:440
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff819002bd)
Location: include/linux/nodemask.h:440
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/mm/numa.c (ffffffff826c41a1)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff8198a25d)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/mm/numa.c (ffffffff826ee43c)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff819e6b16)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/mm/numa.c (ffffffff828a512a)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81a2203e)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81a91dcd)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81ac955d)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81bc1c81)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:451
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81c3ad1b)
Location: include/linux/nodemask.h:451
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:451
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81c2d392)
Location: include/linux/nodemask.h:451
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:451
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81d4bbff)
Location: include/linux/nodemask.h:451
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void node_set_online(int nid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff81e5188f)
Location: include/linux/nodemask.h:450
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In mm/memory_hotplug.c (ffffffff81f1b4ee)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81e5188f-ffffffff81e518c2: node_set_online (STB_LOCAL)
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
Location: include/linux/nodemask.h:458
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In mm/memory_hotplug.c (ffffffff820c345e)
Location: include/linux/nodemask.h:458
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:458
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:alloc_node_data
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In mm/memory_hotplug.c (ffffffff8214723e)
Location: include/linux/nodemask.h:458
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
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
Location: include/linux/nodemask.h:458
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In mm/memory_hotplug.c (ffffffff822299f9)
Location: include/linux/nodemask.h:458
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void node_set_online(int nid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/numa.c (ffff8000100b2320)
Location: include/linux/nodemask.h:450
Inline: False
Direct callers:
  - arch/arm64/mm/numa.c:numa_init
```
```
In mm/memory_hotplug.c (ffff80001034dbbc)
Location: include/linux/nodemask.h:450
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffff8000100b2320-ffff8000100b2360: node_set_online (STB_LOCAL)
ffff80001034ded0-ffff80001034df38: node_set_online (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void node_set_online(int nid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/numa.c (c0000000000a39ec)
Location: include/linux/nodemask.h:450
Inline: False
Direct callers:
  - arch/powerpc/mm/numa.c:mem_topology_setup
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:parse_numa_properties
  - arch/powerpc/mm/numa.c:numa_setup_drmem_lmb
```
```
In mm/memory_hotplug.c (c0000000004302b8)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
c0000000000a39ec-c0000000000a3a68: node_set_online (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/numa.c (ffffffff828aeb10)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81a683cd)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81a24e8d)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81ad47dd)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
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
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In mm/memory_hotplug.c (ffffffff81ae0cbd)
Location: include/linux/nodemask.h:450
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
