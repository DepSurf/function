# Function: <code>kprobe_disabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kprobes.h:139
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:139
Inline: True
```
```
In kernel/kprobes.c (ffffffff8112d345)
Location: include/linux/kprobes.h:139
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kprobes.h:139
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:139
Inline: True
```
```
In kernel/kprobes.c (ffffffff81135505)
Location: include/linux/kprobes.h:139
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kprobes.h:139
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:139
Inline: True
```
```
In kernel/kprobes.c (ffffffff8113f285)
Location: include/linux/kprobes.h:139
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kprobes.h:140
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:140
Inline: True
```
```
In kernel/kprobes.c (ffffffff81140813)
Location: include/linux/kprobes.h:140
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/kprobes.h:140
Inline: True
```
```
In arch/x86/kernel/kprobes/ftrace.c (0)
Location: include/linux/kprobes.h:140
Inline: True
```
```
In kernel/kprobes.c (ffffffff8114d6b3)
Location: include/linux/kprobes.h:140
Inline: True
Inline callers:
  - kernel/kprobes.c:report_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810691b7)
Location: include/linux/kprobes.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81069355)
Location: include/linux/kprobes.h:140
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8115d99a)
Location: include/linux/kprobes.h:140
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106ef73)
Location: include/linux/kprobes.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8106f0f5)
Location: include/linux/kprobes.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8116a5ba)
Location: include/linux/kprobes.h:133
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073024)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810731d5)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff81177318)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074010)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81074195)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8118323e)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107b12f)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b2b5)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff811970a6)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:arm_all_kprobes
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:unoptimize_all_kprobes
  - kernel/kprobes.c:do_free_cleaned_kprobes
  - kernel/kprobes.c:do_unoptimize_kprobes
  - kernel/kprobes.c:do_unoptimize_kprobes
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107af3f)
Location: include/linux/kprobes.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107b1ae)
Location: include/linux/kprobes.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff81194226)
Location: include/linux/kprobes.h:122
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:arm_all_kprobes
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:unoptimize_all_kprobes
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:do_free_cleaned_kprobes
  - kernel/kprobes.c:do_unoptimize_kprobes
  - kernel/kprobes.c:do_unoptimize_kprobes
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107c119)
Location: include/linux/kprobes.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8107c3b7)
Location: include/linux/kprobes.h:122
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8119521b)
Location: include/linux/kprobes.h:122
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8108a283)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8108a4e7)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff811be102)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8109a78e)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff8109aa53)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff811f1645)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b11fb)
Location: include/linux/kprobes.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b1493)
Location: include/linux/kprobes.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff81238092)
Location: include/linux/kprobes.h:115
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b41ab)
Location: include/linux/kprobes.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810b4455)
Location: include/linux/kprobes.h:115
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8124f172)
Location: include/linux/kprobes.h:115
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bb60b)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810bb8b5)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff812690a2)
Location: include/linux/kprobes.h:114
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:optimize_all_kprobes
  - kernel/kprobes.c:optimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f8254)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/probes/kprobes/opt-arm.c (c0ea1358)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/arm/probes/kprobes/opt-arm.c:arch_optimize_kprobes
```
```
In kernel/kprobes.c (c0438a34)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/optprobes.c (c0000000000575d0)
Location: include/linux/kprobes.h:120
Inline: True
```
```
In arch/powerpc/kernel/kprobes-ftrace.c (c000000000068148)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/powerpc/kernel/kprobes-ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (c00000000026f940)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073010)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81073195)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8117b85e)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81063090)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81063215)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8116e9fe)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072fc0)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff81073145)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff8117962e)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81075020)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:arch_optimize_kprobes
  - arch/x86/kernel/kprobes/opt.c:arch_check_optimized_kprobe
```
```
In arch/x86/kernel/kprobes/ftrace.c (ffffffff810751a5)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/ftrace.c:kprobe_ftrace_handler
```
```
In kernel/kprobes.c (ffffffff81186f3e)
Location: include/linux/kprobes.h:120
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:report_probe
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:__unregister_kprobe_top
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:aggr_post_handler
  - kernel/kprobes.c:aggr_pre_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:proc_kprobes_optimization_handler
  - kernel/kprobes.c:force_unoptimize_kprobe
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:kprobe_optimizer
  - kernel/kprobes.c:opt_pre_handler
```
</details>
</li>
</ul>

## Differences
