# Function: <code>pinconf_to_config_packed</code>

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
In drivers/pinctrl/pinconf-generic.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
```
```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:152
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81469e69)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146ab2a)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146ba16)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81489149)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489e3a)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8148aef5)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148bde3)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148db17)
Location: include/linux/pinctrl/pinconf-generic.h:152
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81492a1c)
Location: include/linux/pinctrl/pinconf-generic.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8149392a)
Location: include/linux/pinctrl/pinconf-generic.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81494787)
Location: include/linux/pinctrl/pinconf-generic.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81495719)
Location: include/linux/pinctrl/pinconf-generic.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814974e2)
Location: include/linux/pinctrl/pinconf-generic.h:144
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8149a7e4)
Location: include/linux/pinctrl/pinconf-generic.h:144
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
In drivers/pinctrl/pinconf-generic.c (ffffffff814cecac)
Location: include/linux/pinctrl/pinconf-generic.h:151
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cfbba)
Location: include/linux/pinctrl/pinconf-generic.h:151
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff814d0a37)
Location: include/linux/pinctrl/pinconf-generic.h:151
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d1a1e)
Location: include/linux/pinctrl/pinconf-generic.h:151
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d3808)
Location: include/linux/pinctrl/pinconf-generic.h:151
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5b47)
Location: include/linux/pinctrl/pinconf-generic.h:151
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff814d8c94)
Location: include/linux/pinctrl/pinconf-generic.h:151
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
In drivers/pinctrl/pinconf-generic.c (ffffffff814ffc94)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81500daa)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81501927)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81502a9e)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815048a6)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff815071d1)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81514704)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8151587a)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815163f7)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815175ae)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815193c0)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8151b751)
Location: include/linux/pinctrl/pinconf-generic.h:153
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff815428da)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81543a16)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815445c4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81545777)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81547592)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81549911)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8156376a)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81564926)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815654a4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff815666a4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff815684b2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8156aab1)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81605e2a)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81606d96)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81607fb2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81609d8b)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160a7d2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8160fb31)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8162a5fa)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162b666)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8162c7a2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162e49b)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162eea9)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632f0d)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81636ed5)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8160e2da)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160f332)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81610476)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81611ffe)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81612b49)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81616c0d)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8161a7f5)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8167d0a4)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e262)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8167f550)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff816811fe)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81681c7c)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81685e7d)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81689c15)
Location: include/linux/pinctrl/pinconf-generic.h:163
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81798a2f)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799e66)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8179b227)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179d352)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179dd0f)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a27f8)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff817a544e)
Location: include/linux/pinctrl/pinconf-generic.h:166
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
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
In drivers/pinctrl/pinconf-generic.c (ffffffff818ae92f)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818afffc)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818b1a57)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b3ef2)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b498f)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b9a83)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff818bd6be)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
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
In drivers/pinctrl/pinconf-generic.c (ffffffff818f187f)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2fcc)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff818f49f5)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f6f7c)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f7a24)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fca8e)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff819007ee)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8193902f)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193a7fc)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff8193c205)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193e74b)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193ff94)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff8194388a)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8194a04e)
Location: include/linux/pinctrl/pinconf-generic.h:171
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
  - drivers/gpio/gpiolib.c:gpio_set_debounce_timeout
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
In drivers/pinctrl/pinconf-generic.c (ffff8000106914dc)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:parse_dt_cfg
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-as3722.c (ffff800010692108)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010693d28)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-bm1880.c (ffff800010694ff8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinconf_cfg_get
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (ffff8000106955ec)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffff800010696fd4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069a088)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinconf_get
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069d7bc)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
  - drivers/pinctrl/pinctrl-single.c:pcs_parse_one_pinctrl_entry
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffff80001069ed74)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a0dd8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a302c)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pctl_dt_node_to_map
```
```
In drivers/pinctrl/bcm/pinctrl-iproc-gpio.c (ffff8000106a5a20)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_pin_config_get
```
```
In drivers/pinctrl/bcm/pinctrl-ns2-mux.c (ffff8000106a7470)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
  - drivers/pinctrl/bcm/pinctrl-ns2-mux.c:ns2_pin_config_get
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106aec54)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (ffff8000106b170c)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_get
```
```
In drivers/pinctrl/sprd/pinctrl-sprd.c (ffff8000106b37b0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinconf_get
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (ffff8000106b5ecc)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pconf_get
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pctrl_dt_node_to_map
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba168)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc3e4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinconf_get
```
```
In drivers/gpio/gpiolib.c (ffff8000106c1010)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (c083308c)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:parse_dt_cfg
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-as3722.c (c0833bf4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get
```
```
In drivers/pinctrl/pinctrl-amd.c (c08352f4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/meson/pinctrl-meson.c (c0835bcc)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinconf_get
```
```
In drivers/pinctrl/pinctrl-palmas.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
```
```
In drivers/pinctrl/pinctrl-rockchip.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
```
```
In drivers/pinctrl/pinctrl-rzn1.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
```
```
In drivers/pinctrl/pinctrl-single.c (c083fd4c)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-sx150x.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c08460dc)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_group_config_get
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pin_config_get
```
```
In drivers/pinctrl/aspeed/pinctrl-aspeed.c (c08471e4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/aspeed/pinctrl-aspeed.c:aspeed_pin_config_get
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084cfa8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084e2c4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_config_group_get
```
```
In drivers/pinctrl/sh-pfc/pinctrl.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c08578ec)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085ade8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
```
```
In drivers/gpio/gpiolib.c (c085e18c)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
```
In drivers/soc/tegra/pmc.c (c093b8f8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_io_pad_pinconf_get
```
```
In drivers/rtc/rtc-omap.c (0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
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
In drivers/pinctrl/pinconf-generic.c (c00000000082d59c)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:parse_dt_cfg
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-as3722.c (c00000000082e634)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get
```
```
In drivers/pinctrl/pinctrl-amd.c (c000000000830d30)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-palmas.c (c000000000831df8)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000834b88)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_get
  - drivers/pinctrl/pinctrl-single.c:pcs_pinconf_clear_bias
```
```
In drivers/pinctrl/pinctrl-sx150x.c (c000000000836f14)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/gpio/gpiolib.c (c00000000083b0e4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffe00049ccde)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:parse_dt_cfg
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-as3722.c (ffffffe00049d6b2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinconf_get
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049eb8c)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-palmas.c (ffffffe00049f8d4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinconf_get
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a1be2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
  - drivers/pinctrl/pinctrl-single.c:pcs_dt_node_to_map
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffe0004a2a74)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a52c0)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8155bd5a)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155cf16)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155db74)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81560271)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8154c21a)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154ccb4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154eac2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff815510c1)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff81557a9a)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81558c56)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff815597d4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155a9d4)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155c7e2)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff8155ede1)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
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
In drivers/pinctrl/pinconf-generic.c (ffffffff8157192a)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:pinconf_generic_dump_one
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572ae6)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_pinconf_get
```
```
In drivers/pinctrl/pinctrl-sx150x.c (ffffffff81573664)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_pinconf_get
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81574864)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pin_config_get
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81576672)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_get
```
```
In drivers/gpio/gpiolib.c (ffffffff81578c71)
Location: include/linux/pinctrl/pinconf-generic.h:161
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_set_transitory
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
</details>
</li>
</ul>

## Differences
