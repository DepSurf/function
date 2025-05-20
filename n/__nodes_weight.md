# Function: <code>__nodes_weight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810519a6)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:smp_announce
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff81f78e5a)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81f79138)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff81f7c2e6)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In kernel/sched/fair.c (ffffffff810b5f99)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_migrate
```
```
In mm/page_alloc.c (ffffffff81f8751a)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/hugetlb.c (ffffffff811dabf0)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
Direct callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff811e0450)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:node_random
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff811efb07)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff81f9956c)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In drivers/acpi/numa.c (ffffffff8148b142)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff816b77dd)
Location: include/linux/nodemask.h:226
Inline: True
```
**Symbols:**

```
ffffffff811dabf0-ffffffff811dabfe: __nodes_weight.constprop.52 (STB_LOCAL)
ffffffff811e0450-ffffffff811e045e: __nodes_weight.constprop.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105208a)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
  - arch/x86/kernel/smpboot.c:smp_announce
```
```
In arch/x86/mm/numa.c (ffffffff81fa1585)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fa188e)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff81fa5089)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
```
```
In mm/page_alloc.c (ffffffff81fb0449)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff811f9daa)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
Direct callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff811ffeea)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff8120ef52)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff81fc42df)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In lib/nodemask.c (ffffffff81433f0a)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/numa.c (ffffffff814d9f7c)
Location: include/linux/nodemask.h:228
Inline: True
```
```
In drivers/md/dm.c (ffffffff81703b4f)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817192b6)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
**Symbols:**

