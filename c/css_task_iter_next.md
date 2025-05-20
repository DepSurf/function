# Function: <code>css_task_iter_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81118a10)
Location: kernel/cgroup.c:4106
Inline: False
Direct callers:
  - kernel/cgroup.c:pidlist_array_load
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:update_tasks_cpumask
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:update_flag
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - net/core/netclassid_cgroup.c:update_classid
```
**Symbols:**

```
ffffffff81118a10-ffffffff81118a85: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81120540)
Location: kernel/cgroup.c:4295
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - net/core/netclassid_cgroup.c:update_classid
```
**Symbols:**

```
ffffffff81120540-ffffffff811205b6: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81128a30)
Location: kernel/cgroup.c:4306
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81128a30-ffffffff81128aa6: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81127f90)
Location: kernel/cgroup/cgroup.c:3793
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_start
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81127f90-ffffffff81128006: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811344c0)
Location: kernel/cgroup/cgroup.c:4208
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811344c0-ffffffff81134536: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81142be0)
Location: kernel/cgroup/cgroup.c:4245
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81142be0-ffffffff81142c56: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e710)
Location: kernel/cgroup/cgroup.c:4314
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8114e710-ffffffff8114e786: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a250)
Location: kernel/cgroup/cgroup.c:4600
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115a250-ffffffff8115a2e2: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165ef0)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81165ef0-ffffffff81165f82: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177010)
Location: kernel/cgroup/cgroup.c:4545
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81177010-ffffffff811770f7: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173cf0)
Location: kernel/cgroup/cgroup.c:4546
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81173cf0-ffffffff81173dd7: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811748c0)
Location: kernel/cgroup/cgroup.c:4559
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811748c0-ffffffff811749a7: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119b990)
Location: kernel/cgroup/cgroup.c:4734
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8119b990-ffffffff8119ba77: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cbbe0)
Location: kernel/cgroup/cgroup.c:4745
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811cbbe0-ffffffff811cbcc8: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120f090)
Location: kernel/cgroup/cgroup.c:4942
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8120f090-ffffffff8120f178: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81224aa0)
Location: kernel/cgroup/cgroup.c:4919
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81224aa0-ffffffff81224b88: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123c790)
Location: kernel/cgroup/cgroup.c:4951
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
  - kernel/bpf/task_iter.c:bpf_iter_css_task_next
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8123c790-ffffffff8123c87f: css_task_iter_next (STB_GLOBAL)
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
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7a80)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffff8000101d7a80-ffff8000101d7b80: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a788)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
c041a788-c041a848: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000244830)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
c000000000244830-c000000000244960: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150b4c)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffe000150b4c-ffffffe000150c24: css_task_iter_next (STB_GLOBAL)
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
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e510)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115e510-ffffffff8115e5a2: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811517d0)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811517d0-ffffffff8115185c: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c2e0)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115c2e0-ffffffff8115c372: css_task_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *css_task_iter_next(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81169410)
Location: kernel/cgroup/cgroup.c:4611
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81169410-ffffffff81169499: css_task_iter_next (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
