# Function: <code>mtk_gpio_get</code>

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
int mtk_gpio_get(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b84e8)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:810
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_get_gpio_state
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba458)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:431
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc5f0)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:705
Inline: False
```
**Symbols:**

```
ffff8000106b84e8-ffff8000106b8588: mtk_gpio_get (STB_LOCAL)
ffff8000106ba458-ffff8000106ba4e4: mtk_gpio_get (STB_LOCAL)
ffff8000106bc5f0-ffff8000106bc67c: mtk_gpio_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mtk_gpio_get(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c08593c4)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:810
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_get_gpio_state
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b154)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:431
Inline: False
```
**Symbols:**

```
c08593c4-c0859460: mtk_gpio_get (STB_LOCAL)
c085b154-c085b1dc: mtk_gpio_get (STB_LOCAL)
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
