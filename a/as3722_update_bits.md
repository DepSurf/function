# Function: <code>as3722_update_bits</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/pinctrl/pinctrl-as3722.c (ffff800010691e94)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
```
```
In drivers/mfd/as3722.c (ffff80001094f678)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/power/reset/as3722-poweroff.c (ffff800010ac9440)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
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
In drivers/pinctrl/pinctrl-as3722.c (c08339a0)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
```
```
In drivers/mfd/as3722.c (c0a396f0)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/power/reset/as3722-poweroff.c (c0baa030)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
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
In drivers/pinctrl/pinctrl-as3722.c (c00000000082e290)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
```
```
In drivers/mfd/as3722.c (c0000000009fc0d4)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/power/reset/as3722-poweroff.c (c000000000bab1d8)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
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
In drivers/pinctrl/pinctrl-as3722.c (ffffffe00049d48a)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_gpio_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_gpio_set_direction
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_set
```
```
In drivers/mfd/as3722.c (ffffffe0005bfeb6)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/mfd/as3722.c:as3722_i2c_probe
  - drivers/mfd/as3722.c:as3722_i2c_probe
```
```
In drivers/power/reset/as3722-poweroff.c (ffffffe0006c7594)
Location: include/linux/mfd/as3722.h:408
Inline: True
Inline callers:
  - drivers/power/reset/as3722-poweroff.c:as3722_pm_power_off
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
