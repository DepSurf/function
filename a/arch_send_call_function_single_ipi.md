# Function: <code>arch_send_call_function_single_ipi</code>

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
In kernel/smp.c (ffffffff8110388d)
Location: arch/x86/include/asm/smp.h:131
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff81170de6)
Location: arch/x86/include/asm/smp.h:131
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff8110acb1)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8117e4d0)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff811124d1)
Location: arch/x86/include/asm/smp.h:118
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8118a0e0)
Location: arch/x86/include/asm/smp.h:118
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff81113a91)
Location: arch/x86/include/asm/smp.h:118
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8118cc2d)
Location: arch/x86/include/asm/smp.h:118
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff8111f011)
Location: arch/x86/include/asm/smp.h:119
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff8119a84f)
Location: arch/x86/include/asm/smp.h:119
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff8112c34a)
Location: arch/x86/include/asm/smp.h:119
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811b028f)
Location: arch/x86/include/asm/smp.h:119
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff81137c1a)
Location: arch/x86/include/asm/smp.h:119
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811be8aa)
Location: arch/x86/include/asm/smp.h:119
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff81142d67)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811ce462)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff8114e8bf)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811daa82)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3ef2)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/sched/core.c:send_call_function_single_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e191c)
Location: arch/x86/include/asm/smp.h:110
Inline: True
Inline callers:
  - kernel/sched/core.c:send_call_function_single_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e372c)
Location: arch/x86/include/asm/smp.h:110
Inline: True
Inline callers:
  - kernel/sched/core.c:send_call_function_single_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fa291)
Location: arch/x86/include/asm/smp.h:110
Inline: True
Inline callers:
  - kernel/sched/core.c:send_call_function_single_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116881)
Location: arch/x86/include/asm/smp.h:117
Inline: True
Inline callers:
  - kernel/sched/core.c:send_call_function_single_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113ddab)
Location: arch/x86/include/asm/smp.h:106
Inline: True
Inline callers:
  - kernel/sched/core.c:send_call_function_single_ipi
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120e1f1)
Location: arch/x86/include/asm/smp.h:105
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81225981)
Location: arch/x86/include/asm/smp.h:99
Inline: True
Inline callers:
  - kernel/smp.c:smp_call_function_many_cond
  - kernel/smp.c:__smp_call_single_queue
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
void arch_send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/smp.c (ffff80001009c7f0)
Location: arch/arm64/kernel/smp.c:810
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffff80001009c7f0-ffff80001009c8dc: arch_send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp.c (c0312fb0)
Location: arch/arm/kernel/smp.c:566
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
c0312fb0-c03130ec: arch_send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/smp.c (c000000000055010)
Location: arch/powerpc/kernel/smp.c:337
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
c000000000055010-c0000000000550bc: arch_send_call_function_single_ipi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void arch_send_call_function_single_ipi(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/smp.c (ffffffe0000b7fc6)
Location: arch/riscv/kernel/smp.c:177
Inline: False
Direct callers:
  - kernel/smp.c:generic_exec_single
  - kernel/irq_work.c:irq_work_queue_on
```
**Symbols:**

```
ffffffe0000b7fc6-ffffffe0000b8034: arch_send_call_function_single_ipi (STB_GLOBAL)
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
In kernel/smp.c (ffffffff81146edf)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811d30a2)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff8113a1db)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811c5e62)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff81144d8f)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811d0e72)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
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
In kernel/smp.c (ffffffff8115190f)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/smp.c:generic_exec_single
```
```
In kernel/irq_work.c (ffffffff811df165)
Location: arch/x86/include/asm/smp.h:120
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_queue_on
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
