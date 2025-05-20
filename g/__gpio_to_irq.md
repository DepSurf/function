# Function: <code>__gpio_to_irq</code>

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
In drivers/mfd/arizona-irq.c (ffffffff8157e7c0)
Location: include/asm-generic/gpio.h:107
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff815d3a71)
Location: include/asm-generic/gpio.h:111
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff816007b5)
Location: include/asm-generic/gpio.h:111
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff816146f1)
Location: include/asm-generic/gpio.h:111
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff8167cd97)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff816b870f)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff816d98f2)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff81714fa9)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff817392b9)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int __gpio_to_irq(unsigned int gpio);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/arizona-irq.c (ffffffff817f6b3b)
Location: include/asm-generic/gpio.h:110
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/intel_msic.c (ffffffff8180c433)
Location: include/asm-generic/gpio.h:110
Inline: True
```
**Symbols:**

```
ffffffff817f65c0-ffffffff817f65d3: __gpio_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int __gpio_to_irq(unsigned int gpio);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/arizona-irq.c (ffffffff8180986f)
Location: include/asm-generic/gpio.h:110
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
```
In drivers/mfd/intel_msic.c (ffffffff8181b693)
Location: include/asm-generic/gpio.h:110
Inline: True
```
**Symbols:**

```
ffffffff818092f0-ffffffff81809303: __gpio_to_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __gpio_to_irq(unsigned int gpio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mfd/arizona-irq.c (ffffffff817ee44d)
Location: include/asm-generic/gpio.h:110
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
Direct callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
**Symbols:**

```
ffffffff817ede90-ffffffff817edea3: __gpio_to_irq (STB_LOCAL)
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092fa54)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (ffff8000109340a4)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/stmpe.c (c0a110f0)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (c0a16fa0)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/stmpe.c (c0000000009cf8c4)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (c0000000009d50d0)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/stmpe.c (ffffffe0005a63c2)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/stmpe.c:stmpe_probe
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a9dc2)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff816fd019)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff816d0e29)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff8172c779)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
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
In drivers/mfd/arizona-irq.c (ffffffff81747bb9)
Location: include/asm-generic/gpio.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
