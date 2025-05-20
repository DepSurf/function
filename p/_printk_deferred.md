# Function: <code>_printk_deferred</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81cac616)
Location: kernel/printk/printk.c:3270
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_flags_change
  - kernel/sched/psi.c:psi_group_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81cac616-ffffffff81cac685: _printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81e5cb71)
Location: kernel/printk/printk.c:3526
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - lib/ratelimit.c:___ratelimit
```
**Symbols:**

```
ffffffff81e5cb71-ffffffff81e5cc05: _printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3789
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - kernel/trace/rv/reactor_printk.c:rv_printk_reaction
  - lib/ratelimit.c:___ratelimit
```
**Symbols:**

```
ffffffff82058bea-ffffffff82058bff: _printk_deferred.cold (STB_LOCAL)
ffffffff811926a0-ffffffff81192765: _printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:3830
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/workqueue.c:wq_cpu_intensive_report
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - kernel/trace/rv/reactor_printk.c:rv_printk_reaction
  - lib/ratelimit.c:___ratelimit
```
**Symbols:**

```
ffffffff820d7482-ffffffff820d7497: _printk_deferred.cold (STB_LOCAL)
ffffffff811a3f40-ffffffff811a4005: _printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b35c0)
Location: kernel/printk/printk.c:3948
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
  - arch/x86/kernel/cpu/mce/threshold.c:mce_track_storm
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/workqueue.c:wq_cpu_intensive_report
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:replenish_dl_entity
  - kernel/sched/build_policy.c:enqueue_task_rt
  - kernel/sched/build_policy.c:update_curr_rt
  - kernel/sched/build_utility.c:psi_flags_change
  - kernel/sched/build_utility.c:psi_group_change
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
  - kernel/trace/rv/reactor_printk.c:rv_printk_reaction
  - lib/ratelimit.c:___ratelimit
```
**Symbols:**

```
ffffffff811b35c0-ffffffff811b3655: _printk_deferred (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
