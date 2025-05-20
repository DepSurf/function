# Function: <code>rcu_irq_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7ba0)
Location: kernel/rcu/tree.c:754
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace_stack.c:check_stack
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810e7ba0-ffffffff810e7c2c: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eddfb)
Location: kernel/rcu/tree.c:789
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff810eb350-ffffffff810eb3a9: rcu_irq_exit.part.66 (STB_LOCAL)
ffffffff810eddb0-ffffffff810eddd6: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4edb)
Location: kernel/rcu/tree.c:790
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff810f2fe0-ffffffff810f3039: rcu_irq_exit.part.68 (STB_LOCAL)
ffffffff810f4e90-ffffffff810f4eb6: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5cce)
Location: kernel/rcu/tree.c:885
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff810f5c80-ffffffff810f5cb0: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffad0)
Location: kernel/rcu/tree.c:888
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff810ffad0-ffffffff810ffb08: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81107ecb)
Location: kernel/rcu/tree.c:842
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffff81107e90-ffffffff81107eaf: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113350)
Location: kernel/rcu/tree.c:733
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff81113350-ffffffff811133ca: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111cfa0)
Location: kernel/rcu/tree.c:694
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff8111cfa0-ffffffff8111d01a: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129490)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff81129490-ffffffff81129516: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bbfa00)
Location: kernel/rcu/tree.c:759
Inline: False
Direct callers:
  - arch/x86/entry/common.c:idtentry_exit_cond_rcu
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff81bbfa00-ffffffff81bbfa0b: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c387e0)
Location: kernel/rcu/tree.c:825
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81c387e0-ffffffff81c387eb: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c2abe0)
Location: kernel/rcu/tree.c:830
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81c2abe0-ffffffff81c2abeb: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81d49180)
Location: kernel/rcu/tree.c:805
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81d49180-ffffffff81d4918b: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81f185f0)
Location: kernel/rcu/tree.c:812
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
  - kernel/entry/common.c:irqentry_exit
```
**Symbols:**

```
ffffffff81f185f0-ffffffff81f185ff: rcu_irq_exit (STB_GLOBAL)
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
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010190a08)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffff800010190a08-ffff800010190a90: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03de588)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
c03de588-c03de67c: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ebe30)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
c0000000001ebe30-c0000000001ebee8: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000123fae)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffe000123fae-ffffffe000124036: rcu_irq_exit (STB_GLOBAL)
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
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81121a70)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff81121a70-ffffffff81121af6: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811140e0)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff811140e0-ffffffff8111417c: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f960)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff8111f960-ffffffff8111f9e6: rcu_irq_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_irq_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112bad0)
Location: kernel/rcu/tree.c:702
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit
  - kernel/rcu/tree.c:rcu_irq_exit_irqson
```
**Symbols:**

```
ffffffff8112bad0-ffffffff8112bb56: rcu_irq_exit (STB_GLOBAL)
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
