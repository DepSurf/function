# Function: <code>irq_domain_is_msi</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec5a6)
Location: include/linux/irqdomain.h:457
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff810ebee4)
Location: include/linux/irqdomain.h:492
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff810f43c4)
Location: include/linux/irqdomain.h:504
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff810fc7b4)
Location: include/linux/irqdomain.h:510
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff81108064)
Location: include/linux/irqdomain.h:513
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff811116a5)
Location: include/linux/irqdomain.h:520
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff8111d905)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff81129ae5)
Location: include/linux/irqdomain.h:533
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
```
In drivers/gpio/gpiolib.c (ffffffff8160d22c)
Location: include/linux/irqdomain.h:533
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In kernel/irq/irqdomain.c (ffffffff81125395)
Location: include/linux/irqdomain.h:549
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
```
In drivers/gpio/gpiolib.c (ffffffff81633ff4)
Location: include/linux/irqdomain.h:549
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In kernel/irq/irqdomain.c (ffffffff811256f5)
Location: include/linux/irqdomain.h:545
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
```
In drivers/gpio/gpiolib.c (ffffffff81617b44)
Location: include/linux/irqdomain.h:545
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In kernel/irq/irqdomain.c (ffffffff81145e25)
Location: include/linux/irqdomain.h:554
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
```
In drivers/gpio/gpiolib.c (ffffffff81686dc4)
Location: include/linux/irqdomain.h:554
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In kernel/irq/irqdomain.c (ffffffff8116a034)
Location: include/linux/irqdomain.h:569
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
```
In drivers/gpio/gpiolib.c (ffffffff817a3cf8)
Location: include/linux/irqdomain.h:569
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In kernel/irq/irqdomain.c (ffffffff8119ea94)
Location: include/linux/irqdomain.h:557
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
```
In drivers/gpio/gpiolib.c (ffffffff818bb5e7)
Location: include/linux/irqdomain.h:557
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In drivers/gpio/gpiolib.c (ffffffff818fe703)
Location: include/linux/irqdomain.h:560
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In drivers/gpio/gpiolib.c (ffffffff81945d33)
Location: include/linux/irqdomain.h:560
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In kernel/irq/irqdomain.c (ffff800010182dbc)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (c03d2138)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/irqdomain.h:569
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
In kernel/irq/irqdomain.c (ffffffe00011a250)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
</details>
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
In kernel/irq/irqdomain.c (ffffffff81115ee5)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff81106bd5)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff81113dd5)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
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
In kernel/irq/irqdomain.c (ffffffff8111f3f5)
Location: include/linux/irqdomain.h:527
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_check_msi_remap
```
</details>
</li>
</ul>

## Differences
