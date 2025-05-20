# Function: <code>printk_deferred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118bd88)
Location: kernel/printk/printk.c:2751
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff8118bd88-ffffffff8118be26: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119ead5)
Location: kernel/printk/printk.c:2893
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/printk/nmi.c:printk_nmi_flush_line
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff8119ead5-ffffffff8119eb73: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811ae538)
Location: kernel/printk/printk.c:2725
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - arch/x86/kernel/unwind_frame.c:unwind_next_frame
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/printk/nmi.c:printk_nmi_flush_line
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
**Symbols:**

```
ffffffff811ae538-ffffffff811ae5d6: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4b15)
Location: kernel/printk/printk.c:2737
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/timekeeping_debug.c:tk_debug_account_sleep_time
```
**Symbols:**

```
ffffffff810e4b15-ffffffff810e4b83: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ecdb4)
Location: kernel/printk/printk.c:2731
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff810ecdb4-ffffffff810ece22: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f50a6)
Location: kernel/printk/printk.c:2908
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
**Symbols:**

```
ffffffff810f50a6-ffffffff810f5115: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81100861)
Location: kernel/printk/printk.c:2920
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
**Symbols:**

```
ffffffff81100861-ffffffff811008d0: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81109042)
Location: kernel/printk/printk.c:2985
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff81109042-ffffffff811090b1: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81115424)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff81115424-ffffffff81115493: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81120de0)
Location: kernel/printk/printk.c:3063
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_flags_change
  - kernel/sched/psi.c:psi_group_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush_line
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81120de0-ffffffff81120e4f: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81be13ec)
Location: kernel/printk/printk.c:3142
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_flags_change
  - kernel/sched/psi.c:psi_group_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush_line
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81be13ec-ffffffff81be145b: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81bd3470)
Location: kernel/printk/printk.c:3206
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/i8259.c:mask_and_ack_8259A
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_flags_change
  - kernel/sched/psi.c:psi_group_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:printk_safe_flush_line
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81bd3470-ffffffff81bd34df: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff8000101768a8)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
**Symbols:**

```
ffff8000101768a8-ffff800010176934: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c872c)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
**Symbols:**

```
c03c872c-c03c8790: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001d00c8)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
```
**Symbols:**

```
c0000000001d00c8-c0000000001d0118: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe000111b28)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/timekeeping.c:timekeeping_resume
```
**Symbols:**

```
ffffffe000111b28-ffffffe000111b6c: printk_deferred (STB_GLOBAL)
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
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110da04)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff8110da04-ffffffff8110da73: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe764)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff810fe764-ffffffff810fe7d3: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b8f4)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff8110b8f4-ffffffff8110b963: printk_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int printk_deferred(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116e0a)
Location: kernel/printk/printk.c:2995
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:get_stack_info
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - arch/x86/kernel/unwind_frame.c:unwind_dump
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/rt.c:update_curr_rt
  - kernel/sched/deadline.c:replenish_dl_entity
  - kernel/sched/psi.c:psi_task_change
  - kernel/sched/psi.c:psi_task_change
  - kernel/power/main.c:__pm_pr_dbg
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/printk/printk_safe.c:__printk_safe_flush
  - kernel/time/clockevents.c:clockevents_program_min_delta
  - kernel/time/clockevents.c:clockevents_program_min_delta
```
**Symbols:**

```
ffffffff81116e0a-ffffffff81116e79: printk_deferred (STB_GLOBAL)
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
