# Function: <code>srcu_read_lock_notrace</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81a2ca78)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff81083ec9)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81a2ccf5)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffff810fe3fb)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffffffff815f9ccc)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff816b0323)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
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
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818595b2)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81a9cbe1)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff81087b87)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81a9ce58)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffff81106b1c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffffffff8162c07c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff816e90f3)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8189ce3f)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81ad4431)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff81088847)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81ad46a8)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffff81112eac)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffffffff8164d62c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff8170d153)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818cf21d)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81bcc526)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff8108af46)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81bcc713)
Location: include/linux/srcu.h:161
Inline: True
```
```
In kernel/printk/printk.c (ffffffff8111dfb0)
Location: include/linux/srcu.h:161
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816ffe5c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff817c9235)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
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
```
In drivers/cpuidle/cpuidle.c (ffffffff819a190c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/printk/printk.c (ffffffff811188a1)
Location: include/linux/srcu.h:161
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8171d1a6)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff817ddb62)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81118f31)
Location: include/linux/srcu.h:164
Inline: True
```
```
In drivers/clk/clk.c (ffffffff816fdfd6)
Location: include/linux/srcu.h:164
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff817c1ee2)
Location: include/linux/srcu.h:164
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff81139de1)
Location: include/linux/srcu.h:170
Inline: True
```
```
In drivers/clk/clk.c (ffffffff81777903)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff8184bd8f)
Location: include/linux/srcu.h:170
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff8115e61b)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_sprint
```
```
In drivers/clk/clk.c (ffffffff818ade85)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff819916e7)
Location: include/linux/srcu.h:171
Inline: True
Inline callers:
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
In kernel/printk/printk.c (ffffffff8119154b)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - kernel/printk/printk.c:printk_sprint
```
```
In drivers/clk/clk.c (ffffffff819f96f5)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff81b01ab7)
Location: include/linux/srcu.h:208
Inline: True
Inline callers:
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
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/process.c (ffff800010088ebc)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/arm64/kernel/process.c:arch_cpu_idle
  - arch/arm64/kernel/process.c:arch_cpu_idle
```
```
In arch/arm64/kernel/smp.c (ffff80001009cc0c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/arm64/kernel/smp.c:handle_IPI
  - arch/arm64/kernel/smp.c:handle_IPI
```
```
In kernel/sched/idle.c (ffff800010da7248)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffff800010174314)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffff8000107c110c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffff8000108fc4f4)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (ffff800010b26f98)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/arm/kernel/smp.c (c0313a04)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:smp_send_stop
  - arch/arm/kernel/smp.c:smp_send_reschedule
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:handle_IPI
  - arch/arm/kernel/smp.c:tick_broadcast
  - arch/arm/kernel/smp.c:arch_irq_work_raise
  - arch/arm/kernel/smp.c:arch_send_call_function_single_ipi
  - arch/arm/kernel/smp.c:arch_send_wakeup_ipi_mask
  - arch/arm/kernel/smp.c:arch_send_call_function_ipi_mask
```
```
In arch/arm/mach-omap2/pm34xx.c (c033d750)
Location: include/linux/srcu.h:161
Inline: True
```
```
In arch/arm/mach-omap2/powerdomain.c (c034524c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/arm/mach-omap2/powerdomain.c:pwrdm_set_next_pwrst
  - arch/arm/mach-omap2/powerdomain.c:_pwrdm_state_switch
```
```
In kernel/sched/idle.c (c0e9ee94)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (c03c65bc)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (c08eaef4)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
```
```
In drivers/base/power/runtime.c (c09e6b30)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (c0c01e8c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In kernel/sched/idle.c (c000000000ee9b0c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (c0000000001cd110)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/base/power/runtime.c (c000000000998df4)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (c000000000c1e154)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0008c92a4)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffe00010f768)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffffffe00050b592)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffe00058b72a)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
</details>
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
In arch/x86/kernel/process.c (ffffffff81a732a1)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff81087847)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81a73518)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffff8110b48c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffffffff8161368c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff816d28a3)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff81872cc8)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81a2f661)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff810764b6)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81a2f8a2)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffff810fc2ea)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffffffff81607bbc)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff816adb97)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff8183cab2)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81adf6b1)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff810877f7)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81adf928)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffff8110937c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
```
```
In drivers/clk/clk.c (ffffffff8164146c)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff81700e13)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818c46cd)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
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
In arch/x86/kernel/process.c (ffffffff81aebe48)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
```
```
In arch/x86/mm/tlb.c (ffffffff81089963)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
```
```
In kernel/sched/idle.c (ffffffff81aec0ff)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_idle_poll
  - kernel/sched/idle.c:cpu_idle_poll
```
```
In kernel/printk/printk.c (ffffffff81114677)
Location: include/linux/srcu.h:161
Inline: True
```
```
In drivers/clk/clk.c (ffffffff8165b823)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_enable
  - drivers/clk/clk.c:clk_core_disable
  - drivers/clk/clk.c:clk_core_disable
```
```
In drivers/base/power/runtime.c (ffffffff8171acb0)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_resume
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
  - drivers/base/power/runtime.c:rpm_idle
```
```
In drivers/cpuidle/cpuidle.c (ffffffff818e0a54)
Location: include/linux/srcu.h:161
Inline: True
Inline callers:
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
</details>
</li>
</ul>

## Differences
