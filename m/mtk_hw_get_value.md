# Function: <code>mtk_hw_get_value</code>

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
int mtk_hw_get_value(struct mtk_pinctrl *hw, const struct mtk_pin_desc *desc, int field, int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106bafa0)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:194
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_get_gpio_state
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_get_direction
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_pinconf_get
```
**Symbols:**

```
ffff8000106bafa0-ffff8000106bb0e0: mtk_hw_get_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_hw_get_value(struct mtk_pinctrl *hw, const struct mtk_pin_desc *desc, int field, int *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085bbfc)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:194
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_pinconf_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_adv_pull_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_drive_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_get_rev1
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_pinconf_bias_disable_get
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_get_gpio_state
```
**Symbols:**

```
c085bbfc-c085bd10: mtk_hw_get_value (STB_GLOBAL)
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
