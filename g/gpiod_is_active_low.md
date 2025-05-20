# Function: <code>gpiod_is_active_low</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81424190)
Location: drivers/gpio/gpiolib.c:1245
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
```
**Symbols:**

```
ffffffff81424190-ffffffff814241a6: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146ee20)
Location: drivers/gpio/gpiolib.c:2209
Inline: True
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8146ee20-ffffffff8146eeaa: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81490df0)
Location: drivers/gpio/gpiolib.c:2399
Inline: True
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81490df0-ffffffff81490e7a: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a8b0)
Location: drivers/gpio/gpiolib.c:2403
Inline: True
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8149a8b0-ffffffff8149a94c: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d8d60)
Location: drivers/gpio/gpiolib.c:2551
Inline: True
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff814d8d60-ffffffff814d8dfc: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506c10)
Location: drivers/gpio/gpiolib.c:2709
Inline: False
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81506c10-ffffffff81506c3b: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151fd7b)
Location: drivers/gpio/gpiolib.c:2789
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8151b150-ffffffff8151b17b: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154dece)
Location: drivers/gpio/gpiolib.c:2877
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff815491b0-ffffffff815491db: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156f0ce)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8156a5a0-ffffffff8156a5cb: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161358e)
Location: drivers/gpio/gpiolib.c:3632
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff816146c6-ffffffff81614723: gpiod_is_active_low.cold (STB_LOCAL)
ffffffff81610660-ffffffff816106ad: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81638480)
Location: drivers/gpio/gpiolib.c:2458
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81bf5f2f-ffffffff81bf5f8c: gpiod_is_active_low.cold (STB_LOCAL)
ffffffff81636a50-ffffffff81636a9d: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161bfc3)
Location: drivers/gpio/gpiolib.c:2435
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81be7dd5-ffffffff81be7e32: gpiod_is_active_low.cold (STB_LOCAL)
ffffffff8161a370-ffffffff8161a3bd: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168b4da)
Location: drivers/gpio/gpiolib.c:2464
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81ce195f-ffffffff81ce19bc: gpiod_is_active_low.cold (STB_LOCAL)
ffffffff81689760-ffffffff816897ad: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a87e8)
Location: drivers/gpio/gpiolib.c:2582
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81ea81d2-ffffffff81ea822f: gpiod_is_active_low.cold (STB_LOCAL)
ffffffff817a6660-ffffffff817a66b8: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c12b3)
Location: drivers/gpio/gpiolib.c:2652
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff818bea60-ffffffff818beb01: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8190424d)
Location: drivers/gpio/gpiolib.c:2693
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81901c00-ffffffff81901c9d: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194bc70)
Location: drivers/gpio/gpiolib.c:2886
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81949740-ffffffff819497dd: gpiod_is_active_low (STB_GLOBAL)
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
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c5054)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffff8000106bdcb8-ffff8000106bdcfc: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08631a8)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
c085d9b8-c085d9ec: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000841c08)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
c00000000083a290-c00000000083a2e4: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a968e)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffe0004a4b6a-ffffffe0004a4ba6: gpiod_is_active_low (STB_GLOBAL)
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
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156488e)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8155fd60-ffffffff8155fd8b: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815556de)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
```
**Symbols:**

```
ffffffff81550bb0-ffffffff81550bdb: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815633fe)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff8155e8d0-ffffffff8155e8fb: gpiod_is_active_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gpiod_is_active_low(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157d31e)
Location: drivers/gpio/gpiolib.c:3224
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
Direct callers:
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_ro
  - drivers/mmc/core/slot-gpio.c:mmc_gpiod_request_cd
```
**Symbols:**

```
ffffffff81578760-ffffffff8157878b: gpiod_is_active_low (STB_GLOBAL)
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
