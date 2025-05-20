# Function: <code>sh_pfc_get_pin_index</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int sh_pfc_get_pin_index(struct sh_pfc *pfc, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afb30)
Location: drivers/pinctrl/sh-pfc/core.c:110
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_validate
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
```
**Symbols:**

```
ffff8000106afb30-ffff8000106afbc0: sh_pfc_get_pin_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sh_pfc_get_pin_index(struct sh_pfc *pfc, unsigned int pin);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/sh-pfc/core.c (c0853540)
Location: drivers/pinctrl/sh-pfc/core.c:110
Inline: False
Direct callers:
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_pinconf_validate
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_set_direction
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_disable_free
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_gpio_request_enable
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
  - drivers/pinctrl/sh-pfc/pinctrl.c:sh_pfc_func_set_mux
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_get
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_set_value
  - drivers/pinctrl/sh-pfc/gpio.c:gpio_pin_request
```
**Symbols:**

```
c0853540-c08535c0: sh_pfc_get_pin_index (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<b>Arch</b>
<ul>
</ul>
