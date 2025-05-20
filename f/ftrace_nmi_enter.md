# Function: <code>ftrace_nmi_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/ftrace_irq.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: include/linux/ftrace_irq.h:9
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810317c4)
Location: include/linux/ftrace_irq.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f9d4)
Location: include/linux/ftrace_irq.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810319e4)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032b54)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81033f04)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035ca7)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810364be)
Location: include/linux/ftrace_irq.h:19
Inline: True
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
In arch/x86/kernel/traps.c (ffffffff81bbd72b)
Location: include/linux/ftrace_irq.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
  - arch/x86/kernel/traps.c:exc_double_fault
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbdeb5)
Location: include/linux/ftrace_irq.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbea4d)
Location: include/linux/ftrace_irq.h:10
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:exc_machine_check
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
In kernel/entry/common.c (ffffffff81c3889c)
Location: include/linux/ftrace_irq.h:10
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
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
In kernel/entry/common.c (ffffffff81c2ac9c)
Location: include/linux/ftrace_irq.h:10
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
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
In kernel/entry/common.c (ffffffff81d49237)
Location: include/linux/ftrace_irq.h:15
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
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
In kernel/entry/common.c (ffffffff81f186f7)
Location: include/linux/ftrace_irq.h:15
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
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
In kernel/entry/common.c (ffffffff820bfc97)
Location: include/linux/ftrace_irq.h:15
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
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
In kernel/entry/common.c (ffffffff82141a74)
Location: include/linux/ftrace_irq.h:15
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
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
In kernel/entry/common.c (ffffffff822239a4)
Location: include/linux/ftrace_irq.h:15
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_enter
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
In arch/arm64/kernel/irq.c (ffff800010086e88)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
```
In arch/arm64/kernel/traps.c (ffff800010095778)
Location: include/linux/ftrace_irq.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:do_serror
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a946c)
Location: include/linux/ftrace_irq.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7d18)
Location: include/linux/ftrace_irq.h:19
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800010081aa4)
Location: include/linux/ftrace_irq.h:19
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
In arch/arm/kernel/traps.c (c0302214)
Location: include/linux/ftrace_irq.h:19
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/ftrace_irq.h:19
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
In arch/powerpc/kernel/traps.c (c00000000002e5c8)
Location: include/linux/ftrace_irq.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037aac)
Location: include/linux/ftrace_irq.h:19
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In arch/powerpc/perf/core-book3s.c (c000000000129304)
Location: include/linux/ftrace_irq.h:19
Inline: True
Inline callers:
  - arch/powerpc/perf/core-book3s.c:perf_event_interrupt
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103661e)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81025f6a)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103647e)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8103747e)
Location: include/linux/ftrace_irq.h:19
Inline: True
```
</details>
</li>
</ul>

## Differences
