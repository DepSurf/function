# Function: <code>__nodes_clear</code>

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
In arch/x86/mm/numa.c (ffffffff81f78a34)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810bb065)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/cpuset.c (ffffffff8111b489)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff81191f20)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff811dc09e)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff811e0469)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_parse_str
```
```
In mm/slub.c (ffffffff811e946c)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff81560b25)
Location: include/linux/nodemask.h:134
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
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
In arch/x86/mm/numa.c (ffffffff81fa11d6)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810be4c5)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
```
In kernel/cpuset.c (ffffffff81123399)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff811a69ed)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff811fa33e)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81201e04)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff81207d01)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff815b5262)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
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
In arch/x86/mm/numa.c (ffffffff81fdc8ec)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810bdc4d)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cpuset.c (ffffffff8112ba10)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_css_alloc
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff811b6cc6)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8120a803)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8121395a)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81219d35)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff815e452b)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
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
In arch/x86/mm/numa.c (ffffffff820bd91f)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810b8bd1)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8112f2c1)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff811bec06)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81215b83)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8121ecda)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81225a9d)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff815f912b)
Location: include/linux/nodemask.h:136
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
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
In arch/x86/mm/numa.c (ffffffff826c4756)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810c0a31)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8113c16d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff811d3906)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff812307b6)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81239efa)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:SYSC_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8124112d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff816611fb)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
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
In arch/x86/mm/numa.c (ffffffff826ee9f8)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810c6042)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8114a3f2)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff811f4bff)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81252f99)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8125d6b4)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff812640d0)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff8169c9c7)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
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
In arch/x86/mm/numa.c (ffffffff828a56e6)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810d0612)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff81156f91)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff81206fdf)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81267a09)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff81271f4c)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff81278840)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff816bd217)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_mem_sect_under_nodes
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
In arch/x86/mm/numa.c (ffffffff828bdc7f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810d8541)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff81163b0b)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff8126d045)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8128216f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
```
```
In mm/mempolicy.c (ffffffff8128d578)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129493d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
```
In drivers/base/node.c (ffffffff816f7fc5)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - drivers/base/node.c:unregister_memory_block_under_nodes
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
In arch/x86/mm/numa.c (ffffffff828c4109)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810e2e41)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8116f940)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff8127c0c5)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81291c00)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8129cf9f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff812a470d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
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
In arch/x86/mm/numa.c (ffffffff82ce7696)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810ec3a0)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff81181cad)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffff812c5372)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812d0b7f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff812d8e9d)
Location: include/linux/nodemask.h:146
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
In arch/x86/mm/numa.c (ffffffff82fd500b)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810e9eb0)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8117ebbd)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffff812d0f82)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812dc69f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff812e448d)
Location: include/linux/nodemask.h:146
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
In arch/x86/mm/numa.c (ffffffff831dfad8)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810eb7a3)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8117ebcd)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffff812d7d62)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812e3edc)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
```
```
In mm/slub.c (ffffffff812eb691)
Location: include/linux/nodemask.h:146
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
In arch/x86/mm/numa.c (ffffffff832c305d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff81103323)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff811a6d8d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffff8131e772)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8132b1cc)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff81333d61)
Location: include/linux/nodemask.h:146
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
In arch/x86/mm/numa.c (ffffffff834758de)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff8111ea04)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff811d7d91)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffff81389d5d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8139ac34)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff813a5045)
Location: include/linux/nodemask.h:146
Inline: True
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
In arch/x86/mm/numa.c (ffffffff83e9e385)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff81147dc1)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8121cca1)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffff8140aadd)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8141aca4)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff81425a95)
Location: include/linux/nodemask.h:147
Inline: True
```
```
In mm/khugepaged.c (ffffffff8144cb00)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
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
In arch/x86/mm/numa.c (ffffffff836c24e5)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff81157c65)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff812330ed)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffff8143e18d)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8144e21c)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8145ad25)
Location: include/linux/nodemask.h:147
Inline: True
```
```
In mm/khugepaged.c (ffffffff814823ab)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
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
In arch/x86/mm/numa.c (ffffffff838f2ee5)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff81163eb5)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8124d225)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/slub.c (ffffffff81456085)
Location: include/linux/nodemask.h:147
Inline: True
```
```
In mm/hugetlb.c (ffffffff81477e1d)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_store
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff81487dbc)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
  - mm/mempolicy.c:do_get_mempolicy
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/khugepaged.c (ffffffff814b1751)
Location: include/linux/nodemask.h:147
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:hpage_collapse_scan_file
  - mm/khugepaged.c:hpage_collapse_scan_pmd
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
In arch/arm64/mm/numa.c (ffff800011438d30)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_init
  - arch/arm64/mm/numa.c:numa_init
  - arch/arm64/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (0)
Location: include/linux/nodemask.h:146
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3680)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:146
Inline: True
```
```
In mm/hugetlb.c (ffff80001032fd28)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffff80001033aa38)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
```
```
In mm/slub.c (ffff800010344c9c)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
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
In kernel/cgroup/cpuset.c (c0424338)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/slub.c (c054a16c)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
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
In kernel/sched/fair.c (c000000000193d20)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
```
In kernel/cgroup/cpuset.c (c0000000002530c0)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (c0000000003e4afc)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (c0000000004082ac)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (c000000000416fe0)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (c000000000422de8)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
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
In kernel/cgroup/cpuset.c (ffffffe000159c5e)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/hugetlb.c (ffffffe000017ba6)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/slub.c (ffffffe000238b50)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
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
In arch/x86/mm/numa.c (ffffffff828af0df)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810dcff1)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff81167f60)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff81274715)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8128a1e0)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8129557f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129cced)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
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
In arch/x86/mm/numa.c (ffffffff828a72d1)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810cc001)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff8115b180)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff81266685)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff8127c010)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8128718f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8128e87d)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
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
In arch/x86/mm/numa.c (ffffffff828c1fde)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810d9371)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff81165d30)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff812724b5)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81287ff0)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff8129338f)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff8129aafd)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
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
In arch/x86/mm/numa.c (ffffffff828c5129)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/sched/fair.c (ffffffff810e4da1)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/sched/fair.c:preferred_group_nid
```
```
In kernel/cgroup/cpuset.c (ffffffff81173310)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/page_alloc.c (ffffffff81281de5)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/page_alloc.c:build_zonelists
```
```
In mm/hugetlb.c (ffffffff81298430)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:__nr_hugepages_store_common
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
```
```
In mm/mempolicy.c (ffffffff812a31ef)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:init_nodemask_of_mempolicy
  - mm/mempolicy.c:kernel_get_mempolicy
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:migrate_to_node
```
```
In mm/slub.c (ffffffff812aa9dd)
Location: include/linux/nodemask.h:146
Inline: True
Inline callers:
  - mm/slub.c:process_slab
```
</details>
</li>
</ul>

## Differences
