# Function: <code>__preempt_count_sub</code>

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
In arch/x86/kernel/traps.c (ffffffff8102f298)
Location: arch/x86/include/asm/preempt.h:72
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/nmi.c (ffffffff81032a35)
Location: arch/x86/include/asm/preempt.h:72
Inline: True
```
```
In kernel/softirq.c (ffffffff81084c91)
Location: arch/x86/include/asm/preempt.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:__local_bh_enable
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:irq_exit
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
In arch/x86/kernel/nmi.c (ffffffff81031bba)
Location: arch/x86/include/asm/preempt.h:72
Inline: True
```
```
In kernel/softirq.c (ffffffff81088a60)
Location: arch/x86/include/asm/preempt.h:72
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff8112822e)
Location: arch/x86/include/asm/preempt.h:72
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff8103181b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/softirq.c (ffffffff8108d9a0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff81131e2e)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff8102fa2b)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
```
```
In kernel/softirq.c (ffffffff8108a9d0)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff811333ea)
Location: arch/x86/include/asm/preempt.h:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff81031a3b)
Location: arch/x86/include/asm/preempt.h:79
Inline: True
```
```
In kernel/softirq.c (ffffffff810916a0)
Location: arch/x86/include/asm/preempt.h:79
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff8114009c)
Location: arch/x86/include/asm/preempt.h:79
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff81032bab)
Location: arch/x86/include/asm/preempt.h:79
Inline: True
```
```
In kernel/softirq.c (ffffffff81095170)
Location: arch/x86/include/asm/preempt.h:79
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff8114ea97)
Location: arch/x86/include/asm/preempt.h:79
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff81033f5b)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff8109d4e0)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff8115b677)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff81035d02)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff810a1ac0)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff81167dc5)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff81036519)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff810a8080)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff81173c85)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/traps.c (ffffffff81bbd779)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
```
```
In arch/x86/kernel/irq.c (ffffffff81bbdc91)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbdefb)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbea85)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
```
```
In arch/x86/kernel/smp.c (ffffffff81bbefe9)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810af960)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff81185a85)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/irq.c (ffffffff81c363e3)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff81c377e8)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810ab0f0)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/entry/common.c (ffffffff81c388e1)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
```
In kernel/stop_machine.c (ffffffff81182b95)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/irq.c (ffffffff81c287e3)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff81c29eb8)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810ac2e0)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/entry/common.c (ffffffff81c2ace1)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
```
In kernel/stop_machine.c (ffffffff81183ce5)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/irq.c (ffffffff81d46953)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff81d48422)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810bd940)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/entry/common.c (ffffffff81d49281)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
```
In kernel/stop_machine.c (ffffffff811abe72)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/irq.c (ffffffff81f14e12)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff81f17374)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In arch/x86/mm/kmmio.c (ffffffff810b708d)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In kernel/softirq.c (ffffffff810d45ba)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/signal.c (ffffffff810e4354)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
```
```
In kernel/smpboot.c (ffffffff81103df7)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff81f226da)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/sched/core.c:__cond_resched
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
```
```
In kernel/entry/common.c (ffffffff81f18740)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
```
In kernel/stop_machine.c (ffffffff811dd92f)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/irq.c (ffffffff820bc282)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff820be9f4)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810f348a)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/signal.c (ffffffff811049e4)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
```
```
In kernel/smpboot.c (ffffffff81129567)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8113a261)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
```
```
In kernel/entry/common.c (ffffffff820bfcf0)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
```
In kernel/stop_machine.c (ffffffff8122339f)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/irq.c (ffffffff8213d9c2)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff82140554)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff810ff8ba)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/signal.c (ffffffff81110c64)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
```
```
In kernel/smpboot.c (ffffffff81136a07)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8115244d)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
```
```
In kernel/entry/common.c (ffffffff82141af9)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
```
In kernel/stop_machine.c (ffffffff81239bcf)
Location: arch/x86/include/asm/preempt.h:83
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/irq.c (ffffffff8221f9c1)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_nested_ipi
  - arch/x86/kernel/irq.c:sysvec_kvm_posted_intr_ipi
