# Function: <code>mtk_hw_set_value</code>

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
int mtk_hw_set_value(struct mtk_pinctrl *hw, const struct mtk_pin_desc *desc, int field, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bad88)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:175
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_set_direction
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_request_enable
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pmx_set_mux
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinmux_gpio_set_direction
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinmux_gpio_request_enable
```
**Symbols:**

```
ffff8000106bad88-ffff8000106baec8: mtk_hw_set_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_hw_set_value(struct mtk_pinctrl *hw, const struct mtk_pin_desc *desc, int field, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085b9f8)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:175
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_set
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_set_direction
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_gpio_request_enable
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinmux_set_mux
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_set_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
```
**Symbols:**

```
c085b9f8-c085bb20: mtk_hw_set_value (STB_GLOBAL)
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
