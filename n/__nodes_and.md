# Function: <code>__nodes_and</code>

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
In kernel/cpuset.c (ffffffff8111b75c)
Location: include/linux/nodemask.h:151
Inline: True
Inline callers:
  - kernel/cpuset.c:guarantee_online_mems
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:cpuset_hotplug_workfn
```
```
In mm/mempolicy.c (ffffffff811e095e)
Location: include/linux/nodemask.h:151
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cpuset.c (ffffffff81125141)
Location: include/linux/nodemask.h:153
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff811ff52c)
Location: include/linux/nodemask.h:153
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
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
In kernel/cpuset.c (ffffffff8112e54f)
Location: include/linux/nodemask.h:153
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_hotplug_workfn
  - kernel/cpuset.c:cpuset_write_resmask
  - kernel/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8120fcf7)
Location: include/linux/nodemask.h:153
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
  - mm/mempolicy.c:mpol_set_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8112fbec)
Location: include/linux/nodemask.h:153
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8121b32f)
Location: include/linux/nodemask.h:153
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8113cd85)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8123654f)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8114b3c1)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8125a266)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81157c6b)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_workfn
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8126e0f6)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811621f3)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff81289703)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8116ded3)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff81299299)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81182c8d)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff812cd410)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8117fbdd)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff812d9c75)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811806bd)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff812e14f1)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811a84ad)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff813287c1)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811d9616)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff81397a16)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8121ea16)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff814175f6)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/memory-tiers.c (ffffffff81436f67)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
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
In kernel/cgroup/cpuset.c (ffffffff81234b06)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff8144ab86)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/memory-tiers.c (ffffffff8146cc27)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
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
In kernel/cgroup/cpuset.c (ffffffff8124e726)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_nodemasks_hier
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
```
In mm/mempolicy.c (ffffffff814845c5)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
```
In mm/memory-tiers.c (ffffffff8149bd77)
Location: include/linux/nodemask.h:164
Inline: True
Inline callers:
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
In kernel/cgroup/cpuset.c (ffff8000101e2700)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffff800010337d24)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (c0424acc)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
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
In arch/powerpc/mm/numa.c (c000000001357770)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:mem_topology_setup
```
```
In kernel/cgroup/cpuset.c (c000000000250e2c)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (c000000000412bc8)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffe0001592c6)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
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
In kernel/cgroup/cpuset.c (ffffffff811664f3)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff81291879)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff81159733)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff812834f9)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff811642c3)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8128f689)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
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
In kernel/cgroup/cpuset.c (ffffffff8117176e)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
  - kernel/cgroup/cpuset.c:guarantee_online_mems
```
```
In mm/mempolicy.c (ffffffff8129faf3)
Location: include/linux/nodemask.h:163
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:mpol_rebind_nodemask
```
</details>
</li>
</ul>

## Differences
