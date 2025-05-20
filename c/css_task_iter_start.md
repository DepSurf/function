# Function: <code>css_task_iter_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81118930)
Location: kernel/cgroup.c:4074
Inline: False
Direct callers:
  - kernel/cgroup.c:pidlist_array_load
  - kernel/cgroup.c:cgroup_transfer_tasks
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
ffffffff81118930-ffffffff81118a03: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81120460)
Location: kernel/cgroup.c:4263
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
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
ffffffff81120460-ffffffff81120540: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81128950)
Location: kernel/cgroup.c:4274
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_pidlist_start
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
ffffffff81128950-ffffffff81128a30: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81127ed0)
Location: kernel/cgroup/cgroup.c:3761
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_start
  - kernel/cgroup/cgroup.c:cgroup_procs_start
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
ffffffff81127ed0-ffffffff81127f89: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811343f0)
Location: kernel/cgroup/cgroup.c:4175
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
ffffffff811343f0-ffffffff811344b8: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81142b20)
Location: kernel/cgroup/cgroup.c:4212
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
ffffffff81142b20-ffffffff81142be0: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e650)
Location: kernel/cgroup/cgroup.c:4281
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
ffffffff8114e650-ffffffff8114e710: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a180)
Location: kernel/cgroup/cgroup.c:4567
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
ffffffff8115a180-ffffffff8115a243: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165e20)
Location: kernel/cgroup/cgroup.c:4578
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
ffffffff81165e20-ffffffff81165ee3: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81176f60)
Location: kernel/cgroup/cgroup.c:4515
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
ffffffff81176f60-ffffffff8117700c: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173c40)
Location: kernel/cgroup/cgroup.c:4516
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
ffffffff81173c40-ffffffff81173cf0: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174810)
Location: kernel/cgroup/cgroup.c:4529
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
ffffffff81174810-ffffffff811748bc: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119b8b0)
Location: kernel/cgroup/cgroup.c:4704
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
ffffffff8119b8b0-ffffffff8119b983: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cbb00)
Location: kernel/cgroup/cgroup.c:4715
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
ffffffff811cbb00-ffffffff811cbbd7: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120efb0)
Location: kernel/cgroup/cgroup.c:4912
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
ffffffff8120efb0-ffffffff8120f07c: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff812249c0)
Location: kernel/cgroup/cgroup.c:4889
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff812249c0-ffffffff81224a8c: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123c6a0)
Location: kernel/cgroup/cgroup.c:4919
Inline: False
Direct callers:
  - kernel/sched/core.c:uclamp_update_active_tasks
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
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
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
  - kernel/bpf/task_iter.c:bpf_iter_css_task_new
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
ffffffff8123c6a0-ffffffff8123c776: css_task_iter_start (STB_GLOBAL)
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
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d79b0)
Location: kernel/cgroup/cgroup.c:4578
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
ffff8000101d79b0-ffff8000101d7a80: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a69c)
Location: kernel/cgroup/cgroup.c:4578
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_util_update_eff
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
  - kernel/cgroup/cgroup-v1.c:cgroupstats_build
  - kernel/cgroup/cgroup-v1.c:cgroup_pidlist_start
  - kernel/cgroup/cgroup-v1.c:cgroup_transfer_tasks
  - kernel/cgroup/freezer.c:cgroup_freeze
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/cgroup/cpuset.c:update_flag
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - net/core/netclassid_cgroup.c:write_classid
```
**Symbols:**

```
c041a69c-c041a788: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002446e0)
Location: kernel/cgroup/cgroup.c:4578
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
c0000000002446e0-c000000000244828: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150a70)
Location: kernel/cgroup/cgroup.c:4578
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
ffffffe000150a70-ffffffe000150b4c: css_task_iter_start (STB_GLOBAL)
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
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e440)
Location: kernel/cgroup/cgroup.c:4578
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
ffffffff8115e440-ffffffff8115e503: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151710)
Location: kernel/cgroup/cgroup.c:4578
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
ffffffff81151710-ffffffff811517cd: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c210)
Location: kernel/cgroup/cgroup.c:4578
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
ffffffff8115c210-ffffffff8115c2d3: css_task_iter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void css_task_iter_start(struct cgroup_subsys_state *css, unsigned int flags, struct css_task_iter *it);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81169350)
Location: kernel/cgroup/cgroup.c:4578
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
ffffffff81169350-ffffffff8116940a: css_task_iter_start (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>css, it</code> ➡️ <code>css, flags, it</code>
</li>
</ul>
</details>
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
