# Function: <code>css_task_iter_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81118a90)
Location: kernel/cgroup.c:4133
Inline: False
Direct callers:
  - kernel/cgroup.c:pidlist_array_load
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:update_tasks_cpumask
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:update_flag
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - net/core/netclassid_cgroup.c:update_classid
```
**Symbols:**

```
ffffffff81118a90-ffffffff81118b0a: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811205c0)
Location: kernel/cgroup.c:4322
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - net/core/netclassid_cgroup.c:update_classid
```
**Symbols:**

```
ffffffff811205c0-ffffffff81120643: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81128ab0)
Location: kernel/cgroup.c:4333
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
  - kernel/cgroup.c:cgroupstats_build
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup.c:cgroup_transfer_tasks
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_apply_state
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/cpuset.c:update_flag
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81128ab0-ffffffff81128b33: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128040)
Location: kernel/cgroup/cgroup.c:3820
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_apply_state
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81128040-ffffffff811280bf: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81134560)
Location: kernel/cgroup/cgroup.c:4235
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81134560-ffffffff8113462a: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81142c80)
Location: kernel/cgroup/cgroup.c:4272
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81142c80-ffffffff81142d4a: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e7b0)
Location: kernel/cgroup/cgroup.c:4341
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:unfreeze_cgroup
  - kernel/cgroup/freezer.c:freeze_cgroup
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8114e7b0-ffffffff8114e87a: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a310)
Location: kernel/cgroup/cgroup.c:4631
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115a310-ffffffff8115a3de: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165fc0)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81165fc0-ffffffff8116608e: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81177130)
Location: kernel/cgroup/cgroup.c:4576
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81177130-ffffffff81177218: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173e10)
Location: kernel/cgroup/cgroup.c:4577
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81173e10-ffffffff81173ef8: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811749e0)
Location: kernel/cgroup/cgroup.c:4590
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811749e0-ffffffff81174ac8: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119bab0)
Location: kernel/cgroup/cgroup.c:4765
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8119bab0-ffffffff8119bb98: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cbd00)
Location: kernel/cgroup/cgroup.c:4776
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811cbd00-ffffffff811cbdf7: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120f1d0)
Location: kernel/cgroup/cgroup.c:4973
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
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
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8120f1d0-ffffffff8120f2c7: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81224be0)
Location: kernel/cgroup/cgroup.c:4950
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81224be0-ffffffff81224cd7: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123c8d0)
Location: kernel/cgroup/cgroup.c:4984
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup.c:__cgroup_kill
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
  - kernel/bpf/task_iter.c:bpf_iter_css_task_destroy
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8123c8d0-ffffffff8123c9cd: css_task_iter_end (STB_GLOBAL)
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
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7bc8)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffff8000101d7bc8-ffff8000101d7d28: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a88c)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
c041a88c-c041a96c: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000244990)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
c000000000244990-c000000000244b30: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150c60)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffe000150c60-ffffffe000150dae: css_task_iter_end (STB_GLOBAL)
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
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e5e0)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115e5e0-ffffffff8115e6ae: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151890)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff81151890-ffffffff81151958: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c3b0)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8115c3b0-ffffffff8115c47e: css_task_iter_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void css_task_iter_end(struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811694d0)
Location: kernel/cgroup/cgroup.c:4642
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:cgroup_procs_release
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_do_freeze
  - kernel/cgroup/legacy_freezer.c:unfreeze_cgroup
  - kernel/cgroup/legacy_freezer.c:freeze_cgroup
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/cgroup/cpuset.c:update_tasks_flags
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff811694d0-ffffffff81169595: css_task_iter_end (STB_GLOBAL)
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
