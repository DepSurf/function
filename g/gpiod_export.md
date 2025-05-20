# Function: <code>gpiod_export</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81428170)
Location: drivers/gpio/gpiolib-sysfs.c:547
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81428170-ffffffff81428443: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81473470)
Location: drivers/gpio/gpiolib-sysfs.c:547
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81473470-ffffffff81473748: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81495690)
Location: drivers/gpio/gpiolib-sysfs.c:547
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81495690-ffffffff81495968: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8149f0b0)
Location: drivers/gpio/gpiolib-sysfs.c:556
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8149f0b0-ffffffff8149f376: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff814ddbf0)
Location: drivers/gpio/gpiolib-sysfs.c:556
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff814ddbf0-ffffffff814ddeb6: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8150cd90)
Location: drivers/gpio/gpiolib-sysfs.c:571
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8150cd90-ffffffff8150d070: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815222c0)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff815222c0-ffffffff815225a0: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff815507d0)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff815507d0-ffffffff81550ac2: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81571c80)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81571c80-ffffffff81571f6a: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81616300)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81616300-ffffffff816165eb: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8163cc90)
Location: drivers/gpio/gpiolib-sysfs.c:567
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8163cc90-ffffffff8163cf81: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff816207c0)
Location: drivers/gpio/gpiolib-sysfs.c:575
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff816207c0-ffffffff81620ab1: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8168fd90)
Location: drivers/gpio/gpiolib-sysfs.c:564
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8168fd90-ffffffff81690075: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff817aee30)
Location: drivers/gpio/gpiolib-sysfs.c:547
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff817aee30-ffffffff817af112: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff818c8400)
Location: drivers/gpio/gpiolib-sysfs.c:547
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff818c8400-ffffffff818c86e2: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8190b3b0)
Location: drivers/gpio/gpiolib-sysfs.c:557
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8190b3b0-ffffffff8190b6a0: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff819530b0)
Location: drivers/gpio/gpiolib-sysfs.c:560
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff819530b0-ffffffff819533b8: gpiod_export (STB_GLOBAL)
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
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffff8000106c97f0)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffff8000106c97f0-ffff8000106c9b78: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c0866b64)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3517_legacy_init
  - arch/arm/mach-omap2/pdata-quirks.c:omap3_sbc_t3x_usb_hub_init
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - sound/soc/soc-jack.c:snd_soc_jack_add_gpios
```
**Symbols:**

```
c0866b64-c0866e7c: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (c0000000008474c0)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
c0000000008474c0-c0000000008478b8: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffe0004acad8)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffe0004acad8-ffffffe0004acdb2: gpiod_export (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81567440)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81567440-ffffffff8156772a: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81558290)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81558290-ffffffff8155857a: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81565fb0)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81565fb0-ffffffff8156629a: gpiod_export (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_export(struct gpio_desc *desc, bool direction_may_change);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-sysfs.c (ffffffff8157fed0)
Location: drivers/gpio/gpiolib-sysfs.c:566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8157fed0-ffffffff815801ba: gpiod_export (STB_GLOBAL)
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