```
ffffffff811f8d60-ffffffff811f8d6e: __nodes_weight.constprop.54 (STB_LOCAL)
ffffffff811fe730-ffffffff811fe73e: __nodes_weight.constprop.36 (STB_LOCAL)
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
In arch/x86/kernel/smpboot.c (ffffffff81054961)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff81fdc354)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff81fdce6f)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff81fe09ee)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff81fe5d2a)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff81fed11b)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/hugetlb.c (ffffffff8120a861)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81ff2baf)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81221056)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff82000d98)
Location: include/linux/nodemask.h:228
Inline: True
```
```
In lib/nodemask.c (ffffffff81450191)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/numa.c (ffffffff814fc832)
Location: include/linux/nodemask.h:228
Inline: True
```
```
In drivers/md/dm.c (ffffffff81735a08)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8174b8f5)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/smpboot.c (ffffffff810542ab)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff820bd36b)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff820bde79)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff820c183d)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff820c6646)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff820ced86)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/hugetlb.c (ffffffff81215bd9)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff820d5279)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8122c91d)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff820e467a)
Location: include/linux/nodemask.h:228
Inline: True
```
```
In drivers/acpi/numa.c (ffffffff8150cb9d)
Location: include/linux/nodemask.h:228
Inline: True
```
```
In drivers/md/dm.c (ffffffff8174ee38)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817696d6)
Location: include/linux/nodemask.h:228
Inline: True
```
```
In lib/nodemask.c (ffffffff818eff31)
Location: include/linux/nodemask.h:228
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/kernel/smpboot.c (ffffffff81058046)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff826c41aa)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff826c4cb0)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff826c9a2e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff826cecb2)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff826d77a1)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/hugetlb.c (ffffffff8123080c)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff826dde3f)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff81248151)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff826ed319)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/acpi/numa.c (ffffffff8154fafd)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff817c1058)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff817df46c)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81976381)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
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
In arch/x86/kernel/smpboot.c (ffffffff8105acdb)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff826ee445)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff826eef36)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff826f3c0d)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff826f93c6)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff82701be2)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
```
In mm/hugetlb.c (ffffffff81252fce)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff82708399)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff8126ba85)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
```
In security/apparmor/lsm.c (ffffffff82717647)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/acpi/numa.c (ffffffff8158639d)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff818096d5)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81829430)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff819d2b40)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106095b)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
```
In arch/x86/mm/numa.c (ffffffff828a5133)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff828a5c24)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff828aa9f5)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff828b02a0)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff828b86db)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff81267a3e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
Direct callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8126f235)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffffffff81a2204a)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff828cf017)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In drivers/acpi/numa.c (ffffffff8159e6ad)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff818357e5)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81853e60)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81a0c1c0)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff8126cf8b-ffffffff8126cf9b: __nodes_weight.constprop.78 (STB_LOCAL)
ffffffff8126d3d0-ffffffff8126d3e0: __nodes_weight.constprop.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063450)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff8108c404)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108c425)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810bef43)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff8114386f)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff81273a5b)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff81281400)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8128a116)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/memory_hotplug.c (ffffffff8129be80)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff8148e3d5)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/acpi/numa.c (ffffffff815cfbad)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff81876b15)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81897840)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81a7bb20)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81063450-ffffffff81063467: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108c404-ffffffff8108c41b: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108c425-ffffffff8108c43c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff810bef43-ffffffff810bef5a: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8114386f-ffffffff81143886: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81273a5b-ffffffff81273a72: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81281400-ffffffff81281410: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81288790-ffffffff812887a0: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8129be80-ffffffff8129be97: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8148e3d5-ffffffff8148e3ec: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81897840-ffffffff81897857: __nodes_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063b00)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106da13)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff8108d064)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108d085)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810c546f)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff8114f353)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff812828cb)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff81290cf0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81299c86)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/memory_hotplug.c (ffffffff812abc40)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff814a8295)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/acpi/numa.c (ffffffff815f0e1d)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff818a8915)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818c9e00)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81ab2e80)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81063b00-ffffffff81063b17: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8106da13-ffffffff8106da2a: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108d064-ffffffff8108d07b: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108d085-ffffffff8108d09c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff810c546f-ffffffff810c5486: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8114f353-ffffffff8114f36a: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812828cb-ffffffff812828e2: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81290cf0-ffffffff81290d00: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81298300-ffffffff81298310: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812abc40-ffffffff812abc57: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff814a8295-ffffffff814a82ac: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff818c9e00-ffffffff818c9e17: __nodes_weight.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/smpboot.c (ffffffff81069993)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1643)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff82ce6c4e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff82ce79d1)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff82ced78b)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff82cf218d)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff82cfc584)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff812c50e4)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff82cfe501)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812e05ed)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In fs/io-wq.c (ffffffff8138a925)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_manager
```
```
In lib/nodemask.c (ffffffff815ed730)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/numa/srat.c (ffffffff816e7a1d)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197a135)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199b5c2)
Location: include/linux/nodemask.h:238
Inline: True
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
In arch/x86/kernel/smpboot.c (ffffffff8106b663)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce3ea)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff82fd45cd)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff82fd53c8)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff82fd9de5)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff82fdec66)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff82fe8f9f)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff812d0ce4)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff82feaef4)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (ffffffff812ebdcd)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In lib/nodemask.c (ffffffff81611e6e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/numa/srat.c (ffffffff8170530d)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197e775)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8199e662)
Location: include/linux/nodemask.h:238
Inline: True
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831ceb8c)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8106c043)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d8e8e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff831df14c)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff831dfe7e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff831e479c)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff831e9778)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff831f37d9)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff812c6745)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff812d7a3a)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff831f5840)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In lib/nodemask.c (ffffffff815f555e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/numa/srat.c (ffffffff816e69bd)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff819625c5)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff819832c9)
Location: include/linux/nodemask.h:238
Inline: True
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b0e32)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81076c2b)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc355)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff832c26a1)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff832c344b)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff832c8458)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff832cdd7b)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff832d9a15)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff8130b1ab)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff8131e343)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff832dbee3)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In lib/nodemask.c (ffffffff816629be)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/numa/srat.c (ffffffff8175fe66)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff81a09805)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81a2c8b9)
Location: include/linux/nodemask.h:238
Inline: True
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83461fc9)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81085ac9)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346dc72)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff81e5189f)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:node_set_online
```
```
In kernel/workqueue.c (ffffffff8347b564)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff83481a29)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/bpf/core.c (ffffffff8126c33e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_alloc
```
```
In mm/vmalloc.c (ffffffff8136703d)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff8348e9dc)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff81373c38)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff81389ddb)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff83491681)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In lib/nodemask.c (ffffffff8177c85e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
```
In drivers/acpi/numa/srat.c (ffffffff81893804)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff81b71145)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81b98065)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e8423d)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff81098d06)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e939c2)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff83e9e91b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff83ea63e5)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff83eaec7a)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81217950)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:node_random
```
```
In kernel/bpf/core.c (ffffffff812c40af)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/vmalloc.c (ffffffff813e2edd)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/page_alloc.c (ffffffff83ec0c75)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/memory_hotplug.c (ffffffff813f1385)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In mm/hugetlb.c (ffffffff8140ab5b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff83ec4a6f)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory-tiers.c (ffffffff81437961)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In drivers/acpi/numa/srat.c (ffffffff819db2e4)
Location: include/linux/nodemask.h:239
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d0df55)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81d39313)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a778d)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff8109c01b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b74df)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff836c2a7b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:alloc_node_data
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/workqueue.c (ffffffff836caba5)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffffffff836d3caa)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81234e1d)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/bpf/core.c (ffffffff812eb05f)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/mm_init.c (ffffffff836e25cd)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/vmalloc.c (ffffffff81417b3a)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/memory_hotplug.c (ffffffff81424ec5)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
```
In mm/hugetlb.c (ffffffff8143e20b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff836e9b8f)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:offset_il_node
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory-tiers.c (ffffffff8146d621)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In drivers/acpi/numa/srat.c (ffffffff81a22f94)
Location: include/linux/nodemask.h:239
Inline: True
```
```
In drivers/md/dm.c (ffffffff81d77555)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81da3db3)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d7ccd)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init
```
```
In arch/x86/kernel/smpboot.c (ffffffff810a361b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:announce_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7def)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff838f349b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:init_gi_nodes
  - arch/x86/mm/numa.c:init_cpu_to_node
