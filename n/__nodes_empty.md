# Function: <code>__nodes_empty</code>

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
In arch/x86/mm/numa.c (0)
Location: include/linux/nodemask.h:214
Inline: True
```
```
In kernel/cpuset.c (0)
Location: include/linux/nodemask.h:214
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:214
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:214
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
In arch/x86/mm/numa.c (0)
Location: include/linux/nodemask.h:216
Inline: True
```
```
In kernel/cpuset.c (0)
Location: include/linux/nodemask.h:216
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:216
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:216
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/nodemask.h:216
Inline: True
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
In arch/x86/mm/numa.c (ffffffff81fdc9ee)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cpuset.c (ffffffff8112e600)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_can_attach
```
```
In mm/mempolicy.c (ffffffff81213dd8)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_preferred
```
```
In mm/slub.c (ffffffff8121e47d)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff81220e5c)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff820bd9ec)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8112fcb3)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In mm/mempolicy.c (ffffffff8121f0e6)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff8122a045)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff8122c6fe)
Location: include/linux/nodemask.h:216
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff826c4823)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8113ccd0)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In mm/mempolicy.c (ffffffff8123a306)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff812451f5)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff81247ede)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff826eeac5)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8114b475)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In mm/mempolicy.c (ffffffff8125d8b6)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff8126930c)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff8126b82e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff828a57b3)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81157d90)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
```
```
In mm/mempolicy.c (ffffffff81272146)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff81278d24)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff812800be)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff828bdd70)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff811622cb)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff8128d785)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff81294e1c)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff8129c0ee)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff828c41d6)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8116dfe3)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff8129d445)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff812a4bfe)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff812ac19e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff82ce7004)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e6b2)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff812d1045)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
```
```
In mm/slub.c (ffffffff812d93a7)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff812e107e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
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
In arch/x86/mm/numa.c (ffffffff82fd4983)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117b522)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff812dcb65)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
```
```
In mm/slub.c (ffffffff812e4a1f)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff812ec1e2)
Location: include/linux/nodemask.h:226
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
In arch/x86/mm/numa.c (ffffffff831df446)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff8117f0ab)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/memory_hotplug.c (ffffffff812c6baa)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In mm/mempolicy.c (ffffffff812e43a7)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
```
```
In mm/slub.c (ffffffff812ec1f4)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
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
In arch/x86/mm/numa.c (ffffffff832c2843)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In kernel/cgroup/cpuset.c (ffffffff811a726b)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/memory_hotplug.c (ffffffff8130b656)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In mm/mempolicy.c (ffffffff8132b6c7)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/slub.c (ffffffff81333528)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/migrate.c (ffffffff8133e32d)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/migrate.c:__set_migration_target_nodes
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080c45)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
```
```
In arch/x86/mm/numa.c (ffffffff83474f5c)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff83475e32)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff811d830f)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/memory_hotplug.c (ffffffff813740a6)
Location: include/linux/nodemask.h:226
Inline: True
```
```
In mm/mempolicy.c (ffffffff8139b2a8)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/slub.c (ffffffff813a4d11)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/migrate.c (ffffffff813b11fe)
Location: include/linux/nodemask.h:226
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810939b5)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
```
```
In arch/x86/mm/numa.c (ffffffff83e9d8fc)
Location: include/linux/nodemask.h:227
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff83e9ebbc)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8121d263)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/memory_hotplug.c (ffffffff813f1b4c)
Location: include/linux/nodemask.h:227
Inline: True
```
```
In mm/mempolicy.c (ffffffff8141b328)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/slub.c (ffffffff81424fce)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memory-tiers.c (ffffffff820cc130)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096935)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
```
```
In arch/x86/mm/numa.c (ffffffff836c1682)
Location: include/linux/nodemask.h:227
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff836c2d30)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff812336fc)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/memory_hotplug.c (ffffffff814255ec)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/mempolicy.c (ffffffff8144e8d8)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/slub.c (ffffffff8145a37e)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memory-tiers.c (ffffffff821503e0)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109dea5)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:arch_node_attr_is_visible
```
```
In arch/x86/mm/numa.c (ffffffff838f2082)
Location: include/linux/nodemask.h:227
Inline: True
```
```
In arch/x86/mm/amdtopology.c (ffffffff838f3920)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - arch/x86/mm/amdtopology.c:amd_numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8124d56e)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach_check
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/memory_hotplug.c (ffffffff814528f4)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/memory_hotplug.c:do_migrate_range
```
```
In mm/slub.c (ffffffff8145544e)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/mempolicy.c (ffffffff81488478)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:mpol_parse_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new
  - mm/mempolicy.c:mpol_new_preferred
  - mm/mempolicy.c:mpol_new_nodemask
```
```
In mm/memory-tiers.c (ffffffff82233220)
Location: include/linux/nodemask.h:227
Inline: True
Inline callers:
  - mm/memory-tiers.c:memtier_hotplug_callback
  - mm/memory-tiers.c:establish_demotion_targets
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
In arch/arm64/mm/numa.c (ffff800011438e38)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/arm64/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffff8000101e27b8)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffff80001033c2b8)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffff8000103455f8)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
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
In kernel/irq/affinity.c (c03d6710)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (c0424b58)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
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
In kernel/cgroup/cpuset.c (c000000000250f28)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (c0000000004175ac)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (c0000000004234c0)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (c00000000042da80)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In kernel/irq/affinity.c (ffffffe00011d64c)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
```
In kernel/cgroup/cpuset.c (ffffffe00015943c)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/hugetlb.c (ffffffe00022d920)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
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
In arch/x86/mm/numa.c (ffffffff828af1ac)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81166603)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff81295a25)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff8129d1de)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff812a477e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff828a739e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff81159843)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff81287635)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff8128ed6e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff8129624e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff828c20ab)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff811643d3)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff81293835)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff8129afee)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff812a258e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
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
In arch/x86/mm/numa.c (ffffffff828c51f6)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - arch/x86/mm/numa.c:numa_init
```
```
In kernel/cgroup/cpuset.c (ffffffff8117187e)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:validate_change
  - kernel/cgroup/cpuset.c:validate_change
```
```
In mm/mempolicy.c (ffffffff812a3695)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
  - mm/mempolicy.c:numa_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_new_bind
  - mm/mempolicy.c:mpol_new_interleave
```
```
In mm/slub.c (ffffffff812aaece)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In mm/memory_hotplug.c (ffffffff812b28ee)
Location: include/linux/nodemask.h:226
Inline: True
Inline callers:
  - mm/memory_hotplug.c:new_node_page
```
</details>
</li>
</ul>

## Differences
