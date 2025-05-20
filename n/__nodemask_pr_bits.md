# Function: <code>__nodemask_pr_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:113
Inline: True
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
In kernel/cgroup/cpuset.c (ffffffff8114c1e5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff811f3936)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff811fada4)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8125da13)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff81269341)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff8169c565)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81158e15)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81205a45)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff8120d654)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff812722a3)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff81278d59)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff816bcef5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81165565)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff8121d17a)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff81273b0b)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8128d8ea)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff81294e50)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff816f7725)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81171455)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff8122ab57)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff81282942)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8129d5aa)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff812a4c33)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff8171bb85)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81183165)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81257915)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff812b49e4)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff812d11aa)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff812d93dc)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff817d7c25)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81180105)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81be6c1d)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff81be7d04)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff812dccca)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff812e4a3f)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff817ebd89)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81180bd5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81bd89b9)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff81bd9afb)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff812e4526)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff812ec209)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff817d05a9)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff811a89c5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81cba275)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff813073f9)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8132b86b)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff81333548)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In drivers/base/node.c (ffffffff8185ade5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff811d9b85)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81e6b9c3)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff8136f72c)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8139b460)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff813a4d32)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In drivers/base/node.c (ffffffff819a1d34)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff8121f065)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8136413d)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff813ebcec)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8141b4e0)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff81424fef)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memory-tiers.c (ffffffff814369d8)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/memory-tiers.c:nodelist_show
```
```
In drivers/base/node.c (ffffffff81b13c54)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81235195)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff8139660d)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff81420cfc)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8144ea5f)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff8145a39f)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/memory-tiers.c (ffffffff8146c698)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/memory-tiers.c:nodelist_show
```
```
In drivers/base/node.c (ffffffff81b62984)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff8124ede5)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_hotplug_update_tasks
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (ffffffff813c0e4d)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/page_alloc.c (ffffffff8144dabc)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/slub.c (ffffffff8145546f)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/slub.c:slab_debugfs_show
```
```
In mm/mempolicy.c (ffffffff814885ff)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/memory-tiers.c (ffffffff8149b7e8)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - mm/memory-tiers.c:nodelist_show
```
```
In drivers/base/node.c (ffffffff81bb6494)
Location: include/linux/nodemask.h:114
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/mempolicy.c (ffff80001033c370)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:113
Inline: True
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:113
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/mempolicy.c (c0000000004176d0)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:113
Inline: True
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:113
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:113
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
In kernel/cgroup/cpuset.c (ffffffff81169a75)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff812231a7)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff8127af92)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff81295b8a)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff8129d213)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff816e1eb5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff8115cc75)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81216357)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff8126ce72)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8128779a)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff8128eda3)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff816bc4f5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81167845)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff81220f47)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff81278d32)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff8129399a)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff8129b023)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff8170f3e5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff81174f15)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff812300ed)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff81288922)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (ffffffff812a37fa)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_to_str
```
```
In mm/slub.c (ffffffff812aaf03)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff8172a1a5)
Location: include/linux/nodemask.h:113
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
```
</details>
</li>
</ul>

## Differences
