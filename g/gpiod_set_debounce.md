# Function: <code>gpiod_set_debounce</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814245f0)
Location: drivers/gpio/gpiolib.c:1218
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffff814245f0-ffffffff814246ac: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146def0)
Location: drivers/gpio/gpiolib.c:2186
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
```
**Symbols:**

```
ffffffff8146def0-ffffffff8146dffc: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148fdc0)
Location: drivers/gpio/gpiolib.c:2376
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
```
**Symbols:**

```
ffffffff8148fdc0-ffffffff8148fecc: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a790)
Location: drivers/gpio/gpiolib.c:2378
Inline: True
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
```
**Symbols:**

```
ffffffff8149a790-ffffffff8149a8ac: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d8c40)
Location: drivers/gpio/gpiolib.c:2526
Inline: True
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
```
**Symbols:**

```
ffffffff814d8c40-ffffffff814d8d5f: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506c80)
Location: drivers/gpio/gpiolib.c:2640
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_request_cd
```
**Symbols:**

```
ffffffff81506c80-ffffffff81506d30: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151b220)
Location: drivers/gpio/gpiolib.c:2720
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8151b220-ffffffff8151b2d0: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815493d0)
Location: drivers/gpio/gpiolib.c:2808
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff815493d0-ffffffff81549480: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a6a0)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8156a6a0-ffffffff8156a750: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81610ad0)
Location: drivers/gpio/gpiolib.c:3576
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81610ad0-ffffffff81610ae6: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81636ed0)
Location: drivers/gpio/gpiolib.c:2419
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81636ed0-ffffffff81636ee6: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161a7f0)
Location: drivers/gpio/gpiolib.c:2396
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8161a7f0-ffffffff8161a806: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81689c10)
Location: drivers/gpio/gpiolib.c:2425
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81689c10-ffffffff81689c26: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a6c50)
Location: drivers/gpio/gpiolib.c:2543
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff817a6c50-ffffffff817a6c6e: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818befb0)
Location: drivers/gpio/gpiolib.c:2613
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff818befb0-ffffffff818befce: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81902010)
Location: drivers/gpio/gpiolib.c:2654
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81902010-ffffffff8190202e: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949c30)
Location: drivers/gpio/gpiolib.c:2848
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81949c30-ffffffff81949c4e: gpiod_set_debounce (STB_GLOBAL)
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
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bddc8)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffff8000106bddc8-ffff8000106bde98: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085da8c)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
c085da8c-c085db60: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a460)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
c00000000083a460-c00000000083a568: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4c90)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffe0004a4c90-ffffffe0004a4d4c: gpiod_set_debounce (STB_GLOBAL)
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
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155fe60)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8155fe60-ffffffff8155ff10: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550cb0)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
```
**Symbols:**

```
ffffffff81550cb0-ffffffff81550d60: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e9d0)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8155e9d0-ffffffff8155ea80: gpiod_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_set_debounce(struct gpio_desc *desc, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578860)
Location: drivers/gpio/gpiolib.c:3155
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81578860-ffffffff81578910: gpiod_set_debounce (STB_GLOBAL)
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
