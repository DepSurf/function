# Function: <code>pm_runtime_get</code>

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
In drivers/phy/phy-core.c (ffffffff8141bd14)
Location: include/linux/pm_runtime.h:221
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814238e9)
Location: include/linux/pm_runtime.h:221
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429bfa)
Location: include/linux/pm_runtime.h:221
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_mid_irq_type
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_input
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_direction_output
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8142a901)
Location: include/linux/pm_runtime.h:221
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff81613fd6)
Location: include/linux/pm_runtime.h:221
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff81464374)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146cc92)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81475518)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/usb/core/driver.c (ffffffff816740d6)
Location: include/linux/pm_runtime.h:227
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff81483674)
Location: include/linux/pm_runtime.h:230
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148caa2)
Location: include/linux/pm_runtime.h:230
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81497ae8)
Location: include/linux/pm_runtime.h:230
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/usb/core/driver.c (ffffffff816a1d66)
Location: include/linux/pm_runtime.h:230
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff8148d8ff)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814963f2)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a1798)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/usb/core/driver.c (ffffffff816b75c6)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff814c9a5f)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d2727)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814e0168)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/usb/core/driver.c (ffffffff81722e86)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff814f9d70)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81503750)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150f506)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/usb/core/driver.c (ffffffff81761025)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff8150e940)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815181a0)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524bb6)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81527e7d)
Location: include/linux/pm_runtime.h:218
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff817855e5)
Location: include/linux/pm_runtime.h:218
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff8153df2b)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815464e2)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81553296)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pwm/pwm-lpss.c (ffffffff815570d8)
Location: include/linux/pm_runtime.h:219
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff817c4365)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff8155ed4b)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815678d7)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81574936)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81578718)
Location: include/linux/pm_runtime.h:219
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff817f4d05)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff815ffeab)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81609472)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8161d647)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/usb/core/driver.c (ffffffff818c41a5)
Location: include/linux/pm_runtime.h:229
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81624d9b)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162db82)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81643e8b)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/usb/core/driver.c (ffffffff818d0095)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8160874b)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81611802)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81626c42)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/usb/core/driver.c (ffffffff818b36c5)
Location: include/linux/pm_runtime.h:368
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8167738b)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81680ab2)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/pwm/pwm-lpss.c (ffffffff816964d5)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/usb/core/driver.c (ffffffff81948b55)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8179240b)
Location: include/linux/pm_runtime.h:404
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179cbc2)
Location: include/linux/pm_runtime.h:404
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b7364)
Location: include/linux/pm_runtime.h:404
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_probe
```
```
In drivers/usb/core/driver.c (ffffffff81aa1695)
Location: include/linux/pm_runtime.h:404
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a6e2b)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b3721)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1a25)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
```
In drivers/usb/core/driver.c (ffffffff81c26f25)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818e9c9b)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f6781)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914a15)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffff81abf37c)
Location: include/linux/pm_runtime.h:408
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff81c8dee5)
Location: include/linux/pm_runtime.h:408
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8193113b)
Location: include/linux/pm_runtime.h:406
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195c983)
Location: include/linux/pm_runtime.h:406
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:devm_pwm_lpss_probe
```
```
In drivers/tty/serial/serial_core.c (ffffffff81b121ac)
Location: include/linux/pm_runtime.h:406
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:__uart_start
```
```
In drivers/usb/core/driver.c (ffffffff81d42a05)
Location: include/linux/pm_runtime.h:406
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffff800010687998)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/usb/core/driver.c (ffff800010a258f0)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082b568)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/clk/samsung/clk-exynos5-subcmu.c (c1585348)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe
```
```
In drivers/usb/core/driver.c (c0afbedc)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
```
In drivers/usb/musb/musb_gadget.c (c0b6f74c)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/musb/musb_gadget.c:musb_gadget_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c000000000820cfc)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/usb/core/driver.c (c000000000ae0150)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffe000495fcc)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/usb/core/driver.c (ffffffe0006473fa)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff8155733b)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155eda7)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/usb/core/driver.c (ffffffff817ad0e5)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff815477fb)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154dee7)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155af46)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/usb/core/driver.c (ffffffff8179eae5)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff8155307b)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155bc07)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568c66)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8156c468)
Location: include/linux/pm_runtime.h:219
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff817e9b85)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
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
In drivers/phy/phy-core.c (ffffffff8156cf0b)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:phy_pm_runtime_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81575c27)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_request_enable
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582b86)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_request
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81586968)
Location: include/linux/pm_runtime.h:219
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffff818040b5)
Location: include/linux/pm_runtime.h:219
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_async
```
</details>
</li>
</ul>

## Differences
