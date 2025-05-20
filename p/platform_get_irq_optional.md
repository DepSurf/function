# Function: <code>platform_get_irq_optional</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81701ba0)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
ffffffff81701ba0-ffffffff81701bb0: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817bc820)
Location: drivers/base/platform.c:158
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffffffff817bc820-ffffffff817bc9a3: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817d1720)
Location: drivers/base/platform.c:189
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff817d1720-ffffffff817d18a5: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817b5150)
Location: drivers/base/platform.c:189
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff817b5150-ffffffff817b52d5: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8183e440)
Location: drivers/base/platform.c:169
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8183e440-ffffffff8183e5c5: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81981290)
Location: drivers/base/platform.c:171
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81981290-ffffffff81981409: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81aeede0)
Location: drivers/base/platform.c:171
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81aeede0-ffffffff81aeef5b: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b3d1d0)
Location: drivers/base/platform.c:171
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81b3d1d0-ffffffff81b3d34b: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81b94d10)
Location: drivers/base/platform.c:171
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81b94d10-ffffffff81b94e85: platform_get_irq_optional (STB_GLOBAL)
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
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108edd98)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
```
**Symbols:**

```
ffff8000108edd98-ffff8000108eddcc: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dbc3c)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
  - drivers/net/ethernet/freescale/fec_ptp.c:fec_ptp_init
```
**Symbols:**

```
c09dbc3c-c09dbc58: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000986310)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
c000000000986310-c000000000986324: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580f0e)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
ffffffe000580f0e-ffffffe000580f40: platform_get_irq_optional (STB_GLOBAL)
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
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c72f0)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
ffffffff816c72f0-ffffffff816c7300: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a25f0)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
ffffffff816a25f0-ffffffff816a2600: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f5860)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
ffffffff816f5860-ffffffff816f5870: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int platform_get_irq_optional(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff817100f0)
Location: drivers/base/platform.c:194
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_plat_probe
```
**Symbols:**

```
ffffffff817100f0-ffffffff81710100: platform_get_irq_optional (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
