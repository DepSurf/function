# Function: <code>devm_pinctrl_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81467470)
Location: drivers/pinctrl/core.c:1904
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff81467470-ffffffff814674f5: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81486760)
Location: drivers/pinctrl/core.c:1904
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81486760-ffffffff814867e5: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81490040)
Location: drivers/pinctrl/core.c:2202
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81490040-ffffffff814900d2: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cc200)
Location: drivers/pinctrl/core.c:2211
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff814cc200-ffffffff814cc292: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fd1b0)
Location: drivers/pinctrl/core.c:2160
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff814fd1b0-ffffffff814fd241: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81511c10)
Location: drivers/pinctrl/core.c:2188
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81511c10-ffffffff81511ca1: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815401d0)
Location: drivers/pinctrl/core.c:2177
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815401d0-ffffffff81540255: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81561090)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81561090-ffffffff81561115: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816038e0)
Location: drivers/pinctrl/core.c:2201
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff816038e0-ffffffff81603992: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816287f0)
Location: drivers/pinctrl/core.c:2224
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff816287f0-ffffffff816288a2: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160c2d0)
Location: drivers/pinctrl/core.c:2248
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff8160c2d0-ffffffff8160c382: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8167afd0)
Location: drivers/pinctrl/core.c:2250
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff8167afd0-ffffffff8167b089: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff817966d0)
Location: drivers/pinctrl/core.c:2250
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff817966d0-ffffffff81796795: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818abeb0)
Location: drivers/pinctrl/core.c:2249
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff818abeb0-ffffffff818abf75: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818eedf0)
Location: drivers/pinctrl/core.c:2258
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff818eedf0-ffffffff818eeeb5: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff819365b0)
Location: drivers/pinctrl/core.c:2272
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff819365b0-ffffffff81936675: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068dc70)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-bm1880.c:bm1880_pinctrl_probe
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_register
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_pinctrl_probe
  - drivers/pinctrl/bcm/pinctrl-iproc-gpio.c:iproc_gpio_probe
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
**Symbols:**

```
ffff80001068dc70-ffff80001068dd08: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082fcbc)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/meson/pinctrl-meson.c:meson_pinctrl_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra.c:tegra_pinctrl_probe
  - drivers/pinctrl/tegra/pinctrl-tegra-xusb.c:tegra_xusb_padctl_legacy_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_pinctrl_probe
  - drivers/pinctrl/berlin/berlin.c:berlin_pinctrl_probe_regmap
  - drivers/pinctrl/mvebu/pinctrl-mvebu.c:mvebu_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/samsung/pinctrl-samsung.c:samsung_pinctrl_probe
  - drivers/pinctrl/uniphier/pinctrl-uniphier-core.c:uniphier_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
```
**Symbols:**

```
c082fcbc-c082fd44: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000827f50)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
**Symbols:**

```
c000000000827f50-c000000000828028: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000499dc2)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-palmas.c:palmas_pinctrl_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
**Symbols:**

```
ffffffe000499dc2-ffffffe000499e48: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81559680)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff81559680-ffffffff81559705: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81549b40)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81549b40-ffffffff81549bc5: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815553c0)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815553c0-ffffffff81555445: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pinctrl_dev *devm_pinctrl_register(struct device *dev, struct pinctrl_desc *pctldesc, void *driver_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156f250)
Location: drivers/pinctrl/core.c:2204
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8156f250-ffffffff8156f2d5: devm_pinctrl_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