```
```
In kernel/smp.c (ffffffff83905c8a)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ea3d)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In kernel/bpf/core.c (ffffffff81309574)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/core.c:alloc_new_pack
```
```
In mm/mm_init.c (ffffffff83914ece)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init
  - mm/mm_init.c:find_zone_movable_pfns_for_nodes
```
```
In mm/vmalloc.c (ffffffff8144468a)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_node_range
```
```
In mm/memory_hotplug.c (ffffffff81452105)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:__try_online_node
```
```
In mm/hugetlb.c (ffffffff81477e9b)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_hugetlb_folio
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8391cf4f)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:interleave_nid
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory-tiers.c (ffffffff8149c791)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - mm/memory-tiers.c:next_demotion_node
```
```
In drivers/md/dm.c (ffffffff81e2e785)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5be43)
Location: include/linux/nodemask.h:239
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/arm64/mm/numa.c (ffff8000100b2344)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:node_set_online
```
```
In kernel/workqueue.c (ffff800011442ef4)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_numa_init
```
```
In kernel/smp.c (ffff800011449714)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffff80001031b168)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffff80001032fa14)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
Direct callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffff800010338a00)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
```
```
In mm/memory_hotplug.c (ffff80001034dbd8)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In security/apparmor/lsm.c (ffff80001146b774)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - security/apparmor/lsm.c:alloc_buffers
```
```
In drivers/acpi/numa.c (ffff80001077b950)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffff800010afd038)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In lib/nodemask.c (ffff800010d8d0f0)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffff80001031b168-ffff80001031b184: __nodes_weight.constprop.0 (STB_LOCAL)
ffff80001032e320-ffff80001032e338: __nodes_weight.constprop.0 (STB_LOCAL)
ffff800010337160-ffff800010337178: __nodes_weight.constprop.0 (STB_LOCAL)
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
In arch/powerpc/mm/numa.c (c0000000000a3a3c)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:node_set_online
```
```
In arch/powerpc/platforms/powernv/memtrace.c (c0000000000e0984)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/memtrace.c:memtrace_init_regions_runtime
```
```
In arch/powerpc/perf/imc-pmu.c (c00000000012d508)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
  - arch/powerpc/perf/imc-pmu.c:init_imc_pmu
```
```
In kernel/workqueue.c (c000000001366e5c)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (c00000000136ea00)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (c000000001381770)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (c0000000004082fc)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (c000000001383e60)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_relative_nodemask
```
```
In mm/memory_hotplug.c (c00000000042d5e4)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (c00000000139a334)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/md/dm.c (c000000000beb3f8)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In lib/nodemask.c (c000000000ecf33c)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffe0000156c4)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffe00022d51e)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
Direct callers:
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
**Symbols:**

