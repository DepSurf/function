# Function: <code>__next_node_in</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81433eb0)
Location: lib/nodemask.c:5
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cpuset.c:cpuset_slab_spread_node
  - kernel/cpuset.c:cpuset_mem_spread_node
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/memory_hotplug.c:new_node_page
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81433eb0-ffffffff81433efe: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81450130)
Location: lib/nodemask.c:5
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cpuset.c:cpuset_slab_spread_node
  - kernel/cpuset.c:cpuset_mem_spread_node
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_zonelist
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/memory_hotplug.c:new_node_page
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/page_isolation.c:alloc_migrate_target
```
**Symbols:**

```
ffffffff81450130-ffffffff81450185: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff818efee0)
Location: lib/nodemask.c:5
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff818efee0-ffffffff818eff23: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81976330)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81976330-ffffffff81976373: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff819d2af0)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff819d2af0-ffffffff819d2b38: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81a0c170)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81a0c170-ffffffff81a0c1b8: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81a7bad0)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81a7bad0-ffffffff81a7bb20: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81ab2e30)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81ab2e30-ffffffff81ab2e80: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff815ed6d0)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff815ed6d0-ffffffff815ed724: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81611e00)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff81611e00-ffffffff81611e54: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff815f54e0)
Location: lib/nodemask.c:6
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:hstate_next_node_to_alloc
  - mm/hugetlb.c:hstate_next_node_to_alloc
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff815f54e0-ffffffff815f5544: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81662950)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:hstate_next_node_to_alloc
  - mm/hugetlb.c:hstate_next_node_to_alloc
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff81662950-ffffffff816629aa: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff8177c7d0)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages_bulk_array_mempolicy
  - mm/mempolicy.c:alloc_pages
  - mm/mempolicy.c:vma_alloc_folio
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff8177c7d0-ffffffff8177c847: __next_node_in (STB_GLOBAL)
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093ba7)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/mm/numa.c (ffffffff83e9e5c3)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8121ecc7)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In mm/hugetlb.c (ffffffff8140ab8e)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81415181)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_get_mempolicy
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096b37)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/mm/numa.c (ffffffff836c2723)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81234dbd)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In mm/hugetlb.c (ffffffff8143e23e)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_huge_page
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff8144875e)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_get_mempolicy
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e0a7)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
```
In arch/x86/mm/numa.c (ffffffff838f3123)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8124e9dd)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
```
In mm/hugetlb.c (ffffffff81477ece)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:remove_pool_hugetlb_folio
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81481fb4)
Location: include/linux/nodemask.h:280
Inline: True
Inline callers:
  - mm/mempolicy.c:interleave_nodes
  - mm/mempolicy.c:do_get_mempolicy
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
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffff800010d8d090)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffff800010d8d090-ffff800010d8d0f0: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (c0e875d4)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
**Symbols:**

```
c0e875d4-c0e87614: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (c000000000ecf280)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
c000000000ecf280-c000000000ecf318: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffe0008b5de4)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
```
**Symbols:**

```
ffffffe0008b5de4-ffffffe0008b5e34: __next_node_in (STB_GLOBAL)
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
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81a51c80)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81a51c80-ffffffff81a51cd0: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81a0ed80)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81a0ed80-ffffffff81a0edd0: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81abe070)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81abe070-ffffffff81abe0c0: __next_node_in (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __next_node_in(int node, const nodemask_t *srcp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nodemask.c (ffffffff81aca510)
Location: lib/nodemask.c:6
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - kernel/cgroup/cpuset.c:cpuset_slab_spread_node
  - kernel/cgroup/cpuset.c:cpuset_mem_spread_node
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:free_pool_huge_page
  - mm/hugetlb.c:get_valid_node_allowed
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
  - mm/mempolicy.c:huge_node
  - mm/mempolicy.c:mempolicy_slab_node
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/memcontrol.c:mem_cgroup_select_victim_node
```
**Symbols:**

```
ffffffff81aca510-ffffffff81aca560: __next_node_in (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
