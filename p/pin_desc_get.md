# Function: <code>pin_desc_get</code>

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
In drivers/pinctrl/core.c (ffffffff8141daf2)
Location: drivers/pinctrl/core.h:179
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff8141f7fa)
Location: drivers/pinctrl/core.h:179
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
```
```
In drivers/pinctrl/pinconf.c (ffffffff814210bc)
Location: drivers/pinctrl/core.h:179
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
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
In drivers/pinctrl/core.c (ffffffff81467137)
Location: drivers/pinctrl/core.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff8146846a)
Location: drivers/pinctrl/core.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
```
```
In drivers/pinctrl/pinconf.c (ffffffff814693fa)
Location: drivers/pinctrl/core.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
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
In drivers/pinctrl/core.c (ffffffff81486427)
Location: drivers/pinctrl/core.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81487747)
Location: drivers/pinctrl/core.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
```
```
In drivers/pinctrl/pinconf.c (ffffffff814886d7)
Location: drivers/pinctrl/core.h:181
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
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
In drivers/pinctrl/core.c (ffffffff8148ebaf)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81491025)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
```
```
In drivers/pinctrl/pinconf.c (ffffffff81492377)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81493d2e)
Location: drivers/pinctrl/core.h:236
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
In drivers/pinctrl/core.c (ffffffff814cad0f)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff814cd230)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
```
```
In drivers/pinctrl/pinconf.c (ffffffff814ce5f7)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cffce)
Location: drivers/pinctrl/core.h:236
Inline: True
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d6720)
Location: drivers/pinctrl/core.h:236
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
In drivers/pinctrl/core.c (ffffffff814fbcaf)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff814fe226)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
```
```
In drivers/pinctrl/pinconf.c (ffffffff814ff618)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814fff35)
Location: drivers/pinctrl/core.h:236
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
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
In drivers/pinctrl/core.c (ffffffff8151077f)
Location: drivers/pinctrl/core.h:230
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81512c96)
Location: drivers/pinctrl/core.h:230
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
```
```
In drivers/pinctrl/pinconf.c (ffffffff81514088)
Location: drivers/pinctrl/core.h:230
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815149a5)
Location: drivers/pinctrl/core.h:230
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
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
In drivers/pinctrl/core.c (ffffffff8153ee1f)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff815412f2)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
```
```
In drivers/pinctrl/pinconf.c (ffffffff81542233)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81542b75)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
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
In drivers/pinctrl/core.c (ffffffff8155fcbf)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81562132)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff815630c3)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81563a05)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
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
In drivers/pinctrl/core.c (ffffffff81602eec)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_register_one_pin
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81604712)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff816056b3)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81607127)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
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
In drivers/pinctrl/core.c (ffffffff81627dfc)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_register_one_pin
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81629282)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff81629fa3)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162a837)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632639)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
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
In drivers/pinctrl/core.c (ffffffff8160b8dc)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff8160ce02)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff8160dc83)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160e517)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81616219)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
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
In drivers/pinctrl/core.c (ffffffff8167a5ec)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff8167bc7c)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff8167c9f3)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167e4bb)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81685549)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
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
In drivers/pinctrl/core.c (ffffffff81795c21)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81797453)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff817982f8)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8179a0c3)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a1d70)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
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
In drivers/pinctrl/core.c (ffffffff818aaf2e)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff818acec3)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff818ae048)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818b06c0)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b8f32)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
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
In drivers/pinctrl/core.c (ffffffff818ede12)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff818f0075)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff818f0f96)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f36c2)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fbfb2)
Location: drivers/pinctrl/core.h:239
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
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
In drivers/pinctrl/core.c (ffffffff819355e2)
Location: drivers/pinctrl/core.h:244
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_groups_show
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pinctrl_register_pins
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81937825)
Location: drivers/pinctrl/core.h:244
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff81938746)
Location: drivers/pinctrl/core.h:244
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8193aef2)
Location: drivers/pinctrl/core.h:244
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_set_mux
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81943ce2)
Location: drivers/pinctrl/core.h:244
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
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
In drivers/pinctrl/core.c (ffff80001068c450)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffff80001068ef88)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffff8000106901f0)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff80001069286c)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069bcbc)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_get_function
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
In drivers/pinctrl/core.c (c082e5ec)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (c0830da4)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (c0831f0c)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (c0834278)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
```
In drivers/pinctrl/pinctrl-single.c (c083e930)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_get_function
```
```
In drivers/pinctrl/uniphier/pinctrl-uniphier-core.c (c0857230)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_set
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_input_enable
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_pin_config_get
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_conf_get_drvctrl_data
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
In drivers/pinctrl/core.c (c0000000008252c0)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (c00000000082a1d4)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (c00000000082baf0)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (c00000000082efc4)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000832e48)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_get_function
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
In drivers/pinctrl/core.c (ffffffe00049876e)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffe00049ae42)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffe00049bd5a)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a02b2)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_get_function
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
In drivers/pinctrl/core.c (ffffffff815582af)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff8155a722)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff8155b6b3)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155bff5)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
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
In drivers/pinctrl/core.c (ffffffff8154876f)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff8154abe2)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff8154bb73)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
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
In drivers/pinctrl/core.c (ffffffff81553fef)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff81556462)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff815573f3)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81557d35)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
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
In drivers/pinctrl/core.c (ffffffff8156de7f)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_pins_show
  - drivers/pinctrl/core.c:pin_get_from_name
```
```
In drivers/pinctrl/pinmux.c (ffffffff815702f2)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_pins_show
  - drivers/pinctrl/pinmux.c:pinmux_disable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pinmux_enable_setting
  - drivers/pinctrl/pinmux.c:pin_free
  - drivers/pinctrl/pinmux.c:pin_request
  - drivers/pinctrl/pinmux.c:pinmux_can_be_used_for_gpio
```
```
In drivers/pinctrl/pinconf.c (ffffffff81571283)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf.c:pinconf_pins_show
  - drivers/pinctrl/pinconf.c:pinconf_show_setting
```
```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81571bc5)
Location: drivers/pinctrl/core.h:229
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
</details>
</li>
</ul>

## Differences
