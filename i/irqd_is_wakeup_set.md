# Function: <code>irqd_is_wakeup_set</code>

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
In kernel/irq/pm.c (ffffffff810e276a)
Location: include/linux/irq.h:257
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/pm.c (ffffffff810e81fa)
Location: include/linux/irq.h:265
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/pm.c (ffffffff810eec34)
Location: include/linux/irq.h:267
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
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
In kernel/irq/pm.c (ffffffff810eea89)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149f9cc)
Location: include/linux/irq.h:295
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/base/power/wakeirq.c (ffffffff815ed912)
Location: include/linux/irq.h:295
Inline: True
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
In kernel/irq/pm.c (ffffffff810f7539)
Location: include/linux/irq.h:307
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de450)
Location: include/linux/irq.h:307
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/tty/serial/serial_core.c (ffffffff815fadc7)
Location: include/linux/irq.h:307
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff81654cc2)
Location: include/linux/irq.h:307
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff810f5db0)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff810ff899)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150d73a)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
```
```
In drivers/tty/serial/serial_core.c (ffffffff81632ee7)
Location: include/linux/irq.h:302
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff81690592)
Location: include/linux/irq.h:302
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff81101460)
Location: include/linux/irq.h:303
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff8110b079)
Location: include/linux/irq.h:303
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff81651fe7)
Location: include/linux/irq.h:303
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816b0da2)
Location: include/linux/irq.h:303
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff81109c60)
Location: include/linux/irq.h:303
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff8111475b)
Location: include/linux/irq.h:303
Inline: True
Inline callers:
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff81686afb)
Location: include/linux/irq.h:303
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816eaa52)
Location: include/linux/irq.h:303
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff81116030)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff81120bd6)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff816a920b)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8170ea92)
Location: include/linux/irq.h:306
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
In kernel/irq/irqdesc.c (ffffffff81121ce0)
Location: include/linux/irq.h:322
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff8112d1a1)
Location: include/linux/irq.h:322
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175b44b)
Location: include/linux/irq.h:322
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817ca202)
Location: include/linux/irq.h:322
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff8111dd40)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff81128c01)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff8177652b)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817deca2)
Location: include/linux/irq.h:332
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff8111e040)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff81128e81)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff8175a10b)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff817c30a2)
Location: include/linux/irq.h:332
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff8113e4c0)
Location: include/linux/irq.h:334
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff81149461)
Location: include/linux/irq.h:334
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff817dd64b)
Location: include/linux/irq.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8184d4f2)
Location: include/linux/irq.h:334
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff811610d0)
Location: include/linux/irq.h:334
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff8116e018)
Location: include/linux/irq.h:334
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff8191c04a)
Location: include/linux/irq.h:334
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff819928d2)
Location: include/linux/irq.h:334
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff811946d0)
Location: include/linux/irq.h:336
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff811a3298)
Location: include/linux/irq.h:336
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff81a77faa)
Location: include/linux/irq.h:336
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff81b02dc2)
Location: include/linux/irq.h:336
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff811a5f30)
Location: include/linux/irq.h:339
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff811b5198)
Location: include/linux/irq.h:339
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff81ac2a5a)
Location: include/linux/irq.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acba51)
Location: include/linux/irq.h:339
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
```
```
In drivers/base/power/wakeirq.c (ffffffff81b50dc2)
Location: include/linux/irq.h:339
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff811b5a20)
Location: include/linux/irq.h:336
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff811c5018)
Location: include/linux/irq.h:336
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b14a2a)
Location: include/linux/irq.h:336
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1e1f6)
Location: include/linux/irq.h:336
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_handle_irq
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba9342)
Location: include/linux/irq.h:336
Inline: True
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
In kernel/irq/irqdesc.c (ffff800010177834)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffff800010186c10)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffff800010880df4)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffff8000108feab4)
Location: include/linux/irq.h:306
Inline: True
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
In kernel/irq/irqdesc.c (c03c9114)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (c03d5870)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (c0980fcc)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (c09e8f4c)
Location: include/linux/irq.h:306
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
In kernel/irq/irqdesc.c (c0000000001d1578)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (c0000000001e1448)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (c000000000929f74)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (c00000000099ba30)
Location: include/linux/irq.h:306
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
In kernel/irq/irqdesc.c (ffffffe00011278c)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054f60c)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffe00058d096)
Location: include/linux/irq.h:306
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
In kernel/irq/irqdesc.c (ffffffff8110e610)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff811191b6)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff8166ec6b)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816d41e2)
Location: include/linux/irq.h:306
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff810ff3d0)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff8110a226)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff8164dc7b)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff816af482)
Location: include/linux/irq.h:306
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff8110c500)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff811170a6)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff8169d04b)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff81702752)
Location: include/linux/irq.h:306
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff81117630)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:wakeup_show
```
```
In kernel/irq/pm.c (ffffffff81122736)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - kernel/irq/pm.c:rearm_wake_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
```
In drivers/tty/serial/serial_core.c (ffffffff816b5feb)
Location: include/linux/irq.h:306
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
```
```
In drivers/base/power/wakeirq.c (ffffffff8171cf72)
Location: include/linux/irq.h:306
Inline: True
```
</details>
</li>
</ul>

## Differences
