# Function: <code>gpio_chip_get_multiple</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dbe04)
Location: drivers/gpio/gpiolib.c:2594
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
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
In drivers/gpio/gpiolib.c (ffffffff8150a0cc)
Location: drivers/gpio/gpiolib.c:2752
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151ce80)
Location: drivers/gpio/gpiolib.c:2832
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff8151ce80-ffffffff8151cf32: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154afb0)
Location: drivers/gpio/gpiolib.c:2920
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff8154afb0-ffffffff8154b062: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c190)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff8156c190-ffffffff8156c242: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160dbe0)
Location: drivers/gpio/gpiolib.c:3686
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff8160dbe0-ffffffff8160dc92: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81634460)
Location: drivers/gpio/gpiolib.c:2512
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff81634460-ffffffff81634512: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81617e70)
Location: drivers/gpio/gpiolib.c:2489
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff81617e70-ffffffff81617f2a: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816870f0)
Location: drivers/gpio/gpiolib.c:2518
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff816870f0-ffffffff816871aa: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a5240)
Location: drivers/gpio/gpiolib.c:2639
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff817a5240-ffffffff817a5310: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bf618)
Location: drivers/gpio/gpiolib.c:2709
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff818bbf20-ffffffff818bbf9a: gpio_chip_get_multiple.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fee10)
Location: drivers/gpio/gpiolib.c:2750
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff818fee10-ffffffff818feebc: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *gc, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81946710)
Location: drivers/gpio/gpiolib.c:2943
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff81946710-ffffffff819467bc: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bf3e0)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffff8000106bf3e0-ffff8000106bf4f8: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085fb7c)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
c085fb7c-c085fc5c: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083cfb0)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
c00000000083cfb0-c00000000083d14c: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a697c)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffe0004a697c-ffffffe0004a6a64: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81561950)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff81561950-ffffffff81561a02: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815527a0)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff815527a0-ffffffff81552852: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815604c0)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff815604c0-ffffffff81560572: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gpio_chip_get_multiple(struct gpio_chip *chip, long unsigned int *mask, long unsigned int *bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157a330)
Location: drivers/gpio/gpiolib.c:3278
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
  - drivers/gpio/gpiolib.c:gpiod_get_array_value_complex
```
**Symbols:**

```
ffffffff8157a330-ffffffff8157a3e2: gpio_chip_get_multiple (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *chip</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
