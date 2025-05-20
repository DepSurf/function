# Function: <code>gpio_get_value_cansleep</code>

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
In drivers/mfd/arizona-irq.c (ffffffff8157e267)
Location: include/asm-generic/gpio.h:79
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff815ed3df)
Location: include/asm-generic/gpio.h:79
Inline: True
Inline callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_update_regs
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
In drivers/mfd/arizona-irq.c (ffffffff815d3554)
Location: include/asm-generic/gpio.h:83
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8164c3a6)
Location: include/asm-generic/gpio.h:83
Inline: True
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
In drivers/mfd/arizona-irq.c (ffffffff816002a1)
Location: include/asm-generic/gpio.h:83
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8167e0b6)
Location: include/asm-generic/gpio.h:83
Inline: True
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
In drivers/mfd/arizona-irq.c (ffffffff81614144)
Location: include/asm-generic/gpio.h:83
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816931f7)
Location: include/asm-generic/gpio.h:83
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
In drivers/mfd/arizona-irq.c (ffffffff8167c7e4)
Location: include/asm-generic/gpio.h:84
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff816fd107)
Location: include/asm-generic/gpio.h:84
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
In drivers/mfd/arizona-irq.c (ffffffff816b8241)
Location: include/asm-generic/gpio.h:84
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8173b2d6)
Location: include/asm-generic/gpio.h:84
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
In drivers/mfd/arizona-irq.c (ffffffff816d9481)
Location: include/asm-generic/gpio.h:84
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (ffffffff8175ea88)
Location: include/asm-generic/gpio.h:84
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
In drivers/mfd/arizona-irq.c (ffffffff81714a9e)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff81738dae)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff817f672e)
Location: include/asm-generic/gpio.h:82
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff8180945e)
Location: include/asm-generic/gpio.h:82
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff817ee001)
Location: include/asm-generic/gpio.h:82
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/arizona-irq.c (ffff800010933a9c)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (c0a16a84)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (c0000000009d4a00)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffe0005a9902)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff816fcb0e)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff816d091e)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff8172c26e)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
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
In drivers/mfd/arizona-irq.c (ffffffff817476ae)
Location: include/asm-generic/gpio.h:84
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
  - drivers/mfd/arizona-irq.c:arizona_irq_thread
```
</details>
</li>
</ul>

## Differences
