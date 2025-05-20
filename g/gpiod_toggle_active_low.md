# Function: <code>gpiod_toggle_active_low</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a5d0)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffff8156a5d0-ffffffff8156a5f5: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3643
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff816148f3-ffffffff81614947: gpiod_toggle_active_low.cold (STB_LOCAL)
ffffffff81610870-ffffffff816108b5: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2469
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81bf615c-ffffffff81bf61b0: gpiod_toggle_active_low.cold (STB_LOCAL)
ffffffff81636c60-ffffffff81636ca5: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2446
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81be8002-ffffffff81be8056: gpiod_toggle_active_low.cold (STB_LOCAL)
ffffffff8161a580-ffffffff8161a5c5: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2475
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81ce1b24-ffffffff81ce1b78: gpiod_toggle_active_low.cold (STB_LOCAL)
ffffffff81689920-ffffffff81689965: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2593
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81ea8391-ffffffff81ea83e5: gpiod_toggle_active_low.cold (STB_LOCAL)
ffffffff817a6860-ffffffff817a68bd: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818be8e0)
Location: drivers/gpio/gpiolib.c:2663
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff818be8e0-ffffffff818be974: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901a80)
Location: drivers/gpio/gpiolib.c:2704
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81901a80-ffffffff81901b2f: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819495c0)
Location: drivers/gpio/gpiolib.c:2897
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff819495c0-ffffffff8194966f: gpiod_toggle_active_low (STB_GLOBAL)
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
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bf968)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffff8000106bf968-ffff8000106bf9d0: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085f034)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
c085f034-c085f070: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a2f0)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
c00000000083a2f0-c00000000083a354: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4ba6)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffe0004a4ba6-ffffffe0004a4be8: gpiod_toggle_active_low (STB_GLOBAL)
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
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155fd90)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffff8155fd90-ffffffff8155fdb5: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550be0)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
```
**Symbols:**

```
ffffffff81550be0-ffffffff81550c05: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e900)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffff8155e900-ffffffff8155e925: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiod_toggle_active_low(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578790)
Location: drivers/gpio/gpiolib.c:3235
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffff81578790-ffffffff815787b5: gpiod_toggle_active_low (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
