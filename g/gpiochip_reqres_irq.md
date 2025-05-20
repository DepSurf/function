# Function: <code>gpiochip_reqres_irq</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151c6d0)
Location: drivers/gpio/gpiolib.c:3532
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff8151c6d0-ffffffff8151c752: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3621
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff8154ee6f-ffffffff8154eea4: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff8154a9a0-ffffffff8154a9ed: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff815703e2-ffffffff81570417: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff8156b390-ffffffff8156b3dd: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160f7e8)
Location: drivers/gpio/gpiolib.c:4388
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81614554-ffffffff81614589: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff8160f780-ffffffff8160f7cd: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816353a8)
Location: drivers/gpio/gpiolib.c:3212
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81bf5c6a-ffffffff81bf5c9f: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff81635340-ffffffff8163538d: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81619748)
Location: drivers/gpio/gpiolib.c:3189
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81be7b58-ffffffff81be7b8d: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff81618de0-ffffffff81618e2d: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81688a48)
Location: drivers/gpio/gpiolib.c:3248
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81ce1677-ffffffff81ce16ac: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff81688340-ffffffff8168838d: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a5328)
Location: drivers/gpio/gpiolib.c:3369
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81ea7ca9-ffffffff81ea7cde: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff817a4090-ffffffff817a40e9: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bba80)
Location: drivers/gpio/gpiolib.c:3439
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff818bba80-ffffffff818bbb16: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818feca0)
Location: drivers/gpio/gpiolib.c:3480
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff818feca0-ffffffff818fed36: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81946360)
Location: drivers/gpio/gpiolib.c:3673
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81946360-ffffffff819463f6: gpiochip_reqres_irq (STB_GLOBAL)
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
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c1fc0)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffff8000106c1fc0-ffff8000106c204c: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085eab0)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
c085eab0-c085eb30: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083bb70)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
c00000000083bb70-c00000000083bc2c: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a5bba)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffe0004a5bba-ffffffe0004a5c32: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81565ba2-ffffffff81565bd7: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff81560b50-ffffffff81560b9d: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff815569f2-ffffffff81556a27: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff815519a0-ffffffff815519ed: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff81564712-ffffffff81564747: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff8155f6c0-ffffffff8155f70d: gpiochip_reqres_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiochip_reqres_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3975
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
```
**Symbols:**

```
ffffffff8157e632-ffffffff8157e667: gpiochip_reqres_irq.cold (STB_LOCAL)
ffffffff81579540-ffffffff8157958d: gpiochip_reqres_irq (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
