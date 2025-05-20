# Function: <code>ftrace_nmi_exit</code>

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
Location: include/linux/ftrace_irq.h:10
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
Location: include/linux/ftrace_irq.h:10
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
In arch/x86/kernel/nmi.c (ffffffff81031826)
Location: include/linux/ftrace_irq.h:27
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
In arch/x86/kernel/nmi.c (ffffffff8102fa36)
Location: include/linux/ftrace_irq.h:27
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
In arch/x86/kernel/nmi.c (ffffffff81031a46)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff81032bb6)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff81033f66)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff81035d0d)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff81036524)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/traps.c (ffffffff81bbd759)
Location: include/linux/ftrace_irq.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_debug
  - arch/x86/kernel/traps.c:exc_int3
```
```
In arch/x86/kernel/nmi.c (ffffffff81bbded7)
Location: include/linux/ftrace_irq.h:18
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:exc_nmi
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81bbea69)
Location: include/linux/ftrace_irq.h:18
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
In kernel/entry/common.c (ffffffff81c388c0)
Location: include/linux/ftrace_irq.h:18
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
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
In kernel/entry/common.c (ffffffff81c2acc0)
Location: include/linux/ftrace_irq.h:18
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
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
In kernel/entry/common.c (ffffffff81d49260)
Location: include/linux/ftrace_irq.h:27
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
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
In kernel/entry/common.c (ffffffff81f18720)
Location: include/linux/ftrace_irq.h:27
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
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
In kernel/entry/common.c (ffffffff820bfcd0)
Location: include/linux/ftrace_irq.h:27
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
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
In kernel/entry/common.c (ffffffff82141ad0)
Location: include/linux/ftrace_irq.h:27
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
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
In kernel/entry/common.c (ffffffff82223a00)
Location: include/linux/ftrace_irq.h:27
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_nmi_exit
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
In arch/arm64/kernel/irq.c (ffff800010086e24)
Location: include/linux/ftrace_irq.h:28
Inline: True
```
```
In arch/arm64/kernel/traps.c (ffff800010095800)
Location: include/linux/ftrace_irq.h:28
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:do_serror
```
```
In arch/arm64/kernel/acpi.c (ffff8000100a9528)
Location: include/linux/ftrace_irq.h:28
Inline: True
Inline callers:
  - arch/arm64/kernel/acpi.c:apei_claim_sea
```
```
In arch/arm64/kernel/sdei.c (ffff800010da7e78)
Location: include/linux/ftrace_irq.h:28
Inline: True
Inline callers:
  - arch/arm64/kernel/sdei.c:__sdei_handler
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800010081a5c)
Location: include/linux/ftrace_irq.h:28
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
In arch/arm/kernel/traps.c (c0302278)
Location: include/linux/ftrace_irq.h:28
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:handle_fiq_as_nmi
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/ftrace_irq.h:28
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
In arch/powerpc/kernel/traps.c (c00000000002e584)
Location: include/linux/ftrace_irq.h:28
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:machine_check_exception
  - arch/powerpc/kernel/traps.c:system_reset_exception
```
```
In arch/powerpc/kernel/watchdog.c (c000000000037b70)
Location: include/linux/ftrace_irq.h:28
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In arch/powerpc/perf/core-book3s.c (c0000000001294c4)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff81036684)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff81025fd0)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff810364e4)
Location: include/linux/ftrace_irq.h:28
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
In arch/x86/kernel/nmi.c (ffffffff810374e4)
Location: include/linux/ftrace_irq.h:28
Inline: True
```
</details>
</li>
</ul>

## Differences
