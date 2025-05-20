# Function: <code>unregister_ftrace_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81144870)
Location: kernel/trace/ftrace.c:5577
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_disable_func
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81144870-ffffffff811448a1: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114bcd0)
Location: kernel/trace/ftrace.c:5611
Inline: False
Direct callers:
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8114bcd0-ffffffff8114bd01: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81155bd0)
Location: kernel/trace/ftrace.c:5660
Inline: False
Direct callers:
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81155bd0-ffffffff81155c01: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811585b0)
Location: kernel/trace/ftrace.c:6440
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811585b0-ffffffff811585e1: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811650a0)
Location: kernel/trace/ftrace.c:6739
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811650a0-ffffffff811650d1: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81173d80)
Location: kernel/trace/ftrace.c:6725
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81173d80-ffffffff81173db1: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811819d0)
Location: kernel/trace/ftrace.c:6664
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_object
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811819d0-ffffffff81181a01: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118e770)
Location: kernel/trace/ftrace.c:6718
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/kprobes.c:disarm_kprobe
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8118e770-ffffffff8118e7a5: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119a6f0)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8119a6f0-ffffffff8119a725: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b37f3)
Location: kernel/trace/ftrace.c:7393
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/kprobes.c:__disarm_kprobe_ftrace
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811b0400-ffffffff811b045a: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b13c3)
Location: kernel/trace/ftrace.c:7563
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/kprobes.c:__disarm_kprobe_ftrace
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811ade80-ffffffff811adeda: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1f03)
Location: kernel/trace/ftrace.c:7568
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/kprobes.c:__disarm_kprobe_ftrace
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811ae850-ffffffff811ae8aa: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811dbe33)
Location: kernel/trace/ftrace.c:7571
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/kprobes.c:__disarm_kprobe_ftrace
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff811d8670-ffffffff811d86ca: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812121e8)
Location: kernel/trace/ftrace.c:8011
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi
  - kernel/trace/ftrace.c:unregister_ftrace_direct_multi
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/kprobes.c:__disarm_kprobe_ftrace
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/fprobe.c:unregister_fprobe
```
**Symbols:**

```
ffffffff8120df50-ffffffff8120dfac: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:8263
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_func
  - kernel/kprobes.c:disarm_kprobe_ftrace
  - kernel/trace/ftrace.c:unregister_ftrace_direct_multi
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
  - kernel/trace/fprobe.c:unregister_fprobe
```
**Symbols:**

```
ffffffff8205ce1f-ffffffff8205ce40: unregister_ftrace_function.cold (STB_LOCAL)
ffffffff81256fb0-ffffffff81257114: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:8078
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/kprobes.c:disarm_kprobe_ftrace
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff820db7ab-ffffffff820db7cc: unregister_ftrace_function.cold (STB_LOCAL)
ffffffff8126e4a0-ffffffff8126e604: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:8078
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/kprobes.c:disarm_kprobe_ftrace
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/trace_functions.c:func_set_flag
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_reset
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff821b74b6-ffffffff821b74d7: unregister_ftrace_function.cold (STB_LOCAL)
ffffffff81288980-ffffffff81288ae4: unregister_ftrace_function (STB_GLOBAL)
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
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010213420)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffff800010213420-ffff800010213468: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0452218)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
c0452218-c0452258: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000293780)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
c000000000293780-c0000000002937ec: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001736b8)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffe0001736b8-ffffffe0001736fe: unregister_ftrace_function (STB_GLOBAL)
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
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81192d10)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81192d10-ffffffff81192d45: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81185e20)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81185e20-ffffffff81185e55: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190ae0)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff81190ae0-ffffffff81190b15: unregister_ftrace_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_ftrace_function(struct ftrace_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119e670)
Location: kernel/trace/ftrace.c:6753
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/trace/trace_functions.c:function_trace_reset
  - kernel/trace/trace_stack.c:stack_trace_sysctl
  - kernel/trace/trace_event_perf.c:perf_ftrace_event_register
```
**Symbols:**

```
ffffffff8119e670-ffffffff8119e6a5: unregister_ftrace_function (STB_GLOBAL)
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
