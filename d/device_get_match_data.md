# Function: <code>device_get_match_data</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688e10)
Location: drivers/base/property.c:1481
Inline: False
```
**Symbols:**

```
ffffffff81688e10-ffffffff81688e44: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8b10)
Location: drivers/base/property.c:1004
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816a8b10-ffffffff816a8b48: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1bb0)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816e1bb0-ffffffff816e1be8: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705d60)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81705d60-ffffffff81705d98: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0380)
Location: drivers/base/property.c:1182
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817c0380-ffffffff817c03b8: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5240)
Location: drivers/base/property.c:1234
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817d5240-ffffffff817d5278: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8c80)
Location: drivers/base/property.c:1247
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817b8c80-ffffffff817b8cb8: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818428e0)
Location: drivers/base/property.c:1256
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff818428e0-ffffffff81842918: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986ae0)
Location: drivers/base/property.c:1203
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81986ae0-ffffffff81986b36: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const void *device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af5250)
Location: drivers/base/property.c:1217
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_spi_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81af5250-ffffffff81af52a6: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const void *device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43480)
Location: drivers/base/property.c:1278
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_spi_probe
  - drivers/mfd/palmas.c:palmas_i2c_probe
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_match_data
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b43480-ffffffff81b434d6: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const void *device_get_match_data(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9b350)
Location: drivers/base/property.c:1342
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_get_soc_data
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe_by_hid
  - drivers/pwm/pwm-lpss-platform.c:pwm_lpss_probe_platform
  - drivers/dma/lgm/lgm-dma.c:intel_ldma_probe
  - drivers/tty/serial/max310x.c:max310x_i2c_probe
  - drivers/tty/serial/max310x.c:max310x_spi_probe
  - drivers/usb/dwc2/params.c:dwc2_init_params
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_probe
  - drivers/i2c/i2c-core-base.c:i2c_get_match_data
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff81b9b350-ffffffff81b9b3a6: device_get_match_data (STB_GLOBAL)
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
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f28f0)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffff8000108f28f0-ffff8000108f2954: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df59c)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/soc/amlogic/meson-clk-measure.c:meson_msr_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
**Symbols:**

```
c09df59c-c09df5f4: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c5f0)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
c00000000098c5f0-c00000000098c678: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584460)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffe000584460-ffffffe0005844aa: device_get_match_data (STB_GLOBAL)
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
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb4b0)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff816cb4b0-ffffffff816cb4e8: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a67e0)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff816a67e0-ffffffff816a6818: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9a20)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff816f9a20-ffffffff816f9a58: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const void *device_get_match_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817142c0)
Location: drivers/base/property.c:1103
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe
```
**Symbols:**

```
ffffffff817142c0-ffffffff817142f8: device_get_match_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
