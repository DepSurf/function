# Function: <code>mtk_gpio_set</code>

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
void mtk_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b8348)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:92
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_direction_output
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (ffff8000106ba3f8)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:446
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_direction_output
```
```
In drivers/pinctrl/mediatek/pinctrl-paris.c (ffff8000106bc590)
Location: drivers/pinctrl/mediatek/pinctrl-paris.c:720
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_direction_output
```
**Symbols:**

```
ffff8000106b8348-ffff8000106b83fc: mtk_gpio_set (STB_LOCAL)
ffff8000106ba3f8-ffff8000106ba454: mtk_gpio_set (STB_LOCAL)
ffff8000106bc590-ffff8000106bc5ec: mtk_gpio_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void mtk_gpio_set(struct gpio_chip *chip, unsigned int offset, int value);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c0859290)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:92
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_direction_output
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pconf_group_set
```
```
In drivers/pinctrl/mediatek/pinctrl-moore.c (c085b110)
Location: drivers/pinctrl/mediatek/pinctrl-moore.c:446
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_direction_output
```
**Symbols:**

```
c0859290-c085930c: mtk_gpio_set (STB_LOCAL)
c085b110-c085b154: mtk_gpio_set (STB_LOCAL)
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
