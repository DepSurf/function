# Function: <code>mtk_pmx_set_mode</code>

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
int mtk_pmx_set_mode(struct pinctrl_dev *pctldev, long unsigned int pin, long unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (ffff8000106b89e8)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:673
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_request_enable
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux
```
**Symbols:**

```
ffff8000106b89e8-ffff8000106b8af4: mtk_pmx_set_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mtk_pmx_set_mode(struct pinctrl_dev *pctldev, long unsigned int pin, long unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/mediatek/pinctrl-mtk-common.c (c08597dc)
Location: drivers/pinctrl/mediatek/pinctrl-mtk-common.c:673
Inline: False
Direct callers:
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_xt_set_gpio_as_eint
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_gpio_request_enable
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pmx_set_mux
```
**Symbols:**

```
c08597dc-c08598bc: mtk_pmx_set_mode (STB_LOCAL)
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
