# Function: <code>mtk_pmx_gpio_set_direction</code>

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
int mtk_pmx_gpio_set_direction(struct pinctrl_dev *pctldev, struct pinctrl_gpio_range *range, unsigned int offset, bool input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b8760)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:68
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
```
**Symbols:**

```
ffff8000106b8760-ffff8000106b8860: mtk_pmx_gpio_set_direction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_pmx_gpio_set_direction(struct pinctrl_dev *pctldev, struct pinctrl_gpio_range *range, unsigned int offset, bool input);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c08595e4)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:68
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
```
**Symbols:**

```
c08595e4-c08596cc: mtk_pmx_gpio_set_direction (STB_LOCAL)
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
