# Function: <code>arch_irq_work_has_interrupt</code>

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
In arch/x86/kernel/irq_work.c (ffffffff81033cc5)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff81170fc6)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_needs_cpu
  - kernel/irq_work.c:irq_work_tick
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
In arch/x86/kernel/irq_work.c (ffffffff81032e95)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff8117e73b)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81032b15)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff8118a34b)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81030cc5)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff8118ce3b)
Location: arch/x86/include/asm/irq_work.h:6
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81032ed5)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff8119a90b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81034215)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811b034b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff810353f5)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811be96b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81037545)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811ce50b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81037d15)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811dab2b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81039c75)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811f75cb)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff8103a485)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811f612b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff8103be95)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811f701b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81041965)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff812285eb)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81049685)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff812696bb)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_single
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81054715)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff812be59b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_single
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81055775)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff812e51db)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_single
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff8105c9d5)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/time/tick-sched.c (ffffffff83905803)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/irq_work.c (ffffffff8130328b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_single
  - kernel/irq_work.c:irq_work_needs_cpu
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
In kernel/irq_work.c (ffff80001025b344)
Location: arch/arm64/include/asm/irq_work.h:7
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/arm/kernel/smp.c (c0313100)
Location: arch/arm/include/asm/irq_work.h:7
Inline: True
Inline callers:
  - arch/arm/kernel/smp.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (c048e500)
Location: arch/arm/include/asm/irq_work.h:7
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (0)
Location: arch/powerpc/include/asm/irq_work.h:5
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (0)
Location: include/asm-generic/irq_work.h:5
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
In arch/x86/kernel/irq_work.c (ffffffff81037e75)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811d314b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81027855)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/time/tick-sched.c (ffffffff828b25b4)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/time/tick-sched.c:tick_nohz_init
```
```
In kernel/irq_work.c (ffffffff811c5f0b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81037cd5)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811d0f1b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
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
In arch/x86/kernel/irq_work.c (ffffffff81038cd5)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - arch/x86/kernel/irq_work.c:arch_irq_work_raise
```
```
In kernel/irq_work.c (ffffffff811df20b)
Location: arch/x86/include/asm/irq_work.h:8
Inline: True
Inline callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_needs_cpu
```
</details>
</li>
</ul>

## Differences