```
```
In arch/x86/kernel/smp.c (ffffffff82222563)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/smp.c:sysvec_reschedule_ipi
```
```
In kernel/softirq.c (ffffffff81108f6d)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/signal.c (ffffffff8111a5d4)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/smpboot.c (ffffffff81141c07)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff8115e312)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_mm_cid_after_execve
  - kernel/sched/core.c:sched_mm_cid_before_execve
  - kernel/sched/core.c:klp_cond_resched
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:rt_mutex_schedule
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
```
```
In kernel/entry/common.c (ffffffff82223a29)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
```
```
In kernel/stop_machine.c (ffffffff8125389f)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/arm64/kernel/irq.c (ffff800010086e10)
Location: arch/arm64/include/asm/preempt.h:51
Inline: True
```
```
In arch/arm64/kernel/traps.c (ffff8000100957ec)
Location: arch/arm64/include/asm/preempt.h:51
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:do_serror
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a9518)
Location: arch/arm64/include/asm/preempt.h:51
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7e64)
Location: arch/arm64/include/asm/preempt.h:51
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
```
```
In kernel/softirq.c (ffff8000100ff170)
Location: arch/arm64/include/asm/preempt.h:51
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffff8000101e8088)
Location: arch/arm64/include/asm/preempt.h:51
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800010081a48)
Location: arch/arm64/include/asm/preempt.h:51
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_handle_irq
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
In arch/arm/kernel/traps.c (c0302264)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
```
```
In kernel/softirq.c (c035be88)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (c04283a0)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/asm-generic/preempt.h:57
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
In arch/powerpc/kernel/traps.c (c00000000002e570)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037b64)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In arch/powerpc/perf/core-book3s.c (c0000000001294b0)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
```
```
In kernel/softirq.c (c00000000014648c)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (c000000000258cb8)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In kernel/softirq.c (ffffffe0000c7096)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffe00015d39a)
Location: include/asm-generic/preempt.h:57
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff81036679)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff810a19a0)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff8116c2a5)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff81025fc5)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff8109035b)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff8115f4a5)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/kernel/nmi.c (ffffffff810364d9)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/softirq.c (ffffffff810a1950)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/stop_machine.c (ffffffff8116a075)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
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
In arch/x86/xen/irq.c (ffffffff810293c3)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/xen/irq.c:xen_irq_disable
  - arch/x86/xen/irq.c:xen_restore_fl
```
```
In arch/x86/kernel/traps.c (ffffffff81032a46)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_debug
  - arch/x86/kernel/traps.c:ist_begin_non_atomic
```
```
In arch/x86/kernel/nmi.c (ffffffff810374d9)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c9be)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
  - arch/x86/mm/kmmio.c:kmmio_handler
```
```
In kernel/softirq.c (ffffffff810a9940)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:__do_softirq
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:__local_bh_enable_ip
  - kernel/softirq.c:_local_bh_enable
```
```
In kernel/signal.c (ffffffff810b5121)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
```
```
In kernel/smpboot.c (ffffffff810d1162)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/smpboot.c:smpboot_thread_fn
```
```
In kernel/sched/core.c (ffffffff810da8df)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/sched/core.c:do_sched_yield
  - kernel/sched/core.c:preempt_schedule_irq
  - kernel/sched/core.c:preempt_schedule_notrace
  - kernel/sched/core.c:preempt_schedule_common
  - kernel/sched/core.c:schedule_preempt_disabled
  - kernel/sched/core.c:schedule
  - kernel/sched/core.c:schedule
```
```
In kernel/locking/percpu-rwsem.c (ffffffff81105dc8)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
```
```
In kernel/stop_machine.c (ffffffff811777cb)
Location: arch/x86/include/asm/preempt.h:82
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
```
</details>
</li>
</ul>

## Differences
