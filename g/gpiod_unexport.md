# Function: <code>gpiod_unexport</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81428030)
Location: drivers/gpio/gpiolib-sysfs.c:676
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:__gpiod_free
```
**Symbols:**

```
ffffffff81428030-ffffffff814280ec: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81473330)
Location: drivers/gpio/gpiolib-sysfs.c:678
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:__gpiod_free
```
**Symbols:**

```
ffffffff81473330-ffffffff814733ec: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81495550)
Location: drivers/gpio/gpiolib-sysfs.c:678
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:__gpiod_free
```
**Symbols:**

```
ffffffff81495550-ffffffff8149560c: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149ef60)
Location: drivers/gpio/gpiolib-sysfs.c:687
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:__gpiod_free
```
**Symbols:**

```
ffffffff8149ef60-ffffffff8149f021: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814ddaa0)
Location: drivers/gpio/gpiolib-sysfs.c:687
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff814ddaa0-ffffffff814ddb61: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:702
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff8150d2e7-ffffffff8150d2ff: gpiod_unexport.cold.4 (STB_LOCAL)
ffffffff8150cc70-ffffffff8150cd19: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81522947-ffffffff8152295f: gpiod_unexport.cold.4 (STB_LOCAL)
ffffffff815226a0-ffffffff81522749: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81550e67-ffffffff81550e7f: gpiod_unexport.cold (STB_LOCAL)
ffffffff81550bd0-ffffffff81550c76: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81572307-ffffffff8157231f: gpiod_unexport.cold (STB_LOCAL)
ffffffff81572070-ffffffff81572116: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81616862-ffffffff8161687a: gpiod_unexport.cold (STB_LOCAL)
ffffffff81616070-ffffffff81616118: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:698
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81bf6874-ffffffff81bf688c: gpiod_unexport.cold (STB_LOCAL)
ffffffff8163ca00-ffffffff8163caa8: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:706
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81be879c-ffffffff81be87b4: gpiod_unexport.cold (STB_LOCAL)
ffffffff81620530-ffffffff816205d8: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:695
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81ce257e-ffffffff81ce2596: gpiod_unexport.cold (STB_LOCAL)
ffffffff8168fae0-ffffffff8168fb88: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:678
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81ea8fbe-ffffffff81ea8fd6: gpiod_unexport.cold (STB_LOCAL)
ffffffff817af2c0-ffffffff817af384: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c8900)
Location: drivers/gpio/gpiolib-sysfs.c:678
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff818c8900-ffffffff818c89ec: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b8b0)
Location: drivers/gpio/gpiolib-sysfs.c:688
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff8190b8b0-ffffffff8190b99c: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff819535d0)
Location: drivers/gpio/gpiolib-sysfs.c:690
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiochip_sysfs_unregister
  - drivers/gpio/gpiolib-sysfs.c:unexport_store
```
**Symbols:**

```
ffffffff819535d0-ffffffff819536bc: gpiod_unexport (STB_GLOBAL)
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
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c9470)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffff8000106c9470-ffff8000106c957c: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c0867080)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
c0867080-c0867148: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c000000000847290)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
c000000000847290-c0000000008473d8: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004acf6c)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffe0004acf6c-ffffffe0004ad052: gpiod_unexport (STB_GLOBAL)
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
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81567ac7-ffffffff81567adf: gpiod_unexport.cold (STB_LOCAL)
ffffffff81567830-ffffffff815678d6: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81558917-ffffffff8155892f: gpiod_unexport.cold (STB_LOCAL)
ffffffff81558680-ffffffff81558726: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81566637-ffffffff8156664f: gpiod_unexport.cold (STB_LOCAL)
ffffffff815663a0-ffffffff81566446: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void gpiod_unexport(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: drivers/gpio/gpiolib-sysfs.c:697
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_free_commit
```
**Symbols:**

```
ffffffff81580557-ffffffff8158056f: gpiod_unexport.cold (STB_LOCAL)
ffffffff815802c0-ffffffff81580366: gpiod_unexport (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
