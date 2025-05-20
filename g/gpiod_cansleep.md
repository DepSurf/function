# Function: <code>gpiod_cansleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814241b0)
Location: drivers/gpio/gpiolib.c:1582
Inline: False
```
**Symbols:**

```
ffffffff814241b0-ffffffff814241ce: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146eeb0)
Location: drivers/gpio/gpiolib.c:2539
Inline: True
```
**Symbols:**

```
ffffffff8146eeb0-ffffffff8146ef38: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81490e80)
Location: drivers/gpio/gpiolib.c:2729
Inline: True
```
**Symbols:**

```
ffffffff81490e80-ffffffff81490f08: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a950)
Location: drivers/gpio/gpiolib.c:2726
Inline: True
```
**Symbols:**

```
ffffffff8149a950-ffffffff8149a9ea: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d8e00)
Location: drivers/gpio/gpiolib.c:2997
Inline: True
```
**Symbols:**

```
ffffffff814d8e00-ffffffff814d8e9a: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506c40)
Location: drivers/gpio/gpiolib.c:3189
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81506c40-ffffffff81506c71: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151b180)
Location: drivers/gpio/gpiolib.c:3361
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8151b180-ffffffff8151b1b1: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815491e0)
Location: drivers/gpio/gpiolib.c:3450
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff815491e0-ffffffff81549211: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a600)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8156a600-ffffffff8156a631: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4210
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81614723-ffffffff8161478b: gpiod_cansleep.cold (STB_LOCAL)
ffffffff816106b0-ffffffff816106fb: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3034
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81bf6040-ffffffff81bf60a8: gpiod_cansleep.cold (STB_LOCAL)
ffffffff81636b50-ffffffff81636b9b: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3011
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81be7ee6-ffffffff81be7f4e: gpiod_cansleep.cold (STB_LOCAL)
ffffffff8161a470-ffffffff8161a4bb: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3060
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81ce1b78-ffffffff81ce1bfb: gpiod_cansleep.cold (STB_LOCAL)
ffffffff81689970-ffffffff816899ca: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3181
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81ea83e5-ffffffff81ea8468: gpiod_cansleep.cold (STB_LOCAL)
ffffffff817a68c0-ffffffff817a6925: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3251
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8208e57f-ffffffff8208e59a: gpiod_cansleep.cold (STB_LOCAL)
ffffffff818be990-ffffffff818bea4c: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3292
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8210e881-ffffffff8210e89c: gpiod_cansleep.cold (STB_LOCAL)
ffffffff81901b40-ffffffff81901bea: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3485
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:gpio_clk_driver_probe
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_ro
```
**Symbols:**

```
ffffffff821ec4d4-ffffffff821ec4ef: gpiod_cansleep.cold (STB_LOCAL)
ffffffff81949680-ffffffff8194972a: gpiod_cansleep (STB_GLOBAL)
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
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bdd00)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffff8000106bdd00-ffff8000106bdd4c: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d9ec)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
c085d9ec-c085da24: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a360)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
c00000000083a360-c00000000083a3b8: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4be8)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffe0004a4be8-ffffffe0004a4c28: gpiod_cansleep (STB_GLOBAL)
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
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155fdc0)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8155fdc0-ffffffff8155fdf1: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550c10)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
```
**Symbols:**

```
ffffffff81550c10-ffffffff81550c41: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e930)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8155e930-ffffffff8155e961: gpiod_cansleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_cansleep(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815787c0)
Location: drivers/gpio/gpiolib.c:3804
Inline: False
Direct callers:
  - drivers/clk/clk-gpio.c:clk_hw_register_gpio_gate
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff815787c0-ffffffff815787f1: gpiod_cansleep (STB_GLOBAL)
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
