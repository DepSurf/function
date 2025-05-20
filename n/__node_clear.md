# Function: <code>__node_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __node_clear(int node, volatile nodemask_t *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d5bb)
Location: include/linux/nodemask.h:122
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810bb0c8)
Location: include/linux/nodemask.h:122
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
  - kernel/sched/fair.c:task_numa_fault
```
```
In mm/vmstat.c (ffffffff811ad8b9)
Location: include/linux/nodemask.h:122
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/mempolicy.c (ffffffff811e158c)
Location: include/linux/nodemask.h:122
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/memory_hotplug.c (ffffffff811ef2c0)
Location: include/linux/nodemask.h:122
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
```
```
In mm/memcontrol.c (ffffffff811ff3c3)
Location: include/linux/nodemask.h:122
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff8107d5bb-ffffffff8107d5c5: __node_clear.constprop.8 (STB_LOCAL)
ffffffff811ef2c0-ffffffff811ef2ce: __node_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __node_clear(int node, volatile nodemask_t *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f0a0)
Location: include/linux/nodemask.h:124
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810be52f)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In mm/vmstat.c (ffffffff811c6b05)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/mempolicy.c (ffffffff811fff73)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/memory_hotplug.c (ffffffff8120ef49)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff8122313d)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff8107f0a0-ffffffff8107f0aa: __node_clear.constprop.9 (STB_LOCAL)
ffffffff8120e570-ffffffff8120e57e: __node_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __node_clear(int node, volatile nodemask_t *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81083756)
Location: include/linux/nodemask.h:124
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810bdcd6)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff811d6c6c)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mempolicy.c (ffffffff81211b62)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/memory_hotplug.c (ffffffff8122104d)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff81235605)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81083756-ffffffff81083760: __node_clear.constprop.9 (STB_LOCAL)
ffffffff812205b0-ffffffff812205be: __node_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __node_clear(int node, volatile nodemask_t *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106cec0)
Location: include/linux/nodemask.h:124
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810b8c52)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff811dfacc)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mempolicy.c (ffffffff8121ba0b)
Location: include/linux/nodemask.h:124
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8122c914)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff81241020)
Location: include/linux/nodemask.h:124
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff8106cec0-ffffffff8106ceca: __node_clear.constprop.17 (STB_LOCAL)
ffffffff8122c250-ffffffff8122c25e: __node_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __node_clear(int node, volatile nodemask_t *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81071bdf)
Location: include/linux/nodemask.h:134
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810c0ab2)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff811f58dc)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mempolicy.c (ffffffff81236d0b)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81248148)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff81260d60)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81071bdf-ffffffff81071be9: __node_clear.constprop.18 (STB_LOCAL)
ffffffff81247a20-ffffffff81247a2e: __node_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __node_clear(int node, volatile nodemask_t *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810748d5)
Location: include/linux/nodemask.h:134
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810c60c3)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff81216b5c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mempolicy.c (ffffffff81259ccc)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff8126ba7c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:new_node_page
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff81284d82)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff810748d5-ffffffff810748df: __node_clear.constprop.18 (STB_LOCAL)
ffffffff8126b500-ffffffff8126b50e: __node_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void __node_clear(int node, volatile nodemask_t *dstp);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107a7e8)
Location: include/linux/nodemask.h:134
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810d0693)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff81229a6c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mempolicy.c (ffffffff8126dcdc)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812800b5)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
```
In mm/memcontrol.c (ffffffff81299c92)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff8107a7e8-ffffffff8107a7f2: __node_clear.constprop.22 (STB_LOCAL)
ffffffff8127fd90-ffffffff8127fd9e: __node_clear (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff828bc573)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810d85c1)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff8123970c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/mempolicy.c (ffffffff81289332)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81a9242d)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff812b4f4f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
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
In arch/x86/mm/init_64.c (ffffffff828c2a1a)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810e2ec1)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff81247a0c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffffffff812917f9)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81298ec2)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812abce0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff812c6a3f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
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
In arch/x86/mm/init_64.c (ffffffff82ce5e37)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810ec420)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff81275bf6)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffffffff812c4959)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812cd011)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812e05e0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/init_64.c (ffffffff82fd37b8)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810e9f30)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff812804d6)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffffffff812d05f9)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812d98a0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/memory_hotplug.c (ffffffff812ebdc0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
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
In arch/x86/mm/init_64.c (ffffffff831de3e8)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810eb81d)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff812855d6)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812c6738)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff812d6e75)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/mempolicy.c (ffffffff812e1126)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff812f290d)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
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
In arch/x86/mm/init_64.c (ffffffff832c1676)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff8110339d)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff812c3f8a)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff8130b19e)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8131cd45)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/mempolicy.c (ffffffff813283f6)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff8133a355)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
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
In arch/x86/mm/init_64.c (ffffffff83473d05)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff8111ea84)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff813217b5)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81373c2f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff8138880d)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/mempolicy.c (ffffffff813975df)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff813ac0bf)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/migrate.c (ffffffff813b11b7)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
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
In arch/x86/mm/init_64.c (ffffffff83e9b93e)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff81147e41)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff813957c5)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff813f1378)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/hugetlb.c (ffffffff814082cb)
Location: include/linux/nodemask.h:135
Inline: True
```
```
In mm/mempolicy.c (ffffffff814171b7)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff8142aa5f)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/memory-tiers.c (ffffffff820cc127)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
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
In arch/x86/mm/init_64.c (ffffffff836bf3de)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff81157ce2)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff813c83e5)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81424eb8)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/hugetlb.c (ffffffff8143b1db)
Location: include/linux/nodemask.h:135
Inline: True
```
```
In mm/mempolicy.c (ffffffff8144a749)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/slub.c (ffffffff8145fece)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/memory-tiers.c (ffffffff821503d7)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
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
In arch/x86/mm/init_64.c (ffffffff838efe7e)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff81163f32)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff813f2dd5)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff814520f8)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff8145d26e)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/slub.c:slab_memory_callback
```
```
In mm/hugetlb.c (ffffffff81474fc8)
Location: include/linux/nodemask.h:135
Inline: True
```
```
In mm/mempolicy.c (ffffffff81484193)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
```
```
In mm/memory-tiers.c (ffffffff82233217)
Location: include/linux/nodemask.h:135
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
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
In kernel/sched/fair.c (ffff800010147d88)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In mm/vmstat.c (ffff8000102dbf08)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffff80001032f53c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffff8000103376d4)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memcontrol.c (ffff800010369740)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000193df8)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In mm/vmstat.c (c00000000039bab0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (c0000000004079f8)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (c00000000041266c)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (c00000000042d5a8)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (c00000000045808c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022c8ea)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In arch/x86/mm/init_64.c (ffffffff828ad9f0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810dd071)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff8124005c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffffffff81289dd9)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff812914a2)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812a42c0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff812bf01f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
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
In arch/x86/mm/init_64.c (ffffffff828a5c8e)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810cc081)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff8123305c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffffffff8127bc09)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff81283122)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff81295d90)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff812b010f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
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
In arch/x86/mm/init_64.c (ffffffff828c08ef)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810d93f1)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff8123ddfc)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffffffff81287be9)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8128f2b2)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812a20d0)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff812bce2f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
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
In arch/x86/mm/init_64.c (ffffffff828c3a3a)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In kernel/sched/fair.c (ffffffff810e4e21)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In mm/vmstat.c (ffffffff8124d52c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/hugetlb.c (ffffffff8129817f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
```
```
In mm/mempolicy.c (ffffffff8129f732)
Location: include/linux/nodemask.h:134
Inline: True
```
```
In mm/memory_hotplug.c (ffffffff812b2360)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:new_node_page
```
```
In mm/memcontrol.c (ffffffff812cd61f)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_select_victim_node
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
