# Function: <code>rcu_irq_exit_irqson</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810edde0)
Location: kernel/rcu/tree.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
```
**Symbols:**

```
ffffffff810edde0-ffffffff810ede2b: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4ec0)
Location: kernel/rcu/tree.c:811
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
```
**Symbols:**

```
ffffffff810f4ec0-ffffffff810f4f0b: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5cb0)
Location: kernel/rcu/tree.c:904
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
```
**Symbols:**

```
ffffffff810f5cb0-ffffffff810f5d05: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffb10)
Location: kernel/rcu/tree.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff810ffb10-ffffffff810ffb3d: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81107eb0)
Location: kernel/rcu/tree.c:860
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff81107eb0-ffffffff81107eec: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811133e0)
Location: kernel/rcu/tree.c:745
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:pm_schedule_suspend
  - drivers/base/power/runtime.c:pm_suspend_timer_fn
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:pm_runtime_work
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff811133e0-ffffffff8111340d: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d020)
Location: kernel/rcu/tree.c:706
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff8111d020-ffffffff8111d04d: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129520)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff81129520-ffffffff8112954d: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137d70)
Location: kernel/rcu/tree.c:811
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
  - drivers/cpuidle/cpuidle.c:enter_s2idle_proper
```
**Symbols:**

```
ffffffff81137d70-ffffffff81137da0: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133600)
Location: kernel/rcu/tree.c:877
Inline: False
Direct callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff81133600-ffffffff81133630: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134120)
Location: kernel/rcu/tree.c:882
Inline: False
Direct callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff81134120-ffffffff81134158: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811566b0)
Location: kernel/rcu/tree.c:835
Inline: False
Direct callers:
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff811566b0-ffffffff811566e8: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117f6b0)
Location: kernel/rcu/tree.c:842
Inline: False
Direct callers:
  - kernel/printk/printk.c:printk_sprint
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:update_autosuspend
  - drivers/base/power/runtime.c:pm_runtime_allow
  - drivers/base/power/runtime.c:pm_runtime_get_if_active
  - drivers/base/power/runtime.c:__pm_runtime_suspend
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffff8117f6b0-ffffffff8117f6e5: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
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
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010190aa8)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - kernel/cpu_pm.c:cpu_pm_notify
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffff800010190aa8-ffff800010190aec: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03de69c)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_reschedule
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:tick_broadcast
  - arch/arm/kernel/smp.c:arch_irq_work_raise
  - arch/arm/kernel/smp.c:arch_send_call_function_single_ipi
  - arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask
  - arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - kernel/cpu_pm.c:cpu_pm_notify
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/perf/arm_pmu.c:cpu_pm_pmu_setup
```
**Symbols:**

```
c03de69c-c03de6c4: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ebef0)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
c0000000001ebef0-c0000000001ebf3c: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000124056)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
**Symbols:**

```
ffffffe000124056-ffffffe000124088: rcu_irq_exit_irqson (STB_GLOBAL)
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
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81121b00)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff81121b00-ffffffff81121b2d: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114180)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff81114180-ffffffff81114197: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f9f0)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/printk/printk.c:console_unlock
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff8111f9f0-ffffffff8111fa1d: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_irq_exit_irqson();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112bb60)
Location: kernel/rcu/tree.c:714
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace.c:__trace_stack
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle
```
**Symbols:**

```
ffffffff8112bb60-ffffffff8112bb8d: rcu_irq_exit_irqson (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
