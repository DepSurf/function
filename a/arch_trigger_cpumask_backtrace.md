# Function: <code>arch_trigger_cpumask_backtrace</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81058cd0)
Location: arch/x86/kernel/apic/hw_nmi.c:35
Inline: False
Direct callers:
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81058cd0-ffffffff81058ceb: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81058320)
Location: arch/x86/kernel/apic/hw_nmi.c:35
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81058320-ffffffff8105833b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff8105c820)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff8105c820-ffffffff8105c83b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff8105f890)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff8105f890-ffffffff8105f8ab: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81065500)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81065500-ffffffff8106551b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81068c20)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81068c20-ffffffff81068c3b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff810695a0)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff810695a0-ffffffff810695bb: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81070580)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81070580-ffffffff8107059b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81071a40)
Location: arch/x86/kernel/apic/hw_nmi.c:37
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81071a40-ffffffff81071a5b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81072540)
Location: arch/x86/kernel/apic/hw_nmi.c:37
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/rcu/tree.c:trigger_single_cpu_backtrace
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81072540-ffffffff8107255b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff8107e420)
Location: arch/x86/kernel/apic/hw_nmi.c:37
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/rcu/tree.c:trigger_single_cpu_backtrace
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff8107e420-ffffffff8107e43b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff8108dae0)
Location: arch/x86/kernel/apic/hw_nmi.c:37
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/rcu/tree.c:trigger_single_cpu_backtrace
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff8108dae0-ffffffff8108db05: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff810a22b0)
Location: arch/x86/kernel/apic/hw_nmi.c:37
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/sched/core.c:dump_cpu_task
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff810a22b0-ffffffff810a22d5: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, int exclude_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff810a5290)
Location: arch/x86/kernel/apic/hw_nmi.c:37
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/sched/core.c:dump_cpu_task
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
  - kernel/watchdog.c:watchdog_hardlockup_check
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff810a5290-ffffffff810a52b1: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, int exclude_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff810ac310)
Location: arch/x86/kernel/apic/hw_nmi.c:39
Inline: False
Direct callers:
  - kernel/panic.c:oops_enter
  - kernel/panic.c:panic
  - kernel/panic.c:panic
  - kernel/sched/core.c:dump_cpu_task
  - kernel/hung_task.c:check_hung_uninterruptible_tasks
  - kernel/watchdog.c:watchdog_timer_fn
  - kernel/watchdog.c:watchdog_hardlockup_check
  - kernel/watchdog.c:watchdog_hardlockup_check
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff810ac310-ffffffff810ac331: arch_trigger_cpumask_backtrace (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp.c (c0313b58)
Location: arch/arm/kernel/smp.c:813
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
c0313b58-c0313b7c: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/stacktrace.c (c0000000000699d0)
Location: arch/powerpc/kernel/stacktrace.c:267
Inline: False
Direct callers:
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
c0000000000699d0-c000000000069a0c: arch_trigger_cpumask_backtrace (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81069090)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81069090-ffffffff810690ab: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81059400)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81059400-ffffffff8105941b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff81069540)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff81069540-ffffffff8106955b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/hw_nmi.c (ffffffff8106ac40)
Location: arch/x86/kernel/apic/hw_nmi.c:36
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/hung_task.c:watchdog
  - kernel/watchdog.c:watchdog_timer_fn
  - drivers/tty/sysrq.c:sysrq_handle_showallcpus
```
**Symbols:**

```
ffffffff8106ac40-ffffffff8106ac5b: arch_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int exclude_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
