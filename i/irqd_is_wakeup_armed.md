# Function: <code>irqd_is_wakeup_armed</code>

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
In kernel/irq/pm.c (ffffffff810e2909)
Location: include/linux/irq.h:282
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/pm.c (ffffffff810e8399)
Location: include/linux/irq.h:290
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/pm.c (ffffffff810eedc9)
Location: include/linux/irq.h:292
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/pm.c (ffffffff810eec59)
Location: include/linux/irq.h:320
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff814f8139)
Location: include/linux/irq.h:320
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_freeze_wake
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
In kernel/irq/pm.c (ffffffff810f7709)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff8153950c)
Location: include/linux/irq.h:332
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_wake
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
In kernel/irq/pm.c (ffffffff810ffa69)
Location: include/linux/irq.h:327
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff8156f65c)
Location: include/linux/irq.h:327
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
In kernel/irq/pm.c (ffffffff8110b249)
Location: include/linux/irq.h:328
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff81587246)
Location: include/linux/irq.h:328
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
In kernel/irq/pm.c (ffffffff81114929)
Location: include/linux/irq.h:328
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff815b7eb6)
Location: include/linux/irq.h:328
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
In kernel/irq/pm.c (ffffffff81120a89)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff815d9071)
Location: include/linux/irq.h:331
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
In kernel/irq/pm.c (ffffffff8112d045)
Location: include/linux/irq.h:347
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff816830d8)
Location: include/linux/irq.h:347
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
In kernel/irq/pm.c (ffffffff81128aa5)
Location: include/linux/irq.h:357
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff816a14c8)
Location: include/linux/irq.h:357
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
In kernel/irq/pm.c (ffffffff81128d35)
Location: include/linux/irq.h:357
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff81684354)
Location: include/linux/irq.h:357
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
In kernel/irq/pm.c (ffffffff81149315)
Location: include/linux/irq.h:359
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff816f9604)
Location: include/linux/irq.h:359
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
In kernel/irq/pm.c (ffffffff8116de85)
Location: include/linux/irq.h:359
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff818268bc)
Location: include/linux/irq.h:359
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
In kernel/irq/pm.c (ffffffff811a2f85)
Location: include/linux/irq.h:361
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff81958663)
Location: include/linux/irq.h:361
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
In kernel/irq/pm.c (ffffffff811b4e85)
Location: include/linux/irq.h:364
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff8199e951)
Location: include/linux/irq.h:364
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
In kernel/irq/pm.c (ffffffff811c4d05)
Location: include/linux/irq.h:361
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff819e6ff1)
Location: include/linux/irq.h:361
Inline: True
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
In kernel/irq/pm.c (ffff800010186a54)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (c03d567c)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/pm.c (c0000000001e1264)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/pm.c (ffffffff81119069)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
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
In kernel/irq/pm.c (ffffffff8110a0d9)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff815b5561)
Location: include/linux/irq.h:331
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
In kernel/irq/pm.c (ffffffff81116f59)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff815cd351)
Location: include/linux/irq.h:331
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
In kernel/irq/pm.c (ffffffff811225e9)
Location: include/linux/irq.h:331
Inline: True
Inline callers:
  - kernel/irq/pm.c:irq_pm_check_wakeup
```
```
In drivers/acpi/sleep.c (ffffffff815e71f1)
Location: include/linux/irq.h:331
Inline: True
```
</details>
</li>
</ul>

## Differences
