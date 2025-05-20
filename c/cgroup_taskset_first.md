# Function: <code>cgroup_taskset_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81116190)
Location: kernel/cgroup.c:2421
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup_freezer.c:freezer_attach
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cpuset.c:cpuset_cancel_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_can_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81116190-ffffffff811161b9: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111cba0)
Location: kernel/cgroup.c:2462
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup_freezer.c:freezer_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_cancel_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8111cba0-ffffffff8111cbc9: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124ed0)
Location: kernel/cgroup.c:2467
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup_freezer.c:freezer_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_cancel_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81124ed0-ffffffff81124ef9: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811248e0)
Location: kernel/cgroup/cgroup.c:2027
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff811248e0-ffffffff81124909: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81130a40)
Location: kernel/cgroup/cgroup.c:2205
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81130a40-ffffffff81130a69: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113f110)
Location: kernel/cgroup/cgroup.c:2223
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8113f110-ffffffff8113f139: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114ab30)
Location: kernel/cgroup/cgroup.c:2264
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8114ab30-ffffffff8114ab59: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811562b0)
Location: kernel/cgroup/cgroup.c:2400
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff811562b0-ffffffff811562d9: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161f10)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81161f10-ffffffff81161f39: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173350)
Location: kernel/cgroup/cgroup.c:2327
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81173350-ffffffff81173379: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170050)
Location: kernel/cgroup/cgroup.c:2323
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81170050-ffffffff81170079: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170c80)
Location: kernel/cgroup/cgroup.c:2336
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81170c80-ffffffff81170ca9: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81197350)
Location: kernel/cgroup/cgroup.c:2391
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81197350-ffffffff81197379: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c7390)
Location: kernel/cgroup/cgroup.c:2395
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff811c7390-ffffffff811c73c1: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120a200)
Location: kernel/cgroup/cgroup.c:2497
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8120a200-ffffffff8120a231: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121f7e0)
Location: kernel/cgroup/cgroup.c:2466
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8121f7e0-ffffffff8121f811: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81237530)
Location: kernel/cgroup/cgroup.c:2475
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81237530-ffffffff81237561: cgroup_taskset_first (STB_GLOBAL)
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
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d32f8)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffff8000101d32f8-ffff8000101d333c: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04160b8)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
c04160b8-c04160ec: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023e4a0)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
c00000000023e4a0-c00000000023e4cc: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014cb44)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffe00014cb44-ffffffe00014cb84: cgroup_taskset_first (STB_GLOBAL)
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
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a530)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8115a530-ffffffff8115a559: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d820)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8114d820-ffffffff8114d849: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158300)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81158300-ffffffff81158329: cgroup_taskset_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_first(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165350)
Location: kernel/cgroup/cgroup.c:2401
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_cancel_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81165350-ffffffff81165379: cgroup_taskset_first (STB_GLOBAL)
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
