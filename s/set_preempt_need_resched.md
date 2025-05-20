# Function: <code>set_preempt_need_resched</code>

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
In arch/x86/kernel/acpi/cstate.c (ffffffff8105014e)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810aa37e)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
  - kernel/sched/core.c:scheduler_ipi
```
```
In kernel/sched/idle.c (ffffffff810c3ee6)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/idle/intel_idle.c (ffffffff814794ad)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle
  - drivers/idle/intel_idle.c:intel_idle_freeze
```
```
In drivers/cpuidle/driver.c (ffffffff816bc0c3)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff810502aa)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810aeeae)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c7bdb)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
```
In drivers/idle/intel_idle.c (ffffffff814c7956)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff8171d9d3)
Location: arch/x86/include/asm/preempt.h:48
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff818d3d33)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810b4fda)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cdbf9)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814e9870)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff818d407d)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff8190ae93)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810b125a)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ca609)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff814f5490)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_freeze
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/driver.c (ffffffff8190b208)
Location: arch/x86/include/asm/preempt.h:54
Inline: True
Inline callers:
  - drivers/cpuidle/driver.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81995206)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810b869a)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d1e19)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff81535d13)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff819955a5)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff819f1764)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810c018a)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c45a9)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In drivers/idle/intel_idle.c (ffffffff8156b8b4)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff819f1ae5)
Location: arch/x86/include/asm/preempt.h:55
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2cc04)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810c94fa)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810cd869)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff81114a69)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
```
In drivers/idle/intel_idle.c (ffffffff81583434)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2d07a)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a9cd72)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810d112a)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d5c59)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff8111a540)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff815b3b7f)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a9d1fa)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81ad45c2)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810db0da)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e0259)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff81126940)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff815d4dbf)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81ad4a02)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff8102e360)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81068ae4)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smp.c (ffffffff81bbefd9)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff810e1ded)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e85c4)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff81136cbe)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff8167e906)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81bcc985)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff8102f1c0)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a784)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smp.c (ffffffff81c377d8)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff810df1af)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e61cb)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff8113231e)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:sync_sched_exp_online_cleanup
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff8169d606)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c454e5)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff8102fcd0)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b24b)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smp.c (ffffffff81c29ea8)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff810e0e3f)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e819b)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff81bd48d9)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff8168038d)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81c38765)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff810346c0)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075d68)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smp.c (ffffffff81d48415)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff810f5d7c)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810ff85b)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle_precise
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff81caed51)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcutree_online_cpu
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff816f50fa)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81d57045)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff8103a3c0)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff810847b1)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smp.c (ffffffff81f17367)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff81110f2d)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff81133890)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff8117dbe6)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_flavor_sched_clock_irq
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff81821a23)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff81f29a14)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff81042a10)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff81097a41)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:mwait_idle_with_hints
```
```
In arch/x86/kernel/smp.c (ffffffff820be9e7)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff81137edb)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff8115dcc0)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff811b6a88)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff81952713)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
```
```
In drivers/cpuidle/poll_state.c (ffffffff820d5874)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff81042be0)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff82143124)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smp.c (ffffffff82140547)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff8114703a)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff8116e3a0)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff811c74b8)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff8214365b)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff82144080)
Location: arch/x86/include/asm/preempt.h:59
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/xen/smp.c (ffffffff810490b0)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/xen/smp.c:xen_reschedule_interrupt
```
```
In arch/x86/kernel/acpi/cstate.c (ffffffff8222580f)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In arch/x86/kernel/smp.c (ffffffff82222556)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/sched/core.c (ffffffff8115286a)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/build_policy.c (ffffffff8117b960)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:play_idle_precise
  - kernel/sched/build_policy.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff811d79d8)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_read_unlock_special
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff82225d6b)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle_xstate
  - drivers/idle/intel_idle.c:intel_idle_ibrs
  - drivers/idle/intel_idle.c:intel_idle_irq
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff822267a0)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
</details>
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
In kernel/sched/core.c (ffff80001013ad58)
Location: arch/arm64/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffff80001013ff78)
Location: arch/arm64/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffff80001018c830)
Location: arch/arm64/include/asm/preempt.h:29
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
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
In kernel/sched/core.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
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
In kernel/sched/core.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
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
In kernel/sched/core.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
```
```
In kernel/sched/idle.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/asm-generic/preempt.h:35
Inline: True
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a73432)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810d558a)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810da409)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff8111ef20)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff815c8b0f)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a73872)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81a2f7e2)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810c3bda)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810c9419)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff81110930)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff815b1b7f)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81a2fbec)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81adf842)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810d23ca)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810d6789)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff8111ce10)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_need_qs
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff815c909f)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81adfc82)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
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
In arch/x86/kernel/acpi/cstate.c (ffffffff81aec012)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_enter
```
```
In kernel/sched/core.c (ffffffff810dce5a)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:resched_curr
```
```
In kernel/sched/idle.c (ffffffff810e2090)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/sched/idle.c:play_idle
  - kernel/sched/idle.c:do_idle
```
```
In kernel/rcu/tree.c (ffffffff8112a697)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__rcu_read_unlock
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
```
In drivers/idle/intel_idle.c (ffffffff815e2eff)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_s2idle
  - drivers/idle/intel_idle.c:intel_idle
```
```
In drivers/cpuidle/poll_state.c (ffffffff81aec482)
Location: arch/x86/include/asm/preempt.h:58
Inline: True
Inline callers:
  - drivers/cpuidle/poll_state.c:poll_idle
```
</details>
</li>
</ul>

## Differences
