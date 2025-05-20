# Function: <code>__nodemask_pr_numnodes</code>

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
In kernel/cgroup/cpuset.c (ffffffff8113d92e)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffff811d2a3c)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffff811d77c6)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (ffffffff8124522e)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffffffff81660da6)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffff8114c30b)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff81158f35)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff8116536b)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff81171262)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff81182f72)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff8117fee2)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff811809bb)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff811a87ab)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In drivers/base/node.c (ffffffff8185adf4)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff811d9940)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In drivers/base/node.c (ffffffff819a1d43)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff8121edf0)
Location: include/linux/nodemask.h:110
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In drivers/base/node.c (ffffffff81b13c63)
Location: include/linux/nodemask.h:110
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
In kernel/cgroup/cpuset.c (ffffffff81234f20)
Location: include/linux/nodemask.h:110
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In drivers/base/node.c (ffffffff81b62993)
Location: include/linux/nodemask.h:110
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
In kernel/cgroup/cpuset.c (ffffffff8124eb40)
Location: include/linux/nodemask.h:110
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In mm/memory-tiers.c (0)
Location: include/linux/nodemask.h:110
Inline: True
```
```
In drivers/base/node.c (ffffffff81bb64a3)
Location: include/linux/nodemask.h:110
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
In kernel/cgroup/cpuset.c (ffff8000101e4b70)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffff8000102b8edc)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffff800010318040)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (ffff800010345608)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (ffff80001090f644)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (c0425998)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (c04e56e4)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (c0532580)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
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
In kernel/cgroup/cpuset.c (c0000000002553e4)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (c000000000371080)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (c0000000003ea63c)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (c0000000004234e8)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (c0000000009b0500)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
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
In kernel/cgroup/cpuset.c (ffffffe00015ad18)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (ffffffe0001dcb0a)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (ffffffe00021dea0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
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
In kernel/cgroup/cpuset.c (ffffffff81169882)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff8115ca82)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff81167652)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
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
In kernel/cgroup/cpuset.c (ffffffff81174cd7)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_task_status_allowed
  - kernel/cgroup/cpuset.c:cpuset_print_current_mems_allowed
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
  - kernel/cgroup/cpuset.c:cpuset_common_seq_show
```
```
In mm/oom_kill.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
```
```
In mm/page_alloc.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/mempolicy.c (0)
Location: include/linux/nodemask.h:109
Inline: True
```
```
In mm/slub.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - mm/slub.c:list_locations
```
```
In drivers/base/node.c (0)
Location: include/linux/nodemask.h:109
Inline: True
Inline callers:
  - drivers/base/node.c:show_node_state
```
</details>
</li>
</ul>

## Differences
