# Function: <code>mtk_xt_get_gpio_n</code>

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
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int mtk_xt_get_gpio_n(void *data, long unsigned int eint_n, unsigned int *gpio_n, struct gpio_chip **gpio_chip);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b7f90)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:927
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (ffff8000106baa88)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:229
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_get_gpio_state
```
**Symbols:**

```
ffff8000106b7f90-ffff8000106b8030: mtk_xt_get_gpio_n (STB_LOCAL)
ffff8000106baa88-ffff8000106bab54: mtk_xt_get_gpio_n (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mtk_xt_get_gpio_n(void *data, long unsigned int eint_n, unsigned int *gpio_n, struct gpio_chip **gpio_chip);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c0858f64)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:927
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c (c085b750)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:229
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common-v2.c:mtk_xt_get_gpio_state
```
**Symbols:**

```
c0858f64-c0858fd8: mtk_xt_get_gpio_n (STB_LOCAL)
c085b750-c085b7f0: mtk_xt_get_gpio_n (STB_LOCAL)
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
