# Function: <code>mtk_eint_set_debounce</code>

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
int mtk_eint_set_debounce(struct mtk_eint *eint, long unsigned int eint_num, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/mtk-eint.c (ffff8000106b7b90)
Location: drivers/pinctrl/mediatek/mtk-eint.c:390
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-paris.c:mtk_gpio_set_config
```
**Symbols:**

```
ffff8000106b7b90-ffff8000106b7d54: mtk_eint_set_debounce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_eint_set_debounce(struct mtk_eint *eint, long unsigned int eint_num, unsigned int debounce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/mtk-eint.c (c0858b04)
Location: drivers/pinctrl/mediatek/mtk-eint.c:390
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_gpio_set_config
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_gpio_set_config
```
**Symbols:**

```
c0858b04-c0858cb0: mtk_eint_set_debounce (STB_GLOBAL)
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
