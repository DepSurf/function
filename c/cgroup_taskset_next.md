# Function: <code>cgroup_taskset_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811160e0)
Location: kernel/cgroup.c:2438
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup.c:cgroup_taskset_first
  - kernel/cgroup_freezer.c:freezer_attach
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
```
**Symbols:**

```
ffffffff811160e0-ffffffff81116184: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111caf0)
Location: kernel/cgroup.c:2479
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup.c:cgroup_taskset_first
  - kernel/cgroup_freezer.c:freezer_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
```
**Symbols:**

```
ffffffff8111caf0-ffffffff8111cb94: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81124e20)
Location: kernel/cgroup.c:2484
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup.c:cgroup_taskset_first
  - kernel/cgroup_freezer.c:freezer_attach
  - kernel/cgroup_pids.c:pids_cancel_attach
  - kernel/cgroup_pids.c:pids_can_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81124e20-ffffffff81124ec4: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124840)
Location: kernel/cgroup/cgroup.c:2044
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81124840-ffffffff811248d6: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811309a0)
Location: kernel/cgroup/cgroup.c:2222
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff811309a0-ffffffff81130a36: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113f070)
Location: kernel/cgroup/cgroup.c:2240
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8113f070-ffffffff8113f106: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114aa90)
Location: kernel/cgroup/cgroup.c:2281
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8114aa90-ffffffff8114ab26: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156210)
Location: kernel/cgroup/cgroup.c:2417
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81156210-ffffffff811562a6: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81161e70)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81161e70-ffffffff81161f06: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811732b0)
Location: kernel/cgroup/cgroup.c:2344
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff811732b0-ffffffff8117334c: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116ffb0)
Location: kernel/cgroup/cgroup.c:2340
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8116ffb0-ffffffff8117004c: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170be0)
Location: kernel/cgroup/cgroup.c:2353
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81170be0-ffffffff81170c79: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81197240)
Location: kernel/cgroup/cgroup.c:2408
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81197240-ffffffff81197345: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c7280)
Location: kernel/cgroup/cgroup.c:2412
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff811c7280-ffffffff811c738e: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120a0e0)
Location: kernel/cgroup/cgroup.c:2514
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8120a0e0-ffffffff8120a1ee: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8121f6c0)
Location: kernel/cgroup/cgroup.c:2483
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8121f6c0-ffffffff8121f7ce: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81237410)
Location: kernel/cgroup/cgroup.c:2492
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
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
ffffffff81237410-ffffffff8123751e: cgroup_taskset_next (STB_GLOBAL)
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
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d3238)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffff8000101d3238-ffff8000101d32f4: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0416014)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
c0416014-c04160b8: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023e3e0)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
c00000000023e3e0-c00000000023e49c: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014ca88)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffe00014ca88-ffffffe00014cb44: cgroup_taskset_next (STB_GLOBAL)
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
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a490)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8115a490-ffffffff8115a526: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d780)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8114d780-ffffffff8114d816: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158260)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81158260-ffffffff811582f6: cgroup_taskset_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *cgroup_taskset_next(struct cgroup_taskset *tset, struct cgroup_subsys_state **dst_cssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811652b0)
Location: kernel/cgroup/cgroup.c:2418
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_attach
  - kernel/sched/core.c:cpu_cgroup_can_attach
  - kernel/cgroup/cgroup.c:cgroup_taskset_first
  - kernel/cgroup/legacy_freezer.c:freezer_attach
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_can_attach
  - kernel/events/core.c:perf_cgroup_attach
  - block/blk-cgroup.c:blkcg_can_attach
  - net/core/netprio_cgroup.c:net_prio_attach
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff811652b0-ffffffff81165346: cgroup_taskset_next (STB_GLOBAL)
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
