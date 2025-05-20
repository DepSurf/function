# Function: <code>irq_set_parent</code>

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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:457
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:457
Inline: True
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:479
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:479
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:479
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:496
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:496
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:496
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:546
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:546
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:546
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:573
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:573
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:573
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:575
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:575
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:575
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:576
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:576
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:576
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:583
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:583
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:583
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:601
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81122750)
Location: kernel/irq/manage.c:901
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff81122750-ffffffff811227b8: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111e580)
Location: kernel/irq/manage.c:971
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff8111e580-ffffffff8111e5e8: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111e890)
Location: kernel/irq/manage.c:971
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff8111e890-ffffffff8111e8f8: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113ed20)
Location: kernel/irq/manage.c:995
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff8113ed20-ffffffff8113ed88: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81162340)
Location: kernel/irq/manage.c:1010
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff81162340-ffffffff811623bc: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81195e90)
Location: kernel/irq/manage.c:1002
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff81195e90-ffffffff81195f0c: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a7850)
Location: kernel/irq/manage.c:1008
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff811a7850-ffffffff811a78cc: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b73b0)
Location: kernel/irq/manage.c:1010
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
```
**Symbols:**

```
ffffffff811b73b0-ffffffff811b742c: irq_set_parent (STB_GLOBAL)
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
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010178c28)
Location: kernel/irq/manage.c:818
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
**Symbols:**

```
ffff800010178c28-ffff800010178cb0: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca510)
Location: kernel/irq/manage.c:818
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/tps65217.c:tps65217_irq_map
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
**Symbols:**

```
c03ca510-c03ca598: irq_set_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_parent(int irq, int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d2e10)
Location: kernel/irq/manage.c:818
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/base/regmap/regmap-irq.c:regmap_irq_map
  - drivers/mfd/twl6030-irq.c:twl6030_irq_map
```
**Symbols:**

```
c0000000001d2e10-c0000000001d2eb0: irq_set_parent (STB_GLOBAL)
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:601
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:601
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:601
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:601
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
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/linux/irq.h:601
Inline: True
```
```
In drivers/mfd/twl6030-irq.c (0)
Location: include/linux/irq.h:601
Inline: True
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
</ul>
