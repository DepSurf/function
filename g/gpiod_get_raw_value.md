# Function: <code>gpiod_get_raw_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81425c20)
Location: drivers/gpio/gpiolib.c:1303
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
```
**Symbols:**

```
ffffffff81425c20-ffffffff81425c5f: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146f6f0)
Location: drivers/gpio/gpiolib.c:2262
Inline: True
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
```
**Symbols:**

```
ffffffff8146f6f0-ffffffff8146f795: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491a60)
Location: drivers/gpio/gpiolib.c:2452
Inline: True
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core.c:get_sda_gpio_value
  - drivers/i2c/i2c-core.c:get_scl_gpio_value
```
**Symbols:**

```
ffffffff81491a60-ffffffff81491b05: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149b270)
Location: drivers/gpio/gpiolib.c:2456
Inline: True
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
```
**Symbols:**

```
ffffffff8149b270-ffffffff8149b318: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814da110)
Location: drivers/gpio/gpiolib.c:2669
Inline: True
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:get_sda_gpio_value
  - drivers/i2c/i2c-core-base.c:get_scl_gpio_value
```
**Symbols:**

```
ffffffff814da110-ffffffff814da1b8: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508fc0)
Location: drivers/gpio/gpiolib.c:2845
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81508fc0-ffffffff81508fff: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d660)
Location: drivers/gpio/gpiolib.c:2964
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8151d660-ffffffff8151d69f: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3052
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8154f07b-ffffffff8154f08e: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff8154b9b0-ffffffff8154b9f2: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156c940)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8156c940-ffffffff8156c982: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3818
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff81614a62-ffffffff81614acd: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff81610a00-ffffffff81610a5a: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2643
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff81bf62cb-ffffffff81bf6336: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff81636df0-ffffffff81636e4a: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2620
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff81be8171-ffffffff81be81dc: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff8161a710-ffffffff8161a76a: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2660
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff81ce1d2a-ffffffff81ce1da9: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff81689b20-ffffffff81689b86: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2781
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff81ea8522-ffffffff81ea859f: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff817a6a30-ffffffff817a6aa4: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2851
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff8208e59a-ffffffff8208e5af: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff818bec00-ffffffff818beccf: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2892
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff8210e8b1-ffffffff8210e8c6: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff81901e60-ffffffff81901f1d: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3085
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff821ec504-ffffffff821ec519: gpiod_get_raw_value.cold (STB_LOCAL)
ffffffff819499a0-ffffffff81949a5d: gpiod_get_raw_value (STB_GLOBAL)
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
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bfc98)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffff8000106bfc98-ffff8000106bfcf8: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c08604cc)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_start_tx
  - drivers/tty/serial/omap-serial.c:serial_omap_stop_tx
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
c08604cc-c0860534: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083dd70)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
c00000000083dd70-c00000000083dde4: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a71de)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffe0004a71de-ffffffe0004a722e: gpiod_get_raw_value (STB_GLOBAL)
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
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562100)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81562100-ffffffff81562142: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81552f50)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
```
**Symbols:**

```
ffffffff81552f50-ffffffff81552f92: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560c70)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff81560c70-ffffffff81560cb2: gpiod_get_raw_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_get_raw_value(const struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157ab30)
Location: drivers/gpio/gpiolib.c:3410
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/mmc/core/slot-gpio.c:mmc_gpio_get_cd
```
**Symbols:**

```
ffffffff8157ab30-ffffffff8157ab72: gpiod_get_raw_value (STB_GLOBAL)
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