```
ffffffe00022c22a-ffffffe00022c248: __nodes_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810635f0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff8108c024)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108c045)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810bf7df)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff81147973)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff8127af1b)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff812892d0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81292266)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/memory_hotplug.c (ffffffff812a4220)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff814a0875)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/acpi/numa.c (ffffffff815dfaad)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81746b15)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
```
```
In drivers/md/dm.c (ffffffff8184e795)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff8186e520)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81a51cd0)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff810635f0-ffffffff81063607: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108c024-ffffffff8108c03b: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108c045-ffffffff8108c05c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff810bf7df-ffffffff810bf7f6: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81147973-ffffffff8114798a: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8127af1b-ffffffff8127af32: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812892d0-ffffffff812892e0: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812908e0-ffffffff812908f0: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812a4220-ffffffff812a4237: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff814a0875-ffffffff814a088c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8186e520-ffffffff8186e537: __nodes_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053900)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff8107ab54)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff8107ab75)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810adfff)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff8113ac23)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff8126cdfb)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff8127b170)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81283e76)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/memory_hotplug.c (ffffffff81295cf0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff81491295)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/acpi/numa.c (ffffffff815cb0ed)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81728795)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns_head
```
```
In drivers/md/dm.c (ffffffff81815db5)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818364e0)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81a0edd0)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81053900-ffffffff81053917: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8107ab54-ffffffff8107ab6b: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8107ab75-ffffffff8107ab8c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff810adfff-ffffffff810ae016: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8113ac23-ffffffff8113ac3a: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8126cdfb-ffffffff8126ce12: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8127b170-ffffffff8127b180: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81282560-ffffffff81282570: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81295cf0-ffffffff81295d07: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81491295-ffffffff814912ac: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff818364e0-ffffffff818364f7: __nodes_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063aa0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/mm/numa.c (ffffffff8108bfd4)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108bff5)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810bed3f)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff81145823)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff81278cbb)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff812870e0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81290076)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/memory_hotplug.c (ffffffff812a2030)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff8149c915)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/acpi/numa.c (ffffffff815e50fd)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff8189ddc5)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818bf2b0)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81abe0c0)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81063aa0-ffffffff81063ab7: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108bfd4-ffffffff8108bfeb: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108bff5-ffffffff8108c00c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff810bed3f-ffffffff810bed56: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81145823-ffffffff8114583a: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81278cbb-ffffffff81278cd2: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812870e0-ffffffff812870f0: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8128e6f0-ffffffff8128e700: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812a2030-ffffffff812a2047: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8149c915-ffffffff8149c92c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff818bf2b0-ffffffff818bf2c7: __nodes_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81065060)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106f0e3)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
  - arch/x86/kernel/apic/x2apic_uv_x.c:build_socket_tables
```
```
In arch/x86/mm/numa.c (ffffffff8108e334)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
```
```
In arch/x86/mm/amdtopology.c (ffffffff8108e355)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/workqueue.c (ffffffff810c70c7)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init
```
```
In kernel/smp.c (ffffffff81152433)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - kernel/smp.c:smp_init
```
```
In mm/page_alloc.c (ffffffff812888ab)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/page_alloc.c:page_alloc_init
  - mm/page_alloc.c:find_zone_movable_pfns_for_nodes
```
```
In mm/hugetlb.c (ffffffff81297820)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8129fea6)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_relative_nodemask
Direct callers:
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:offset_il_node
```
```
In mm/memory_hotplug.c (ffffffff812b22c0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:add_memory_resource
```
```
In security/apparmor/lsm.c (ffffffff814b4ea0)
Location: include/linux/nodemask.h:238
Inline: True
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
```
```
In drivers/acpi/numa.c (ffffffff815fefad)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In drivers/md/dm.c (ffffffff818ba175)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_numa_node
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff818db5c0)
Location: include/linux/nodemask.h:238
Inline: True
```
```
In lib/nodemask.c (ffffffff81aca560)
Location: include/linux/nodemask.h:238
Inline: True
Inline callers:
  - lib/nodemask.c:node_random
```
**Symbols:**

```
ffffffff81065060-ffffffff81065077: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8106f0e3-ffffffff8106f0fa: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108e334-ffffffff8108e34b: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8108e355-ffffffff8108e36c: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff810c70c7-ffffffff810c70de: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81152433-ffffffff8115244a: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812888ab-ffffffff812888c2: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff81297820-ffffffff81297830: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff8129e5f0-ffffffff8129e600: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff812b22c0-ffffffff812b22d7: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff814b4ea0-ffffffff814b4eb7: __nodes_weight.constprop.0 (STB_LOCAL)
ffffffff818db5c0-ffffffff818db5d7: __nodes_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
