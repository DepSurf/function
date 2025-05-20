# Function: <code>rcu_irq_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e7c30)
Location: kernel/rcu/tree.c:882
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:default_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/process.c:mwait_idle
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/sched/idle.c:cpu_startup_entry
  - kernel/time/tick-broadcast-hrtimer.c:bc_set_next
  - kernel/trace/trace_stack.c:check_stack
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_freeze
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810e7c30-ffffffff810e7c80: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ede7b)
Location: kernel/rcu/tree.c:927
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff810eb3b0-ffffffff810eb3ce: rcu_irq_enter.part.67 (STB_LOCAL)
ffffffff810ede30-ffffffff810ede5f: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f4f5b)
Location: kernel/rcu/tree.c:928
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff810f3040-ffffffff810f305e: rcu_irq_enter.part.69 (STB_LOCAL)
ffffffff810f4f10-ffffffff810f4f3f: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5d5b)
Location: kernel/rcu/tree.c:1016
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/trace/trace_stack.c:check_stack
```
**Symbols:**

```
ffffffff810f5d10-ffffffff810f5d40: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffbc0)
Location: kernel/rcu/tree.c:1037
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff810ffbc0-ffffffff810ffbf7: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81107ffb)
Location: kernel/rcu/tree.c:995
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
```
**Symbols:**

```
ffffffff81107fc0-ffffffff81107fdf: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811134a0)
Location: kernel/rcu/tree.c:898
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff811134a0-ffffffff81113502: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d0e0)
Location: kernel/rcu/tree.c:860
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff8111d0e0-ffffffff8111d142: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811295e0)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff811295e0-ffffffff81129648: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bbfa80)
Location: kernel/rcu/tree.c:1042
Inline: False
Direct callers:
  - arch/x86/entry/common.c:idtentry_enter_cond_rcu
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff81bbfa80-ffffffff81bbfa8b: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c38860)
Location: kernel/rcu/tree.c:1111
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff81c38860-ffffffff81c3886b: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81c2ac60)
Location: kernel/rcu/tree.c:1115
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff81c2ac60-ffffffff81c2ac6b: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81d49200)
Location: kernel/rcu/tree.c:1068
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff81d49200-ffffffff81d4920b: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81f18680)
Location: kernel/rcu/tree.c:1068
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
  - kernel/entry/common.c:irqentry_enter
```
**Symbols:**

```
ffffffff81f18680-ffffffff81f1868f: rcu_irq_enter (STB_GLOBAL)
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
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010190b80)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffff800010190b80-ffff800010190bf4: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03de768)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
c03de768-c03de80c: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ec020)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
c0000000001ec020-c0000000001ec0a8: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000124114)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffe000124114-ffffffe000124194: rcu_irq_enter (STB_GLOBAL)
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
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81121bc0)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff81121bc0-ffffffff81121c28: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811141d0)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff811141d0-ffffffff8111424b: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111fab0)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff8111fab0-ffffffff8111fb18: rcu_irq_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_irq_enter();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112bc20)
Location: kernel/rcu/tree.c:868
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wait
  - kernel/softirq.c:irq_enter
  - kernel/rcu/tree.c:rcu_irq_enter_irqson
```
**Symbols:**

```
ffffffff8112bc20-ffffffff8112bc88: rcu_irq_enter (STB_GLOBAL)
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
