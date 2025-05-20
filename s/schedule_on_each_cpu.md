# Function: <code>schedule_on_each_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b410)
Location: kernel/workqueue.c:2938
Inline: False
Direct callers:
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff8109b410-ffffffff8109b50c: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ea00)
Location: kernel/workqueue.c:3038
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff8109ea00-ffffffff8109eafd: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3750)
Location: kernel/workqueue.c:3064
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810a3750-ffffffff810a3854: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0a10)
Location: kernel/workqueue.c:3063
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810a0a10-ffffffff810a0b0e: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a72a0)
Location: kernel/workqueue.c:3077
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810a72a0-ffffffff810a7386: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ade40)
Location: kernel/workqueue.c:3151
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810ade40-ffffffff810adf28: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b6f50)
Location: kernel/workqueue.c:3174
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810b6f50-ffffffff810b7038: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd9d0)
Location: kernel/workqueue.c:3274
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810bd9d0-ffffffff810bdabf: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3060)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810c3060-ffffffff810c314f: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810caad0)
Location: kernel/workqueue.c:3280
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810caad0-ffffffff810cabbd: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5c00)
Location: kernel/workqueue.c:3286
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810c5c00-ffffffff810c5ced: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7530)
Location: kernel/workqueue.c:3287
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810c7530-ffffffff810c7630: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da250)
Location: kernel/workqueue.c:3326
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810da250-ffffffff810da38b: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f3960)
Location: kernel/workqueue.c:3309
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810f3960-ffffffff810f3a9e: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81115af0)
Location: kernel/workqueue.c:3316
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff81115af0-ffffffff81115c49: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81122850)
Location: kernel/workqueue.c:3632
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_init
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff81122850-ffffffff811229a9: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112c820)
Location: kernel/workqueue.c:3653
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/rcu/update.c:rcu_tasks_rude_wait_gp
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - mm/util.c:overcommit_policy_handler
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff8112c820-ffffffff8112c979: schedule_on_each_cpu (STB_GLOBAL)
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
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010120df0)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
```
**Symbols:**

```
ffff800010120df0-ffff800010120f08: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0374d54)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
```
**Symbols:**

```
c0374d54-c0374e60: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016a250)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
```
**Symbols:**

```
c00000000016a250-c00000000016a3d4: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d9d5a)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
```
**Symbols:**

```
ffffffe0000d9d5a-ffffffe0000d9e88: schedule_on_each_cpu (STB_GLOBAL)
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
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd3d0)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810bd3d0-ffffffff810bd4bf: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810abc00)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810abc00-ffffffff810abcef: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc930)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810bc930-ffffffff810bca1f: schedule_on_each_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int schedule_on_each_cpu(work_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4cb0)
Location: kernel/workqueue.c:3283
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_time.c:uv_rtc_setup_clock
  - kernel/livepatch/transition.c:klp_reverse_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/livepatch/transition.c:klp_complete_transition
  - kernel/trace/ftrace.c:ftrace_graph_release
  - mm/vmstat.c:vmstat_refresh
  - drivers/clocksource/numachip.c:numachip_timer_init
```
**Symbols:**

```
ffffffff810c4cb0-ffffffff810c4d9f: schedule_on_each_cpu (STB_GLOBAL)
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
