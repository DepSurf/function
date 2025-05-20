# Function: <code>mtk_gpio_set_config</code>

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
int mtk_gpio_set_config(struct gpio_chip *chip, unsigned int offset, long unsigned int config);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b8460)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:840
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba4e8)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:485
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc710)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:759
Inline: False
```
**Symbols:**

```
ffff8000106b8460-ffff8000106b84e4: mtk_gpio_set_config (STB_LOCAL)
ffff8000106ba4e8-ffff8000106ba56c: mtk_gpio_set_config (STB_LOCAL)
ffff8000106bc710-ffff8000106bc794: mtk_gpio_set_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int mtk_gpio_set_config(struct gpio_chip *chip, unsigned int offset, long unsigned int config);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c0859358)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:840
Inline: False
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b1dc)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:485
Inline: False
```
**Symbols:**

```
c0859358-c08593c4: mtk_gpio_set_config (STB_LOCAL)
c085b1dc-c085b24c: mtk_gpio_set_config (STB_LOCAL)
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
