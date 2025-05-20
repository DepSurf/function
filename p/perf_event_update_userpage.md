# Function: <code>perf_event_update_userpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117fd30)
Location: kernel/events/core.c:4445
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
```
**Symbols:**

```
ffffffff8117fd30-ffffffff8117fe59: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81191aa0)
Location: kernel/events/core.c:4735
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81191aa0-ffffffff81191bd3: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1250)
Location: kernel/events/core.c:4832
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811a1250-ffffffff811a1383: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a8b20)
Location: kernel/events/core.c:4924
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811a8b20-ffffffff811a8c36: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811bc380)
Location: kernel/events/core.c:4874
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811bc380-ffffffff811bc492: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dc530)
Location: kernel/events/core.c:5230
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811dc530-ffffffff811dc64d: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ec930)
Location: kernel/events/core.c:5239
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811ec930-ffffffff811eca4d: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204310)
Location: kernel/events/core.c:5285
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81204310-ffffffff8120442b: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81210f00)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81210f00-ffffffff8121101b: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123cf20)
Location: kernel/events/core.c:5649
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff8123cf20-ffffffff8123d03d: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81247150)
Location: kernel/events/core.c:5728
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff81247150-ffffffff81247272: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124b000)
Location: kernel/events/core.c:5812
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff8124b000-ffffffff8124b120: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812845f0)
Location: kernel/events/core.c:5920
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff812845f0-ffffffff81284710: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d8aa0)
Location: kernel/events/core.c:5818
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff812d8aa0-ffffffff812d8c07: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81341060)
Location: kernel/events/core.c:6036
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
```
**Symbols:**

```
ffffffff81341060-ffffffff813411c7: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81371ff0)
Location: kernel/events/core.c:6036
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - drivers/iommu/intel/perfmon.c:iommu_pmu_del
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
**Symbols:**

```
ffffffff81371ff0-ffffffff81372147: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139b360)
Location: kernel/events/core.c:6109
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - arch/x86/events/intel/core.c:icl_set_topdown_event_period
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:perf_event_context_sched_out
  - kernel/events/core.c:perf_event_context_sched_out
  - drivers/iommu/intel/perfmon.c:iommu_pmu_del
  - drivers/iommu/intel/perfmon.c:iommu_pmu_start
```
**Symbols:**

```
ffffffff8139b360-ffffffff8139b4b7: perf_event_update_userpage (STB_GLOBAL)
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
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029b3e0)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - drivers/perf/arm-cci.c:cci_pmu_del
  - drivers/perf/arm-cci.c:cci_pmu_del
  - drivers/perf/arm-cci.c:cci_pmu_add
  - drivers/perf/arm_pmu.c:armpmu_add
  - drivers/perf/arm_pmu.c:armpmu_del
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_del
  - drivers/perf/hisilicon/hisi_uncore_pmu.c:hisi_uncore_pmu_start
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_del
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_del
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_del
  - drivers/perf/qcom_l2_pmu.c:l2_cache_event_add
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_del
  - drivers/perf/qcom_l3_pmu.c:qcom_l3_cache__event_add
  - drivers/perf/xgene_pmu.c:xgene_perf_del
  - drivers/perf/xgene_pmu.c:xgene_perf_start
```
**Symbols:**

```
ffff80001029b3e0-ffff80001029b4e8: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04ca880)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
  - drivers/perf/arm-cci.c:cci_pmu_del
  - drivers/perf/arm-cci.c:cci_pmu_add
  - drivers/perf/arm_pmu.c:armpmu_add
  - drivers/perf/arm_pmu.c:armpmu_del
  - drivers/perf/arm_pmu.c:armpmu_event_set_period
```
**Symbols:**

```
c04ca880-c04ca9c8: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000034b1a0)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - arch/powerpc/perf/core-book3s.c:record_and_restart
  - arch/powerpc/perf/core-book3s.c:power_pmu_del
  - arch/powerpc/perf/core-book3s.c:power_pmu_enable
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
c00000000034b1a0-c00000000034b31c: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cd9b4)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - arch/riscv/kernel/perf_event.c:riscv_pmu_del
  - arch/riscv/kernel/perf_event.c:riscv_pmu_start
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffe0001cd9b4-ffffffe0001cda74: perf_event_update_userpage (STB_GLOBAL)
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
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209550)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81209550-ffffffff8120966b: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fc300)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff811fc300-ffffffff811fc41b: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812072f0)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff812072f0-ffffffff8120740b: perf_event_update_userpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_event_update_userpage(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81216070)
Location: kernel/events/core.c:5380
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_perf_event_set_period
  - arch/x86/events/amd/uncore.c:amd_uncore_start
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_del
  - arch/x86/events/amd/ibs.c:perf_ibs_start
  - arch/x86/events/amd/iommu.c:perf_iommu_del
  - arch/x86/events/amd/iommu.c:perf_iommu_start
  - arch/x86/events/intel/ds.c:intel_pmu_save_and_restart_reload
  - kernel/events/core.c:task_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:cpu_clock_event_add
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:perf_mmap
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_event_task_sched_out
  - kernel/events/core.c:__perf_event_task_sched_out
```
**Symbols:**

```
ffffffff81216070-ffffffff812161b0: perf_event_update_userpage (STB_GLOBAL)
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
